# Spider-Murph

Hobby developer on Windows. I build bots and automation for things I actually use: prediction-market trading, a mobile game, a Discord server, my own PC. Python and PowerShell, Playwright for anything that needs a browser, Claude Code as a daily tool.

Most of my repos are private. Here's what's in them.

## Projects

| Project | What it is | Stack |
|---|---|---|
| **MSF Sidekick** | Local-first assistant for Marvel Strike Force: daily chores, a screen-reading vision engine, a counters knowledge base, and advice that refuses when it isn't sure. Runs entirely on one machine. | Python, FastAPI, Playwright, Tesseract |
| **PokeBreaker** | Discord bot that gives real-time Pokémon card price estimates (raw and PSA 9/10) for live streams and breaks. | Python, discord.py |
| **kalshi-crypto-killer** | Bot for Kalshi 15-minute crypto prediction markets: conviction-scored entries, multi-asset, live dashboard. Built on a friend's original. | Python |
| **polycopy** | Polymarket wallet tracker and copy-trader: finds consistently winning wallets, tracks them, mirrors their trades. US-legal by design. | Python |
| **pc-toolkit** | Small Windows utilities: a UPS power-loss watchdog and a weekly app updater. | PowerShell |
| **claude-code-mods** | Hooks, slash commands, skills, plugins, MCP servers and status lines for Claude Code. In progress; this one will be public. | |

## How I work

- Paper-trade first, real money later, kill switches on everything.
- Secrets live in `.env` and never in a repo. Every push goes through gitleaks.
- Specs before code. Mistakes get logged so they don't repeat.
