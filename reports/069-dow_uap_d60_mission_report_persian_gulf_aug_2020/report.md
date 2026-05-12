# #069 DOW-UAP-D60：21 小時 8 分鐘任務的中段 UAP 觀測

![page-1](page-1.jpg)

2020-08-08 03:37Z，一架 MQ-9 Reaper 無人機（482 ATKS, 432 AEW）從代號 OKAS 的基地起飛，開始一場長達 21 小時 8 分鐘的任務。

任務目標是支援 NAVCENT（美海軍中央司令部）在阿拉伯灣、荷莫茲海峽、阿曼灣的行動。

起飛 3 小時 49 分鐘後，07:26Z，目標莢艙的 FMV（Full Motion Video）抓到 1 個 UAP，位於 MGRS 39RWL08[?]52[?]。

UAP 的動作只有一個字：「TRANSITTING」（穿越通過）。

5 小時 24 分鐘後，這架 Reaper 被伊朗防空指揮部用 guard 頻道喊話。

## MQ-9 Reaper 的 21 小時任務

報告 Mission ID MISREP 4592219，平台是 432 AEW（432nd Air Expeditionary Wing，內華達州 Creech AFB 的 MQ-9 母聯隊）旗下的 482 ATKS（482nd Attack Squadron）。

時間軸：

| 時刻（UTC, 8/8） | 事件 |
|---|---|
| 03:37 | 從 OKAS 起飛 |
| 03:59 | LRE（Launch Recovery Element）交棒 |
| 04:34 | 開始 SIGINT 收集（via AIRHANDLER）|
| 05:13 | 到達任務區，開始支援 NAVCENT |
| 07:26 | 觀測 1x UAP（FMV）|
| 12:50 | 被 IRANIAN AIR DEFENSE GUARD 喊話 |
| 22:56 | 完成 NAVCENT 支援 |
| 23:00 | 獲准 RTB |
| 00:17（8/9） | LRE 接手 |
| 00:45（8/9） | 於 OKAS 落地 |

總任務時間 21 小時 8 分鐘，期間累計 17.7 IMINT hours + 18.4 SIGINT hours（重疊收集）。

MQ-9 Block 5 在戰區的標準任務週期。F/A-18 / F-15E 一次飛行 4-6 小時極限，含空中加油也很難超過 10 小時。長時間 ISR 是無人機平台特有的能力。

## 「TRANSITTING」是什麼意思

報告的 OBSERVATION 區塊填寫如下：

| 欄位 | 內容 |
|---|---|
| Observed Activity Description | TRANSITTING |
| Method of Observation | FMV |
| Observation DTG | 080726:00ZAUG20 |
| Observed Activity Location | 39RVL90[?]53[?]（或 39RWL08[?]52[?]）|
| Aircraft Location | 39RWK95[?]5[?] |
| Aircraft Heading / Altitude / Airspeed | 全部空白 |
| Relative Bearing / Range / Killbox | 全部空白 |

「TRANSITTING」（轉場/穿越）是軍方術語，指物體經過觀測區但不停留、不互動。對比其他 D 系列描述：

- D3 阿拉伯灣：「multiple contacts」
- D38 中東：「range fouler」
- D55 敘利亞：「possible missile」
- D56 北阿拉伯海：「3 maintained relative course, speed, altitude」（編隊）
- D60：TRANSITTING

D60 的描述比上面幾份都單純。沒有加速、沒有編隊、沒有電子干擾、沒有形態變化。只是經過。

## UAP 觀測 + 伊朗防空喊話的同一份報告

兩個獨立事件出現在同一份 MISREP，間隔 5 小時 24 分鐘：

1. 07:26Z：UAP 觀測（不明物體穿越）
2. 12:50Z：伊朗防空指揮部 GUARD 喊話「standard call」

報告對伊朗喊話的描述：「PROFESSIONAL」、「STANDARD CALL」、「STANDARD RESPONSE」、「NO IMPACT TO THE MISSION」。意味飛機處於伊朗認為可主張管轄的空域邊緣，但雙方都按 SOP 處理。

時序上，Reaper 在 12:50Z 被喊話時位於：

- 高度 FL170（17,000 ft）
- 速度 110 KIAS（200 km/h，符合 MQ-9 巡航）
- 航向 200°（南南西方向，飛離伊朗）
- 位置 40RCP98[?]7[?]（MGRS 40 R CP 100km square，伊朗東南海岸附近）

5 小時前的 UAP 觀測位置 39RWL（39 R WL square）在更西邊，靠近阿拉伯半島南岸。Reaper 從 07:26Z 觀測位置往東飛 5 小時後到伊朗對面被喊話。

兩件事相隔 5 小時、沒有明顯關聯。MISREP 把兩者寫進同一份文件，是因為都屬於需要回報的非例行事件。

## ANDAS4 + AH_GMESH

報告 ACEQUIP 區塊：

- TGT Pod：ANDAS4（推測為 AN/DAS-4 或 AN/DAS-2 變體，MQ-9 的多光譜目標莢艙）
- Additional Avionics：AH_GMESH（AIRHANDLER + GMESH，SIGINT 收集系統）
- Air-to-Ground Weapons：1.4(a) 遮蔽（意味攜帶武器，數量遮）

FMV 是 ANDAS4 拍下的。MQ-9 的目標莢艙在追蹤地面目標時能做高解析度 EO/IR 拍攝，巡航速度下幾秒就能跟蹤一個移動目標。

UAP 在 FMV 中是「TRANSITTING」，意味物體有可辨識的飛行軌跡。但 OBSERVATION 區塊的 Aircraft Heading / Altitude / Airspeed / Range 都空白，可能是操作員沒能精確測量物體的速度與高度。

## 為什麼 declassification 寫 2045

報告 Admin 區塊：

- Classification：SECRET
- Caveats：REL TO USA, FVEY（Five Eyes 共享）
- Declassification Date：20450301（2045 年 3 月 1 日）

原本這份報告要等到 2045 年 3 月 1 日才會自動解密，2026 年 5 月 8 日 AARO 釋出包提前 19 年讓它見光。

「DECLASSIFY ON 25X1」是美國國安檔案的標準語法，25-year rule 的變體（X1 表示需個案審核，但仍以 25 年為基準）。2045 − 25 = 2020，剛好對應事件年份。AARO 法律強制提前釋出，繞過原本的時序。

## 影像規格與來源

| 屬性 | 內容 |
|---|---|
| 格式 | PDF（6 頁 MISREP 表格） |
| 影像化解析度 | 150 DPI 轉 JPEG |
| 來源 | USCENTCOM，編號 MDR 26-0038 to 26-0046 |
| 原始機密等級 | SECRET//REL TO USA, FVEY |
| 解密日期（原訂） | 2045-03-01 |
| 解密日期（實際 AARO 釋出） | 2026-03-20（提前 19 年）|
| 解密官 | MG Richard A. Harrison, USCENTCOM Chief of Staff |
| AARO 釋出 | Approved for Release to AARO |
| 公開日 | 2026-05-08 |
| **MISREP 編號** | **4592219** |
| **事件時間** | **2020-08-08 07:26Z** |
| **事件地點** | **MGRS 39RWL（推測阿拉伯半島南岸）**|
| **觀測平台** | **MQ-9 Reaper（482 ATKS, 432 AEW）** |
| **任務總時長** | **21 小時 8 分鐘** |
| **目標數量** | **1 個 UAP** |
| **目標描述** | **TRANSITTING**（穿越通過） |
| **觀測方法** | **FMV (Full Motion Video) via ANDAS4 目標莢艙** |
| **同期事件** | **12:50Z 伊朗防空 GUARD 喊話**（standard call/response）|
| FMV 處理 | DGS-1（Distributed Common Ground System-1, Langley）|
| 直接下載 | <https://www.war.gov/medialink/ufo/release_1/dow-uap-d60-mission-report-persian-gulf-august-2020.pdf> |
| 官方 portal | [war.gov/UFO/#DOW-UAP-D60](https://www.war.gov/UFO/#DOW-UAP-D60,%20Mission%20Report,%20Arabian%20Gulf,%20August%202020) |

## 相關案件

- [#068 D6 阿拉伯灣 2020](../068-dow_uap_d6_mission_report_arabian_gulf_2020/report.md)：同地區、同年代，但 7 頁中 6 頁全黑。
- [#066 D57 亞丁灣 2020-09](../066-dow_uap_d57_range_fouler_gulf_of_aden_sep_2020/report.md)：另一份 MQ-9 觀測（密西根 172 ATKS）。
- [#067 D58 NA 2020-10](../067-dow_uap_d58_range_fouler_na_oct_2020/report.md)：F-15E 攔截 + 電子干擾的高互動案。
- [#047 D3 阿拉伯灣 2020](../047-dow_uap_d3_mission_report_arabian_gulf_2020/report.md)：阿拉伯灣家族代表。
