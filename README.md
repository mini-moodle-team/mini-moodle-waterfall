# Mini Moodle（Waterfall + AI）

模仿 Moodle 的課程網站。本 repo 為軟體工程期中專案 **Waterfall + AI** 組的工作區，依 Waterfall 流程進行到 Requirement Analysis（需求分析），並預計完成 UML 與架構雛形。

## 文件導覽

| 路徑 | 內容 |
| --- | --- |
| `docs/waterfall-workflow.md` | 工作流程與分工 |
| `docs/interview-notes/` | 需求獲取問卷回覆與需求決定表（SRS 需求的來源） |
| `docs/SRS.md` | 軟體需求規格書（Software Requirements Specification） |
| `uml/` | UML 原始碼（PlantUML），`uml/images/` 放匯出的圖 |
| `src/` | 架構雛形（技術選型確定後建立） |
| `ai-log/` | AI 使用紀錄 |

## 工作流程
每個階段的文件簽核後，才進入下一階段：
```
需求獲取 → SRS（簽核）→ UML（簽核）→ 架構雛形（審查）
```
詳細流程與分工見 [`docs/waterfall-workflow.md`](docs/waterfall-workflow.md)。

## AI 使用規則

- AI 可以起草，只有組員可以決定採用。
- 每次使用 AI 都記錄在 `ai-log/`：詢問內容、採用內容、修改或拒絕內容、理由、人工審查者、時間影響。
- 不在 prompt 中放入個資或機密資料。
