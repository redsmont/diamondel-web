# SDIAMOND (信東電子) - diamondel-web

## 專案概覽
- 公司官網 + 後台管理系統
- 前端：純 HTML/CSS/JS（單頁式）
- 後端 API：`https://diamondel-api.vercel.app`
- 正式網址：`www.diamondel.com`（已啟用 HTTPS）
- 預覽網址：`https://redsmont.github.io/diamondel-web/`
- Repo：`https://github.com/redsmont/diamondel-web`

## 檔案結構
- `index.html` — 主網站（含客戶前台 + 登入/註冊）
- `admin.html` — 後台管理
- `inquiries.html` — 詢價管理
- `inventory.html` — 庫存管理
- `logo.png` — 公司 Logo

## 公司資訊
- 地址：231039新北市新店區北宜路一段18-5號17樓
- Email：sale@diamondel.com
- 網站：www.diamondel.com

## 近期完成事項
- [2026-05-17] 更新完整公司地址（含郵遞區號+路名+樓層）
- [2026-05-17] 地址加上 Google Maps 連結（點擊可開啟地圖）
- [2026-05-17] 網站已啟用 HTTPS SSL 憑證
- [2026-05-17] 註冊/登入流程已測試通過

## 關聯專案
- CRM 系統：`~/Downloads/sdiamond-cti`（Python Flask + 多頁 HTML）
- 兩個專案共用同一個後端 API：`https://diamondel-api.vercel.app`
- 網站詢價 → CRM 接收處理；CRM 庫存 → 網站顯示

## 待處理
- CRM 網站顯示錯誤，需排查原因
