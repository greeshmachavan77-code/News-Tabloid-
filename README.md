# 📰 The Daily Scoop

A tabloid-styled news reader built as a single self-contained HTML file. Pick a category (or search a topic) and it pulls live headlines from [GNews.io](https://gnews.io), styled up like a scrappy newsroom front page — scrolling breaking-news ticker, rubber-stamp tags, and torn-clipping story cards.

![status](https://img.shields.io/badge/status-personal%20project-lightgrey)

## Features

- Live headlines via the GNews API
- Category browsing: Top Stories, World, Business, Tech, Entertainment, Sports, Science, Health
- Free-text search across headlines
- Scrolling "breaking news" ticker built from the current results
- No build step, no dependencies — just one HTML file

## Getting started

1. Clone this repo
2. Open `daily-scoop.html` directly in your browser

That's it — no server, no npm install, nothing to build.

## API key

This project talks to GNews directly from the browser using an API key embedded in `daily-scoop.html` (look for the `API_KEY` constant near the top of the `<script>` block).

⚠️ **Heads up:** because the key lives in plain sight in the file, anyone with access to this code — or this repo, if it's public — can see and use it. That's fine for a personal, local-only project like this one. If you ever want to:

- **make this repo public** → swap in a fresh key first (get one free at [gnews.io](https://gnews.io)), since it'll be visible in your commit history
- **publish the website itself** → don't embed the key in the frontend at all; put it behind a small serverless proxy (e.g. a Cloudflare Worker) that holds the key server-side instead

## Project structure

```
.
├── daily-scoop.html   # everything — markup, styles, and script in one file
└── README.md
```


- Free-tier GNews accounts have a daily request limit — if headlines stop loading, you may have hit it for the day.
- Built for personal use / experimentation, not production deployment.
- 
