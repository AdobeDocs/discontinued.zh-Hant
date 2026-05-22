---
title: Adobe Media SDK （1.x和2.x版）生命週期結束常見問題集
description: 取得有關Adobe Media SDK 1.x和2.x版（原稱為視訊心率程式庫）終止的常見問題解答。
source-git-commit: d014c200dd926ccf0116faa50c4bffb1d234e926
workflow-type: tm+mt
source-wordcount: '1046'
ht-degree: 0%

---


# Adobe Media SDK （1.x和2.x版）生命週期結束常見問題集

Adobe Media SDK **2.x於2021年8月31日終止支援**。 視訊心率程式庫(VHL) **1.x已過時**，並且已有數年不受支援。

## 發生什麼事？

原始的視訊心率庫(VHL) （之後重新命名為Media SDK）提供音訊和視訊分析的使用者端追蹤。 Adobe已將追蹤功能轉換為功能更強大的較新實作：

* **Media SDK 3.x （僅限Analytics）：**&#x200B;目前支援。 使用Media Collection API追蹤媒體。 建議尚未移轉至Edge Network的現有2.x使用者使用。
* **適用於Edge Network的串流媒體（建議）：**&#x200B;目前建議的實作。 使用Adobe Experience Platform Web SDK、Mobile SDK或Media Edge API透過Edge Network傳送媒體資料，並可跨Adobe Analytics、Customer Journey Analytics、Real-Time CDP和Adobe Journey Optimizer使用。

## 生命週期結束包含哪些專案，但哪些專案未包含？

**生命週期結束（不再支援）：**

* 影片心率庫(VHL) 1.x — 所有平台(Android、iOS、JavaScript、Apple TV、Chromecast、Roku、TVML)
* Media SDK 2.x — Android、iOS、JavaScript

**未結束生命週期（仍受支援）：**

* Media SDK 3.x — JavaScript、Chromecast、Roku （僅限Analytics）
* Edge Network適用的串流媒體 — 所有支援的平台

## 為什麼1.x和2.x版已淘汰？

從3.0版開始，Media SDK已重新設計為直接使用Media Collection API，不需要委派模式並簡化追蹤器的建立。 舊版1.x和2.x SDK所依賴的心率伺服器架構已遭取代。

Adobe也推出了Edge Network實作，以提供能供應多個下游Adobe應用程式的單一資料收集管道，而舊版心率SDK不支援該應用程式。

## 我可以在哪裡找到已封存的檔案？

舊版檔案已封存至GitHub，可供參考：

| 版本 | 狀態 | 封存的檔案 |
|---|---|---|
| 1.x （視訊心率程式庫） | 已棄用 | [`video-heartbeat` GitHub存放庫](https://github.com/Adobe-Marketing-Cloud/video-heartbeat/tree/master/docs) |
| 2.x (Media SDK) | 終止支援2021年8月31日 | [`media-sdks` GitHub存放庫](https://github.com/Adobe-Marketing-Cloud/media-sdks/blob/master/docs/2.x/README.md) |

## 什麼是轉換選項？

**選項1：移轉至Media SDK 3.x （僅限Analytics）**

如果您使用2.x，並專門使用Adobe Analytics，移轉至3.x是最簡單的路徑。 如需完整的API比較和程式碼範例，請參閱[2.x移轉至3.x指南](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/migrate-js-2x-to-3x.html)。

**選項2：移轉至Edge Network適用的串流媒體（建議）**

若為新實作，或想在多個Adobe應用程式中使用資料，請使用Adobe Experience Platform Edge Network：

* [Media Edge Web SDK](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-web-sdk.html)
* [Media Edge Mobile SDK](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)
* [Media Edge API](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/implementation-edge-api.html)

## 常見問答

+++**Roku和Chromecast SDK支援是否會受到影響？**

沒有。 Roku和Chromecast SDK仍可在Media SDK 3.x中使用和支援（僅限Analytics）。 此終止服務僅涵蓋1.x和2.x版本。

+++

+++**Media Analytics JavaScript SDK實施是否會受到影響？**

沒有。 使用Media Analytics適用的JavaScript SDK的客戶可以繼續使用獨立的SDK或標籤擴充功能。

+++

+++**我仍在Media SDK 2.x上。 我應該怎麼做？**

Adobe建議您將所有新專案移轉至Edge Network實施。 如果您需要中繼步驟，請[從JavaScript SDK 2.x移轉至3.x](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/migrate-js-2x-to-3x.html)，然後計畫移至Edge Network。

+++

+++**移轉至支援實作的工作量為何？**

移轉工作取決於每位客戶的實作，且會有所不同。 檢閱移轉檔案後，如需其他支援，請洽詢諮詢或客戶服務：

* [使用行動Edge SDK — Android和iOS實作串流媒體](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)
* [從JavaScript SDK 2.x移轉至3.x](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/migrate-js-2x-to-3x.html)

+++

+++**我是否需要使用Adobe Experience Platform標籤作為標籤管理系統？**

在行動應用程式實作中，Experience Platform Tags的用途與網頁版不同，並非作為標籤管理系統。 設定SDK擴充功能時，必須要有標籤UI。 這類似於使用Adobe Mobile Services UI設定Mobile v4 SDK的方式。 標籤會根據您選擇的擴充功能，提供自訂的安裝指示。

+++

+++**此支援終止是否會影響tvOS的SDK？**

有。 tvOS （10以上版本）的建議實作方法是使用Adobe Experience Platform Mobile SDK移轉至Edge Network適用的串流媒體。 如需詳細資訊，請參閱[使用Mobile Edge SDK實作串流媒體](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)。

+++

+++**此支援終止是否會影響Fire TV和Android TV的SDK？**

有。 Fire TV和Android TV的建議實作方法是使用Adobe Experience Platform Mobile SDK移轉至Edge Network適用的串流媒體。 如需詳細資訊，請參閱[使用Mobile Edge SDK實作串流媒體](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/edge-mobile-sdk.html)。

+++

+++**我可以在哪裡找到Mobile v4 SDK生命週期結束資訊？**

請參閱[Mobile Services生命週期結束常見問答集](mobile-services.md)。 Mobile Services平台和Mobile v4 SDK已於2022年12月31日終止服務。

+++

+++**如果有任何問題，可以前往何處？**

如需移轉協助，請連絡您的Adobe客戶團隊或Adobe客戶服務。

+++

>[!MORELIKETHIS]
>
>* [串流媒體實作概觀](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/overview.html)
>* [適用於Edge Network的串流媒體](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/edge/implementation-edge.html)
>* [Media SDK 3.x — JavaScript設定](https://experienceleague.adobe.com/docs/media-analytics/using/implementation/media-sdk/setup/web-implementation.html)
