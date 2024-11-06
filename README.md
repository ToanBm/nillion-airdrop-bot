# Nillion Airdrop Bot
- [Faucet](https://faucet.testnet.nillion.com/)
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
- Edit file `accounts.json` with your wallet seed key. (Ctrl + X, Y and Enter will do to save)
   ```bash
   nano accounts.json
   ```
Example:
```json
[
  "abc def ghi jkl mno pqr stu vwx yz"
]
```

- Edit file `privateKeys.json` with your wallet seed key. (Ctrl + X, Y and Enter will do to save)
   ```bash
   nano privateKeys.json
   ```
Example:
```json
[
  "abfrsgrgdgfdgfgfgfsgfgfsgfgdsgsz"
]
```
### 4. Run the bot:
   ```bash
   npm start
   ```
   - Choose the wallet initialization method (0 for mnemonic, 1 for private key).
   - Specify the number of transactions.
   - The bot will dynamically sleep between 30 to 60 seconds between transactions if more than one transaction is specified.

## ............ Thank you!..............

