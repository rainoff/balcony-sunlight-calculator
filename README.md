# 把一年的陽光，放進陽台裡。 / A year of sunlight, inside your balcony.

Event submission: a single-file balcony sunlight calculator for Taipei (25.04 N, 121.51 E, UTC+8, year 2026).

One aquarium-style graphic shows a full year of estimated direct-sun hours for a chosen pot position (back chart), the selected day's 12×12 floor heatmap (front floor), and a movable pot. A right-hand panel gives one plant verdict, today's hours against the plant's known reference minimum, and a "try a brighter spot" comparison. Chinese by default with an English toggle.

## What it estimates

- **Simplified direct-sun estimate only.** Sun position uses the NOAA solar position equations at 5-minute midpoints; a point is "lit" when the ray clears the parapet, awning, closed side walls and one parallel building across the street. No reflected or diffuse light, cloud cover or weather.
- Plant thresholds (full sun 6 h, part sun 3 h) are this tool's reference definitions. Shade-tolerant plants have an unknown minimum and are reported as "direct sun alone is insufficient". Meeting a light reference is not a cultivation guarantee.
- A built-in self-check (sunrise/sunset, solar-noon elevation, geometry cases, season lengths, conversions) runs on load and is shown at the bottom of the page.

## How to open

- Live site: served from this repository's `main` branch via GitHub Pages (see the repository's Pages URL).
- Locally: download `index.html` and open it directly in a browser. No build step, packages, server or fonts are required.
- Plant photos are loaded by URL from Wikimedia Commons only for the currently selected plant. Open the page with `?NO_REMOTE` appended to the URL to never request images and show a same-size fallback instead. Photo credits and licences are in the in-app "Data & sources" dialog.
