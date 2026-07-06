# BlazeNXT OTP Bot

**BlazeNXT OTP Bot** — Advanced Telegram bot for automatic OTP collection, forwarding, and number management.

## Features

- 🔄 **Multi-Panel Support** — Auto-detects Old, MO, and PS API types
- 🔌 **IVAS WebSocket Support** — Real-time SMS via WebSocket
- 📱 **Custom Emoji Formatting** — Premium Telegram emoji support
- 👑 **Advanced Admin System** — Granular permissions for staff
- 📦 **Number Stock Management** — Country-wise number inventory
- 📊 **Full Statistics & History** — OTP logs, user stats, panel hits
- 🚀 **Async Architecture** — High-performance background workers

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Copy `.env.example` to `.env` and fill in your credentials
4. Run the bot:
   ```bash
   python main.py
   ```

## Configuration

Edit the following in `main.py` or use environment variables:

- `BOT_TOKEN` — Your Telegram bot token
- `OWNER_IDS` — List of owner Telegram user IDs
- Panel tokens and URLs in `DEFAULT_PANELS`

## Number Format

Numbers are now formatted as:
```
+XXX-NXT-XX
```
Example: `+923-NXT-55035`

## Developer

**BlazeNXT** (@firstoget)

---

> ⚠️ **Disclaimer**: This tool is for educational and authorized use only. Misuse may violate laws and Telegram's terms of service.
