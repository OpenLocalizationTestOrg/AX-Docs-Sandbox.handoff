---
title: Configure a conditional decision in a workflow
description: Use the following procedure to configure the properties of a conditional decision.
author: sericks007
manager: AnnBe
ms.date: 2016-09-30 15 - 55 - 34
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
audience: Application User, IT Pro
ms.search.scope: AX 7.0.0, Operations, Core
ms.custom: 195703
ms.assetid: 25acaadc-9297-49c3-a5c1-58f631b87c27
ms.search.region: Global
ms.author: donaldc
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: d9e5f89115da09f5f957d4f161783f78668a2f35


---

# <a name="configure-a-conditional-decision-in-a-workflow"></a>Configure a conditional decision in a workflow

Use the following procedure to configure the properties of a conditional decision.

A conditional decision is a point at which a workflow divides into two branches. To configure a conditional decision, in the workflow editor, right-click the conditional decision, and then click **Properties** to open the **Properties** form.

## <a name="name-a-decision"></a>Name a decision
Follow these steps to enter a name for a conditional decision.
1.  In the left pane, click **Basic Settings**.
2.  In the **Name** field, enter a unique name for the conditional decision.

## <a name="set-conditions"></a>Set conditions
The system determines which branch is used by evaluating the submitted document to determine whether it meets specific conditions.
1.  In the left pane, click **Basic Settings**.
2.  Click **Add condition**.
3.  Enter a condition.
4.  Enter additional conditions, if they are required.
5.  To verify that the conditions that you entered are configured correctly, complete the following steps:
    1.  Click **Test** to open the **Test workflow condition** form.
    2.  Select a record in the **Validate condition** area of the form.
    3.  Click **Test**. The system evaluates the record to determine whether it meets the conditions that you defined.
    4.  Click **OK** or **Cancel** to return to the **Properties** form.






<!--HONumber=Feb17_HO3-->


