The bot is written in Python 3.10.
To run the bot, you additionally need to install the following libraries: Requests, pyTelegramBotAPI, python-telegram-bot-calendar, python-dotenv, loguru.
The bot uses the rapidapi.com API.
For working with the database, sqlite3 is used.

The bot consists of the following files:
1. «config.py» – contains configuration settings such as the API key, the Telegram bot token, and other settings.
2. «data_base.py» - contains functions for working with the database.
3. «commands.py», «history.py» - modules responsible for executing the bot’s main commands.
4. «keyboard.py» - module responsible for creating keyboards.
5. «main.py» - the main module. Contains procedures for analyzing user responses and displaying results in the chat.
6. «search_dest_id.py», «search_hostels.py», «search_photos.py» - modules for working with the API.
7. «user_data.db» - the database file.

To launch the bot, you need Python 3.10 installed, as well as a .env file where you must store your RAPIDAPI_KEY and your bot’s token.

Version 1.61
