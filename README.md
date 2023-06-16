<h1 align="center">Welcome to Binance Future Order Notifier(PYTHON) via Telegram👋</h1>
<h2>Binance order notification when order created, cancelled or filled etc.. With this repo you will receive telegram notification for your binance future order status.</h2>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/PiyushDixit96/binance-spot-order-notification/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/PiyushDixit_" target="_blank">
    <img alt="Twitter: PiyushDixit_" src="https://img.shields.io/twitter/follow/PiyushDixit_.svg?style=social" />
  </a>
</p>

> This repo sends TELEGRAM ALERTS for BINANCE ORDER STATUS like CREATED, PARTIALLY FILLED, FILLED, CANCELLED, PENDING CANCEL, REJECTED, EXPIRED etc.



<h4>SETUP TELEGRAM BOT</h4>

1. Create account on Telegram (skip if you have)
2. Create Telegram Bot Goto [Bot help](https://core.telegram.org/bots#3-how-do-i-create-a-bot) follow steps at the END Copy **TOKEN**
3. Open created Bot and click **START**
4. Goto [@getuseridbot](https://t.me/getuseridbot) and click **START** and copy **NUMERIC VALUE** this is your **CHAT ID**

<h4>SETUP BINANCE ACCOUNT</h4>

1. [Signup](https://www.binance.com/en/register?ref=35219097) for Binance (skip if you have)
2. Enable Two-factor Authentication (skip if you're done already)
3. Go API Center, [Create New](https://www.binance.com/en/my/settings/api-management?ref=35219097) Api Key and follow steps and at the END, SET API restrictions to  **ENABLE READING ** only
4. **Copy API Key and Secret Key** save and Notepad for later use


------------
### Run Locally
- Download and install python
- Download Repo and open Repo root folder.
- Create .env in root folder and copy , paste below code
 ```sh
BINANCE_API_KEY="your binance api key"
BINANCE_SECRET_KEY="your binance api secret"
TELEGRAM_TOKEN="your telegram token"
TELEGRAM_CHAT_ID="your telegram chat id"
```
- Edit required fields in .env file and save
- Open terminal on current folder 
- Run this command to install `python future.py`

## Original Author

👤 **Piyush Dixit**

* Twitter: [@PiyushDixit\_](https://twitter.com/PiyushDixit_)
* Github: [@PiyushDixit96](https://github.com/PiyushDixit96)
* Telegram: [@Killer_PD](https://t.me/Killer_PD)

