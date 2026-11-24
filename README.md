# Tenno Hub

**An all-in-one desktop companion for Warframe.**

Tenno Hub brings the world state, the market, build planning, your profile, your daily and weekly progress and the Warframe community together in one Windows app. There is nothing to host and no new account to create: install it, answer a one-minute setup wizard, and you're ready.

![Tenno Hub home screen](screenshots/01-home.png)

> Tenno Hub is an unofficial fan project. It is not affiliated with, endorsed by or sponsored by Digital Extremes Ltd. Warframe and all related names and images are trademarks of Digital Extremes Ltd.

## Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Updates](#updates)
- [Versions](#versions)
- [Safety and privacy](#safety-and-privacy)
- [Reporting problems](#reporting-problems)
- [System requirements](#system-requirements)
- [Credits](#credits)

## Features

| Area | What Tenno Hub does |
|---|---|
| **World state** | Void Fissures (normal, Steel Path and Void Storms), alerts, invasions, the Sortie, the Archon Hunt, Arbitration, open-world cycles, bounties, Nightwave, Baro Ki'Teer and Varzia with live market prices, Steel Path honors, Archimedea and the 1999 calendar. Every mission shows the planet, the mission type and the node, the way the game does. |
| **Origin System map** | An interactive 3D map of the Origin System. Select a planet to see the resources extractors bring back there, the extractor hazard, every node with its mission type, faction and level range, and everything happening on that planet right now. |
| **Extractors and Foundry** | Deploy Titan and Distilling extractors from the map and get a desktop notification when they are ready to collect. Foundry timers can be started from any item. |
| **Mission detection** | Alerts, Sortie stages, the Archon Hunt and Kahl's Garrison are marked as done when you finish them in Warframe, by reading the game's own log file on your PC. |
| **Market** | Live warframe.market prices and order books with one-click whisper copy, price history, set breakdowns, a price watchlist with alerts, riven auctions and ducat values. |
| **Builds** | A full build planner with live stat math, Forma and capacity, arcanes, Archon Shards and build cost in platinum. Share builds as a code or post them straight to a Discord channel. |
| **Codex and relics** | Every Warframe, weapon, companion, mod and arcane with stats, crafting requirements, drop locations and prices, a drop finder, and a relic browser with each relic's art, rewards and expected platinum per run. |
| **Profile** | Link your Warframe account on Digital Extremes' own sign-in page to see your glyph, Mastery Rank, playtime, combat stats, loadout, syndicates, achievements with progress, and your in-game wishlist. |
| **Trackers** | Daily and weekly checklist, Mastery tracker synced from your profile, and a wishlist that tracks the parts you still need and where they drop. |
| **Community** | The official Warframe Forums, r/Warframe and Discord inside the app, each in its own isolated session. |
| **Discord** | Rich Presence on your Discord profile and alerts posted to your own server channels (Baro, fissures, alert rewards, Sorties and more), plus one-click sharing of builds, prices and screenshots. |
| **Notifications** | Desktop notifications for Baro, Sorties, Nightwave, alert and invasion rewards, fissure rules, cycle changes, timers and price targets, with quiet hours. |
| **Screenshots** | Capture the Tenno Hub window with **Ctrl + Shift + S**. Screenshots are saved to *Pictures › Tenno Hub* and can be copied to the clipboard or shared to Discord. |
| **Interface** | Nine themes including a light theme, accent colours, and optional interface sounds. |

## Screenshots

> The screenshots show a demonstration profile.

| | |
|---|---|
| ![World state](screenshots/02-world-state.png) **World state** | ![Origin System map](screenshots/03-origin-system.png) **Origin System map** |
| ![Planet details](screenshots/04-planet-details.png) **Planet details** | ![Sortie and Archon Hunt](screenshots/05-sortie-archon-hunt.png) **Sortie and Archon Hunt** |
| ![Market](screenshots/06-market.png) **Market** | ![Build planner](screenshots/07-build-planner.png) **Build planner** |
| ![Codex](screenshots/08-codex.png) **Codex** | ![Relics](screenshots/09-relics.png) **Relics** |
| ![Profile](screenshots/10-profile.png) **Profile** | ![Achievements](screenshots/11-achievements.png) **Achievements** |
| ![Wishlist](screenshots/12-wishlist.png) **Wishlist** | ![Trackers](screenshots/13-trackers.png) **Trackers** |
| ![Foundry and extractors](screenshots/14-foundry-extractors.png) **Foundry and extractors** | ![Settings](screenshots/15-settings.png) **Settings** |
| ![Setup wizard](screenshots/16-setup-wizard.png) **Setup wizard** | ![Light theme](screenshots/17-home-light-theme.png) **Light theme** |

## Installation

1. Download `TennoHub-Setup-<version>.exe` from the [latest release](https://github.com/iRelapsedx/TennoHub/releases/latest).
2. Run the installer. Tenno Hub is installed for your Windows account only and does not require administrator rights. You can choose the install folder.
3. Follow the setup wizard. Every step (platform, Warframe account, Discord and notifications) is optional and can be changed later in Settings.

The installer is not code-signed yet, so Windows SmartScreen may report an unknown publisher. If you downloaded the installer from this repository's releases, choose **More info → Run anyway** to continue.

## Updates

New versions are published on this repository's [Releases](https://github.com/iRelapsedx/TennoHub/releases) page. To update, download the newest installer and run it; your settings, trackers, builds and linked account are kept. To be notified of new versions, choose **Watch → Custom → Releases** at the top of this page. Your current version is shown in **Settings → About**.

## Versions

Tenno Hub uses `MAJOR.MINOR.PATCH` version numbers, and each release is tagged with its version (for example `v1.0.0`).

- **Major** versions (`2.0.0`) bring large changes to how the app works.
- **Minor** versions (`1.1.0`) add features and improvements.
- **Patch** versions (`1.0.1`) fix problems. Urgent fixes are published as **hotfix** releases, which also increase the patch number and are marked as a hotfix in their release notes.

Every release lists what is new, followed by what was added, changed, fixed and removed.

## Safety and privacy

- Tenno Hub never asks for your Warframe password. You sign in on Digital Extremes' own page, and Tenno Hub reads only your public account ID.
- Tenno Hub sends no telemetry and runs no servers. Your trackers, builds, settings and screenshots stay on your PC.
- Mission detection reads Warframe's log file on your PC and keeps only which activities were completed and when. Nothing from the log leaves your computer, and the feature can be turned off in **Settings → General**.
- The Warframe Forums, Reddit, Discord, warframe.market and Overframe each run unmodified in their own isolated session, with no access to Tenno Hub or your files.
- Discord channel links are stored encrypted with Windows' data protection, and nothing Tenno Hub posts can ping @everyone, roles or users.
- Game data is downloaded from public sources and verified with SHA-256 checksums before use.

## Reporting problems

Open a [bug report](https://github.com/iRelapsedx/TennoHub/issues/new?template=bug_report.yml) and include your Tenno Hub version from **Settings → About**. Reports are public, so please don't include passwords, Discord webhook links or other personal information.

## System requirements

- Windows 10 or Windows 11, 64-bit
- An internet connection for live data (Tenno Hub starts with the last data it downloaded when you are offline)
- Graphics with WebGL support for the 3D Origin System map (a flat chart is shown otherwise)

## Credits

- World state: [warframestat.us](https://hub.warframestat.us) (WFCD)
- Items, mods, relics and drops: [WFCD warframe-items](https://github.com/WFCD/warframe-items)
- Achievements, star chart nodes and extractor resources: [warframe-public-export-plus](https://github.com/calamity-inc/warframe-public-export-plus)
- Market data: [warframe.market](https://warframe.market)
- Player profiles: Digital Extremes' public profile service
- Game art (item icons, relic art, glyphs, scenes and portraits) is loaded from the WFCD image CDN and is never taken from game files, as permitted for fan projects by Digital Extremes' [Content Policy](https://warframe.fandom.com/wiki/Content_Policy). Planet art and interface sounds are created by the app.
