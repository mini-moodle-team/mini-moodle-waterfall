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

<!-- 系統要做什麼、不做什麼 -->

### 1.2 Product Value（產品價值）

<!-- 為什麼需要這個系統？對使用者有什麼幫助？ -->

### 1.3 Intended Audience（目標使用者）

<!-- 教師、學生各自是誰 -->

### 1.4 Intended Use（預期用途）

<!-- 不同角色會如何使用系統 -->

### 1.5 General Description（整體描述）

<!-- 系統的整體概述 -->

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
