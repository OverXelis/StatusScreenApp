# Changelog

All notable changes to the Status Screen App. This project uses a single self-contained
`StatusScreenApp.html`; versions below were developed iteratively and consolidated into 1.0.0.

## [1.0.0] — 2026-07-14

First stable release. Includes everything below, plus:

- Renamed the app file `index.html` → `StatusScreenApp.html`.
- Visual polish (slate theme): larger buttons, grouped FP/TP stepper pills, section
  headers with accent bars and dividers, enlarged tabs, topbar stat pills, and a
  centered, framed Home "status window".
- Keyboard **Tab** now moves cleanly between fields within a section (focus is preserved
  across edits; inline utility buttons are skipped in the tab order).
- Published as a live web app via GitHub Pages.

## [0.3] — Training Points, exports & sharing

- **Training Points** — a new unlimited per-stat point pool (earned through effort),
  shown as "TP" in the topbar and folded into the stat math inside trait multipliers.
- **Titles & Traits** restyled as cards, each with a manuscript-ready **Copy** button.
- **Per-character export** for sharing a single character with another user.
- Removed decorative emojis.

## [0.2] — Home screen, traits & manuscript export

- **Home tab** with a live, book-formatted status overview and a **Copy Status Screen**
  button producing the exact manuscript format.
- **Traits** (permanent passives, soft cap of 3) with optional stat effects, including
  multipliers such as ×3 Willpower.
- **HP / MP** derived stats (Constitution ×10 / Mana ×10, configurable).
- **Level-10 class unlock** with an auto-snapshot; class points only apply once a class
  is assigned.
- **Skills** — Active/Bond use Proficiency + Level, Passive uses Tier; skills keep an
  evolution history. Added a **Bond Skills** section.
- **Structured items** (rank / type / rarity / enchantments) with per-item export.
- **Profile tab** — character-bible fields captured in snapshots.

## [0.1] — Initial tracker

- Single-file local character tracker with layered stat engine, free-point banking,
  class rarity × proficiency stats-per-level, ranks (E→S), snapshots, skills, titles,
  and gear. Saved locally with JSON backup/import.

[1.0.0]: https://github.com/OverXelis/StatusScreenApp/releases/tag/v1.0.0
