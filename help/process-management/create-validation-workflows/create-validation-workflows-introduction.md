---
title: 创建验证工作流 - 简介
description: 了解如何配置不同的批准验证工作流。
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: f25e3e7553d23aacf96c0f05e1ad78ee783192ff
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 66%

---

# 创建验证工作流 — 简介

Adobe Campaign 为营销人员提供了多个选项，用于审核和提供投放内容、活动目标、数据提取和预算批准。

## 先决条件 {#prerequisite}

在启用批准步骤之前，营销团队必须定义审阅人：

* 批准活动中的 Adobe Campaign 审阅人角色可以是单个审阅人（操作员）或一组审阅人（操作员角色）。
* 要使活动开发人员能够选择审阅人作为活动或投放中的批准者，必须由管理员在 Adobe Campaign 中配置审阅人和审阅人组。

## 配置批准 {#configuring-approvals}

Campaign提供三个不同的批准级别：

1. [配置促销活动的批准](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md):如果营销活动工作流中所有投放都有相同的审阅人集，请通过在营销活动级别设置批准和审阅人来应用营销活动批准功能。 执行工作流后，审批任务和审阅人会被向下推送到工作流的每个投放活动中。
2. [配置投放的批准](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md):您还可以在投放级别设置批准。 如果投放批准步骤及审阅人与活动批准步骤及审阅人不同，那么投放设置会覆盖活动设置。
3. [在工作流中创建批准流程](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md):批准活动允许在工作流中创建批准流程。 如此便可以在启动投放之前批准定位选择逻辑。如有必要，您还可以在工作流的多个级别进行批准。

有关更多信息，请参阅 [文档](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=zh-Hans).
