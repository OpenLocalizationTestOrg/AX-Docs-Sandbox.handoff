---
title: Round-off amount for depreciation calculations
description: This article discusses the Round-off depreciation field that is found on the Book setup pages.
author: twheeloc
manager: AnnBe
ms.date: 2015-12-02 23 - 00 - 51
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: AssetBookTable, AssetDepBookTable
audience: Application User
ms.search.scope: AX 7.0.0, Operations
ms.custom: 13931
ms.assetid: bf91a80f-82aa-42f5-a5e7-57829c26c1ea
ms.search.region: Global
ms.author: saraschi
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: ba27528c7daf1195d43390a1ffc5ffa333cc2d53


---

# <a name="round-off-amount-for-depreciation-calculations"></a>Round-off amount for depreciation calculations

This article discusses the Round-off depreciation field that is found on the Book setup pages.

Round-off depreciation amounts are set for each book. Round-off depreciation amounts are used in the fixed asset depreciation profile that shows the future depreciation and value of the fixed asset, and also in depreciation proposals. Enter the lowest depreciation amount that is allowed for the book. Regardless of the rounding that is set up, the depreciation amount in the last depreciation period isn't rounded. At the end of the last depreciation period, the value of the fixed asset must be 0 (zero) or the scrap value, if scrap value is used.

### <a name="example"></a>Example

Depreciation without rounding is calculated as 2,444.44. As the following table shows, the amounts that are suggested vary, depending on how rounding is set up.

| Rounding method | Depreciation amount |
|-----------------|---------------------|
| Rounding 0.1    | 2,444.40            |
| Rounding 1.00   | 2,444.00            |
| Rounding 10.00  | 2,440.00            |
| Rounding 100.00 | 2,400.00            |






<!--HONumber=Feb17_HO3-->


