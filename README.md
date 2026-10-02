# 💰 Offline Budget Tracker

An **offline-first personal budget tracker** in a single HTML file: record income and expenses, organize them by categories, set bill reminders, and export your data — with everything stored locally in your browser. **No server, no login, no build step.**

## ✨ Features

- **Transaction tracking** — add, edit, and delete income/expense entries with dates, categories, and notes.
- **Category management** — custom income/expense categories with colors.
- **Dashboard** — running balance, monthly totals, and category breakdowns.
- **Filters** — filter transactions by date range and category.
- **Bill reminders** — create and edit reminders for upcoming payments.
- **CSV export / backup & restore** — export transactions to CSV; back up your full data set to a file and restore it later.
- **Fully offline** — single self-contained HTML file with an embedded PWA manifest; all data lives in browser localStorage.
- **No dependencies** — zero libraries, zero build step.

## 🛠️ Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Browser localStorage for persistence
- Data-URI-embedded PWA web app manifest

## 🚀 Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/girishlade111/Offline-Budget-Tracker1.git
   cd Offline-Budget-Tracker1
   ```
2. Open `index.html` (or `offline-budget-tracker.html`) in any modern browser — no server needed.
3. Add categories, log transactions, and track your budget. Use **Backup data** periodically to save a JSON snapshot of your records.

> All data stays in your browser's localStorage. Clearing browser data erases it — keep backups via the export feature.

## 📁 Project Structure

| File | Purpose |
|---|---|
| `index.html` | App entry point (same as `offline-budget-tracker.html`) |
| `offline-budget-tracker.html` | The complete standalone budget tracker app |
| `README.md` | This file |
| `LICENSE` | MIT License |

## 🌐 Live Demo

Hosted on GitHub Pages: https://girishlade111.github.io/Offline-Budget-Tracker1/

## 👤 Author

*Built by Girish Lade — [ladestack.in](https://ladestack.in)*

## 📄 License

MIT — see [LICENSE](LICENSE).
