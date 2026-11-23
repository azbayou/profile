# 📊 Bayu Aziz — Personal Portfolio Website

Welcome to my personal portfolio repository! This website showcases my professional background as a **Data Engineer & Applied AI Engineer**, bridging 8+ years of logistics operations expertise with modern data architectures, automated pipelines, interactive dashboards, and agentic AI solutions.

🔗 **Live Website:** [https://azbayou.github.io/profile](https://azbayou.github.io/profile)

---

## 🌟 Key Features
* **Dark / Light Mode (with Anti-FOUC Persistence):** Instant pre-paint theme initialization using `localStorage` and system `prefers-color-scheme` detection to prevent Flash of Unstyled Content (FOUC), paired with smooth transitions and desktop/mobile toggles.
* **Google Sheets CMS with Smart Cache Diffing & Non-Blocking Sync:** Dynamically hydrates profile details, skills, projects, experience, education, and quick links from Google Sheets. Uses `localStorage` for instant initial rendering, normalized payload diffing to avoid redundant DOM re-renders, skeleton shimmer placeholders, and a non-blocking floating sync indicator.
* **Interactive Featured Projects:** Filter projects by domain (`All`, `AI & ML`, `Data Engineering`, `Analytics & Ops`) with live category counts, expand long descriptions and tool-pill lists inside compact cards, and inspect project visuals in a full-resolution image lightbox modal with keyboard (`Escape`) support.
* **Floating AI Assistant (Miyo):** Interactive virtual assistant widget backed by a Vercel API (powered by Gemini & Groq), featuring quick-topic chips, `sessionStorage` conversation persistence across reloads, and a one-click chat reset button.
* **Snake Arcade Mini-Game (`games/ular.html`):** Standalone retro arcade Snake game ("Snake Klasik") linked from the footer, complete with selectable speed levels, wall-mode toggles, Web Audio sound effects, `localStorage` high-score persistence, and keyboard (Arrow/WASD) plus touch D-pad/swipe controls.
* **Responsive Glassmorphic UI & Navigation:** Optimized across mobile, tablet, and desktop viewports with subtle glassmorphism, reactive cursor spotlighting, scroll-reveal animations, and scroll-spy active navbar indicators.

---

## 🛠️ Built With
* **HTML5 & Modern JavaScript (ES6+)**
* **Tailwind CSS** (via CDN for utility-first styling)
* **Custom CSS3** (Theme variables, glassmorphism, animations, and responsive components)
* **Lucide Icons** (Minimalist UI icons)
* **Google Apps Script & Google Sheets** (Headless CMS backend)
* **Vercel Serverless API (Gemini & Groq)** (Backend for the Miyo AI assistant)
* **GitHub Pages** (Hosting)

---

## 📁 Repository Structure
```text
.
├── index.html                  # Main layout, dynamic CMS renderer, and Miyo AI chat widget
├── style.css                   # Custom styles, theme variables, animations, and UI components
├── favicon.png                 # Optimized 128x128 RGBA "bay" favicon (white for dark theme)
├── favicon-light.png           # Optimized 128x128 RGBA "bay" favicon (black for light theme)
├── logo-bay.png                # Theme-adaptive wordmark logo for footer (white/black)
├── 2_20260925_193506_0001.png  # Optimized 160x160 RGBA mascot avatar for Miyo
├── games/
│   └── ular.html               # Standalone Snake arcade mini-game ("Snake Klasik")
└── README.md                   # Repository documentation
```
