# Mia Wang｜AI Project Manager Portfolio

這個 Repository 是 Mia Wang（王俞文）的正式個人 Portfolio Website，定位為 AI Project Manager・AI 導入與流程改善。

## 線上網站

- Netlify：https://wangsites.netlify.app/
- GitHub Pages：https://witch6996-commits.github.io/MySites/

GitHub `main` 分支更新後，Netlify 會自動重新部署最新版本。

## 網站內容

### 首頁（`index.html`）

Hero、工作方式、精選案例（Selected Projects）、How I Work、AI Project Thinking、Experience、Tools & Capability 與聯絡方式。

### Featured Case Study：我的數位腦

`/作品集/my-digital-brain/`

AI Personal Collection & Recall System 的完整產品案例：從收藏、AI 整理、搜尋、模糊召回到 Ask My Collection。內容包含問題定義、產品流程、我的角色、AI 與 deterministic logic 的責任邊界、產品取捨與驗證方式。

Demo 影片置於 `作品集/my-digital-brain/media/my-digital-brain-demo-v1.mp4`。

### 其他作品（`/作品集/`）

`/作品集/` 內保留其他課程與個人實作頁面：

- 個資假名化工具
- 商業進銷存與收支財務分析系統
- 智能財務現金流量分析儀
- 台灣旅遊景點互動地圖
- 每日一句學英語

其中部分頁面為課程與個人實作，示範資料皆為虛構。

## Repository 結構

```text
MySites/
├── index.html                     # Portfolio 首頁
├── 作品集/
│   ├── index.html                 # 其他作品入口
│   ├── my-digital-brain/          # Featured Case Study
│   │   ├── index.html
│   │   └── media/                 # Demo 影片
│   └── *.html                     # 其他課程與個人實作
├── PIC/                           # 圖片素材
├── Music/                         # 音訊素材
└── README.md
```

## 技術結構

純靜態網站，不使用 build system 或 framework：

- HTML5 / JavaScript
- Tailwind CSS（CDN）、Font Awesome、Google Fonts
- 其他作品視頁面使用 SheetJS、Apache ECharts、Chart.js、CryptoJS 等前端套件

## 部署

GitHub → Netlify 自動部署（靜態檔案，無 build 步驟）。
