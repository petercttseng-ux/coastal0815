# 臺灣沿近海漁業資源動態儀表板

> **農業部水產試驗所** ・ Taiwan Fisheries Research Institute, Ministry of Agriculture

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-0078d7?style=flat-square&logo=github)](https://petercttseng-ux.github.io/coastal0815/)

---

## 📊 關於本儀表板

本儀表板整合農業部水產試驗所及農業部漁業署公開統計資料，提供臺灣沿近海漁業資源之動態監測與可視化分析，**每10分鐘自動更新一次**。

### 主要功能

| 模組 | 說明 |
|------|------|
| 🎯 核心KPI指標 | 沿近海總產量、漁業產值、漁船數量、從業人員 |
| 📈 歷年趨勢 | 2015–2024年沿岸＋近海漁業產量折線圖 |
| 🥧 漁業類別比例 | 沿岸、近海、遠洋、養殖各類型產量圓餅圖 |
| 🗺 作業區域地圖 | 臺灣漁業作業區域示意圖（沿岸/近海/EEZ） |
| 🐟 魚種排名 | 主要漁獲魚種產量排名表（含視覺化進度條） |
| 📊 縣市別產量 | 主要漁業縣市沿近海產量橫條圖 |
| 🌐 貿易概況 | 水產品進出口貿易量趨勢圖 |
| 📢 政策動態 | 最新漁業政策、資源管理及研究動態 |

---

## 📂 資料來源

- **農業部水產試驗所** https://www.tfrin.gov.tw/
- **農業部開放資料平台** https://data.moa.gov.tw/
- **政府資料開放平台** https://data.gov.tw/
- **農業部統計查詢系統** https://agrstat.moa.gov.tw/
- **2025漁業統計年報**（民國113年資料）

---

## 🛠 技術架構

- **前端**：純 HTML5 + Vanilla CSS + JavaScript（無框架依賴）
- **圖表**：[Chart.js 4.4.3](https://www.chartjs.org/)
- **字型**：Google Fonts（Noto Sans TC + Inter）
- **動畫**：Canvas API 海洋粒子背景
- **部署**：GitHub Pages（靜態網站）

---

## 🚀 本地執行

直接開啟 `index.html` 即可在瀏覽器中運行，無需伺服器。

---

## 📋 漁業術語說明

| 術語 | 定義 |
|------|------|
| 沿岸漁業 | 在我國領海（12海浬以內）從事之漁業 |
| 近海漁業 | 在我國經濟海域（12至200海浬）從事之漁業 |
| TAC | 總容許漁獲量（Total Allowable Catch） |
| EEZ | 專屬經濟海域（Exclusive Economic Zone） |

---

© 2025 農業部水產試驗所　｜　數據依據《2025漁業統計年報》
