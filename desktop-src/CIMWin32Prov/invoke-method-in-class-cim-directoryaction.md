---
Description: The Invoke method of the CIM\_DirectoryAction class takes a particular action. Details of how the method performs the action are implementation-specific. This method is inherited from CIM\_Action.
ms.assetid: e919dfdb-a52d-4bcb-abff-e1273c406226
ms.tgt_platform: multiple
title: Invoke method of the CIM_DirectoryAction class
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CIM_DirectoryAction.Invoke
api_type: 
- COM
api_location: 
- CIMWin32.dll
---

# Invoke method of the CIM\_DirectoryAction class

The **Invoke** method of the [**CIM\_DirectoryAction**](cim-directoryaction.md) class takes a particular action. Details of how the method performs the action are implementation-specific. This method is inherited from [**CIM\_Action**](cim-action.md).

> [!IMPORTANT]
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](https://Go.Microsoft.Com/FWLink/p/?LinkID=309367).

 

This topic uses Managed Object Format (MOF) syntax. For more information about using this method, see [Calling a Method](https://docs.microsoft.com/windows/desktop/WmiSdk/calling-a-method).

## Syntax


```mof
uint32 Invoke();
```



## Parameters

This method has no parameters.

## Return value

Returns a value of 0 (zero) on success, 1 (one) if the method is not supported, and any other number to indicate an error.

## Remarks

WMI does not implement this class.

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



## See also

<dl> <dt>

[CIM\_DirectoryAction](invoke-method-in-class-cim-directoryaction.md)
</dt> <dt>

[**CIM\_DirectoryAction**](cim-directoryaction.md)
</dt> </dl>

 

 




