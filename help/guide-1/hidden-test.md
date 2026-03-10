---
title: 隱藏的測試
description: 這是隱藏的測試
hide: true
hidefromtoc: true
landing-page-breadcrumb-title: Test AEM 6.5
landing-page-name: experience-manager-65
feature: Annotations
hold: true
exl-id: e6e5ba1c-98a5-4d7d-9913-426df31bc7a3
source-git-commit: 8d2e39e354962d6a04ba48d33c834e885641b2e1
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 8%

---

# 隱藏的測試

2026年3月10日 — `hold: true`已開啟。

測試新金鑰

此為隱藏測試。 我正在新增此`[`，以確定其在v2轉譯中可正常運作！

## 在新標籤中開啟 {#section_92882928}

`[See What's new](auditor.md){target="_blank"} `

[在同一個索引標籤中開啟](auditor.md)

[含空格的新索引標籤](auditor.md){target="_blank"} 

[含錨點的新索引標籤](auditor.md){target=_blank}

[不帶引號空格的新索引標籤](auditor.md){target="_blank"}

[含空格的新索引標籤，不含引號](auditor.md){target=_blank} 

[不帶引號的新索引標籤](auditor.md){target=_blank}

[具有深層連結的新標籤](commerce-channels.md#channel-manager-extension){target="_blank"}

[錨點含有深層連結的新索引標籤](https://experienceleague.adobe.com/en/docs/analytics/analyze/home#key-analytics-resources){target="_blank"}

[具有外部連結的新索引標籤](https://www.adobe.com){target="_blank"}

[新增索引標籤根連結](/help/guide-1/auditor.md){target="_blank"}


<table>
  <tr>
    <th>帶引號</a></th>
    <th>不含引號</th>
  </tr>
  <tr>
    <td><a href="https://www.adobe.com" target="_blank">Adobe新索引標籤</a></td>
    <td><a href="https://www.adobe.com" target="_blank">Adobe新索引標籤</td>
  </tr>
  <tr>
    <td><a href="https://www.adobe.com">Adobe沒有新標籤</a></td>
    <td><a href="https://www.adobe.com">Adobe沒有新標籤</td>
  </tr>
</table>

## 註解測試

2025年11月18日

<!-- ## Comment with basic text

This is a new line.

Second new line. -->


請在下方註解。 如果您是在本文中看到的最後一件事，則是因為註解語法。

1. 按一下 **[!UICONTROL Create]**。

<!-- ## Create an exclusion using Advanced Search

You can also create exclusions using [!UICONTROL Advanced Search] on the [Catalog Search](/help/main/c-recommendations/c-products/catalog-search.md#save-as) page ( [!UICONTROL Recommendations] > [!UICONTROL Catalog Search] > [!UICONTROL Advanced Search]). 

![Save as dialog](/help/main/c-recommendations/c-products/assets/save-as.png)

After creating a search using "id > contains," for example, you can then click [!UICONTROL Save As] > [!UICONTROL Exclusion].

>[!IMPORTANT]
>
>The [!UICONTROL Advanced Search] functionality is case-insensitive; however, products returned at the time of delivery are based on case-sensitive search. This mismatch might lead to confusion. Ensure that you consider case-sensitivity when you create exclusions based on results using the Advanced Search functionality. For example, if you perform a search for "Holiday," that initial search lists results containing "Holiday" and "holiday." If you then create an exclusion with the intent to exclude products containing "holiday," only products containing "holiday" are excluded. Products containing "Holiday" are not excluded. -->

此行在註解之後。

## 視訊測試

### 純視訊沒有成績單 — 應該顯示成績單，因為metadata.md會向下滴流

>[!VIDEO](https://video.tv.adobe.com/v/332116?hidetitle=true)

### 成績單設為true

>[!VIDEO](https://video.tv.adobe.com/v/332116?hidetitle=true){transcript=true}

### 成績單設為false — 影片成績單不應顯示

>[!VIDEO](https://video.tv.adobe.com/v/332116?hidetitle=true){transcript=false}

## 相對連結

* [概觀](overview.md)
* [Search和Promote](search-promote.md)
* [Social](social.md)

## 明確深層連結

[其他總覽(root)](/help/guide-1/overview.md#additional-products)

[其他概述](overview.md#additional-products)

## 暫留文字測試 {#this-is-a-heading-anchor}

無暫留文字

```
![alt text](assets/maui-flip.jpg)
```

![替代文字](assets/maui-flip.jpg)


是暫留文字

```
![alt text](assets/maui-flip.jpg "Hover text")
```

![替代文字](assets/maui-flip.jpg "暫留文字")

## 投影片

語法：

```
>[!SLIDE](analyze-project)
https://experienceleague-stage.adobe.com/en/slides/analyze-project
```

轉譯：

<!--
>[!SLIDE](analyze-project)
-->

Bob：測試主題位置後，請移除投影片註解。
