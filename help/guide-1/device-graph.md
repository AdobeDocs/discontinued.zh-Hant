---
keywords: 裝置圖表；生命週期結束
title: 裝置圖表
description: 瞭解裝置圖表的生命週期結束計畫。
source-git-commit: bb33d25c2f7f7fa7a3d133c9f9b7c89387ff78e4
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 2%

---

# 裝置圖表終止服務

>[!WARNING]
>
>自&#x200B;**2025年12月31日起，Cross-Device Analytics中的裝置圖表已無法使用**。 請將目前任何啟用裝置圖表的虛擬報表套裝切換為[欄位型方法](https://experienceleague.adobe.com/en/docs/analytics/components/cda/field-based-stitching)。

跨裝置分析確實使用私密圖表將資料彙整在一起。 專用圖表是組織專屬之雜湊裝置ID的存放庫。 CDA會定期與裝置圖表通訊，以將裝置連結在一起。

## 裝置圖表專屬先決條件

如果您打算使用裝置圖表方法實施作業跨裝置分析，須進行下列事項。

>[!WARNING]
>
>若未符合所有必要條件，可能會導致無法啟用跨裝置分析功能，或在連結資料時效果不彰。

* 您的組織必須使用[Adobe Experience Platform Identity Service私密圖表](https://business.adobe.com/products/experience-platform/identity-service.html)。 另請參閱Identity Service使用手冊中的[首頁](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html)。
* 您的實作必須使用最新版Experience Cloud ID服務(ECID)。 請參閱ID服務使用手冊中的[首頁](https://experienceleague.adobe.com/docs/id-service/using/home.html)。 在Adobe Experience Platform中使用[標籤](https://experienceleague.adobe.com/docs/experience-platform/tags/home.html)的大多數實作可能已經部署ID服務。
* 您的實作必須在可識別個人身分時（例如使用者登入或開啟電子郵件），呼叫`setCustomerIDs`函式（或相等SDK專案）。 這項要求適用於所有平台，包括行動應用程式在內（若有使用）。 請參閱ID服務使用手冊中的[`setCustomerIDs`](https://experienceleague.adobe.com/docs/id-service/using/id-service-api/methods/setcustomerids.html)。

## 裝置圖表專屬限制

* 不支援舊版Analytics ID。 系統只會連結具有Experience Cloud ID的訪客。
* 如果您的組織使用「專屬圖表」，則新裝置最多需要24小時的銜接時間。
* 不支援協力廠商裝置圖形。
