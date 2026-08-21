# ⏱️ Burpee Pacer

A sleek, high-contrast interval timer and cadence pacer designed for burpee workouts and high-intensity interval training (HIIT). Built as an installable Progressive Web App (PWA) that runs 100% offline.

🔗 **Live App:** [https://majora1987-debug.github.io/burpee-pacer/](https://majora1987-debug.github.io/burpee-pacer/)

---

## ⚡ Features

- **Cadence & Interval Pacing:** Set target reps, total workout duration, custom sets/rounds, and rep cadence.
- **Dynamic Timeline Preview:** Real-time visual breakdown of work-to-rest ratio and feasibility warnings before starting.
- **Audio Beeps & Countdown:** Built-in Web Audio synthesis with distinct audio cues for prep, rep ticks, work intervals, and rest periods.
- **Screen Wake Lock:** Keeps your mobile screen active and awake throughout the workout without dimming or locking.
- **100% Offline Support:** Powered by a lightweight Service Worker and Web App Manifest — works in Airplane Mode with zero internet connection.
- **Installable PWA:** Can be installed directly to your home screen on Android (Pixel, Samsung, etc.) and iOS to run full-screen like a native app.

---

## 📱 Mobile Installation

### Android (Google Pixel / Chrome)
1. Open [https://majora1987-debug.github.io/burpee-pacer/](https://majora1987-debug.github.io/burpee-pacer/) in Chrome.
2. Tap the **three dots menu (⋮)** in the top right.
3. Select **"Install app"** or **"Add to Home screen"**.
4. Launch from your home screen or app drawer.

### iOS (iPhone / Safari)
1. Open the URL in Safari.
2. Tap the **Share** button (box with an arrow pointing up).
3. Tap **"Add to Home Screen"**.

---

## 🛠️ Tech Stack

- **HTML5 & CSS3:** Responsive, dark-mode native interface with zero external framework overhead.
- **Vanilla JavaScript:** High-precision `requestAnimationFrame` timing engine.
- **Web Audio API:** Latency-free synthesized beeps without external audio assets.
- **Screen Wake Lock API:** Native browser screen management.
- **Service Worker & PWA Manifest:** Full offline caching and standalone display mode.

---

## 📄 License

MIT License — feel free to customize and train with it!
