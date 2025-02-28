---
UID: NF:rpcproxy.CStdStubBuffer2_Connect
title: CStdStubBuffer2_Connect function (rpcproxy.h)
description: Implements the IRpcStubBuffer::Connect method and connects the server object to the stub.
old-location: rpc\cstdstubbuffer2_connect.htm
tech.root: Rpc
ms.assetid: ED3BA34C-1BAE-4CA0-A701-C64B8B9E717E
ms.date: 12/05/2018
ms.keywords: CStdStubBuffer2_Connect, CStdStubBuffer2_Connect function [RPC], rpc.cstdstubbuffer2_connect, rpcproxy/CStdStubBuffer2_Connect
ms.topic: function
f1_keywords:
- rpcproxy/CStdStubBuffer2_Connect
dev_langs:
- c++
req.header: rpcproxy.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2016 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Ole32.lib
req.dll: Ole32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- ole32.dll
- API-MS-Win-Core-Com-MidlProxyStub-L1-1-0.dll
- COMBase.dll
api_name:
- CStdStubBuffer2_Connect
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# CStdStubBuffer2_Connect function


## -description


<p class="CCE_Message">[CStdStubBuffer2_Connect is not supported and may be altered or unavailable in the future.]

Implements the  <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-irpcstubbuffer-connect">IRpcStubBuffer::Connect</a> method and connects the server object to the stub.


## -parameters




### -param pthis [in]

Pointer to  the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-irpcstubbuffer">IRpcStubBuffer</a> object. 


### -param pUnkServer [in]

Pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface of the server object. 


## -returns



Returns S_OK if success. Returns E_NOINTERFACE on error.




## -remarks



This function is used internally by proxies that are generated by MIDL.



