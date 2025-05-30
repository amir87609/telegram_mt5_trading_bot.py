# Telegram MT5 Trading Bot

A Python Telegram bot for live trading and analysis using MetaTrader 5 (MT5).  
It provides real market data, allows manual and automated trading, and includes advanced indicator settings—all via Telegram.

## Features

- **Login/Logout**: Securely connect/disconnect your MT5 account.
- **Real Analysis**: Uses real-time MT5 data, not simulated data.
- **Trading Panel**: Place trades, set trade amounts, and view summaries.
- **Auto-Trading**: Enable auto-trading with advanced indicator settings.
- **Indicators**: Choose from SMA, RSI, MACD, Bollinger Bands, and more.
- **Balance Check**: Instantly view your account balance.
- **Arabic Language**: All bot messages and UI are in Arabic.

## Setup

### 1. Requirements

- Python 3.8+
- A Telegram Bot Token ([Get one here](https://t.me/BotFather))
- MetaTrader 5 installed on a Windows machine (for MT5 integration to work)
- A demo or real MT5 account (from a broker like Exness, IC Markets, XM, etc.)

### 2. Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
pip install -r requirements.txt
```

### 3. Configuration

- Replace `"توكن-بوت-تيليجرام"` in your Python file with your actual Telegram bot token.

### 4. Running the Bot

```bash
python telegram_mt5_trading_bot.py
```

**Note:**  
The MT5 library works only on Windows. If you want to deploy online, use a Windows VPS for full functionality.

## Usage

- Start the bot on Telegram and follow on-screen instructions.
- Use the login button to enter your MT5 account info (login, password, server).
- After login, access trading and analysis features from the main menu.
- Use the auto-trading menu to enable advanced strategies and indicator settings.

## Security

- Never share your account credentials.
- Use demo accounts for testing.
- Keep your bot token and login info safe.

## Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License
