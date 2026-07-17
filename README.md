# 👁️ ctOS Chat Control Interceptor & Profiler

An interactive, cyberpunk-styled desktop monitor emulator inspired by the **Watch Dogs (ctOS)** interface and the soundtrack of **Buckshot Roulette**. This mini-app was created in Python 3.10 as a creative response to the ongoing news about "Chat Control" mass surveillance legislation in the EU. 

> *"Big Brother is watching you — don't let him restrict your freedom."*

---

## ⚡ Features

* **5 Interactive Screens:** Switch seamlessly between tabs using keys `1`, `2`, `3`, `4`, `5`.
  1. **INTERCEPT:** View intercepted anti-government data locks (User 🔄 Anon).
  2. **LIVE SCAN:** Type any text in real-time. If you input flagged words (like *VPN, TG, privacy, freedom, EU*), the built-in AI scanner triggers a high-risk alarm state.
  3. **MANIFESTO:** A static cyberpunk protest screen dedicated to privacy.
  4. **PROFILER:** Press `R` to instantly scan the ctOS citizen database and generate random civilian profiles with risk assessments.
  5. **DATABASE:** A multi-page hacker database containing real articles and arguments against Chat Control (navigate via `Left/Right` arrow keys).
* **Retro CRT Shader:** Hardware-accelerated screen curvature distortion (barrel effect), neon glow, and raster scanlines built purely on NumPy and OpenCV without external game engines.
* **Audio Engine:** Programmatically synthesized custom low-volume keyboard clicks, AI sirens, and a dedicated `page_select.mp3` module for transition glitches.
* **Adaptive 2K Fullscreen:** Instantly queries your monitor info and scales smoothly into full-screen immersive mode.

---

## 📸 Preview

*Insert your TikTok video link, a high-quality screenshot, or a demonstration GIF here to grab attention!*

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com
cd ctos-chat-control
```

### 2. Install dependencies
Make sure you have Python 3.10+ installed. Then run:
```bash
pip install pygame opencv-python numpy
```

### 3. Audio files configuration
For the application to sound exactly as intended, place your audio files directly into the root folder next to `ctos2.py`:
* `bg_music.mp3` (Recommended: *Buckshot Roulette OST* by Mike Klubnika)
* `page_select.mp3` (Any glitch/static transition sound effect)

### 4. Run the app
```bash
python ctos2.py
```

---

## 🎮 Controls

* `1` - `5` : Switch between monitoring tabs.
* `R` : Scan next citizen (Only available on Screen 4: PROFILER).
* `Left` / `Right` Arrow Keys : Navigate through article pages (Only available on Screen 5: DATABASE).
* `Backspace` / `Return` : Edit text inside the live chat analyzer (Screen 2).
* `Esc` / `Alt + F4` : Safely exit the fullscreen app.

---

## ⚖️ Disclaimer & Context
This project is an artistic simulation and a political satire. It does not actually intercept or analyze real network data, nor does it communicate with any government entities. It serves as a visual commentary on the erosion of digital privacy rights.
