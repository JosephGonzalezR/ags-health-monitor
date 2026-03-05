# AGS Health Monitor

External health monitor for Academic Global Solution bots.
Runs on GitHub Actions every 5 minutes and sends Telegram alerts if any bot is down.

## Monitored Services

| Bot | URL |
|-----|-----|
| Tareapp (Chile) | https://tareapp.ags-ed.com/health |
| EducaProject (Peru) | https://webhook.ags-ed.com/health |
| Trabajos Helper (Argentina) | https://helper.ags-ed.com/health |

## Setup

Secrets required in GitHub repo settings:
- `TELEGRAM_BOT_TOKEN`
- `TELEGRAM_CHAT_ID`
