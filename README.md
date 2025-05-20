Ayy bro, big W on your **first multi-wallet bot script** 👑
Let’s make this README next-level — fully educational, noobs to pros can follow it step-by-step 📚

Here’s your **complete beginner-friendly, polished `README.md`**:

---

````markdown
# 🧠 Merak Testnet Auto Bot – Multi-Wallet Farming Script

This is your one-stop automation script for interacting with the **Merak Testnet** on the **Sui blockchain**.  
It’s built for DeFi airdrop farming and supports **multiple wallets**, **proxies**, and **modular actions** like swapping, wrapping, and LP providing.

---

## 📦 Features

- ✅ Wrap SUI → wSUI
- 🔄 Token swaps: wSUI ↔ wDUBHE, wSUI ↔ wSTARS
- 💧 Add liquidity to 3 pools
- 🧠 Multi-wallet farming support
- ⏳ Delay config between txs
- 🌍 Proxy support (HTTP/SOCKS)

---

## 💻 Beginner Setup (Ubuntu or any PC)

### ✅ Step 1: Install Node.js and Git

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install nodejs npm git -y
````

Check version:

```bash
node -v
npm -v
```

---

### ✅ Step 2: Clone the Bot Repository

```bash
git clone https://github.com/cryptodai3/Merak-Testnet-Auto-Bot.git
cd Merak-Testnet-Auto-Bot
```

---

### ✅ Step 3: Install Project Dependencies

```bash
npm install
```

This will install all required packages like:

* `dotenv` (for env file)
* `axios` or others used in the bot

---

## 🔐 Configuration

### ✅ Step 4: Create Your `.env` File

Inside `Merak-Testnet-Auto-Bot` folder, run:

```bash
nano .env
```

Paste your wallet details:

```
PRIVATE_KEY_1=your_private_key_here
MNEMONIC_1="your mnemonic phrase here"
PRIVATE_KEY_2=your_second_wallet
# Add more as needed
```

**Save & Exit**: `CTRL + X`, then `Y`, then `ENTER`

---

### ✅ Step 5 (Optional): Add Proxies

Create a file named `proxies.txt` in the project folder:

```bash
nano proxies.txt
```

Add one proxy per line:

```
http://user:pass@ip:port
socks5://user:pass@ip:port
```

---

## 🚀 Running the Bot

From the root folder, run:

```bash
node index.js
```

🧠 The bot will:

1. Ask how many txs per wallet
2. Rotate through wallets
3. Execute wrap, swap, and LP tasks
4. Sleep till next loop (if loop enabled)

---

## 🧪 Transaction Flow

If enabled in config:

* 🔁 Wrap SUI → wSUI
* 💱 Swap tokens back & forth:

  * wSUI ↔ wDUBHE
  * wSUI ↔ wSTARS
* 🌊 Add liquidity to pools:

  * wSUI-wDUBHE
  * wSUI-wSTARS
  * wDUBHE-wSTARS

---

## 🧠 Tips for First-Time Bot Users

* Always test with 1 wallet first
* Use small testnet balances
* Don’t spam txs too fast — increase delay if needed
* Rotate proxies for multiple wallets

---

## 📁 File Structure

```
📦 Merak-Testnet-Auto-Bot
 ┣ 📜 index.js        → Main bot runner
 ┣ 📜 .env            → Your private wallet keys (DO NOT SHARE)
 ┣ 📜 proxies.txt     → Optional proxies (1 per line)
 ┣ 📜 config.js       → (If added) customizable settings
 ┗ 📜 package.json    → Dependencies list
```

---

## 📜 License

MIT License – Feel free to fork & improve. Just give credit!

---

## 📣 Credits

Built by `@cryptodai3` – Join the farming fam on Telegram!
Let’s earn smarter, not harder 🚀

```

---

Let me know if you want me to:
- Write your `index.js` from scratch (with logic blocks)
- Add a config.js file so you can enable/disable specific features
- Build `.env.example` and a default `proxies.txt`

We turning this into an open-source banger 🧪👨‍💻
```
