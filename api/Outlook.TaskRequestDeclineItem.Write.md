---
title: TaskRequestDeclineItem.Write event (Outlook)
ms.prod: outlook
api_name:
- Outlook.TaskRequestDeclineItem.Write
ms.assetid: e0abe283-c3f4-fd1a-7a41-8b1dd0f6c161
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# TaskRequestDeclineItem.Write event (Outlook)

Occurs when an instance of the parent object is saved, either explicitly (for example, using the  **[Save](Outlook.TaskRequestDeclineItem.Save.md)** or **[SaveAs](Outlook.TaskRequestDeclineItem.SaveAs.md)** methods) or implicitly (for example, in response to a prompt when closing the item's inspector).


## Syntax

_expression_. `Write`( `_Cancel_` )

_expression_ A variable that represents a [TaskRequestDeclineItem](Outlook.TaskRequestDeclineItem.md) object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Cancel_|Required| **Boolean**| (Not used in VBScript). **False** when the event occurs. If the event procedure sets this argument to **True**, the save operation is not completed.|

## Remarks

In Microsoft Visual Basic Scripting Edition (VBScript), if you set the return value of this function to  **False**, the save operation is not completed.


## See also


[TaskRequestDeclineItem Object](Outlook.TaskRequestDeclineItem.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]