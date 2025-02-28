---
UID: NF:wincodec.IWICDevelopRaw.GetRenderMode
title: IWICDevelopRaw::GetRenderMode (wincodec.h)
description: Gets the current WICRawRenderMode.
old-location: wic\_wic_codec_iwicdevelopraw_getrendermode.htm
tech.root: wic
ms.assetid: d8cf4508-6a2c-4d02-b98f-0455a3dc966c
ms.date: 12/05/2018
ms.keywords: GetRenderMode, GetRenderMode method [Windows Imaging Component], GetRenderMode method [Windows Imaging Component],IWICDevelopRaw interface, IWICDevelopRaw interface [Windows Imaging Component],GetRenderMode method, IWICDevelopRaw.GetRenderMode, IWICDevelopRaw::GetRenderMode, _wic_codec_iwicdevelopraw_getrendermode, wic._wic_codec_iwicdevelopraw_getrendermode, wincodec/IWICDevelopRaw::GetRenderMode
ms.topic: method
f1_keywords:
- wincodec/IWICDevelopRaw.GetRenderMode
dev_langs:
- c++
req.header: wincodec.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Wincodec.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Windowscodecs.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Windowscodecs.lib
- Windowscodecs.dll
api_name:
- IWICDevelopRaw.GetRenderMode
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWICDevelopRaw::GetRenderMode


## -description


Gets the current <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/ne-wincodec-wicrawrendermode">WICRawRenderMode</a>.


## -parameters




### -param pRenderMode [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/wincodec/ne-wincodec-wicrawrendermode">WICRawRenderMode</a>*</b>

A pointer that receives the current <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/ne-wincodec-wicrawrendermode">WICRawRenderMode</a>.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



