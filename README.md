# BrainWave 🧠

<img width="1800" height="1360" alt="brainwave-1" src="https://github.com/user-attachments/assets/368d7a12-6e67-453a-a80c-2c14f054ae12" />

A fully responsive, fully-coded AI landing page kit built with **React**, **Vite**, and **Tailwind CSS** — based on the [Brainwave UI8 design kit](https://ui8.net/ui8/products/brainwave-ai-landing-page-kit?rel=jsm).

🔗 **Live Demo:** [brain-wave-site.netlify.app](https://brain-wave-site.netlify.app/)
🎨 **Design Source:** [Brainwave AI Landing Page Kit on UI8](https://ui8.net/ui8/products/brainwave-ai-landing-page-kit?rel=jsm)

![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?logo=tailwindcss&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-7-CA4245?logo=reactrouter&logoColor=white)

---

## Overview

BrainWave is a polished, modern landing page template designed for AI/SaaS products. It's a coded implementation of the original Brainwave Figma design kit, translated into a production-ready React application. The project provides a clean, customizable foundation for building marketing sites, product pages, and app landing pages with minimal setup.

The template includes premade sections for a full marketing site — hero, features, pricing, roadmap, and authentication pages — all built with reusable, composable components so sections can be mixed, matched, and rearranged to fit different brands.

## ✨ Features

- ⚡️ Fast development and optimized builds powered by Vite
- 🎨 Fully responsive design — looks great on desktop, tablet, and mobile
- 🧩 Modular, reusable component architecture
- 💅 Styled entirely with Tailwind CSS for rapid, consistent styling
- 🧭 Client-side routing between pages via React Router
- 🖱️ Parallax scroll effects for a more dynamic, layered feel
- 🔒 Scroll locking for modals and mobile navigation menus
- 🔤 Custom typography using the Sora and Source Code Pro fonts
- 🖼️ Custom illustrations and graphics matching the original design kit

## 📄 Pages Included

| Page | Description |
|---|---|
| Home | Main landing page with hero, features, and CTA sections |
| Features | Detailed breakdown of product features |
| How to Use | Step-by-step product walkthrough |
| Roadmap | Product roadmap / upcoming releases |
| Pricing | Pricing plans and tiers |
| Sign In | User login page |
| Sign Up | User registration page |

## 🛠️ Built With

**Languages**
- JavaScript (JSX) — component logic and markup
- CSS — utility-driven styling via Tailwind, plus custom rules
- HTML — base document markup

**Frameworks / Libraries**
- [React](https://react.dev/) 18 — UI library
- [React Router](https://reactrouter.com/) 7 — client-side routing
- [Tailwind CSS](https://tailwindcss.com/) 3 — utility-first CSS framework
- [react-just-parallax](https://www.npmjs.com/package/react-just-parallax) — parallax scroll effects
- [scroll-lock](https://www.npmjs.com/package/scroll-lock) — scroll locking for overlays/menus

**Build Tools & Tooling**
- [Vite](https://vitejs.dev/) 6 — build tool and dev server
- [PostCSS](https://postcss.org/) + [Autoprefixer](https://github.com/postcss/autoprefixer) — CSS processing and vendor prefixing
- [ESLint](https://eslint.org/) — code linting and formatting consistency

**Deployment**
- [Netlify](https://www.netlify.com/) — hosting and continuous deployment

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (comes with Node.js) or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/rkazumovi/BrainWave.git
   cd BrainWave
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The optimized production build is output to the `dist/` folder, ready to deploy to any static hosting provider.

### Preview the Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## 📁 Project Structure

```
BrainWave/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── assets/          # Images, icons, illustrations
│   └── ...
├── index.html           # Entry HTML file
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.js    # PostCSS configuration
├── vite.config.js       # Vite configuration
└── package.json
```

## 🎨 Design Credit

The visual design and Figma source files for this project are based on the [Brainwave AI Landing Page Kit](https://ui8.net/ui8/products/brainwave-ai-landing-page-kit?rel=jsm), available on UI8. This repository contains an original, hand-coded implementation of that design using React, Vite, and Tailwind CSS.

## 📦 Deployment

This project is deployed with Netlify and is live at:
👉 [brain-wave-site.netlify.app](https://brain-wave-site.netlify.app/)

To deploy your own version, connect this repository to Netlify, Vercel, or any static hosting provider that supports Vite builds.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/rkazumovi/BrainWave/issues) if you'd like to contribute.

## 📄 License

This project is licensed under the MIT License. The original Brainwave design assets are property of their respective creators on UI8 and are subject to UI8's licensing terms.

---

<p align="center">Made with ❤️ using React + Vite + Tailwind CSS</p>
