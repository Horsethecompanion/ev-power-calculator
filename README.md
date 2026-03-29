# ⚡ EV Power Cost Calculator

Calculate how much your EV is actually costing you to charge, based on your real half-hourly power usage data.

**Live version:** [evpowcalculator.vercel.app](https://evpowcalculator.vercel.app)

## How It Works

1. Export your half-hourly power data from your NZ electricity retailer as a CSV
2. Upload it to the calculator
3. Set your plan's rates (flat, day/night, time-of-use, or free hours)
4. See exactly what your EV is costing you — including supply charges and the EA levy

## Supported Retailers & Formats

Tested with:
- **Meridian** — standard ICPCONS export format

Should work with any retailer that provides:
- A timestamp column (date + time per reading)
- A kWh consumption column
- Half-hourly (or similar) intervals

If your retailer's CSV has a different column layout, [let me know](https://www.youtube.com/@ev-tim) and I'll add support.

## Features

- **All NZ plan types**: Flat, Day/Night, Time-of-Use, Free Hours
- **Daily supply charge**: configurable per day, week, or month
- **EA Levy**: separate line item, fractional ¢/kWh supported
- **Plan comparison**: save one result and compare two plans side-by-side
- **Works offline**: runs entirely in the browser, no server needed

## For Developers

Single HTML file — no build step, no dependencies to install.
Drop it on any static host (Vercel, Netlify, GitHub Pages, anything).

```bash
# Just open it
open index.html
```

## Credits

Made by [EV Tim](https://www.youtube.com/@ev-tim) — the Christchurch Kiwis EV channel.
