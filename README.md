# Telegram Bot

Basic Telegram bot converting from EUR to USD and back.

[Tutorial](https://www.html.it/pag/398314/telegrambot-in-python/) (in Italian).

## To start the Bot

1. Download the source code on the machine that is going to be running it.
1. Open Telegram with your account and start the BotFather. It will guide you during the creation of a new Telegram Bot. The BotFather will assign an HTTP API access token that you must save and keep secret.
1. Add the HTTP API token to the `bot_main.py` code in the variable `TOKEN`.
1. Run the code with `python3 bot_main.py`
1. Interact with your bot:
    - if you type `/eur 100`, it will convert 100 EUR to USD;
    - if you type `/usd 100`, it will convert 100 USD to EUR.