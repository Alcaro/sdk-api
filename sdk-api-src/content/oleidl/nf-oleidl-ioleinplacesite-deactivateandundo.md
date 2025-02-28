---
UID: NF:oleidl.IOleInPlaceSite.DeactivateAndUndo
title: IOleInPlaceSite::DeactivateAndUndo (oleidl.h)
description: Deactivates the object, ends the in-place session, and reverts to the container's saved undo state.
old-location: com\ioleinplacesite_deactivateandundo.htm
tech.root: com
ms.assetid: 59229720-cd3b-45d5-90c4-391acb124f4d
ms.date: 12/05/2018
ms.keywords: DeactivateAndUndo, DeactivateAndUndo method [COM], DeactivateAndUndo method [COM],IOleInPlaceSite interface, IOleInPlaceSite interface [COM],DeactivateAndUndo method, IOleInPlaceSite.DeactivateAndUndo, IOleInPlaceSite::DeactivateAndUndo, IOleInPlaceSiteWindowless.DeactivateAndUndo, _ole_ioleinplacesite_deactivateandundo, com.ioleinplacesite_deactivateandundo, oleidl/IOleInPlaceSite::DeactivateAndUndo
ms.topic: method
f1_keywords:
- oleidl/IOleInPlaceSite.DeactivateAndUndo
dev_langs:
- c++
req.header: oleidl.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: OleIdl.Idl
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
- OleIdl.h
- browsewm.dll
api_name:
- IOleInPlaceSite.DeactivateAndUndo
- IOleInPlaceSiteWindowless.DeactivateAndUndo
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IOleInPlaceSite::DeactivateAndUndo


## -description


Deactivates the object, ends the in-place session, and reverts to the container's saved undo state.


## -parameters






## -returns



This method returns S_OK on success. Other possible return values include the following.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_UNEXPECTED</b></dt>
</dl>
</td>
<td width="60%">
An unexpected error has occurred.

</td>
</tr>
</table>
 




## -remarks



<h3><a id="Notes_to_Callers"></a><a id="notes_to_callers"></a><a id="NOTES_TO_CALLERS"></a>Notes to Callers</h3>
Called by the active object when the user invokes undo just after activating the object.

<h3><a id="Notes_to_Implementers"></a><a id="notes_to_implementers"></a><a id="NOTES_TO_IMPLEMENTERS"></a>Notes to Implementers</h3>
Upon completion of this call, the container should call <a href="https://docs.microsoft.com/windows/desktop/api/oleidl/nf-oleidl-ioleinplaceobject-uideactivate">IOleInPlaceObject::UIDeactivate</a> to remove the user interface for the object, activate itself, and undo.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/oleidl/nn-oleidl-ioleinplacesite">IOleInPlaceSite</a>
 

 

