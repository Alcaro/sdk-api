---
UID: NF:evr.IMFVideoMixerControl2.GetMixingPrefs
title: IMFVideoMixerControl2::GetMixingPrefs (evr.h)
description: Gets the current preferences for video deinterlacing.
old-location: mf\imfvideomixercontrol2_getmixingprefs.htm
tech.root: medfound
ms.assetid: 4ec03db2-9e7f-4a11-8d69-7654391a33d8
ms.date: 12/05/2018
ms.keywords: GetMixingPrefs, GetMixingPrefs method [Media Foundation], GetMixingPrefs method [Media Foundation],IMFVideoMixerControl2 interface, IMFVideoMixerControl2 interface [Media Foundation],GetMixingPrefs method, IMFVideoMixerControl2.GetMixingPrefs, IMFVideoMixerControl2::GetMixingPrefs, evr/IMFVideoMixerControl2::GetMixingPrefs, mf.imfvideomixercontrol2_getmixingprefs
ms.topic: method
f1_keywords:
- evr/IMFVideoMixerControl2.GetMixingPrefs
dev_langs:
- c++
req.header: evr.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
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
- COM
api_location:
- evr.h
api_name:
- IMFVideoMixerControl2.GetMixingPrefs
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMFVideoMixerControl2::GetMixingPrefs


## -description


Gets the current preferences for video deinterlacing.


## -parameters




### -param pdwMixFlags [out]

Receives a bitwise <b>OR</b> of zero or more flags from the <a href="https://docs.microsoft.com/windows/desktop/api/evr/ne-evr-mfvideomixprefs">MFVideoMixPrefs</a> enumeration.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/evr/nn-evr-imfvideomixercontrol2">IMFVideoMixerControl2</a>



<a href="https://docs.microsoft.com/windows/desktop/medfound/video-quality-management">Video Quality Management</a>
 

 

