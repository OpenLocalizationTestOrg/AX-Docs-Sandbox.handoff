---
title: Financial dimensions and main accounts in a right-to-left language
description: This topic describes some of the implementation decisions that you should consider when you use a right-to-left language in Microsoft Dynamics 365 for Operations, and you must set up financial dimensions and main accounts.
author: RobinARH
manager: AnnBe
ms.date: 2016-10-31 18 - 44 - 07
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
audience: Application User
ms.search.scope: Operations, Core
ms.custom: 222564
ms.assetid: f48ea074-d5cb-4d2e-a5e9-e3b8ddeea9fc
ms.search.region: global
ms.author: aolson
ms.dyn365.ops.intro: Nov-16
ms.dyn365.ops.version: Version 1611
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: b9f88d2cfd012b1d839a79ee3777b456d83b4efb


---

# <a name="financial-dimensions-and-main-accounts-in-a-right-to-left-language"></a>Financial dimensions and main accounts in a right-to-left language

This topic describes some of the implementation decisions that you should consider when you use a right-to-left language in Microsoft Dynamics 365 for Operations, and you must set up financial dimensions and main accounts.

Financial dimensions and main accounts are key components of the planning phase for an implementation. After financial dimensions and main accounts are created in the system, they are used on the **Configure account structures**, **Advanced rule structures**, and **Financial dimension configuration for integrating applications** pages. The order that is defined on those pages is used in the system for data entry and consumption. In some places in the system, the financial dimensions and main accounts appear in separate fields. However, in other places, such as journals, the financial dimensions and main accounts appear as a single string.

### <a name="best-practices-for-setting-up-financial-dimensions-and-main-accounts-in-a-right-to-left-system"></a>Best practices for setting up financial dimensions and main accounts in a right-to-left system

-   When you select the delimiter for charts of accounts, select one of the double delimiter options: double hyphen (--), double bar (||) or double period (..), or double underscore (\_\_).
-   When you create financial dimension and main account values, use only numbers and right-to-left language characters.
-   Avoid using the selected chart of accounts delimiter in financial dimension and main account values.

By following these best practices, you help guarantee consistent representation of the user defined-order throughout the system.




<!--HONumber=Feb17_HO3-->


