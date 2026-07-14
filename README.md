# Status Screen App

A local, single-file character stat tracker for litRPG fantasy novels. It models classes, ranks, stats, skills, titles, traits, gear, and snapshots, and exports a character's status screen in manuscript-ready format.

**No install, no account, no internet required.** The whole app is one HTML file; your data is saved in your own browser.

## Use it

**Online (easiest):** open the live version —> **https://overxelis.github.io/StatusScreenApp/**

**Offline / your own copy:**
1. Download [`StatusScreenApp.html`](StatusScreenApp.html) (on the file page, click the download / "Raw" button and save it).
2. Double-click the file — it opens in your default browser.
3. That's it. No other files are needed.

> Tip: bookmark the online version, or keep the downloaded file somewhere handy. Both work the same way.

## Sharing with a friend

Send them the one file **`StatusScreenApp.html`** (or just the link above). Nothing else from this folder is required.

Characters are saved **per browser**, so a fresh copy starts empty. To hand someone a specific character exactly as you see it:

1. Open the character → **Profile** tab → **Sharing → “Export this character”**. This saves a `.json` file.
2. Send them that `.json`.
3. They open the app → **Import** (sidebar) → pick the file. The character loads with all stats, snapshots, items, and traits intact.

Use **Backup (JSON)** in the sidebar to export *all* your characters at once (for your own backups or moving between computers).

## Features

- **Layered stat engine** — Base + Free points + Training points + Class, then Titles, Traits, and Gear, with a per-stat breakdown showing the math.
- **Free points & Training points** — bank and distribute the 3 free points per level; add unlimited training points earned through effort.
- **Classes** — rarity × proficiency stats-per-level table, level-ups, proficiency advances, and class evolution (with automatic snapshots).
- **Ranks & levels** — levels never reset; Rank climbs E→S every 30 levels. Class unlocks at level 10.
- **Titles, Traits, Skills, Items** — structured entries with manuscript-ready **Copy** buttons; traits can carry stat multipliers (e.g. ×3 Willpower).
- **Home status screen** — a live, book-formatted overview with a one-click **Copy Status Screen** for pasting into your manuscript.
- **Snapshots** — freeze a character's full state at any milestone and revert to it later.
- **Character bible** — description, chapter introduced/last seen, motivation, fear, organization, and notes.

## Data & privacy

Everything is stored locally in the browser's `localStorage` — nothing is uploaded anywhere. Clearing your browser data will remove saved characters, so use **Backup (JSON)** periodically.

## Versioning

See [CHANGELOG.md](CHANGELOG.md) for what changed in each version.

## Tech notes

Single self-contained `StatusScreenApp.html` — plain HTML/CSS/JavaScript, no build step, no dependencies, no server.

## License

See [LICENSE](LICENSE).
