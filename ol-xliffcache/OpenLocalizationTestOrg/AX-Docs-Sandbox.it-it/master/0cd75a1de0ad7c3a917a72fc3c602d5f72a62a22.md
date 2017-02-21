---
title: Reuse product configurations
description: "You can specify that you want to automatically reuse an existing configuration for a product. Then, when a user has completed a configuration session, the system verifies whether a configuration that matches the user’s selections already exists. If a matching configuration is found, the configuration ID, corresponding bill of materials (BOM), and route are reused."
author: YuyuScheller
manager: AnnBe
ms.date: 2016-10-07 08 - 36 - 48
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: PCProductConfigurationModelDetails
audience: Application User
ms.reviewer: YuyuScheller
ms.search.scope: AX 7.0.0, Operations
ms.custom: 201813
ms.assetid: 3caa6d94-856c-4426-81bd-e664cc54bb09
ms.search.region: Global
ms.search.industry: Manufacturing
ms.author: yuyus
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: 0cd75a1de0ad7c3a917a72fc3c602d5f72a62a22


---

# <a name="reuse-product-configurations"></a>Reuse product configurations

You can specify that you want to automatically reuse an existing configuration for a product. Then, when a user has completed a configuration session, the system verifies whether a configuration that matches the user’s selections already exists. If a matching configuration is found, the configuration ID, corresponding bill of materials (BOM), and route are reused.

<a name="requirements-for-reusing-configurations"></a>Requirements for reusing configurations
---------------------------------------

To enable configurations to be reused, you must specify the following information for the components and attributes on the **Product configuration model details** page:

-   **Components and subcomponents** – On the **General** FastTab, in the **Reuse configurations** field, select **Yes**.
-   **Attributes** – On the **Attributes** FastTab, select the **Include in reuse** option. This option appears only when the related component is enabled for reuse. If you don't select any attributes for reuse, the configuration is always reused, regardless of the user’s selections during a configuration session. The attribute values in the existing configuration must match the user’s selections. For example, if the user selects **Blue** as the color during a configuration session, the system verifies whether an existing configuration of the component has the color blue.

## <a name="resetting-configuration-reuse"></a>Resetting configuration reuse
When you reset configuration reuse, previously created configurations are no longer considered. You might want to reset configuration reuse if the BOM or route was changed, but no related attributes were changed. You reset configuration reuse on the **General** FastTab for the component.




<!--HONumber=Feb17_HO3-->


