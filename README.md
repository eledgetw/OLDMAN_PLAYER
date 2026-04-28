# OLDMAN'S Player (老人的播放器)

OLDMAN'S Playeris a lightweight, high-performance, browser-based video tool specifically engineered for music and vocal learners. 

The project was born out of a real-world frustration: the struggle of learning complex fingerstyle guitar pieces. Traditional video platforms like YouTube make it incredibly difficult to focus on a specific 5-second riff, slow down the tempo without losing audio clarity, or visualize the rhythm of a thumb slap technique. This player solves those pain points by providing a non-linear timeline (NLE) experience directly in your browser.

---

## 🎸 Why use this?
When mastering an instrument, repetition is everything. OLDMAN'S Playerallows you to strip away the distractions and focus on the music:
Custom Segmenting:Unlike standard players, you can "cut" the video into specific segments (A/B sections) to practice one riff at a time.
Precision Looping:Drag to select a range and loop it infinitely until your muscle memory takes over.
Visual Rhythm:The player renders a high-resolution audio waveform, allowing you to "see" the beat and phrasing before you even play a note.
Variable Speed Control:Slow down the action from 0.1x to 4.0xwithout changing the pitch, perfect for catching every finger movement.

## 🚀 Key Features
NLE Timeline Architecture:Split, move, and manage video clips with a professional editing interface.
Instrument-Friendly Hotkeys:Control playback and editing entirely through your keyboard, keeping your hands free for your guitar.
Project Persistence:Export your practice sessions, including all custom regions and clips, as a `.json` file to resume later.
Bilingual UI:Full support for both Traditional Chineseand English.

## 🛠 Usage Recommendations
### For the Best Experience
Since this is a local HTML5 application, it works best with local files. We recommend using a YouTube downloader (such as `yt-dlp`) to save your practice videos to your computer first. This ensures zero buffering and maximum privacy.

### Video Guidelines
Because the player decodes audio data locally to generate waveforms, performance is tied to your browser's memory. To keep the experience smooth on modern hardware (like a MacBook Air M3/M4):
Recommended Length:Under 30 minutes.
Recommended File Size:Under 500MB.
Note: Extremely long videos or 4K files may lead to long initial loading times while the waveform is being processed.

## ⌨️ Hotkeys
| Key | Action |
| :--- | :--- |
| Space (空白鍵)| Play / Pause (播放/暫停) |
| A| Select Mode - Move or select clips (選取模式) |
| B| Split Mode - Cut clips at the current time (分割模式) |
| [ / ]| Select all clips to the Left / Right of the playhead |
| Del / Backspace| Delete selected segments (刪除片段) |
| Shift + Click| Range selection on the timeline (兩點框選) |
| 1, 2, 3, 4| Instant speed presets (1x, 2x, 3x, 4x) |
| 5, 8| Slow-motion presets (0.5x, 0.8x) |
| Ctrl/Cmd + Z| Undo last action (復原) |


## Support This Project
✨ Do you like this project? ✨
If this tool has saved you time ⏱️ or inspired your research 💡,
🧋 click the icon to buy me a pearl milk tea! 🧋

[![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![Buy me a Boba](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(Click the Boba icon to support the author)
