# 🤖 Velo AI - Telegram Bot

A powerful Telegram bot powered by Google's Gemini AI, offering intelligent conversations and assistance.

[![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-blue?logo=telegram)](https://t.me/VeloAIbot)
[![Node.js](https://img.shields.io/badge/Node.js-v16+-green?logo=node.js)](https://nodejs.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## ✨ Features

- 🧠 Powered by Google's Gemini AI
- 💬 Natural conversation capabilities
- ⚡ Fast response times
- 🔄 Reply mode for seamless chat
- 👥 Multi-admin support
- 🛡️ User blocking system
- ✉️ Message length protection

## 🚀 Try the Bot

You can try the bot right now by messaging [@VeloAIbot](https://t.me/VeloAIbot) on Telegram!

## 🛠️ Development

### Prerequisites

- Node.js 16 or higher
- A Telegram Bot Token
- Google Gemini API Key(s)

### Environment Variables

Create a `.env` file with:

```env
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
GEMINI_API_KEYS=your_gemini_api_key1,your_gemini_api_key2
ADMIN_ID=id1,id2,id3
BLOCKED_USERS=blocked_id1,blocked_id2,blocked_id3
```

### Installation

1. Clone the repository
```bash
git clone https://github.com//afxz/Velo-AI-Telegram-Bot.git
cd velo-ai-bot
```

2. Install dependencies
```bash
npm install
```

3. Start the bot
```bash
npm start
```

For development with auto-reload:
```bash
npm run dev
```

## 🚀 Deployment

The bot can be deployed to any Node.js hosting platform that supports:
- Node.js 16 or higher
- Environment variables
- Long-running processes

## 📝 Commands

- `/start` - Start the bot
- `/ask` - Ask a question
- `/reply` - Toggle reply mode (on/off)

## 🔐 Admin Features

- Multiple admin support through comma-separated IDs in `ADMIN_ID`
- User blocking system through `BLOCKED_USERS` environment variable
- Blocked users are silently ignored by the bot

## 🛡️ Protection Features

- Message length limit to prevent Telegram API errors
- Automatic message splitting for long responses
- Silent blocking of unwanted users

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Support Development

If you find this bot useful, consider supporting its development:
- Star ⭐ this repository
- Share with friends
- [Buy me a coffee](https://superprofile.bio/vp/64188fab190024001f59f638)
