# School Static Web Project / 學校靜態網頁作品

This project was created during university as a static web design and build exercise.  
此專案為大學時期的靜態網頁設計練習，使用自動化工具進行前端建構。

## Features / 功能特色

- **HTML**: Main layout with `index.html` / 主頁面架構
- **SCSS & CSS**: Modular styling compiled with Gulp / 使用 Gulp 編譯 SCSS 樣式
- **JavaScript**: Basic dynamic behavior (`js/`) / 基本互動功能
- **Image Assets**: Stored under `img/` / 圖片資源
- **Vendor Libraries**: Included under `vendor/` / 外部函式庫
- **Automation**: `gulpfile.js` manages build tasks / 使用 gulpfile 自動建構
- **Node.js**: Managed with `package.json` / 使用 npm 管理套件
- **CI/CD**: `.travis.yml` supports Travis CI / 支援 Travis CI 持續整合

## Folder Structure / 資料夾結構
```
FreeWebpage_work/
├── index.html
├── css/
├── scss/
├── js/
├── img/
├── vendor/
├── gulpfile.js
├── package.json
└── .travis.yml
```
## Setup Instructions / 專案啟動

1. Run `npm install` to install dependencies  
   執行 `npm install` 安裝相依套件  
2. Run `gulp` to start the development workflow  
   執行 `gulp` 啟動自動化流程

## License / 授權

MIT
