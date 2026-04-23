# 飢餓遊戲 — 都城控制系統
### The Hunger Games · Capitol Surveillance Control System

一個以《飢餓遊戲》為主題的互動式模擬網頁，完全以原生 HTML/CSS/JS 製作，無任何外部框架依賴。

---

## ✨ 功能特色

- **24 名完整貢品名冊** — 全部 24 名貢品（12個區各2名）
- **自訂貢品** — 遊戲開始前輸入名字加入競技場
- **即時事件引擎** — 隨機生成戰鬥、社交、環境、系統事件
- **可調速度** — 0.5× / 1× / 2× / 3× 四段速控制
- **手動觸發** — 「觸發」按鈕可立即產生事件
- **事件篩選** — 按標籤篩選（全部 / 戰鬥 / 環境 / 社交 / 系統）
- **觀眾支持度排行** — 動態更新的人氣排行
- **音效系統** — 死亡砲聲、廣播提示音、鍵盤打字音
- **全螢幕模式** — 按 `F` 鍵切換全螢幕
- **空白鍵觸發事件** — 按 `Space` 手動推進
- **全螢幕死亡閃紅** — 貢品死亡時整個畫面閃紅
- **遊戲結束統計** — 顯示天數、事件數、淘汰人數
- **手機版 RWD** — 底部分頁導覽，完整支援手機
- **無障礙 ARIA** — 完整 aria-label 支援

---

## 🚀 部署方式

### 部署到 Vercel（推薦）

1. 將此資料夾推送至 GitHub：
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/你的帳號/你的repo名稱.git
git push -u origin main
```

2. 前往 [vercel.com](https://vercel.com)，點擊 **New Project**
3. 匯入你的 GitHub repo
4. 不需要任何設定，直接點擊 **Deploy**
5. 部署完成！取得你的 `.vercel.app` 連結

### 本地預覽
```bash
# 方法一：用 Python
python3 -m http.server 8080

# 方法二：用 Node.js
npx serve .

# 方法三：直接用瀏覽器開啟 index.html
```

---

## 🎮 操作說明

| 操作 | 說明 |
|------|------|
| `F` 鍵 | 全螢幕模式 |
| `Space` 鍵 | 立即觸發事件 |
| 「自動」按鈕 | 自動播放模式 |
| 「暫停」按鈕 | 暫停自動播放 |
| `◀◀` / `▶▶` | 調整速度（0.5x ~ 3x）|
| 「觸發」按鈕 | 手動觸發一個事件 |
| 「語錄」按鈕 | 顯示飢餓遊戲語錄 |
| 篩選按鈕 | 按類型篩選事件記錄 |
| 手機底部 Tab | 切換貢品 / 事件 / 狀態面板 |

---

## 📁 檔案結構

```
/
├── index.html      # 主要網頁（單一檔案，包含所有 HTML/CSS/JS）
├── vercel.json     # Vercel 部署設定
└── README.md       # 說明文件
```

---

## 🛠 技術細節

- **純原生** HTML5 / CSS3 / JavaScript（無框架）
- **字型**：Google Fonts（Noto Serif TC、Cinzel、Share Tech Mono）
- **音效**：Web Audio API 程式生成（無外部音效檔案）
- **儲存**：無需後端，完全前端運作
- **瀏覽器支援**：Chrome / Firefox / Safari / Edge 現代版本

---

*願機率永遠站在你這邊。*  
*May the odds be ever in your favor.*
