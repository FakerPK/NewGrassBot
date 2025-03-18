# ⚠️ **DISCLAIMER** ⚠️  
## **Important:** 
### To prevent unauthorized distribution and theft of this script, **please join my exclusive Telegram group to obtain the latest version and updates, It's all free. Click on the Telegram Icon to join my group:**  
<p align="center">
<a href="https://t.me/+rurxli5cagplMjM8"><img width="120px" alt="Telegram" src="https://img.icons8.com/fluency/96/0088CC/telegram-app.png"/></a>


# LATEST: Grass Community Node Bot 1.25x Earnings, Multiple Accounts 🚀

Automate Grass Node mining with this Python based script for VPS, managing multiple devices and IP addresses to ensure 24/7 uptime and maximize earnings. Perfect for those seeking a seamless and efficient way to handle WebSocket connections through the SOCKS5 Protocol.

![AGPL License](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)

---

## Features ✨

- **Season 2 Boost & 1.25x Earnings:** Enjoy enhanced earnings with the latest Season 2 update!
- **WebSocket Connection via SOCKS Proxies:** Securely connect using the SOCKS5 protocol.
- **Multiple User IDs:** Manage several Get Grass accounts simultaneously with multiple proxies.
- **High Earning Potential:** Each proxy (≈ 3000 $GRASS Points per day) maximizes your daily earnings.
- **Cost Efficiency:** As per Stage 1 Airdrop data, 1M Grass Points roughly equals 45 GRASS tokens (Bonus Epooch not included).
- **Data Usage Efficiency:** Approximately 2 GB of proxy data yields 1M points, meaning ~$6 spent on proxies produces around 45 GRASS tokens.
- **Robust Error Handling:** The script automatically manages errors such as dead proxies, SSL errors (e.g., WRONG_VERSION_NUMBER), invalid packed IP addresses, empty connect replies, and internal errors (sent 1011 keepalive). Dead proxies are automatically removed from the file.

---

## Get Your User ID 🔍

1. Open [Get Grass Dashboard](https://app.getgrass.io/register/?referralCode=citNrn5sQAg87PE) and log in.
2. Press `F12` (or `Ctrl + Shift + I`) to open the developer console.
3. Enter the following code in the console:
   ```javascript
   localStorage.getItem('userId')
   ```
4. The printed text is your **USER_ID**.

![User ID Screenshot](https://github.com/user-attachments/assets/ef45b21c-4a13-4853-a4b2-9c1b88b2eaae)

---

## Requirements ✅

- **Get Grass Accounts Invitation:**  
  [Sign Up Here](https://app.getgrass.io/register/?referralCode=citNrn5sQAg87PE)
- **Python:**  
  Download from [python.org](https://www.python.org/downloads/) for Windows/Mac or install on Ubuntu:
  ```bash
  sudo apt install python3
  ```
- **VPS Server:**  
  Options include AWS free tier, Google Cloud free tier, or any affordable VPS (~$2-5/month).
- **Proxy Server:**  
  **Important:** Use only ISP Residential Proxies to earn $GRASS tokens; data center or cheap proxies will result in 0% earnings.
- **Recommended Proxy Provider:**  
  Use [Proxies.fo](https://app.proxies.fo/ref/f1353b58-10c4-98a5-d94d-6164e2efcfaf). Purchase the ISP plan (not the residential plan) for optimal performance.

---

## If You Want to Buy Proxies From My Recommended Provider 🔒

1. **Sign Up:**  
   Visit [Proxies.fo](https://app.proxies.fo/ref/f1353b58-10c4-98a5-d94d-6164e2efcfaf) and register.
2. **Go to the ISP Section:**  
   **DO NOT** buy the Residential Plan—only purchase the ISP plan.  
   ![ISP Section](https://github.com/user-attachments/assets/c81fc995-11f9-4448-9355-0065d4286cf2)
3. **Select a Plan:**  
   Choose one of the ISP plans (avoid the Residential Plan).  
   ![Plan Selection](https://github.com/user-attachments/assets/bbd22e0a-22c7-42cf-8608-361d7310e0ae)
4. **Generate SOCKS5 Proxies:**
   ![image](https://github.com/user-attachments/assets/51e6e2a4-cccc-47f7-88cb-65548445fcd4)

   Add the generated proxies to the `proxy.txt` file in the following format:
   ```
   socks5://username:pass@ip:port
   OR
   socks://username:pass@ip:port
   ```

---

## Steps to Run the Code ▶️

Before running the script, ensure you have Python installed and all necessary packages.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/FakerPK/NewGrassBot.git
   ```
2. **Change Directory:**
   ```bash
   cd NewGrassBot
   ```
3. **Install Required Packages:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Enter Your User ID and Proxy Count:**  
   You will be prompted to enter your `UserID` and the number of proxies you wish to use.
5. **Add Your Proxies:**  
   Add your proxies to the `proxy.txt` file. You can add 10,000+ proxies!  
   **Format:**
   ```bash
   socks5://username:pass@ip:port
   OR
   socks://username:pass@ip:port
   ```
7. **Multiple Proxies:**  
   Each IP is estimated to earn ~3000 $GRASS per day.
8. **Run the Script:**
   ```bash
   python3 main.py
   ```
9. **Multiple User IDs:**  
   To run multiple User IDs, add them to the `config.json` file.
   *Format for `config.json`:*
   ```json
   {
    "user_ids": [
        "USER_ID_1",
        "USER_ID_2"
    ]
   }
   ```

---

### NOTE:

Approximately 2GB of proxy data yields about 45 $GRASS tokens (around $90), based on past trends and Stage 1 user data.

Happy mining and good luck maximizing your earnings! 💰🔥

*For further assistance or updates, always refer to our Telegram group.*

---
##  **💸Donations**
If you would like to support me or the development of this projects, you can make a donation using the following addresses:
- **Solana :**
```bash
9SqcZjiUAz9SYBBLwuA9uJG4UzwqC5HNWV2cvXPk3Kro
```
- **EVM :**
```bash
0x2d550c8A47c60A43F8F4908C5d462184A40922Ef
```
- **BTC :**
```bash
bc1qhx7waktcttam9q9nt0ftdguguwg5lzq5hnasmm
```
----
## Support 🆘  
Contact `FakerPK` on:  
<p align="center">
  <a href="https://t.me/+rurxli5cagplMjM8"><img width="60px" alt="Telegram" src="https://img.icons8.com/fluency/96/0088CC/telegram-app.png"/></a>
  <a href="https://discord.gg/mjzgatMCk8"><img width="60px" alt="Discord" src="https://img.icons8.com/fluency/96/FFA500/discord-logo.png"/></a> &#8287;
  <a href="https://medium.com/@FakerPK"><img width="60px" src="https://img.icons8.com/ios-filled/96/F0F0EC/medium-monogram.png" alt="Medium"></a>&#8287;
