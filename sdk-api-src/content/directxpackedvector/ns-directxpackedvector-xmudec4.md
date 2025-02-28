---
UID: NS:directxpackedvector.XMUDEC4
title: XMUDEC4 (directxpackedvector.h)
description: A 4D vector with x-,y-, and z- components represented as 10 bit unsigned integer values, and the w-component as a 2 bit unsigned integer value.
old-location: dxmath\xmudec4.htm
tech.root: dxmath
ms.assetid: T:Microsoft.directx_sdk.reference.XMUDEC4
ms.date: 12/05/2018
ms.keywords: XMUDEC4, XMUDEC4 structure [DirectX Math Support APIs], directxpackedvector/XMUDEC4, dxmath.xmudec4
ms.topic: struct
f1_keywords:
- directxpackedvector/XMUDEC4
dev_langs:
- c++
req.header: directxpackedvector.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
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
- DirectXPackedVector.h
api_name:
- XMUDEC4
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMUDEC4 structure


## -description


A 4D vector with x-,y-, and z- components represented as 10 bit unsigned integer values, and the
	w-component as a 2 bit unsigned integer value.
    

For a list of additional functionality such as constructors and operators that are available
	using <code>XMUDEC4</code> when you are programming in C++, see <a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xmudec4-extensions">XMUDEC4 Extensions</a>.
<div class="alert"><b>Note</b>  See <a href="https://docs.microsoft.com/windows/desktop/dxmath/pg-xnamath-internals">DirectXMath Library Type
	Equivalences</a> for information about equivalent <a href="https://docs.microsoft.com/windows/desktop/direct3d9/d3ddecltype">D3DDECLTYPE</a>, <a href="https://docs.microsoft.com/windows/desktop/direct3d9/d3dformat">D3DFORMAT</a>, and <a href="https://docs.microsoft.com/windows/desktop/api/dxgiformat/ne-dxgiformat-dxgi_format">DXGI_FORMAT</a> objects.
    </div><div> </div>

## -struct-fields




### -field x

Unsigned integer value in the range [0, 1023] describing the
			    x-coordinate of the vector.
			


### -field y

Unsigned integer value in the range [0, 1023] describing the
			    y-coordinate of the vector.
			


### -field z

Unsigned integer value in the range [0, 1023] describing the
			    z-coordinate of the vector.
			


### -field w

Unsigned integer value in the range [0, 3] describing the w-coordinate
			    of the vector.
			


### -field v

Unsigned 32-bit integer representing the 4D vector.
		    


### -field XMUDEC4

TBD 


### -field operator uint32_t

TBD 


### -field operator=

TBD 




## -remarks



<code>XMUDEC4</code> can be loaded into instances of <a href="https://docs.microsoft.com/windows/desktop/dxmath/xmvector-data-type">XMVECTOR</a> by using
	    <a href="https://docs.microsoft.com/en-us/windows/desktop/api/directxpackedvector/nf-directxpackedvector-xmloadudec4">XMLoadUDec4</a>.
	

Instances of <code>XMVECTOR</code> can be stored into an instance of <code>XMUDEC4</code> with <a href="https://docs.microsoft.com/windows/desktop/api/directxpackedvector/nf-directxpackedvector-xmstoreudec4">XMStoreUDec4</a>.
	

<b>Namespace:</b> Use DirectX::PackedVector

<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-structures">DirectXMath Library Structures</a>



<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xmudec4-extensions">XMUDEC4 Extensions</a>
 

 

