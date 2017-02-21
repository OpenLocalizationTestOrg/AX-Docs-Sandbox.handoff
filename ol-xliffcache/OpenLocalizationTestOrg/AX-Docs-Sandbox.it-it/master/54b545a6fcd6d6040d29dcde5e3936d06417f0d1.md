---
title: Correct a free text invoice
description: This article explains how to correct a free text invoice that has been posted and reissue it as a corrected invoice.
author: twheeloc
manager: AnnBe
ms.date: 2015-12-02 23 - 03 - 17
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: CustFreeInvoice
audience: Application User
ms.reviewer: twheeloc
ms.search.scope: AX 7.0.0, Operations
ms.custom: 13991
ms.assetid: 3db2a6f1-25b1-49d8-a9c0-614a6ce67e40
ms.search.region: Global
ms.author: mfalkner
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: 54b545a6fcd6d6040d29dcde5e3936d06417f0d1


---

# <a name="correct-a-free-text-invoice"></a>Correct a free text invoice

This article explains how to correct a free text invoice that has been posted and reissue it as a corrected invoice.

To correct a free text invoice that has already been posted, open the posted free text invoice. On the **Invoice** page, select **Cancel**, and then select **Correct invoice**. Select a reason code, add comments, and select the date for new corrected invoice. You can modify the corrected invoice, and post it. When you post the corrected invoice, a canceling invoice is created for a credit amount that equals the original invoice amount. Therefore, the combined balance of the original invoice and the canceling invoice is 0 (zero). The canceling invoice is settled against the original invoice. After you post the corrected invoice, you will have three invoices:

-   **Original invoice** – The invoice that includes the information that you're correcting.
-   **Canceling invoice** – The system-generated credit invoice that was created to cancel the invoice that was most recently corrected.
-   **Corrected invoice** – The invoice that contains the corrected invoice information.

You can identify canceling and correcting invoices in two ways:

-   The **All free text invoices** page includes a **Correction** column, where you can see which invoices are canceling invoices and corrected invoices.
-   The header of the free text invoice shows a status of **Cancelling invoice '\[invoice number\]'** or **Corrected invoice '\[invoice number\]'**.

**Note:** This feature is available only if the **Free text invoice correction** configuration key is selected.




<!--HONumber=Feb17_HO3-->


