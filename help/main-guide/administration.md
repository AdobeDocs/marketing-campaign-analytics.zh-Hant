---
title: 管理
description: 瞭解如何管理Marketing Campaign Analytics。
feature: Administration
exl-id: 76d6d15d-a838-4ee2-9929-e55ea8946b80
autotag-review: '2026-05-01T09:07:55.299Z'
TQID: 'https://experienceleague.adobe.com/GZOR-NsylnAmpFEuZNDpvF0Br8eL-HKGYIPUBs00sNQ'
product_v2:
  - id: b88c80e3-31df-4609-989d-d4dac0e6d973
    internal-label: Marketing Campaign Analytics
feature_v2:
  - id: a567f0f7-0057-4079-8ded-5b24cc25af15
    internal-label: Harmonized data
  - id: d822825b-9821-40d5-9b0d-42a9e3f317c5
    internal-label: Plans
  - id: e0abf868-dae2-4c1c-83e9-b21799232845
    internal-label: Datasets
  - id: f40f1683-8300-4054-aab8-77da06ad63ff
    internal-label: Models
  - id: f6633d1c-3d2d-4f48-95d4-4bbc9913db52
    internal-label: Data governance
  - id: fbd94e4b-f9b8-42a4-8df5-3f917aabae24
    internal-label: Schemas
  - id: fe2edbb1-46f9-4347-a27c-577cab3640cb
    internal-label: Administration
subfeature_v2:
  - id: abe9e290-7d2f-4131-b71e-ef9900865044
    internal-label: Access control
  - id: a6da0571-746e-4d59-89a4-7b691b1c3b9a
    internal-label: Architecture
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
topic_v2:
  - id: b23e006f-0a29-4f1d-8fd0-77aa56f3d12b
    internal-label: Data modeling
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
    internal-label: Governance
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
    internal-label: Data management
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
source-git-commit: 9d6bd798e97d36d49b7753dc9574b102efb3d6bf
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 6%
---
# 管理

{{mm-mca-rebranding}}

使用[Adobe Admin Console](https://helpx.adobe.com/tw/enterprise/using/admin-console.html)管理Marketing Campaign Analytics產品和使用者。

若要讓Marketing Campaign Analytics正常運作，您必須設定正確的許可權。

在Adobe Experience Cloud UI中：

1. 從左側邊欄選取&#x200B;**[!UICONTROL ADMINISTRATION]**&#x200B;下方的&#x200B;**[!UICONTROL Permissions]**。

1. 從左側面板中選取![使用者](/help/assets/icons/User.svg) **[!UICONTROL Roles]**。

1. 選取現有的角色，或使用&#x200B;**[!UICONTROL Create role]**&#x200B;建立角色（例如，**Marketing Campaign Analytics**）。 如果您選取現有的角色，請選取![編輯](/help/assets/icons/Edit.svg) **[!UICONTROL Edit]**&#x200B;以編輯角色的許可權。 如需詳細資訊，請參閱[管理角色](https://helpx.adobe.com/tw/enterprise/using/admin-console.html)。

1. 確保您已為角色選取一或多個沙箱。

1. 將&#x200B;**Adobe Marketing Campaign Analytics**&#x200B;資源新增至角色的資源清單。

1. 請確定您為正在設定的角色選取正確的&#x200B;**[!UICONTROL Adobe Marketing Campaign Analytics]**&#x200B;許可權。 您可以選取下列一或多個角色：

   - **[!UICONTROL View Adobe Marketing Campaign Analytics Harmonized Data]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Harmonized Data]**
   - **[!UICONTROL View Adobe Marketing Campaign Analytics Models Configuration]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Models Configuration]**
   - **[!UICONTROL View Adobe Marketing Campaign Analytics Plans Configuration]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Plans Configuration]**

     ![Marketing Campaign Analytics RBAC](/help/assets/mix-modeler-rbac.png)


1. 請確定您為角色選取其他許可權。 例如，若要檢視或管理資料集和結構描述，您可以選取：

   - **[!UICONTROL Data Management]**：選取相關選項： **[!UICONTROL View Datasets]**&#x200B;或&#x200B;**[!UICONTROL Manage Datasets]**。

   - **[!UICONTROL Data Modeling]**：選取相關選項： **[!UICONTROL Manage Schemas]**&#x200B;或&#x200B;**[!UICONTROL View Schemas]**。

   <!--
    * **[!UICONTROL Data Governance]**: ensure you select **[!UICONTROL View User Activity Log]** and **[!UICONTROL View Data Usage Policies]**.
    -->

   <!--![Permissions](assets/permissions-including-privacy.png)-->

   選取&#x200B;**[!UICONTROL Save]**&#x200B;以儲存許可權。

1. 在&#x200B;**[!UICONTROL Role]**&#x200B;內的&#x200B;**[!UICONTROL Details]**&#x200B;中，新增適當的&#x200B;**[!UICONTROL Users]**&#x200B;或&#x200B;**[!UICONTROL User groups]**&#x200B;以提供使用者存取Marketing Campaign Analytics的許可權。
