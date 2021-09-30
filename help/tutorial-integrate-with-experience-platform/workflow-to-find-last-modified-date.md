---
title: 创建导出工作流（第1部分） — 查找收件人列表的上次修改日期
description: 在“创建导出工作流”教程的第一部分中，了解如何创建工作流，以查找从Experience Platform区段创建的收件人列表的上次修改日期。
feature: Data Import/Export, Workflows
kt: 8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: c685927a01d08ae6533399ad2466967c6cd3f9fd
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# 创建导出工作流（第1部分） — 查找收件人列表的上次修改日期

在“创建导出工作流”教程的第一部分中，了解如何创建工作流，以查找从Experience Platform区段创建的收件人列表的上次修改日期。

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12)

## 资产

JavaScript建立日期范围：

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## 下一个视频

[创建导出工作流（第2部分） — 提取、格式化数据并将其保存到外部帐户](extract-format-save-data-to-external-account.md)
