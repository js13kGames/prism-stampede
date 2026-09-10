# js13k2026-prism-stampede
Game submitted for JS13K 2026 contest

# 🌈 Prism Stampede 🦄

Prism Stampede is a colorful arcade-puzzle game where a cloud-riding unicorn must free trapped Cloudlings before the storm reaches the danger line. Aim magical Sparks through numbered prisms, build the correct color route, rescue Lost Unicorns, and overcome powerful Guardians across 15 handcrafted levels.

Unlike a traditional block-breaking game, every shot is also a routing decision. Sparks begin white and gain color as they pass through prisms, so the angle, order, and color of a shot matter as much as the target it hits.

## ✨ Features

- 15 levels across three increasingly challenging chapters
- Ricochet shooting controlled by mouse, touch, or keyboard
- Numbered Prism Routes that trigger powerful bursts
- Six Spark colors with colorblind-friendly shape glyphs
- Sealed Cloudlings that require matching colors
- Lost Unicorn rescues and descent-freezing Rescue Shields
- Starbursts, reinforcement waves, and Storm Guardians
- Three-star scoring with 45 stars to collect
- Procedural music and sound effects made with Web Audio
- Responsive desktop, phone, and tablet controls

## 🎯 How to Play

### Objective

Destroy every required Cloudling and Guardian before one crosses the danger line. Levels marked as rescue missions also require every Lost Unicorn to be saved.

### Game Elements

- **Unicorn** — Your cloud-riding hero and Spark launcher
- **Sparks** — White projectiles that gain color from prisms
- **Prisms** — Numbered diamonds that form the active route
- **Cloudlings** — Colored blocks freed by reducing their HP to zero
- **Sealed Cloudlings** — Armored blocks damaged by matching colors
- **Lost Unicorns** — Rescue targets that provide protection from descent
- **Starbursts** — Collectibles that cause area damage
- **Guardians** — Large enemies with special defenses
- **Danger Line** — The boundary enemies must not cross

### Rules

- Aim and fire one volley per turn
- Touch the numbered prisms in order to complete a Prism Route
- Matching Spark and Cloudling colors causes stronger damage
- The first three unique prisms collected add Sparks to later volleys
- Surviving formations descend as turns progress
- A Rescue Shield cancels one formation descent
- Clearing all required targets completes the level

## 🎮 Controls

### Mouse and Touch

- **Drag and release** — Aim and fire
- **FIRE** — Fire at the current angle
- **FAST** — Speed up an active volley

### Keyboard

- **Left/Right Arrow** or **A/D** — Adjust aim
- **Space** or **Enter** — Fire
- **F** — Toggle fast-forward
- **R** — Restart the level
- **H** or **?** — Open help
- **M** — Toggle music
- **S** — Toggle sound effects

## ⭐ Scoring

Each level awards up to three stars:

- ⭐ Complete the level
- ⭐⭐ Finish within the target turn count
- ⭐⭐⭐ Complete the level's mastery objective

The mastery objective usually requires completing a Prism Route. Earn all 45 stars to master every Cloud Route.

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in a modern browser
3. Select an unlocked level and start playing

No installation, server, external library, or build process is required.

## 🛠️ Technical Details

- Vanilla JavaScript
- HTML5 Canvas 2D rendering
- Fixed-step gameplay simulation
- Procedural Web Audio music and effects
- Local browser storage for progress and settings
- No external runtime dependencies

The readable game is separated into three files:

- `index.html` — Page structure and controls
- `styles.css` — Responsive layout and button presentation
- `game.js` — Levels, gameplay, audio, input, and rendering

## 🧩 Level Design

All 15 levels are defined in the `LV` array near the beginning of `game.js`. A level can configure its title, target turns, starting Sparks, danger line, prism route, Cloudlings, reinforcement waves, rescue targets, Starbursts, sealed blocks, and Guardian rules.


