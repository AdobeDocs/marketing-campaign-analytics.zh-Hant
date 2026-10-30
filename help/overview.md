---
title: Marketing Campaign Analytics指南
description: 瞭解如何使用Marketing Campaign Analytics衡量行銷活動，並跨所有管道整體最佳化規劃。
short-description: 瞭解如何使用Marketing Campaign Analytics衡量行銷活動，並跨所有管道整體最佳化規劃。
feature: Harmonized Data, Models, Plans
exl-id: 3427c338-f2a0-416b-bb4c-d8fef929c38a
autotag-review: '2026-05-01T09:02:01.855Z'
TQID: 'https://experienceleague.adobe.com/GoeY6zk9v3aRSfKJsRbvakvu2AV0jG4ggXqfGVZ-MK8'
product_v2:
  - id: b88c80e3-31df-4609-989d-d4dac0e6d973
    internal-label: Marketing Campaign Analytics
feature_v2:
  - id: a234aebd-3855-4376-a64d-29b38411e0c5
    internal-label: Marketing mix modeling
  - id: a567f0f7-0057-4079-8ded-5b24cc25af15
    internal-label: Harmonized data
  - id: d822825b-9821-40d5-9b0d-42a9e3f317c5
    internal-label: Plans
  - id: e0abf868-dae2-4c1c-83e9-b21799232845
    internal-label: Datasets
  - id: f40f1683-8300-4054-aab8-77da06ad63ff
    internal-label: Models
  - id: fbd94e4b-f9b8-42a4-8df5-3f917aabae24
    internal-label: Schemas
  - id: fe1c9ae8-a908-4ae1-a0b6-fcf35177b134
    internal-label: Marketing touch attribution
subfeature_v2:
  - id: a9505d76-24a1-4ffe-bd01-6ac32d5af453
    internal-label: Model insights
  - id: ba4fd72c-282e-4fb6-abc1-08e6fb87b2ad
    internal-label: Dataset rules
  - id: bc2f5225-03d4-4bc8-89ec-99d78c30e6dd
    internal-label: Conversions
  - id: c89e26b6-808d-4500-8b01-450a63466999
    internal-label: Build model
  - id: cb40363e-1205-4921-971c-9ee6bdb18329
    internal-label: Scoring data
  - id: b2d4aeb9-eabe-49f6-8edb-bb2862d5980b
    internal-label: Marketing touchpoints
  - id: b4655f7e-1a6e-4fa3-a7c5-3c34d4786e49
    internal-label: Harmonized fields
  - id: d4b8ba18-64c1-4413-be54-74405ec7f558
    internal-label: Dataset mapping
  - id: d7b067e6-4f39-41e9-a081-7650346a84cd
    internal-label: Build plans
  - id: b2520ae7-8f6c-4952-935e-aacc2c10256f
    internal-label: Compare plans
  - id: e6c284e0-b6e6-4f82-bf96-e96bb5157b90
    internal-label: Plan insights
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
topic_v2:
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
source-git-commit: 9d6bd798e97d36d49b7753dc9574b102efb3d6bf
workflow-type: tm+mt
source-wordcount: '424'
ht-degree: 0%
---
# Adobe Marketing Campaign Analytics指南

{{mm-mca-rebranding}}

本技術檔案指南提供Adobe **Marketing Campaign Analytics** （原稱Adobe **[!UICONTROL Mix Modeler]**）的自助協助。 Marketing Campaign Analytics是一種Adobe Experience Cloud應用程式，可跨所有管道（付費、贏取和擁有）來測量行銷活動及最佳化規劃。 Marketing Campaign Analytics是以Adobe Experience Platform為建置基礎。

## 從基礎知識開始

<table style="table-layout:fixed">
  <tr style="border: 0;">
    <td>
    <a href="/help/get-started/about.md"><img src="assets/whatis-mm.png"></a>
    <div><strong>快速入門</strong><br/>在Marketing Campaign Analytics的工作流程中取得和insight的概觀。</div>
    </td>
    <td>
    <a href="/help/ingest-data/overview.md"><img src="assets/data-ingestion-mm.png"></a>
    <div><strong>擷取資料</strong><br/>瞭解如何將事件和彙總或摘要資料擷取到Marketing Campaign Analytics。</div>
    </td>
    <td>
    <a href="/help/harmonize-data/overview.md"><img src="assets/plan-mm.png"/></a>
    <div><strong>協調資料</strong><br/>瞭解如何將彙總和事件資料同化為一致的資料檢視。 
    </div>
    </td>
    <td>
    <a href="/help/models/overview.md"><img src="assets/models-mm.png"></a>
    <div><strong>模型與計畫</strong><br/>訓練您的模型並為其評分，然後為您的行銷計畫使用深入分析。</div>
    </td>
  </tr>
  <tr style="border: 0;">
    <td align="center"><a href="/help/get-started/about.md"><img src="assets/learn-more-button.svg"></a></td>
    <td align="center"><a href="/help/ingest-data/overview.md"><img src="assets/learn-more-button.svg"></a></td>
    <td align="center"><a href="/help/harmonize-data/overview.md"><img src="assets/learn-more-button.svg"></a></td>
    <td align="center"><a href="/help/models/overview.md"><img src="assets/learn-more-button.svg"></a></td>
    </tr>
</table>


## 探索檔案

<table style="table-layout:fixed">
  <tr style="border: 0;">
    <td>
      <img src="assets/Data.svg" width="35px"><br/>
      <strong>擷取資料</strong><br/><a href="/help/ingest-data/overview.md">總覽</a> - <a href="/help/ingest-data/schemas.md">結構描述</a> - <a href="/help/ingest-data/datasets.md">資料集</a> 
    </td>
    <td>
      <img src="assets/DataCheck.svg" width="35px"><br/>
      <strong>協調資料</strong><br/><a href="/help/harmonize-data/overview.md">概觀</a> - <a href="/help/harmonize-data/fields.md">欄位</a> - <a href="/help/harmonize-data/dataset-rules.md">資料集規則</a> - <a href="/help/harmonize-data/marketing-touchpoints.md">行銷接觸點</a> - <a href="/help/harmonize-data/conversions.md">轉換</a> - <a href="/help/harmonize-data/usage-report.md">使用情況報告</a>  
    </td>
    <td>
      <img src="assets/FileGear.svg" width="35px"><br/>
      <strong>模型</strong><br/><a href="/help/models/overview.md">總覽</a> - <a href="/help/models/build.md">建立模型</a> - <a href="/help/models/insights.md">模型深入分析</a> - <a href="/help/models/scoring-data.md">使用評分資料</a>
    </td>
  </tr>
  <tr style="border: 0;">
    <td>
      <img src="assets/FileChart.svg" width="35px"><br/>
      <strong>計畫</strong><br/><a href="/help/plans/overview.md">計畫</a> - <a href="/help/plans/build.md">建置計畫</a> - <a href="/help/plans/compare.md">比較計畫</a> - <a href="/help/plans/build.md">計畫深入分析</a>
    </td>
    <td>
      <img src="assets/Dashboard.svg" width="35px"><br/>
      <strong>總覽</strong><br/><a href="/help/dashboard/overview.md">結構描述</a> - <a href="/help/dashboard/harmonized-data.md">協調資料</a> - <a href="/help/dashboard/plans.md">計畫</a>
    </td>
        <td>
      <img src="assets/Learn.svg" width="35px"><br/>
      <strong>教學課程</strong><br/><a href="https://experienceleague.adobe.com/docs/mix-modeler-learn/tutorials/overview.html?lang=zh-Hant">總覽</a> - <a href="https://experienceleague.adobe.com/docs/mix-modeler-learn/tutorials/intro/use-cases.html?lang=zh-Hant">使用案例</a> - <a href="https://experienceleague.adobe.com/docs/mix-modeler-learn/tutorials/intro/user-workflow.html?lang=zh-Hant">使用者工作流程</a> - <a href="https://experienceleague.adobe.com/docs/mix-modeler-learn/tutorials/intro/user-interface-tour.html?lang=zh-Hant">使用者介面導覽</a>
    </td>
  </tr>
</table>

