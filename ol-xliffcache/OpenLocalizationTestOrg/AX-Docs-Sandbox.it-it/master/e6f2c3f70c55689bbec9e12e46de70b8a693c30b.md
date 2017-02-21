---
title: Single voucher and currency revaluation upgrade for Microsoft Dynamics 365 for Operations version 1611
description: Some organizations enter journals that contain a single voucher that has more than one customer or vendor, and they also run the Accounts receivable or Accounts payable foreign currency revaluation process. This topic describes the steps that these organizations should follow when they upgrade to Microsoft Dynamics 365 for Operations version 1611.
author: twheeloc
manager: AnnBe
ms.date: 2016-12-28 16 - 04 - 17
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
audience: Application User
ms.search.scope: Operations, Core
ms.custom: 265364
ms.assetid: 3dbc31e1-951a-427f-8e19-fbd7074ea660
ms.search.region: Global
ms.author: saraschi
ms.dyn365.ops.intro: Nov-16
ms.dyn365.ops.version: Version 1611
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: e6f2c3f70c55689bbec9e12e46de70b8a693c30b


---

# <a name="single-voucher-and-currency-revaluation-upgrade-for-microsoft-dynamics-365-for-operations-version-1611"></a>Single voucher and currency revaluation upgrade for Microsoft Dynamics 365 for Operations version 1611

Some organizations enter journals that contain a single voucher that has more than one customer or vendor, and they also run the Accounts receivable or Accounts payable foreign currency revaluation process. This topic describes the steps that these organizations should follow when they upgrade to Microsoft Dynamics 365 for Operations version 1611.

Follow these steps when you upgrade to Microsoft Dynamics 365 for Operations version 1611.

1.  Before you upgrade to Dynamics 365 for Operations, run the foreign currency revaluation processes for Accounts receivable and Accounts payable. Set the **Method** field to **Invoice date**. A revaluation transaction is created that reverses the last foreign currency revaluation. Therefore, the open transactions are valued at their original accounting currency.
2.  Upgrade to Dynamics 365 for Operations version 1611.
3.  Run the Accounts receivable and Accounts payable foreign currency revaluation processes again. This time, set the **Method** field to **Standard**. A new revaluation transaction is created that is based on the current exchange rates. This transaction records the unrealized gain/loss and the correct summary ledger account.





<!--HONumber=Feb17_HO3-->


