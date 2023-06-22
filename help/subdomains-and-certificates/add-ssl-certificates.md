---
title: 新增 SSL 憑證
description: 瞭解如何新增 SSL 憑證以保護您的子網域。
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: af05bde1295913c93388dd014462e32afb081669
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 100%

---

# 新增 SSL 憑證

Adobe Campaign [!UICONTROL Control Panel] 可以讓您新增 SSL 憑證，以保護您的子網域。

## 存取控制面板子網域管理

若要存取「控制面板」的「子網域管理」，請前往：

* [Experience Cloud 首頁](https://experience.adobe.com/#/home) > 解決方案選擇器：**[!DNL Campaign]** > **[!UICONTROL Control Panel]** 卡片 > **[!UICONTROL Subdomains & Certificates]** 卡片

  或
* 直接從 URL：[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## 新增 SSL 憑證的步驟

新增 SSL 憑證需要三個步驟：

### 1. 產生憑證申請檔

購買 SSL 憑證，需要憑證申請檔 (CSR)。需要為您欲保護的執行個體與子網域產生申請檔。

以下影片說明如何在「控制面板」產生「憑證申請檔」。

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12&learn=0n)

*產生憑證申請檔 (02:36分鐘)*

>[!NOTE]
>
>對 CSR 的產生過程進行了一些功能增強：
>
>* 產生 CSR 時，現在可以選擇所包含的子網域中之一作為「一般名稱」。
>* 現在產生 CSR 之前，可以複製 CSR 摘要。
>* 產生 CSR 之後，可以從作業記錄中重新下載。 此功能不適用於此版本之前產生的憑證。
>
>![下載 CSR](/help/assets/download-csr.gif)
>
>請參閱[產品文件](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=zh-Hant)以深入瞭解。
>

### 2. 購買 SSL 憑證

取得 CSR 後，須向貴組織核准的憑證機構購買 SSL 憑證。

### 3. 安裝 SSL 憑證

取得 SSL 憑證後，須為您欲保護的子網域安裝 SSL 憑證。

以下影片說明如何在 [!UICONTROL Control Panel] 安裝 SSL 憑證。

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12&learn=0n)

*安裝 SSL 憑證 (01:25分鐘)*


