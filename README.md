# Power Cost Calculator

Calculate how much you're actually paying for electricity, based on your detailed half-hourly power usage data.

**Live version:** [horsethecompanion.github.io/ev-power-calculator](https://horsethecompanion.github.io/ev-power-calculator)

## How It Works

1. Export your half-hourly power data from your electricity retailer as a CSV
2. Upload it to the calculator
3. Set your plan's rates (flat, day/night, time-of-use, or free hours)
4. See exactly what you've been paying — including supply charges and the EA levy

## Supported Retailers & Formats

Works with any NZ retailer that provides:
- A timestamp column (date + time per reading)
- A kWh consumption column
- Half-hourly (or similar) intervals

Known to work with:
- **Meridian** — standard ICPCONS export format

If your retailer's CSV has a different layout, [let me know](https://www.youtube.com/@ev-tim) and I can add support.

## Features

- **All NZ plan types**: Flat, Day/Night, Time-of-Use, Free Hours
- **Daily supply charge**: configurable per day, week, or month
- **EA Levy**: separate line item, fractional ¢/kWh supported
- **Plan comparison**: save one result and compare two plans side-by-side
- **Light / dark mode**
- **Works offline**: runs entirely in the browser — no server needed

## Credits

Made by [EV Tim](https://www.youtube.com/@ev-tim) — the NZ EV channel.
