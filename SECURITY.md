# Security Policy

## Supported Versions

Archers Arrow Shoot is a static, single-file browser game with no backend
service. The `main` branch is always the currently supported version.

| Version | Supported |
| ------- | --------- |
| main    | ✅         |

## Reporting a Vulnerability

This project has no server, database, or user authentication — all game
state (coins, skins, leaderboard, achievements) is stored client-side in the
browser's `localStorage` and never transmitted anywhere.

If you nonetheless discover a security-relevant issue (for example, an XSS
vector via the player name input, or a way to corrupt/escape the
`localStorage` sandbox), please report it responsibly:

1. **Do not** open a public issue for security reports.
2. Open a private security advisory via the repository's **Security** tab
   (GitHub → Security → Report a vulnerability), or contact a maintainer
   directly.
3. Include steps to reproduce and, if possible, a minimal example.

We aim to acknowledge reports within a few days and will credit reporters
in the fix's release notes unless anonymity is requested.

## Scope

Out of scope: issues that require a compromised browser, a malicious
browser extension, or physical access to the user's device — these are
outside what a static front-end game can defend against.
