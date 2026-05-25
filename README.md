# codex-lazy-packs

Codex 懶人包與教學指南。

## 內容

- **懶人包指南**：Codex 使用教學，協助教師快速上手
  - `04.5-連接-Firebase-資料庫.md` — 連接 Firebase Cloud Firestore
  - `07-初始化班級工具工作模式.md` — 專案初始化與工作流程設定
- **SOIL 簡報技能**：AI 生成簡報的完整技能包
  - `skills_claude/` — Claude 版（soil-html-deck、soil-image-deck、soil-teaching-deck）
  - `skills_codex/` — Codex 版（同上）

## 工作模式

- **開工**：說「開工」→ AI 讀 AGENTS.md + Obsidian 駕駛艙 + 檢查 Git
- **收工**：說「收工」→ AI 更新 Obsidian 駕駛艙 + 必要時 commit & push
- **初始化**：說「新專案初始化」→ AI 建立專案基底

## 安全原則

- API key、token、密碼不 commit
- 學生資料只存座號與班級代號
- `.codex/`、`.claude/` 不納入版本控制

## 相關連結

- GitHub Pages：https://mathruffian-dot.github.io/codex-lazy-packs
- Obsidian 駕駛艙：`codex-lazy-packs/專案工作流程.md`
