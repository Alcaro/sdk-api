---
UID: NF:mobsync.ISyncMgrRegister.GetHandlerRegistrationInfo
title: ISyncMgrRegister::GetHandlerRegistrationInfo (mobsync.h)
description: Called by the registered application's handler to get current registration information.
old-location: shell\syncmgr_isyncmgrregister_gethandlerregistrationinfo.htm
tech.root: shell
ms.assetid: 35241829-58b8-448a-ae69-1d43b4d0ba10
ms.date: 12/05/2018
ms.keywords: GetHandlerRegistrationInfo, GetHandlerRegistrationInfo method [Windows Shell], GetHandlerRegistrationInfo method [Windows Shell],ISyncMgrRegister interface, ISyncMgrRegister interface [Windows Shell],GetHandlerRegistrationInfo method, ISyncMgrRegister.GetHandlerRegistrationInfo, ISyncMgrRegister::GetHandlerRegistrationInfo, mobsync/ISyncMgrRegister::GetHandlerRegistrationInfo, shell.syncmgr_isyncmgrregister_gethandlerregistrationinfo, syncmgr.isyncmgrregister_gethandlerregistrationinfo
ms.topic: method
f1_keywords:
- mobsync/ISyncMgrRegister.GetHandlerRegistrationInfo
dev_langs:
- c++
req.header: mobsync.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
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
req.lib: 
req.dll: Mobsync.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Mobsync.dll
api_name:
- ISyncMgrRegister.GetHandlerRegistrationInfo
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ISyncMgrRegister::GetHandlerRegistrationInfo


## -description


Called by the registered application's handler to get current registration information.
   


## -parameters




### -param clsidHandler [in]

Type: <b>REFCLSID</b>

The CLSID of the handler.


### -param pdwSyncMgrRegisterFlags [in, out]

Type: <b>LPDWORD</b>

Returns registration flags from the <a href="https://docs.microsoft.com/windows/desktop/api/mobsync/ne-mobsync-syncmgrregisterflags">SYNCMGRREGISTERFLAGS</a> enumeration that indicate events for which the handler is registered to be notified.


## -returns



Type: <b>HRESULT</b>

This method supports the standard return values E_INVALIDARG, E_UNEXPECTED, and E_OUTOFMEMORY, as well as the following:

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
Call was successful, the handler is registered.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_FALSE</b></dt>
</dl>
</td>
<td width="60%">
Call was not successful, the handler is not registered.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mobsync/nn-mobsync-isyncmgrregister">ISyncMgrRegister</a>
 

 

