# bp-tracker
🩺 Privacy-first blood pressure tracker PWA — log readings, view trends, and install on iOS &amp; Android. No account, no cloud, 100% local storage.
# 🩺 BP Tracker — Blood Pressure Mobile App

> A free, privacy-first Progressive Web App (PWA) for tracking your blood pressure, heart rate, and health trends — installable on iOS & Android, no account required.

![PWA](https://img.shields.io/badge/PWA-Installable-3b82f6?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-a855f7?style=flat-square)
![Storage](https://img.shields.io/badge/Storage-Local%20Device%20Only-f97316?style=flat-square)

---

## ✨ Features

- **📋 Log Readings** — Record systolic, diastolic, heart rate, date, time, and optional notes
- **🏷️ Auto Classification** — Readings categorised automatically (Normal → Crisis) per AHA guidelines
- **⚠️ Crisis Alert** — Instant warning modal if a hypertensive crisis reading is detected (>180/>120)
- **📜 Reading History** — Filter by Today / This Week / This Month with swipe-to-delete
- **📊 Trends & Charts** — SVG line chart, 30-day averages, and category distribution breakdown
- **📤 Export Data** — Download all readings as CSV or JSON at any time
- **🌐 Works Offline** — Full offline support via Service Worker after first load
- **📲 Installable** — Add to Home Screen on iOS (Safari) and Android (Chrome) for a native feel
- **🔒 100% Private** — All data stored locally on your device. Nothing sent to any server.

---

## 📱 BP Category Reference

| Category | Systolic | Diastolic | Indicator |
|---|---|---|---|
| Normal | < 120 | < 80 | 🟢 Green |
| Elevated | 120–129 | < 80 | 🟡 Yellow |
| High Stage 1 | 130–139 | 80–89 | 🟠 Orange |
| High Stage 2 | ≥ 140 | ≥ 90 | 🔴 Red |
| Hypertensive Crisis | > 180 | > 120 | 🚨 Deep Red |

*Based on American Heart Association (AHA) 2017 guidelines.*

---

## 🚀 Live App

👉 **[Open BP Tracker](https://yourusername.github.io/bp-tracker)**

Open in your mobile browser and tap **"Add to Home Screen"** to install.

---

## 📲 How to Install on Your Device

### iPhone / iPad
1. Open in **Safari** (not Chrome — required for PWA install on iOS)
2. Tap the **Share** icon (square with arrow)
3. Tap **"Add to Home Screen"** → **"Add"**

### Android
1. Open in **Chrome**
2. Tap the **three-dot menu (⋮)**
3. Tap **"Add to Home Screen"** or **"Install App"**

---

## 🗂️ Project Structure

```
bp-tracker/
├── index.html    # Entire app — HTML, CSS, and JS in one file
└── README.md     # This file
```

Zero build tooling. No Node.js. No dependencies to install.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | Vanilla HTML5 + Tailwind CSS (CDN) |
| Charts | Chart.js (CDN) |
| Icons | Lucide Icons (CDN) |
| Storage | IndexedDB (local device) |
| Offline | Service Worker |
| Hosting | GitHub Pages |

---

## 🔒 Privacy

Zero data collection. No analytics, no trackers, no accounts. All readings stay on your device forever.

---

## ⚠️ Medical Disclaimer

For personal tracking purposes only. Not a medical device. Consult a qualified healthcare professional for any medical concerns.

---

## 📄 License

MIT — free to use, fork, and modify.

---

*Made with ❤️ for better heart health.*
