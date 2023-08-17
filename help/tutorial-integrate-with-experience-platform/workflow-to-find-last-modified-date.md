---
title: 创建导出工作流（第 1 部分） - 查找收件人列表的上次修改日期
description: 在“创建导出工作流”教程的第一部分中，了解如何创建工作流，以查找从 Experience Platform 区段创建的收件人列表的上次修改日期。
feature: Data Management, Workflows
jira: KT-8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
source-git-commit: a6b4e7f12c6565bcef644705b23f96803c5b6f85
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---

# 创建导出工作流（第 1 部分） - 查找收件人列表的上次修改日期

在“创建导出工作流”教程的第一部分中，了解如何创建工作流，以查找从 Experience Platform 区段创建的收件人列表的上次修改日期。

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12&learn=on)

## 资产

JavaScript 建立日期范围：

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

[创建导出工作流（第 2 部分）- 提取、格式化数据并将其保存到外部帐户](extract-format-save-data-to-external-account.md)
