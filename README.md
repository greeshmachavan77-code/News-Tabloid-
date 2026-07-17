# 📰 The Daily Scoop

A tabloid-styled news reader built with plain HTML, CSS, and JavaScript. Pick a category (or search a topic) and it pulls live headlines from [GNews.io](https://gnews.io) into a newspaper-clipping layout, complete with a scrolling breaking-news ticker and rubber-stamp category tags.

![style: tabloid newspaper](https://img.shields.io/badge/style-tabloid%20newspaper-c62b1f)
![stack: HTML/CSS/JS](https://img.shields.io/badge/stack-HTML%2FCSS%2FJS-2c4a6b)

## Features

- Live headlines from GNews, sorted into categories: Top Stories, World, Business, Tech, Entertainment, Sports, Science, Health
- Free-text search across all news
- Scrolling ticker tape of the latest headlines
- No build step, no dependencies — a single `.html` file

## Getting started

1. **Get a free API key** at [gnews.io](https://gnews.io) (free tier is enough for personal use).
2. **Open `daily-scoop.html`** in a text editor and find this line near the top of the `<script>` section:
   ```js
   const API_KEY = 'YOUR_GNEWS_API_KEY_HERE';
   ```
   Replace it with your own key.
3. **Open the file in a browser** — double-click it, or right-click → Open With → your browser. That's it, no server required.

## Project structure

```
daily-scoop.html   — the entire app (markup, styles, and logic in one file)
```

## ⚠️ A note on the API key

This project calls the GNews API directly from the browser, which means the key lives in plain sight inside the page's source code (anyone with the file can view it). That's fine for a personal project you run locally, but:

- **Don't publish this repo publicly with your real key still in the code** — swap it out for a placeholder (like the one above) before committing, or add the real key back locally after cloning.
- If you ever want to host this as a public website, keep the key server-side instead (e.g. a small serverless function that proxies the request) rather than embedding it in the frontend.

## Customizing

- **Categories** — edit the `CATEGORIES` array in the script to add, remove, or relabel categories.
- **Look and feel** — all colors, fonts, and spacing are CSS variables at the top of the `<style>` block (`--paper`, `--ink`, `--tabloid-red`, `--mustard`, `--faded-blue`).
- **Result count** — change the `max=12` parameter in the `buildUrl()` function to show more or fewer stories per load.

