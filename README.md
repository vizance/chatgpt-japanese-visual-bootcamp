# chatgpt-japanese-visual-bootcamp

四週 ChatGPT 日系視覺挑戰營（專案代號 `P-20260824`）的網頁素材。

- 直播：2026 / 8/17、8/24、8/31、9/7（週一 20:00–21:00）
- 開賣：2026 / 7/6
- 早鳥名單登記蒐集：2026 / 6 月下旬啟動
- 線上網址（GitHub Pages）：<https://vizance.github.io/chatgpt-japanese-visual-bootcamp/>

## 目錄

| 路徑 | 內容 |
| :--- | :--- |
| `index.html` | 早鳥名單登記頁（深色 Hero + 淺色日系內容 + 深色 CTA 收尾，含進場動畫）。GitHub Pages 從 repo 根目錄部署，所以這就是首頁。 |
| `assets/hero-banner.png` | Hero Banner 主圖（1672×941），同時當 OG 分享圖 |
| `assets/instructor-chi.jpg` | 講師形象照（已縮成 900×1350），用在「關於講師」區 |
| `assets/kit-form.css` | Kit 表單的深色樣式（已內建在 `index.html` 裡；要讓 Kit 自家 host 的版本也一致，就把它貼進 Kit 後台的 Custom CSS） |

## 部署

GitHub Pages：Settings → Pages → Source = Deploy from a branch → `main` / `/ (root)`。
推到 `main` 後約 1–2 分鐘自動更新到 <https://vizance.github.io/chatgpt-japanese-visual-bootcamp/>。

Kit 表單已嵌入（form `9432006` / uid `240ee4992a`），深色樣式由 `index.html` 的 `<style>` 負責。
若日後重新從 Kit 複製 embed code，整段換掉 `index.html` 裡 `<!-- Kit（ConvertKit）表單嵌入區 -->` 那段即可（樣式會自動套用）。

## 待辦

- [x] Hero 放上 1.png + 加漸層 / 動畫（2026-05-12）
- [x] OG 分享圖 → 用 hero-banner.png（已改成絕對網址）
- [x] 接上 Kit 表單 embed code（form 9432006），深色樣式已套（2026-05-12）
- [x] 推上 GitHub + 開 GitHub Pages（2026-05-12）
- [ ] 決定售價（NT.6,800–7,800 區間，5/16 前）→ 開賣後若要在頁面標價再補
- [ ] 把 Kit 後台的按鈕文字也改成「先幫我卡位 →」（目前頁面上是新的，Kit 後台還是舊的）
- [ ] 6/20 對外發布早鳥登記頁連結（FB / Substack）
