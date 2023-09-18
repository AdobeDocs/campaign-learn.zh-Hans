---
title: 创建导出工作流（第 2 部分）- 提取、格式化数据并将其保存到外部帐户
description: 在“创建导出工作流”教程的第二部分中，您将了解如何设置导出数据的格式，以及如何将数据保存到外部帐户。
feature: Data Management, Workflows
jira: KT-8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: a6b4e7f12c6565bcef644705b23f96803c5b6f85
workflow-type: ht
source-wordcount: '0'
ht-degree: 100%

---

# 创建导出工作流（第 2 部分）：提取数据、设置数据格式并将其保存到外部帐户

在“创建导出工作流”教程的第二部分中，您将了解如何设置导出数据的格式，以及如何将数据保存到外部帐户。

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12&learn=on)

## 资产

JavaScript：保存日期

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
