---
UID: NF:directxpackedvector.XMStoreHalf4
title: XMStoreHalf4 function (directxpackedvector.h)
description: Stores an XMVECTOR in an XMHALF4.
old-location: dxmath\xmstorehalf4.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.storing.XMStoreHalf4(XMHALF4@,XMVECTOR)
ms.date: 12/05/2018
ms.keywords: DirectX::PackedVector.XMStoreHalf4, XMStoreHalf4, XMStoreHalf4 method [DirectX Math Support APIs], dxmath.xmstorehalf4
ms.topic: function
f1_keywords:
- directxpackedvector/XMStoreHalf4
dev_langs:
- c++
req.header: directxpackedvector.h
req.include-header: DirectXPackedVector.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: DirectX::PackedVector
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- directxpackedvector.inl
api_name:
- XMStoreHalf4
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMStoreHalf4 function


## -description


Stores an <a href="https://docs.microsoft.com/windows/desktop/dxmath/xmvector-data-type">XMVECTOR</a> in an <a href="https://docs.microsoft.com/windows/desktop/api/directxpackedvector/ns-directxpackedvector-xmhalf4">XMHALF4</a>.


## -parameters




### -param pDestination [out]

Address at which to store the data.


### -param V [in]

Vector containing the data to store.


## -returns



None.




## -remarks



This function takes a vector, converts the components into a half-precision format, and writes the results out to four half-precision floating-point values at the given address. The most significant component is written to the first two bytes of the address, the next most significant component is written to the next two bytes of the address, and so on.

The following pseudocode demonstrates the operation of the function.


```
pDestination->x = XMConvertFloatToHalf(V.x); // 2 bytes to address pDestination
pDestination->y = XMConvertFloatToHalf(V.y); // 2 bytes to address (uint8_t*)pDestination + 2
pDestination->z = XMConvertFloatToHalf(V.z); // 2 bytes to address (uint8_t*)pDestination + 4
pDestination->w = XMConvertFloatToHalf(V.w); // 2 bytes to address (uint8_t*)pDestination + 6
```


<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-storage">DirectXMath Library Vector Store Functions</a>
 

 

