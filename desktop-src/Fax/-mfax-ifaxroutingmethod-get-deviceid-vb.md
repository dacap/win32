---
Description: The DeviceId property is a number representing the line identifier for the fax port.
ms.assetid: bb18ef93-53db-4423-9ef1-34ab3161acba
title: FaxRoutingMethod.DeviceId property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# FaxRoutingMethod.DeviceId property

The **DeviceId** property is a number representing the line identifier for the fax port.

This property is read-only.

## Syntax


```VB
Property DeviceId As Long
```



## Property value

A **Long** that receives the permanent line identifier for the fax port associated with the specified fax routing method.

## Remarks

A fax client application can use the **DeviceId** property to uniquely identify a fax port. You can call the [**DeviceName**](-mfax-ifaxroutingmethod-get-devicename-vb.md) property to retrieve the user-friendly name for a port. Note, however, that it is possible for multiple fax ports to have the same user-friendly name.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 2000 Professional \[desktop apps only\]<br/>                            |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Faxcom.h</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Faxcom.dll</dt> </dl> |



## See also

<dl> <dt>

[**FaxRoutingMethod**](-mfax-faxroutingmethod-object-visual-basic-.md)
</dt> <dt>

[Fax Service Client API for Windows 2000](-mfax-fax-service-client-api-for-windows-2000.md)
</dt> <dt>

[Fax Service Client API Interfaces](-mfax-fax-service-client-api-interfaces.md)
</dt> <dt>

[**IFaxRoutingMethod**](/previous-versions/windows/desktop/api/Faxcom/nn-faxcom-ifaxroutingmethod)
</dt> <dt>

[**IFaxRoutingMethods**](/previous-versions/windows/desktop/api/Faxcom/nn-faxcom-ifaxroutingmethods)
</dt> <dt>

[**IFaxPort**](/previous-versions/windows/desktop/api/Faxcom/nn-faxcom-ifaxport)
</dt> <dt>

[**IFaxPorts**](/previous-versions/windows/desktop/api/Faxcom/nn-faxcom-ifaxports)
</dt> <dt>

[**DeviceName**](-mfax-ifaxroutingmethod-get-devicename-vb.md)
</dt> </dl>

 

 



