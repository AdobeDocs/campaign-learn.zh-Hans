---
title: 创建导出工作流（第2部分） — 提取、格式化数据并将其保存到外部帐户
Description: In this second part of the Create an Export Workflow tutorial, you learn how to format the data for export and how to save the data to an external account. 
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: 9a75069ee3bb9352ba7fa5350eb54e421e9427c8
workflow-type: tm+mt
source-wordcount: '62'
ht-degree: 0%

---


# 创建导出工作流（第2部分）：提取数据、设置数据格式并将其保存到外部帐户

在创建导出工作流教程的第二部分中，您将学习如何设置导出数据的格式，以及如何将数据保存到外部帐户。

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12)

## 资产

JavaScript:保存日期

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


