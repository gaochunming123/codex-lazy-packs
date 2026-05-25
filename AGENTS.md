# codex-lazy-packs — AGENTS.md

## 專案入口

專案名稱：codex-lazy-packs
專案用途：Codex 懶人包與教學指南
主要工作目錄：G:\我的云端硬盘\opencloud_0525
GitHub repo：gaochunming123/codex-lazy-packs
預設 branch：main

## Obsidian 對應筆記

Obsidian vault：G:\我的云端硬盘\2ndbrain
專案駕駛艙：codex-lazy-packs/專案工作流程.md

## 工作桌 + 三個家

- 工作桌：G:\我的云端硬盘\opencloud_0525
- GitHub：gaochunming123/codex-lazy-packs
- Obsidian：G:\我的云端硬盘\2ndbrain + codex-lazy-packs/專案工作流程.md
- Firebase：暫未使用

## 同步規則

開工時：
- 使用 `startup` 流程
- 讀本檔
- 讀 Obsidian 駕駛艙
- 檢查 Git 狀態
- 不自動 pull / commit / push

收工時：
- 使用 `shutdown` 流程
- 更新 Obsidian 駕駛艙
- 如規則、路徑、專案邊界改變才更新本檔
- 需要時 commit + push GitHub

新專案初始化時：
- 使用 `project-init` 流程

## 檔案結構

```
opencloud_0525/
├── AGENTS.md              # 本檔，AI 助理專案規則
├── README.md              # 專案說明
├── .gitignore             # Git 忽略規則
├── 04.5-連接-Firebase-資料庫.md  # 懶人包：Firebase 連接
├── 07-初始化班級工具工作模式.md    # 懶人包：專案初始化
├── skills_claude/         # Claude 版 SOIL 簡報技能
│   ├── README.md
│   ├── soil-html-deck/
│   ├── soil-image-deck/
│   └── soil-teaching-deck/
└── skills_codex/          # Codex 版 SOIL 簡報技能
    ├── soil-html-deck/
    ├── soil-image-deck/
    └── soil-teaching-deck/
```

## 主要檔案

入口檔：
- 04.5-連接-Firebase-資料庫.md
- 07-初始化班級工具工作模式.md
設定檔：.gitignore
部署位置：GitHub Pages（公開 repo）

## 不要做

- 不要把每日進度寫進 AGENTS.md
- 不要自動納入無關 git 變更
- 不要把 API key、token、密碼寫進 repo
- 不要儲存學生姓名；正式資料只用座號與班級代號
- skills_codex/ 和 skills_claude/ 的內容不要互相覆蓋
