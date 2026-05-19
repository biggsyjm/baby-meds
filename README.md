# 💊 Baby Medicine Tracker

A lightweight, offline-first web app for tracking baby medication doses and temperature readings. Runs entirely in the browser with no server, no account, no dependencies. Data stays on your device via localStorage.

## Features

- **Dose logging** — Record medicine, dosage amount, date/time, and auto-schedule the next dose
- **Regimen support** — Set up multi-day medication courses (e.g., 2× daily for 10 days) with progress tracking
- **Temperature tracking** — Log temps with color-coded status: 🟢 Normal (under 99.4°F), 🟡 Elevated (99.4–100.3°F), 🔴 Fever (100.4°F+)
- **Today dashboard** — At-a-glance view of doses given today, temps taken today, active regimens, and next dose due
- **Unified history** — Chronological timeline of all doses and temperature readings
- **Dark/light mode** — Toggle between themes; preference persists across sessions
- **Fully offline** — No internet required after initial page load. All data stored in browser localStorage.

## Pre-configured medications

| Medicine | Default Dose | Interval |
|----------|-------------|----------|
| Children's Tylenol | 3.75 mL | Every 6 hours |
| Children's Motrin | 3.75 mL | Every 6 hours |
| Other (custom) | — | Configurable |

Dosages are based on pediatrician guidance for our baby's weight. Adjust as needed for yours.

## Setup

This is a single HTML file. No build step, no dependencies, no framework.

### Run locally
Open `index.html` in any browser.

### Host on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under "Source," select **Deploy from a branch**
4. Choose `main` branch, `/ (root)` folder
5. Click Save
6. Your app will be live at `https://<your-username>.github.io/<repo-name>/`

### Add to iPhone home screen
1. Open the GitHub Pages URL in **Safari**
2. Tap the **Share** button (square with arrow)
3. Tap **Add to Home Screen**
4. Name it whatever you want
5. It opens full-screen like a native app

## Data & Privacy

All data is stored in your browser's localStorage. Nothing is sent to any server. If you clear your browser data, the history will be lost. This is intentional — no accounts, no cloud, no tracking.

## Tech

One self-contained HTML file. Vanilla JavaScript. CSS custom properties for theming. No external dependencies of any kind.

## License

MIT — do whatever you want with it.
