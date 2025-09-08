---
title: 隱藏的疑難排解測試
description: 這是隱藏的疑難排解測試
hide: true
hidefromtoc: true
source-git-commit: 388f61fa721e0fedf858634dde807baeadde06f3
workflow-type: ht
source-wordcount: '2876'
ht-degree: 100%

---

# AEM 中的移難排解


## 一列表格

| 疑難排解 AEM Sites |
|--- |
| + [(Dynamic Media) AEM Dynamic Media 中的迴轉集停留在處理狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [數位資產管理 (DAM) 轉譯與 AEM 中的原始檔案不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未產生智慧裁切轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修正 AEM 中的影片上傳、處理和轉譯問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 時，Adobe Asset Link 會使連結處於無法存取的狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [在 AEMaaCS 中，Dynamic Media 與 DAM 卡片視圖所顯示的影片縮圖不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 從 Dynamic Media 匯出資產和中繼資料](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中的大型 MP4 檔案資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 影片播放器在較低階的環境下無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(具有 OpenAPI 的 Dynamic Media) 運用以 IMS 使用者群組為基礎的 Open API 啟用 Dynamic Media 的受限制資產存取權](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [具有 ZIP 壓縮格式的 Tiff 檔案上傳到 AEM Assets 時，不會產生任何轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM 在超過 10 萬個語彙基元後，會截斷從大型 PDF 擷取的文字](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 變更 DM 資產的 Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解決 AEMaaCS 中非管理員使用者的中繼資料結構可見度問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 影像轉譯的背景顏色變更問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 資產輪換問題導致後續的輪換無法顯示](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal) 使用 OAuth 伺服器至伺服器認證來啟用 Brand Portal](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media) 解決 Adobe Experience Manager 6.5 Dynamic Media 中「智慧裁切」的影像損壞問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [放寬 Photoshop Firefly API 整合的單一部分資產上傳限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解決 AEM 環境中 PDF 檔案的 Dynamic Media 資產名稱差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些影像未在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中顯示縮圖轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) Dynamic Media「一般設定」頁面未開啟](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 解決在 AEM 中使用 Dynamic Media 造成的影片檔案音訊問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自動標記新上傳的資產](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中完成 JWT 移轉到 OAuth 之後，「智慧標記」功能無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決 AEM Managed Services 中的共用連結問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal) 共用連結下載問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + [(Dynamic Media) AEM Dynamic Media 發生資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中資產同步執行失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [在 AEM as a Cloud Service 中更新影片資產的自訂縮圖](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 的影像中繼資料出現差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放到 AEM Assets Web UI 失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal 編輯者和檢視者無法看到任何影像](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media) 解決 AEM as a Cloud Service 中的資產處理問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大型 PDF 的文字擷取限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解決 InDesign 中的 Adobe Experience Manager (AEM) 資產連結連線問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 外掛程式網路錯誤：無法聯繫伺服器](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media 同步使用者建議](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| 疑難排解 AEM Assets |
|--- |
| + [AEM 中的資產下載 ZIP 檔案中缺少轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-27140) |
| + [AEM Assets 授權中未包含內容片段](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26616) |
| + [儘管擁有讀取權限，「資產視圖」中的評論功能仍受限](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26928) |
| + [(Dynamic Media) AEM Dynamic Media 中的迴轉集停留在處理狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [數位資產管理 (DAM) 轉譯與 AEM 中的原始檔案不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未產生智慧裁切轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修正 AEM 中的影片上傳、處理和轉譯問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 時，Adobe Asset Link 會使連結處於無法存取的狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [在 AEMaaCS 中，Dynamic Media 與 DAM 卡片視圖所顯示的影片縮圖不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 從 Dynamic Media 匯出資產和中繼資料](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中的大型 MP4 檔案資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 影片播放器在較低階的環境下無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(具有 OpenAPI 的 Dynamic Media) 運用以 IMS 使用者群組為基礎的 Open API 啟用 Dynamic Media 的受限制資產存取權](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [具有 ZIP 壓縮格式的 Tiff 檔案上傳到 AEM Assets 時，不會產生任何轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM 在超過 10 萬個語彙基元後，會截斷從大型 PDF 擷取的文字](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 變更 DM 資產的 Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解決 AEMaaCS 中非管理員使用者的中繼資料結構可見度問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 影像轉譯的背景顏色變更問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 資產輪換問題導致後續的輪換無法顯示](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Dynamic Media) 解決 Adobe Experience Manager 6.5 Dynamic Media 中「智慧裁切」的影像損壞問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [放寬 Photoshop Firefly API 整合的單一部分資產上傳限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解決 AEM 環境中 PDF 檔案的 Dynamic Media 資產名稱差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些影像未在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中顯示縮圖轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) Dynamic Media「一般設定」頁面未開啟](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 解決在 AEM 中使用 Dynamic Media 造成的影片檔案音訊問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自動標記新上傳的資產](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中完成 JWT 移轉到 OAuth 之後，「智慧標記」功能無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決 AEM Managed Services 中的共用連結問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Dynamic Media) AEM Dynamic Media 發生資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中資產同步執行失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [在 AEM as a Cloud Service 中更新影片資產的自訂縮圖](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 的影像中繼資料出現差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放到 AEM Assets Web UI 失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Dynamic Media) 解決 AEM as a Cloud Service 中的資產處理問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大型 PDF 的文字擷取限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解決 InDesign 中的 Adobe Experience Manager (AEM) 資產連結連線問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 外掛程式網路錯誤：無法聯繫伺服器](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media 同步使用者建議](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| 疑難排解 AEM Forms |
|--- |
| + [(Dynamic Media) AEM Dynamic Media 中的迴轉集停留在處理狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [數位資產管理 (DAM) 轉譯與 AEM 中的原始檔案不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未產生智慧裁切轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修正 AEM 中的影片上傳、處理和轉譯問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 時，Adobe Asset Link 會使連結處於無法存取的狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [在 AEMaaCS 中，Dynamic Media 與 DAM 卡片視圖所顯示的影片縮圖不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 從 Dynamic Media 匯出資產和中繼資料](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中的大型 MP4 檔案資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 影片播放器在較低階的環境下無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(具有 OpenAPI 的 Dynamic Media) 運用以 IMS 使用者群組為基礎的 Open API 啟用 Dynamic Media 的受限制資產存取權](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [具有 ZIP 壓縮格式的 Tiff 檔案上傳到 AEM Assets 時，不會產生任何轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM 在超過 10 萬個語彙基元後，會截斷從大型 PDF 擷取的文字](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 變更 DM 資產的 Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解決 AEMaaCS 中非管理員使用者的中繼資料結構可見度問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 影像轉譯的背景顏色變更問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 資產輪換問題導致後續的輪換無法顯示](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal) 使用 OAuth 伺服器至伺服器認證來啟用 Brand Portal](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media) 解決 Adobe Experience Manager 6.5 Dynamic Media 中「智慧裁切」的影像損壞問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [放寬 Photoshop Firefly API 整合的單一部分資產上傳限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解決 AEM 環境中 PDF 檔案的 Dynamic Media 資產名稱差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些影像未在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中顯示縮圖轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) Dynamic Media「一般設定」頁面未開啟](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 解決在 AEM 中使用 Dynamic Media 造成的影片檔案音訊問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自動標記新上傳的資產](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中完成 JWT 移轉到 OAuth 之後，「智慧標記」功能無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決 AEM Managed Services 中的共用連結問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal) 共用連結下載問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + [(Dynamic Media) AEM Dynamic Media 發生資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中資產同步執行失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [在 AEM as a Cloud Service 中更新影片資產的自訂縮圖](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 的影像中繼資料出現差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放到 AEM Assets Web UI 失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal 編輯者和檢視者無法看到任何影像](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media) 解決 AEM as a Cloud Service 中的資產處理問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大型 PDF 的文字擷取限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解決 InDesign 中的 Adobe Experience Manager (AEM) 資產連結連線問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 外掛程式網路錯誤：無法聯繫伺服器](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media 同步使用者建議](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25471) |

## 三欄表格

| 疑難排解 AEM Sites | 疑難排解 AEM Assets | 疑難排解 AEM Forms |
|--- |--- |--- |
| + [(Dynamic Media) AEM Dynamic Media 中的迴轉集停留在處理狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26715) | + [AEM 中的資產下載 ZIP 檔案中缺少轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-27140) | + [(Dynamic Media) AEM Dynamic Media 中的迴轉集停留在處理狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26715) |
| + [數位資產管理 (DAM) 轉譯與 AEM 中的原始檔案不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [AEM Assets 授權中未包含內容片段](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26616) | + [數位資產管理 (DAM) 轉譯與 AEM 中的原始檔案不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [AEMaaCS 中未產生智慧裁切轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26873) | + [儘管擁有讀取權限，「資產視圖」中的評論功能仍受限](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26928) | + [AEMaaCS 中未產生智慧裁切轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26873) |
| + [(Dynamic Media) 修正 AEM 中的影片上傳、處理和轉譯問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26533) | + [(Dynamic Media) AEM Dynamic Media 中的迴轉集停留在處理狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26715) | + [(Dynamic Media) 修正 AEM 中的影片上傳、處理和轉譯問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26533) |
| + [(Asset Link) 使用 InDesign 時，Adobe Asset Link 會使連結處於無法存取的狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26922) | + [數位資產管理 (DAM) 轉譯與 AEM 中的原始檔案不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [(Asset Link) 使用 InDesign 時，Adobe Asset Link 會使連結處於無法存取的狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26922) |
| + [在 AEMaaCS 中，Dynamic Media 與 DAM 卡片視圖所顯示的影片縮圖不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [AEMaaCS 中未產生智慧裁切轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26873) | + [在 AEMaaCS 中，Dynamic Media 與 DAM 卡片視圖所顯示的影片縮圖不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media) 使用 API 從 Dynamic Media 匯出資產和中繼資料](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26902) | + [(Dynamic Media) 修正 AEM 中的影片上傳、處理和轉譯問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26533) | + [(Dynamic Media) 使用 API 從 Dynamic Media 匯出資產和中繼資料](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26902) |
| + [AEM as a Cloud Service 中的大型 MP4 檔案資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26610) | + [(Asset Link) 使用 InDesign 時，Adobe Asset Link 會使連結處於無法存取的狀態](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26922) | + [AEM as a Cloud Service 中的大型 MP4 檔案資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media 影片播放器在較低階的環境下無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26871) | + [在 AEMaaCS 中，Dynamic Media 與 DAM 卡片視圖所顯示的影片縮圖不相符](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [(Dynamic Media) Dynamic Media 影片播放器在較低階的環境下無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [(具有 OpenAPI 的 Dynamic Media) 根據 IMS 使用者群組啟用對具有 Open API 的 Dynamic Media 的受限制資產存取權](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media) 使用 API 從 Dynamic Media 匯出資產和中繼資料](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26902) | + [(具有 OpenAPI 的 Dynamic Media) 運用以 IMS 使用者群組為基礎的 Open API 啟用 Dynamic Media 的受限制資產存取權](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [具有 ZIP 壓縮格式的 Tiff 檔案上傳到 AEM Assets 時，不會產生任何轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [AEM as a Cloud Service 中的大型 MP4 檔案資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26610) | + [具有 ZIP 壓縮格式的 Tiff 檔案上傳到 AEM Assets 時，不會產生任何轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM 在超過 10 萬個語彙基元後，會截斷從大型 PDF 擷取的文字](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26785) | + [(Dynamic Media) Dynamic Media 影片播放器在較低階的環境下無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26871) | + [AEM 在超過 10 萬個語彙基元後，會截斷從大型 PDF 擷取的文字](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [(Dynamic Media) 變更 DM 資產的 Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-17628) | + [(具有 OpenAPI 的 Dynamic Media) 根據 IMS 使用者群組啟用對具有 Open API 的 Dynamic Media 的受限制資產存取權](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media) 變更 DM 資產的 Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-17628) |
| + [解決 AEMaaCS 中非管理員使用者的中繼資料結構可見度問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [具有 ZIP 壓縮格式的 Tiff 檔案上傳到 AEM Assets 時，不會產生任何轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [解決 AEMaaCS 中非管理員使用者的中繼資料結構可見度問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + [(Dynamic Media) Dynamic Media 中 TIFF 影像轉譯的背景顏色變更問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [AEM 在超過 10 萬個語彙基元後，會截斷從大型 PDF 擷取的文字](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26785) | + [(Dynamic Media) Dynamic Media 中 TIFF 影像轉譯的背景顏色變更問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS 資產輪換問題導致後續的輪換無法顯示](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [(Dynamic Media) 變更 DM 資產的 Dynamic Media URL](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-17628) | + [AEMaaCS 資產輪換問題導致後續的輪換無法顯示](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal) 使用 OAuth 伺服器至伺服器認證來啟用 Brand Portal](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-22074) | + [解決 AEMaaCS 中非管理員使用者的中繼資料結構可見度問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [(Brand Portal) 使用 OAuth 伺服器至伺服器認證來啟用 Brand Portal](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media) 解決 Adobe Experience Manager 6.5 Dynamic Media 中「智慧裁切」的影像損壞問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26367) | + [(Dynamic Media) Dynamic Media 中 TIFF 影像轉譯的背景顏色變更問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [(Dynamic Media) 解決 Adobe Experience Manager 6.5 Dynamic Media 中「智慧裁切」的影像損壞問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [放寬 Photoshop Firefly API 整合的單一部分資產上傳限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [AEMaaCS 資產輪換問題導致後續的輪換無法顯示](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [放寬 Photoshop Firefly API 整合的單一部分資產上傳限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media) 解決 AEM 環境中 PDF 檔案的 Dynamic Media 資產名稱差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media) 解決 Adobe Experience Manager 6.5 Dynamic Media 中「智慧裁切」的影像損壞問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26367) | + [(Dynamic Media) 解決 AEM 環境中 PDF 檔案的 Dynamic Media 資產名稱差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [某些影像未在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中顯示縮圖轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26233) | + [放寬 Photoshop Firefly API 整合的單一部分資產上傳限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [某些影像未在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中顯示縮圖轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26233) |
| + [(Dynamic Media) Dynamic Media「一般設定」頁面未開啟](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [(Dynamic Media) 解決 AEM 環境中 PDF 檔案的 Dynamic Media 資產名稱差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media) Dynamic Media「一般設定」頁面未開啟](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media) 解決在 AEM 中使用 Dynamic Media 造成的影片檔案音訊問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26197) | + [某些影像未在 Adobe Experience Manager (AEM) as a Cloud Service - Asset 中顯示縮圖轉譯](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26233) | + [(Dynamic Media) 解決在 AEM 中使用 Dynamic Media 造成的影片檔案音訊問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在 AEM as a Cloud Service 中自動標記新上傳的資產](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [(Dynamic Media) Dynamic Media「一般設定」頁面未開啟](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [在 AEM as a Cloud Service 中自動標記新上傳的資產](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在 AEM 中完成 JWT 移轉到 OAuth 之後，「智慧標記」功能無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Dynamic Media) 解決在 AEM 中使用 Dynamic Media 造成的影片檔案音訊問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-26197) | + [在 AEM 中完成 JWT 移轉到 OAuth 之後，「智慧標記」功能無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決 AEM Managed Services 中的共用連結問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25903) | + [在 AEM as a Cloud Service 中自動標記新上傳的資產](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [解決 AEM Managed Services 中的共用連結問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal) 共用連結下載問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25771) | + [在 AEM 中完成 JWT 移轉到 OAuth 之後，「智慧標記」功能無法運作](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Brand Portal) 共用連結下載問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + [(Dynamic Media) AEM Dynamic Media 發生資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25607) | + [解決 AEM Managed Services 中的共用連結問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25903) | + [(Dynamic Media) AEM Dynamic Media 發生資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中資產同步執行失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25885) | + [(Dynamic Media) AEM Dynamic Media 發生資產處理失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25607) | + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中資產同步執行失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [在 AEM as a Cloud Service 中更新影片資產的自訂縮圖](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25829) | + [(Dynamic Media) Adobe Experience Manager (AEM) Dynamic Media 中資產同步執行失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25885) | + [在 AEM as a Cloud Service 中更新影片資產的自訂縮圖](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets 的影像中繼資料出現差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [在 AEM as a Cloud Service 中更新影片資產的自訂縮圖](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25829) | + [Adobe Experience Manager (AEM) Assets 的影像中繼資料出現差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放到 AEM Assets Web UI 失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [Adobe Experience Manager (AEM) Assets 的影像中繼資料出現差異](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [將資產資料夾拖放到 AEM Assets Web UI 失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal 編輯者和檢視者無法看到任何影像](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-20177) | + [將資產資料夾拖放到 AEM Assets Web UI 失敗](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [(Brand Portal) Brand Portal 編輯者和檢視者無法看到任何影像](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media) 解決 AEM as a Cloud Service 中的資產處理問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25525) | + [(Dynamic Media) 解決 AEM as a Cloud Service 中的資產處理問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25525) | + [(Dynamic Media) 解決 AEM as a Cloud Service 中的資產處理問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25525) |
| + [Adobe Experience Manager as a Cloud Service 中大型 PDF 的文字擷取限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25518) | + [Adobe Experience Manager as a Cloud Service 中大型 PDF 的文字擷取限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25518) | + [Adobe Experience Manager as a Cloud Service 中大型 PDF 的文字擷取限制](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link) 解決 InDesign 中的 Adobe Experience Manager (AEM) 資產連結連線問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25562) | + [(Asset Link) 解決 InDesign 中的 Adobe Experience Manager (AEM) 資產連結連線問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25562) | + [(Asset Link) 解決 InDesign 中的 Adobe Experience Manager (AEM) 資產連結連線問題](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25562) |
| + [(Asset Link) Adobe Asset Link 外掛程式網路錯誤：無法聯繫伺服器](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link 外掛程式網路錯誤：無法聯繫伺服器](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link 外掛程式網路錯誤：無法聯繫伺服器](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media 同步使用者建議](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) Dynamic Media 同步使用者建議](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) Dynamic Media 同步使用者建議](https://experienceleague.adobe.com/zh-hant/docs/experience-cloud-kcs/kbarticles/ka-25471) |
