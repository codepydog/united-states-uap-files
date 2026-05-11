# #107 FBI Photo A1：軍方 FLIR / 紅外線感測器靜止影像，中央十字準星瞄準的小黑點目標即 UAP，全幅 HUD metadata（時間、高度、速度、座標、sensor 模式、目標 ID）以 12 條 1.4(a) 黑色長條完全遮蔽，準星右側可見「5」字（疑為 range gate 或 zoom level 標示）

| 欄位 | 內容 |
|---|---|
| 報告類型 | **靜止影像**（PNG，**A 系列為 PNG 8-bit RGBA，B 系列為 PDF**）|
| 識別碼 | FBI Photo A1 |
| 影像格式 | **PNG 8-bit RGBA, 544 × 368 像素, 94,513 bytes** |
| 影像來源 | **FBI**（依 DOW UAP 釋出包分類） |
| 影像內容 | **軍方 FLIR / 紅外線感測器** 螢幕截圖 |
| 公開日 | 2026-05-08（**Late 2025** 釋出標記） |
| 機密層級 | 影像內 metadata 以 **1.4(a)** 黑條遮蔽（HUD 邊緣 12 條） |

![photo](photo.png)

## 為什麼 FBI Photo A1 是 D 系列軍方 sensor 紀錄影像的縮影

FBI Photo A1 是**美國國家 UAP 影像檔案首次以 FBI 名義公開的軍方 sensor 截圖**。從影像格式、HUD 佈局、遮蔽模式來看，A1 **與 2004-12-14 USS Nimitz「Tic Tac」FLIR1 截圖、2015 USS Theodore Roosevelt GIMBAL 截圖、2015 USS Theodore Roosevelt GOFAST 截圖**屬於同一影像家族（軍方 EO/IR 戰術 sensor pod 輸出）。

A1 的特殊性：

1. **完全靜止影像**（不是視頻幀）：意味 FBI 取得的是被擷取下來的單一畫面，非完整影片串流
2. **HUD metadata 全幅遮蔽**：12 條 1.4(a) 黑色長條覆蓋影像四邊
3. **僅保留視覺核心**：中央十字準星 + 小黑點目標 + 右側「5」字標示
4. **FBI 持有的軍方 sensor 影像**：意味 FBI 透過跨部門合作取得 USAF / USN / USA / USMC 的 sensor 紀錄，**對應 FBI 反情報（counterintelligence）對 UAP 相關威脅評估**

## 1. 影像視覺特徵詳細描述

**整體構圖**：

- **影像尺寸**：544 × 368 像素（橫式畫面比例約 1.48:1，**與標準軍方 sensor 顯示器 4:3 / 3:2 比例接近**）
- **影像格式**：PNG 8-bit RGBA 灰階
- **背景**：均勻灰色，**無明顯地形 / 海面波紋 / 雲層特徵**（推測為高空 IR 視場中的均勻天空或遠距離模糊背景）

**HUD 元素**：

- **中央十字準星（reticle）**：標準軍方 sensor pod 瞄準準星，含主十字線 + 多個刻度小齒（cardinal pitch ladder 風格）
- **準星上方刻度齒**：12-15 個垂直刻度
- **準星水平刻度齒**：包含左右兩側等間距刻度
- **準星正中央偏左**：**一個小黑點**——即被瞄準的 UAP 目標
- **準星右側標示「5」**：通常對應**距離標示（range gate）、zoom level、target ID 或 sensor 模式編號**

**1.4(a) 遮蔽結構**：

影像四邊共有 12 條黑色長條，覆蓋典型軍方 sensor HUD 中應顯示的：

| 位置 | 典型 HUD 內容（被遮蔽） |
|---|---|
| 頂部左 | 任務識別 / 任務日期 / 時間（Z 時區） |
| 頂部中 | sensor 模式、polarity（BHOT / WHOT / Lin / Log）|
| 頂部右 | 機體高度、空速、heading |
| 左邊 | sensor 俯仰角（pitch）、左偏向 |
| 右邊 | sensor 偏航角（yaw）、右偏向 |
| 底部左 | UAP 經緯度估算座標 |
| 底部中 | sensor 焦距、FOV（field of view）|
| 底部右 | 任務代碼、aircrew ID / 機尾號 |

**這個 HUD 遮蔽模式對應 D 系列 MISREP 中 GENTEXT/UAP 之外被遮蔽的「Friendly Aircraft」欄位群**。

## 2. 對應軍方 sensor 影像歷史脈絡

A1 影像格式對應以下公開 UAP 影像：

| 案件 | 來源 | 形式 |
|---|---|---|
| 2004-11-14 USS Nimitz Tic Tac (FLIR1) | F/A-18F ATFLIR | 1 分 16 秒影片 |
| 2015-01-21 USS Theodore Roosevelt GIMBAL | F/A-18F ATFLIR | 34 秒影片 |
| 2015-01-21 USS Theodore Roosevelt GOFAST | F/A-18F ATFLIR | 35 秒影片 |
| AARO 2023-08 「Middle East UAP Sphere」 | MQ-9 MTS-B | 1 分 9 秒影片 + 多張截圖 |
| **FBI Photo A1（2025 Late）** | **不明 sensor**（可能 ATFLIR / MTS-B / SNIPER LDP） | **單張靜止影像** |

A1 的「**單張靜止影像 + 完全 HUD metadata 遮蔽**」呈現方式，意味 FBI 認為**動態軌跡資訊**（速度、加速度、機動）或**地理 / 時序資訊**不可公開，但**目標的視覺外觀**可以。

## 3. 「準星中央小黑點」的物理意涵

在 IR sensor Black Hot polarity 模式下：

- **黑色 = 熱**
- 灰色 = 中等溫度
- 白色 = 冷

如果 A1 是 Black Hot polarity，準星中央的**小黑點**意味目標**比背景溫暖**——可能是：

1. **常規飛機 / 無人機**（引擎熱）
2. **彈道飛彈 / 火箭羽流**
3. **熱源點目標**（如熱氣球的燃燒器）
4. **UAP 本身具熱訊號**

但若 A1 是 White Hot polarity：

- 白色 = 熱
- 黑色 = 冷

則小黑點**比背景冷**——對應 [#053 D38](../053-dow_uap_d38_range_fouler_debrief_middle_east_may_2020/report.md) + [#056 D44](../056-dow_uap_d44_range_fouler_gulf_of_aden_october_2020/report.md) + [#042+#043 D23](../042_043-dow_uap_d23_mission_report_uae_october_2023/report.md) 等 D 系列「**thermal cold UAP**」signature。

**沒有 HUD polarity 標示，無法直接判定**，但 D 系列中 thermal cold UAP 已累積 3 案件，A1 是 thermal cold 的可能性需要進一步分析。

## 4. 觀察

**(1) FBI 持有軍方 sensor 影像意味跨部門 UAP 情報共享**：FBI 不直接執行軍方 ISR sensor 任務，但本影像由 FBI 公開，意味 FBI 透過跨部門合作（可能透過 AARO、USD(I&S)、AFOSI、NCIS 等）取得 USAF / USN / USA / USMC 的 sensor 影像。對應 [#061 D51](../061-dow_uap_d51_email_correspondence_pacific_time_zone_march_2023/report.md) 中 AFOSI CI 體系吸收民眾 UAP 報告的模式。

**(2) 「Late 2025」釋出時間意味本影像於 2025 年下半年首次公開**：對應 AARO 在 2024-2025 期間積極推動 UAP 影像公開的政策動向。

**(3) HUD metadata 完全遮蔽意味影像最高價值在「視覺外觀」**：與 D 系列 MISREP 重視文字描述（速度、高度、機動）不同，A1 重視**物體本身的視覺呈現**。意味 AARO 認為視覺特徵已足以協助公眾理解 UAP，**動態 / 地理資訊則仍需保護**。

**(4) 單張靜止影像 vs. 視頻**：D 系列前案多為文字 MISREP，A1 是首份**靜止影像實體**。對應 [Section 8 PR（Unresolved UAP Report）](../../README.md#pr)中 28 份影片 / 影像案件，部分可能對應 A1 同類影像。

**(5) 影像 RGBA 8-bit 但內容為灰階**：意味原始 sensor 輸出為灰階（單通道 IR），編碼為 RGBA 是為了相容性（PNG-A 標準）。**Alpha 通道實際無透明度資訊**。

**(6) 「5」字標示的可能解讀**：
   - **5 nautical miles range gate**（5 海里距離標示）
   - **5x zoom level**（5 倍變焦）
   - **5° pitch indicator**（5 度俯仰）
   - **Target ID 5**（第 5 號目標）
   
   **無 HUD 上下文無法確認**，需參考 D 系列 SPEAR Range Fouler Form 等案件的 sensor 設定常見值。

## 5. 跨檔案連結

- **[#053 D38 波斯灣 2020-05-14](../053-dow_uap_d38_range_fouler_debrief_middle_east_may_2020/report.md)**：D 系列首份海軍 SPEAR Range Fouler Form，F/A-18 ATFLIR Black Hot 影像。**A1 可能來自同類 F/A-18 ATFLIR 平台**。
- **[#056 D44 Gulf of Aden 2020-10-15](../056-dow_uap_d44_range_fouler_gulf_of_aden_october_2020/report.md)**：D 系列第 3 份 thermal cold 案件，含 sensor 下視角 + slant range 計算。**A1 若為 thermal cold，可與 D44 對照**。
- **[#048-050 D32 敘利亞 2024-10-20](../048_049_050-dow_uap_d32_mission_report_syria_october_2024/report.md)**：D 系列首份 plasma signature 案件，AFSOC 12 SOS MQ-9 觀測 misshapen ball of white light。

## 6. 來源

- 原始檔案：[U.S. Department of War — FBI Photo A1](https://www.war.gov/UFO/#FBI%20Photo%20A1)
- PNG 直接下載：`https://www.war.gov/medialink/ufo/release_1/fbi-photo-a1.png`
- 格式：PNG, 544 × 368, 8-bit RGBA, 94,513 bytes
- 釋出時間：Late 2025
- 公開日：2026-05-08
- 注意：影像內 HUD metadata 完全 1.4(a) 遮蔽（12 條黑色長條），無法直接判定 sensor 平台、polarity、時間、地點。影像本體呈灰階 IR 風格，與軍方 EO/IR 戰術 sensor 影像格式一致。
