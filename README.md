# Hi, I'm Andy Lin 👋

我是一名從工業系統整合與現場問題排查，轉向 **Backend / Cloud Engineering** 的軟體工程師。

過去的工作讓我熟悉真實系統環境中的 log 分析、版本確認、跨團隊溝通與問題追蹤；目前專注把這些經驗延伸到 Node.js 後端、REST API、PostgreSQL、Docker 與雲端部署。

## Featured Projects

### [Stellar Archive — AI Skill / Prompt 探索平台](https://2026nodeclass.github.io/frontend/)

四人團隊專案。我負責公開 Catalog API，以及將 React 的 Explore / PlanetDetail 從 mock data 改接 PostgreSQL backend。

- Node.js / Express / PostgreSQL 公開查詢與參數化搜尋
- React API client、動態 2D 星圖與單筆 Planet 載入
- loading、error、404 與 `AbortController` request lifecycle
- 使用 AI 協助理解 schema、產生第一版實作與 review；再以 seed、build、lint、request 和 Git diff 驗證
- 可驗證成果：[Backend commit](https://github.com/2026NodeClass/backend/commit/f6b6036b486d8358124a9e93deb57af6996b2325) · [Frontend commit](https://github.com/2026NodeClass/frontend/commit/83372df2934e2554d1a825cd31b3d196c3eb1e5d)

### [FitConnect — 健身課程預約平台](https://github.com/AndyLinStrongtyping/node-js-final-2026)

我的主要後端作品。以 Node.js、Express、TypeORM 與 PostgreSQL 實作會員、教練、課程、點數方案和預約流程。

- JWT authentication 與 USER / COACH 角色權限
- PostgreSQL 關聯模型與商業規則
- 預約 transaction + pessimistic lock，降低並行請求造成的超賣風險
- Docker Compose、Swagger、GitHub Actions
- 68 個 API / contract tests

### [Member Management API](https://github.com/AndyLinStrongtyping/node-js-week3-2026-main)

Express REST API 基礎作品，包含會員 CRUD、條件篩選、圖片上傳、Swagger UI 與 Jest / Supertest。

- 16 個整合測試
- HTTP status 與錯誤情境處理
- 跨 Windows、macOS、Linux 的上傳暫存路徑

### [Relational Database Lab](https://github.com/AndyLinStrongtyping/node-js-week8-2026)

以兩組資料模型練習 TypeORM EntitySchema、PostgreSQL migration、foreign key 與可重複執行的 seeder。

## Tech Stack

- **Backend:** Node.js、Express、JavaScript、REST API
- **Database:** PostgreSQL、SQL、TypeORM
- **Testing:** Jest、Supertest
- **DevOps:** Git、GitHub Actions、Docker、Docker Compose、Linux
- **Currently learning:** TypeScript、AWS、CI/CD、production monitoring

## What I Bring

- 能從現象、log 與版本差異逐步定位問題
- 重視可驗證的結果：測試、API 規格、健康檢查與部署文件
- 能把業務流程拆成資料模型、權限與邊界條件
- 熟悉與不同角色合作，會持續追蹤問題直到解決

## How I Use AI / Vibe Coding

我會用 AI 加速陌生 codebase 導覽、需求拆解、第一版實作與 edge-case review，但不把「AI 已產生程式」當作完成。我的流程是：

1. 先提供規格、schema、現有程式與責任邊界。
2. 把工作拆成可獨立驗收的小任務。
3. 人工決定 API contract、資料安全與錯誤處理。
4. 審查 AI 產出的 diff，避免修改到其他功能。
5. 以 test、build、lint、實際 request 與 Git history 驗證。

Stellar Archive 的 catalog API 與前端整合，是這套協作方式的實際案例；每項貢獻都有 commit 與 PR 可追溯。

## Current Goal

尋找能持續累積 **Backend + Cloud + Production** 經驗的 Junior Backend / Software Engineer 機會，特別關注 API、B2B SaaS、企業系統、自動化與智慧製造相關產品。
