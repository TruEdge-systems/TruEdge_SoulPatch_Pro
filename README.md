# 🌀 TruEdge Apex Engine™

> A modular trading system that fuses volatility tier overlays, recursive wave mapping, and IBD-style breakout geometry into a fully synchronized signal engine.

![LegacyDrop](https://img.shields.io/badge/LegacyDrop-v1.0-purple?style=for-the-badge)
![Platform](https://img.shields.io/badge/Built%20for-Thinkorswim-blue?style=for-the-badge)
![WaveSync](https://img.shields.io/badge/Wave_Sync-Enabled-green?style=for-the-badge)

---

## 📦 Module Overview

| Module                  | Purpose                                                   |
|--------------------------|------------------------------------------------------------|
| `TI_VBH_MultiTickerUnifiedSTUDY.ts` | Hour-aware volatility tiers for 10 tickers × 2 modes      |
| `ZigZagRecursive.ts`     | Detects pivot swings + tracks phase-aware wave sequences   |
| `IBD_PatternEngine.ts`   | Detects base patterns (e.g. cup with handle)                |
| `TruEdgeApexLauncher.ts` | Combines overlays + gates entry when all modules align     |
| `TI_ApexWatchlistColumn.ts` | Displays signal readiness across watchlist tickers        |

---

## 🚀 Getting Started

1. 📁 Clone or download the full `TruEdgeApexSuite/` folder
2. Open Thinkorswim → Charts → Studies → “Create”
3. Paste contents of each `.ts` file into its own named study
4. Add `TruEdgeApexLauncher.ts` to your chart
5. (Optional) Add `TI_ApexWatchlistColumn.ts` to your watchlist columns

---

## 🎯 Signal Fires Only When:

✔️ Time-based **bias tier** is active (VBH zones)  
✔️ Valid **wave phase** is in play (≥ Phase 3 and upward swing)  
✔️ Confirmed **IBD-style pattern** geometry is detected

This ensures intentional entries—no cloud until all systems align.

---

## 🎼 Inspired By...

- 📊 VolatilityBox-style matrix logic  
- 🎷 Elliott Wave symmetry and rhythm  
- 🧱 Modular coding ethics for remixability and clarity  
- 🧭 A desire to make market structure feel musical and navigable

---

## 🛠 Developer Notes

- Full matrix supports 10 tickers × 2 bias modes × 7 hours = 140 tier conditions
- All modules can be extended separately: try divergence overlays or volume filters
- Watchlist column enables scalable signal tracking across sectors

---

## 🧪 File Map

![TruEdge Architecture Map](docs/truedge_suite_map.svg)
# TruEdge_SoulPatch_Pro# TruEdge_SoulPack_Pro 🎷
_An expressive expansion for the TruEdge Pro™ Visual Suite_

## Overview
This submodule infuses the Suite with rhythm-aware overlays and soulful visual accents. Perfect for users seeking expressive feedback and emotionally resonant tier dynamics.

## Features
- 🎨 Soul-infused visual cues synced with tier overlays
- 🔄 Modular import with no external dependencies
- ⚡ Lag-minimized, real-time performance tuning
- 🎛️ Theme compatibility with toggle controls

## Setup
```thinkscript
// Import into ThinkOrSwim > Studies > Edit Studies > Import
// File: TruEdge_SoulPack_Pro.ts

---

### 📘 Notion Version (Narrative & Visual)

**📀 TruEdge_SoulPack_Pro**  
*Part of the TruEdge Pro™ Visual Suite v1.0_LegacyDrop*

> “A groove within the system—made to be seen, not just analyzed.”

**What It Is:**  
A visual theme module that adds tone, tempo, and tier-aware overlays to the base Visual Suite. Think of it like layering a vinyl crackle over digital audio—adding depth, warmth, and feeling.

**Why Use It:**  
- Brings attention to rhythm shifts, peak-tier swings, and crossover moments  
- Enhances your trading suite with visual soul and thematic cohesion  
- Optimized to *look good and feel good* even in high-volatility playback  

**How to Install:**  
1. Make sure your base Visual Suite is installed and active.  
2. Drag or import the `.ts` file into your ThinkOrSwim editor.  
3. Style it via your Theme Control Panel—toggle opacity, animation rate, etc.

**Future Enhancements:**  
We’re exploring "SoulMap™" visuals, adaptive tempo layers, and harmonic sync options.

---

Want to round it out with a branded logo caption or icon summary next? I’m vibing with this whole aesthetic.
