# 短除法動態教室 📐 Short Division Interactive Classroom

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?style=for-the-badge&logo=github)](https://cconecone-cmyk.github.io/short-division/)
[![Language](https://img.shields.io/badge/Language-繁體中文-blue?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero-orange.svg?style=for-the-badge)](#)

> 國中／國小數學《短除法動態教室》互動幾何視覺化教學工具！  
> 將抽象的短除法運算，轉化為生動的**方格重組等分幾何動畫**與**長度比例尺倍數延伸**，讓學生一眼看懂「為什麼短除法可以求最大公因數與最小公倍數」。

🔗 **線上即時體驗網址 (Live Demo)**：[https://cconecone-cmyk.github.io/short-division/](https://cconecone-cmyk.github.io/short-division/)

---

## ✨ 核心特色 (Key Features)

1. **雙教學主題切換 (GCD & LCM)**
   - **最大公因數 (GCD)**：所有數皆能整除才除，動畫以方格重新排列框組，動態展示共同等分單位。
   - **最小公倍數 (LCM)**：至少兩數能整除即除，無法整除者直落；動畫以長度條依比例伸縮，最後展示各倍數齊平於共同終點。
2. **雙表徵支援：整數 ⇄ 標準分解式**
   - **整數題**：支援 2～3 個數（範圍 1～500），短除過程顯示純數與商。
   - **標準分解式題**：支援以質因數分解型態輸入與呈現（例如 `2^4*3`、`2^2*3^2`），短除法梯形表內同步動態呈現質數次方扣減與質數相乘。
3. **HTML5 Canvas 向量動態圖解**
   - **最大公因數**：每格代表 1，依除數動態將小方格合併重新分組框選，大數自動調整晶格縮放。
   - **最小公倍數**：淡色框保留原始量、亮色長條展示商的收縮；完結步驟展開至 LCM 總長度，刻畫各數幾倍延伸齊步到位。
4. **同題左右對照模式 (Side-by-Side Comparison)**
   - 點擊「📋 左右對照」，即時在同一個對話框中並列展示該題在「最大公因數」與「最小公倍數」的不同短除法梯形表。
   - 一眼看清「全部整除 vs 兩數整除落下」與「只乘左側 vs 乘左側加最後一列」的本質差異。
5. **雙版面模式（大屏 / 手機）**
   - 🖥 **大屏模式**：左右分欄（短除梯形表 ＋ 動態圖解），適合教室觸控電視、電子白板與投影機。
   - 📱 **手機模式**：垂直流動佈局，適合學生隨身手機與平板。
   - 支援全螢幕（⛶ 全螢幕）沉浸式教學。
6. **豐富預設題庫與隨機出題**
   - 內建 20+ 組涵蓋互質、落下、三數倍數、兩兩有公因數、含質因數 5、含 1 等經典診斷題型。
   - 支援 🎲 隨機出題快速展開隨堂測驗。

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
