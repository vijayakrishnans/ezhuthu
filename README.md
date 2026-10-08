# Ezhuthu

A Qidian-style web novel platform prototype. It is a single static page with no build step.

## Features
- Discover page with featured books, editors' picks, recent updates and power ranking
- Browse by genre and status, rankings (power stones, readers, rating, length), search
- Reader with Page/Sepia/Night modes, font size, contents drawer, arrow-key paging
- Paragraph comments
- Coins: free early chapters, paid chapter unlock, auto-unlock, 20% off unlock-all, daily check-in, demo top-ups
- Library with saved reading progress
- Author studio: create books and publish chapters

## Run
Open `index.html` in a browser, or serve the folder with any static host.

## Current limits
All state (coins, library, comments, user books) lives in the browser's localStorage. Payments are simulated. There are no accounts and no backend.
