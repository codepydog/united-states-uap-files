# #095 PR38 中東 2013：1 分 46 秒 IR 影片，對比區形似八角星臂長交替，10 秒放大、30 秒離開後復現

![cover](cover.jpg)

PR38 是整個 PR 系列裡年代最早的影片，回到 2013 年的中東上空。畫面中央出現的東西很難用一般詞描述：八個臂，臂長交替長短，像一顆對稱失序的星。官方 caption 也只好寫成「octagonal contrast region with alternating arm lengths」。沒有 D 系列 MISREP 配對，2013 年的資料庫無法回溯比對現代無人機型錄或衛星發射記錄。

## 影片內容

- 長度：1 分 46 秒（106.4 秒），4:3 比例 IR 畫面，30 fps
- 感測器：IR，White Hot，HUD 含 N 北方標記與十字準星，邊角多塊 1.4(a) 黑色遮蔽
- 開頭：對比區進入畫面，形態被官方 caption 描述為「八角星，臂長交替」（octagonal contrast region with alternating arm lengths）
- 約 10 秒：感測器執行放大（zoom in），對比區尺寸放大
- 約 30 秒：對比區離開畫面後再次出現
- 無人聲、無 HUD annotation

![開頭對比區進入畫面](frame-start.jpg)

![~ t=50s 中段對比區持續可見](frame-mid.jpg)

![~ t=90s 對比區復現後段](frame-end.jpg)

## 為什麼未解

「八角星 + 臂長交替」是 PR 系列中對形狀描述最具體的 caption。可能候選：

- 鏡頭散射造成的星狀繞射圖樣（lens flare / spike artifact），但臂長交替不易由光學鏡頭自然產生
- 高度旋轉物體的 motion blur 殘影
- 感測器 dead pixel cluster 投影（已排除，因為對比區會移動）

AARO 未能歸入任何已知類別，且 2013 年資料無法與現代資料庫（無人機型錄、商業衛星發射）回溯比對，列為 unresolved。

## 影像規格與來源

| 欄位 | 內容 |
|---|---|
| 系列 | DOW-UAP-PR38 |
| 地點 | 中東（未細分） |
| 年份 | 2013 |
| 影片長度 | 1:46（106.4 秒） |
| 解析度 / fps | 1920×1080 / 30 fps（4:3 內容區） |
| 感測器 | IR（型號未知，2013 年常見為 MQ-1 / MQ-9 MTS-A/B） |
| 對應 MISREP | 無（公開資料中未指認對應 D 系列） |
| 機密層級 | 原 SECRET，公開 cleared |
| 公開日 | 2026-05-08 |
| 釋出途徑 | USCENTCOM MDR 25-0094 thru MDR 25-0099 |
| 官方來源 | [DOW-UAP-PR38, Unresolved UAP Report, Middle East, 2013](https://www.war.gov/UFO/#DOW-UAP-PR38,%20Unresolved%20UAP%20Report,%20Middle%20East,%202013) |
| DVIDS 鏡像 | [DVIDS video 1006088](https://www.dvidshub.net/video/1006088/dow-uap-pr38-unresolved-uap-report-middle-east-2013) |

## 相關報告

- [#099 PR42 中東 2020](../099-dow_uap_pr42_middle_east_2020/report.md)，另一份長片（4:53）中東 IR 影片，可對照 2013 vs 2020 長期觀測在 sensor 操作上的差異
- [#097 PR40 中東 2020](../097-dow_uap_pr40_middle_east_2020/report.md)，同為 AARO 對形態有具體 caption 的案件（白圈 U/I 標籤 vs 八角星描述）
- [#093 PR36 中東 2020](../093-dow_uap_pr36_middle_east_may_2020/report.md)，中東 PR 系列前段，可作為 PR 系列在中東 AOR 整體脈絡的入口
