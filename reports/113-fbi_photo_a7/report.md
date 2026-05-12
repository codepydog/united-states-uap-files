# #113 FBI Photo A7：目標突然變白了

![photo](photo.png)

打開 A7，第一眼就會發現有件事不對勁。

前面六張裡，目標都是一個**暗色**的圓塊，比背景更黑、形狀邊緣略圓。A7 的準星左下方仍然有個目標，位置與 A3、A5、A6 大致對得上，但這次它是**亮白色**的，不是黑色。

其他的東西全部沒變。準星十字、HUD 邊緣那十二條黑色長條、右側那個「5」，全部與前六張同款。背景變得比較均勻，沒有 A2 那種明顯的沙漠地表紋路，但有點像 A1 的霧灰質感。

只有目標的顏色翻了過來。

## 為什麼會翻過來

軍方 IR sensor 通常提供兩種顯示模式：**Black Hot** 與 **White Hot**。差別只在顯示反演：

- **Black Hot**：黑色 = 熱，白色 = 冷
- **White Hot**：白色 = 熱，黑色 = 冷

兩種模式對應同一個物理輸入。同一個物體，在 Black Hot 看起來黑、切到 White Hot 就變白。**這是顯示設定的問題，不是物體本身的變化**。

戰機與 ISR 平台的 sensor 操作員會根據場景對比度需求，**在飛行中切換 polarity**。沙漠白天用 Black Hot 比較容易識別熱的目標（引擎、車輛、人體）；夜間或低對比場景則切到 White Hot。這是常規操作。

如果 A1-A6 是 Black Hot 設定，目標呈黑色（比背景熱），那 A7 切到 White Hot 就會讓同樣的目標變白（仍然比背景熱），**沒有任何物理變化，只是顯示反演**。

這是最簡單的解讀。

## 但還有第二種解讀

如果 A1-A6 一直是 Black Hot，**而且** A7 也仍然是 Black Hot，那目標從黑變白意味著：

**這個物體從「比背景熱」變成了「比背景冷」**

物理上能在短時間內把熱訊號完全翻轉的物體不多。常規飛機、無人機、車輛的引擎與機體無法快速冷卻；它們即使熄火，也要幾分鐘才能與環境同溫。**沒有任何已知的常規載具能在 sensor 視野中即時改變熱訊號**。

但 D 系列已經累積了三筆「物體本身就是 thermal cold」的紀錄：
- [D23（UAE 上空）](../042_043-dow_uap_d23_mission_report_uae_october_2023/report.md)：兩個 UAP 在 ATFLIR Black Hot 中呈 solid white，被機組稱為 thermally cold
- [D38（波斯灣海面）](../053-dow_uap_d38_range_fouler_debrief_middle_east_may_2020/report.md)：F/A-18 ATFLIR Black Hot/Lin gain 設定下，一個 solid white 物體在水面上 erratic movement
- [D44（亞丁灣海面）](../056-dow_uap_d44_range_fouler_gulf_of_aden_october_2020/report.md)：MQ-9 在 Black Hot 中觀測到 bright white 圓形 + abrupt directional changes

A7 的「白色目標」如果是 Black Hot 設定下的呈現，**直接屬於這個 thermally cold 家族**。

## 兩種解讀的判別

要從 A7 本身判斷是 polarity 切換還是物體本身變冷，需要參考背景對比。

**Polarity 切換的證據**：整個畫面的「明暗分配」會反演。Black Hot 切到 White Hot，沙漠地表（白天熱）會從淺灰變深灰，天空（冷）會從深灰變淺灰。

**物體本身變冷的證據**：背景的明暗分配維持不變，只有目標一個元素改變顏色。

把 A7 與 A1 的灰度比對：A1 的背景是均勻中灰，A7 的背景也是均勻中灰，**亮度差不多**。如果是 polarity 切換，A7 的背景應該明顯反演（從 A1 的中灰變成相反的中灰，但因為原本就是中灰，反演後仍接近中灰，差別不容易看）。

換個方法：比對 A2 與 A7。A2 在 Black Hot 下沙漠地表偏白偏亮（沙地白天熱）。如果 A7 是 White Hot，沙漠地表會變深灰。但 A7 沒有 A2 那種明顯的地形紋路可以直接比對，看不出來。

兩種解讀都成立，**無法用單張 A7 排除任一種**。

## 為什麼 FBI 選了這一張

把這個問題擺一邊，回到 FBI 的選擇邏輯。

如果 A1-A8 真的是同一場觀測的關鍵幀，FBI 把 A7 放進來的意義在哪？

第一種可能，**展示物體外觀的多樣性**。讓觀眾看到同一目標在 Black Hot 與 White Hot 兩種模式下的對照：黑色與白色都不是物體「真正的顏色」，而是熱訊號的視覺呈現。這帶有教育意味，幫助公眾理解 IR sensor。

第二種可能，**留下足以辨識 thermal cold signature 的線索**。如果 A7 真的在 Black Hot 下呈現 thermally cold 物體，那 FBI 公開這張就是在向 UAP 研究社群暗示：「**這個案件與 D23 / D38 / D44 同類**」。沒有文字、沒有時間戳，但視覺證據在這。

第三種可能，**完全是另一場觀測**。A7 與 A1-A6 沒有時序關聯，FBI 只是把所有形態相似的截圖打包成一個系列。

沒有一個解讀能確定，但這就是 FBI 公開影像的特點：**留下可解讀的素材，但不替你解讀**。

## 影像規格與來源

| 屬性 | 內容 |
|---|---|
| 格式 | PNG, 8-bit RGBA |
| 尺寸 | 412 × 306 像素 |
| 檔案大小 | 88,727 bytes |
| 來源 | FBI（透過 DOW UAP 釋出包）|
| 釋出時間 | Late 2025 |
| 公開日 | 2026-05-08 |
| 機密遮蔽 | HUD 邊緣 12 條 1.4(a) 黑條（與 A1-A3 同款式）|
| **特殊元素** | **目標呈現為亮白色**（不同於 A1-A6 的暗色目標）|
| 直接下載 | <https://www.war.gov/medialink/ufo/release_1/fbi-photo-a7.png> |
| 官方 portal | [war.gov/UFO/#FBI Photo A7](https://www.war.gov/UFO/#FBI%20Photo%20A7) |

## 相關案件

- [#107-112 FBI Photo A1-A6](../107-fbi_photo_a1/report.md)：序列前段，目標都呈現為暗色塊。A7 是序列中首次出現的「白色目標」。
- [#042+#043 D23 UAE 2023-10-24](../042_043-dow_uap_d23_mission_report_uae_october_2023/report.md)：D 系列首份 thermal cold UAP 紀錄，ATFLIR Black Hot 中 solid white。
- [#053 D38 波斯灣 2020-05-14](../053-dow_uap_d38_range_fouler_debrief_middle_east_may_2020/report.md)：海軍 ATFLIR UL TN/Black Hot/Lin gain 設定下的 solid white 物體。
- [#056 D44 亞丁灣 2020-10-15](../056-dow_uap_d44_range_fouler_gulf_of_aden_october_2020/report.md)：Black Hot 中 bright white 圓形物體在 171 ft 海面上空 abrupt directional changes。
