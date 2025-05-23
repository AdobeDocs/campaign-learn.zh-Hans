---
title: Android 推送通知入门 - 简介
description: 本教程将指导您完成从 Adobe Campaign 发送推送通知以及在 Android™ 应用程序中接收这些通知所涉及的步骤。
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noCatalog
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
source-git-commit: 116a24a8aa123f615e08fa4ebd187b3c4c460ba2
workflow-type: tm+mt
source-wordcount: '314'
ht-degree: 100%

---

# Android 推送通知入门 - 简介

通过 Adobe Campaign，您可以向 [!DNL iOS] 和 [!DNL Android™] 移动设备发送个性化的分段 [!DNL push] 通知。本教程将指导您完成将 [!DNL push] 通知从 Adobe Campaign 发送到 [!DNL Android™] 应用程序时涉及的步骤。

## 先决条件

在开始之前，您必须具备以下条件：

1) **Android™ 移动应用程序**

   本教程不包含设置移动应用程序所需的详细步骤。您必须具有集成了 [!DNL Campaign SDK] 的 **[!DNL Android™]移动应用程序**。

   您可以在产品文档中找到所需步骤的详细说明：

   [将 Campaign SDK 集成到移动应用程序](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=zh-Hans)

2) 已安装 **[!DNL Mobile App channel]软件包**

   必须在 [!DNL Campaign] 实例上安装 [!DNL Mobile App channel] 软件包。以下视频介绍如何检查是否在实例上安装了 [!DNL Mobile App channel]，如果未安装，应如何安装。

>[!VIDEO](https://video.tv.adobe.com/v/340421?quality=12&learn=on&captions=chi_hans){transcript=true}

## 教程概述

目的是向 [!DNL Neotrip] [!DNL Android™] 移动应用程序的订户发送个性化促销 [!DNL push] 通知。使用 [!DNL Campaign SDK] 配置 [!DNL Neotrip] 应用程序，并在 [!DNL Campaign] 实例上激活 [!DNL Mobile App channel]。

需要以下配置步骤：

### 步骤 1：扩展应用程序订阅模式以个性化 [!DNL push] 通知

要个性化 [!DNL push] 通知，您必须先[扩展应用程序订阅模式](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)。这样系统便可存储用户订阅服务时从应用程序收到的个性化值。

### 步骤 2：在 Campaign 中配置 Android™ 服务并创建移动应用程序

接下来，[必须配置 Android™ 服务，并在 Campaign 中创建移动应用程序](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md)。在此步骤中，[!DNL Neotrip] 应用程序被定义为推送通知的目标。

### 步骤 3：配置并发送推送通知

现在，推送通知已准备就绪，可[配置并发送](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md)。

## 启动教程

步骤 1：[扩展应用程序订阅模式](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
