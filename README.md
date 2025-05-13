# 🔒 Fake Product Identification using Blockchain

A decentralized application (DApp) that uses blockchain technology to detect fake products via QR code scanning and verification on a local blockchain network.

---

## 🚀 Features
- QR code-based product authentication
- Smart contract-backed validation system
- Local blockchain integration using Ganache
- Real-time product verification through a web interface
- Metamask integration for blockchain account management

---

## 🧰 Tech Stack

- **Blockchain:** Solidity, Ganache, Truffle
- **Frontend:** HTML, CSS, SCSS, JavaScript
- **Libraries:** Web3.js, QRCode.js
- **Development Tools:** Node.js, npm
- **Browser Requirements:** Chrome or any Chromium-based browser with MetaMask extension

---

## 📦 Packages Required

| Package         | Version   |
|----------------|-----------|
| Truffle         | v5.6.7    |
| Ganache         | v7.5.0    |
| Solidity        | v0.5.16 (solc-js) |
| Node.js         | v15.8.0   |
| Web3.js         | v1.7.4    |
| npm             | v7.5.1    |

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
## 🔗 Ganache Setup

1. Open **Ganache** and create a **new workspace**.
2. In the workspace settings:
   - Add the project's `truffle-config.js` file.
   - Set the **server port** to `7545` (must match the port in `truffle-config.js`).
3. Start the workspace to launch your local blockchain.

---

## 🦊 MetaMask Configuration

1. Open **MetaMask** in your Chromium-based browser (e.g., Chrome).
2. Click on the network dropdown and select **"Add Network"**.
3. Enter the following details to connect to the local blockchain:

   - **Network Name:** Localhost 7545  
   - **New RPC URL:** `http://127.0.0.1:8545`  
   - **Chain ID:** `1337`  
   - **Currency Symbol:** ETH  
   - **Network ID:** `5777`

4. Import an account using the **private key** from one of the default accounts shown in **Ganache**.

---

## 📤 Deploy Smart Contracts

With Ganache running and MetaMask connected to the local network:

```bash
truffle migrate
