# 無盡擊殺 | Endless Slayer — 音遊玩家部落格

Personal blog of **無盡擊殺 (Endless Slayer)**, a rhythm game player from Taiwan.  
Live at: [https://xd45houo.github.io/Blog/](https://xd45houo.github.io/Blog/)

---

## 頁面功能 Features

- 🎨 **全暗色設計** — 深黑背景、紅紫漸層主題、霓虹發光效果、動態網格背景
- 🖼️ **Hero 橫幅** — 自訂封面圖（無文字版），底部漸層融入頁面
- 👤 **個人資料卡** — 真實 Instagram 大頭貼、旋轉彩環邊框、個人簡介
- 🔗 **社群連結** — Instagram、Facebook、YouTube、Discord 按鈕
- 🎮 **音遊紀錄** — CHUNITHM、maimai DX、Phigros、Arcaea 的核心數據卡片
- 🏆 **近期成就** — 可點擊的成就列表，連結至對應 Instagram Reel
- 📸 **Instagram 精選故事** — 四個精選故事的快速連結
- 📱 **Instagram 個人檔案嵌入** — 嵌入 `@endless.slayer` 的完整個人頁面
- ℹ️ **關於我** — 個人資訊與興趣標籤雲
- 🕐 **即時時鐘** — 頁尾顯示台灣時間，每 0.1 秒更新一次

---

## 音遊數據 Game Stats

| 遊戲 | 數據 |
|------|------|
| **CHUNITHM** | Rating 16.37 / 段位 IV |
| **maimai DX** | Rating 13946 / 八段 |
| **Phigros** | Ranking Score 13.29 |
| **Arcaea** | Potential 10.04 |

---

## 近期成就 Recent Achievements

| 遊戲 | 曲名 | 成績 |
|------|------|------|
| CHUNITHM · Master Lv 14.0 | INTERNET YAMERO | 1,009,250 · SSS+ Full Combo |
| CHUNITHM · Expert Lv 13.0 | 初音ミクの激唱 (The Intense Voice of Hatsune Miku) | 1,009,705 · All Justice |
| maimai DX · Master | 花となれ | 100.5616% · SSS+ |

---

## 檔案結構 File Structure

```
blog/
├── index.html          # 主頁面（單一 HTML 檔，含所有 CSS 與 JS）
├── banner.png          # 封面橫幅（AI 生成，無文字版）
├── avatar_real.jpg     # Instagram 個人大頭貼（真實下載）
├── avatar.png          # 初版 AI 生成大頭貼（備用）
└── README.md           # 本說明文件
```

---

## 開發歷程 Development History

### 階段 1 — 初始建立
- 根據 Instagram (`@endless.slayer`) 與 Facebook (`@endlos.toeten`) 個人檔案建立部落格
- AI 生成大頭貼與封面圖，套用深色霓虹主題設計

### 階段 2 — 圖片換新
- 將大頭貼換為從 Instagram 下載的**真實頭像** (`avatar_real.jpg`)
- 重新生成封面圖，移除所有文字水印，改為純藝術風格橫幅

### 階段 3 — 音遊紀錄區塊
- 新增 Arcaea 卡片（Potential 10.04）
- 更新 Phigros 為 Ranking Score 13.29
- 更新 CHUNITHM Rating → 16.37、段位 IV
- 更新 maimai DX Rating → 13946、八段
- 標題改為「音遊紀錄」，每張卡片只保留核心數據（Rating / Potential / Ranking Score + 段位）

### 階段 4 — Instagram 精選故事連結
- 更新四個精選故事的正確 highlight URL

### 階段 5 — 即時時鐘 & IG 嵌入
- 頁尾新增即時時鐘（台灣時間，每 0.1 秒更新，顯示至十分之一秒）
- 新增 Instagram 個人檔案嵌入（`@endless.slayer`），放於音遊紀錄上方
- 移除個人資料卡的貼文／追蹤者數據區塊

### 階段 6 — 社群連結擴充
- 新增 YouTube (`@endless.slayer/videos`) 與 Discord (`XsN3EWMdHR`) 按鈕

### 階段 7 — 近期成就更新
- 更新三筆成就（INTERNET YAMERO、初音ミクの激唱、花となれ），並附上對應 Instagram Reel 連結

### 階段 8 — 上傳 GitHub
- 初始化 git repo，設定遠端 `https://github.com/XD45hOuO/Blog`
- Merge 遠端現有 commits，成功推送至 `main` 分支
- 啟用 **GitHub Pages**，部落格正式上線

---

## 社群連結 Social Links

| 平台 | 連結 |
|------|------|
| Instagram | [@endless.slayer](https://www.instagram.com/endless.slayer/) |
| Facebook | [@endlos.toeten](https://www.facebook.com/endlos.toeten) |
| YouTube | [@endless.slayer](https://www.youtube.com/@endless.slayer/videos) |
| Discord | [XsN3EWMdHR](https://discord.gg/XsN3EWMdHR) |

---

© 2026 無盡擊殺 · Endless Slayer · All Justice Achieved
