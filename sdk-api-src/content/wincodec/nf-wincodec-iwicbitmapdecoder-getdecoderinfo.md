---
UID: NF:wincodec.IWICBitmapDecoder.GetDecoderInfo
title: IWICBitmapDecoder::GetDecoderInfo (wincodec.h)
description: Retrieves an IWICBitmapDecoderInfo for the image.
old-location: wic\_wic_codec_iwicbitmapdecoder_getdecoderinfo.htm
tech.root: wic
ms.assetid: 45bcdcda-c45a-4646-a511-3a16d3fda262
ms.date: 12/05/2018
ms.keywords: GetDecoderInfo, GetDecoderInfo method [Windows Imaging Component], GetDecoderInfo method [Windows Imaging Component],IWICBitmapDecoder interface, IWICBitmapDecoder interface [Windows Imaging Component],GetDecoderInfo method, IWICBitmapDecoder.GetDecoderInfo, IWICBitmapDecoder::GetDecoderInfo, _wic_codec_iwicbitmapdecoder_getdecoderinfo, wic._wic_codec_iwicbitmapdecoder_getdecoderinfo, wincodec/IWICBitmapDecoder::GetDecoderInfo
ms.topic: method
f1_keywords:
- wincodec/IWICBitmapDecoder.GetDecoderInfo
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
req.dll: Windowscodecs.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Windowscodecs.dll
api_name:
- IWICBitmapDecoder.GetDecoderInfo
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWICBitmapDecoder::GetDecoderInfo


## -description


Retrieves an <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicbitmapdecoderinfo">IWICBitmapDecoderInfo</a> for the image.


## -parameters




### -param ppIDecoderInfo [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicbitmapdecoderinfo">IWICBitmapDecoderInfo</a>**</b>

A pointer that receives a pointer to an <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicbitmapdecoderinfo">IWICBitmapDecoderInfo</a>.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



