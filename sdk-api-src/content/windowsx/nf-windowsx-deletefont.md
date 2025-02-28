---
UID: NF:windowsx.DeleteFont
title: DeleteFont macro (windowsx.h)
description: The DeleteFont macro deletes a font object, freeing all system resources associated with the font object.
old-location: gdi\deletefont.htm
tech.root: gdi
ms.assetid: 5cb6c667-3c8b-41cf-b2b7-9e1e89729da7
ms.date: 12/05/2018
ms.keywords: DeleteFont, DeleteFont macro [Windows GDI], _win32_DeleteFont, gdi.deletefont, windowsx/DeleteFont
ms.topic: macro
f1_keywords:
- windowsx/DeleteFont
dev_langs:
- c++
req.header: windowsx.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Windowsx.h
api_name:
- DeleteFont
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# DeleteFont macro


## -description



The <b>DeleteFont</b> macro deletes a font object, freeing all system resources associated with the font object.




## -parameters




### -param hfont

A handle to the font object.


## -remarks



After the font object is deleted, the specified handle is no longer valid.

The <b>DeleteFont</b> macro is equivalent to calling <a href="https://docs.microsoft.com/windows/desktop/api/wingdi/nf-wingdi-deleteobject">DeleteObject</a> as follows:

<pre class="syntax" xml:space="preserve"><code>
   DeleteObject((HGDIOBJ)(HFONT)(hfont))
</code></pre>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wingdi/nf-wingdi-deleteobject">DeleteObject</a>



<a href="https://docs.microsoft.com/windows/desktop/api/windowsx/nf-windowsx-selectfont">SelectFont</a>
 

 

