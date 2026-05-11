# #053 DOW-UAP-D38：2020-05-14 20:40Z 中東 ISR 任務中，海軍機組以 ATFLIR Black Hot / Linear gain 觀測到 1 個熱致冷「圓形實體」UAP 在水面之上做不規則運動，4x zoom 中失蹤

| 欄位 | 內容 |
|---|---|
| 報告類型 | **Range Fouler Debrief Form**（單頁表格，非 MISREP） |
| 識別碼 | DOW-UAP-D38 |
| 日期 | **2020-05-14**（mm/dd/yy 格式即 05/14/20） |
| **觀測時間** | **20:40:00Z** |
| Day/Night | **Night**（夜間） |
| **Mission Description** | **ISR** |
| Side No. | ISR |
| LFE（Large Force Exercise） | **Yes** |
| **Contact 位置** | **28°31'4"N, 49°52'4"E**（DD:MM:SS 格式 → **波斯灣 / 沙烏地阿拉伯外海**） |
| Contact Altitude | 20,000 ft |
| Altitude Constant | **Yes**（高度保持穩定） |
| Contact 移動 | **Yes** |
| Stable Trackfile | **Intermittent**（間歇追蹤） |
| **形狀** | **Round（圓形）** |
| **# of Contacts in "Group"** | **1** |
| 機隊 | **Navy**（推測，因表格含 BUNO 欄位 + AIM-9X self-track + ATFLIR autotrack 等海軍 F/A-18 系統欄位） |
| **感測器 / Polarity** | **ATFLIR pod, Black Hot, Linear gain**（IR mode） |
| 機密層級 | SECRET（caveat 遮蔽） |
| 釋出途徑 | USCENTCOM **MDR 26-0019**（與 D33 + D35 同批） |
| 公開日 | 2026-05-08 |
| PDF 頁數 | **1 頁**（單頁表格） |

![form](form.jpg)

## 為什麼 D38 是 D 系列首份「Range Fouler Debrief」表格

D 系列前 12 份檔案（D3, D10-D32, D33, D35）全部為**多頁 MISREP**（5-10 頁），結構為完整的任務報告 + 詳細 UAP 表單。**D38 是 D 系列首份「Range Fouler Debrief Form」單頁版本**，使用完全不同的通報模板：

| 項目 | MISREP（D10-D32 等） | Range Fouler Form（D38） |
|---|---|---|
| 頁數 | 5-10 頁 | **1 頁** |
| 通報單位 | Air Force（USAF / AFSOC / AFRC / ANG） | **Navy**（表格欄位含 BUNO, AIM-9X, ATFLIR） |
| Originator | 33 SOS, 50 ATKS, 196 ATKS, etc. | **遮蔽**（表格設計為去識別化）|
| 機密層級 | SECRET // NOFORN | SECRET（caveat 遮蔽）|
| 詳細欄位 | 數十項（aircrew, location, sensor, UAP 詳細） | **約 20 欄位**（compact） |
| 用途 | 完整任務記錄 + UAP 通報 | **SPEAR 系統去識別化 UAP 通報**（用於統計分析） |

「**SPEAR**」（Sensor Performance Evaluation and Reporting）是海軍空中作戰中心（NAWDC）建立的飛行員觀測通報系統，**專為 UAP / Range Fouler / Intercept 案例設計**，最早源自 2019 年海軍 AIMSISS 計畫。表格上的明示說明：

> "This information is for contact only. SPEAR sanitizes all reports of identifying information. Absolutely no identifying information for aircrew or squadron will be recorded for analysis."
>
> 「此資訊僅供聯繫之用。SPEAR 會清除所有報告中的識別資訊。絕對不會記錄任何飛行員或中隊的識別資訊用於分析。」

這就是為什麼 D38 表格將 Last Name / First Name / Rank / Squadron / Crew Position 等欄位設為「僅聯繫用、不留存」。**Range Fouler Form 是海軍版本的 UAP 通報，與空軍 MISREP 的設計理念完全不同**。

## 1. UAP 觀測核心內容

機組描述（手寫填入「Description and Interaction」欄位）：

> "While performing an ISR tasking (UL TN/Black Hot/Lin), a solid white object flew through the FOV. There was a temporary loss of the object but re-acquired shortly thereafter. The crew was able to follow the object as it appeared to make erratic movements above the water. During the follow, crew was able to obtain 4x zoom on the object but lost the object due to poor track placement. While following, the sensor operator was continuously manipulating the sensor to maintain eyes on the object. This is apparent by the waves of the water in the background being visible and not being visible."

> 「在執行 ISR 任務（**UL TN / Black Hot / Lin** 設定）期間，一個實體白色物體穿過 FOV（視野）。物體一度短暫消失但隨即重新捕捉。機組能夠追蹤該物體在水面之上做出**不規則運動**。追蹤期間機組將 sensor 拉到 4x zoom，但因 track placement 不佳而失去目標。追蹤期間，sensor operator 持續調整 sensor 以保持鎖定。背景中水面波浪一下可見、一下不可見，可見 sensor 操作之頻繁。」

關鍵技術術語解析：

- **UL TN**：Upper Left, Target Narrow（ATFLIR 視野設定，narrow FOV 高解析）
- **Black Hot**：IR polarity，熱物體呈黑色、冷物體呈白色
- **Lin**：Linear gain mode（vs. log mode，對均勻熱對比場景表現較佳）
- **「Solid white object」+ Black Hot polarity** = **物體相對背景為冷的（cold-against-warm）**

「**Solid white in Black Hot**」是 D 系列**第二份「熱致冷（thermally cold）」UAP 案件**，前一份為 [#042+#043 D23 UAE 2023-10-24](../042_043-dow_uap_d23_mission_report_uae_october_2023/report.md)。**這個 signature 在白晝水面背景中具強烈異常意義**：

- 水面白天被太陽加熱，在 IR Black Hot 中通常呈深色（熱）
- 一個物體呈白色（冷）+ 在水面上方移動 → 物體本身比海水冷
- 普通飛機、無人機、飛彈引擎本身高熱，不可能呈現「solid white」
- 候選：氣球（內部冷氣）、冷卻設備、低溫材質物體、未知物體

但本案為**夜間（Night）20:40Z** → 海水在夜間反而保溫（thermal inertia），仍可能比物體本身溫暖。

## 2. 地理脈絡：波斯灣 28°31'N, 49°52'E

座標轉換 28°31'4"N, 49°52'4"E 對應**波斯灣中部**，具體位置在：

- **沙烏地阿拉伯東部省份外海**（達曼 Dammam 東北約 100 km）
- **巴林南方約 100 km**
- **卡達半島東北方約 150 km**
- **伊朗 Lavan 島西南約 200 km**

這片海域是**美國第五艦隊（5th Fleet）**主要活動區，常駐美軍航母戰鬥群（CSG）、巡防艦、F/A-18 戰機從 USS Eisenhower / Truman / Reagan 等 carrier 操作。2020-05 期間在波斯灣執勤的美海軍 CSG 包括：

- USS Dwight D. Eisenhower（CSG 8）
- USS Harry S. Truman（CSG 4）

任務型態欄位「**ISR**」對應海軍 F/A-18E/F Super Hornet 在 LFE（Large Force Exercise，大型聯合演習）中執行的偵察任務。本案發生時機（夜間 20:40Z）與「LFE: Yes」共構，意味本案是在**夜間大規模演習期間**的觀測。

## 3. 機動特徵：「erratic movements above the water」

「**不規則運動**」是 D 系列中極少見的形容詞，過往案件多用「直線」「90 度轉彎」「漂浮」「在原地」「分離」等具體描述。「Erratic」（雜亂、無規律）暗示：

- 物體並非沿可預測軌道飛行
- 物體機動方向多次改變
- 機組無法以一般氣動模型解釋

對應其他 D 系列水面案件：

| 案件 | 機動描述 |
|---|---|
| D3（2020 阿拉伯灣） | 4 個 UAP 分 3 波，無明確機動 |
| D27（2024 Gulf of Oman） | 直線貼水面 140 KTS |
| **D33（2023 東地中海）** | **Sharp 90 degree turns** |
| D35（2023 東地中海） | 直線飛向陸地 |
| **D38（2020 波斯灣）** | **Erratic movements above the water** |

「Erratic」可能涵蓋「多次 90 度轉彎」（D33 模式）+ 高度起伏 + 速度變化。D38 機組描述強調「4x zoom 失去目標」，意味物體在 ATFLIR 視野中的位置改變過快、超出 sensor 自動追蹤能力。

## 4. 觀察

**(1) D38 是 D 系列首份海軍 Range Fouler Form 案件**：表格欄位包含 BUNO、AIM-9X self-track、ATFLIR autotrack，明確指向 F/A-18 系統。對應 [Navy UAP 通報歷史](https://en.wikipedia.org/wiki/Nimitz_UFO_incident)，2020 年 USS Theodore Roosevelt FLIR 案、2019 年 USS Russell case 之後 SPEAR 表格已標準化。

**(2) D 系列首次「Black Hot solid white」記錄**：對應 [#042+#043 D23](../042_043-dow_uap_d23_mission_report_uae_october_2023/report.md) 的「thermal cold」描述，但 D23 未提供 polarity 與 gain mode 細節。D38 提供完整 ATFLIR 設定（UL TN / Black Hot / Lin），是 D 系列**首份完整 IR sensor 操作參數記錄**。

**(3) 「Erratic above water」+ Altitude Constant: Yes 構成張力**：表格填寫 Altitude Constant: Yes，但描述卻是「erratic movements」。可能解讀：「高度大致穩定但水平方向不規則」即水平機動異常 + 垂直軸線穩定。對應 D33 的 90 度水平直角轉彎 + 貼水面（垂直軸線穩定）。

**(4) MDR 26-0019 是 D33/D35/D38 三案同批解密**：D33（USAF 33 SOS）、D35（USAF 33 SOS）、D38（Navy）來自完全不同軍種與年份（D38 = 2020，D33/D35 = 2023），但都在 USCENTCOM MDR 26-0019 同批次解密（2026-01-22）。意味本批次包含跨軍種 + 跨年份的 USCENTCOM AOR UAP 案件，由 MG Harrison 統一解密處理。

**(5) 表格「Apparent Propulsion」欄位空白**：D 系列 MISREP 多寫 UNK 或 NONE，D38 表格此欄留白未勾選任何選項。對應 [#045 D27](../045-dow_uap_d27_mission_report_gulf_of_oman_june_2024/report.md) 「UAP Propulsion: UNKNOWN」記錄方式不同，意味 SPEAR 表格允許「未填寫 = 未觀察到推進」的隱性解讀。

## 5. 跨檔案連結

- **[#042+#043 D23 UAE 2023-10-24](../042_043-dow_uap_d23_mission_report_uae_october_2023/report.md)**：D 系列另一「thermal cold」案件，但 USAF MQ-9 + 320/440 mph 直線。
- **[#047 D3 阿拉伯灣 2020](../047-dow_uap_d3_mission_report_arabian_gulf_2020/report.md)**：同年（2020）+ 同 USCENTCOM AOR + 同水面相關的最早 D 系列案件。D3 是 USAF MQ-9 編隊觀測，D38 是 Navy F/A-18 單機觀測，**構成 2020 年 USCENTCOM 跨軍種 UAP 觀測對**。
- **[#051 D33 + #052 D35 希臘 2023-10](../051-dow_uap_d33_mission_report_greece_october_2023/report.md)**：同 MDR 26-0019 解密批次，但東地中海 vs. 波斯灣兩個不同戰區。

## 6. 來源

- 原始檔案：[U.S. Department of War — DOW-UAP-D38, Range Fouler Debrief, Middle East, May 2020](https://www.war.gov/UFO/#DOW-UAP-D38,%20Range%20Fouler%20Debrief,%20Middle%20East,%20May%202020)
- PDF 直接下載：`https://www.war.gov/medialink/ufo/release_1/dow-uap-d38-range-fouler-debrief-middle-east-may-2020.pdf`
- 1 頁，Range Fouler Debrief Form
- USCENTCOM MDR 26-0019 解密（與 D33 / D35 同批）
- Approved for Release to AARO：2026-01-26
- 公開日：2026-05-08
- 注意：表格通過 SPEAR 系統去識別化處理，aircrew / squadron / BUNO 欄位資訊永久不可恢復
