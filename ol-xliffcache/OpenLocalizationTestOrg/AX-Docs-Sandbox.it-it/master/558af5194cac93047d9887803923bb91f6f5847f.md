---
title: Cost object dimensions
description: When you analyze costs, you use cost element dimensions to determine where costs flow to. You use cost object dimensions to determine where you should assign costs. This topic provides information about cost object dimensions.
author: YuyuScheller
manager: AnnBe
ms.date: 2016-11-01 13 - 17 - 57
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: CAMDimensionMember
audience: Application User
ms.search.scope: Operations
ms.custom: 223174
ms.assetid: 976fd34d-d322-4835-9e1f-46836a6ee444
ms.search.region: global
ms.search.industry: Manufacturing
ms.author: yuyus
ms.dyn365.intro: Nov-16
ms.dyn365.version: Version 1611
translationtype: Human Translation
ms.sourcegitcommit: 2b7f7f6979ca245a01ac65958d07084879fea5c4
ms.openlocfilehash: 558af5194cac93047d9887803923bb91f6f5847f


---

# <a name="cost-object-dimensions"></a>Cost object dimensions

When you analyze costs, you use cost element dimensions to determine where costs flow to. You use cost object dimensions to determine where you should assign costs. This topic provides information about cost object dimensions.

A cost object can be any type of object that you want to estimate, allocate costs to, or measure directly. Typical cost objects include products, projects, resources, departments, cost centers, and geographical regions. Management uses cost objects to quantify costs and also to drive profitability analysis.

## <a name="cost-object-dimensions-and-cost-object-dimension-members"></a>Cost object dimensions and cost object dimension members
Cost objects are known as *cost object dimensions*. After you’ve decided which entity the cost object dimension should refer to, you must specify the individual dimension values or import them into Cost accounting from other source systems. These individual dimension values are known as *cost object dimension members*. For example, you want to use the financial dimension that is named Cost center as the cost object dimension. To see how costs flow to the individual cost centers, you must import the cost object dimension members. In this case, the cost object dimension members are the actual cost centers, such as Sales, Production, Administration, and Geographic locations. The following screenshot shows an example of Cost Centers as the cost object dimension with its actual cost centers as cost object dimension members. [![cost-object-dimensions](./media/cost-object-dimensions.png)](./media/cost-object-dimensions.png)

## <a name="import-cost-object-dimension-members-through-data-connectors"></a>Import cost object dimension members through data connectors
To make the import of cost object dimension members easier, you use data connectors to retrieve the values from the entities that you want to use as cost object dimensions. You can use either the pre-built data connectors or custom data connectors that you build.




<!--HONumber=Feb17_HO3-->


