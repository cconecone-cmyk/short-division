# 短除法動態教室 📐 Short Division Interactive Classroom

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?style=for-the-badge&logo=github)](https://cconecone-cmyk.github.io/short-division/)
[![Language](https://img.shields.io/badge/Language-繁體中文-blue?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero-orange.svg?style=for-the-badge)](#)

> 國中／國小數學《短除法動態教室》互動幾何視覺化教學工具！  
> 將抽象的短除法運算，轉化為生動的**方格重組等分幾何動畫**、**長度比例尺倍數延伸**與**課本 6 大生活應用情境模擬**，讓學生一眼看懂「為什麼短除法可以求最大公因數與最小公倍數」。

🔗 **線上即時體驗網址 (Live Demo)**：[https://cconecone-cmyk.github.io/short-division/](https://cconecone-cmyk.github.io/short-division/)

---

## ✨ 核心特色 (Key Features)

### 1. 🌟 全新「應用問題」分頁：課本 6 大經典情境動態圖解
短除法算式與生活應用問題雙軌對照呈現，支援自訂題目參數與一鍵切換情境：
- ✂️ **長方形切成最大正方形 (GCD)**：長方形紙板動態裁切網格，直觀呈現正方形邊長與總塊數。
- 🌲 **長方形周圍種樹問題 (GCD)**：池塘周圍等距種樹，展示四角必種與最大樹距、最少棵數。
- 🧊 **長方體切成小正方體 (GCD)**：以 3D 等角投影（Isometric）動態剖分木塊，高亮單位正方體與總個數。
- 🧱 **小長方體拼成大正方體 (LCM)**：以 3D 等角投影展示彩色積木在三維空間逐層堆疊拼成大正方體。
- 🏃 **三人不同速率繞操場跑 (LCM)**：真實橢圓田徑跑道，甲、乙、丙三位跑者依各自速率跑步，於 LCM 秒數在起點精確齊平相遇！
- 📅 **多人週期輪流值班排班 (LCM)**：多軌時間軸動態掃描，演示三位醫師各週期在第 LCM 天再次同一天值班。

### 2. 雙教學主題切換與嚴謹教學對照 (GCD & LCM Alignment)
- **最大公因數 (GCD)**：所有數皆能整除才除，動畫以方格重新排列框組，動態展示共同等分單位。
- **最小公倍數 (LCM)**：一律**優先提出三數皆能整除的公因數**，與最大公因數前段步驟完全一致！待三數無公因數後，才提出兩數公因數並將無法整除者直落；動畫以長度條依比例伸縮，最後展示各倍數齊平於共同終點。

### 3. 三大題目類型表徵支援
- **整數題**：支援 2～3 個數（範圍 1～1000），短除過程顯示純數與商。
- **標準分解式題**：支援質因數分解型態輸入與呈現（例如 `2^4*3`、`2^2*3^2`，數值最高支援至 1000），具備**獨立欄寬間距優化**，避免多個因數乘號混雜，梯形表內同步動態呈現質數次方扣減。
- **應用問題**：直接載入完整生活題幹，步驟逐步引導觀念分析、短除計算與後續應用解答。

### 4. 教室大螢幕投影專用：超大字體左右對照 (Classroom Projector Big View)
- 點擊「📋 左右對照」，即時在同一個對話框中並列展示該題在「最大公因數」與「最小公倍數」的梯形表。
- 預設採用 **32px～56px** 高清晰字體與加粗短除線條，後排同學一覽無遺；更內建「🔍 投影超大字體」一鍵切換至特大模式（最高 72px）。

### 5. 雙版面模式（大屏 / 手機）
- 🖥 **大屏模式**：左右分欄（短除梯形表 ＋ 動態圖解），適合教室觸控電視、電子白板與投影機。
- 📱 **手機模式**：垂直流動佈局，適合學生隨身手機與平板。
- 支援全螢幕（⛶ 全螢幕）沉浸式教學。

---

## ⌨️ 鍵盤快捷鍵指南 (Keyboard Shortcuts)

| 快捷鍵 (Key) | 功能說明 (Action) |
| :---: | :--- |
| `→` (方向鍵右) | **下一步 (Next Step)**：執行下一步短除或圖解演進 |
| `←` (方向鍵左) | **上一步 (Previous Step)**：回退上一個步驟 |
| `Space` (空白鍵) | **自動連續播放 / 暫停 (Auto Play / Pause)** |
| `Esc` | 關閉「左右對照」彈跳視窗 |

---

## 🚀 本地端運行 (Local Running)

本專案為零依賴的純原生 Web 應用（HTML5 + CSS3 + Canvas + Vanilla JavaScript），無須 Node.js 或打包建置：

```bash
# 複製專案
git clone https://github.com/cconecone-cmyk/short-division.git

# 進入資料夾
cd short-division

# 直接用任何瀏覽器開啟 index.html
start index.html # Windows
open index.html  # macOS
```

---

## 📄 授權條款 (License)

MIT License - 歡迎各級學校教師、學生與教育工作者自由分享與教學使用。
