# 🌐 MNL-website  

## www.mnlinnovation.com

[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro-ff5d01?logo=astro&logoColor=white)](https://astro.build)  
[![TailwindCSS](https://img.shields.io/badge/Styled%20with-TailwindCSS-06b6d4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)  
[![Deploys by Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)](https://vercel.com)  

A modern, high-performance website built with **Astro** & **TailwindCSS** for **MNL Innovation**.

---

## 🔍 Overview  
This repository contains the source code for the official website of **MNL Innovation**.  
It’s built using the static-site generator **Astro**, styled with **Tailwind CSS**, and optimized for speed, responsiveness, and a clean visual experience.  

**Key goals:**
- ⚡ Lightning-fast performance with minimal JavaScript  
- 🎨 Utility-first styling using Tailwind CSS  
- 📱 Fully responsive design  
- 🧩 Easy content management via Astro’s component model  
- 🚀 Ready for modern deployment platforms like **Vercel** and **Netlify**

---

## 🧰 Technologies & Setup  

**Core stack:**
- [Astro](https://astro.build) — Static-site framework for fast, content-focused sites.  
- [Tailwind CSS](https://tailwindcss.com) — Utility-based styling for rapid development.  
- [Vite](https://vitejs.dev) — Modern frontend tooling for blazing-fast builds.  
- [TypeScript](https://www.typescriptlang.org/) — Type-safe development.

**Installation & usage:**
```bash
# Install dependencies
npm install

# Run the local development server
npm run dev

# Build the project for production
npm run build

# Preview the production build locally
npm run preview
```
*(You can also use `yarn` or `pnpm`.)*

---

## 📂 Project Structure  
```
/
├── public/               # Static assets (images, icons, etc.)
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Astro pages (each file = route)
│   ├── styles/           # Global styles, Tailwind imports
│   └── layouts/          # Common layouts and wrappers
├── astro.config.mjs      # Astro configuration
├── tailwind.config.cjs   # Tailwind configuration
├── vite.config.ts        # Vite setup
└── tsconfig.json         # TypeScript configuration
```

---

## ✅ Features  
- 🚀 Pre-rendered static pages (improved SEO + performance)  
- 🧱 Modular components and layouts  
- 🌙 Dark mode friendly design  
- 💨 Tailwind utility classes for consistent styling  
- 🌍 Fully responsive and mobile-optimized  
- 🧩 Clean separation between content and presentation  

---

## 🚀 Deployment  
To deploy to **Vercel** (recommended):

1. Push your repository to GitHub.  
2. Go to [Vercel](https://vercel.com/new), import your repo, and follow the setup steps.  
3. Vercel will detect **Astro** automatically and configure the build:  
   ```bash
   Build Command: npm run build
   Output Directory: dist
   ```  
4. Your site will be live after the first build.  
5. Optionally, enable **automatic deployments** from your `main` branch.

---

## 🛠 Contributing  
We welcome contributions! Whether you’re fixing a typo, improving performance, or designing a new component, your help makes this project better.

**How to contribute:**
1. Fork the repository  
2. Create a new branch (`feature/new-component` or `fix/typo`)  
3. Commit your changes with clear messages  
4. Open a Pull Request to `main`  

Please follow existing coding and styling conventions (Tailwind + Astro).

---

## 🧑‍💻 Maintainers  
**[MNL Innovation](https://github.com/Mnl-Innovation)**  
Building smart, beautiful, and efficient digital experiences.

---

## 📄 License  
This project is licensed under the **MIT License**.  

You are free to:
- ✅ Use the code in personal or commercial projects  
- 🔧 Modify and distribute it under the same terms  
- 💡 Attribute credit to the original authors when possible  

See the [LICENSE](./LICENSE) file for the full legal text.

---

Made with ❤️ and a passion for clean code by **MNL Innovation**.
