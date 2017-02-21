---
title: Depreciation methods and conventions
description: This article provides an overview of the depreciation conventions and depreciation methods that are supported by Microsoft Dynamics AX.
author: twheeloc
manager: AnnBe
ms.date: 2015-09-10 21 - 04 - 03
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: AssetDepreciationProfile, AssetGroupBookSetup, AssetGroupDepBookSetup
audience: Application User
ms.reviewer: twheeloc
ms.search.scope: AX 7.0.0, Operations
ms.custom: 3441
ms.assetid: a11f0444-27a6-4948-a0ca-786e1db096b1
ms.search.region: Global
ms.author: saraschi
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: e82005f66a6d120dc6c90fd12665a27be0463748


---

# <a name="depreciation-methods-and-conventions"></a>Depreciation methods and conventions

This article provides an overview of the depreciation conventions and depreciation methods that are supported by Microsoft Dynamics AX.

You can select various depreciation methods and conventions. The purpose of the methods is to allocate the depreciable value of the fixed asset into fiscal periods. The depreciable value of the fixed asset is the acquisition price, reduced by a scrap value, if any. If you are using depreciation conventions and you modify the last depreciation run date for an asset, which then causes some depreciations to be skipped, the depreciation for the last year might be more than or less than is expected. The depreciation is adjusted by the number of depreciation periods affected by the modification of the last depreciation run date. For example, if you are using the Half year depreciation convention over three years, depreciation ordinarily occurs over 3 1/2 years. If you change the last depreciation run date during the 3 1/2 years, the last year of depreciation moves out the number of periods affected. If you move the date by three months, the last year will have nine months’ worth of depreciation, when ordinarily there would be six months’ worth of depreciation. You can select from the following depreciation conventions.
-   Half year
-   Full month
-   Mid quarter
-   Mid month (1st of month)
-   Mid month (15th of month)
-   Half year (start of year)
-   Half year (next year)

You can select from the following depreciation methods.
-   Straight line service life
-   Reducing balance
-   Manual
-   Factor
-   Consumption
-   Straight line life remaining
-   200% reducing balance
-   175% reducing balance
-   150% reducing balance
-   125% reducing balance

 



<a name="see-also"></a>See also
--------

[Fixed asset depreciation](fixed-asset-depreciation.md)

[Straight line service life depreciation](https://ax.help.dynamics.com/en/wiki/Straight-line-service-life-depreciation/)

[Reducing balance depreciation](reduce-balance-depreciation.md)

[Manual depreciation](manual-depreciation.md)

[Factor depreciation](factor-depreciation.md)

[Consumption depreciation](consumption-depreciation.md)

[Straight line life remaining depreciation](straight-line-life-remaining-depreciation.md)

[125 percent reducing balance depreciation](125-percent-reducing-balance-depreciation.md)

[150 percent reducing balance depreciation](150-percent-reducing-balance-depreciation.md)

[175 percent reducing balance depreciation](175-percent-reducing-balance-depreciation.md)

[200 percent reducing balance depreciation](200-percent-reducing-balance-depreciation.md)




<!--HONumber=Feb17_HO3-->


