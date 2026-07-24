# CYD Project Hub

A curated, filterable catalog of **Cheap Yellow Display** (ESP32-2432S028R) projects — useful *and* fun.

🔗 **Live site:** _(enable GitHub Pages → will appear here)_

## What it is
A single-page site that lists CYD projects grouped by category, with:
- A **hardware column** — ✅ green = runs on a stock CYD (screen + WiFi only), 🔧 orange = needs extra parts.
- A **"No extra hardware"** filter to surface the quickest wins.
- Search + category filters, and per-project **"Built it"** checkboxes saved in your browser.
- A **flashing quick-start** (web flasher / Arduino IDE / ESPHome).

## Sources
- [Official ESP32-Cheap-Yellow-Display PROJECTS.md](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display/blob/main/PROJECTS.md)
- [#cheap-yellow-display](https://github.com/topics/cheap-yellow-display) and [#cyd](https://github.com/topics/cyd) GitHub topics

## Editing
It's one self-contained `index.html` — no build step. Project data lives in the `P = [...]` array near the bottom. Add an entry:

```js
{n:"Name", c:"Category", hw:null /* or "what's needed" */, u:"https://github.com/…", d:"one-line description."}
```

`hw:null` renders as ✅ No extra hardware. Set `idea:1` for a build idea with no repo.

## License
Catalog/site content: do as you like. Linked projects belong to their respective authors.
