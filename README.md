<h1>FundMe - A Decentralized Crowdfunding Smart Contract 🚀</h1>

Welcome to FundMe, a smart contract project built using Hardhat that enables decentralized crowdfunding on the Ethereum blockchain. This project allows users to contribute funds and enables the contract owner to withdraw them securely.

📌 Project Overview

The FundMe smart contract is designed to:
✅ Allow users to donate funds in ETH.
✅ Store all contributions securely on the blockchain.
✅ Allow only the contract owner (deployer) to withdraw funds.
✅ Use Chainlink Oracles to fetch real-world ETH/USD price data.

⚡ Tech Stack & Tools

This project is built with:

Solidity (0.8.x) – Smart contract programming language
Hardhat – Ethereum development framework
Chainlink Oracles – For real-time ETH/USD price conversion
Ethers.js – Interacting with Ethereum blockchain
Mocha & Chai – For smart contract testing
Gas Reporter – To track gas consumption
Hardhat Deploy – Automating deployment scripts
🚀 Getting Started

Follow these steps to set up and deploy the FundMe smart contract locally.

1️⃣ Clone the Repository

git clone https://github.com/yourusername/FundMe-Hardhat.git
cd FundMe-Hardhat

2️⃣ Install Dependencies

yarn install

3️⃣ Configure Environment Variables

Create a .env file in the root directory and add:

SEPOLIA_RPC_URL=your_alchemy_or_infura_url
PRIVATE_KEY=your_private_key
ETHERSCAN_API_KEY=your_etherscan_api_key
COINMARKETCAP_API_KEY=your_coinmarketcap_api_key

⚙️ Compiling & Deploying the Contract
🔹 Compile the Smart Contract

yarn hardhat compile

🔹 Deploy to a Local Hardhat Network

yarn hardhat deploy

🔹 Deploy to Sepolia Testnet

yarn hardhat deploy --network sepolia

✅ Running Tests

yarn hardhat test

🔍 Verifying the Contract on Etherscan

yarn hardhat verify --network sepolia DEPLOYED_CONTRACT_ADDRESS
