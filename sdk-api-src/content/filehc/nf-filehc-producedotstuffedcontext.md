---
UID: NF:filehc.ProduceDotStuffedContext
title: ProduceDotStuffedContext function (filehc.h)
description: Retrieves the FIO_CONTEXT structure with the requested state.
old-location: winprog\_producedotstuffedcontext.htm
tech.root: DevNotes
ms.assetid: 6fbac935-339d-4744-9359-7b3b85bfb7c6
ms.date: 12/05/2018
ms.keywords: ProduceDotStuffedContext, ProduceDotStuffedContext function [Windows API], filehc/ProduceDotStuffedContext, winprog._producedotstuffedcontext
ms.topic: function
f1_keywords:
- filehc/ProduceDotStuffedContext
dev_langs:
- c++
req.header: filehc.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
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
req.lib: Fcachdll.lib
req.dll: Fcachdll.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Fcachdll.dll
api_name:
- ProduceDotStuffedContext
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ProduceDotStuffedContext function


## -description


Retrieves the <a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a> structure with the requested state.


## -parameters




### -param pContext [in]

A pointer to an <a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a> structure.


### -param lpstrName [in]

Not currently used.


### -param fWantItDotStuffed [in]

Specifies whether the <a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a> structure should be dot stuffed. If <b>TRUE</b>, dots should be added. If <b>FALSE</b>, dots should be removed.


## -returns



Returns the <a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a> structure.




## -remarks



This call may or may not create a new <a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a> structure. If a new structure is created, it remains in the cache so that it can be used again. If a new structure is created, the user has the only reference to the resulting <a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a> structure, so it disappears when <a href="Http://go.microsoft.com/fwlink/p/?linkid=85303">ReleaseContext</a> is called.




## -see-also




<a href="Http://go.microsoft.com/fwlink/p/?linkid=85304">FIO_CONTEXT</a>



<a href="Http://go.microsoft.com/fwlink/p/?linkid=85303">ReleaseContext</a>
 

 

