---
UID: NF:portabledeviceapi.IPortableDevice.Close
title: IPortableDevice::Close (portabledeviceapi.h)
description: The Close method closes the connection with the device.
old-location: wpdsdk\iportabledevice_close.htm
tech.root: wpd_sdk
ms.assetid: aa60a439-7589-465e-98e5-56b93d594f96
ms.date: 12/05/2018
ms.keywords: Close, Close method [Windows Portable Devices SDK], Close method [Windows Portable Devices SDK],IPortableDevice interface, IPortableDevice interface [Windows Portable Devices SDK],Close method, IPortableDevice.Close, IPortableDevice::Close, IPortableDeviceClose, portabledeviceapi/IPortableDevice::Close, wpdsdk.iportabledevice_close
ms.topic: method
f1_keywords:
- portabledeviceapi/IPortableDevice.Close
dev_langs:
- c++
req.header: portabledeviceapi.h
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
req.lib: PortableDeviceGUIDs.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- PortableDeviceGUIDs.lib
- PortableDeviceGUIDs.dll
api_name:
- IPortableDevice.Close
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IPortableDevice::Close


## -description


The <b>Close</b> method closes the connection with the device.
      


## -parameters






## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.
          

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
The method succeeded.

</td>
</tr>
</table>
 




## -remarks



You should not usually need to call this method yourself. When the last reference to the <a href="https://docs.microsoft.com/windows/desktop/api/portabledeviceapi/nn-portabledeviceapi-iportabledevice">IPortableDevice</a> interface  is released, Windows Portable Devices calls <b>Close</b> for you. Calling this method manually forces the connection to the device to close, and any Windows Portable Devices objects hosted on this device will cease to function. You can call <a href="https://docs.microsoft.com/windows/desktop/api/portabledeviceapi/nf-portabledeviceapi-iportabledevice-open">Open</a> to reopen the connection.
      




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/portabledeviceapi/nn-portabledeviceapi-iportabledevice">IPortableDevice Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/portabledeviceapi/nf-portabledeviceapi-iportabledevice-open">IPortableDevice::Open</a>
 

 

