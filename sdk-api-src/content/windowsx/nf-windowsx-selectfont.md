---
UID: NF:windowsx.SelectFont
title: SelectFont macro (windowsx.h)
description: The SelectFont macro selects a font object into the specified device context (DC). The new font object replaces the previous font object.
old-location: gdi\selectfont.htm
tech.root: gdi
ms.assetid: e7c145aa-566d-4754-a4dd-a5e71e188258
ms.date: 12/05/2018
ms.keywords: SelectFont, SelectFont macro [Windows GDI], _win32_SelectFont, gdi.selectfont, windowsx/SelectFont
ms.topic: macro
f1_keywords:
- windowsx/SelectFont
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
- SelectFont
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# SelectFont macro


## -description



The <b>SelectFont</b> macro selects a font object into the specified device context (DC). The new font object replaces the previous font object.




## -parameters




### -param hdc

A handle to the DC.


### -param hfont

A handle to the font object to be selected. The font object must have been created using either <a href="https://docs.microsoft.com/windows/desktop/api/wingdi/nf-wingdi-createfonta">CreateFont</a> or <a href="https://docs.microsoft.com/windows/desktop/api/wingdi/nf-wingdi-createfontindirecta">CreateFontIndirect</a>.


## -remarks



After an application has finished drawing with the new font object, it should always replace a new font object with the original font object.

The <b>SelectFont</b> macro is equivalent to calling <a href="https://docs.microsoft.com/windows/desktop/api/wingdi/nf-wingdi-selectobject">SelectObject</a> as follows:

<pre class="syntax" xml:space="preserve"><code>
((HFONT) SelectObject((hdc), (HGDIOBJ)(HFONT)(hfont)))
</code></pre>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/windowsx/nf-windowsx-deletefont">DeleteFont</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wingdi/nf-wingdi-selectobject">SelectObject</a>
 

 

