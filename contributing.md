# 🤖 Telegram Emoji Reaction Bot

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=3,22,29&height=210&section=header&text=Telegram%20Emoji%20Reaction%20Bot&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=React%20Smarter.%%20Engage%20More.&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.6.0-2D6A4F?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Python](https://img.shields.io/badge/Python-3.11+-40916C?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-52B788?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Emojis](https://img.shields.io/badge/emojis-200%2B-74C69D?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.org)

<br/>

### ✨ A smart Telegram bot that adds automatic emoji reactions to messages

*🎯 Auto-React • 🧠 Context-Aware • 🎨 Custom Sets • ⚡ Lightning Fast*

<br/>

<a href="https://share.google/yGkQzrd1eetx7UDIe">
  <img src="https://img.shields.io/badge/🤖_ADD_TO_TELEGRAM-2D6A4F?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1B4332" alt="Add to Telegram" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/yGkQzrd1eetx7UDIe">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-40916C?style=for-the-badge&logo=rocket&logoColor=white&labelColor=2D6A4F" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/yGkQzrd1eetx7UDIe">
  <img src="https://img.shields.io/badge/📚_DOCS-52B788?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=3A855F" alt="Docs" height="45"/>
</a>

</div>

<img width="1440" height="1020" alt="file" src="https://github.com/user-attachments/assets/e09ca9e5-5bde-4b21-bce3-e2e8bcbe2959" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Telegram Emoji Reaction Bot** is a lightweight, configurable bot that automatically adds **emoji reactions** to messages in your Telegram groups and channels. Whether you want to welcome new members with a 👋, celebrate good news with 🎉, or just add personality to every conversation — this bot does it intelligently.

Built on the official **Telegram Bot API**, it supports custom reaction rules, keyword triggers, and context-aware emoji selection.

> 💡 **Perfect for:** Community groups, fan channels, support chats, or any Telegram space that deserves more personality.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎯 **Auto-React** | 🧠 **Smart Triggers** | 🎨 **Custom Sets** |
|:---:|:---:|:---:|
| Instantly react to<br/>every new message | Keyword, regex<br/>& context-based | Upload your own<br/>emoji collections |

| 🔀 **Random Mode** | 👥 **Per-Chat Config** | ⚡ **Fast & Light** |
|:---:|:---:|:---:|
| Pick emojis from a set<br/>for natural variety | Different rules for<br/>each group or channel | Async Python, handles<br/>thousands of messages |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Bot

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⚡ **Blazing Fast** | Built on `python-telegram-bot` async — reacts in milliseconds |
| 🧠 **Context-Aware** | Detects sentiment and keywords to pick the perfect emoji |
| 🎛️ **Fully Configurable** | YAML config for rules, per-chat overrides, blacklists, and rate limits |
| 🎨 **200+ Emojis** | Full Telegram reaction set ready to use, plus custom emoji support |
| 🛡️ **Safe & Moderated** | Rate limiting, admin-only commands, and opt-out per chat |
| 🌍 **Multi-Language** | Bot messages in 20+ languages out of the box |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Bot in Action

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🤖  Telegram Emoji Reaction Bot  v2.6.0         ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  👤 Alice:  "Just launched my new project! 🎉"   ║
║  🤖 Bot reacted:  🎉  🔥  👏                     ║
║                                                  ║
║  👤 Bob:    "Good morning everyone ☀️"           ║
║  🤖 Bot reacted:  ☀️  😊  👋                     ║
║                                                  ║
║  👤 Carol:  "This is amazing news!"              ║
║  🤖 Bot reacted:  ❤️  🔥  ✨                     ║
║                                                  ║
║  ⚡ Latency: 12ms   🎯 Accuracy: 96%             ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🤖 telegram-emoji-reaction-bot/
├── 🎯 src/
│   ├── bot/                   # Main bot logic
│   │   ├── handlers.py
│   │   ├── reactions.py
│   │   └── commands.py
│   ├── rules/                 # Trigger rules
│   │   ├── keywords.yaml
│   │   └── sentiment.py
│   ├── storage/               # Chat configs & state
│   └── utils/                 # Helpers & rate limits
├── 🎨 emojis/                 # Emoji packs & sets
├── ⚙️  config.yaml             # Bot configuration
├── 🧪 tests/                  # Unit & integration tests
└── 📖 docs/                   # Setup & usage guides
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-2D6A4F?style=for-the-badge&logo=python&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want a new emoji rule? Have a feature idea?

<div align="center">

<a href="https://share.google/yGkQzrd1eetx7UDIe">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/yGkQzrd1eetx7UDIe">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-2D6A4F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/yGkQzrd1eetx7UDIe">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-52B788?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🤖 Made with ✨ by the Emoji Reaction Team

*If this bot made your chat more fun — drop a star!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=3,22,29&height=120&section=footer" width="100%"/>

</div>
