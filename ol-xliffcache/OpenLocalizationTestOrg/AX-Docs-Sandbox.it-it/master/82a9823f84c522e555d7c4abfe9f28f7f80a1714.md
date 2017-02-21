---
title: Hybrid customer orders
description: A hybrid customer order is a single order, which contains products that can be carried out of the store by the customer, as well as products that will be picked up or shipped later.
author: josaw1
manager: AnnBe
ms.date: 2016-12-02 19 - 53 - 25
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
audience: Application User
ms.search.scope: Operations
ms.custom: 261164
ms.assetid: bbbc6ca7-8321-446d-8800-f2c2aae6cac1
ms.search.region: global
ms.search.industry: Retail
ms.author: anpurush
ms.dyn365.ops.intro: Nov-16
ms.dyn365.ops.version: Version 1611
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: 82a9823f84c522e555d7c4abfe9f28f7f80a1714


---

# <a name="hybrid-customer-orders"></a>Hybrid customer orders

A hybrid customer order is a single order, which contains products that can be carried out of the store by the customer, as well as products that will be picked up or shipped later.

In Microsoft Dynamics 365 for Operations - Retail, you can select either carry out all products or carry out selected products for a customer order. The product lines that are marked as carry out are automatically invoiced after the order is created, similarly this is the same for an order that is to be picked-up after the order is created. The amount due on hybrid orders is determined by adding the deposit percentage on pick and ship product lines with the full amount of the carry out lines. For hybrid orders, the system switches between customer order mode and cash and carry mode as follows:

-   If all products in the cart are set to **Carry out delivery**, the order will be handled as a Cash and Carry transaction.
-   If any or all lines in the cart are set to either **Pick** or **ship delivery**, the order will be handled as a Customer order transaction.

If a cart line is selected and **Pick selected**, **Ship selected**, or **Carry out selected** is selected, only the specific cart line is set with that delivery method. In that case, the downstream flow of the operation continues as usual. However, if **Pick selected**, **Ship selected**, or **Carry out selected** is selected without a cart line being selected, a new page opens that lists all the cart lines. On that screen, you can select multiple lines at once for setting the delivery method. When you use that method for selecting lines, any previous delivery method that has been assigned to the line will be overridden.

<a name="see-also"></a>See also
--------

[Customer orders overview](customer-orders-overview.md)




<!--HONumber=Feb17_HO3-->


