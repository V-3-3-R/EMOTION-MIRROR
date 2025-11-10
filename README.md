# 🪞 EmotionMirror 

> **AI-Powered Emotion Detection & Wellness Tracker — All in Your Browser**

---

## 🌟 Overview

**EmotionMirror ** is an advanced, client-side web application that uses **AI-powered facial recognition** to detect and analyze your emotions in real-time.  
Built with **modern web technologies**, it provides a holistic **mood tracking dashboard**, **journaling**, **wellness insights**, and **personalized recommendations** — all running entirely in your browser for **privacy and speed**.

> Turn your webcam into a mirror of your mind. Perfect for mental wellness, emotional awareness, or just exploring how your face reflects your mood.

---

## ✨ Features

### 🎭 Real-Time Emotion Detection
- Detects **7 core emotions** using `face-api.js`:
  - Happy 😊, Sad 😢, Angry 😠, Neutral 😐, Surprised 😲, Fearful 😨, Disgusted 🤢
- Live webcam feed with privacy toggle (blur mode)
- Confidence bars and emoji overlays

### 📊 Mood Analytics Dashboard
- Interactive charts for emotion distribution and trends  
- Weekly **heatmap** for mood patterns  
- **Streak tracking** and **dominant mood** highlights  

### 🧘 Journaling & Wellness Tools
- Quick journal entries linked to detected moods  
- Guided **breathing exercises** and relaxation prompts  
- Personalized **quotes**, **music**, and **self-care** tips  

### 💡 Wellness Scoring
- AI-calculated metrics for **emotional balance**, **consistency**, and **positivity**

### 🔐 Data & Privacy
- 100% client-side: **No servers, no tracking**
- Data saved in browser **LocalStorage**
- Export moods/journals as JSON backups

### 💻 Responsive & Offline-Ready
- Fully responsive design (desktop/tablet/mobile)
- Works **offline** with preloaded TensorFlow.js models

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML5, JavaScript (ES6+), Tailwind CSS |
| **AI / ML** | `face-api.js` (TensorFlow.js backend) |
| **Visualization** | Chart.js |
| **Models** | Pre-trained: expressions, landmarks (68-point), MTCNN, SSD MobileNetV1, Tiny Face Detector |
| **Storage** | LocalStorage (browser-based) |
| **Deployment** | GitHub Pages / Netlify / Vercel |

---

## 🚀 Quick Start

### 🧠 Option 2: Run Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/emotionmirror-pro.git
cd emotionmirror-pro

# Open the main file
open index.html  # or double-click index.html
```

💡 For HTTPS-based camera access, serve locally with:
```bash
npx serve .
# or
python -m http.server
```

✅ Offline Mode: Models are preloaded in /models/ so no internet needed after first load.

# Browser Compatibility:
Chrome 80+, Firefox 75+, Safari 14+ (HTTPS required for camera).

---

# ☁️ Option 3: Self-Host
Deploy to Vercel, Netlify, or any static hosting platform.
Make sure to set:
```bash
const MODEL_URL = './models/';
```
to enable offline *AI model loading*.

---

# 🧠 Extend the App:
- Add new emotions → Modify moodMap in JS and retrain models
- Integrate APIs → Add Spotify, weather-based mood correlation
- Convert to App → Use Capacitor.js for Android/iOS packaging
- Dev Mode → Use VS Code Live Server for live reload

---

# 🔒 Data & Privacy
- 🔐 Local-Only: All data stays in your browser
- 🧘 No tracking: No cookies, analytics, or remote storage
- 💾 Export Ready: Download your JSON mood log anytime
- ⚖️ Ethical AI: Open-source models with consent-based emotion detection

---

# 🤝 Contributing:
Contributions are welcome! 🎉
```bash
# Fork & branch
git checkout -b feature/amazing-feature

# Commit & push
git commit -m "Add amazing feature"
git push origin feature/amazing-feature
```

*Then open a Pull Request 💬*

*Guidelines:*
- Follow Conventional Commits.
- Add tests for new logic.
- Update README.md for new features.
- Use GitHub Issues for bugs and ideas.

---

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

Built with ❤️ for emotional well-being.
Track your vibes, boost your wellness — start mirroring today! 🌈🪞✨








