# Batch-05 封面視覺驗證（PR19–PR35）

**時間**：2026-05-12
**範圍**：reports/079 – reports/092（共 14 個 folder）
**方法**：Read tool 視覺檢查 cover.jpg；沒有 cover 的 folder 標 `no_image_available`
**動作**：不動 README.md、不動 git

---

## 摘要

| 狀態 | 數量 | folder |
|---|---|---|
| `keep`（封面有趣、UAP-themed） | 3 | 079, 084, 092 |
| `keep_marginal`（可保留但偏弱） | 1 | 091 |
| `no_image_available`（folder 無圖檔） | 10 | 080, 081, 082, 083, 085, 086, 087, 088, 089, 090 |

---

## 逐 folder manifest

### 有 cover.jpg（4 個）

#### 079 — dow_uap_pr19_video_middle_east_may_2022
- **狀態**：`keep`
- **觀察**：黑白 IR sensor 截圖，畫面中央偏下可見細長深色物體與淺色拖尾，背景為陸地紋路（疑似海岸線或地表），畫面有 redaction 黑塊與 reticle 角標。對比強、UAP-themed 明顯。
- **動作**：保留 cover.jpg。

#### 084 — dow_uap_pr26_video_uae_october_2023
- **狀態**：`keep`
- **觀察**：sensor frame，中央 cyan 十字 reticle、右下 `N` 方位指示、左側有一個淺色物體脫離 reticle，雲層紋路明顯。雖然物體不大，但 HUD + 對比都到位。
- **動作**：保留 cover.jpg。

#### 091 — dow_uap_pr34_video_greece_october_2023
- **狀態**：`keep_marginal`
- **觀察**：純灰雜訊背景，中央 cyan reticle、頂部 `N`，幾乎看不到明確物體（畫面中段一片極淡的暗影）。HUD 在但 subject 偏弱。
- **動作**：folder 內無其他 frame-*.jpg / keyframe-*.jpg 可換，保留現有 cover.jpg；建議後續若能從原 mp4 重抽 keyframe 再評估。

#### 092 — dow_uap_pr35_video_greece_october_2023
- **狀態**：`keep`
- **觀察**：藍灰天空、左上方雲團、右下角海面/海岸線紋路、中央完整 reticle + N 方位指示。畫面構圖最像經典 UAP IR 影片截圖。
- **動作**：保留 cover.jpg。

---

### 無圖檔（10 個）

以下 folder 內僅有 `report.md`，原始 mp4 連結未能解析、無 frame 抽取結果。README 對應「照片」欄位已是 `—` placeholder，本批次無 swap 可做。

| folder | 狀態 |
|---|---|
| 080-dow_uap_pr20_image_kuwait_may_2022 | `no_image_available` |
| 081-dow_uap_pr21_video_iraq_may_2022 | `no_image_available` |
| 082-dow_uap_pr22_video_syria_july_2022 | `no_image_available` |
| 083-dow_uap_pr23_video_iraq_december_2022 | `no_image_available` |
| 085-dow_uap_pr27_video_uae_october_2023 | `no_image_available` |
| 086-dow_uap_pr28_video_greece_january_2024 | `no_image_available` |
| 087-dow_uap_pr29_video_uae_june_2024 | `no_image_available` |
| 088-dow_uap_pr31_video_syria_october_2024 | `no_image_available` |
| 089-dow_uap_pr32_video_syria_october_2024 | `no_image_available` |
| 090-dow_uap_pr33_video_syria_october_2024 | `no_image_available` |

**後續建議**（不在本次任務範圍）：若日後拿到 mp4，可從 DoW 官方 PR 頁面或 YouTube mirror 重抽 keyframe；目前 README placeholder `—` 保持原狀即可。
