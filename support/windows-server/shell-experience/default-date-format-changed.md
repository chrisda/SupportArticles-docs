---
title: The default date format is changed
description: Discusses that the default date format is changed in Windows 8 and Windows Server 2012.
ms.date: 09/09/2020
author: Deland-Han
ms.author: delhan
manager: dscontentpm
audience: itpro
ms.topic: troubleshooting
ms.prod: windows-server
localization_priority: medium
ms.reviewer: kaushika, cenki
ms.prod-support-area-path: DST and Timezones
ms.technology: ShellExperience
---
# The default date format is changed in Windows 8 and Windows Server 2012

This article describes that the default date format is changed and provides a workaround for issues caused by this change, for example, some tools or programs that depend on the earlier date formats fail.

_Original product version:_ &nbsp; Windows 10 - all editions, Windows Server 2012 R2  
_Original KB number:_ &nbsp; 2905782

## Summary

Versions of Windows and Windows Server that are earlier than Windows 8 and Windows Server 2012 use the following date formats:

Short Date: dd.MM.yyyy
Long Date: dd MMMM yyyy dddd

Starting in Windows 8 and Windows Server 2012, the date formats are changed to the following:

Short Date: d.M.yyyy
Long Date: d MMMM yyyy dddd

This change may cause some tools or programs that depend on the earlier date formats to fail.

> [!NOTE]
> These date formats are for the Turkish language locale. However, similar changes may apply to other regions.

## Workaround

To work around this change, revert the date formats to the original formats that are mentioned in the "Summary" section. To do this, use the **Change date, time, or number formats** item in **Control Panel**.