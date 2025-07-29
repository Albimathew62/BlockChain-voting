
# 🗳️ Ethereum Blockchain Voting System

This is a decentralized voting application built with **Ethereum smart contracts**. It allows secure, transparent, and tamper-proof voting using the Ethereum blockchain. Users interact with the application via a frontend integrated with **MetaMask**, while local blockchain testing is done using **Ganache** and **Truffle**.

---

## 🚀 Features

- Ethereum-based voting using smart contracts
- One vote per registered Ethereum address
- MetaMask integration for user authentication and transactions
- Local blockchain network using Ganache
- Admin can add candidates and start/stop the election
- Real-time voting results

---

## 🧰 Tech Stack

- **Smart Contracts:** Solidity
- **Development Framework:** Truffle
- **Blockchain Network:** Ganache (local Ethereum)
- **Frontend:** HTML, CSS, JavaScript, Web3.js
- **Wallet:** MetaMask

---

## 📁 Project Structure

```

dVoting/
├── client/               # Frontend HTML/CSS/JS
├── contracts/            # Solidity smart contracts
│   └── Voting.sol
├── migrations/           # Truffle deployment scripts
├── truffle-config.js     # Truffle configuration
└── README.md

````

---

## 🛠️ Getting Started

### 1. 📦 Install Prerequisites

- [Node.js](https://nodejs.org/)
- [Truffle](https://trufflesuite.com/)
- [Ganache](https://trufflesuite.com/ganache/)
- [MetaMask](https://metamask.io/)

### 2. 🚀 Clone & Setup

```bash
git clone https://github.com/Albimathew62/BlockChain-voting.git
cd BlockChain-voting/dVoting
npm install
````

### 3. 🔧 Start Ganache

* Open Ganache GUI or run:

  ```bash
  ganache
  ```

* Copy the RPC URL (usually [http://127.0.0.1:7545](http://127.0.0.1:7545))

### 4. 📜 Compile & Deploy Contracts

```bash
truffle compile
truffle migrate --network development
```

> Make sure `development` network in `truffle-config.js` points to your Ganache RPC and port.

### 5. 🌐 Start the Frontend

```bash
cd client
npx live-server
```

Then visit `http://127.0.0.1:8080` (or as shown) and connect MetaMask to **Localhost 7545**.

---


---

## 🔮 Future Improvements

* Deploy to Ethereum Testnet (Sepolia, Goerli)
* Add IPFS to store candidate data/images
* Voter registration with KYC integration
* Result analytics dashboard
* Admin panel with dashboard

---

## 👨‍💻 Author

**Albi Mathew**
[GitHub](https://github.com/albimathew62) · [Portfolio](https://albimathew62.github.io/portfolio/) · [LinkedIn](https://in.linkedin.com/in/albi-mathew-183a5720b)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

```
