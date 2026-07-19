# Archers Arrow Shoot

### 🏹 Defend the keep — a single-file, browser-based archery defense game

*Draw, aim, release — with a full coin & skin shop for your bow and arrows.*

[![Made with HTML5 Canvas](https://img.shields.io/badge/made%20with-HTML5%20Canvas-orange?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)
[![No build step](https://img.shields.io/badge/build-none%20needed-blue?style=for-the-badge)](#-quick-start)

[🎮 Play Online](#-quick-start) · [🐛 Report Bug](.github/ISSUE_TEMPLATE/bug_report.md) · [💡 Request Feature](.github/ISSUE_TEMPLATE/feature_request.md)

---

## 📌 About

**Archers Arrow Shoot** is a self-contained archery defense game that runs entirely in the browser — no build tools, no dependencies, just one `index.html` file. Pull back the bow, judge the arc, and stop every raider before they reach your gate.

It also ships with a persistent **coin economy and shop**, so you can unlock and equip cosmetic bow and arrow skins as you play.

### ✨ Features

| Feature | Description |
| --- | --- |
| 🏹 **Physics-based archery** | Drag-to-aim, power-based draw, real projectile arc with gravity |
| 🌊 **Wave-based combat** | Increasingly difficult raider waves, including shielded and ranged enemies |
| 🔥 **Combo & scoring system** | Chain hits and headshots for bonus points and slow-motion payoff shots |
| 🪙 **Coin economy** | Earn coins by playing; persisted locally between sessions |
| 🛍️ **Skin shop** | Unlock and equip colored bow & arrow skins (Crimson, Emerald, Azure, Void, Gold, and more) |
| 🏆 **Leaderboard & achievements** | Local high-score leaderboard, unlockable achievements, and daily rewards |
| 📱 **Mobile-first** | Touch-friendly controls, responsive canvas, safe-area aware HUD |

---

## 🚀 Quick Start

### Option 1 — Play Instantly (Recommended)

Just open `index.html` in any modern browser. No server, no install, no build step.

### Option 2 — Clone & Run Locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/Archers-Arrow-Shoot.git
cd Archers-Arrow-Shoot

# Open it directly...
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux

# ...or serve it locally (recommended for consistent behavior)
python3 -m http.server 8000
# then visit http://localhost:8000
```

### Option 3 — GitHub Pages

This repo is Pages-ready (`index.html` at root + `.nojekyll`). Enable **Settings → Pages → Deploy from branch (main)** and your game will be live at:

```
https://<your-username>.github.io/Archers-Arrow-Shoot/
```

---

## 🕹️ How to Play

- **Aim:** drag from your archer, away from the target.
- **Power:** the further you pull, the harder you shoot.
- **Release:** let go to fire the arrow.
- Stop every raider before they reach the gate. Chain hits to build combo multipliers, and land headshots for bonus score and a slow-motion moment.

---

## 🗂️ Project Structure

```
Archers-Arrow-Shoot/
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── docs/
│   └── CHANGELOG.md
├── assets/            # reserved for future sprites/audio
├── index.html         # the entire game (HTML + CSS + JS, single file)
├── .gitignore
├── .nojekyll
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── LICENSE
└── README.md
```

The whole game — markup, styling, and logic — lives in `index.html` by design, so it can be opened, forked, and shared without any tooling.

---

## 🛍️ Shop & Skins

Coins are earned during runs and stored locally in the browser (`localStorage`). Open the **🛍️ Toko** button from the main menu to browse:

- **Bow skins:** Oak Recurve (default), Crimson Warbow, Emerald Longbow, Azure Bow, Void Bow, Golden Bow
- **Arrow skins:** Classic Fletch (default), Blood Arrow, Frost Arrow, Toxic Arrow, Shadow Arrow, Golden Arrow

Owned skins can be freely swapped at any time; your equipped skin is reflected live on the archer and every arrow fired.

---

## 🤝 Contributing

Contributions are welcome — from balance tweaks and new enemy types to entirely new skins.

1. **Fork** this repository
2. **Create** your branch: `git checkout -b feat/your-contribution`
3. **Commit**: `git commit -m 'feat: add new bow skin'`
4. **Push**: `git push origin feat/your-contribution`
5. **Open a Pull Request**

📋 Read the full [**Contributing Guide →**](CONTRIBUTING.md)

| Type | How |
| --- | --- |
| 🐛 Found a bug | [Open an Issue](.github/ISSUE_TEMPLATE/bug_report.md) |
| 💡 Feature idea | [Open an Issue](.github/ISSUE_TEMPLATE/feature_request.md) |
| 🎨 New skin | Submit a Pull Request adding to `BOW_SKINS` / `ARROW_SKINS` in `index.html` |

---

## 📄 License

Licensed under the [MIT License](LICENSE) — free to use, modify, and share.

---

**⭐ If you enjoy Archers Arrow Shoot, consider starring the repo!**
