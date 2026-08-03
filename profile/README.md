# GGScore

**CS2 Match Data API** — structured JSON for played and upcoming Counter-Strike 2 matches.

| | |
|--|--|
| Product | [ggscore.net](https://ggscore.net) |
| Docs | [ggscore.net/docs](https://ggscore.net/docs) |
| Get API key | [ggscore.net](https://ggscore.net) (Free tier to prototype) |

## Public examples

Minimal bots that call the GGScore REST API (`X-API-Key`):

- **[discord-cs2-bot](https://github.com/ggscore-org/discord-cs2-bot)** — Discord `/results`
- **[telegram-cs2-bot](https://github.com/ggscore-org/telegram-cs2-bot)** — Telegram `/results` + `/schedule`

Point `CS2_MATCH_API_BASE` at `https://api.ggscore.net` (default) and set `CS2_MATCH_API_KEY` from the cabinet.

## Platform

Product source (`web` / `api`) lives in **private** repositories in this organization.
