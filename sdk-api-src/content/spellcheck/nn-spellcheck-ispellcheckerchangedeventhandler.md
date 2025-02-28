---
UID: NN:spellcheck.ISpellCheckerChangedEventHandler
title: ISpellCheckerChangedEventHandler (spellcheck.h)
description: Allows the caller to create a handler for notifications that the state of the speller has changed.
old-location: intl\ispellcheckerchangedeventhandler.htm
tech.root: Intl
ms.assetid: 9dd1f768-a901-4682-9530-019fe1dfbf0b
ms.date: 12/05/2018
ms.keywords: ISpellCheckerChangedEventHandler, ISpellCheckerChangedEventHandler interface [Internationalization for Windows Applications], ISpellCheckerChangedEventHandler interface [Internationalization for Windows Applications],described, intl.ispellcheckerchangedeventhandler, spellcheck/ISpellCheckerChangedEventHandler
ms.topic: interface
f1_keywords:
- spellcheck/ISpellCheckerChangedEventHandler
dev_langs:
- c++
req.header: spellcheck.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2012 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Spellcheck.idl
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
- Spellcheck.h
api_name:
- ISpellCheckerChangedEventHandler
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ISpellCheckerChangedEventHandler interface


## -description


Allows the caller to create a handler for notifications that the state of the speller has changed.


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">ISpellCheckerChangedEventHandler</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>ISpellCheckerChangedEventHandler</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>ISpellCheckerChangedEventHandler</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/spellcheck/nf-spellcheck-ispellcheckerchangedeventhandler-invoke">Invoke</a>
</td>
<td align="left" width="63%">
Receives the SpellCheckerChanged event.

</td>
</tr>
</table> 

