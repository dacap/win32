---
title: IsTSCGroupPresent method of the Win32_TSLicenseServer class
description: IsTSCGroupPresent is no longer available for use as of Windows Server 2012.
ms.assetid: 2bbb00ff-4fb3-4a7a-a0e7-3daabf97d70a
ms.tgt_platform: multiple
keywords:
- IsTSCGroupPresent method Remote Desktop Services
- IsTSCGroupPresent method Remote Desktop Services , Win32_TSLicenseServer class
- Win32_TSLicenseServer class Remote Desktop Services , IsTSCGroupPresent method
topic_type:
- apiref
api_name:
- Win32_TSLicenseServer.IsTSCGroupPresent
api_location:
- TlsWmiProv.dll
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# IsTSCGroupPresent method of the Win32\_TSLicenseServer class

\[**IsTSCGroupPresent** is no longer available for use as of Windows Server 2012.\]

This method is not supported.

**Windows Server 2008 R2 and Windows Server 2008:** Retrieves whether the Terminal Server Computers local group exists on the Remote Desktop license server.

## Syntax


```mof
uint32 IsTSCGroupPresent(
  [out] boolean Present
);
```



## Parameters

<dl> <dt>

*Present* \[out\]
</dt> <dd>

Boolean value that indicates whether the Terminal Server Computers local group exists.

</dd> </dl>

## Return value

Returns **WBEM\_E\_NOT\_SUPPORTED**.

**Windows Server 2008 R2 and Windows Server 2008:** If the method succeeds, it returns zero. If the method is unsuccessful, it returns a nonzero value. For a list of error codes, see [Remote Desktop Services WMI Provider Error Codes](terminal-services-wmi-provider-error-codes.md).

## Remarks

You must be a member of the Administrators group to call this method.

Managed Object Format (MOF) files contain the definitions for Windows Management Instrumentation (WMI) classes. MOF files are not installed as part of the Microsoft Windows Software Development Kit (SDK). They are installed on the server when you add the associated role by using the Server Manager. For more information about MOF files, see [Managed Object Format (MOF)](https://docs.microsoft.com/windows/desktop/WmiSdk/managed-object-format--mof-).

## Requirements



|                                     |                                                                                           |
|-------------------------------------|-------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | None supported<br/>                                                                 |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                            |
| End of client support<br/>    | None supported<br/>                                                                 |
| End of server support<br/>    | Windows Server 2008 R2<br/>                                                         |
| Namespace<br/>                | Root\\CIMv2<br/>                                                                    |
| MOF<br/>                      | <dl> <dt>TlsWmiProv.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>TlsWmiProv.dll</dt> </dl> |



## See also

<dl> <dt>

[**Win32\_TSLicenseServer**](win32-tslicenseserver.md)
</dt> </dl>

 

 





