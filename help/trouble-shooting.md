---
title: 控制面板疑難排解
description: 瞭解如何進行控制面板疑難排解。
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
TQID: 'https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
source-git-commit: e4a8e51ee4016895090eb90d528d0a2707fd0225
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 92%
---
# [!UICONTROL 控制面板]疑難排解

## 登入和首頁

### 症狀：無法登入 Experience Cloud

**該做什麼：**
使用者必須找到自己的 IMS Org ID (xxx)。 系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔「Campaign-xxx-Admins」。 如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：使用者看不到 Experience Cloud 首頁存取[!UICONTROL 控制面板]的連結

**原因：**
使用者必須新增為產品設定檔 _Campaign-xxx-Administrators/ Admin_ 的使用者，才能看到連結。

**該做什麼：**
系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔 _Campaign-xxx-Admins_。 如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：執行個體未列於[!UICONTROL 控制面板]

**原因：**
最可能的情況是，使用者必須新增為遺失執行個體之產品設定檔 _Campaign-xxx-Administrators/ Admin_ 的&#x200B;*使用者*。

**該做什麼：**
系統管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔 _Campaign-xxx-Admins_。 如果使用者是所有執行個體的管理員，則他們仍需將自己新增為「使用者」。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*檢查IMS組織ID （00:26分鐘）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*如何為產品設定檔管理員新增管理員，以便使用[!UICONTROL 控制面板] （01:03分鐘）*

### 實用文件

* [探索 [控制面板]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)
* [管理[!UICONTROL 控制面板]的權限](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)

## 建立與 SFTP 伺服器（用戶端或 API）的連線

連線至 SFTP 伺服器需要：

* [!UICONTROL 允許列出]您連線至 SFTP 伺服器的 IP 位址
* 需要以 Adobe Campaign 註冊私人/公有金鑰組
* 如需直接連接到 SFTP 伺服器，您還需要 SFTP 用戶端軟體

### 實用文件 {#helpful-docs}

* [登入您的 SFTP 伺服器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)
