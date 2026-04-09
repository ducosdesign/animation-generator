# SVG Animata 🚀
**The Lightweight Interactive SVG Animation Generator**

SVG Animata is a web-based utility designed for designers and developers who need high-quality, interactive SVG animations without the overhead of heavy libraries like Lottie or the complexity of manual CSS keyframe coding.

## 🔗 Live Demo
[Check out the live tool here](https://animation-generator-ten.vercel.app/)

---

## ✨ Features
* **Zero-Configuration:** Simply paste an SVG URL to get started.
* **Self-Contained Embeds:** Generates code that includes the SVG data and animation logic in one snippet—no external hosting required.
* **Interactive Triggers:** Toggle between `Infinite Loop` and `On Hover` modes.
* **Pro Animation Library:**
    * **Pulse:** Gentle scaling effect.
    * **Spin:** 360-degree rotation.
    * **Shake:** High-energy wiggle for alerts.
    * **Float:** Smooth vertical levitation.
    * **Neon Glow:** Dynamic drop-shadow pulsing.
* **Vibe Coding Workflow:** Built using an AI-assisted development cycle to prioritize UX and performance.

---

## 🛠️ How It Works
SVG Animata uses a **Reactive UI** approach. When you change a setting, the program:
1.  Updates a hidden configuration object.
2.  Re-renders a live preview using a parent-container hover logic (to prevent "shaking" bugs).
3.  Wraps the animation into a custom CSS `@keyframes` block and provides a copy-pasteable HTML snippet.

---

## 🚀 Installation & Usage
This is a client-side application. No installation is required.
1.  Open `index.html` in any modern browser.
2.  Paste your SVG link.
3.  Select your animation style.
4.  Copy the generated code into your own project's `<body>`.

---

## 📅 Roadmap (Assignment 2 Timeline)
- [x] **Week 1-2:** MVP Release with core animations.
- [x] **Week 3:** Implementation of Hover-Stability logic.
- [ ] **Week 5:** Support for local SVG file uploads (FileReader API).
- [ ] **Week 6:** Individual path/layer selection for complex SVGs.
- [ ] **Week 7:** Final UI polish and minification.

---

## 🎓 Academic Context
This project was developed for **Assignment 2** as an exploration of **Agentic Engineering**. By orchestrating AI tools to handle technical boilerplate, I focused the design on solving specific friction points in the digital media workflow.

---

## 📄 License
MIT License - Feel free to use this for your own projects!
