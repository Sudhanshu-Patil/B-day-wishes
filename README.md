# Luminary ✦ Personalised Birthday Experience

Luminary is a high-end, interactive web application designed to transform digital birthday wishes into a cinematic journey. Unlike traditional greeting cards, Luminary allows users to "bake" their own photos, messages, and music into a single, self-contained HTML file that can be shared via WhatsApp, Email, or AirDrop.

## ✨ Features
- **Cinematic Scroll-Driven Animations:** Powered by GSAP & ScrollTrigger for a narrative-driven photo gallery.
- **Ambient 3D Environment:** A real-time starfield and nebula background built with Three.js.
- **Procedural Audio Engine:** A custom Web Audio API synthesizer that plays an adaptive "Happy Birthday" melody based on the selected theme (Love, Friend, or Family).
- **Interactive SVG Cake:** A virtual candle-blowing ceremony using CSS animations and JavaScript logic.
- **Zero-Server Architecture:** All data is processed locally. Images are converted to Base64 and injected into the exported file, ensuring 100% privacy and permanent availability.

## 🛠️ Tech Stack
- **Engine:** JavaScript (ES6+)
- **Visuals:** [Three.js](https://threejs.org/) (WebGL), [GSAP](https://greensock.com/gsap/) (Animations)
- **Audio:** Web Audio API (Oscillators, Gains, Convolvers)
- **Styling:** CSS3 (Flexbox, Grid, Glassmorphism)

## 🚀 How It Works
1. **Personalise:** Enter the recipient's name and choose a relationship theme.
2. **Curate:** Upload 4–12 photos (stored locally in memory as Base64).
3. **Generate:** The app "bakes" the data into a new standalone HTML file.
4. **Share:** Download the file and send it. The recipient receives the full experience without needing to host or upload anything to a server.

## 🔒 Privacy & Security
Luminary is a "Local-First" application. No data is ever sent to a server or stored in a database. The images and messages never leave the user's browser until they choose to send the final file to someone else.

---
*Created with passion for unforgettable moments.*
