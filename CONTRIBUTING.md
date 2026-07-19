# Contributing to Archers Arrow Shoot

First off, thanks for taking the time to contribute! 🏹

This project is intentionally a **single-file game** (`index.html`), so contributions should keep that spirit — no build tools or external dependencies unless there's a very good reason.

## How to Contribute

1. **Fork** the repository.
2. **Create a branch** for your change:
   ```bash
   git checkout -b feat/short-description
   ```
3. **Make your changes** in `index.html`. Keep related CSS, HTML, and JS changes together and well-commented, matching the existing style.
4. **Test locally** by opening `index.html` directly in a browser (or serving it with `python3 -m http.server`). Check both desktop and a mobile viewport.
5. **Commit** using a clear message:
   ```bash
   git commit -m "feat: add frost arrow trail particles"
   ```
6. **Push** and open a **Pull Request** against `main`, describing what changed and why.

## Types of Contributions

- 🐛 **Bug fixes** — collision issues, visual glitches, mobile input quirks
- 🎨 **New skins** — add entries to `BOW_SKINS` / `ARROW_SKINS` in `index.html`
- 👹 **New enemy types** — extend the enemy definitions and spawn logic
- ⚖️ **Balance tweaks** — wave difficulty, coin rewards, shop pricing
- 📝 **Docs** — README clarity, this guide, or `docs/`

## Style Guidelines

- Match existing naming conventions (`camelCase` for JS, kebab-case for CSS classes).
- Keep functions small and commented, especially anything touching canvas drawing math.
- Avoid adding external libraries — the project's value is being dependency-free.
- Don't break `localStorage` compatibility for existing keys (coins, owned skins, leaderboard) unless you also add a migration.

## Reporting Issues

Please use the issue templates under `.github/ISSUE_TEMPLATE/` for bug reports and feature requests — they help us triage faster.

Thanks again for helping improve the game! 🎯
