<div align="center">
  <img src="cws_assets/store_icon_128.png" alt="BrainTab Logo" width="128">

  # 🧠 BrainTab

  **Your Browser Needs a Second Brain.**

  [![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available-blue?logo=googlechrome)](https://chrome.google.com/webstore)
  [![Version](https://img.shields.io/badge/Version-1.0.1-brightgreen.svg)]()
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  <p align="center">
    <img src="cws_assets/marquee_tile_1400x560.jpg" alt="BrainTab Banner" width="100%">
  </p>

  <p align="center">
    <b>BrainTab</b> is an AI-powered Chrome extension that automatically remembers, summarizes, and connects everything you read into an intelligent, interactive knowledge graph.
  </p>
</div>

---

## 🚀 The Problem
Information overload is real. You leave 50 tabs open because you don't want to lose them, or you bookmark articles you never read. When you need that specific piece of information from three weeks ago, it's completely lost in your browser history.

## 💡 The Solution
**Frictionless Knowledge Management.** 
Install BrainTab and browse normally. Our AI silently reads, understands, and extracts the core concepts from your tabs, building a personal, highly searchable database of your mind.

---

## 🔥 Core Features

### 🤖 Meet Kira: Your Persistent AI Copilot
Stop switching tabs to use ChatGPT. Kira lives in your side panel, follows you across websites, and knows exactly what page you are reading. Ask her to explain complex topics, summarize long articles, or retrieve past memories instantly.

<p align="center">
  <img src="cws_assets/screenshot2.jpg" alt="Kira AI Chat" width="80%">
</p>

### 🌌 Visual Knowledge Graph
Experience your knowledge like never before. BrainTab connects related concepts and visualizes your research in a beautiful, interactive GraphQL interface. See how your thoughts connect in real-time.

<p align="center">
  <img src="cws_assets/screenshot3.jpg" alt="Knowledge Graph" width="80%">
</p>

### ⚡ Automatic Summarization & Tagging
Never manually tag a bookmark again. As you browse, BrainTab automatically generates concise summaries and extracts key entities (tools, concepts, people) from the page.

### 🛡️ 100% Private & Portable
Your data belongs to you. Export your entire Second Brain to JSON or PDF at any time. Need to browse privately? Simply toggle **Incognito Mode** to instantly pause memory capture.

<p align="center">
  <img src="cws_assets/screenshot5.jpg" alt="Settings & Privacy" width="80%">
</p>

---

## 🛠️ Installation (Developer Mode)

If you want to run BrainTab locally from source:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/braintab.git
   ```
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (toggle in the top right corner).
4. Click **Load unpacked** and select the cloned `braintab` extension directory.
5. Pin the extension to your toolbar and open the Chrome Side Panel!

---

## 💻 Tech Stack

- **Frontend UI:** Vanilla JS, HTML5, CSS3 (Glassmorphism & Neon Design)
- **Visualization:** 3D Force-Directed Graph (D3.js / ForceGraph)
- **Storage:** `chrome.storage.local` (Local-first architecture)
- **AI Engine:** DeepSeek AI API integration for summarization and chat
- **Background Processes:** Chrome Manifest V3 Service Workers

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---
<div align="center">
  <i>Built with ❤️ for deep thinkers and researchers.</i>
</div>
