---
title: 创建批准和验证工作流——简介
description: 了解如何配置不同的批准验证工作流。
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Intermediate
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 4d21755204c22fbeb4ac3a2916e9ee68cd2e0f9a
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%

---

# 创建批准和验证工作流——简介

Adobe Campaign 为营销人员提供了多个选项，用于审核和提供投放内容、活动目标、数据提取和预算批准。了解如何[管理批准](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md)。

## 先决条件 {#prerequisite}

在启用批准步骤之前，营销团队必须定义审阅人：

* 批准活动中的 Adobe Campaign 审阅人角色可以是单个审阅人（操作员）或一组审阅人（操作员角色）。
* 要使活动开发人员能够选择审阅人作为活动或投放中的批准者，必须由管理员在 Adobe Campaign 中配置审阅人和审阅人组。

## 配置批准 {#configuring-approvals}

1. [为营销活动配置批准](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md)：如果活动工作流中所有投放都设定同一组审阅人，那么您要在活动级别设置批准和审阅人来应用活动批准功能。执行工作流后，审批任务和审阅人会被向下推送到工作流的每个投放活动中。
2. [为投放配置批准](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md)：您还可以在投放级别设置批准。如果投放批准步骤及审阅人与活动批准步骤及审阅人不同，那么投放设置会覆盖活动设置。
3. [在工作流中创建批准流程](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md)：批准活动允许在工作流中创建批准流程。如此便可以在启动投放之前批准定位选择逻辑。如有必要，您还可以在工作流的多个级别进行批准。

有关更多信息，请参阅[文档](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=zh-Hans)。
