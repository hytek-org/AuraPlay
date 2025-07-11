# AuraPlay  
**Offline AI-Powered Smart Music Video Player**  
*Next-generation intelligent media experience, powered entirely in-browser.*

---

## 📌 Overview

**AuraPlay** is an intelligent, offline-first music video player that responds to your mood, gestures, and vibe — no server, no cloud, no compromise.

Built using modern web technologies and in-browser machine learning, AuraPlay delivers a futuristic, immersive entertainment interface that runs 100% client-side. It combines emotion recognition and gesture control to adapt your audio-visual experience in real time — all while keeping your data local and secure.

---

## ✅ Core Features

### 🎧 Local Media Playback
- Upload and manage local music and video files.
- Create and manage playlists.
- HTML5-native playback (`<audio>`, `<video>`).
- Essential controls: play, pause, volume, seek, shuffle.

### 🖐 Gesture Control System
- Uses **TensorFlow.js** and **MediaPipe Hands** (offline).
- Default gesture mappings:
  - 🖐 Open palm → Play/Pause  
  - 👈👉 Swipe Left/Right → Previous/Next  
  - ✌️ Two fingers Up/Down → Volume  
  - ✊ Fist → Stop  
  - 👌 OK sign → Toggle visualizer

### 😊 Emotion Detection Engine
- Uses **face-api.js** (lightweight offline model).
- Maps detected emotion to music mood:
  - 😀 Happy → Energetic / Pop  
  - 😢 Sad → Chill / Slow  
  - 😠 Angry → Intense / Instrumental  
  - 😐 Neutral → LoFi / Background

### 🧠 Mood-Adaptive Playback
- Polls emotion every 5–10 seconds.
- Automatically adjusts playlists to match mood.
- **“Vibe Lock”** option disables automatic switching.

### 🎨 Visualizer Mode
- WebGL/Canvas-based reactive visuals.
- Optional beat detection via **Tone.js**.
- Mood-driven themes: color, speed, intensity.

### 🔒 Fully Offline Architecture
- No server or internet required.
- All AI models and media stored locally.
- Preferences and data saved via **IndexedDB** / **LocalStorage**.

### ⚙️ Customization Dashboard
- Remap gestures to custom actions.
- Edit emotion-to-playlist mappings.
- Switch themes (light, dark, or dynamic).
- Export/import local settings.

---

## 🧠 Tech Stack

| Category       | Technology |
|----------------|------------|
| **Frontend**   | HTML5, CSS3, JavaScript (ES6+),TailwindCSS |
| **AI / ML**    | TensorFlow.js, face-api.js, MediaPipe Hands |
| **Audio / Visual** | Web Audio API, WebGL, Canvas, Tone.js (optional) |
| **Storage**    | IndexedDB, LocalStorage |
| **Architecture** | 100% Offline / Client-Side Only |

---

## 🗂 Project Structure

```
AuraPlay/
├── index.html
├── style.css
├── app.js
├── models/
│   ├── face-api/
│   ├── handpose/
│   └── gesture-custom/
├── assets/
│   ├── music/
│   ├── videos/
│   └── thumbnails/
├── js/
│   ├── mediaManager.js        # Playback, playlists, local media
│   ├── gestureController.js   # Hand gesture recognition logic
│   ├── emotionEngine.js       # Real-time mood detection
│   ├── visualizer.js          # Audio-reactive visual rendering
│   └── settings.js            # UI preferences, mappings
```

---

## 🔍 Ideal Use Cases

- AI-powered personal music experience.
- Smart media interface prototypes.
- Accessible, touchless media control.
- Frontend ML portfolio projects.
- Emotion-aware entertainment systems.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/AuraPlay.git
cd AuraPlay
```

### 2. Open `index.html`
This project runs entirely in the browser. No installation or build steps required.

### 3. Upload Your Media
Use the UI to load your local music and video files.

### 4. Enable Webcam Access
Camera is used for gesture and facial emotion detection (locally only).


## 🤝 Contributing

I welcome contributions, feedback, and ideas.  
Feel free to fork the repo, open issues, or submit pull requests.

---

## 📄 License

**MIT License** — free to use, modify, and distribute.

---

## 👤 Maintainer

**[Your Name]**  
[GitHub](https://github.com/kuldeepsharma1) · [LinkedIn](https://linkedin.com/in/kuldeepsharma22) ·

---

