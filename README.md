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

- `/home/runner/work/Birthday-count-down/Birthday-count-down/Birthday count down(English version).html` – English app version (HTML/CSS/JS in one file)
- `/home/runner/work/Birthday-count-down/Birthday-count-down/Birthday count down(生日倒數慶祝網頁).html` – Traditional Chinese app version (HTML/CSS/JS in one file)
- `/home/runner/work/Birthday-count-down/Birthday-count-down/README.md` – project documentation

## How to Run

1. Open `index.html` in a modern browser and choose your language.
2. Click **⚙️** to set the name and birthday date.
3. (Optional) Use query parameters to preview/share specific settings.

No build step or external backend is required.

## Host on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your main branch and `/ (root)` folder, then click **Save**.
5. Open the generated `https://<username>.github.io/<repository>/` URL.

`index.html` is included as a language selector page, so visitors can open either the English or Traditional Chinese version on GitHub Pages.