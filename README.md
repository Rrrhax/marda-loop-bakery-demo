# Marda Loop Bakery Demo

Telegram Mini App + Flask backend for bakery orders.

## Deploy

1. `python3 bakery_webapp_fixed.py` (port 5000)
2. ngrok http 5000 → WEBAPP_URL
3. `TELEGRAM_TOKEN=... python3 bakery_bot_fixed.py`

GitHub Pages: https://Rrrhax.github.io/marda-loop-bakery-demo/

## Files
- `bakery_index.html`: Frontend
- `bakery_webapp_fixed.py`: Flask API/server
- `bakery_bot_fixed.py`: Telegram bot
- `menu.json`: Editable menu