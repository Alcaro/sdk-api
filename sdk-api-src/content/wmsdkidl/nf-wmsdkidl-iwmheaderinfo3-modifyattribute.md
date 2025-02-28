---
UID: NF:wmsdkidl.IWMHeaderInfo3.ModifyAttribute
title: IWMHeaderInfo3::ModifyAttribute (wmsdkidl.h)
description: The ModifyAttribute method modifies the settings of an existing attribute.
old-location: wmformat\iwmheaderinfo3_modifyattribute.htm
tech.root: wmformat
ms.assetid: 503099e9-a1a9-406f-abc9-7c632d757cca
ms.date: 12/05/2018
ms.keywords: IWMHeaderInfo3 interface [windows Media Format],ModifyAttribute method, IWMHeaderInfo3.ModifyAttribute, IWMHeaderInfo3::ModifyAttribute, IWMHeaderInfo3ModifyAttribute, ModifyAttribute, ModifyAttribute method [windows Media Format], ModifyAttribute method [windows Media Format],IWMHeaderInfo3 interface, wmformat.iwmheaderinfo3_modifyattribute, wmsdkidl/IWMHeaderInfo3::ModifyAttribute
ms.topic: method
f1_keywords:
- wmsdkidl/IWMHeaderInfo3.ModifyAttribute
dev_langs:
- c++
req.header: wmsdkidl.h
req.include-header: Wmsdk.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only],Windows Media Format 9 Series SDK, or later versions of the SDK
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
req.lib: Wmvcore.lib; WMStubDRM.lib (if you use DRM)
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Wmvcore.lib
- Wmvcore.dll
- WMStubDRM.lib
- WMStubDRM.dll
api_name:
- IWMHeaderInfo3.ModifyAttribute
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMHeaderInfo3::ModifyAttribute


## -description



The <b>ModifyAttribute</b> method modifies the settings of an existing attribute.




## -parameters




### -param wStreamNum [in]

<b>WORD</b> containing the stream number to which the attribute applies. Pass zero for file-level attributes.


### -param wIndex [in]

<b>WORD</b> containing the index of the attribute to change.


### -param Type [in]

Type of data used for the new attribute value. For more information about the types of data supported, see <a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/ne-wmsdkidl-wmt_attr_datatype">WMT_ATTR_DATATYPE</a>.


### -param wLangIndex [in]

<b>WORD</b> containing the language index of the language to be associated with the new attribute. This is the index of the language in the language list for the file.


### -param pValue [in]

Pointer to an array of bytes containing the attribute value.


### -param dwLength [in]

<b>DWORD</b> containing the length of the attribute value, in bytes.


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
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
An illegal parameter combination, data type, or attribute name was used.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_NOTIMPL</b></dt>
</dl>
</td>
<td width="60%">
The method is not implemented on a reader object.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
A pointer is not valid.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>NS_E_ATTRIBUTE_READ_ONLY</b></dt>
</dl>
</td>
<td width="60%">
The attribute cannot be changed.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>NS_E_INVALID_REQUEST</b></dt>
</dl>
</td>
<td width="60%">
<i>wStreamNum</i> is not a valid stream number, or there is no attribute at <i>wIndex</i>.

</td>
</tr>
</table>
 




## -remarks



You can use 0xFFFF for the stream number to specify an attribute using its global index. Global index values range from 0 to one less than the count of attributes received from a call to <a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nf-wmsdkidl-iwmheaderinfo3-getattributecountex">IWMHeaderInfo3::GetAttributeCountEx</a> where the stream number was set to 0xFFFF.

When setting attributes for MP3 files, the metadata editor will automatically insert a byte-order mark in accordance with the Unicode specification. If you manually insert a byte-order mark, this method will not fail, but the value will then have two marks, which can cause problems when reading the attribute.

The objects of the Windows Media Format SDK perform type checking on some supported metadata attributes, but not all of them. You should ensure that any attributes you use are set using the data type specified in the <a href="https://docs.microsoft.com/windows/desktop/wmformat/attributes">Attributes</a> section of this documentation. Likewise, you cannot assume that an attribute set by another application will use the correct data type.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nn-wmsdkidl-iwmheaderinfo3">IWMHeaderInfo3 Interface</a>
 

 

