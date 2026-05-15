# Workspace Tracker

A zero-build, high-performance workspace session tracker built to log physical or mental reps while working. Designed with a focus on raw functional utility, immediate visual feedback, and a frictionless user experience.

![UI Preview](https://via.placeholder.com/800x400.png?text=Workspace+Tracker+UI)

## ⚡ Core Philosophy
* **Zero Boilerplate:** Runs entirely from a single file via CDN. No `npm install`, no Webpack, no node_modules.
* **Declarative Logic:** Uses Vue 3's Composition API for absolute state control.
* **Utility-First UI:** Styled completely with Tailwind CSS for rapid, scalable design.

## 🛠 Tech Stack
* **Vue 3 (Composition API):** Reactivity and state management.
* **Tailwind CSS:** Layout and typography.
* **Canvas Confetti:** Micro-interaction physics engine.
* **Native CSS:** GPU-accelerated opacity fades and transitions.

## 🚀 How to Run
Because this relies on zero build tools, deployment and local testing are instant.

1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. *Optional:* Use VS Code's **Live Server** extension for hot-reloading during development.

## 🧠 Technical Highlights
* **Dynamic Binding:** Utilizes Vue's `:class` to trigger hardware-accelerated background color interpolation without forcing DOM reflows.
* **Component Lifecycle:** Implements `<transition>` tags with explicit `:key` tracking to unmount and remount specific text elements cleanly.
* **Scoped Execution:** Stacks UI updates, randomized array selection, and external physics triggers into a single synchronous JavaScript pipeline.

---
*Developed by Dishant Naik | Built in Goa, India*