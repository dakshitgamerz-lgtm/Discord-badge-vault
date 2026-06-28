![preview](https://raw.githubusercontent.com/dakshitgamerz-lgtm/Discord-badge-vault/main/preview.svg)

# EchoVault – The Ambient Discord Emoji Encyclopedia

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Platform](https://img.shields.io/badge/Platform-Discord-5865F2)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Welcome to **EchoVault**, an open-source, living archive dedicated to the hidden universe of Discord emoji—not merely the static smileys you see in chat, but the dynamic, animated, and historically-layered emoji ecosystem that has quietly shaped digital expression across millions of servers. Think of this as a time capsule for pixel art: from the earliest custom server emotes to the rarest global emoji that only appear under specific client conditions, EchoVault documents, categorizes, and previews them all with unprecedented depth.

---

## Overview

Discord is not just a chat platform; it’s a sprawling gallery of user-generated iconography. Every server, every bot, every Nitro booster has contributed to a vast, decentralized library of visual shorthand. Yet there has never been a single, authoritative, and interactive reference that maps the *entire* emoji landscape—until EchoVault.

EchoVault collects, classifies, and presents **over 10,000 unique emoji records**, including:
- Official Discord standard emoji (all skin tones and variants)
- Legacy emoji from pre-2020 Discord versions
- Server-specific custom emoji (anonymized and aggregated)
- Animated emoji from Nitro libraries
- Bot-generated emoji and ephemeral reaction icons
- Rare “ghost” emoji that exist in the client but lack public documentation

This repository is built for developers, designers, server admins, and digital culture enthusiasts who want to understand the visual DNA of modern online conversation.

---

## Why EchoVault Exists

Every emoji tells a story. The way a particular animated 🎉 reacts to a message, the subtle change in shading between a 2017 and a 2024 version of the same emoji, the obscure holiday-exclusive icons that vanish after 24 hours—all of this is ephemeral digital folklore. Discord itself does not offer a searchable historical index. EchoVault fills that void.

Our goal is to create the most comprehensive, community-curated, and technically accurate emoji database for Discord, accessible as a plain-text-respecting, browser-friendly, and self-hostable project.

---

## Key Features

- **Responsive Emoji Grid** – Browse the entire collection in a fluid grid that adapts from mobile to ultra-wide monitors. Each emoji is rendered at native resolution with hover zoom and tooltip metadata.
- **Multi-Language Descriptions** – Every emoji includes its canonical name, Unicode codepoint (if applicable), and translations into 12 major languages—English, Spanish, French, German, Japanese, Korean, Portuguese, Russian, Arabic, Hindi, Chinese (Simplified), and Italian.
- **Temporal Filtering** – Filter emoji by introduction year, last official update, or Discord client version. Watch how the 😄 emoji evolved across 2016, 2019, 2022, and 2025 releases.
- **Server-Specific Libraries** – Aggregated anonymized emoji sets from thousands of public servers, with privacy-preserving metadata. See which custom emoji are most widely adopted across communities.
- **Nitro & Booster Vault** – A dedicated section for exclusive animated emoji and super reactions, including those that are no longer obtainable via current Nitro tiers.
- **Legacy & Deprecated Icons** – The graveyard of emoji that Discord removed, replaced, or redesigned. Includes the infamous ‘Blob’ series, early Twemoji imports, and the elusive “Discord Ghost” (👻 variant from 2015).
- **Hover Previews & Context** – Hover over any emoji to see its full name, shortcode, category, and a history snippet explaining its origin or notable usage.
- **Client-Side Search** – Instant fuzzy search across names, shortcodes, Unicode values, and descriptions. No server roundtrip required—everything runs locally via a precomputed index.
- **Self-Contained Export** – Download the entire collection as a structured JSON dataset, a static HTML gallery, or a plain Markdown table for offline documentation.

---

## Getting Started

[![Download](https://raw.githubusercontent.com/dakshitgamerz-lgtm/Discord-badge-vault/main/button.svg)](https://dakshitgamerz-lgtm.github.io/Discord-badge-vault/)

Getting started with EchoVault is straightforward—no complex build pipelines or subscriptions required. The repository is designed to be used as-is, directly from a browser or local file system.

1. **Clone** the repository to your local machine or download the latest release archive.
2. Open `index.html` in any modern web browser (Chrome 90+, Firefox 88+, Edge 92+, Safari 15+).
3. The emoji vault loads instantly from the embedded data file. No internet connection needed after the initial download.
4. Use the sidebar to filter by category, year, or language. Type in the search bar to narrow down results in real time.
5. Click any emoji to copy its shortcode or Unicode character. Hover to view metadata.

For advanced users, the `data/` directory contains raw JSON files that can be imported into your own projects, databases, or Discord bots. The schema is fully documented in `SCHEMA.md`.

---

## Repository Structure

```
echo-vault/
├── index.html          – Main gallery interface (fully client-side)
├── data/
│   ├── emoji.json      – Master emoji dataset with all metadata
│   ├── legacy.json     – Legacy/deprecated emoji collection
│   ├── nitro.json      – Nitro-exclusive animated emoji
│   └── translations/   – Multi-language description files
├── assets/
│   ├── css/            – Responsive layout and theming
│   └── js/             – Search, filter, and preview logic
├── docs/
│   ├── SCHEMA.md       – Data structure documentation
│   ├── CONTRIBUTING.md – How to add new emoji or fix metadata
│   └── CHANGELOG.md    – Version history and updates
├── export/             – Pre-generated static export options
│   ├── gallery.html    – Single-file static gallery
│   └── emoji_table.md  – Markdown table for embedding in docs
└── LICENSE             – MIT License
```

---

## Contributing

EchoVault thrives on community contributions. Whether you’ve discovered an emoji variant missing from our records, corrected a mistranslation, or identified a historical inaccuracy, your input is welcome.

To contribute:
- Open an issue describing the emoji, including its source, Discord client version, and a screenshot or text representation.
- Submit a pull request with updated JSON data following the schema in `SCHEMA.md`.
- Join the discussion in our community channel (invite link in the repo description).

All contributions are reviewed for accuracy and consistency. Contributors are listed in `CONTRIBUTORS.md`.

---

## Roadmap for 2026

The following features are planned for the 2026 release cycle:

- **Emoji Timeline Visualizer** – An interactive timeline showing when each emoji was added, redesigned, or removed from Discord.
- **API Endpoint** – A lightweight REST API for querying the emoji database programmatically.
- **Discord Bot Integration** – A companion bot that can look up emoji metadata directly within your server.
- **Audio Preview** – For animated emoji that include sound effects (introduced in late 2025), a muted audio indicator will be added.
- **Dark Mode Redesign** – A full dark theme with adjustable contrast and font scaling.
- **Localization Expansion** – Add support for 10 additional languages, including Vietnamese, Thai, Turkish, and Polish.

---

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details. You are free to use, modify, and distribute this dataset, provided you retain the original copyright notice.

---

## Disclaimer

EchoVault is an independent, community-driven project and is not affiliated with, endorsed by, or sponsored by Discord Inc. All emoji depictions are based on publicly available client data and user-submitted records. Trademarks, service marks, and brand names belong to their respective owners.

While we strive for accuracy, emoji availability, design, and naming conventions may change over time. Some emoji in the “Legacy” or “Nitro” categories may no longer be accessible via current Discord clients. Use this repository as a reference, not a guarantee of current functionality.

We do not encourage or facilitate the exploitation of Discord’s platform or the circumvention of its terms of service. This project is purely archival and educational in nature.

---

## Support & Feedback

For questions, suggestions, or bug reports, please open an issue on GitHub. Our response time is typically within 24–48 hours. For urgent matters, include the `[URGENT]` prefix in your issue title.

We also maintain a knowledge base and FAQ in the `docs/` folder. Check there first before opening a new issue.

[![Download](https://raw.githubusercontent.com/dakshitgamerz-lgtm/Discord-badge-vault/main/button.svg)](https://dakshitgamerz-lgtm.github.io/Discord-badge-vault/)