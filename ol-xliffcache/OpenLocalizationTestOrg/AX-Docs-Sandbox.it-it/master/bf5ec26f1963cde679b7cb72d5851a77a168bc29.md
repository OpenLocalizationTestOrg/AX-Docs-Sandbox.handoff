---
title: Benefit eligibility policies
description: This article provides information about benefit eligibility policies, which help you define who is eligible for specific benefits.
author: rschloma
manager: AnnBe
ms.date: 2015-12-04 02 - 16 - 06
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: HcmBenefitEligibilityDetail, SysPolicyListPage, SysPolicySourceDocumentRuleType
audience: Application User
ms.reviewer: rschloma
ms.search.scope: AX 7.0.0, Operations
ms.custom: 16441
ms.assetid: fcf6473f-c7f1-49f2-a32e-6ef5ee2c9101
ms.search.region: Global
ms.author: kherr
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: bf5ec26f1963cde679b7cb72d5851a77a168bc29


---

# <a name="benefit-eligibility-policies"></a>Benefit eligibility policies

This article provides information about benefit eligibility policies, which help you define who is eligible for specific benefits.

When you create benefits, you decide which benefits will be available to which employees. The following table shows examples of benefits that you might make available to specific employees.

| Benefit          | Who the benefit is available to |
|------------------|---------------------------------|
| Health insurance | All employees                   |
| Mobile phone     | Sales staff, executives         |
| Parking passes   | Executives                      |

The following components in are used to create eligibility policies:

-   Policy rule types
-   Benefit eligibility policies

Policy rule types define the query parameters that are used when you develop specific policy rules. After you create policy rule types, you can create benefit eligibility policies. The policies let you create a collection of rules that apply to one or more legal entities. Within each policy, you can view any of the benefit eligibility policy rule types that you created earlier. You define the scope of the rule within the policy. For example, if you create a benefit eligibility policy rule type that is named **Executive**, you can specify what the rule is within that policy. In this example, the rule might state that any job title that contains the word “executive” should be included in the rule. After you've defined the parameters of the rule or rules that are included in the policy, you can assign a specific rule to the benefit.

<a name="see-also"></a>See also
--------

[Defining and managing a benefit program](manage-benefit-program.md)




<!--HONumber=Feb17_HO3-->


