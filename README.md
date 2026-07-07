# 🎒 Task Bar Hero Helper

**The all-in-one companion for _TBH: Task Bar Hero_** — your stash value, live Steam Market prices, and a full optimization coach, all read straight from your save. No login, no typing, nothing written to your game.

<p align="center">
  <a href="../../releases/latest"><b>⬇ Download the latest version</b></a>
  &nbsp;·&nbsp;
  <a href="https://tanpaulus.github.io/task-bar-hero-helper-releases/"><b>📖 Full feature guide</b></a>
</p>

---

## ✨ What it does

Open it beside the game and it reads your save automatically — no login, no typing. Everything below is computed locally on your PC.

**💰 Market & selling** — turn your stash into money on the Steam Market
| | |
|---|---|
| 💰 | **My items sell desk** — your whole stash valued and ranked, list price vs instant-sell side by side, with a Instant / List / Hold recommendation per item. |
| 🏷 | **Sell advisor** — your Steam listing slots (listed / free / locked), a one-tap dismantle-for-gold tip for loose items, and your gear ranked by in-game NPC sell value (a reminder that the Steam Market usually pays far more). |
| 📊 | **Browse market** — search live Steam prices, sort by grade/level/category, with Listings, buy Orders and units Sold-24h columns. |
| 🏷 | **Suggested listing price** — undercuts the cheapest listing without dropping below the best buy order (public order book, no login). |
| 🎚 | **Sell-now score & tags** — a 0–100 "good time to sell" score plus Undervalued/Fair/Overpriced, Verified/Estimated confidence, and volume pace. |
| 📈 | **Price history sparkline** — a tiny price-over-time chart parsed from Steam's own public history graph. |
| 🔎 | **Deep Scan** — an order-book scan that suggests undercut/ask prices for each item (with per-item timeouts so it never hangs). |
| 📋 | **Sell Assist** — click a price chip to open the item on Steam and copy the price to paste; a "Copy sell list" export and a local listed-checklist to tick off what you've listed. |
| 🔔 | **Watchlist alerts** — star any item with a target (drops-to / rises-to) and get pinged in-app (and via desktop notification) when the price crosses it. |
| 🛒 | **Afford-X planner** — "when can I afford this?" for both a gold goal (gap + ETA to farm it) and a Steam buy funded by selling stash items. |
| ⬆ | **Upgrade Finder** — the gear on sale right now that would raise a fielded hero's POWER the most, ranked by value, one click to its listing. Advisory only. |

**🧠 Optimization coach** — one screen that tells you what to do next
| | |
|---|---|
| 🎯 | **Overview** — your single best next move, an "also worth doing" to-do list, and party DPS / POWER / gold / stage at a glance. |
| 👋 | **Return Briefing** — reopen after a break and get a recap: gold waiting to claim, chests that overflowed, and your deltas since last visit. |
| 💡 | **Insight strip** — up to three blunt cards: gold left on the table, active-vs-idle, and your next level-up ETA, each jumping to the right tab. |

**📈 Progression planners** — spend gold, gear and time in the best order
| | |
|---|---|
| ⛏ | **Farm optimizer** — every stage ranked by gold/hr & exp/hr, calibrated from your real recorded runs, with a stay-vs-switch verdict. |
| 🆙 | **Leveling planner** — your lowest hero focused first, XP-rate ETAs to each next level and milestone, plus an ability-point spend coach. |
| 🛡 | **Gear comparator** — equipped vs best-in-bag with the exact POWER gain per swap, and a count of free upgrades sitting in your bag. |
| ⚔ | **Heroes hub** — push-readiness (EHP vs incoming DPS), per-hero stat sheets & DPS breakdown, carry-concentration, and equipped-gear market value. |
| ❖ | **Rune tree** — all 197 nodes mapped, a "spend your gold now" cart, and every rune ranked by power-per-gold. |
| 🐾 | **Pets** — the best pet for gold/EXP/drops and the next one to unlock (which monster to beat, at which stage, or which DLC). |
| 🎁 | **Loot finder** — the best stages to farm for gear you don't own yet, plus a chase-by-slot table with per-box drop chances. |
| 🛍 | **Shop / build planner** — gear-synthesis (fuse-to-upgrade) picks and a materials table showing what each grants and how many you own. |

**⏱ Activity** — timers and your real run history
| | |
|---|---|
| ⏳ | **Idle timer** — progress toward the offline-reward cap and the best stage to park at. |
| 📦 | **Chest planner** — auto-open cooldowns and capacity per tier, a best-stage-to-fill plan, and a yield tracker across your runs. |
| 📜 | **Runs history** — every cleared run (stage, team, clear time, DPS, gold, EXP, drops, deaths) grouped into sessions; refresh & reset. |
| 📊 | **History** — your POWER, gold **and stash value (net worth)** charted over time, plus a 7-day change on your stash value. |

**📚 Reference** — live game data from the wiki
| | |
|---|---|
| 🐉 | **Codex / Bestiary** — searchable monsters (element, HP/attack/gold/EXP) and stages (waves, boss, gold & EXP per clear). |
| 🔨 | **Crafting** — Craft / Extract / Synthesize / Cube recipes, save-aware "can craft now" filtering, and a missing-materials shopping list. |
| 📰 | **Updates** — game News (Steam official) and Patch Notes (SteamDB build feed), with a "new" badge when there's unseen content. |

**🖥 In-game overlays** _(opt-in, off by default, Electron desktop app only)_
| | |
|---|---|
| 💲 | **Price HUD** — a transparent price card beside the item you hover in-game: instant-sell, suggested list, deal tag, sparkline, sell-now score. |
| ⚡ | **Live DPS overlay** — always-on-top stage/DPS/damage/gold/EXP with a live time-to-level bar; also logs your runs. |

> Both overlays read the game's memory **read-only** (no writes, no injection, no network) and download a small verified reader component on first enable.

**🔧 Convenience**
| | |
|---|---|
| 🔄 | **Auto-updates itself** — new versions download in the background with a one-click Restart-now / Later prompt. |
| ♻ | **Refresh & auto-refresh** — one-click re-read of your save/engine/runs, plus a 30s–10min interval that pauses while hidden. |
| 🔔 | **Desktop notifications** — opt-in toasts for level-ups, almost-affordable runes, a freed market slot, a full idle cap, and marketable-drop alerts. |
| 💱 | **Multi-currency** — prices in your auto-detected Steam currency (41 supported), switchable in Settings. |
| 🌐 | **16 languages** — item/hero/pet/rune names localize from the wiki; UI fully translated for English & Bahasa Indonesia. |
| 🎨 | **Light / dark theme** and a **global show/hide hotkey** to summon or hide the window from inside the game. |

> Built specifically for **TBH: Task Bar Hero** — it finds and reads your save automatically.

---

## ⬇ Install (2 minutes)

1. **[Download the latest version](../../releases/latest)** — grab **`Task-Bar-Hero-Helper-Setup-x.x.x.exe`**.
2. Run it. Windows may show **"Windows protected your PC"** — that's the normal warning for any free app that isn't code-signed, **not** a problem with this app. Click **"More info" → "Run anyway"**.
3. Done! It opens in its own window, finds your stash automatically, and **updates itself**.

> 💡 Use the **`Setup`** installer (not the `portable` `.exe`) so auto-update works.
>
> 🕹️ First time? Open TBH at least once so the game creates its save, then launch the app.

---

## ✅ Is it safe?

**Yes.** This app **only READS** files already on your computer — like opening a file in Notepad.

- ✅ Reads a **copy** of your save (in memory) to compute value and advice.
- ✅ Uses the same public price data the Steam website uses.
- ❌ Does **not** modify your save or touch the game while it runs.
- ❌ Does **not** automate buying or selling.
- ❌ Does **not** send your data anywhere — it runs **100% on your PC**.

It never changes your save and never automates anything in the game. The optional in-game overlays use a **read-only** memory reader (no writes, no injection, no network) that is **off by default**; all pricing comes from **anonymous public** Steam Market pages and never touches your Steam login.

> ⚠️ Independent project — not affiliated with Valve or the TBH developers.

---

## 🆘 Quick help

| Problem | Fix |
|---|---|
| **"TBH save not found"** | Open the TBH game once (so it creates the save), then click **Refresh**. |
| Item shows **"no listing"** | Normal — no active **sell** listing right now. Click **💸 View buy orders** for an instant buyer. |
| Windows blocked the install | **"More info" → "Run anyway"** — the standard unsigned-app prompt. |

---

## ℹ️ About

- 🔄 **Auto-update:** the installed app checks here on startup and applies new versions automatically.
- 🔒 **Source code is private.** Only the built Windows installers are published in this repo.
- 🧠 The optimization engine is adapted from [shigake/tbh-copilot](https://github.com/shigake/tbh-copilot) (MIT).
- 📄 **License:** MIT.

Made by **Tan Paulus**. If it helps you, a ⭐ on the release is appreciated!
