---
title: 创建定期投放和连续电子邮件投放
description: 了解如何设置循环和连续投放，并了解两种方法之间的差异。
feature: Workflows
jira: KT-7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Intermediate
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
TQID: https://experienceleague.adobe.com/pdYTRO3rBq3BdS-WUGcx3POKjD6V4lH1dco4W9L6FwM
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 233
ht-degree: 100%

---

# 创建定期投放和连续电子邮件投放

本教程介绍了如何设置循环和连续投放，以及这两种方法之间的差异。

## 循环和连续投放跟踪 {#recurring-and-continuous-delivery-tracking}

循环投放和连续投放在管理联系人数据的方式上有所不同：

* **连续投放**&#x200B;允许您向现有投放添加新收件人，并避免在每次添加新收件人时都创建投放。 您可以直接在活动工作流中更新创意，活动工作流会更新投放模板资源文件夹中的模板。

  连续投放会创建单个投放和投放日志 (broadLog) 以及跟踪日志，日志引用投放，因此每执行一次投放都会添加日志。

![连续投放](/help/assets/delivery_continuous.jpg)

* 每次执行&#x200B;**循环投放**&#x200B;时，都会创建一个投放实例。 例如，如果工作流计划每周运行一次，那么一年后将产生 52 次投放。 它还意味着广义日志和跟踪日志会按投放实例进行分隔。

![循环投放](/help/assets/delivery_recurring.jpg)

## 如何设置循环投放 {#how-to-set-up-a-recurring-delivery}

此视频介绍了如何配置循环投放和调度程序活动。

>[!VIDEO](https://video.tv.adobe.com/v/3446884?captions=chi_hans&quality=12&learn=on){transcript=true}

## 如何设置连续投放 {#how-to-set-up-a-continuous-delivery}

本视频演示了如何使用增量查询配置连续投放。

>[!VIDEO](https://video.tv.adobe.com/v/3444577?captions=chi_hans&quality=12&learn=on){transcript=true}
