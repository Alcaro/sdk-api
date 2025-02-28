---
UID: NF:processthreadsapi.GetThreadDescription
title: GetThreadDescription function (processthreadsapi.h)
description: Retrieves the description that was assigned to a thread by calling SetThreadDescription.
old-location: base\getthreaddescription.htm
tech.root: ProcThread
ms.assetid: 9CFF0A2D-2196-4AE0-8F77-229A8AB7A3E8
ms.date: 12/05/2018
ms.keywords: GetThreadDescription, GetThreadDescription function, base.getthreaddescription, processthreadsapi/GetThreadDescription
ms.topic: function
f1_keywords:
- processthreadsapi/GetThreadDescription
dev_langs:
- c++
req.header: processthreadsapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1607 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2016 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Kernel32.lib
req.dll: Kernel32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Kernel32.dll
- Kernelbase.dll
- Api-ms-win-core-processthreads-l1-1-3.dll
api_name:
- GetThreadDescription
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# GetThreadDescription function


## -description


Retrieves the description that was assigned to a thread by calling <a href="https://docs.microsoft.com/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreaddescription">SetThreadDescription</a>.


## -parameters




### -param hThread [in]

A handle to the thread for which to retrieve the description. The handle must have THREAD_QUERY_LIMITED_INFORMATION access.


### -param ppszThreadDescription [out]

A Unicode string that contains the description of the thread.


## -returns



If the function succeeds, the return value is the <b>HRESULT</b> that denotes a successful operation.
If the function fails, the return value is an <b>HRESULT</b> that denotes the error.





## -remarks



The description for a thread can change at any time. For example, a different thread can change the description of a thread of interest while you try to retrieve that description.

Thread descriptions do not need to be unique.

To free the memory for the thread description, call the <a href="https://docs.microsoft.com/windows/desktop/api/winbase/nf-winbase-localfree">LocalFree</a> method.


#### Examples

The following example gets the description for a thread,  prints the description, and then frees the memory for the description.


```cpp
HRESULT hr = GetThreadDescription(ThreadHandle, &data);
if (SUCCEEDED(hr))
{   
    wprintf(“%ls\m”, data);
    LocalFree(data);
}

```





## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/winbase/nf-winbase-localfree">LocalFree</a>



<a href="https://docs.microsoft.com/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreaddescription">SetThreadDescription</a>
 

 

