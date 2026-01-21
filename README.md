# AI Market Screener

An automated market screener that pulls daily data for key assets, calculates levels, generates signals, and sends AI insights to Telegram. All history is saved to Google Sheets — everything in one place.

## Client Value
- Save time: clear, concise signals without manual analysis.
- Single source of truth: market history and insights stored in one sheet.
- Fast notifications: Telegram messages arrive right after calculations.
- Scalable: easy to add new assets and channels.

## What It Does
1. On schedule, fetches quotes for BTC, Gold, NASDAQ, and AAPL.
2. Normalizes data and calculates key levels.
3. Classifies signal: bullish / bearish / neutral.
4. Generates an AI insight (recommendation, risk, confidence, factors).
5. Writes results to Google Sheets and sends to Telegram.
6. Sends automatic error alerts on failures.

## Integrations
- n8n (orchestration)
- Coingecko, Yahoo Finance (data sources)
- OpenAI (AI insights)
- Telegram (notifications)
- Google Sheets (history)

## Screenshots

![Signals and levels](screenshots/Screenshot%20from%202025-12-06%2014-50-07.png)
![AI insights](screenshots/Screenshot%20from%202025-12-06%2014-51-47.png)
![History in Google Sheets](screenshots/Screenshot%20from%202025-12-06%2014-54-56.png)

---

Ready for fast client branding and rollout: schedule, asset list, and message format are easy to customize.
