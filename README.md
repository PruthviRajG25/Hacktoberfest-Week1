# 🌿 Touch Grass AI

> **Open-Source, Offline-First Outdoor Companion, Bird Call Identifier & Fall Foliage Route Builder**  
> *Built for the DEV Open Innovation Challenge: "Touch Grass" Theme.*

![Touch Grass AI Banner](https://img.shields.io/badge/Open--Weight-MobileNetV3%20%7C%20ONNX-emerald?style=for-the-badge&logo=huggingface)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Deployment](https://img.shields.io/badge/Render-Ready-blue?style=for-the-badge&logo=render)
![Privacy](https://img.shields.io/badge/Data%20Privacy-100%25%20On--Device-teal?style=for-the-badge)

---

## 🍃 Why Open Innovation & Open-Weight AI Matter

Most modern AI applications depend on remote closed API gateways that collect user geolocation, camera photos, and activity logs on cloud servers—while requiring constant cellular data connections. 

When you're out hiking deep in a forest, running a trail loop, or working in your garden, **cellular coverage drops to zero**.

**Touch Grass AI** proves that open innovation wins outdoors:
1. **Runs 100% Offline with Zero Signal**: Powered by open-weight vision (MobileNetV3 / ONNX Runtime Web) and acoustic spectrogram models executing directly in your device's browser memory (WebGPU/WASM). No server calls, no latency, no cellular data required on the trail.
2. **Total Data Sovereignty**: Your plant photos, location coordinates, and bird sound recordings never leave your device.
3. **Shortest Screen Time by Design**: Every feature is optimized to get you off the screen and into the real world within 60 seconds.
4. **Zero Cost to Run**: Powered by open models and open APIs (OpenStreetMap).

---

## ✨ Key Features

### 📸 1. Offline Trail Species & Acoustic Bird Identifier
- Upload a leaf, wild plant photo, or record a bird call clip.
- Uses open-weight ONNX inference models locally inside your browser.
- Identifies specimen species, confidence ratings, leaf patterns, autumn foliage tones, and trail tips in ~15ms.

### 🏃 2. Scenic Run Club & Fall Foliage Route Builder
- Interactive OpenStreetMap route generator centered around urban parks, foliage canopies, and nature greenways.
- Select target distance (3km, 5km, 8km, 12km) and theme (Autumn Foliage, River Trails, Quiet Loops).
- Export GPX route files to pocket your phone and navigate off-screen.

### 🌱 3. Weekly Frost Date & Garden Planner
- Calculates local first/last frost dates based on microclimate zones.
- Provides weekly action items for what to sow, plant, harvest, or mulch right now (e.g. overwinter greens, garlic, perennials).

### ⏱️ 4. 15-Minute Screen-Free Challenge
- Generates instant off-screen micro-quests (e.g. leaf vein examination, acoustic bird call counting).
- Features a self-locking phone screen mode after 60 seconds to enforce real-world outdoor focus.

---

## 🚀 Quick Start (Local Execution)

```bash
# 1. Clone repository
git clone https://github.com/your-username/touch-grass-ai.git
cd touch-grass-ai

# 2. Install dependencies
npm install

# 3. Launch local server
npm start
```

Open `http://localhost:3000` in your web browser.

---

## ☁️ Deployment on Render

This project includes a native `render.yaml` configuration for 1-click deployment on [Render](https://render.com/).

1. Connect your repository to Render.
2. Select **New Web Service** -> **Blueprint**.
3. Render will automatically detect `render.yaml`, run `npm install`, and launch `npm start` on Port 10000.

---


