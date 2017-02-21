---
title: Fixed asset disposal posting accounts
description: This article explains how to set up general ledger posting accounts for disposing of assets.
author: twheeloc
manager: AnnBe
ms.date: 2015-09-10 21 - 04 - 08
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: AssetPosting
audience: Application User
ms.reviewer: twheeloc
ms.search.scope: AX 7.0.0, Operations
ms.custom: 3461
ms.assetid: fb07b5b8-7a31-40c0-b3ec-4495f36b3a4a
ms.search.region: Global
ms.author: saraschi
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: a0d56dad0dc93a1f53a99b698df515641fb1afd6


---

# <a name="fixed-asset-disposal-posting-accounts"></a>Fixed asset disposal posting accounts

This article explains how to set up general ledger posting accounts for disposing of assets.

In the Fixed asset posting profiles page, on the Ledger accounts FastTab, select Disposal - sale and Disposal - scrap to set up postings to the ledger.
For both transaction types, the ledger account is credited for the disposal value of the fixed asset. The debit is posted to an offset account, which might be, for example, a bank account. If a fixed asset is sold to a customer, the customer account is used instead of the offset account. Click Disposal and then click Sale or Scrap, and then set up detailed accounts to reverse the net book value of the fixed asset. You can also enter information in the Post value and Sales value type fields in the Disposal parameters page. The disposal transaction for an asset in a low-value pool reduces the net book value of the low-value pool by the disposed amount only. However, when the sale of an asset is exceeds the net book value of the low-value pool, the net book value is reduced to zero.






<!--HONumber=Feb17_HO3-->


