---
UID: NF:rpcproxy.CStdStubBuffer_IsIIDSupported
title: CStdStubBuffer_IsIIDSupported function (rpcproxy.h)
description: The CStdStubBuffer_IsIIDSupported function implements the IRpcStubBuffer::IsIIDSupported method.
old-location: rpc\cstdstubbuffer_isiidsupported.htm
tech.root: Rpc
ms.assetid: a0f47424-7286-493b-815f-96e27e645824
ms.date: 12/05/2018
ms.keywords: CStdStubBuffer_IsIIDSupported, CStdStubBuffer_IsIIDSupported, CStdStubBuffer_IsIIDSupported function [RPC], rpc.cstdstubbuffer_isiidsupported, rpcproxy/CStdStubBuffer_IsIIDSupported
ms.topic: function
f1_keywords:
- rpcproxy/CStdStubBuffer_IsIIDSupported
dev_langs:
- c++
req.header: rpcproxy.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps \| UWP apps]
req.target-min-winversvr: Windows 2000 Server [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: RpcRT4.lib
req.dll: RpcRT4.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- RpcRT4.dll
api_name:
- CStdStubBuffer_IsIIDSupported
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# CStdStubBuffer_IsIIDSupported function


## -description


<p class="CCE_Message">[CStdStubBuffer_IsIIDSupported is not supported and may be altered or unavailable in the future.]

The <b>CStdStubBuffer_IsIIDSupported</b> function implements the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-irpcstubbuffer-isiidsupported">IRpcStubBuffer::IsIIDSupported</a> method.


## -parameters




### -param This [in]

Pointer to the <b>IRpcStubBuffer</b> object.


### -param riid [in]

IID being tested for support.


## -returns



If the IID is supported, returns a pointer to the <b>IRpcStubBuffer</b> object associated with the IID.




## -remarks



This function is used internally by proxies that are generated by MIDL.



