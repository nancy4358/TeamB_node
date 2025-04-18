TeamB 運動揪團網站

## 專案簡介
這是一個不同於一般社群媒體，提供專業運動揪團組織功能。 使用 React.js 開發前端介面，Node.js + Express 實作後端 API，並以 MySQL 作為資料儲存。使用者可以新增、查看與刪除留言，前後端分離設計，適合展示 CRUD 與 RESTful API 能力。

## 使用技術

### Frontend（前端）
- React.js
- Next.js
  
### Backend（後端）
- Node.js
- Express.js
- CORS

### Database（資料庫）
- MySQL
---------------------------------
## 建立環境變數 dev.nev

# Server Port
WEB_PORT=3001

# MySQL Database Configuration
DB_HOST=your-database-host

DB_USER=your-database-user

DB_PASS=your-database-password

DB_NAME=your-database-name

DB_PORT=3306

# JWT Secret Key
JWT_KEY=your-jwt-secret-key

# OpenAI API Key 
OPENAI_API_KEY=your-openai-api-key

# Google OAuth
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_SECRET_KEY=your-google-secret-key

## My Contribution（我的貢獻）

我在本專案中負責以下功能的開發與實作：

- 使用者登入 / 登出功能（JWT 驗證）
- 忘記密碼與重設密碼流程（含驗證碼機制）
- 修改會員資料（含圖片上傳、下拉選單、多選項）
- 第三方登入整合（Google OAuth）
- 會員中心介面與 API 開發
- 聯繫表單功能與後端處理
- 前後端資料串接與錯誤處理設計

---------------------------------
## ⚙️ 安裝與執行方式

### 1️⃣ 安裝前端（TeamB_next）

npm i

npm run dev
---------------------------------
##  前端網址
https://github.com/zx0938013408/TeamB_next

---------------------------------
## 資料庫檔案
### 放在 TeamB_node 專案內部
檔名: mfee59_teamb_database 0408.sql
