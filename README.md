# Birthday Count Down 🎂

A single-page birthday countdown and celebration web app.

## Overview

This project shows a live countdown to the next birthday date, then switches into a celebration scene with effects like fireworks, confetti, balloons, birthday music, and interactive cake candles.

## Features

- Live countdown (days / hours / minutes / seconds)
- Birthday date and name settings panel
- Local persistence using `localStorage`
- Shareable URL parameters:
  - `?date=MMDD` (example: `?date=0314`)
  - `?name=YourName`
- Celebration mode with:
  - Fireworks and confetti effects
  - Balloon animation
  - Interactive cake and candle blowing
  - Generated birthday song (Web Audio API)

## Project Structure

- `/home/runner/work/Birthday-count-down/Birthday-count-down/Birthday count down(生日倒數慶祝網頁).html` – main app file (HTML/CSS/JS in one file)
- `/home/runner/work/Birthday-count-down/Birthday-count-down/README.md` – project documentation

## How to Run

1. Open `Birthday count down(生日倒數慶祝網頁).html` in a modern browser.
2. Click **⚙️** to set the name and birthday date.
3. (Optional) Use query parameters to preview/share specific settings.

No build step or external backend is required.