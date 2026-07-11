# 🆕 What's new

Every release, at a glance. The app **updates itself automatically** — you'll get these on the next restart.

[⬇ Download the latest version](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/latest){ .md-button .md-button--primary }
[See all releases on GitHub](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases){ .md-button }

---

## v1.22.1 — Graceful handling when the game updates { #v1-22-1 }
!!! info "2026-07-11"

- 💱 **Groundwork for game build 1.00.27.** TBH updated, and the read-only memory reader can't yet locate the live **stage / EXP / party** on that build (DPS, gold and kills still read). Until a reader update lands, the app now behaves honestly:
    - 📟 The overlay stage shows **—** ("unknown") instead of freezing on a stage you've left.
    - ⛏ The **Farm Optimizer** picks up every stage it can attribute (no longer dropped just because the difficulty label didn't read).
    - 🔎 The reader logs precise self-diagnostics so an unsupported build can be fixed quickly.

[Release notes →](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/tag/v1.22.1)

## v1.22.0 — Compact live DPS overlay { #v1-22-0 }
!!! info "2026-07-08"

- 📟 **The in-game overlay is ~55% shorter** and auto-sizes to its content — a clean two-line layout (stage + big DPS on top, a slim wave bar and stat chips below).
- 📈 **DPS sparkline + trend** ride behind the number, with your session peak on hover.
- 🪙 **Gold/hr** replaces the always-zero EXP stat at max level — a number you can act on.
- ⛏ **Best-stage nudge**, ⏱ **clear ETA**, and a click-to-**collapse** one-line mode.

[Release notes →](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/tag/v1.22.0)

## v1.21.2 — Correct prices for Rupiah / Yen / Dong / Won { #v1-21-2 }
!!! info "2026-07-07"

- 💱 **Fixes prices reading ~100× too low** in zero-decimal currencies (IDR, JPY, VND, KRW). Everything priced off the list — the market table, **equipped-gear value**, stash value, the sell digest, the watchlist and the Afford planner — is now on one correct scale. *Click ↻ Refresh once to re-pull prices.*
- 💰 Equipped-gear value now refreshes as soon as prices update.

[Release notes →](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/tag/v1.21.2)

## v1.21.1 — Farm Optimizer updates live as you play { #v1-21-1 }
!!! info "2026-07-07"

- ⛏ **The Farm Optimizer now refreshes while you play** — it used to lag behind the Runs tab. Recommendations and rates track your latest runs without a manual refresh.
- 📊 **Better estimates when you farm a single stage** — the model anchors to your real clear time, so the ranking is far more realistic.
- 📟 The live DPS overlay's stage/wave indicator holds steady through brief reader gaps.

[Release notes →](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/tag/v1.21.1)

## v1.21.0 — Watchlist, sell-now digest, Afford planner, net-worth { #v1-21-0 }
!!! info "2026-07-07"

- ⭐ **Price watchlist + alerts** — track any item with a target price; get pinged when the live price crosses it.
- 💸 **Afford-X planner** — when/how you can afford a gold or market goal, funded by your sellable stash.
- ✅ **Sell-now digest** — a clear "list these now" vs "hold these" split by sell-now score.
- 💰 **Per-hero equipped-gear value** in Heroes, and 📈 **net-worth (stash value) over time** in History.

[Release notes →](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/tag/v1.21.0)

## v1.20.0 — Runs reset, clearer pet unlocks, refresh polish { #v1-20-0 }
!!! info "2026-07-07"

- 🗑 **Reset Runs data** button in Activity › Runs.
- 🐾 **Clearer pet unlock requirements** in Progressions › Pets (which monster/stage unlocks each pet).
- ↻ Refresh button polish (only the icon spins) and the stash list stays expanded.

[Release notes →](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/tag/v1.20.0)

---

!!! tip "Older versions"
    The full history — every build back to the beginning — is on the [GitHub Releases page](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases).
