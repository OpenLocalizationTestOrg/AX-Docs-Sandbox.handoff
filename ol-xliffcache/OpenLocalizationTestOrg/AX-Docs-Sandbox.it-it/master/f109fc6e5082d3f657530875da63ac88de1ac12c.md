---
title: Physical and financial updates
description: This topic provides an overview of which types of transactions increase or decrease inventory quantities.
author: YuyuScheller
manager: AnnBe
ms.date: 2016-03-31 12 - 50 - 59
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: InventTrans, InventTransVoucher
audience: Application User
ms.search.scope: AX 7.0.0, Operations
ms.custom: 75023
ms.assetid: c0c67163-e261-4264-97a7-8b0d7b998376
ms.search.region: Global
ms.search.industry: Manufacturing
ms.author: mguada
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: f109fc6e5082d3f657530875da63ac88de1ac12c


---

# <a name="physical-and-financial-updates"></a>Physical and financial updates

This topic provides an overview of which types of transactions increase or decrease inventory quantities. 

Inventory transactions can be physically updated and financially updated in Microsoft Dynamics 365 for Operations. Some types of physical and financial transactions increase inventory quantities, whereas others decrease the quantity.

## <a name="physical-increases"></a>Physical increases
When a physical transaction is posted, the status of the transaction record is **Received**. The following transactions are considered physical increases:

-   Purchase order receipt
-   Sales order packing slip return
-   Reporting a production order as finished
-   By-product on a production order picking list

## <a name="financial-increases"></a>Financial increases
When a financial receipt transaction is posted, the status of the transaction record that increases the quantity is **Purchased**. The following transactions are considered financial increases:

-   Vendor invoice
-   Sales order invoice for a return
-   Production order costing
-   Positive quantity inventory journals, such as movement, profit and loss, counting, bill of materials, and transfer

## <a name="transactions-that-increase-quantity"></a>Transactions that increase quantity
Transactions that increase quantity are posted at the running average cost price. Dynamics 365 for Operations calculates a running average cost price that is based on the cost of each of these transactions for each inventory dimension that is being tracked financially. For information about running average cost prices, see [Running average cost price](running-average-cost-price.md).

## <a name="transactions-that-decrease-quantity"></a>Transactions that decrease quantity
Dynamics 365 for Operations uses the calculated running average cost price when a transaction that decreases quantity is posted, regardless of the inventory model that is associated with that inventory. The transaction that decreases quantity must not have been marked to another transaction before it was posted. If the physical on-hand inventory becomes negative, Dynamics 365 for Operations uses the inventory cost that is defined for the item on the **Item** page. **Note:** If multisite functionality is enabled, this cost will instead be the inventory cost that is defined for a site on the **Default order settings** page.

## <a name="physical-issues-vs-financial-issues"></a>Physical issues vs. financial issues
When a physical issue transaction is posted, the status of the transaction record is **Deducted**. The following transactions are considered physical issues:

-   Production order picking list journal
-   Sales order packing slip
-   Purchase order packing slip return

When a financial transaction is posted, the status of the transaction record is **Sold**. The following transactions are considered financial issues:

-   Ending a production order
-   Sales order invoice
-   Vendor invoice return
-   Negative quantity inventory journals, such as movement, profit and loss, counting, bill of materials, and transfer

Transactions that decrease quantity are posted at the running average cost price. Therefore, the inventory close procedure is required in order to settle issue transactions to receipt transactions, based on the inventory model that is assigned to each item.




<!--HONumber=Feb17_HO3-->


