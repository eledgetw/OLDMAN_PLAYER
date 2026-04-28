# OLDMAN'S Instrument Practice Player

OLDMAN'S Player is a lightweight, high-performance, browser-based video tool specifically engineered for music and vocal learners.

The project was born out of a real-world frustration: the struggle of mastering complex musical pieces, such as fingerstyle guitar arrangements. Traditional video platforms like YouTube make it incredibly difficult to focus on a specific 5-second riff, slow down the tempo without losing audio clarity, or visualize the rhythm of a percussive technique. This player solves those pain points by providing a non-linear timeline (NLE) experience directly in your browser.

---

## 🎸 Why use this?
When mastering an instrument, repetition and precision are everything. OLDMAN'S Player allows you to strip away the distractions and focus on the music:

Intelligent Segmenting: Double-click any clip to instantly name and "Define a Region," or "cut" the video into specific segments (A/B sections) to practice one riff at a time.
Precision Looping: Drag or use Shift + Clickto select a range and loop it infinitely until your muscle memory takes over.
Visual Rhythm: The player renders a high-resolution audio waveform (up to 15,000 samples), allowing you to "see" the beat and phrasing even when zoomed in.
Precision Merging: Seamlessly combine multiple clips into a single continuous segment to practice transitions between riffs.
Variable Speed Control: Slow down the action from 0.1x to 4.0xwithout changing the pitch, perfect for catching every finger movement.

## 🚀 Key Features
NLE Timeline Architecture: Split, move, and manage video clips with a professional editing interface.
Dynamic UI: Includes a resizable editor area and a Zoom-to-Fitfunction for a clear view of your entire practice session.
Instrument-Friendly Hotkeys: Control playback, mode switching, and editing entirely through your keyboard, keeping your hands free for your guitar.
Project Persistence: Export your practice sessions, including all custom regions, named labels, and clips, as a `.json` file to resume later.
Bilingual UI: Full support for both Traditional Chineseand English.

## 🛠 Usage Recommendations
### For the Best Experience
Since this is a local HTML5 application, it works best with local files. We recommend using a downloader to save your practice videos to your computer first. This ensures zero buffering and maximum privacy.

### Video Guidelines
Because the player decodes audio data locally to generate waveforms, performance is tied to your browser's memory. To keep the experience smooth on modern hardware (like a MacBook Air M4):
Recommended Length: Under 30 minutes.
Recommended File Size: Under 500MB.
Note: Extremely long videos or 4K files may lead to longer initial loading times while the 15,000-point waveform is being processed.

## ⌨️ Hotkeys

| Key | Action |
| :--- | :--- |
| **Space (空白鍵)** | Play / Pause (播放/暫停) |
| **A** | Select Mode - Move or select clips (選取模式) |
| **B** | Split Mode - Cut clips at the current time (分割模式) |
| **`** | **Select selected clip & Define Region (框選片段並定義區間)** |
| **Double-Click Clip** | Instantly name and define a region (快速命名區間) |
| **Enter** | Zoom to Fit (一鍵填滿/適應螢幕) |
| **[ / ]** | Select all clips to the Left / Right of the playhead |
| **Del / Backspace** | Delete selected segments (刪除片段) |
| **Shift + Click** | Range selection on the timeline (兩點框選) |
| **1, 2, 3, 4** | Instant speed presets (1x, 2x, 3x, 4x) |
| **5, 8** | Slow-motion presets (0.5x, 0.8x) |
| **Ctrl/Cmd + Z** | Undo last action (復原) |
| **Ctrl/Cmd + Y** | Redo last action (重做) |
---

# 老人的樂器練習播放器

「老人的播放器」是一款專為音樂及歌唱學習者量身打造的輕量化、高效能網頁版影片工具。

本專案源於一個真實的困擾：在練習複雜的樂曲（如指彈吉他）時，傳統影片平台的限制。無論是想反覆練習一段 5 秒鐘的過門、在不影響音質的情況下放慢速度，或是視覺化觀察節奏，YouTube 等平台都難以滿足需求。這款播放器透過在瀏覽器中直接提供非線性剪輯 (NLE) 的時間軸體驗，徹底解決了這些痛點。

---

## 🎸 為什麼選擇這個工具？
練習樂器時，精準的重複是進步的關鍵。老人的播放器讓您可以排除干擾，專注於音樂本身：

智慧區段標記：直接雙擊任何影片片段即可彈出命名視窗並「定義區間」，或是將影片「切割」成特定的 A/B 段落，逐一攻克難關。
精準循環播放：透過拖曳或 Shift + 點擊快速框選範圍，並無限循環播放，直到您的肌肉記憶徹底掌握。
視覺化節奏感：播放器會渲染高解析度的音訊波形（最高達 15,000 個採樣點），即使在極度放大下，也能讓您在彈奏前先「看見」節拍與樂句。
精確片段合併：可將多個選取的碎片段無縫合併為一個完整的區塊，方便練習不同樂句間的銜接。
變速不變調：支援 0.1x 至 4.0x的速度調整，且不影響音高，讓您能看清每一個細微的手指動作。

## 🚀 核心功能
NLE 時間軸架構：具備專業剪輯軟體邏輯的介面，可自由切割、移動並管理影片片段。
動態調整 UI：包含可調整高度的編輯區，以及「一鍵填滿」功能，確保您能清楚掌握整個練習進度。
樂手友善快捷鍵：完全透過鍵盤控制播放與模式切換，讓您的雙手能專注於琴弦上。
專案存檔功能：可將您的練習進度（包含所有定義的區域名稱與剪輯狀態）匯出為 `.json` 檔，方便隨時回到練習狀態。
雙語介面：完整支援繁體中文與英文。

## 🛠 使用建議
### 最佳體驗
本程式為本地端 HTML5 應用程式，使用本地檔案效果最佳。建議先使用影片下載工具將練習素材儲存在電腦中，這能確保零緩衝並最大化隱私。

### 影片規格建議
由於播放器需在本地解碼音訊以產生波形，效能表現取決於瀏覽器的記憶體。為確保在現代硬體（如 MacBook Air M4）上運行流暢：
建議長度：30 分鐘以內。
建議大小：500MB 以內。
注意：過長的影片或 4K 檔案在處理 15,000 點高解析波形時，初始載入時間可能會較長。

## ⌨️ 快捷鍵

| 按鍵 | 功能 |
| :--- | :--- |
| **Space (空白鍵)** | 播放 / 暫停 |
| **A** | 選取模式 - 移動或選取片段 |
| **B** | 分割模式 - 在當前時間切割片段 |
| **` (倒引號)** | **框選選取的片段並定義區間 (快速命名)** |
| **雙擊片段** | 自動啟動「定義區間」並輸入名稱 |
| **Enter** | 一鍵填滿 (適應螢幕) |
| **[ / ]** | 全選播放頭以左 / 以右的所有片段 |
| **Del / Backspace** | 刪除選取的片段 |
| **Shift + 點擊** | 在時間軸上進行兩點範圍框選 |
| **1, 2, 3, 4** | 常用倍速切換 (1x, 2x, 3x, 4x) |
| **5, 8** | 慢動作預設 (0.5x, 0.8x) |
| **Ctrl/Cmd + Z** | 復原 (Undo) |
| **Ctrl/Cmd + Y** | 重做 (Redo) |

---

## Support This Project
✨ 喜歡這個專案嗎？ ✨
如果這個工具節省了您的時間 ⏱️ 或對您的練習有所啟發 💡，
🧋 歡迎點擊下方圖示請我喝一杯珍珠奶茶！ 🧋

[![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(點擊珍奶圖示支持作者)
