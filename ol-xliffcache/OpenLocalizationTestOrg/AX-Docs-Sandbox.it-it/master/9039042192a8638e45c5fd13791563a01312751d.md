---
title: Balance sheet financial reports
description: This article describes the default reports for balance sheets. It also describes the building blocks that are associated with these reports.
author: twheeloc
manager: AnnBe
ms.date: 2015-11-04 19 - 29 - 22
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
audience: Application User
ms.reviewer: annbe
ms.search.scope: AX 7.0.0, Operations
ms.custom: 12274
ms.assetid: 5df57e42-1290-41d6-9de7-45a8cb1541a5
ms.search.region: Global
ms.author: jcart
ms.dyn365.intro: Feb-16
ms.dyn365.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: 9039042192a8638e45c5fd13791563a01312751d


---

# <a name="balance-sheet-financial-reports"></a>Balance sheet financial reports

This article describes the default reports for balance sheets. It also describes the building blocks that are associated with these reports. 

<a name="default-balance-sheet-reports"></a>Default balance sheet reports
-----------------------------

There are two default balance sheet reports. On one report, the sections are stacked. On the other report, the sections are side by side.

| Default report                       | What it does                                                                                                                           |
|--------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Balance Sheet – Default              | Provides a view of the organization's financial position for the year.                                                                 |
| Side by Side Balance Sheet – Default | Provides a view of the organization's financial position for the year. Assets and liability and shareholder’s equity are side by side. |

## <a name="building-blocks"></a>Building blocks
The balance sheet financial reports use the following building blocks.

| Default report                       | Row definition                       | Column definition             |
|--------------------------------------|--------------------------------------|-------------------------------|
| Balance Sheet - Default              | Balance Sheet - Default              | YTD and Variance - Default    |
| Side by Side Balance Sheet – Default | Side by Side Balance Sheet – Default | Year to Date Column - Default |

### <a name="row-definition"></a>Row definition

The row definitions for both balance sheet reports contain sections for each part of a traditional balance sheet. The side-by-side report includes a column break, so that liability and the owner’s equity appear next to assets. The Main Account Category dimension is used to build both row definitions. Therefore, anyone can generate the reports without having to make any modifications.

### <a name="column-definition"></a>Column definition

The column definitions contain different types of columns to provide different levels of detail and financial data.

-   **YTD and Variance – Default column types:**
    -   **DESC** – The description from the row definition
    -   **FD** – Year-to-date financial data for the current year
    -   **FD** – Year-to-date financial data for the last year
    -   **CALC** – The variance from subtracting last year from this year

<!-- -->

-   **Year to Date Column – Default:**
    -   **DESC** – The description from the row definition
    -   **FD** – Year-to-date financial data for the current year

 

<a name="see-also"></a>See also
--------

[Financial reporting](financial-reporting-getting-started.md)

[View financial reports](view-financial-reports.md)

[Dynamics Financial Reporting Blog](http://blogs.msdn.com/b/dynamics_financial_reporting/)




<!--HONumber=Feb17_HO3-->


