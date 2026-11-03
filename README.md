# 🩸 血色等式：惡靈除靈術 (Crimson Equation: Demon Exorcism Art)

<p align="center">
  <img src="image_421bdb.png" alt="血色等式主視覺" width="100%" style="border-radius: 10px; border: 2px solid #06b6d4;">
</p>

<p align="center">
  <strong>一款結合哥德奇幻氛圍、自適應數學運算與 AI 沉浸式互動的一頁式惡靈除靈網頁遊戲</strong>
</p>

<p align="center">
  <a href="#-專案緣由與動機">專案動機</a> •
  <a href="#-遊戲特色">遊戲特色</a> •
  <a href="#-遊戲機制與職業">遊戲機制</a> •
  <a href="#-開發歷程">開發歷程</a> •
  <a href="#-技術架構">技術架構</a> •
  <a href="#-快速開始">快速開始</a>
</p>

---

## 📖 專案簡介 (Overview)

**《血色等式：惡靈除靈術》** 是一款打破傳統嚴肅教學框架的哥德暗黑風數學解謎網頁遊戲。玩家將扮演踏入詛咒古堡的除靈師，面對被血跡與符文封印的八大房間，唯有迅速且精準地解開惡靈留下的高階數學詛咒（包含代數方程、高階三角函數與初階微積分），才能在理智值（SAN 值）歸零前滌清深淵、揭開慘案真相。

---

## 🎯 專案緣由與動機 (Motivation & Background)

* **翻轉數學學習的枯燥感**：將高階數學題目（如微分極限、三角恆等式）轉化為遊戲中的「除靈咒語」，讓演算過程充滿緊迫感與成就感。
* **探索生成式 AI 與網頁遊戲的結合**：利用 Gemini AI 技術即時繪製殘像圖像與生成動態惡靈對話，打造具備生命力的文字冒險體驗。
* **建構沉浸式暗黑美學**：以鮮明高對比的青色魔法光效與深邃哥德氛圍，帶來視覺與聽覺兼具的腦力衝擊。

---

## ✨ 遊戲特色 (Core Features)

- 🧠 **高階自適應數學題庫**：動態隨機生成代數方程、正餘弦倍角公式、極限 $\lim$ 與定積分 $\int_a^b$ 試煉。
- 🤖 **AI 惡靈即時對決模式**：支援「血色伯爵 AI」競速模式，AI 會動態倒數破譯詛咒，並根據戰況發出個性化嘲諷。
- 🛡️ **三大除靈職業天賦**：
  - **驅魔神父**：擁有【聖血護體】，顯著降低答錯時的精神反噬傷害。
  - **占星術士**：擁有【星相破譯】，開局獲得額外 50:50 淨化道具與特定題目積分加成。
  - **瘋狂數學教授**：擁有【代數解析】，大幅提升連擊倍率成長與淨化積分。
- 📜 **8 大哥德歷史試煉房間**：隨著解題進度蒐集殘留日記碎片，解開古堡慘案真相。
- 🏆 **成就勳章與排行榜系統**：內建 8 項成就勳章解鎖機制，並記錄高分除靈師榜單。
- 🎵 **雙重驚悚音效與網頁合成器**：整合哥德氛圍配樂與 Web Audio API 低頻不和諧音效合成備案，確保 100% 音訊相容性。

---

## 📜 開發歷程 (Development Journey)

```
[ Phase 1: 基礎啟蒙 ] ───> [ Phase 2: 高階試煉 ] ───> [ Phase 3: AI 殘像與對決 ] ───> [ Phase 4: 一頁式平台與成就 ]
 建立代數方程與       加入三角函數與         整合 Gemini AI 視覺     打造 8 大勳章、排行榜
 基礎除靈邏輯         初階微積分極限         與動態惡靈嘲諷         與一頁式官網平台
```

1. **Phase 1: 血色代數啟蒙**
   - 建立基本驅魔框架，導入一元一次與一元二次方程，奠定「數學即除靈符文」的世界觀。
2. **Phase 2: 高階試煉升級**
   - 加入微積分極限 $\lim$, 導數斜率與三角函數 ($\sin/\cos/\tan$) 題目陣列，提升挑戰性與演算深度。
3. **Phase 3: AI 殘像與對決機制**
   - 整合 Gemini API 繪製慘案場景幻象與血色伯爵 AI 即時對決嘲諷，實現生成式動態劇情。
4. **Phase 4: 全面優化與一頁式展示**
   - 擴充職業天賦系統、8 大成就勳章解鎖、排行榜與復活血契機制，並整合成現代化單頁官網介紹。

---

## 🛠️ 技術架構 (Tech Stack)

* **前端框架與樣式**：HTML5, CSS3, Tailwind CSS (CDN), FontAwesome Icons
* **動態互動與邏輯**：Vanilla JavaScript (ES6+), Web Audio API
* **AI 服務整合**：Google Gemini API (用於文字生成與動態圖像繪製)
* **字體支援**：Google Fonts (Cinzel / Noto Serif TC)

---

## 🚀 快速開始 (Quick Start)

本專案採用單一檔案（Single-file Application）設計，無須安裝複雜的包管理工具即可直接運行。

1. **複製專案庫 (Clone Repository)**：
   ```bash
   git clone https://github.com/your-username/crimson-equation.git
   cd crimson-equation
   ```

2. **開啟專案**：
   直接使用瀏覽器開啟 `landing_page.html` 即可瀏覽官網與體驗線上試玩 platform。
   ```bash
   # 例如在 macOS 上使用 open 指令
   open landing_page.html
   ```

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 授權開源。
