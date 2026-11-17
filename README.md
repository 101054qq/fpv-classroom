# 穿越機新手飛行教室

給完全新手的 FPV（穿越機）飛行練習網站，純 HTML + CSS，不需要任何建置工具。

- AI 規則：見 [AGENTS.md](./AGENTS.md)
- 新增課程：複製 `templates/lesson-template.html` 到 `lessons/`，再更新 `index.html`

## 本機預覽

直接用瀏覽器打開 `index.html` 即可。

## 部署到 GitHub Pages

1. 把整個資料夾上傳到 GitHub 新 repo（public）。
2. 到 repo 的 **Settings → Pages**。
3. Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 等 1–2 分鐘，網址會是 `https://<你的帳號>.github.io/<repo 名稱>/`。
