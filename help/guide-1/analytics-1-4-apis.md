---
title: Adobe Analytics 1.4 API生命週期結束
description: Adobe Analytics 1.4 API和WSSE驗證已於2026年8月31日終止服務。 瞭解受影響的專案以及如何移轉至Analytics 2.0 API。
source-git-commit: 4056ba0953e81a279d25b15449c7b41a4a5eb7f9
workflow-type: tm+mt
source-wordcount: '743'
ht-degree: 1%
---
# Adobe Analytics 1.4 API生命週期結束

自&#x200B;**2026年8月31日起**，Adobe已淘汰Adobe Analytics 1.4 API和WSSE驗證。 所有使用此版本API的端點已無法存取，且在此基礎上建立的整合功能已停止運作。

Adobe Analytics 1.4 API提供多種動作，例如報告、分類、資料摘要、區段、計算量度、資料來源及報告套裝設定。 已由[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0)取代，可讓您執行Adobe Analytics使用者介面中幾乎所有可用的動作，包括報表和管理元件，例如區段和計算量度。 如果您有仍需升級的整合，請依照[移轉至Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0/guides/migration)指南操作。

## 哪些產品已終止服務

此生命週期結束直接影響下列1.4 API功能。 將每個受影響的工作流程移轉至[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0)：

* 報表（包括Data Warehouse、即時、路徑和摘要報表）
* 報表套裝的設定和管理
* 分類
* 區段
* 計算量度
* 資料來源
* 資料摘要
* 書籤和公司（端點）方法

它也會撤銷&#x200B;**Adobe Analytics WSSE驗證** （請參閱下方的[WSSE驗證](#wsse-authentication)）。

>[!IMPORTANT]
>
>此生命週期結束&#x200B;*不會*&#x200B;影響您的資料收集。 標籤（前身為Adobe Launch）、Web SDK和AppMeasurement等標籤解決方案不受影響。 [資料插入API](#data-insertion-api)也&#x200B;*不是*&#x200B;已淘汰。 不過，如果您使用1.4資料來源或分類API來增強資料，必須將這些工作流程移轉至Adobe Analytics 2.0 API。

## WSSE驗證

WSSE驗證是Analytics 1.4 API支援的舊版驗證通訊協定。 已由[Adobe Developer Console](https://developer.adobe.com/console/home)中提供的OAuth驗證選項取代。 使用WSSE驗證的專案必須將其憑證更新為Adobe Developer Console中布建的憑證。

若要移轉，請登入[Adobe Developer Console](https://developer.adobe.com/console/home)，並為您的Analytics 2.0 API整合建立專案。 選取&#x200B;**OAuth使用者**&#x200B;或&#x200B;**OAuth伺服器對伺服器**&#x200B;驗證方法。

## 資料插入 API

資料插入API是此生命週期結束的&#x200B;**非**&#x200B;部分。 其檔案已移至[Adobe Analytics資料收集API](https://developer.adobe.com/analytics-collection-apis/)網站，連同其他伺服器端收集方法：

* [資料插入API](https://developer.adobe.com/analytics-collection-apis/methods/data-insertion/)：以查詢字串（影像要求）或XML `POST`的方式，一次傳送一次點選的事件資料。
* [大量資料插入API](https://developer.adobe.com/analytics-collection-apis/methods/bulk-data-insertion/)：將伺服器呼叫資料的批次上傳為檔案。 Adobe建議針對新的伺服器端實作使用大量資料插入API。

## 常見問題

+++這是否會影響Analytics API的現有Adobe Developer專案？

任何使用Analytics 1.4 API的現有專案都會受到影響。 這些整合必須移轉至[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0/)。

+++

+++我已與使用Adobe API的其他產品或應用程式共用我的Analytics認證。 他們是否會受到影響？

如果該產品或應用程式使用您的WSSE憑證或呼叫Analytics 1.4 API，則會受到影響，且必須移轉。 請洽詢產品或應用程式提供者，以取得其移轉計畫和時程表的詳細資訊。

+++

+++如何判斷專案使用的API？

專案呼叫的基本URL會決定使用哪個API版本。 Adobe Analytics 1.4 API使用下列基底URL：

* `https://api.omniture.com`
* `https://api3.omniture.com`
* `https://api4.omniture.com`
* `https://api5.omniture.com`

[Adobe Analytics 2.0 API](https://developer.adobe.com/analytics-apis/docs/2.0/)使用下列基底URL：

* `https://analytics.adobe.io`

如果任何API專案呼叫`api*.omniture.com`，這些專案就會使用已淘汰的Adobe Analytics 1.4 API，而且必須移轉至2.0 API。

+++

+++此生命週期結束是否會影響資料收集？

沒有。 此生命週期結束&#x200B;**不會**&#x200B;影響直接資料收集，例如標籤、網頁SDK、AppMeasurement或資料插入API。 不過，如果您使用1.4資料來源或分類API來增強資料，必須將這些工作流程移轉至Adobe Analytics 2.0 API。

+++

如果您對此服務終止有進一步問題但本頁沒有回答，請聯絡您的Adobe客戶團隊。
