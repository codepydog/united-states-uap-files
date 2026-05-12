# #104 PR47 INDOPACOM 2023：1 分 59 秒 IR 影片，感測器追蹤 3 處對比區，相對位置與方位固定

![cover](cover.jpg)

PR47 畫面中央是紅色 autotrack 環，鎖住一處對比區；環的上方還有兩個亮點水平並排。3 處對比區在感測器視角下保持 2 分鐘相對位置不變、方位不變。三個獨立物體不會湊巧維持精準幾何，所以剩兩種可能：要嘛它們黏在同一個剛體上，要嘛在做剛體編隊飛行。

## 影片內容

- 長度：1 分 59 秒（119.7 秒），1920×1080，30 fps
- 感測器：IR，HUD 含紅色 autotrack 環、青色十字準星，邊角多塊 1.4(a) 黑色遮蔽
- 3 處對比區可見於畫面中央區域：
  - 2 處對比區位於 autotrack 環上方，水平排列
  - 1 處對比區位於 autotrack 環內或正下方
- 3 處對比區的相對位置與方位在 2 分鐘內保持穩定
- HUD 邊框遭 1.4(a) 黑塊大量遮蔽

![~ t=10s 影片早段](frame-start.jpg)

![~ t=60s 紅色追蹤環中央 + 3 處對比區呈固定編隊](cover.jpg)

![~ t=110s 後段持續觀測](frame-end.jpg)

## 為什麼「相對位置固定」很關鍵

3 個對比區的相對位置與方位在 2 分鐘內保持穩定，可推得：

- 三點所構成的幾何在感測器視角下不變 → 三點可能黏附於同一剛體
- 或三點彼此維持精準編隊飛行（rigid formation flying）
- 排除「三個獨立物體湊巧出現在同一畫面」（隨機物體不會維持精準幾何）

候選解釋包括：

- 多旋翼 UAV（rotor blades 高速旋轉造成 3 個亮點？需要解析度與快門配合，IR 通常不會這樣顯示）
- 高空汽球攜帶多感測器吊艙
- 衛星發射後上面級殘骸（單一物體三個突出部）
- 真正未知

## 為什麼仍列為 unresolved

INDOPACOM 戰區廣大，2 分鐘影片無雷達 / IFF / RWR 交叉，且 HUD redaction 移除距離、方位變化率，無法解算剛體尺寸或姿態。

## 影像規格與來源

| 欄位 | 內容 |
|---|---|
| 系列 | DOW-UAP-PR47 |
| 地點 | INDOPACOM AOR（未細分） |
| 年份 | 2023 |
| 影片長度 | 1:59（119.7 秒） |
| 解析度 / fps | 1920×1080 / 30 fps |
| 感測器 | IR |
| 對比區數量 | 3 處，相對位置固定 |
| 對應 MISREP | 無 |
| 機密層級 | 原 SECRET，公開 cleared |
| 公開日 | 2026-05-08 |
| 釋出途徑 | 推測 INDOPACOM 解密通道 |
| 官方來源 | [DOW-UAP-PR47, Unresolved UAP Report, INDOPACOM, 2023](https://www.war.gov/UFO/#DOW-UAP-PR47,%20Unresolved%20UAP%20Report,%20INDOPACOM,%202023) |
| DVIDS 鏡像 | [DVIDS video 1006107](https://www.dvidshub.net/video/1006107/dow-uap-pr47-unresolved-uap-report-indopacom-2023) |

## 相關報告

- [#103 PR46 INDOPACOM 2024](../103-dow_uap_pr46_indopacom_2024/report.md)，同戰區案件，可對照「3 對比區固定編隊」與「橄欖球 + 3 突出物」兩種多元件幾何描述
- [#105 PR48 INDOPACOM 2024](../105-dow_uap_pr48_indopacom_2024/report.md)，同戰區同型 IR 影片但僅一處中央對比區，可對照「多目標」與「單目標」處理流程
- [#099 PR42 中東 2020](../099-dow_uap_pr42_middle_east_2020/report.md)，另一份長片（4:53）跨 AOR 對照，可比較模態切換 vs 多目標相對位置固定兩種 unresolved 訊號
