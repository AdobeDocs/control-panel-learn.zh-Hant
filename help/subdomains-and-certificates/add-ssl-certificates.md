---
title: 添加SSL證書
description: 瞭解如何添加SSL證書以保護子域的安全。
feature: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: d12902547ffde67838b326c93162d0937ff438a6
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 38%

---

# 添加SSL證書

Adobe Campaign [!UICONTROL Control Panel] 可以讓您新增 SSL 憑證，以保護您的子網域。

## 存取控制面板子網域管理

若要存取「控制面板」的「子網域管理」，請前往：

* [Experience Cloud 首頁](https://experience.adobe.com/#/home) > 解決方案選擇器：**[!DNL Campaign]** > **[!UICONTROL Control Panel]** 卡片 > **[!UICONTROL Subdomains & Certificates]** 卡片

   或
* 直接從 URL：[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## 新增 SSL 憑證的步驟

新增 SSL 憑證需要三個步驟：

### 1. 產生憑證申請檔

購買SSL證書需要證書籤名請求(CSR)。 必須為您計畫保護的實例和子域生成它。

以下影片說明如何在「控制面板」產生「憑證申請檔」。

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*產生憑證申請檔 (02:36分鐘)*

>[!NOTE]
>
>對CSR生成過程進行了幾項改進：
>
>* 生成CSR時，現在可以選擇包含的子域之一作為「公用名稱」。
>* 現在，在生成CSR之前，可以複製CSR摘要。
>* 生成CSR後，可以從作業日誌中再次下載。 此功能不適用於此版本之前生成的證書。
>
>![下載CSR](/help/assets/download-csr.gif)
>
>查看 [產品文檔](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) 來瞭解更多資訊。

### 2. 購買 SSL 憑證

獲得CSR後，您必須從組織批准的證書頒發機構購買SSL證書。

### 3. 安裝 SSL 憑證

獲得SSL證書後，必須為您計畫保護的子域安裝該證書。

以下影片說明如何在 [!UICONTROL Control Panel] 安裝 SSL 憑證。

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*安裝 SSL 憑證 (01:25分鐘)*


