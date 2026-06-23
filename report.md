Telegram Chatbot using Telegram Bot API
Objective

This project implements a Telegram chatbot using the Telegram Bot API. The bot supports the following commands:

/start – Sends a welcome message.
/help – Displays available commands.
/echo <message> – Returns the user's message.
Technologies Used
Python 3
Telegram Bot API
python-telegram-bot library
Installation
pip install python-telegram-bot
Creating a Telegram Bot
Open Telegram.
Search for BotFather.
Create a new bot using /newbot.
Copy the generated API token.
Replace:
TOKEN = "YOUR_BOT_TOKEN"

with your actual token.

Running the Bot
python bot.py
Available Commands
Command	Description
/start	Welcome message
/help	List of commands
/echo <message>	Echoes the message
Example
User: /echo Hello
Bot: Hello
Deployment

The bot can be deployed on:

Render
Railway
Heroku
Author

Kummari Giribabu
