---
title: 故障排除控制面板
description: 了解如何排查控制面板
feature: 控制面板
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: 4fc34f56e13c3df5f1c42c24c87a6c7c5caff04b
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 19%

---

# 故障排除[!UICONTROL 控制面板]

了解如何对控制面板进行故障诊断。

## 登录和主页

### 症状：无法登录Experience Cloud

**要做什么：**
用户必须找到其IMS组织ID(xxx)。管理员必须将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。 如果用户是所有实例的管理员，则必须将自己添加为用户。

### 症状：Experience Cloud主页中访问[!UICONTROL 控制面板]的链接不显示给用户

**原因：**
用户只有在将他们添加为产品用户档案Campaign-xxx-Administrators/Admin _的用户后，才会看到这些链接_。

**要做什么：**
管理员必须将用户添加到要管理的每个 _实例的产品用户档案Campaign-xxx-_  Admin中。如果用户是所有实例的管理员，则必须将自己添加为用户。

### 症状：[!UICONTROL 控制面板]中未列出实例

**原因：**
对于缺少的实例，最可能的 ** 用户必 _须添加为用户产品用户档案Campaign-xxx-_ Administrators/Admin

**要做什么：**
管理员必须将用户添加到要管理的每个 _实例的产品用户档案Campaign-xxx-_  Admin中。如果用户是所有实例的管理员，则必须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*查找 IMS Org ID（00:26 分钟）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何向产品配置文件管理员添加管理员，以便能够使 [!UICONTROL 用控制面板] （01:03分钟）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理控制面板的权 [!UICONTROL 限]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL 允] 许列出您连接到SFTP服务器的IP地址
* 必须在Adobe Campaign中注册的私钥/公钥对
* 要直接连接到SFTP服务器，您还需要SFTP客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
