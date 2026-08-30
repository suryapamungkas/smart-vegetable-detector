# 🥦 RootFact — AI-Powered Vegetable Vision & Fact Generator

[![Live Demo](https://img.shields.io/badge/Live_Demo-Netlify-00C7B7?style=flat&logo=netlify)](https://penerapan-ai-di-aplikasi-web.netlify.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-4.22-FF6F00?logo=tensorflow)](https://www.tensorflow.org/js)
[![Transformers.js](https://img.shields.io/badge/Transformers.js-ONNX-yellow?logo=huggingface)](https://huggingface.co/docs/transformers.js)
[![PWA Ready](https://img.shields.io/badge/PWA-Workbox-blue?logo=pwa)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)

**RootFact** is a client-side AI Progressive Web App (PWA) that performs real-time vegetable recognition via camera streaming and generates instant contextual health fun facts using local in-browser LLMs—completely private and offline-ready.

---

## ✨ Key Features

- 📷 **Real-Time Computer Vision:** Uses custom TensorFlow.js models running on WebGPU/WebGL to identify vegetables with real-time FPS counter and confidence scores.
- 💡 **On-Device Generative AI:** Uses Transformers.js (`Xenova/LaMini-Flan-T5-77M` quantized ONNX) to produce personalized health fun facts with customizable personas (Funny, History, Science) without hitting external paid APIs.
- ⚡ **Offline-First PWA:** Integrated with Workbox Service Worker for precaching app shells and caching AI models locally for instant offline usage.
- 🏛️ **Clean MVP Architecture:** Built with clear separation of concerns (Models, Views, Presenters) for maintainability and scalability.

---

## 🛠️ Tech Stack

- **Frontend Core:** HTML5, Modern CSS (Glassmorphism Dark Theme), Vanilla JavaScript (ES2022)
- **AI & Machine Learning:** TensorFlow.js, Hugging Face Transformers.js (ONNX Runtime Web)
- **Offline & Bundling:** Webpack 5, Workbox (`workbox-webpack-plugin`), Service Workers
- **Deployment:** Netlify

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation
1. Clone repository:
   ```bash
   git clone https://github.com/suryapamungkas/root-fact-app.git
   cd root-fact-app

2. Install dependencies:
   ```bash
   npm install

3. Run development server:
   ```bash
   npm run start-dev

4. Build for production:
   ```bash
   npm run build

👤 Author
Nur Hidayat Surya Pamungkas
GitHub: @suryapamungkas
