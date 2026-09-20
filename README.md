# 元利鑫國際有限公司網站 Demo

此倉庫僅存放 Next.js 靜態匯出的展示網站，不包含開發原始碼。

- 預計展示網址：https://sr0927.github.io/yuanlixin-demo/
- GitHub Pages 發布來源：main 分支的根目錄（/）。
- `.nojekyll` 保留 Next.js 所需的 `_next` 靜態資源。
- CMS 登入：`/yuanlixin-demo/admin/login/`。
- 展示帳號：admin / Admin123!、editor / Editor123!。
- CMS 資料僅儲存於各自瀏覽器，不同步至前台；詢價表單不會寄信。

網站更新由本機原始碼執行 `npm run build:pages` 後，重新發布 `out/` 內容。
