---
UID: NE:wnvapi._WNV_NOTIFICATION_TYPE
title: WNV_NOTIFICATION_TYPE (wnvapi.h)
description: Specifies the type of a given Windows Network Virtualization (WNV) notification.
old-location: wnv\wnv_notification_type.htm
tech.root: wnv
ms.assetid: 70BE564E-A054-4991-ADCD-79E4D219307B
ms.date: 12/05/2018
ms.keywords: '*PWNV_NOTIFICATION_TYPE, PWNV_NOTIFICATION_TYPE, PWNV_NOTIFICATION_TYPE enumeration pointer [Windows Network Virtualization], WNV_NOTIFICATION_TYPE, WNV_NOTIFICATION_TYPE enumeration [Windows Network Virtualization], WnvNotificationTypeMax, WnvObjectChangeType, WnvPolicyMismatchType, WnvRedirectType, wnv.wnv_notification_type, wnvapi/PWNV_NOTIFICATION_TYPE, wnvapi/WNV_NOTIFICATION_TYPE, wnvapi/WnvNotificationTypeMax, wnvapi/WnvObjectChangeType, wnvapi/WnvPolicyMismatchType, wnvapi/WnvRedirectType'
ms.topic: enum
f1_keywords:
- wnvapi/WNV_NOTIFICATION_TYPE
dev_langs:
- c++
req.header: wnvapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2012 [desktop apps only]
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
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- wnvapi.h
api_name:
- WNV_NOTIFICATION_TYPE
targetos: Windows
req.typenames: WNV_NOTIFICATION_TYPE, *PWNV_NOTIFICATION_TYPE
req.redist: 
ms.custom: 19H1
---

# WNV_NOTIFICATION_TYPE enumeration


## -description


Specifies the type of a given Windows Network Virtualization (WNV) notification.


## -enum-fields




### -field WnvPolicyMismatchType

A policy mismatch notification.


### -field WnvRedirectType

A notification that an Internet Control Message Protocol
(ICMP) redirect message has been received.


### -field WnvObjectChangeType

A notification that a network object has changed.


### -field WnvNotificationTypeMax

The maximum possible value for this enumeration type. This is not a legal value.


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wnvapi/ns-wnvapi-wnv_notification_param">WNV_NOTIFICATION_PARAM</a>
 

 

