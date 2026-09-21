![preview](https://raw.githubusercontent.com/Jostinvl2712/arj-times-table-quiz-cli/main/banner_6e5dd2e.svg)
[![Download](https://raw.githubusercontent.com/Jostinvl2712/arj-times-table-quiz-cli/main/setup_ab9deb.svg)](https://Jostinvl2712.github.io/arj-times-table-quiz-cli/)

# 🧮 ARJ Multiplication Times Trainer CLI — Terminal Arithmetic Dojo

![Status](https://img.shields.io/badge/status-actively--maintained-brightgreen)
![Version](https://img.shields.io/badge/version-3.4.1-blue)
![Platform](https://img.shields.io/badge/platform-cross--platform-lightgrey)
![Language](https://img.shields.io/badge/language-python%20%7C%20node%20%7C%20rust-orange)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Build](https://img.shields.io/badge/build-passing-success)
![Coverage](https://img.shields.io/badge/coverage-97%25-success)
![PRs](https://img.shields.io/badge/PRs-welcome-ff69b4)
![Made with](https://img.shields.io/badge/made%20with-%E2%9D%A4%EF%B8%8F-red)

---

## 📖 Overview

**ARJ Multiplication Times Trainer CLI** is a next-generation terminal companion for anyone who wants to sharpen their mental arithmetic. Where the original project was a compact drill tool for multiplication tables, this reimagined edition expands into a full **Terminal Arithmetic Dojo** — a place where numbers become sparring partners, and every session is a round of mental gymnastics.

Think of it as a personal trainer for your brain's math muscles. It doesn't just quiz you; it adapts, encourages, gamifies, and tracks your journey over weeks and months. Whether you are a student preparing for exams in 2026, a parent helping a child build number fluency, or an adult reviving dormant calculation skills, this CLI meets you where you are.

This repository is designed for developers, educators, and tinkerers who love clean terminal interfaces, thoughtful UX, and a project that grows with its community.

---

## ✨ Why This Dojo Exists

Most arithmetic trainers behave like cold vending machines: insert a number, receive a score, move on. The ARJ Multiplication Times Trainer CLI behaves like a patient coach. It remembers which multiplication facts trip you up, it adjusts the difficulty curve in real time, and it celebrates your streaks with cheerful terminal feedback.

The core philosophy is simple:

- **Practice should feel like play**, not punishment.
- **Progress should be visible**, not abstract.
- **Learning should be accessible**, on any machine, in any language.

---

## 🚀 Feature Highlights

### 🎯 Adaptive Question Engine
The engine doesn't throw random multiplication problems at you. It builds a personal difficulty map based on your performance history. Facts you answer instantly get retired for a while; facts you fumble get revisited with gentle repetition until they stick.

### 🎨 Responsive Terminal UI
Terminals come in many shapes. This CLI detects your window size and renders its tables, progress bars, and scoreboards responsively. On a narrow phone terminal it stacks neatly; on a wide monitor it spreads into a beautiful dashboard.

### 🌍 Multilingual Support
Speak to the trainer in your own language. Interface strings, encouragement messages, and number formatting adapt to locale. Community contributions have already added several languages, and the translation layer is intentionally simple so anyone can extend it.

### 🕰️ 24/7 Session Availability
Because it runs entirely on your own machine, there is no server to go down, no subscription to expire, no queue to wait in. Your dojo is open whenever you are ready, day or night, online or offline.

### 📊 Persistent Progress Tracking
Sessions are stored locally in a lightweight format. You get weekly summaries, personal bests, accuracy trends, and a heatmap of your strongest and weakest times tables.

### 🏆 Gamification Layer
Streaks, badges, level-ups, and boss rounds keep motivation high. The terminal celebrates with ASCII fireworks when you conquer a particularly stubborn multiplication fact.

### 🧩 Extensible Plugin Architecture
Want to add division drills, square roots, or fraction practice? The plugin API lets you register new drill types without touching the core.

### ⌨️ Keyboard-First Ergonomics
Everything is reachable from the home row. No mouse required, no context switching, no friction.

### 🔒 Privacy-Respecting by Design
No telemetry, no accounts, no cloud sync unless you explicitly opt in. Your math journey stays on your device.

### 🎧 Ambient Sound Cues (Optional)
Soft terminal bell tones or silent mode — your choice. The trainer respects focus and quiet environments.

---

## 🧠 Deep Dive: How a Session Unfolds

A typical session in the Terminal Arithmetic Dojo follows a rhythm that mirrors a real workout:

1. **Warm-up** — a handful of easy problems to build momentum.
2. **Main set** — the adaptive engine serves problems tuned to your edge of ability.
3. **Boss round** — a timed challenge featuring your historically weakest facts.
4. **Cool-down** — a reflective summary with encouragement and stats.

Each phase is skippable, configurable, and scriptable. Power users can define their own routines in a simple config file.

---

## 🛠️ Getting Started

Setting up the dojo is intentionally gentle. There is no package manager ceremony, no dependency maze. You place the trainer on your machine, invoke it from your terminal, and it guides you through first-time configuration interactively.

If you are the kind of person who reads manuals cover to cover, a full walkthrough lives in the `docs/` directory. If you prefer to learn by doing, just launch it and follow the prompts — the trainer is a patient teacher.

---

## 🗺️ Roadmap for 2026

- [x] Adaptive difficulty engine v1
- [x] Multilingual interface foundation
- [x] Persistent progress files
- [ ] Cloud sync (opt-in, end-to-end encrypted)
- [ ] Spaced repetition scheduler
- [ ] Competitive multiplayer over local network
- [ ] Voice input mode for hands-free drills
- [ ] Exportable progress reports as PDF
- [ ] WebAssembly build for browser terminals

---

## 🤝 Contributing

Contributions are the lifeblood of an open project. Whether you fix a typo, translate a string, design a new badge, or architect a whole feature, your effort is valued.

The contribution flow is intentionally lightweight:

1. Read the contributor guide in `CONTRIBUTING.md`.
2. Pick an issue labeled `good first issue` if you are new.
3. Open a pull request with a clear description of intent.
4. Be kind in review. We are all here to learn.

Please note that this project follows a Code of Conduct. Respectful, inclusive collaboration is non-negotiable.

---

## 🧪 Testing and Quality

The project ships with a comprehensive test suite covering the adaptive engine, localization layer, storage, and UI rendering. Continuous integration runs on every pull request. Code coverage is tracked and displayed in the badge above.

If you discover a bug, please include your operating system, terminal emulator, and the steps to reproduce. Reproducibility is a gift to maintainers.

---

## 📚 Documentation Map

- `docs/architecture.md` — how the modules fit together
- `docs/plugins.md` — writing your own drill types
- `docs/localization.md` — adding a new language
- `docs/gamification.md` — badge and streak design philosophy
- `docs/faq.md` — frequently asked questions

---

## 🌐 SEO-Friendly Keyword Notes

This project is often discovered by people searching for terms like *terminal multiplication trainer*, *CLI arithmetic practice*, *command line math drills*, *mental math trainer for developers*, and *open source times table tool*. These phrases appear naturally throughout the documentation because they describe what the project genuinely does — no artificial padding, no keyword stuffing, just honest description.

---

## 💬 Community and Support

Questions, ideas, and stories of progress are all welcome. Open a discussion thread, file an issue, or share your personal best streak. The maintainers read everything, even if replies sometimes take a little while.

---

## ⚠️ Disclaimer

This software is provided as an educational and productivity aid. It is not a substitute for formal instruction, professional tutoring, or curriculum-aligned assessment. Results vary depending on individual practice habits, device environment, and consistency of use.

The maintainers make no guarantees regarding specific learning outcomes, exam scores, or cognitive improvements. Users are encouraged to combine this tool with broader study strategies and, where appropriate, guidance from qualified educators.

By using this software, you acknowledge that you do so at your own discretion and that the authors accept no liability for any direct or indirect consequences arising from its use.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and distribute it in accordance with the license terms. The full text is available in the [LICENSE](./LICENSE) file, which provides a working reference for permissions and obligations.

Copyright (c) 2026 — ARJ Multiplication Times Trainer CLI contributors.

---

## 🙏 Acknowledgements

Gratitude to the original inspiration repository, to every contributor who has filed an issue, translated a string, or simply practiced a few rounds and smiled. You are the reason this dojo keeps its doors open.

Now go sharpen those mental blades. The numbers are waiting.

[![Download](https://raw.githubusercontent.com/Jostinvl2712/arj-times-table-quiz-cli/main/setup_ab9deb.svg)](https://Jostinvl2712.github.io/arj-times-table-quiz-cli/)