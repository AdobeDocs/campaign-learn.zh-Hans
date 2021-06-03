---
title: Android 推送通知入门 - 简介
description: 本教程将指导您完成从Adobe Campaign发送推送通知以及在Android™应用程序中接收这些通知所涉及的步骤。
feature: 推送
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 41%

---

# Android 推送通知入门 - 简介

通过 Adobe Campaign，您可以向 [!DNL iOS] 和 [!DNL Android™] 移动设备发送个性化的分段 [!DNL push] 通知。本教程将指导您完成将[!DNL push]通知从Adobe Campaign发送到[!DNL Android™]应用程序时涉及的步骤。

## 先决条件

在开始之前，您必须具备以下条件：

1) **Android™移动应用程序**

   本教程不涵盖设置移动应用程序所需的详细步骤。您必须具有集成了[!DNL Campaign SDK]的&#x200B;**移动应用程序。**[!DNL Android™]

   您可以在产品文档中找到所需步骤的详细说明：

   [将 Campaign SDK 集成到移动应用程序](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=zh-Hans)

2) **[!DNL Mobile App channel]软件包已安装**

   [!DNL Mobile App channel]包必须安装在[!DNL Campaign]实例上。 以下视频介绍如何检查是否在实例上安装了 [!DNL Mobile App channel]，如果未安装，则介绍如何安装。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 教程概述

其目标是向[!DNL Neotrip] [!DNL Android™]移动应用程序的订户发送个性化促销[!DNL push]通知。 使用[!DNL Campaign SDK]配置[!DNL Neotrip]应用程序，并在[!DNL Campaign]实例上激活[!DNL Mobile App channel]。

需要以下配置步骤：

### 步骤 1：扩展应用程序订阅模式以个性化 [!DNL push] 通知

要个性化[!DNL push]通知，您必须先[扩展应用程序订阅模式](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)。 利用，系统可存储用户订阅服务时从应用程序收到的个性化值。

### 步骤2:在Campaign中配置Android™服务并创建移动应用程序

接下来，必须配置[Android™服务，并在Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md)中创建移动应用程序。 在此步骤中，[!DNL Neotrip]应用程序被定义为推送通知的目标。

### 步骤 3：配置并发送推送通知

现在，推送通知已准备就绪，可配置并发送](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md)。[

## 启动教程

步骤 1：[扩展应用程序订阅模式](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
