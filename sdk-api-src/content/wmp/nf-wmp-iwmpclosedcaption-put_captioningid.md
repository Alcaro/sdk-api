---
UID: NF:wmp.IWMPClosedCaption.put_captioningId
title: IWMPClosedCaption::put_captioningId (wmp.h)
description: The put_captioningId method specifies the name of the element displaying the captioning.
old-location: wmp\iwmpclosedcaption_put_captioningid.htm
tech.root: WMP
ms.assetid: 46736a28-e05d-404c-8bad-a51ac58435f0
ms.date: 12/05/2018
ms.keywords: IWMPClosedCaption interface [Windows Media Player],put_captioningId method, IWMPClosedCaption.put_captioningId, IWMPClosedCaption::put_captioningId, IWMPClosedCaptionput_captioningId, put_captioningId, put_captioningId method [Windows Media Player], put_captioningId method [Windows Media Player],IWMPClosedCaption interface, wmp.iwmpclosedcaption_put_captioningid, wmp/IWMPClosedCaption::put_captioningId
ms.topic: method
f1_keywords:
- wmp/IWMPClosedCaption.put_captioningId
dev_langs:
- c++
req.header: wmp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Media Player 9 Series or later.
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
req.dll: Wmp.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- wmp.dll
api_name:
- IWMPClosedCaption.put_captioningId
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMPClosedCaption::put_captioningId


## -description



The <b>put_captioningId</b> method specifies the name of the element displaying the captioning.




## -parameters




### -param bstrCaptioningID [in]

<b>BSTR</b> containing the captioning ID.


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>
 




## -remarks



The element name specified can be any HTML element in the webpage as long as it supports the <b>innerHTML</b> attribute. If the webpage contains multiple frames, the element name can only refer to an element in the same frame as the Windows Media Player control.

<b>Windows Media Player 10 Mobile: </b>This method always returns E_INVALIDARG.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/WMP/adding-closed-captions-to-digital-media">Adding Closed Captions to Digital Media</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wmp/nn-wmp-iwmpclosedcaption">IWMPClosedCaption Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wmp/nf-wmp-iwmpclosedcaption-get_captioningid">IWMPClosedCaption::get_captioningId</a>
 

 

