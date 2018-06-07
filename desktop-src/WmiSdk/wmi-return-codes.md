---
Description: This section provides a list of the WMI return codes, symbolic constants, literal values, and descriptions. These codes may be returned by scripts, C++ applications, or Wmic commands.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 7ae47482-edf4-4aa4-858a-76e55f3cb0a3
ms.prod: windows-server-dev
ms.technology: windows-management-instrumentation
ms.tgt_platform: multiple
title: WMI Return Codes
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# WMI Return Codes

This section provides a list of the WMI return codes, symbolic constants, literal values, and descriptions. These codes may be returned by scripts, C++ applications, or [**Wmic**](wmic.md) commands.

If an error occurs, WMI returns one of the following error codes as a 32-bit value where the two high-order bits indicate the severity code of the message.

<dl> <dt>

<span id="0"></span>0
</dt> <dd>

Success

</dd> <dt>

<span id="1"></span>1
</dt> <dd>

Informational

</dd> <dt>

<span id="2"></span>2
</dt> <dd>

Warning

</dd> <dt>

<span id="3"></span>3
</dt> <dd>

Error

</dd> </dl>

> [!Note]
>
> If WMI returns error messages, be aware that they may not indicate problems in the WMI service or in WMI providers. Failures can originate in other parts of the operating system and emerge as errors through WMI. Under any circumstances, do not delete the WMI repository as a first action because deleting the repository can cause damage to the system or to installed applications.
>
> To obtain more information about the source of the problem, you can download and run the [WMI Diagnosis Utility](Http://go.microsoft.com/fwlink/p/?linkid=84435) diagnostic command line tool. This tool produces a report that can usually isolate the source of the problem and provide instructions on how to fix it. The report also aids Microsoft support services in assisting you. You can download the WMI Diagnosis Utility [here](Http://go.microsoft.com/fwlink/p/?linkid=84419).

 

-   [**WMI Error Constants**](wmi-error-constants.md)
-   [**WMI Non-Error Constants**](wmi-non-error-constants.md)

 

 


