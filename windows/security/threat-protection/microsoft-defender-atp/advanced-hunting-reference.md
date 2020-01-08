---
title: Advanced hunting schema reference
description: Learn about the tables in the advanced hunting schema
keywords: advanced hunting, atp query, query atp data, intellisense, atp telemetry, events, events telemetry, azure log analytics, column name, data type, description
search.product: eADQiWindows 10XVcnh
search.appverid: met150
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance 
ms.topic: article
ms.date: 07/24/2019
---

# Advanced hunting reference in Microsoft Defender ATP

**Applies to:**

- [Microsoft Defender Advanced Threat Protection (Microsoft Defender ATP)](https://go.microsoft.com/fwlink/p/?linkid=2069559)

>Want to experience Microsoft Defender ATP? [Sign up for a free trial.](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?ocid=docs-wdatp-advancedhuntingref-abovefoldlink)

## Advanced hunting table reference

The Advanced hunting schema is made up of multiple tables that provide either event information or information about certain entities. To effectively build queries that span multiple tables, you need to understand the tables and the columns in the Advanced hunting schema.

The following reference lists all the tables in the Advanced hunting schema. Each table name links to a page describing the column names for that table.

Table and column names are also listed within the Microsoft Defender Security Center, in the schema representation on the Advanced hunting screen.

| Table name | Description |
|------------|-------------|
| **[AlertEvents](advanced-hunting-alertevents-table.md)** | Alerts on Microsoft Defender Security Center |
| **[MachineInfo](advanced-hunting-machineinfo-table.md)** | Machine information, including OS information |
| **[MachineNetworkInfo](advanced-hunting-machinenetworkinfo-table.md)** | Network properties of machines, including adapters, IP and MAC addresses, as well as connected networks and domains |
| **[ProcessCreationEvents](advanced-hunting-processcreationevents-table.md)** | Process creation and related events |
| **[NetworkCommunicationEvents](advanced-hunting-networkcommunicationevents-table.md)** | Network connection and related events |
| **[FileCreationEvents](advanced-hunting-filecreationevents-table.md)** | File creation, modification, and other file system events |
| **[RegistryEvents](advanced-hunting-registryevents-table.md)** | Creation and modification of registry entries |
| **[LogonEvents](advanced-hunting-logonevents-table.md)** | Sign-ins and other authentication events |
| **[ImageLoadEvents](advanced-hunting-imageloadevents-table.md)** | DLL loading events |
| **[MiscEvents](advanced-hunting-miscevents-table.md)** | Multiple event types, including events triggered by security controls such as Windows Defender Antivirus and exploit protection |

## Related topics

- [Query data using Advanced hunting](advanced-hunting.md)
- [Best practices for Advanced hunting query-writing](advanced-hunting-best-practices.md)
