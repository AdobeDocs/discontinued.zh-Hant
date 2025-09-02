---
title: 隱藏的疑難排解測試
description: 這是隱藏的疑難排解測試
hide: true
hidefromtoc: true
source-git-commit: 388f61fa721e0fedf858634dde807baeadde06f3
workflow-type: tm+mt
source-wordcount: '2876'
ht-degree: 0%

---

# AEM的疑難排解


## 單清單格

| 疑難排解AEM Sites |
|--- |
| + [(Dynamic Media)迴轉集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在處理狀態 |
| + [數位資產管理(DAM)轉譯不符合AEM中的原始檔案](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中產生的智慧型裁切轉譯 |
| + [(Dynamic Media)修正AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的視訊上傳、處理和轉譯問題 |
| + [(Asset Link) Adobe Asset Link讓連結在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)時處於無法存取狀態 |
| + AEMaaCS中Dynamic Media與DAM卡片檢視之間的[視訊縮圖不相符](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)從Dynamic Media匯出資產和中繼資料 |
| + [在AEM as a Cloud Service中處理大型MP4檔案的資產失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media視訊播放器無法在較低層環境中運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（具有OpenAPI的Dynamic Media）啟用受限的Assets存取以IMS使用者群組為基礎的Open API的Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [當具有ZIP壓縮格式的Tiff檔案上傳到AEM Assets時，不會產生轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM會在100K代號之後截斷從大型PDF擷取的文字](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [（動態媒體）變更DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的動態媒體URL |
| + [解決AEMaaCS中非管理員使用者的中繼資料結構可見性問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF影像轉譯的[(Dynamic Media)背景色彩變更問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS資產輪換問題導致後續輪換不可見](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal)使用OAuth伺服器對伺服器憑證啟用Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media)解決Adobe Experience Manager 6.5 Dynamic Media中智慧型裁切的損壞影像問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加Photoshop Firefly API整合的單一部分資產上傳限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)針對PDF檔案在AEM環境中解決Dynamic Media資產名稱差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [在Adobe Experience Manager (AEM) as a Cloud Service — 資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中，某些影像未顯示縮圖轉譯 |
| + [ (Dynamic Media) Dynamic Media一般設定頁面未開啟](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)解決AEM中Dynamic Media的視訊檔案中的音訊問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在AEM as a Cloud Service中自動標籤新上傳的資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在AEM中將JWT移轉至OAuth後，智慧標籤功能無法運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決AEM Managed Services中的共用連結問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal)共用連結下載問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + AEM Dynamic Media中的[(Dynamic Media)資產處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[ (Dynamic Media)資產同步處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中視訊資產的自訂縮圖](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的影像中繼資料差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放至AEM Assets Web UI失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal編輯器和檢視器無法看到任何影像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media)正在解決AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的資產處理問題 |
| + Adobe Experience Manager as a Cloud Service中大型PDF的[文字擷取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解決InDesign ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)資產連結連線問題 |
| + [(Asset Link) Adobe Asset Link外掛程式網路錯誤：無法連線伺服器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步處理使用者建議](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| 疑難排解AEM Assets |
|--- |
| + AEM中的資產下載ZIP檔案中缺少[轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27140) |
| + [內容片段未包含在AEM Assets授權中](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26616) |
| + [儘管擁有讀取存取權，但在Assets檢視中仍受限制發表評論](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26928) |
| + [(Dynamic Media)迴轉集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在處理狀態 |
| + [數位資產管理(DAM)轉譯不符合AEM中的原始檔案](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中產生的智慧型裁切轉譯 |
| + [(Dynamic Media)修正AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的視訊上傳、處理和轉譯問題 |
| + [(Asset Link) Adobe Asset Link讓連結在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)時處於無法存取狀態 |
| + AEMaaCS中Dynamic Media與DAM卡片檢視之間的[視訊縮圖不相符](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)從Dynamic Media匯出資產和中繼資料 |
| + [在AEM as a Cloud Service中處理大型MP4檔案的資產失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media視訊播放器無法在較低層環境中運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（具有OpenAPI的Dynamic Media）啟用受限的Assets存取以IMS使用者群組為基礎的Open API的Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [當具有ZIP壓縮格式的Tiff檔案上傳到AEM Assets時，不會產生轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM會在100K代號之後截斷從大型PDF擷取的文字](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [（動態媒體）變更DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的動態媒體URL |
| + [解決AEMaaCS中非管理員使用者的中繼資料結構可見性問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF影像轉譯的[(Dynamic Media)背景色彩變更問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS資產輪換問題導致後續輪換不可見](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Dynamic Media)解決Adobe Experience Manager 6.5 Dynamic Media中智慧型裁切的損壞影像問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加Photoshop Firefly API整合的單一部分資產上傳限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)針對PDF檔案在AEM環境中解決Dynamic Media資產名稱差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [在Adobe Experience Manager (AEM) as a Cloud Service — 資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中，某些影像未顯示縮圖轉譯 |
| + [ (Dynamic Media) Dynamic Media一般設定頁面未開啟](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)解決AEM中Dynamic Media的視訊檔案中的音訊問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在AEM as a Cloud Service中自動標籤新上傳的資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在AEM中將JWT移轉至OAuth後，智慧標籤功能無法運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決AEM Managed Services中的共用連結問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + AEM Dynamic Media中的[(Dynamic Media)資產處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[ (Dynamic Media)資產同步處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中視訊資產的自訂縮圖](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的影像中繼資料差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放至AEM Assets Web UI失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Dynamic Media)正在解決AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的資產處理問題 |
| + Adobe Experience Manager as a Cloud Service中大型PDF的[文字擷取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解決InDesign ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)資產連結連線問題 |
| + [(Asset Link) Adobe Asset Link外掛程式網路錯誤：無法連線伺服器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步處理使用者建議](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |

| 疑難排解AEM Forms |
|--- |
| + [(Dynamic Media)迴轉集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在處理狀態 |
| + [數位資產管理(DAM)轉譯不符合AEM中的原始檔案](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中產生的智慧型裁切轉譯 |
| + [(Dynamic Media)修正AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的視訊上傳、處理和轉譯問題 |
| + [(Asset Link) Adobe Asset Link讓連結在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)時處於無法存取狀態 |
| + AEMaaCS中Dynamic Media與DAM卡片檢視之間的[視訊縮圖不相符](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)從Dynamic Media匯出資產和中繼資料 |
| + [在AEM as a Cloud Service中處理大型MP4檔案的資產失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media視訊播放器無法在較低層環境中運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（具有OpenAPI的Dynamic Media）啟用受限的Assets存取以IMS使用者群組為基礎的Open API的Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [當具有ZIP壓縮格式的Tiff檔案上傳到AEM Assets時，不會產生轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM會在100K代號之後截斷從大型PDF擷取的文字](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [（動態媒體）變更DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的動態媒體URL |
| + [解決AEMaaCS中非管理員使用者的中繼資料結構可見性問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF影像轉譯的[(Dynamic Media)背景色彩變更問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS資產輪換問題導致後續輪換不可見](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal)使用OAuth伺服器對伺服器憑證啟用Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media)解決Adobe Experience Manager 6.5 Dynamic Media中智慧型裁切的損壞影像問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加Photoshop Firefly API整合的單一部分資產上傳限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)針對PDF檔案在AEM環境中解決Dynamic Media資產名稱差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [在Adobe Experience Manager (AEM) as a Cloud Service — 資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中，某些影像未顯示縮圖轉譯 |
| + [ (Dynamic Media) Dynamic Media一般設定頁面未開啟](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)解決AEM中Dynamic Media的視訊檔案中的音訊問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在AEM as a Cloud Service中自動標籤新上傳的資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在AEM中將JWT移轉至OAuth後，智慧標籤功能無法運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決AEM Managed Services中的共用連結問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal)共用連結下載問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + AEM Dynamic Media中的[(Dynamic Media)資產處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[ (Dynamic Media)資產同步處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中視訊資產的自訂縮圖](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的影像中繼資料差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放至AEM Assets Web UI失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal編輯器和檢視器無法看到任何影像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media)正在解決AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的資產處理問題 |
| + Adobe Experience Manager as a Cloud Service中大型PDF的[文字擷取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解決InDesign ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)資產連結連線問題 |
| + [(Asset Link) Adobe Asset Link外掛程式網路錯誤：無法連線伺服器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步處理使用者建議](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |

## 三欄表格

| 疑難排解AEM Sites | 疑難排解AEM Assets | 疑難排解AEM Forms |
|--- |--- |--- |
| + [(Dynamic Media)迴轉集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在處理狀態 | + AEM中的資產下載ZIP檔案中缺少[轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-27140) | + [(Dynamic Media)迴轉集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在處理狀態 |
| + [數位資產管理(DAM)轉譯不符合AEM中的原始檔案](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [內容片段未包含在AEM Assets授權中](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26616) | + [數位資產管理(DAM)轉譯不符合AEM中的原始檔案](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) |
| + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中產生的智慧型裁切轉譯 | + [儘管擁有讀取存取權，但在Assets檢視中仍受限制發表評論](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26928) | + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中產生的智慧型裁切轉譯 |
| + [(Dynamic Media)修正AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的視訊上傳、處理和轉譯問題 | + [(Dynamic Media)迴轉集在AEM Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26715)中卡在處理狀態 | + [(Dynamic Media)修正AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的視訊上傳、處理和轉譯問題 |
| + [(Asset Link) Adobe Asset Link讓連結在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)時處於無法存取狀態 | + [數位資產管理(DAM)轉譯不符合AEM中的原始檔案](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26639) | + [(Asset Link) Adobe Asset Link讓連結在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)時處於無法存取狀態 |
| + AEMaaCS中Dynamic Media與DAM卡片檢視之間的[視訊縮圖不相符](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [未在AEMaaCS](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26873)中產生的智慧型裁切轉譯 | + AEMaaCS中Dynamic Media與DAM卡片檢視之間的[視訊縮圖不相符](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) |
| + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)從Dynamic Media匯出資產和中繼資料 | + [(Dynamic Media)修正AEM](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26533)中的視訊上傳、處理和轉譯問題 | + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)從Dynamic Media匯出資產和中繼資料 |
| + [在AEM as a Cloud Service中處理大型MP4檔案的資產失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610) | + [(Asset Link) Adobe Asset Link讓連結在使用InDesign](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26922)時處於無法存取狀態 | + [在AEM as a Cloud Service中處理大型MP4檔案的資產失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610) |
| + [(Dynamic Media) Dynamic Media視訊播放器無法在較低層環境中運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) | + AEMaaCS中Dynamic Media與DAM卡片檢視之間的[視訊縮圖不相符](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26677) | + [(Dynamic Media) Dynamic Media視訊播放器無法在較低層環境中運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) |
| + [（具有OpenAPI的Dynamic Media）啟用受限的Assets存取以IMS使用者群組為基礎的Open API的Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [(Dynamic Media)使用API](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26902)從Dynamic Media匯出資產和中繼資料 | + [（具有OpenAPI的Dynamic Media）啟用受限的Assets存取以IMS使用者群組為基礎的Open API的Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) |
| + [當具有ZIP壓縮格式的Tiff檔案上傳到AEM Assets時，不會產生轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [在AEM as a Cloud Service中處理大型MP4檔案的資產失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26610) | + [當具有ZIP壓縮格式的Tiff檔案上傳到AEM Assets時，不會產生轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) |
| + [AEM會在100K代號之後截斷從大型PDF擷取的文字](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) | + [(Dynamic Media) Dynamic Media視訊播放器無法在較低層環境中運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26871) | + [AEM會在100K代號之後截斷從大型PDF擷取的文字](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) |
| + [（動態媒體）變更DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的動態媒體URL | + [（具有OpenAPI的Dynamic Media）啟用受限的Assets存取以IMS使用者群組為基礎的Open API的Dynamic Media](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26103) | + [（動態媒體）變更DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的動態媒體URL |
| + [解決AEMaaCS中非管理員使用者的中繼資料結構可見性問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [當具有ZIP壓縮格式的Tiff檔案上傳到AEM Assets時，不會產生轉譯](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-23916) | + [解決AEMaaCS中非管理員使用者的中繼資料結構可見性問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) |
| + Dynamic Media中TIFF影像轉譯的[(Dynamic Media)背景色彩變更問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [AEM會在100K代號之後截斷從大型PDF擷取的文字](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26785) | + Dynamic Media中TIFF影像轉譯的[(Dynamic Media)背景色彩變更問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) |
| + [AEMaaCS資產輪換問題導致後續輪換不可見](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [（動態媒體）變更DM Assets](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-17628)的動態媒體URL | + [AEMaaCS資產輪換問題導致後續輪換不可見](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) |
| + [(Brand Portal)使用OAuth伺服器對伺服器憑證啟用Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) | + [解決AEMaaCS中非管理員使用者的中繼資料結構可見性問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26655) | + [(Brand Portal)使用OAuth伺服器對伺服器憑證啟用Brand Portal](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-22074) |
| + [(Dynamic Media)解決Adobe Experience Manager 6.5 Dynamic Media中智慧型裁切的損壞影像問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) | + Dynamic Media中TIFF影像轉譯的[(Dynamic Media)背景色彩變更問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26637) | + [(Dynamic Media)解決Adobe Experience Manager 6.5 Dynamic Media中智慧型裁切的損壞影像問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) |
| + [增加Photoshop Firefly API整合的單一部分資產上傳限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [AEMaaCS資產輪換問題導致後續輪換不可見](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26528) | + [增加Photoshop Firefly API整合的單一部分資產上傳限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) |
| + [(Dynamic Media)針對PDF檔案在AEM環境中解決Dynamic Media資產名稱差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [(Dynamic Media)解決Adobe Experience Manager 6.5 Dynamic Media中智慧型裁切的損壞影像問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26367) | + [(Dynamic Media)針對PDF檔案在AEM環境中解決Dynamic Media資產名稱差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) |
| + [在Adobe Experience Manager (AEM) as a Cloud Service — 資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中，某些影像未顯示縮圖轉譯 | + [增加Photoshop Firefly API整合的單一部分資產上傳限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26450) | + [在Adobe Experience Manager (AEM) as a Cloud Service — 資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中，某些影像未顯示縮圖轉譯 |
| + [ (Dynamic Media) Dynamic Media一般設定頁面未開啟](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [(Dynamic Media)針對PDF檔案在AEM環境中解決Dynamic Media資產名稱差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26461) | + [ (Dynamic Media) Dynamic Media一般設定頁面未開啟](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) |
| + [(Dynamic Media)解決AEM中Dynamic Media的視訊檔案中的音訊問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) | + [在Adobe Experience Manager (AEM) as a Cloud Service — 資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26233)中，某些影像未顯示縮圖轉譯 | + [(Dynamic Media)解決AEM中Dynamic Media的視訊檔案中的音訊問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) |
| + [在AEM as a Cloud Service中自動標籤新上傳的資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [ (Dynamic Media) Dynamic Media一般設定頁面未開啟](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25294) | + [在AEM as a Cloud Service中自動標籤新上傳的資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) |
| + [在AEM中將JWT移轉至OAuth後，智慧標籤功能無法運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Dynamic Media)解決AEM中Dynamic Media的視訊檔案中的音訊問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-26197) | + [在AEM中將JWT移轉至OAuth後，智慧標籤功能無法運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) |
| + [解決AEM Managed Services中的共用連結問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) | + [在AEM as a Cloud Service中自動標籤新上傳的資產](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25925) | + [解決AEM Managed Services中的共用連結問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) |
| + [(Brand Portal)共用連結下載問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) | + [在AEM中將JWT移轉至OAuth後，智慧標籤功能無法運作](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25889) | + [(Brand Portal)共用連結下載問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25771) |
| + AEM Dynamic Media中的[(Dynamic Media)資產處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) | + [解決AEM Managed Services中的共用連結問題](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25903) | + AEM Dynamic Media中的[(Dynamic Media)資產處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) |
| + Adobe Experience Manager (AEM) Dynamic Media中的[ (Dynamic Media)資產同步處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) | + AEM Dynamic Media中的[(Dynamic Media)資產處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25607) | + Adobe Experience Manager (AEM) Dynamic Media中的[ (Dynamic Media)資產同步處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) |
| + [正在更新AEM as a Cloud Service中視訊資產的自訂縮圖](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) | + Adobe Experience Manager (AEM) Dynamic Media中的[ (Dynamic Media)資產同步處理失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25885) | + [正在更新AEM as a Cloud Service中視訊資產的自訂縮圖](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) |
| + [Adobe Experience Manager (AEM) Assets中的影像中繼資料差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [正在更新AEM as a Cloud Service中視訊資產的自訂縮圖](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25829) | + [Adobe Experience Manager (AEM) Assets中的影像中繼資料差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) |
| + [將資產資料夾拖放至AEM Assets Web UI失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [Adobe Experience Manager (AEM) Assets中的影像中繼資料差異](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25828) | + [將資產資料夾拖放至AEM Assets Web UI失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) |
| + [(Brand Portal) Brand Portal編輯器和檢視器無法看到任何影像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) | + [將資產資料夾拖放至AEM Assets Web UI失敗](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-21865) | + [(Brand Portal) Brand Portal編輯器和檢視器無法看到任何影像](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-20177) |
| + [(Dynamic Media)正在解決AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的資產處理問題 | + [(Dynamic Media)正在解決AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的資產處理問題 | + [(Dynamic Media)正在解決AEM as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25525)中的資產處理問題 |
| + Adobe Experience Manager as a Cloud Service中大型PDF的[文字擷取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) | + Adobe Experience Manager as a Cloud Service中大型PDF的[文字擷取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) | + Adobe Experience Manager as a Cloud Service中大型PDF的[文字擷取限制](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25518) |
| + [(Asset Link)解決InDesign ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)資產連結連線問題 | + [(Asset Link)解決InDesign ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)資產連結連線問題 | + [(Asset Link)解決InDesign ](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25562)中的Adobe Experience Manager (AEM)資產連結連線問題 |
| + [(Asset Link) Adobe Asset Link外掛程式網路錯誤：無法連線伺服器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link外掛程式網路錯誤：無法連線伺服器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) | + [(Asset Link) Adobe Asset Link外掛程式網路錯誤：無法連線伺服器](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25506) |
| + [(Dynamic Media) Dynamic Media同步處理使用者建議](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) Dynamic Media同步處理使用者建議](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) | + [(Dynamic Media) Dynamic Media同步處理使用者建議](https://experienceleague.adobe.com/en/docs/experience-cloud-kcs/kbarticles/ka-25471) |
