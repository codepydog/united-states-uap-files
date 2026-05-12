# #107 FBI Photo A1：一切都被擦掉了，只剩一個小黑點

![photo](photo.png)

打開 A1 是一張幾乎沒有東西的照片。

均勻的灰色背景，看不出地形，沒有天空線索，也沒有任何視覺特徵。畫面四邊用十二條黑色長條把 HUD metadata 全部蓋掉，左右各三條、上下各三條，整齊到不像隨機塗抹，比較像是審查員按欄位逐塊處理過。

剩下能看的東西只有三件：中央的十字準星、準星刻度旁邊一個白色的「5」字、還有準星正中央偏左那個**幾乎只有一兩個像素大的小黑點**。

那個小黑點，就是 FBI 給觀眾看的 UAP。

## 為什麼擦得這麼乾淨

軍方 EO/IR sensor 的原始畫面通常擠滿了文字。任務時間、平台高度、空速、heading、sensor 模式（Black Hot / White Hot / Lin / Log）、polarity 設定、焦距、FOV、目標座標、aircrew ID。這些都是後續分析必要的脈絡資訊。

A1 把所有的脈絡都拿掉了。十二條 1.4(a) 黑條切在 HUD 邊緣應該出現文字的位置：左上是日期時間、左中是 sensor pitch、左下是經緯度估算；右上是高度與空速、右中是 yaw、右下是機尾號；上方中段是 sensor 模式與 polarity；下方中段是 zoom 倍率與 FOV。

留下來的部分**只剩下視覺核心**：sensor 看到什麼、準星指向哪裡、那個物體大概是什麼形狀。

這是一個明確的釋出哲學。AARO 與 FBI 認為「**物體本身**」可以被公眾看見，但「**美軍在哪、什麼時候、用什麼設備看到的**」全部不能公開。任務的位置、平台的能力、時序關聯都會洩漏現役 ISR 模式，這些被連根挖掉。

## 那個「5」字

準星右側水平刻度上有個明顯的「5」。前面六張 A 系列截圖（A1-A7）這個「5」字都在同樣的位置、同樣的尺度，意味著 sensor 設定整個序列都保持一致。

它代表什麼，沒有上下文很難確認。常見的可能性有四種：

- **5 海里 range gate**：距離標示
- **5x zoom level**：放大倍率
- **5° pitch indicator**：俯仰角
- **Target ID 5**：第 5 號追蹤目標

如果是 target ID，那就意味著 A1 並非「**第一次接觸**」的瞬間，這場觀測之前還有 1 到 4 號目標。也意味著本系列只截圖了 5 號這個目標的觀測過程。但這只是其中一種可能。

## 為什麼選這張當系列的開頭

A1 是 8 張系列裡面**內容最少**的一張。沒有地形、沒有目標形狀細節、連目標位置都偏離準星中央。如果要選一張當作公開系列的「**接觸開始**」幀，這張的故事張力最低。

但 FBI 仍然把它放進來。

從序列邏輯來看，這張可能對應**剛抓到目標、還沒有 boresight、sensor 操作員正在把準星拉向物體的瞬間**。背景的無特徵感對應**高空巡航 sensor 視角**：還沒有拉低 sensor pitch 對準地面，所以畫面是模糊的中景。後面 A2 開始出現地表紋路，意味 sensor 角度往下調整，視野裡才有了參考物。

如果這個解讀成立，A1 就是 sensor 操作員「**我看到了**」、但還沒「**我抓到了**」的中間點。

## 影像規格與來源

| 屬性 | 內容 |
|---|---|
| 格式 | PNG, 8-bit RGBA |
| 尺寸 | 544 × 368 像素 |
| 檔案大小 | 94,513 bytes |
| 來源 | FBI（透過 DOW UAP 釋出包）|
| 釋出時間 | Late 2025 |
| 公開日 | 2026-05-08 |
| 機密遮蔽 | HUD 邊緣 12 條 1.4(a) 黑色長條（左 3、右 3、上 3、下 3）|
| 影像主體 | 中央十字準星、準星右側「5」字、準星偏左一個小黑點目標 |
| 直接下載 | <https://www.war.gov/medialink/ufo/release_1/fbi-photo-a1.png> |
| 官方 portal | [war.gov/UFO/#FBI Photo A1](https://www.war.gov/UFO/#FBI%20Photo%20A1) |

## 相關案件

- [#108-114 FBI Photo A2-A8](../108-fbi_photo_a2/report.md)：A1 之後的 7 張，地形逐漸出現、目標逐漸接近準星中心。
- [#053 D38 波斯灣 2020-05-14](../053-dow_uap_d38_range_fouler_debrief_middle_east_may_2020/report.md)：D 系列首份海軍 SPEAR Range Fouler Form，F/A-18 ATFLIR Black Hot 影像。A1 的影像家族可能來自類似 F/A-18 ATFLIR 平台。
- [#056 D44 Gulf of Aden 2020-10-15](../056-dow_uap_d44_range_fouler_gulf_of_aden_october_2020/report.md)：D 系列第 3 份 thermal cold 案件，含 sensor 下視角與 slant range 計算。
- [#048-050 D32 敘利亞 2024-10-20](../048_049_050-dow_uap_d32_mission_report_syria_october_2024/report.md)：D 系列首份 plasma signature 案件，AFSOC 12 SOS MQ-9 觀測 misshapen ball of white light。
