# Changelog

All notable changes to this project are documented here.
This project follows a simple date-based log rather than strict semver, since it ships as a single evolving `index.html`.

## [Unreleased]

### Added
- 🛍️ Shop screen with **Bow** and **Arrow** tabs.
- 6 unlockable **bow skins**: Oak Recurve (default), Crimson Warbow, Emerald Longbow, Azure Bow, Void Bow, Golden Bow.
- 6 unlockable **arrow skins**: Classic Fletch (default), Blood Arrow, Frost Arrow, Toxic Arrow, Shadow Arrow, Golden Arrow.
- Live-rendered skin previews inside the shop cards (mini canvas icons).
- Coin display surfaced on the main menu.
- Equipped skins now render on the bow, the nocked arrow, and every arrow in flight.
- Persistent skin ownership & equip state via `localStorage`.

## [Initial]

### Added
- Core archery gameplay: drag-to-aim, power draw, projectile physics.
- Wave-based enemy spawning with multiple enemy types (grunt, runner, brute, shielded, zigzag, ranged archer).
- Combo system, score, lives, and game-over flow.
- Local leaderboard, achievements, and daily reward system.
- Mobile-first responsive HUD with safe-area support.
