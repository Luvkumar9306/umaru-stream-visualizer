# Umaru Streaming Keyboard Visualizer Overlay

> A lightweight, chroma-keyed streaming overlay for OBS, Twitch, and YouTube featuring a pure CSS-art Umaru-chan typing character that reacts to live keystrokes.

---

## 🌟 Features

* **Chroma-Key Background:** Solid `#00ff00` green background for 1-click chroma keying in OBS Studio / Streamlabs.
* **Pure CSS Art Character:** Vector-rendered Himouto! Umaru-chan wearing her iconic orange hoodie.
* **Real-time Input Feedback:** Animated responsive paws that alternate and press down in sync with user keypresses.
* **Zero Dependencies:** Pure HTML5, CSS3 keyframe animations, and lightweight JavaScript.

----

## 🎥 OBS Studio Setup

1. Open **OBS Studio**.
2. Add a new **Browser Source**.
3. Check **Local file** and select `index.html` (or enter `http://localhost:<port>`).
4. Set dimensions to `800 x 600`.
5. Right-click the Browser source → **Filters** → Add **Chroma Key** (`#00ff00`) to make the background transparent.


----

## 📸 Visual Preview

<div align="center">
  <img src="assets/umaru-character.png" alt="Umaru Keyboard Typing Character" width="600" />
  <p><em>Chroma-keyed green screen overlay with reactive typing animations</em></p>
</div>
