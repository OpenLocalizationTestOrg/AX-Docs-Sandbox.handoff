---
title: Balanced journals for interunit accounting
description: This article shows how a journal is automatically balanced when a balancing financial dimension is selected on the Ledger page.
author: twheeloc
manager: AnnBe
ms.date: 2015-12-03 20 - 52 - 10
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: LedgerParameters
audience: Application User
ms.reviewer: annbe
ms.search.scope: AX 7.0.0, Operations
ms.custom: 15791
ms.assetid: 4ad90a76-0894-43d9-9bf7-869bfa985898
ms.search.region: Global
ms.author: peakerbl
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: c575cdc88f701bfee0bd065abb2114859d7d244d


---

# <a name="balanced-journals-for-interunit-accounting"></a>Balanced journals for interunit accounting

This article shows how a journal is automatically balanced when a balancing financial dimension is selected on the Ledger page. 

If account entries don't balance at the level of the financial dimension values, additional account entries are created automatically to balance the journal. These account entries use the **Interunit - debit** and **Interunit - credit** posting types on the **Accounts for automatic transactions** page to determine the main account. For example, Branch, which is the second segment of the ledger account, is selected as the balancing financial dimension, and the following accounting entries are about to be created.

|                      |           |
|----------------------|-----------|
| 6100 – MSP – OU\_256 | 100.00 DR |
| 6100 – NY – OU\_249  | 100.00 DR |
| 2100 – MSP – OU\_256 | 200.00 CR |

In this case, the following balances are determined:

-   For Branch MSP = 100.00 CR
-   For Branch NY = 100.00 DR

Therefore, the following accounting entries are created automatically to balance the  journal at the level of the financial dimension values.

|                                   |           |
|-----------------------------------|-----------|
| (Interunit Debit) – MSP – OU\_256 | 100.00 DR |
| (Interunit Credit) – NY – OU\_249 | 100.00 CR |






<!--HONumber=Feb17_HO3-->


