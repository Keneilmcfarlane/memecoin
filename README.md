
# MemeCoin 💸

A modern web application starter built with Webpack, Sass, Tailwind CSS, and PostCSS — fully customizable and production-ready for creative front-end projects.

---

## 🚀 Features

- ⚡ Fast Webpack 5 bundling
- 🎨 Tailwind CSS & Sass support
- 🧩 HTML partials with simple include plugin
- 💅 Auto-prefixing and PostCSS setup
- 📦 Asset bundling (images, fonts, etc.)
- 🔥 Live reloading via `webpack-dev-server`

---

## 📁 Project Structure

```
📦 MemeCoin/
 ┣ 📂 src/
 ┃ ┣ 📂 assets/
 ┃ ┣ 📂 styles/
 ┃ ┣ 📂 partials/
 ┃ ┗ index.html
 ┣ 📂 dist/
 ┣ webpack.config.js
 ┣ postcss.config.js
 ┣ tailwind.config.js
 ┗ package.json
```

---

## 🛠️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/memecoin.git
cd memecoin
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start Development Server
```bash
npm run dev
```
Your app will be live at `http://localhost:8080`

### 4. Build for Production
```bash
npm run build
```
The final output will be in the `dist` directory (used for Vercel or any static deployment).

---

## ⚙️ Build Tools

- **Webpack** – for bundling and dev server
- **Tailwind CSS** – for utility-first styling
- **Sass** – for writing clean, nested styles
- **PostCSS** – for autoprefixing and future CSS features
- **HTML Include Plugin** – for reusable HTML partials
- **Prettier** – for consistent code formatting

---

## 📦 Deployment (Vercel)

Make sure to configure:
- **Build Command**: `npm run build`
- **Output Directory**: `dist`

---




Built with 💖 and Webpack

---

## 📜 License

MIT License
