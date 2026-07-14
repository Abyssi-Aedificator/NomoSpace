# NomoSpace

A sleek, glassmorphism drive and game space tracker.

## Features

- **Drive Management** — Add, edit, and monitor drives (NVMe, SSD, HDD, External) with animated SVG donut charts showing usage
- **Game Library** — Track installed and uninstalled games with search and filter
- **Ranking** — View games grouped by drive, sorted largest to smallest
- **Bento Grid Dashboard** — Overview with live stats, drive breakdowns, and recent activity
- **Dropbox Sync** — Sync your data across devices via your own Dropbox account (OAuth2 PKCE, no backend)
- **Emotionally Intelligent Theme** — Accent color shifts based on time of day (morning, afternoon, evening, night)
- **Glassmorphism 2.0** — Animated gradient mesh background, frosted glass panels, micro-interactions
- **Hyper-Personalization** — Remembers your last tab, tracks recent activity
- **Data Management** — Export/Import JSON, localStorage persistence
- **Single File** — Entire app in one HTML file, zero dependencies
- **PWA Support** — Installable as a Progressive Web App with offline caching via Service Worker

## Getting Started

Open `index.html` in any modern browser. No server required.

To install as a PWA: serve the files over HTTPS (or localhost) and click "Install" in the browser's address bar.

## Dropbox Sync

1. Create a free app at [Dropbox Developer Console](https://www.dropbox.com/developers/apps)
2. Set the redirect URI to your local file path (e.g. `file:///C:/path/to/index.html`)
3. Enter the App key in Settings → Dropbox Sync → Connect

For testing, type `mock` as the App key to simulate a connected state.

## Tech Stack

- Vanilla HTML/CSS/JS (single file, no build step)
- localStorage for persistence
- Dropbox API (OAuth2 PKCE) for cloud sync
- Service Worker for offline PWA support
