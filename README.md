# Discord Question Answering Bot

This bot is designed to answer questions in a Discord server by using advanced language models. The bot receives a question, retrieves relevant documents from a stored document set, and generates a suitable response using the OpenAI language model.

## Setup

1. Clone the repository and navigate to its directory in your terminal.
2. Install the required packages with `pip install -r requirements.txt`.

## Environment Variables

Before starting the bot, make sure to set the following environment variables:

- `DISCORD_TOKEN`: Your Discord bot token. You can get this from the [Discord Developer Portal](https://discord.com/developers/applications).
- `OPENAI_API_KEY`: Your OpenAI API key. You can get it here [OpenAI Plattform](https://platform.openai.com/account/api-keys)

## Starting the Bot

To start the bot, simply run `python bot.py` in your terminal.

## Usage

After inviting the bot to your Discord server, you can ask it a question with the command `!question <your question here>`. For example:

```
!question What is the Python language?
```

The bot will process your question, retrieve relevant documents, and generate a suitable response using the OpenAI language model.
