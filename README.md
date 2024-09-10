# Nillion Airdrop Bot
Nillion Airdrop Bot is a tool for sending Nillion ($NIL) tokens to multiple recipients on the Nillion testnet. This bot is useful for distributing tokens in an airdrop scenario or for testing purposes.
## Usage
### 1. Clone the repository:
   ```bash
   git clone https://github.com/ToanBm/nillion-airdrop-bot.git
   cd nillion-airdrop-bot
   ```
### 2. Install dependencies:
   ```bash
   npm install
   ```
### 3. Prepare `accounts.json`
Edit file `accounts.json` as in the code below. (Ctrl + X, Y and Enter will do to save)
   ```bash
   nano accounts.json
   ```
### 4. Run the bot:
   ```bash
   npm start
   ```
   - Choose the wallet initialization method (0 for mnemonic, 1 for private key).
   - Specify the number of transactions.
   - The bot will dynamically sleep between 30 to 60 seconds between transactions if more than one transaction is specified.

## ............ Thank you!..............

