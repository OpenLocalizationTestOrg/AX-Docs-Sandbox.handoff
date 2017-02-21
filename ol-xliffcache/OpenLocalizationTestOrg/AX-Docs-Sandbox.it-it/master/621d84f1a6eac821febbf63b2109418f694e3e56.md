---
title: Consolidated batch orders
description: This article describes the concept of consolidated batch orders.
author: YuyuScheller
manager: AnnBe
ms.date: 2015-12-07 09 - 17 - 20
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: PmfAddToConsOrder, PmfBulkItemConv, PmfBulkPackOnHand, PmfConsOrderListPage
audience: Application User
ms.reviewer: YuyuScheller
ms.search.scope: AX 7.0.0, Operations
ms.custom: 19291
ms.assetid: 1c1f059f-c1b3-47f3-b696-9472c20df8ad
ms.search.region: Global
ms.search.industry: Manufacturing
ms.author: yuyus
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: 621d84f1a6eac821febbf63b2109418f694e3e56


---

# <a name="consolidated-batch-orders"></a>Consolidated batch orders

This article describes the concept of consolidated batch orders.

A bulk item that is produced is considered a parent item, whereas a packed item is considered a child item. The relation between the bulk item and the packed item is expressed in a bulk item conversion. This bulk item conversion is defined on the bulk item itself. Packed items can be packaged into containers of either a single size or multiple sizes that are considered one unit. By consolidating the orders for a bulk item, you can see all the related batch orders in a single view that can help you determine any remaining work that must be completed. A consolidated batch order can contain any combination of the following orders:

-   A single bulk order and multiple packed orders
-   Multiple bulk orders and multiple packed orders
-   Multiple bulk orders and a single packed order
-   Only packed orders





<!--HONumber=Feb17_HO3-->


