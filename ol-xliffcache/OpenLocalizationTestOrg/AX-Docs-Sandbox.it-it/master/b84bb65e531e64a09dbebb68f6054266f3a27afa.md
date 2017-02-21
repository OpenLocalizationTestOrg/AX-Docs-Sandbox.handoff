---
title: Advanced bank reconciliation overview
description: This article describes the flow for the advanced bank reconciliation process. The advanced bank reconciliation feature lets you import bank statements that can be automatically reconciled from within bank transactions.
author: ShylaThompson
manager: AnnBe
ms.date: 2015-12-11 21 - 23 - 46
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: BankReconciliationMatchRule
audience: Application User
ms.reviewer: ShylaThompson
ms.search.scope: AX 7.0.0, Operations
ms.custom: 22104
ms.assetid: 85d6def4-e59e-458f-be7c-bab938e23cc6
ms.search.region: Global
ms.author: leguo
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: b84bb65e531e64a09dbebb68f6054266f3a27afa


---

# <a name="advanced-bank-reconciliation-overview"></a>Advanced bank reconciliation overview

This article describes the flow for the advanced bank reconciliation process. The advanced bank reconciliation feature lets you import bank statements that can be automatically reconciled from within bank transactions.

The advanced bank reconciliation feature lets you import bank statements. The imported bank statement can then be automatically reconciled from within bank transactions. Here are the steps in the advanced bank reconciliation flow.

1.  Set up a bank statement import.
    -   Import bank statements through the data entity framework.
    -   Three typical bank statement formats are built in: ISO20022, BAI2, and MT940.
    -   The functionality can be extended to any format.

2.  Set up a number sequence to use for advanced bank reconciliation, and define the bank reconciliation matching rules.
    -   A reconciliation matching rule is a set of criteria that are used to filter bank statement lines and Microsoft Dynamics AX bank transaction lines during the reconciliation process. Depending on your business practice, you can set up more than one matching rule to automate and optimize your reconciliation process.

3.  Reconcile bank statements with Microsoft Dynamics AX bank transactions.
    -   Perform automatic matching and creation of reconciliation journals.
    -   View bank statements and Microsoft Dynamics AX bank transactions side by side.
    -   Automatically post Microsoft Dynamics AX bank transactions if they appear on a bank statement but don't appear in Microsoft Dynamics AX.
    -   Generate a reconciliation statement.






<!--HONumber=Feb17_HO3-->


