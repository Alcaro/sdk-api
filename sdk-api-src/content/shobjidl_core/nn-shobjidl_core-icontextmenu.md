---
UID: NN:shobjidl_core.IContextMenu
title: IContextMenu (shobjidl_core.h)
description: Exposes methods that either create or merge a shortcut menu associated with a Shell object.
old-location: shell\IContextMenu.htm
tech.root: shell
ms.assetid: 6ea0b8f9-4a05-4a4b-adc5-d540eb3287ee
ms.date: 12/05/2018
ms.keywords: IContextMenu, IContextMenu interface [Windows Shell], IContextMenu interface [Windows Shell],described, _win32_IContextMenu, _win32_icontextmenu_cpp, shell.IContextMenu, shobjidl_core/IContextMenu
ms.topic: interface
f1_keywords:
- shobjidl_core/IContextMenu
dev_langs:
- c++
req.header: shobjidl_core.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl_core.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: Shell32.dll (version 4.0 or later)
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Shell32.dll
api_name:
- IContextMenu
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IContextMenu interface


## -description


Exposes methods that either create or merge a shortcut menu associated with a Shell object.


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IContextMenu</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IContextMenu</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IContextMenu</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-icontextmenu-getcommandstring">GetCommandString</a>
</td>
<td align="left" width="63%">
Gets information about a shortcut menu command, including the help string and the language-independent, or <i>canonical</i>, name for the command.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-icontextmenu-invokecommand">InvokeCommand</a>
</td>
<td align="left" width="63%">
Carries out the command associated with a shortcut menu item.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-icontextmenu-querycontextmenu">QueryContextMenu</a>
</td>
<td align="left" width="63%">
Adds commands to a shortcut menu.

</td>
</tr>
</table> 


## -remarks



<h3><a id="When_to_Implement"></a><a id="when_to_implement"></a><a id="WHEN_TO_IMPLEMENT"></a>When to Implement</h3>
Implement <b>IContextMenu</b> in the following situations.
				

<ul>
<li>
<a href="https://docs.microsoft.com/windows/desktop/shell/handlers">Shell extension handlers</a> implement this interface to dynamically add items to a Shell object's shortcut menu.</li>
<li>
<a href="https://docs.microsoft.com/windows/desktop/shell/nse-works">Namespace extensions</a> implement this interface to specify their object's shortcut menus.</li>
</ul>
For a detailed discussion of how to implement <b>IContextMenu</b>, see <a href="https://docs.microsoft.com/windows/desktop/shell/context-menu-handlers">Creating Context Menu Handlers</a>.

<h3><a id="When_to_Use"></a><a id="when_to_use"></a><a id="WHEN_TO_USE"></a>When to Use</h3>
Applications use <b>IContextMenu</b> to retrieve information about the items in an object's shortcut menu and to invoke the associated commands. To retrieve an object's <b>IContextMenu</b> interface, an application must call the object's <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellfolder-getuiobjectof">IShellFolder::GetUIObjectOf</a> method.

Shell extension handlers that export this interface must also export <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ishellextinit">IShellExtInit</a>. For details, see <a href="https://docs.microsoft.com/windows/desktop/shell/handlers">Creating Shell Extension Handlers</a>.

<div class="alert"><b>Note</b>  <b>Windows Vista and later:</b> Prior to Windows Vista this interface was declared in Shlobj.h.</div>
<div> </div>


