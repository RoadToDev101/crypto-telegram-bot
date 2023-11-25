# Bitcoin Price Alert Telegram Bot

This is a Telegram bot that sends alerts about the Bitcoin price. It uses the WebSocket API from CoinCap to get real-time price updates.

## Features

- Sends an alert when the Bitcoin price changes by 2% or more.
- Provides the current Bitcoin price on demand.

## Setup

1. Clone this repository.
2. Install the required Python packages: `pip install -r requirements.txt`
3. Set the `TELEGRAM_TOKEN` and `CHAT_ID` environment variables.
4. Run the bot: `python bot.py`

## Usage

- `/btc_price`: Get the current Bitcoin price.
- The bot will automatically send an alert when the Bitcoin price changes by 2% or more.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License.
