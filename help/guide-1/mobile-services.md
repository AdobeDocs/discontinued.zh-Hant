---
title: Adobe Mobile Services 生命週期結束常見問題集
description: 取得有關 Adobe Mobile Services 生命週期結束公告的常見問題解答。
exl-id: c5f44341-7b87-4530-b86e-17e2911a7959
source-git-commit: 343e0a727c570c9eec503d7903d0477134fc6189
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 100%

---

# Adobe Mobile Services 生命週期結束常見問題集

Adobe Mobile Services 生命週期結束日期為 **2022 年 12 月 31 日**。

## 發生什麼事？

Mobile Services 的生命週期已於 2022 年 12 月 31 日結束。在此日期之後將不再支援 Mobile Services 及其所支援的以行動裝置為中心的 UI、擷取、深度連接、應用程式內傳送訊息、推播通知和地理位置定位。

## 生命週期結束包含哪些部份？又有哪些部份除外？

此生命週期結束僅包括 Adobe Mobile Services，即 [mobilemarketing.adobe.com](https://mobilemarketing.adobe.com) 的獨立平台。依賴此介面的行動版本 4 SDK 已於 2021 年 8 月 31 日停用。

此生命週期結束不包含適用於行動應用程式的 Adobe Analytics，這是 Adobe Experience Platform Mobile SDK 的一部分。而 Adobe 會繼續支援的功能包括應用程式內行為、生命週期分析、傳送訊息互動追蹤和閱聽眾個人資料。

## 為什麼要淘汰這項功能？

隨著 Adobe 不斷擴大其行動裝置行銷能力，之前在 Mobile Services 中提供的功能將在 Adobe Experience Cloud 解決方案中發行，或是由 Adobe Exchange Premier Partners 提供。這項轉變能提供更強大、更靈活的行動裝置行銷能力。

## 在 Mobile Services 中建立的現有處理規則會如何處理？

在 Mobile Services UI 中建立或產生的[處理規則](https://experienceleague.adobe.com/docs/analytics/admin/admin-tools/processing-rules/processing-rules.html?lang=zh-Hant)會在 Mobile Services 生命週期結束日期之前，自動移轉到 Adobe Analytics。所移轉的處理規則之行為與 Adobe Analytics 的其他處理規則類似，您可以自由檢視或編輯規則。此移轉不需要使用者執行任何操作。

淘汰 Mobile Services 後，所有處理規則邏輯將在 Adobe Analytics 內專門處理，通常包括使用[內容資料變數](https://experienceleague.adobe.com/docs/analytics/implementation/vars/page-vars/contextdata.html?lang=zh-Hant)。

## 有哪些可以選擇的轉換選項？

Adobe 會根據您組織的使用案例，提供三種轉換路徑。

1. **應用程式內傳送訊息和推播通知**：Adobe 可以將您的傳送訊息工作流程轉換至 Adobe Journey Optimizer。此產品可協助組織將整個客戶歷程 (包括行動傳訊) 的體驗最佳化及個人化。
1. **擷取和深度連接**：透過 Adobe Exchange Premier Partners 計畫，提供擷取和深度連接。Adobe 的合作夥伴團隊可以適當地介紹，確保您能找到最符合需求的解決方案。
1. **Places Service**：Places Service 提供免費的地理位置定位功能。請參閱 [Places Service 文件](https://experienceleague.adobe.com/docs/places/using/home.html?lang=zh-Hant)。

## 如果我有疑問，可以去哪裡找資訊？

請參閱 [Adobe Mobile Services 生命週期結束 Spark 頁面](https://spark.adobe.com/page/C6D30y09zaRpD/)，了解更多資訊。若有任何疑問，請聯絡您的 Adobe 代表。
