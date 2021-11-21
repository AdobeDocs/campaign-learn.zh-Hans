---
title: 故障排除控制面板
description: 了解如何对控制面板进行故障排除
feature: Control Panel
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 0dca4676-2d5e-411b-9fdf-fbfd1081cb0e
source-git-commit: f7cb6c57d9cd6b00def9f0a4ccbcc94267f0d593
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 100%

---

# 对[!UICONTROL 控制面板]进行故障排除

了解如何对控制面板进行故障排除。

## 登录和主页

### 症状：无法登录 Experience Cloud

**要做什么：**
用户须找到其 IMS Org ID (xxx)。管理员须将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：Experience Cloud 主页中的用于访问[!UICONTROL 控制面板]的链接未向某个用户显示

**原因：**
用户只有在被添加为产品用户档案 _Campaign-xxx-Administrators/Admin_ 中的用户后，才会看到这些链接。

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：实例未在[!UICONTROL 控制面板]中列出

**原因：**
最可能的原因是，对于缺少的实例，须将用户在产品用户档案 _Campaign-xxx-Administrators/Admin_ 中添加为&#x200B;*用户*

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，他们须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*查找 IMS Org ID（00:26 分）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何将管理员添加到产品用户档案管理员中，以便能够使用[!UICONTROL 控制面板]（01:03 分）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理权限[!UICONTROL （控制面板）]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL 将]您连接到 SFTP 服务器时的 IP 地址添加到允许列表
* 须在 Adobe Campaign 中注册的私钥/公钥对
* 要直接连接到 SFTP 服务器，您还需要有 SFTP 客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
