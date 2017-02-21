---
title: Derived books
description: This article provides an overview of derived book functionality.
author: twheeloc
manager: AnnBe
ms.date: 2015-09-10 20 - 49 - 10
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: AssetBookTable
audience: Application User
ms.search.scope: AX 7.0.0, Operations
ms.custom: 3401
ms.assetid: 5b11cce9-6654-483d-a276-44efe138d071
ms.search.region: Global
ms.author: saraschi
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: 32f3e11566cf41b7738c0474dfdbf9c64b56ef18


---

# <a name="derived-books"></a>Derived books

This article provides an overview of derived book functionality.

The purpose of derived books is to simplify the posting of fixed asset book transactions that are planned for regular intervals.  You choose one book as the primary book. This usually is the book that is used for accounting depreciation. You then attach to it other books that are set up to post transactions in the same intervals as the primary book. Tax depreciation books are often set up as derived books. The most common transactions to set up to post to derived books are acquisitions, acquisition adjustments, and disposals. Example Book B and book C are set up as derived books for book A for the Acquisition transaction type. In book A, you enter an acquisition transaction for asset 123 for 1,500.00. When the transaction is posted, an acquisition transaction is generated and posted in asset 123 for book B and in asset 123 for book C for 1,500.00. When you prepare the transactions of the primary book for posting in the fixed asset journal, you can also view and modify the transactions of the derived books. If you prepare the primary book transactions in another journal, the transactions of the derived value are not displayed. However, they are posted to the appropriate accounts and posting layers when you post the primary book transactions.
| **Note**                                                                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Books that are set up to post transactions at intervals other than the primary book intervals must be attached to the fixed asset as separate books and not as derived books. |

 
-



<a name="see-also"></a>See also
--------

[Posting with derived value models](post-derived-value-models.md)




<!--HONumber=Feb17_HO3-->


