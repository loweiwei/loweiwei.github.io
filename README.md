# 羅暐媁個人 GitHub Pages 網站

這是一個不需要框架的多頁式靜態個人作品集網站，可以直接部署到 GitHub Pages。

## 目前內容

- 個人首頁與簡介
- `index.html`：首頁、About Me、網站入口卡片
- `journey.html`：112-1 到 114-2 學期經歷時間軸
- `projects.html`：PROVE-3D、ROS2 自主機器人、Hermes AI Agent、DeFi Lending Protocol、語音情緒辨識 MFCC × 1D CNN、數位電路拔河專題、Snow Field OpenGL Game
- `project-prove3d.html`：PROVE-3D 畢業專題研究架構、pipeline、研究圖與成果版位
- `project-ros.html`：ROS2 自主機器人詳細架構、pipeline、模組串接與任務成果
- `project-hermes.html`：Hermes AI Agent verification pipeline、四個 Skill、Open Test Killer 與成果證據
- `project-defi.html`：DeFi Lending Protocol 前端、合約、借貸、清算與 DAO governance pipeline
- `project-ser.html`：語音情緒辨識資料處理、1D CNN、FastAPI demo、ASR 與 LLM 串接
- `project-digital-tug.html`：數位電路拔河遊戲流程、FSM、計數器、LED 顯示與照片版位
- `project-opengl.html`：Snow Field OpenGL Game 圖學專題、render pipeline、場景模組與展示版位
- `resume.html`：PROVE-3D 研究亮點、履歷重點、證照、TOEIC 與聯絡資訊

## 編輯內容

主要修改對應頁面：

- 首頁內容：修改 `index.html`。
- 若要補照片，可把專案卡片中的 `.project-media` 區塊改成 `<img>`。
- 若要調整學期經歷，修改 `journey.html` 中 `112-1` 到 `114-2` 卡片文字。
- 若要調整作品集總覽卡片，修改 `projects.html`。
- 若要調整單一作品的完整介紹，修改對應的 `project-*.html`。
- 若要調整履歷、證照或聯絡資訊，修改 `resume.html`。
- 目前專題封面是 CSS 繪製的視覺圖，若要換真實圖片，可把 `.cover-visual` 改成 `<img src="images/你的圖片.png" alt="專題封面">`。
- 數位電路照片版位在 `project-digital-tug.html` 的 `.media-gallery`，之後可把 `.media-placeholder` 改成 `<img src="images/檔名.jpg" alt="照片說明">`。
- 若要補影片或 Demo，把 `影片待補`、`Demo 待補`、`展示待補`、`結果圖待補` 的 `<span class="pending-link">...</span>` 改成 `<a href="你的連結">...</a>`。
- 若論文、中文論文或書卷獎證明連結已準備好，把 `ICS 英文論文待補`、`中文論文待補`、`書卷獎證明待補` 的 `<span class="pending-link">...</span>` 改成真實 `<a>` 連結。

如果想改顏色、間距或版面，修改 `styles.css`。

## 部署到 GitHub Pages

1. 在 GitHub 建立 repository。
2. 如果想用 `https://你的帳號.github.io/`，repository 名稱要是 `你的帳號.github.io`。
3. 把這個資料夾的檔案推上 GitHub。
4. 到 repository 的 `Settings` > `Pages`。
5. Source 選 `Deploy from a branch`。
6. Branch 選 `main`，資料夾選 `/(root)`，儲存。
7. 等 1 到 3 分鐘後開啟 GitHub Pages 網址。

## 常用 Git 指令

```bash
git init
git add .
git commit -m "Create personal portfolio"
git branch -M main
git remote add origin https://github.com/你的帳號/你的帳號.github.io.git
git push -u origin main
```
