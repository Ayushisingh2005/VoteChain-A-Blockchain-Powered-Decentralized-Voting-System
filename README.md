🗳️ VoteChain – A Blockchain-Powered Decentralized Voting System

VoteChain is a secure, transparent, and decentralized voting system built using blockchain technology. It ensures tamper-proof elections by recording votes on an immutable distributed ledger, eliminating fraud and increasing trust in the voting process.

🚀 Features

Decentralized and transparent voting

Ethereum smart contract–based system

Immutable and tamper-proof vote storage

One-voter-one-vote enforcement

Real-time vote verification

MetaMask wallet integration

Modern responsive UI with Tailwind CSS

🧰 Tech Stack

Blockchain: Ethereum

Smart Contracts: Solidity

Framework: Hardhat

Frontend: React + Vite

Styling: Tailwind CSS

Web3 Library: ethers.js

Runtime: Node.js

Wallet: MetaMask

📁 Project Directory Structure
VoteChain-A-Blockchain-Powered-Decentralized-Voting-System/
│
├── cache/
├── contracts/
│   └── Voting.sol
│
├── node_modules/
├── public/
│
├── scripts/
│   └── deploy.js
│
├── src/
│   ├── components/
│   ├── App.jsx
│   └── main.jsx
│
├── .env
├── .gitignore
├── bun.lockb
├── components.json
├── DEPLOYMENT.md
├── eslint.config.js
├── hardhat.config.js
├── index.html
├── LICENSE
├── package.json
├── package-lock.json
├── postcss.config.js
├── QUICKSTART.md
├── README.md
├── tailwind.config.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts

⚙️ Prerequisites
🖥️ Terminal (bash)

"""
node -v
npm -v
"""

Install Node.js (v18+)

Install MetaMask browser extension

Basic knowledge of blockchain & Ethereum

📦 Installation
1️⃣ Clone the Repository
🖥️ Terminal (bash)

"""
git clone https://github.com/your-username/VoteChain-A-Blockchain-Powered-Decentralized-Voting-System.git

cd VoteChain-A-Blockchain-Powered-Decentralized-Voting-System
"""

2️⃣ Install Dependencies
🖥️ Terminal (bash)

"""
npm install
"""

⛓️ Blockchain Setup (Hardhat)
3️⃣ Start Local Blockchain
🖥️ Terminal (bash)

"""
npx hardhat node
"""

4️⃣ Compile Smart Contracts
🖥️ Terminal (bash)

"""
npx hardhat compile
"""

🚀 Deploy Smart Contract
🖥️ Terminal (bash)

"""
npx hardhat run scripts/deploy.js --network localhost
"""

📌 Copy the contract address shown in the terminal and use it in your frontend (ethers.js configuration).

🧪 Run Smart Contract Tests
🖥️ Terminal (bash)

"""
npx hardhat test
"""

🌐 Run Frontend Application
🖥️ Terminal (bash)

"""
npm run dev
"""

Open in browser:

http://localhost:5173

🦊 MetaMask Configuration (Localhost)

Add a new network in MetaMask:

Network Name: Hardhat Local
RPC URL: http://127.0.0.1:8545
Chain ID: 31337
Currency Symbol: ETH


Import any private key displayed in the Hardhat node terminal.

📜 Smart Contract Functionalities

Register voters

Register candidates

Cast votes securely

Prevent double voting

Count votes transparently

Display election results

📌 Future Enhancements

Zero-Knowledge Proof (ZKP) voting

Biometric voter authentication

IPFS integration for voter data

Mobile application support

DAO-based election governance

📄 License
MIT License

👩‍💻 Author

Ayushi Singh

⭐ Support

If you like this project, don’t forget to ⭐ the repository on GitHub!


