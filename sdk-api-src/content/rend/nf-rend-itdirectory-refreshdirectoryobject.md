---
UID: NF:rend.ITDirectory.RefreshDirectoryObject
title: ITDirectory::RefreshDirectoryObject (rend.h)
description: The RefreshDirectoryObject method refreshes the time to live (TTL) for an object on the server. Only applies to dynamic servers.
old-location: tapi3\itdirectory_refreshdirectoryobject.htm
tech.root: Tapi
ms.assetid: 85a94960-5d4e-4b23-a3ed-65743a60ee87
ms.date: 12/05/2018
ms.keywords: ITDirectory interface [TAPI 2.2],RefreshDirectoryObject method, ITDirectory.RefreshDirectoryObject, ITDirectory::RefreshDirectoryObject, RefreshDirectoryObject, RefreshDirectoryObject method [TAPI 2.2], RefreshDirectoryObject method [TAPI 2.2],ITDirectory interface, _tapi3_itdirectory_refreshdirectoryobject, rend/ITDirectory::RefreshDirectoryObject, tapi3.itdirectory_refreshdirectoryobject
ms.topic: method
f1_keywords:
- rend/ITDirectory.RefreshDirectoryObject
dev_langs:
- c++
req.header: rend.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Rend.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: Rend.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Rend.dll
api_name:
- ITDirectory.RefreshDirectoryObject
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITDirectory::RefreshDirectoryObject


## -description


<p class="CCE_Message">[Rendezvous IP Telephony Conferencing controls and interfaces are not available for use in Windows Vista, Windows Server 2008, and subsequent versions of the operating system. The RTC Client API
provides similar functionality.]

The 
<b>RefreshDirectoryObject</b> method refreshes the 
<a href="/windows/win32/tapi/t-tapgloss">time to live</a> (TTL) for an object on the server. Only applies to dynamic servers.


## -parameters




### -param pDirectoryObject [in]

Pointer to 
<a href="https://docs.microsoft.com/windows/desktop/api/rend/nn-rend-itdirectoryobject">ITDirectoryObject</a> to be refreshed.


## -returns



This method can return one of these values.

<table>
<tr>
<th>Value</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
The <i>pDirectoryObject</i> parameter is not a valid pointer.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>RND_NOT_CONNECTED</b></dt>
</dl>
</td>
<td width="60%">
The 
<a href="https://docs.microsoft.com/windows/desktop/api/rend/nf-rend-itdirectory-connect">ITDirectory::Connect</a> method has not been invoked or did not succeed.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/rend/nn-rend-itdirectory">ITDirectory</a>
 

 

