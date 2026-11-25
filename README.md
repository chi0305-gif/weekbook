# 四維高中圖書館 · 每週一書介紹

每週精選好書的展示網站。只要把圖片放進 `images/` 資料夾，網頁就會自動偵測並顯示。

## 上架新的一週

1. 把圖片命名為 `第N週`，例如 `第1週.PNG`、`第2週.jpg`
   （支援 PNG / png / jpg / JPG / jpeg / webp）
2. 上傳到 `images/` 資料夾
3. 重新整理網頁，或按「↻ 重新偵測」

最大週次會自動標上 **NEW**。

## 修改設定

打開 `index.html`，在 `<script>` 開頭的「設定區」：

- `TOTAL_WEEKS`：本學期週數（預設 21）
- `IMAGE_BASE`：圖片資料夾路徑

## 發佈到 GitHub Pages

Repository → Settings → Pages → Source 選擇 `Deploy from a branch`，
Branch 選要發佈的分支、資料夾選 `/ (root)`，存檔後約一分鐘即可在
`https://<帳號>.github.io/weekbook/` 看到網站。
