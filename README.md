# Telegram Chat Summarizer Bot

A Telegram bot that summarizes chat messages in **Persian** using OpenAI GPT-4.1.

The bot collects messages from a chat and generates a concise summary in **informal Persian**, mentioning opinions and decisions.

---

## Features

- Summarizes recent Telegram chat messages in **Persian**.
- Keeps track of chat history (up to 200 messages per chat).
- Commands supported:
  - `/start` – Show welcome message and usage instructions.
  - `/summarize [count]` – Summarize the last `count` messages (default: 50, max: 200).
  - `/clear` – Clear chat history.
  - `/stats` – Show statistics: total messages, users, and most active user.
- Ignores bot messages automatically.
- Friendly, informal tone without emojis or formatting.

---

## Requirements

- Python 3.10+
- Packages:
```bash
pip install python-telegram-bot==20.5 openai
