# ▶ Install & safety

## Install (2 minutes)

1. **[Download the latest version](https://github.com/tanpaulus/task-bar-hero-helper-releases/releases/latest)** — grab **`Task-Bar-Hero-Helper-Setup-x.x.x.exe`**.
2. Run it. Windows may show **"Windows protected your PC"** — that's the normal warning for any free app that isn't code-signed, **not** a problem with this app. Click **"More info" → "Run anyway"**.
3. Done! It opens in its own window, finds your stash automatically, and **updates itself**.

!!! tip
    Use the **`Setup`** installer (not the `portable` `.exe`) so auto-update works. First time? Open TBH at least once so the game creates its save, then launch the app.

## Is it safe?

**Yes.** This app **only READS** files already on your computer — like opening a file in Notepad.

- ✅ Reads a **copy** of your save (in memory) to compute value and advice.
- ✅ Uses the same public price data the Steam website uses.
- ❌ Does **not** modify your save or touch the game while it runs.
- ❌ Does **not** automate buying or selling.
- ❌ Does **not** send your data anywhere — it runs **100% on your PC**.

The optional [in-game overlays](overlays.md) use a **read-only** memory reader (no writes, no injection, no network) that is **off by default**; all pricing comes from **anonymous public** Steam Market pages and never touches your Steam login.

!!! warning "Independent project"
    Not affiliated with Valve or the TBH developers. Use at your own risk.

## Convenience

| | |
|---|---|
| 🔄 **Auto-updates itself** | New versions download in the background with a one-click Restart-now / Later prompt. |
| ♻ **Refresh & auto-refresh** | One-click re-read of your save / engine / runs, plus a 30s–10min interval that pauses while hidden. |
| 🔔 **Desktop notifications** | Opt-in toasts for level-ups, almost-affordable runes, a freed market slot, a full idle cap, and marketable-drop alerts. |
| 💱 **Multi-currency** | Prices in your auto-detected Steam currency (**41 supported**), switchable in Settings. |
| 🌐 **16 languages** | Item / hero / pet / rune names localize from the wiki; UI fully translated for English & Bahasa Indonesia. |
| 🎨 **Light / dark theme** | Plus a **global show/hide hotkey** to summon or hide the window from inside the game. |

## Quick help

| Problem | Fix |
|---|---|
| **"TBH save not found"** | Open the TBH game once (so it creates the save), then click **Refresh**. |
| Item shows **"no listing"** | Normal — no active **sell** listing right now. Click **💸 View buy orders** for an instant buyer. |
| Windows blocked the install | **"More info" → "Run anyway"** — the standard unsigned-app prompt. |

Still stuck? [Open an issue](https://github.com/tanpaulus/task-bar-hero-helper-releases/issues) — the app's **📋 Diagnostics** button copies safe text (no raw save, no personal data) to paste in.
