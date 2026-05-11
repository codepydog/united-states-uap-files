# #077 DOW-UAP-D75：跟到追不上的 UAP，speed 比飛機快、走直線同高

![page-1](page-1.jpg)

2024-07-14，一架 USAF ISR 機在亞丁灣戰區先支援 NAVCENT 後 retask 給 AFCENT。第一個任務段才執行 1 小時 43 分鐘，05:17Z 就觀測到 1 個 UAP，飛機嘗試跟蹤，但「UAP'S SPEED WAS FASTER THAN THE [己方平台] FLYING SPEED」，最後「FOLLOWED THE UAP TILL THE DISTANCE BECAME TOO FAR TO FOLLOW」。19 小時 40 分鐘任務裡，UAP 是資訊量最高的觀測。其餘時間都是 NAVCENT 加 AFCENT 標準 target development，narrative 寫 NSTR（Nothing Significant To Report）。

[#076 D74](../151-dow_uap_d74_mission_report_syria_nov_2023/report.md) 使用相同 41 欄 UAP 資料卡格式，D75 多了「己方主動嘗試追蹤」這個動作。

## 任務時間軸

| 時刻 (UTC, 07-14) | 事件 |
|---|---|
| 02:22Z | 起飛 |
| 03:00Z | Time On Station |
| 03:34Z | ISR 1（NAVCENT support）抵達 38P MT 51[?]11[?] |
| 05:17Z | **觀測 1X UAP** IVO 38P MT 53[?]17[?]（ISR 1 段內）|
| 09:25Z | Cleared off target, proceeded to next tasking |
| 10:41Z - 21:30Z | ISR 2（AFCENT support，retasked）IVO 38P MV 24[?]81[?] |
| 21:30Z | Cleared off, RTB |
| 21:42Z | Called off station |
| 22:38Z | Handed back |
| 22:59Z | Landed |

Mission 總長約 19 小時 40 分鐘（02:22Z 起飛到 22:59Z 降落）。MISREP 編號 10194673。

## UAP 41 欄資料卡

### Encounter 基本資料

| 欄位 | 值 |
|---|---|
| Initial Contact DTG | **140517:00Z JUL 24**（2024-07-14 05:17Z）|
| UAP Event Type | UAP Incident |
| MDS Type / Asset Type | 1.4a, 1.4g 遮蔽 |
| Friendly Aircraft Location | 38P MT 64[1.4a]53[1.4a] |
| Friendly Aircraft Altitude/Depth | 1.4g 遮蔽 |
| Friendly Aircraft Trajectory | ALL（多向）|
| Friendly Aircraft Speed | 1.4g 遮蔽 |
| First Coordinate | 38P MT 53[?]17[?] |
| First Seen Radius | 5 |
| Last Coordinate | 38P MT 22[?]49[?] |
| Last Seen Radius | 5 |
| Kinetic Altitude | LOW |
| Kinetic Depth | UNKNOWN |
| Kinetic Velocity | 1.4a 遮蔽 |
| Kinetic Trajectory | **NW**（西北向）|
| UAP Date of DoD Acquisition | 140517:00Z JUL 24 |

### UAP 物理特性

| 欄位 | 值 |
|---|---|
| UAP Maneuverability Observations | **STRAIGHT FLIGHT PATH AT SAME ALTI** |
| UAP Response to Observer Actions | UNKNOWN |
| UAP Physical State | 1.4g 遮蔽 |
| UAP Propulsion Means | UNKNOWN |
| UAP Under Intelligent Control | UNKNOWN |
| UAP Signatures | 1.4g 遮蔽 |
| UAP Advanced Capabilities | UNKNOWN ABOUT ADVANCED CAPABILITIES AND/OR MATERIALS |
| UAP RF Frequency | 未填 |
| UAP RF Duration | 未填 |
| Observer Assessment of UAP | Benign |

### 互動與後果

| 欄位 | 值 |
|---|---|
| UAP Reaction to Observation, Interrogation, Engagement | **[1.4a] FOLLOWED THE UAP TILL THE DISTANCE BECAME TOO FAR TO FOLLOW** |
| UAP Anomalous Characteristics / Behaviors | **UAP'S SPEED WAS FASTER THAN THE [1.4a, 1.4g] FLYING SPEED** |
| Observation Interrogation of UAP | NO |
| Observer Engagement of UAP | NO |
| UAP Effects on Persons | NO |
| UAP Effects on Equipment | NONE |
| UAP Objects/Material Recovered | NO |

## "Followed till too far to follow" 的物理含義

D75 的觀測 narrative 集中在兩個 ANSI-style 欄位：UAP Reaction 與 UAP Anomalous Characteristics。逐字保留：

> UAP Reaction to Observation, Interrogation, Engagement (yes/no; if yes, describe):
> [1.4a] FOLLOWED THE UAP TILL THE DISTANCE BECAME TOO FAR TO FOLLOW
>
> UAP Anomalous Characteristics / Behaviors:
> UAP'S SPEED WAS FASTER THAN THE [1.4a, 1.4g] FLYING SPEED

整起事件：MQ-9 / ISR 機追了 UAP，UAP 速度比 ISR 機快，最後 ISR 機追不上加 UAP 出視距。

MQ-9 Reaper 巡航速度約 170-220 KIAS（200-250 mph），dash 最大約 240 KIAS（280 mph）。AFCENT 戰區其他 ISR 平台像 RC-135 / U-2 巡航速度也類似（U-2 巡航 410 KTAS，但無法低空跟蹤）。

UAP 比這些平台快有幾層意涵：UAP 大於 280 mph 等級（如果是 MQ-9）；UAP 走 STRAIGHT FLIGHT PATH AT SAME ALTI（直線同高度）；Kinetic Trajectory: NW（西北向，與己方 ALL 多向相對）。

「ALL flying」加「UAP 走直線」加「UAP 比我快」三項組合提示這不是被動 wind drift，UAP 主動維持等速直線 NW，sensor 試圖跟拍但距離拉開。

## D74 + D75 對照

兩份 MISREP 都用 41 欄資料卡格式、都是 Tegtmeier 推薦解密（MDR 25-0072）、都是中東戰區 ISR：

| 項目 | D74（2023-11-09 Syria）| D75（2024-07-14 Gulf of Aden / AFCENT 戰區）|
|---|---|---|
| MISREP 編號 | 9381202 | 10194673 |
| MDR | 25-0072（同批次）| 25-0072 |
| 解密推薦者 | MG Tegtmeier | MG Tegtmeier |
| 任務 Operation | INHERENT RESOLVE | 1.4a 遮蔽 |
| 支援單位 | 不適用 | NAVCENT (ISR 1) + AFCENT (ISR 2) |
| Activity Description | TARGET DEVELOPMENT | ISR |
| UAP 觀測時間 | RTB 階段 21:53Z | ISR 1 段 05:17Z |
| UAP 描述 | BOUNCY BALL | No shape given（UAP Description: "UAP HAD..." narrative cut）|
| UAP Maneuverability | NONE | STRAIGHT FLIGHT PATH AT SAME ALTI |
| UAP Physical State | Solid | 1.4g 遮蔽 |
| UAP Propulsion | UNK | UNKNOWN |
| UAP Intelligent Control | NO | UNKNOWN |
| UAP Speed | ~424 KN | 比己方平台快（具體 1.4a 遮蔽）|
| Observer Assessment | Benign | Benign |
| Observer Engagement | NO | NO |
| Followed | 否（UAP 自己 pass）| 是（飛機追蹤直到距離過遠）|
| UAP Duration | 7 min | 不明（追到 out of range）|

D74 的 UAP 是「被動經過」，D75 是「我方主動追蹤、追不上」。

## 兩個觀測座標格的地理意義

UAP 首次接觸：38P MT 53[?]17[?]。UAP 最後接觸：38P MT 22[?]49[?]。

38P 是 UTM zone，MT 是 MGRS 100km 格。MT 53 到 MT 22 對應的位移是 31 km west 加 32 km north，約 44 km NW 直線距離（與 Kinetic Trajectory NW 一致）。

MGRS zone 38P 涵蓋紅海南端、亞丁灣、葉門、北衣索比亞 / 厄利垂亞 / 索馬利亞蘭。38P MT 100km 格對應葉門中南部到亞丁灣海岸。標題「Gulf of Aden」對應這個 region 沒問題，但細看 MT 格實際位置可能在葉門海岸線 inland 端，不純粹是海上。

ISR 1 為 NAVCENT support，第一段 UAP 觀測是支援 CTF 153 / CMF 紅海護航或反胡塞武裝任務。亞丁灣 2023-2024 是胡塞攻擊國際航運的高熱區，CTF 153（Combined Task Force 153 / OPERATION PROSPERITY GUARDIAN）由美國海軍主導護航。胡塞與伊朗常見的 Shahed-136 / 191 衍生型速度都低於 200 mph 且會發出 RF，D75 narrative 偏向未知 high-speed 平台這個解讀。

## 解密路徑與 D74 同步

D75 metadata 與 D74 一致：

- MDR 編號: 25-0072（與 D74 同批次）
- 解密官: MG Brandon R. Tegtmeier, USCENTCOM Chief of Staff
- Recommended on: 2025-06-02（與 D74 同日）
- 原訂解密日: 2049-07-14

兩份在 2025-06-02 同日被推薦解密，USCENTCOM 在那一天集中處理了一批含 41 欄資料卡的近期 UAP MISREP。D74（2023）加 D75（2024）兩份都是 SECRET // REL TO USA, FVEY（五眼釋出），這個 caveat 比 D62-D65 的 SECRET // NOFORN 更寬，五眼盟國也可看到原文。

## 影像規格與來源

| 屬性 | 內容 |
|---|---|
| 格式 | PDF（8 頁 MISREP 表格 + 41 欄 UAP 資料卡）|
| 影像化解析度 | 150 DPI 轉 JPEG |
| 來源 | USCENTCOM，編號 MDR 25-0072 |
| 原始機密等級 | SECRET // REL TO USA, FVEY |
| 解密日期（原訂） | 2049-07-14 |
| 解密日期（推薦）| 2025-06-02 |
| 解密官 | MG Brandon R. Tegtmeier, USCENTCOM Chief of Staff |
| AARO 釋出 | Approved for Release to AARO |
| 公開日 | 2026-05-08 |
| MISREP 編號 | **10194673** |
| 事件時間 | 2024-07-14 05:17Z（UAP first contact）|
| 任務時段 | 02:22Z 起飛 → 22:59Z 降落（19 小時 40 分鐘）|
| 事件地點 | 亞丁灣戰區（MGRS 38P MT 區，葉門 / 紅海南端）|
| 觀測平台 | 1.4a/1.4g 遮蔽 |
| 支援 Operation | NAVCENT (ISR 1) + retasked to AFCENT (ISR 2) |
| 任務類型 | ISR 加 Target Development |
| Primary Sensor | FMV |
| UAP 行為 | **STRAIGHT FLIGHT PATH AT SAME ALTI** |
| UAP 速度 | **比己方平台快**（具體值 1.4a 遮蔽）|
| UAP 軌跡 | NW（kinetic trajectory NW）|
| UAP 高度 | LOW kinetic altitude |
| UAP First Coord | 38P MT 53[?]17[?]（radius 5）|
| UAP Last Coord | 38P MT 22[?]49[?]（radius 5）|
| UAP 移位距離 | ~44 km NW（從首到末座標推算）|
| 己方反應 | **FOLLOWED THE UAP TILL THE DISTANCE BECAME TOO FAR TO FOLLOW** |
| UAP Physical State | 1.4g 遮蔽 |
| UAP Propulsion | UNKNOWN |
| UAP Intelligent Control | UNKNOWN（比 D74 的 NO 更模糊）|
| UAP Signatures | 1.4g 遮蔽 |
| Observer Assessment | Benign |
| Weather | DID NOT PREVENTED IMINT（原文如此，雙重否定 sic）|
| 直接下載 | <https://www.war.gov/medialink/ufo/release_1/dow-uap-d75-mission-report-gulf-of-aden-july-2024.pdf> |
| 官方 portal | [war.gov/UFO/#DOW-UAP-D75](https://www.war.gov/UFO/#DOW-UAP-D75,%20Mission%20Report,%20Gulf%20of%20Aden,%20July%202024) |

## 相關案件

- [#076 D74 敘利亞 2023-11-09](../151-dow_uap_d74_mission_report_syria_nov_2023/report.md)：8 個月前同 MDR 25-0072 批次、同 41 欄資料卡格式、bouncy ball UAP 424 KN。
- [#056 D44 Gulf of Aden 2020-10-15](../056-dow_uap_d44_range_fouler_gulf_of_aden_october_2020/report.md)：同 region 約 4 年前案件，172 ATKS MQ-9 觀測「貼海面 + 熱致冷 + 不規則機動」三重 signature。
- [#045 D27 Gulf of Oman 2024-06-07](../045-dow_uap_d27_mission_report_gulf_of_oman_june_2024/report.md)：37 天前 AFSOC 3 SOS 觀測貼水面 140 KTS「圓柱條附底部」UAP，鄰近戰區。
- [#057 D48 1996](../057-dow_uap_d48_air_force_space_booster_risk_report_1996/report.md)：D 系列非 UAP 案件，可作為文件批次脈絡對照。
