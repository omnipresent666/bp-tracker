# 🩺 BP Tracker — Blood Pressure Mobile App

> A free, privacy-first Progressive Web App (PWA) for tracking your blood pressure, heart rate, and health trends — installable on iOS & Android, no account required.

![BP Tracker](https://img.shields.io/badge/PWA-Installable-3b82f6?style=flat-square&logo=pwa)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-a855f7?style=flat-square)
![Storage](https://img.shields.io/badge/Storage-Local%20Device%20Only-f97316?style=flat-square)

---

## ✨ Features

- **📋 Log Readings** — Record systolic, diastolic, heart rate, date, time, and optional notes
- **🏷️ Auto Classification** — Readings are automatically categorised (Normal → Crisis) per AHA guidelines
- **⚠️ Crisis Alert** — Instant warning modal if a hypertensive crisis reading is detected (>180/>120)
- **📜 Reading History** — Filter by Today / This Week / This Month with swipe-to-delete
- **📊 Trends & Charts** — SVG line chart, 30-day averages, and category distribution breakdown
- **📤 Export Data** — Download all readings as CSV or JSON at any time
- **🌐 Works Offline** — Full offline support via Service Worker after first load
- **📲 Installable** — Add to Home Screen on iOS (Safari) and Android (Chrome) for a native app feel
- **🔒 100% Private** — All data is stored locally on your device. Nothing is sent to any server.

---

## 📱 BP Category Reference

| Category | Systolic | Diastolic | Indicator |
|---|---|---|---|
| Normal | < 120 | < 80 | 🟢 Green |
| Elevated | 120 – 129 | < 80 | 🟡 Yellow |
| High Stage 1 | 130 – 139 | 80 – 89 | 🟠 Orange |
| High Stage 2 | ≥ 140 | ≥ 90 | 🔴 Red |
| Hypertensive Crisis | > 180 | > 120 | 🚨 Deep Red |

*Based on American Heart Association (AHA) 2017 guidelines.*

---

## 🚀 Getting Started

### Option 1 — Use the Live App
👉 **[Open BP Tracker](https://yourusername.github.io/bp-tracker)**

No download needed. Open in your mobile browser and tap **"Add to Home Screen"** to install.

### Option 2 — Run Locally
```bash
git clone https://github.com/yourusername/bp-tracker.git
cd bp-tracker
open index.html   # or just double-click the file
```

No build step, no dependencies, no Node.js required. It's a single HTML file.

---

## 📲 How to Install on Your Device

### iPhone / iPad
1. Open the app in **Safari** (required — Chrome on iOS won't support PWA install)
2. Tap the **Share** icon (square with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **"Add"** — done!

### Android
1. Open the app in **Chrome**
2. Tap the **three-dot menu (⋮)**
3. Tap **"Add to Home Screen"** or **"Install App"**
4. Or watch for Chrome's automatic install prompt

---

## 🗂️ Project Structure

```
bp-tracker/
├── index.html       # The entire app — HTML, CSS, and JS in one file
└── README.md        # This file
```

The app is intentionally a single self-contained HTML file with zero build tooling, making it trivially easy to host, fork, and modify.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI Framework | Vanilla HTML5 + Tailwind CSS (CDN) |
| Charts | Chart.js (CDN) |
| Icons | Lucide Icons (CDN) |
| Storage | AppSDK + IndexedDB fallback |
| Offline | Service Worker (blob-registered) |
| Install | Web App Manifest (blob-registered) |
| Hosting | GitHub Pages |

---

## 🔒 Privacy

BP Tracker collects **zero data**. There are no analytics, no trackers, no third-party data sharing, and no user accounts. All readings are stored in your browser's local storage (IndexedDB) and never leave your device.

---

## ⚠️ Medical Disclaimer

BP Tracker is for **informational and personal tracking purposes only**. It is not a medical device and does not constitute medical advice. Always consult a qualified healthcare professional for diagnosis and treatment of hypertension or any other medical condition.

---

## 📄 License

MIT License — free to use, fork, and modify. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Pull requests are welcome! If you have a feature suggestion or found a bug, please open an issue.

---

*Made with ❤️ for better heart health.*
