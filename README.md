# 🌌 Premium Interactive 2.5D Developer Portfolio & Admin Dashboard

Welcome to my next-generation developer portfolio! This project showcases a beautiful, responsive dark-mode portfolio built with **Vite (Vanilla JS)**, maximum-performance modular styles, an interactive **2.5D isometric game engine**, and a secure **cloud-synchronized Administrative Panel**.

---

## ✨ Features

### 🕹️ 2.5D Isometric Interactive World
* **Procedural Character Sprite**: Pulsing glowing energy node that drifts through an isometric mesh space.
* **Responsive Control Mappings**: Fully responsive seek-on-tap mechanics for phones and tablets, plus standard keyboard WASD/Arrow keys.
* **Neon Gravity Portals**: Orbiting portal nodes that gravitationally attract, compress, and warp visitors to navigate smoothly into `#about`, `#projects`, or `#contact` pages.

### 🛡️ Secure Admin Control Center
* **Authorized Gate**: A hidden glassmorphic console route `/#admin` where the developer can log in.
* **Dynamic Content Manager**: Full create, read, update, and delete (CRUD) forms to manage portfolio project cards in real-time.
* **Dual-Layer Database Sync**: Uses Firebase Firestore and Authentication when environment keys exist, and automatically falls back to a highly-resilient, offline-ready `localStorage` database if offline or credentials are missing.

---

## 🛠️ Technology Stack
* **Bundler & Server**: Vite, esbuild (ES2022 Compilation)
* **Frontend**: HTML5, Vanilla JavaScript (ES6+ Dynamic Modules)
* **Styling**: Vanilla CSS3 (Glassmorphism & HSL Color Gradients)
* **Database & Auth**: Cloud Firebase Firestore, Firebase Auth SDK
* **Automation**: GitHub Actions Continuous Deployment

---

## 🚀 Getting Started

### Local Development
1. Clone the repository and install dependencies:
   ```bash
   npm install
   ```
2. Run the local development server:
   ```bash
   npm run dev
   ```
3. Open `http://localhost:5173/` in your browser.
