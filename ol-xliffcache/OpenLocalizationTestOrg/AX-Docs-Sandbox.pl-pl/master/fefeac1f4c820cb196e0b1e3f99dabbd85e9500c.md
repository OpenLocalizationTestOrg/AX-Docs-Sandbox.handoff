---
# required metadata

title: API, class, and table reference | Microsoft Docs
description: This topic describes where to find API documentation in Visual Studio and on the wiki.
author: annbe
manager: AnnBe
ms.date: 2016-03-09 00:09:13
ms.topic: 
ms.prod: 
ms.service: 
ms.technology: 

# optional metadata

# keywords: 
# ROBOTS: 
audience: Developer
# ms.devlang: 
ms.reviewer: 61
ms.suite: Released- Dynamics AX 7.0.0
# ms.tgt_pltfrm: 
ms.custom: 63853
ms.assetid: 12f6c8ac-f43e-4536-ac99-5e0af7161425
# ms.region: 
# ms.industry: 
ms.author: RobinARH

---

# API, class, and table reference

Application classes and tables
------------------------------

### Application class and table documentation is in Visual Studio

You can find documentation for the Application classes in Microsoft Visual Studio by searching for the application programming interface (API) in Application Explorer and then displaying the code. You can find additional metadata about the API in the **Properties** window.

### Programming with application tables and classes

Application tables are being similar to application classes, but with the following differences from classes:

-   Tables are persistent.
-   Table fields are always public.
-   A table almost always corresponds to a real object.
-   The definition of a table must sometimes be erased if you later want another table to extend it.

### Design Pattern of private new in application classes

All application classes are under Application Explorer &gt; Classes. Every application class has the constructor method named `new`, even if the class has no new node in the AOT. If the class has no explicit new node, the implicit `new` method is public. A design pattern that is sometimes used in the application classes is to declare the explicit `new` constructor method as `private`. Then a `public static` method is added to call the `new` method. The static method can restrict or control the call the `new` method based on various conditions, if necessary.

## System classes and tables
### System API, class, and table documentation is on the Help wiki

Documentation for the classes and functions that are listed under **System Documentation** in Application Explorer is available on the Help wiki.

## X++ compiletime functions
[X++ compile-time functions](http://ax.help.dynamics.com/en/wiki/x-compile-time-functions/)

## X++ runtime functions
[X++ run-time functions](http://ax.help.dynamics.com/en/wiki/x-string-run-time-functions/):

-   [X++ container run-time functions](http://ax.help.dynamics.com/en/wiki/x-container-run-time-functions/)
-   [X++ business run-time functions](http://ax.help.dynamics.com/en/wiki/x-business-run-time-functions/)
-   [X++ conversion run-time functions](http://ax.help.dynamics.com/en/wiki/x-conversion-run-time-functions/)
-   [X++ date run-time functions](http://ax.help.dynamics.com/en/wiki/x-date-run-time-functions/)
-   [X++ math run-time functions](http://ax.help.dynamics.com/en/wiki/x-math-run-time-functions/)
-   [X++ reflection run-time functions](http://ax.help.dynamics.com/en/wiki/x-reflection-run-time-functions/)
-   [X++ session run-time functions](http://ax.help.dynamics.com/en/wiki/x-session-run-time-functions/)
-   [X++ string run-time functions](http://ax.help.dynamics.com/en/wiki/x-string-run-time-functions/)

## System tables
[System tables](http://ax.help.dynamics.com/en/wiki/system-tables/)

## System classes
-   [A classes](http://ax.help.dynamics.com/en/wiki/a-classes/)
-   [B classes](http://ax.help.dynamics.com/en/wiki/b-classes/)
-   [C classes](http://ax.help.dynamics.com/en/wiki/c-classes/)
-   [D classes](http://ax.help.dynamics.com/en/wiki/d-classes/)
-   [E classes](http://ax.help.dynamics.com/en/wiki/e-classes/)
-   [F classes: FieldBinding to FormBuildAnimateControl](http://ax.help.dynamics.com/en/wiki/fieldbinding-classes/)
-   [F classes: FormBuildButtonControl to FormBuildFastTabSummarySeparator](http://ax.help.dynamics.com/en/wiki/FormBuildButtonControl-classes/)
-   [F classes: FormBuildFilterPaneControl to FormBuildRealControl](http://ax.help.dynamics.com/en/wiki/FormBuildFilterPaneControl-classes/)
-   [F classes: FormBuildReferenceControl to FormButtonSeparatorControl](http://ax.help.dynamics.com/en/wiki/FormBuildReferenceControl-classes/)
-   [F classes: FormChangeTracker to FormControlEventArgs](http://ax.help.dynamics.com/en/wiki/FormChangeTracker-classes/)
-   [F classes: FormDataObject to FormFastTabHeaderControl](http://ax.help.dynamics.com/en/wiki/FormDataObject-classes/)
-   [F classes: FormFastTabSummarySeparator to FormGridControl](http://ax.help.dynamics.com/en/wiki/FormFastTabSummarySeparator-classes/)
-   [F classes: FormGroupControl to FormIntControl](http://ax.help.dynamics.com/en/wiki/FormGroupControl-classes/)
-   [F classes: FormListBoxControl to FormNotifyEventArgs](http://ax.help.dynamics.com/en/wiki/FormListBoxControl-classes/)
-   [F classes: FormObject to FormRealControl](http://ax.help.dynamics.com/en/wiki/FormObject-classes/)
-   [F classes: FormReferenceControl to FormStringControl](http://ax.help.dynamics.com/en/wiki/FormReferenceControl-classes/)
-   [F classes: FormTabControl to FormWindowControl](http://ax.help.dynamics.com/en/wiki/FormTabControl-classes/)
-   [G classes](http://ax.help.dynamics.com/en/wiki/g-classes/)
-   [H classes](http://ax.help.dynamics.com/en/wiki/h-classes/)
-   [I classes](http://ax.help.dynamics.com/en/wiki/i-classes/)
-   [J classes](http://ax.help.dynamics.com/en/wiki/j-classes/)
-   [K classes](http://ax.help.dynamics.com/en/wiki/k-classes/)
-   [L classes](http://ax.help.dynamics.com/en/wiki/l-classes/)
-   [M classes](http://ax.help.dynamics.com/en/wiki/m-classes/)
-   [N classes](http://ax.help.dynamics.com/en/wiki/n-classes/)
-   [O classes](http://ax.help.dynamics.com/en/wiki/o-classes/)
-   [P classes](http://ax.help.dynamics.com/en/wiki/p-classes/)
-   [Q classes](http://ax.help.dynamics.com/en/wiki/q-classes/)
-   [R classes](http://ax.help.dynamics.com/en/wiki/r-classes/)
-   [S classes](http://ax.help.dynamics.com/en/wiki/s-classes/)
-   [T classes](http://ax.help.dynamics.com/en/wiki/t-classes/)
-   [U classes](http://ax.help.dynamics.com/en/wiki/u-classes/)
-   [V classes](http://ax.help.dynamics.com/en/wiki/v-classes/)
-   [W classes](http://ax.help.dynamics.com/en/wiki/w-classes/)
-   [X classes](http://ax.help.dynamics.com/en/wiki/x-classes/)

## Additional resources
-   Additional help is available as task guides inside Dynamics 365 for Operations. To access task guides, click the Help button on any page.
-   For information about Microsoft Dynamics 365 for Operations training, see [Microsoft eLearning](https://mbspartner.microsoft.com/AX/LearningPlans) (requires a CustomerSource account).


