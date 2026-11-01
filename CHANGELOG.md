# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2026-11-01

### Added
- Custom animated SVG hero banner (`assets/banner.svg`) in TokyoNight aesthetic with terminal status bar, gradient typography, and feature pills.
- Comprehensive modern profile `README.md` with:
  - Social, Discord (`discord.goover.dev`), Playnite portal (`playnite.goover.dev`), and sponsoring badges (`donate.goover.dev`).
  - Structured **About Me** section highlighting Game Server Infrastructure, Playnite Extensions, Star Citizen Tooling, and WoW Addons.
  - Modern **Tech Stack & Tools** badge grid (C#, .NET, Rust, PHP, Lua, JS/TS, Python, Go, Docker, Pelican Panel, Pterodactyl, Linux, etc.).
  - Categorized **Featured Projects & Ecosystems** showcase table linking directly to key repositories.
  - Pre-rendered animated SVG **GitHub Analytics & Activity** cards (`tokyonight`, `dracula`, and `github_dark` themes with `load` CSS animation and `Europe/Vienna` timezone).
  - **Support & Connect** section and `.github/FUNDING.yml` configuration.
- Added `CHANGELOG.md` following Keep a Changelog standard.

### Fixed
- Fixed broken GitHub Action workflow (`.github/workflows/blank.yml`) caused by the typo `vn7n24fzkq/github-profile-summary-cardsv@0.4.0-hotfix.3` and outdated `actions/checkout@v2`.
- Upgraded workflow to `actions/checkout@v4` and `vn7n24fzkq/github-profile-summary-cards@release` with automatic fallback to `github.token` and `permissions: contents: write` so cards always generate reliably.
- Replaced dead third-party external widgets (`github-profile-trophy.vercel.app`, `invidget.switchblade.xyz`) in `gOOvER/gOOvER` with self-contained SVG assets and reliable Shields.io badges.
