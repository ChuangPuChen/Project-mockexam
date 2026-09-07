# AWS 模擬考題庫

多張 AWS 證照的模擬考題庫，純前端（單一 HTML 檔案 / 證照），無需後端。

## 目前收錄

| 資料夾 | 證照代碼 | 名稱 |
|---|---|---|
| [`/saa`](./saa) | SAA-C03 | Solutions Architect – Associate |
| [`/sap`](./sap) | SAP-C02 | Solutions Architect – Professional |
| [`/aif`](./aif) | AIF-C01 | AI Practitioner |

## 線上使用

透過 GitHub Pages 部署，入口頁面：`https://<你的 GitHub 帳號>.github.io/Project-mockexam/`

各證照題庫可直接以子路徑存取，例如 `.../Project-mockexam/saa/`。

## 本機使用

直接用瀏覽器開啟對應資料夾底下的 `index.html` 即可。

## 新增一張證照題庫

1. 在根目錄建立新的資料夾（以證照代碼命名，例如 `clf`）。
2. 把題庫的 HTML 檔案放進去，命名為 `index.html`。
3. 在根目錄 `index.html` 的卡片清單中新增一個連結。

## 自訂網域

申請好網域後，可在 repo 的 **Settings → Pages → Custom domain** 填入網域，GitHub 會自動建立 CNAME 檔案；接著到你的網域註冊商設定 DNS（CNAME 指向 `<你的帳號>.github.io`，或 A 記錄指向 GitHub Pages IP）。
