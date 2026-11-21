# Mini Apps

Small apps, one tap each — hosted on GitHub Pages at
https://new-meta-monkey.github.io/mini-apps/

## Apps

| App | Folder | What it does |
| --- | --- | --- |
| Wonder Kids GK | `wonder-kids-gk/` | Kids' general knowledge: flip-card learning + Challenge quiz, 11 topics, Supabase leaderboard |
| SleepPulse | `sleep-pulse/` | One-click sleep tracker: log bedtime and wake-up, weekly chart, private local storage |
| ShopPulse | `shop-pulse/` | Offline shop manager: POS billing, stock, sales, expenses, customers, reports, multi-shop |

Each app is its own installable PWA (own `manifest.json` + `sw.js`, scoped to its
folder), so it installs separately on a phone with its own icon and works offline.

## Adding a new mini app

1. Add a folder, e.g. `my-new-app/`, with its own `index.html`, `manifest.json`
   (relative `scope`/`start_url`), `sw.js` and icon.
2. Add a card for it on the dashboard `index.html` and in the table above.
3. Push to `main` — GitHub Pages serves it automatically.
