# FreeGPT4Bot

FreeGPT4Bot is a Telegram bot that provides free access to GPT-4 using the g4f library. This bot allows users to interact with GPT-4 directly from Telegram.

## Features

- Free access to GPT-4.
- Simple and intuitive interface.
- Easy to deploy and customize.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/FreeGPT4Bot.git
    cd FreeGPT4Bot
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file and add your Telegram bot token:

    ```plaintext
    TELEGRAM_TOKEN=your_telegram_bot_token
    ```

## Usage

1. Run the bot:

    ```bash
    python bot.py
    ```

2. Open Telegram and start a chat with your bot.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute.

## Disclaimer

This bot uses the g4f library, which provides unofficial access to GPT-4. Use it at your own risk. The repository owner is not responsible for any consequences resulting from the use of this bot.

## Acknowledgments

- [g4f library](https://github.com/yourusername/g4f) for providing free access to GPT-4.
- [Aiogram](https://github.com/aiogram/aiogram) for the Telegram bot framework.