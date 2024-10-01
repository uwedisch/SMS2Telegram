# SMS2Telegram

Barebone background service that forwards your incoming new SMS (text message) into a chat via Telegram Bot API.
This program does not connect to any intermediate server, it simply issues a new request to Bot API each time the phone gets a new SMS.


## Supported System

Currently tested on

1. Oneplus 5T on Android 10 (dual SIM)
2. Oneplus 7t on Android 11 (dual SIM)
3. Pixel 3 on Android 11
4. Pixel 7a on Android 14 (dual SIM)


## Configuration

You'll need (1) a Telegram bot token and (2) the Telegram chat ID to which you want the bot to forward.
You should be able to follow https://dev.to/rizkyrajitha/get-notifications-with-telegram-bot-537l to obtain your bot token and chat ID.

You'll also want to turn off battery optimisation for this App to avoid it being killed by the system.


## Download

See artifact of Android CI workflow: https://github.com/uwedisch/SMS2Telegram/actions/workflows/android.yml
