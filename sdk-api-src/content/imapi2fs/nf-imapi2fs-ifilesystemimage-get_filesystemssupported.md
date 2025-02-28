---
UID: NF:imapi2fs.IFileSystemImage.get_FileSystemsSupported
title: IFileSystemImage::get_FileSystemsSupported (imapi2fs.h)
description: Retrieves the list of file system types that a client can use to build a file system image.
old-location: imapi\ifilesystemimage_get_filesystemssupported.htm
tech.root: imapi
ms.assetid: 73bf563b-ad8f-4afe-95c6-3bac3c4dadba
ms.date: 12/05/2018
ms.keywords: IFileSystemImage interface [IMAPI],get_FileSystemsSupported method, IFileSystemImage.get_FileSystemsSupported, IFileSystemImage::get_FileSystemsSupported, get_FileSystemsSupported, get_FileSystemsSupported method [IMAPI], get_FileSystemsSupported method [IMAPI],IFileSystemImage interface, imapi.ifilesystemimage_get_filesystemssupported, imapi2fs/IFileSystemImage::get_FileSystemsSupported
ms.topic: method
f1_keywords:
- imapi2fs/IFileSystemImage.get_FileSystemsSupported
dev_langs:
- c++
req.header: imapi2fs.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Imapi2fs.idl
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
- imapi2fs.h
api_name:
- IFileSystemImage.get_FileSystemsSupported
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFileSystemImage::get_FileSystemsSupported


## -description


Retrieves the list of file system types that a client can use to build a file system image.


## -parameters




### -param pVal [out]

One or more file system types that a client can use to build a file system image. For possible values, see the <a href="https://docs.microsoft.com/windows/desktop/api/imapi2fs/ne-imapi2fs-fsifilesystems">FsiFileSystems</a> enumeration type.


## -returns



S_OK is returned on success, but other success codes may be returned as a result of implementation. The following error codes are commonly returned on operation failure, but do not represent the only possible error values:

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
Pointer is not valid.

Value: 0x80004003

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/imapi2fs/nn-imapi2fs-ifilesystemimage">IFileSystemImage</a>



<a href="https://docs.microsoft.com/windows/desktop/api/imapi2fs/nf-imapi2fs-ifilesystemimage-getdefaultfilesystemforimport">IFileSystemImage::GetDefaultFileSystemForImport</a>



<a href="https://docs.microsoft.com/windows/desktop/api/imapi2fs/nf-imapi2fs-ifilesystemimage-get_filesystemstocreate">IFileSystemImage::get_FileSystemsToCreate</a>



<a href="https://docs.microsoft.com/windows/desktop/api/imapi2fs/nf-imapi2fs-ifilesystemimage-put_filesystemstocreate">IFileSystemImage::put_FileSystemsToCreate</a>
 

 

