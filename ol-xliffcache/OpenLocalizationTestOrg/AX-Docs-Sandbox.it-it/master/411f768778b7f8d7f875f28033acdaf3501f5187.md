---
title: Factor depreciation
description: This article gives an overview of the factor depreciation method.
author: twheeloc
manager: AnnBe
ms.date: 2015-12-02 22 - 57 - 58
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: AssetDepreciationProfile
audience: Application User
ms.reviewer: twheeloc
ms.search.scope: AX 7.0.0, Operations
ms.custom: 13831
ms.assetid: 6df44483-e53f-458e-ae39-044ad320c2e9
ms.search.region: Global
ms.author: saraschi
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: 411f768778b7f8d7f875f28033acdaf3501f5187


---

# <a name="factor-depreciation"></a>Factor depreciation

This article gives an overview of the factor depreciation method.

Factors are the percentages that are used to depreciate assets. When you set up a fixed asset depreciation profile and select **Factor** in the **Method** field on the **Depreciation profiles** page, you can set up progressive, digressive, or straight line depreciation:

-   In progressive depreciation, the amount of depreciation increases each depreciation period.
-   In digressive depreciation, the amount of depreciation per period decreases over time.
-   In straight line depreciation, the depreciation is the same in each period.

The rules and examples that follow indicate how you can set up factors for each type of depreciation. **Note:** When you select **Factor** in the **Method** field, the **Factor** field and the **Interval** field are displayed.

## <a name="progressive-depreciation"></a>Progressive depreciation
The value in the **Factor** field is more than **50**.

### <a name="example"></a>Example

The acquisition price is 100,000, the factor is 70, the service life is 10 years, and depreciation starts on January 1. The depreciation amounts and net book value amounts are shown only for the first six years of service life.

| Year | Period      | Depreciation amount | Net book value amount |
|------|-------------|---------------------|-----------------------|
| 1    | December 31 | 307.69              | 99,692.31             |
| 2    | December 31 | 1,447.21            | 98,245.10             |
| 3    | December 31 | 3,104.50            | 95,140.60             |
| 4    | December 31 | 5,150.21            | 89,990.39             |
| 5    | December 31 | 7,522.95            | 82,467.44             |
| 6    | December 31 | 10,184.06           | 72,283.38             |

## <a name="digressive-depreciation"></a>Digressive depreciation
The value in the **Factor** field is less than **50**.

### <a name="example"></a>Example

The acquisition price is 100,000, the factor is 20, the service life is 10 years, and depreciation starts on January 1. The depreciation amounts and net book value amounts are shown only for the first six years of service life.

| Year | Period      | Depreciation amount | Net book value amount |
|------|-------------|---------------------|-----------------------|
| 1    | December 31 | 56,080.43           | 43,919.57             |
| 2    | December 31 | 10,665.70           | 33,253.87             |
| 3    | December 31 | 7,156.22            | 26,097.65             |
| 4    | December 31 | 5,538.06            | 20,559.59             |
| 5    | December 31 | 4,579.89            | 15,979.70             |
| 6    | December 31 | 3,937.36            | 12,042.34             |

## <a name="straight-line-depreciation"></a>Straight line depreciation
The value in the **Factor** field is equal to **50**. In this case, the depreciation is the same in each period, and you should consider the implications of the values that you have specified in other fields, as described in [Straight line service life depreciation](http://authoring.help.dynamics.com/en/wiki/Straight-line-service-life-depreciation/).




<!--HONumber=Feb17_HO3-->


