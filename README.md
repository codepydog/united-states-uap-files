# United States UAP Files

US Department of War 透過 PURSUE 系統解密公開的 UAP 檔案，中文索引與逐檔分析。

**網站版（建議閱讀體驗）**：<https://codepydog.github.io/united-states-uap-files/>

官方 portal：<https://www.war.gov/UFO/>

## 內容

161 條檔案，分為 10 個主題：

1. FBI 62-HQ-83894 案卷（1947–1968 飛碟潮）
2. 二戰到冷戰初期（1944–1955）
3. 事件摘要單冊
4. 1950s–60s 政府反應與目擊
5. NASA 太空任務（1965–1974）
6. 冷戰晚期外交電報（1985–2004）
7. 現代軍方任務報告（MISREP / Range Fouler，2016–2025）
8. 現代軍方未解 UAP 報告（PR，2013–2026）
9. FBI 現代靜止影像（2025）
10. 2023 美國西部目擊事件

完整索引、cover 縮圖、條目描述與報告連結請看[網站版](https://codepydog.github.io/united-states-uap-files/)或 [docs/index.md](docs/index.md)。

## 儲存庫結構

```
docs/
├── index.md                   # 網站首頁、完整分類索引
├── reports/<NNN>-<slug>/      # 149 個報告資料夾
│   ├── report.md              # 中文分析
│   ├── cover.jpg              # 封面圖
│   ├── *.jpg                  # 內文截幀／文件影像
│   └── source.mp4             # 影音原檔（gitignored）
└── uap-full-index.tsv         # 161 條 → folder 對照表
mkdocs.yml                     # 網站建置配置
requirements.txt               # Python 相依（mkdocs-material）
```

## 本地預覽

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
# 開 http://127.0.0.1:8000
```

## 授權

本儲存庫內容為對美國政府公開檔案的中文翻譯與分析。原始檔案為美國政府公開作品，無版權。中文翻譯與分析以 CC BY 4.0 釋出。
