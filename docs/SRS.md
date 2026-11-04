# Software Requirements Specification（軟體需求規格書）

**Project name：** Mini Moodle
**Date：**
**Version：** 0.1（草稿）
**By：** Mini Moodle Waterfall 組

### Version History（版本紀錄）

| 版本 | 日期 | 修改者 | 修改內容 | 修改原因 |

### Review History（審查紀錄）

| 日期 | 審查者 | 審查範圍（PR 編號） | 發現的問題 | 處理結果 |

### Approval History（簽核紀錄）

| 版本 | 簽核者 | 角色 | 日期 |


## Table of Contents

1. Introduction
2. Functional Requirements
3. External Interface Requirements
4. Non-functional Requirements
5. Assumptions and Dependencies
6. Definitions and Acronyms
7. References

---

## 1. Introduction

### 1.1 Product Scope（產品範圍）

Mini Moodle 是一個網頁版的課程管理系統，提供教師與學生在同一個平台上管理課程、發布公告、討論與繳交作業。

**本系統包含以下八項功能：**

| # | 功能 | 使用者 | 對應決定 |
| --- | --- | --- | --- |
| 1 | 註冊 | 教師、學生 | D-01 ~ D-04 |
| 2 | 登入 | 教師、學生 | D-00a、D-05 |
| 3 | 建立與管理課程 | 教師 | D-06 ~ D-08、D-10 ~ D-12 |
| 4 | 以課碼加入課程、退出課程 | 學生 | D-09、D-12 |
| 5 | 課程成員 | 教師、學生 | D-13 ~ D-15 |
| 6 | 公告 | 教師發布，學生查看 | D-16 ~ D-18 |
| 7 | 留言板 | 教師、學生 | D-19 ~ D-21 |
| 8 | 作業 | 教師建立與批改，學生繳交 | D-22 ~ D-28 |

**本系統不包含以下功能（列為未來功能）：**

| 功能 | 對應決定 |
| --- | --- |
| 寄送 Email（含 Email 登入、忘記密碼） | D-00a、D-00b |
| 教師驗證機制（例如教師驗證碼） | D-01 |
| 助教（TA）角色 | D-02 |
| 協同教師（一門課多位教師） | D-11 |
| 線上測驗、系統管理員後台、行事曆、私人訊息、學期成績總表 | D-29 |
| 中英文介面切換 | D-30 |
| 手機版介面 | D-31 |

### 1.2 Product Value（產品價值）

- 提供教師與學生共同使用的線上課程平台，讓課程資訊集中在同一個地方
- 教師可以建立課程、發布公告傳遞資訊，並出作業與批改，不需另外透過通訊軟體或 Email
- 學生輸入課碼即可加入自己修習的課程，並在課程頁查看公告、作業與成績
- 留言板讓課程相關的問題集中在課程內討論，教師與同學都看得到

### 1.3 Intended Audience（目標使用者）

| 使用者 | 說明 |
| --- | --- |
| 教師（Teacher） | 開設課程的人，註冊時選擇「教師」身分，以教職員編號作為帳號 |
| 學生（Student） | 修課的人，註冊時選擇「學生」身分，以學號作為帳號 |

每個帳號只能是教師或學生其中一種身分，註冊後不能更改（D-01、D-02、D-03）。本系統沒有系統管理員角色（D-29）。

### 1.4 Intended Use（預期用途）

**教師**

1. 註冊、登入
2. 建立課程，系統產生課碼後提供給學生
3. 編輯課程資訊、暫停課碼、查看成員名單、手動加入學生
4. 發布、編輯、刪除公告
5. 在留言板發言，並可刪除不當留言
6. 建立作業、查看繳交狀況、批改並發布成績

**學生**

1. 註冊、登入
2. 輸入課碼加入課程；加錯時可以自行退出
3. 查看公告、成員名單與課碼，可將課碼提供給尚未加入的同學
4. 在留言板發言，編輯或刪除自己的留言
5. 上傳作業檔案，截止前可重新繳交，並在教師發布後查看成績與評語

### 1.5 General Description（整體描述）

Mini Moodle 參考學校使用的 Moodle 系統，保留其最核心的課程功能。系統以網頁形式提供，介面為中文，只支援桌上型電腦瀏覽器（D-30、D-31）。帳號由使用者自行註冊，系統不寄送任何 Email（D-00a）。

需求衝突的處理原則為「實作最簡單、先做出可用系統」，詳見需求決定表 `docs/elicitation-notes/decision-table.md`。本系統與 Agile 組開發相同的八項功能範圍，但詳細需求由兩組各自決定。

## 2. Functional Requirements（功能需求）

需求撰寫格式：

> **FR-XX 需求名稱**：系統應……（一條需求只描述一件事，必須可驗證）
> - 來源：（例：學生訪談 #1）
> - 優先度：High / Medium / Low

### 2.1 帳號與登入

### 2.2 課程管理

### 2.3 以課碼加入課程

### 2.4 公告

### 2.5 留言板

## 3. External Interface Requirements（外部介面需求）

### 3.1 User Interface Requirements（使用者介面）

### 3.2 Hardware Interface Requirements（硬體介面）

### 3.3 Software Interface Requirements（軟體介面）

### 3.4 Communication Interface Requirements（通訊介面）

## 4. Non-functional Requirements（非功能需求）

需求撰寫格式：**NFR-XX 需求名稱**：系統應……（需包含可量測的條件）

### 4.1 Security（安全性）

### 4.2 Capacity（容量）

### 4.3 Compatibility（相容性）

### 4.4 Reliability（可靠性）

### 4.5 Scalability（擴充性）

### 4.6 Maintainability（可維護性）

### 4.7 Usability（易用性）

### 4.8 Other（其他）

## 5. Assumptions and Dependencies（假設與相依性）

| 編號 | 假設 | 若假設不成立的影響 | 來源 |
| --- | --- | --- | --- |
| AS-1 | 使用者註冊時會誠實選擇自己的身分，系統不驗證使用者是否真的是教師或學生。已知限制：一般使用者可自行註冊為教師並建立課程；團隊接受此限制，以優先完成可用系統。 | 學生可能註冊為教師並建立課程；教師驗證機制（例如教師驗證碼）列為未來功能 | D-01 |

## 6. Definitions and Acronyms（名詞定義與縮寫）

| Term | Definition |
| --- | --- |
| SRS | Software Requirements Specification，軟體需求規格書 |
| 課碼 | 學生加入課程用的代碼 |
|  |  |

## 7. References（參考資料）

- IEEE Recommended Practice for Software Requirements Specifications（IEEE 830）
- 課程投影片：3_Requirements
