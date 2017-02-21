---
title: Inventory tag counting
description: This article provides information about tag counting, which you use to compare the actual contents of a warehouse with the on-hand inventory.
author: YuyuScheller
manager: AnnBe
ms.date: 2015-10-30 12 - 54 - 09
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: InventJournalCount, InventJournalCountTag
audience: Application User
ms.search.scope: AX 7.0.0, Operations
ms.custom: 11594
ms.assetid: 178ea5aa-fce8-484e-8f8a-7a6b82090c2b
ms.search.region: Global
ms.author: mafoge
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: e647054ca47ef8d2447cacf82df43c3011099903


---

# <a name="inventory-tag-counting"></a>Inventory tag counting

This article provides information about tag counting, which you use to compare the actual contents of a warehouse with the on-hand inventory. 

By creating lines on the **Tag counting** page, you place a tag number on each inventory item, such as a number from 1 to 500. During the count, you enter the item number and the quantity on a corresponding tag. This tag can then be used as the basis for input in the tag counting journal. After you post the tag counting journal, a new counting journal is created on the **Counting** page. The new journal is based on the tag counting journal lines that you created. To tag-count items by a specific inventory dimension, select the dimension on the **Display dimension** page that is displayed when you create the tag counting journal. For example, to count items in a specific warehouse, select the **Warehouse** check box. If the **Lock items during count** slider on the **Inventory and warehouse management parameters** page is selected, items can't be physically updated during counting. However, items in tag counting journals aren't locked during counting. Inventory transactions aren't created until the tag counting lines are posted and transferred to a counting journal. If tags are entered randomly, and you want to identify missing tags, click the **Tag** column header to sort the lines by tag.

<a name="see-also"></a>See also
--------

[Cycle counting](cycle-counting.md)




<!--HONumber=Feb17_HO3-->


