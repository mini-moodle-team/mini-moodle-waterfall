# Mini Moodle Waterfall 組：工作流程

> 最後修改：2026/11/1

## 流程

1. 三人填表單決定詳細功能
2. RA 統計結果 → 決定表 PR
3. 各自寫 SRS 負責的部分（PR 主要由 QA 審查）
4. 三人審查整份 SRS → 簽核 v1.0
5. 進入 UML 與架構雛形（PR 主要由 QA 審查）

## SRS 分工

| 角色 | 負責章節 |
| --- | --- |
| RA | 1. Introduction、2. Functional Requirements、5. Assumptions and Dependencies、6. Definitions and Acronyms |
| SD | 3. External Interface Requirements、4. Non-functional Requirements |
| QA | 開頭三張紀錄表、審查 |

## UML 與架構雛形分工

| 角色 | 負責項目 |
| --- | --- |
| SD | 主要負責：UML、架構雛形 |
| QA | 協助 SD、審查 |
| RA | 處理需求變更（更新決定表與 SRS） |

## QA 負責的 SRS 開頭紀錄表

| 紀錄表 | 用途 | 欄位 |
| --- | --- | --- |
| Version History（版本紀錄） | 記錄 SRS 每個版本改了什麼 | 版本、日期、修改者、修改內容、修改原因 |
| Review History（審查紀錄） | 記錄每次審查的結果 | 日期、審查者、審查範圍（PR 編號）、發現的問題、處理結果 |
| Approval History（簽核紀錄） | 記錄階段簽核 | 版本、簽核者、角色、日期 |

## 共同規則：AI Usage Log

- 適用所有階段（需求、SRS、UML、架構雛形）
- 每次使用 AI 後，由使用 AI 的人記錄在 `ai-log/ai-usage-log.md`，並放進同一個 PR 一起送審
- 每筆紀錄包含：日期、階段、工具／模型、詢問內容、採用的內容、修改或拒絕的內容及理由、人工審查者、時間影響（節省或浪費）
