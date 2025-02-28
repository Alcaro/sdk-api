---
UID: NF:fsrmreports.IFsrmFileManagementJob.get_DaysSinceFileLastModified
title: IFsrmFileManagementJob::get_DaysSinceFileLastModified (fsrmreports.h)
description: The number of days that have elapsed since a file was last modified.
old-location: fsrm\ifsrmfilemanagementjob_dayssincefilelastmodified.htm
tech.root: fsrm
ms.assetid: 3ee02d60-50c7-4643-9604-b72ca1da01f6
ms.date: 12/05/2018
ms.keywords: DaysSinceFileLastModified property [File Server Resource Manager], DaysSinceFileLastModified property [File Server Resource Manager],IFsrmFileManagementJob interface, IFsrmFileManagementJob interface [File Server Resource Manager],DaysSinceFileLastModified property, IFsrmFileManagementJob.DaysSinceFileLastModified, IFsrmFileManagementJob.get_DaysSinceFileLastModified, IFsrmFileManagementJob::DaysSinceFileLastModified, IFsrmFileManagementJob::get_DaysSinceFileLastModified, IFsrmFileManagementJob::put_DaysSinceFileLastModified, fs.ifsrmfilemanagementjob_dayssincefilelastmodified, fsrm.ifsrmfilemanagementjob_dayssincefilelastmodified, fsrmreports/IFsrmFileManagementJob::DaysSinceFileLastModified, fsrmreports/IFsrmFileManagementJob::get_DaysSinceFileLastModified, fsrmreports/IFsrmFileManagementJob::put_DaysSinceFileLastModified, get_DaysSinceFileLastModified
ms.topic: method
f1_keywords:
- fsrmreports/IFsrmFileManagementJob.DaysSinceFileLastModified
dev_langs:
- c++
req.header: fsrmreports.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2008 R2
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
req.dll: SrmSvc.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- SrmSvc.dll
api_name:
- IFsrmFileManagementJob.DaysSinceFileLastModified
- IFsrmFileManagementJob.get_DaysSinceFileLastModified
- IFsrmFileManagementJob.put_DaysSinceFileLastModified
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFsrmFileManagementJob::get_DaysSinceFileLastModified


## -description


<p class="CCE_Message">[This property is supported for compatibility but it's recommended to use the 
    <a href="https://docs.microsoft.com/previous-versions/windows/desktop/fsrm/fsrm-wmi-classes">FSRM WMI Classes</a> to manage FSRM. Please see the 
    <a href="https://docs.microsoft.com/previous-versions/windows/desktop/fsrm/msft-fsrmfilemanagementjob">MSFT_FSRMFileManagementJob</a> class.]

The number of days that have elapsed since a file was last modified.

This property is read/write.


## -parameters


## -remarks



The value is FsrmDaysNotSpecified if not set.

The job considers this condition met for a file if the file's last modified date minus the job's current run 
    date is less than the value of <i>daysSinceModify</i>.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/fsrmreports/nn-fsrmreports-ifsrmfilemanagementjob">IFsrmFileManagementJob</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/fsrm/msft-fsrmfilemanagementjob">MSFT_FSRMFileManagementJob</a>
 

 

