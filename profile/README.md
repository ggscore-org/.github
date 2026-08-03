# GGScore — CS2 Match Data API

**Free / paid REST API** for Counter-Strike 2 **played match results** and **upcoming fixtures** — JSON over HTTPS, `X-API-Key` auth. Build Discord bots, Telegram bots, trackers, and dashboards **without scraping** scoreboard HTML.

| | |
|--|--|
| **Website** | [ggscore.net](https://ggscore.net) |
| **API docs** | [ggscore.net/docs](https://ggscore.net/docs) |
| **Get API key** | [Sign up · Free tier](https://ggscore.net) |
| **Base URL** | `https://api.ggscore.net` |

## Why this org exists

Developers search for **CS2 API**, **CS2 match data**, **Discord bot CS2 scores**, **Telegram CS2 schedule**, and **HLTV scrape alternatives**. These public repos are minimal, MIT-licensed examples that call the live GGScore endpoints:

- `GET /api/v2/matches` — finished CS2 matches  
- `GET /api/v2/upcoming_matches` — scheduled fixtures  

## Public repositories

| Repo | What it does |
|------|----------------|
| [**discord-cs2-bot**](https://github.com/ggscore-org/discord-cs2-bot) | Discord.js slash command `/results` — recent CS2 scores via GGScore |
| [**telegram-cs2-bot**](https://github.com/ggscore-org/telegram-cs2-bot) | Python bot `/results` + `/schedule` — played + upcoming CS2 matches |

```bash
# Same auth for every example
export CS2_MATCH_API_KEY="your-key-from-ggscore-cabinet"
export CS2_MATCH_API_BASE="https://api.ggscore.net"   # default
```

## Quickstart (curl)

```bash
curl -sS -H "X-API-Key: $CS2_MATCH_API_KEY" \
  "https://api.ggscore.net/api/v2/matches?page=1&limit=5"
```

More languages (Node, Python, Go, …): [API documentation](https://ggscore.net/docs).  
Guides: [CS2 Match Data API](https://ggscore.net/guides/cs2-match-data-api) · [Discord bot walkthrough](https://ggscore.net/blog/cs2-discord-bot-api-guide).

## Keywords

`CS2 API` · `Counter-Strike 2 match data` · `esports REST API` · `CS2 Discord bot` · `CS2 Telegram bot` · `match results JSON` · `upcoming CS2 fixtures` · `no scraping`

## Private platform

Product source for ggscore.net (`web` + `api`) is **private** in this organization (`platform`). Public repos above are examples only.
