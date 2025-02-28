---
UID: NN:uiautomationcore.ITableItemProvider
title: ITableItemProvider (uiautomationcore.h)
description: Provides access to child controls of containers that implement ITableProvider.
old-location: winauto\uiauto_ITableItemProvider.htm
tech.root: WinAuto
ms.assetid: 73cba491-1aa6-4bd7-bcd6-95b5d85c9457
ms.date: 12/05/2018
ms.keywords: ITableItemProvider, ITableItemProvider interface [Windows Accessibility], ITableItemProvider interface [Windows Accessibility],described, uiauto.uiauto_ITableItemProvider, uiauto_ITableItemProvider, uiautomationcore/ITableItemProvider, winauto.uiauto_ITableItemProvider
ms.topic: interface
f1_keywords:
- uiautomationcore/ITableItemProvider
dev_langs:
- c++
req.header: uiautomationcore.h
req.include-header: UIAutomation.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2003 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: UIAutomationCore.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: UIAutomationCore.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- UIAutomationCore.dll
api_name:
- ITableItemProvider
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITableItemProvider interface


## -description


Provides access 
        to child controls of containers that implement <a href="https://docs.microsoft.com/windows/desktop/api/uiautomationcore/nn-uiautomationcore-itableprovider">ITableProvider</a>. 
        


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">ITableItemProvider</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>ITableItemProvider</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>ITableItemProvider</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/uiautomationcore/nf-uiautomationcore-itableitemprovider-getcolumnheaderitems">GetColumnHeaderItems</a>
</td>
<td align="left" width="63%">
Retrieves a collection of UI Automation provider 
        representing all the column headers associated with a table item or cell.
        

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/uiautomationcore/nf-uiautomationcore-itableitemprovider-getrowheaderitems">GetRowHeaderItems</a>
</td>
<td align="left" width="63%">
Retrieves a collection of UI Automation provider 
        representing all the row headers associated with a table item or cell.
        

</td>
</tr>
</table> 


## -remarks



This control pattern is analogous to <a href="https://docs.microsoft.com/windows/desktop/api/uiautomationcore/nn-uiautomationcore-igriditemprovider">IGridItemProvider</a> with 
            the distinction that any control implementing <b>ITableItemProvider</b> 
            must expose the relationship between the individual cell and its row and column information.
            

Access to individual cell functionality is provided by the concurrent implementation 
            of <a href="https://docs.microsoft.com/windows/desktop/api/uiautomationcore/nn-uiautomationcore-igriditemprovider">IGridItemProvider</a>. 
            

Implemented on a UI Automation provider that must 
            support the <a href="https://docs.microsoft.com/windows/desktop/WinAuto/uiauto-implementingtableitem">TableItem</a> control pattern.
            




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/WinAuto/uiauto-providersoverview">UI Automation Providers Overview</a>
 

 

