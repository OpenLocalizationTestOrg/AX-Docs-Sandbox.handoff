---
title: Task Single form pattern
description: This article provides information about the Task Single form pattern. This pattern was previously used to present data that users would perceive as originating from a single data source that had multiple records.
author: jasongre
manager: AnnBe
ms.date: 2015-12-02 23 - 39 - 07
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.reviewer: annbe
ms.search.scope: AX 7.0.0, Operations
ms.custom: 14634
ms.assetid: e56a8fb6-ce06-48ab-815c-e8a3a1c5e60c
ms.search.region: Global
ms.author: jasongre
ms.dyn365.ops.intro: Feb-16
ms.dyn365.ops.version: AX 7.0.0
translationtype: Human Translation
ms.sourcegitcommit: 163dd8dd3f119eef45b9bc6d5313f48ef0adc222
ms.openlocfilehash: 065b5dc88279f90bcec65962a8da6b376b3c2b85


---

# <a name="task-single-form-pattern"></a>Task Single form pattern

This article provides information about the Task Single form pattern. This pattern was previously used to present data that users would perceive as originating from a single data source that had multiple records.

<a name="usage"></a>Usage
-----

This type of form was used when you wanted to present data that users will perceive as originating from a single data source with multiple records. This isn't a recommended pattern for new forms. No new forms should be created that use this pattern. This pattern will provide structure and stability for legacy forms, and will also provide a migration path to more modern form patterns.

## <a name="wireframe"></a>Wireframe
[![Wireframe](./media/tasksingle1-1024x577.png)](./media/tasksingle1.png)

## <a name="pattern-changes"></a>Pattern changes
Here are the main changes to this pattern since Microsoft Dynamics AX 2012:

-   The form opens in view mode.
-   Commands have been moved to the standard ActionPane from a Toolbar (ActionPane strips).
-   The **Overview** label on the first tab has been changed to **List**.
-   The content of the tab container uses dynamic columns for a responsive layout.

## <a name="model"></a>Model
### <a name="high-level-structure"></a>High-level structure

Design

ActionPane (Action Pane)

*CustomFilter (Group) \[Optional\]*

Tab (Tab)

Overview (TabPage)

Grid (Grid)

*RowExtension (Group) \[Optional\]*

General (TabPage, repeats 0..N)

*FooterGroup (Group) \[Optional\]*

### <a name="core-components"></a>Core components

1.  Apply the TaskSingle pattern on **Form.Design**.
2.  Address BP Warnings:
    1.  **Design.Caption** isn't empty.
    2.  The form must be referenced by at least one menu item.
    3.  **TabPage.Caption** isn't empty.
    4.  **TabPage.DataSource** isn't empty.
    5.  **StaticText.Text** isn't empty.

### <a name="related-patterns"></a>Related patterns

-   [Task Double](task-double-form-pattern.md)

### <a name="commonly-used-subpatterns"></a>Commonly used subpatterns

-   [Custom Filter Group](custom-filter-group-subpattern.md)
-   [Fields and Field Groups](fields-field-groups-subpattern.md)
-   [Toolbar and List](toolbar-list-subpattern.md)
-   [Toolbar and Fields](toolbar-fields-subpattern.md)

## <a name="ux-guidelines"></a>UX guidelines
The verification checklist shows you the steps for manually verifying that the form complies with UX guidelines. This checklist doesn't include any guidelines that will be enforced automatically through the development environment. Open the form in the browser, and walk through these steps. **Standard form guidelines:**

-   Standard form guidelines have been consolidated into the Microsoft Dynamics AX [General Form Guidelines](general-form-guidelines.md)document.

**Task Single guidelines:**

-   The **Overview** tab is the first tab and is active when the form is opened.
-   The **General** tab must be the second tab and must have the label **General**.

## <a name="examples"></a>Examples
Form: **LedgerJournalTable** [![Task Single example 1](./media/tasksingle2-1024x669.png)](./media/tasksingle2.png) [![Task Single example 2](./media/tasksingle3-1024x424.png)](./media/tasksingle3.png)

## <a name="appendix"></a>Appendix
### <a name="frequently-asked-questions"></a>Frequently asked questions

This section will have answers to frequently asked questions that are related to this guideline/pattern.

### <a name="open-issues"></a>Open issues

-   None

### <a name="ax-2012-content"></a>AX 2012 content

[![AX 2012 visual example](./media/tasksingle4.png)](./media/tasksingle4.png)




<!--HONumber=Feb17_HO3-->


