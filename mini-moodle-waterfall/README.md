# Mini Moodle（Waterfall + AI）

模仿 Moodle 的課程網站。本 repo 為軟體工程期中專案 **Waterfall + AI** 組的工作區，依 Waterfall 流程進行到 Requirement Analysis（需求分析），並完成 UML 與架構雛形。

- Agile + AI 組 repo：（待補連結）
- 繳交日期：2026/11/11

## 組員與角色

| 角色 | 組員 | 主要工作 |
| --- | --- | --- |
| Requirements Analyst（RA，需求分析師） | （待填） | 需求訪談、SRS 功能需求、需求變更 |
| System Designer（SD，系統設計師） | （待填） | SRS 非功能需求、UML、架構雛形 |
| QA & Configuration Manager（QA，品管與組態管理） | （待填） | Repo 管理、審查、追溯表、AI Log 彙整 |

## 文件導覽

| 路徑 | 內容 |
| --- | --- |
| `docs/SRS.md` | 軟體需求規格書（Software Requirements Specification） |
| `docs/interview-notes/` | 需求訪談紀錄（需求的來源） |
| `docs/traceability.md` | 需求追溯表：需求 ↔ 來源 ↔ UML ↔ 程式模組 |
| `docs/review-issues.md` | 審查中發現的問題（模糊、遺漏、AI 編造的需求） |
| `uml/` | UML 原始碼（PlantUML），`uml/images/` 放匯出的圖 |
| `src/` | 架構雛形（技術選型確定後建立） |
| `ai-log/` | AI 使用紀錄 |

## 工作流程

1. 從 `main` 開新 branch，例如 `srs/functional-requirements`。
2. 完成後開 Pull Request，填寫 PR 模板。
3. 至少一位**非作者**組員審查並核准後才能 merge；不得 merge 自己的 PR。
4. 每個階段的文件簽核後，才進入下一階段：

```
需求獲取 → SRS（簽核）→ UML（簽核）→ 架構雛形（審查）
```

## AI 使用規則

- AI 可以起草，只有組員可以決定採用。
- 每次使用 AI 都記錄在 `ai-log/`：工具/模型、問了什麼、採用或拒絕及原因、花費時間。
- 不在 prompt 中放入個資或機密資料。
