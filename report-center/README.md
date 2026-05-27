# PM 工作流程報告

完整的端到端產品開發工作流程文檔，涵蓋從需求形塑到版本發布的四個核心階段。

## 📌 概述

這份報告整合了三個主要工作流程專案：
- **Shape Kickoff** — 需求形塑與提案確認
- **Spec Finalization** — 規格定案與文件化
- **TMS Release Note** — 版本發布通知

## 🔄 工作流程四大階段

### 1️⃣ 需求形塑 (Shape Kickoff)
從客戶需求釐清到提案產出。支援客戶案與內部案兩種情境。

**涉及 Skills：**
- `/shape-proposal` — 客戶提案腦力激盪
- `/build-prototype` — HTML 原型設計
- `/save-proposal` — 寫入合作案文件

### 2️⃣ 啟動執行 (Kickoff)
把已確認的需求轉譯為 Jira Story ticket。

**涉及 Skills：**
- `/kickoff-from-chat` — 從對話轉譯開票
- `/kickoff-from-proposal` — 從合作案轉譯開票

### 3️⃣ 規格定案 (Spec Finalization)
Sprint 驗收完成後，整理產品規格文件，寫入 Google Doc PRD。

**涉及 Skills：**
- `/write-spec` — 單票整理規格
- `/write-spec-batch` — 批次整輪規格

### 4️⃣ 版本發布 (Release Note)
目前已全自動化，固定每兩週 Sprint Demo 後自動撈取開發票務，產生版本發布說明，並通知相關利益者。

**涉及 Skills：**
- `/release-note` — 自動產生版本說明

## 📁 檔案結構

```
├── index.html                  # GitHub Pages 報告頁
├── README.md                  # 本文件
└── .nojekyll                  # GitHub Pages 靜態部署設定
```

## 🚀 快速開始

### 方式一：查看網頁版報告
1. 打開 `index.html`
2. 查看完整的四階段工作流程
3. 找到對應的 skill 使用說明

### 方式二：本地查看原始文件
1. 回到 workspace 中的來源專案資料夾（Shape_Kickoff、Spec_Finalization、TMS_Release_Note）
2. 查看 `CLAUDE.md` 了解專案用途
3. 進入 `.claude/skills/` 找到具體的 skill 定義

## 🛠️ 外部工具與認證

| 工具 | 用途 | 認證方式 |
|------|------|--------|
| Google Drive / Docs | 讀取合作案、寫入提案、更新 PRD | OAuth |
| Figma (MCP) | 設計系統元件庫 | figma-developer-mcp |
| Jira (MCP) | Story ticket 管理 | mcp-atlassian |
| Google Chat (MCP) | 自動發送版本發布通知 | mcp-google-workspace |
| Codebase | 搜尋現有實作 | 本地檔案讀取 |

## 📖 詳細說明

完整的工作流程解析、每個 skill 的詳細用法、輸出格式規則，請參見：
- 📄 **網頁版**：`index.html`
- 🌐 **語言切換**：頁面右上角可切換中文與英文版本
- 🔖 **資料來源**：每個步驟卡片標示 Drive、PRD、Codebase、Figma、Jira 或 Chat 等 input
- 📝 **原始文檔**：各專案的 `CLAUDE.md` 和 `.claude/skills/` 目錄

## 🔗 相關資源

- Shape Kickoff 專案：包含客戶提案、功能規劃、原型設計、ticket 開設的完整流程
- Spec Finalization 專案：規格整理與文件化工具
- TMS Release Note 專案：版本發布說明的自動產生與通知

## 📝 更新記錄

- **2026-05-27** — 初版發布，包含四個工作流程階段的完整文檔

---

**最後更新：2026-05-27**

涵蓋 Shape Kickoff、Spec Finalization 及 TMS Release Note 的完整工作流程文檔

Co-Authored-By: Oz <oz-agent@warp.dev>
