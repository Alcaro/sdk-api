---
UID: NF:directxcollision.Intersects
title: Intersects(XMVECTOR, XMVECTOR, XMVECTOR, XMVECTOR, XMVECTOR, float&) method
description: Test whether a triangle intersects with a ray.
ms.date: 04/22/19
ms.keywords: Intersects
ms.topic: language-reference
f1_keywords:
- directxcollision/Intersects
dev_langs:
- c++
targetos: Windows
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: directxcollision.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
- apiref
api_type:
- 
api_location:
- directxcollision.h
api_name:
- Intersects
---

# Intersects(XMVECTOR, XMVECTOR, XMVECTOR, XMVECTOR, XMVECTOR, float&) method

## -description

Test whether a triangle intersects with a ray.

## -parameters

### -param Origin

The origin of the ray.

### -param Direction

The direction of the ray.

### -param V0

A vector defining the triangle.

### -param V1

A vector defining the triangle.

### -param V2

A vector defining the triangle.

### -param Dist

The distance along the ray where the intersection occurs.

## -returns

A boolean value indicating whether the triangle intersects with the ray.

## -remarks

**Note**  `TriangleTests::Intersects` is new for DirectXMath. This functionality is not available in XNAMath 2.x.
Similar functionality for XNAMath can be found in the DirectX SDK Collision sample.

### Platform Requirements

Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8.
Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.

## -see-also

[DirectXMath Triangle Test Functions](/windows/desktop/dxmath/ovw-xnamath-triangletests)
