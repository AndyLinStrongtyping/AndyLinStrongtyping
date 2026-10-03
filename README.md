# Hi, I'm Andy Lin 👋

我是一名從工業系統整合與現場問題排查，轉向 **Backend / Cloud Engineering** 的軟體工程師。

過去的工作讓我熟悉正式環境中的 log 分析、版本確認、跨團隊溝通與問題追蹤；目前專注把這些經驗延伸到 Node.js 後端、REST API、PostgreSQL、Docker、CI/CD 與雲端部署。

## Featured Projects

### [Stellar Archive Backend](https://github.com/AndyLinStrongtyping/stellar-archive-backend)

AI Skill / Prompt 知識庫的 Express API。我的主要責任是公開 Catalog API，並在個人作品集版本補上 Production 導向的品質改善。

- Node.js / Express / PostgreSQL / TypeORM
- 參數化搜尋、JWT、USER / ADMIN 權限與個人收藏隔離
- 作者、來源、授權、相容 Agent、版本與更新時間 metadata
- Node tests、GitHub Actions、deployment smoke test、source commit SHA
- [可驗證的原始 Backend 貢獻](https://github.com/2026NodeClass/backend/commit/f6b6036b486d8358124a9e93deb57af6996b2325)

### [Stellar Archive Frontend](https://github.com/AndyLinStrongtyping/stellar-archive-frontend)

以 2D 星圖與 Three.js 3D 銀河探索 AI Skill / Prompt。我的主要責任是把 Explore / PlanetDetail 從 mock data 改接真實後端。

- React 19 / Vite / Canvas / Three.js / GSAP
- Catalog API 串接、搜尋篩選、loading / error / 404 狀態
- 首頁即時服務狀態與真實資料筆數
- Skill 來源與授權資訊、CI build / lint、source SHA
- [可驗證的原始 Frontend 貢獻](https://github.com/2026NodeClass/frontend/commit/83372df2934e2554d1a825cd31b3d196c3eb1e5d)

### [Stellar Archive Early Prototype](https://github.com/AndyLinStrongtyping/stellarskill)

早期產品與視覺原型，保留從靜態前端演進到真實 Backend + Production 驗證的脈絡；已清除 `node_modules` 與 `dist` 等生成檔。

### [FitConnect](https://github.com/AndyLinStrongtyping/node-js-final-2026)

Node.js、Express、TypeORM 與 PostgreSQL 的線上課程預約 API。

- JWT authentication 與 USER / COACH 角色權限
- 預約 transaction + pessimistic lock，處理併發超賣
- Docker Compose、Swagger、GitHub Actions
- 68 個 API / contract tests

### [Member Management API](https://github.com/AndyLinStrongtyping/node-js-week3-2026-main)

Express REST API，包含會員 CRUD、分頁、圖片上傳、Swagger UI 與 Jest / Supertest。

### [Relational Database Lab](https://github.com/AndyLinStrongtyping/node-js-week8-2026)

以測試資料模型練習 TypeORM EntitySchema、PostgreSQL migration、foreign key 與可重複執行的 seeder。

## Tech Stack

- **Backend:** Node.js、Express、JavaScript、REST API
- **Database:** PostgreSQL、SQL、TypeORM
- **Testing:** Node test runner、Jest、Supertest
- **DevOps:** Git、GitHub Actions、Docker、Docker Compose、Linux
- **Currently learning:** TypeScript、AWS、CI/CD、production monitoring

## How I Use AI / Vibe Coding

我把 AI 當成 codebase 導讀、需求拆解、初稿實作與 edge-case review 的協作工具，不把「AI 生成」當成完成條件：

1. 先理解需求、schema、既有程式與責任邊界。
2. 把工作拆成可獨立驗收的小任務。
3. 人工決定 API contract、SQL 安全、權限與錯誤行為。
4. 審查 AI 產出的 diff，避免碰到無關功能。
5. 以 tests、build、lint、真實 request、smoke test 與 Git 歷史驗證。

## Current Goal

尋找能累積 **Backend + Cloud + Production** 經驗的 Junior Backend / Software Engineer 機會，特別關注 API、B2B SaaS、企業系統、自動化與智慧製造相關產品。
