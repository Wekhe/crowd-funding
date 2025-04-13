<h1>FundMe - A Decentralized Crowdfunding Smart Contract 🚀</h1>

Welcome to FundMe, a smart contract project built using Hardhat that enables decentralized crowdfunding on the Ethereum blockchain. This project allows users to
contribute funds and enables the contract owner to withdraw them securely.

<h2>📌 Project Overview</h2>

<h3>The FundMe smart contract is designed to:</h3>
✅ Allow users to donate funds in ETH.
✅ Store all contributions securely on the blockchain.
✅ Allow only the contract owner (deployer) to withdraw funds.
✅ Use Chainlink Oracles to fetch real-world ETH/USD price data.

<h2>⚡ Tech Stack & Tools</h2>

<h3>This project is built with:</h3>

Solidity (0.8.x) – Smart contract programming language
Hardhat – Ethereum development framework
Chainlink Oracles – For real-time ETH/USD price conversion
Mocha & Chai – For smart contract testing
Ethers.js – Interacting with Ethereum blockchain
Gas Reporter – To track gas consumption
Hardhat Deploy – Automating deployment scripts
🚀 Getting Started

Follow these steps to set up and deploy the FundMe smart contract locally.

<h2>1️⃣ Clone the Repository</h2>

git clone https://github.com/yourusername/FundMe-Hardhat.git
cd FundMe-Hardhat

<h2>2️⃣ Install Dependencies</h2>

yarn install

<h2>3️⃣ Configure Environment Variables</h2>

<h3>Create a .env file in the root directory and add:</h3>

SEPOLIA_RPC_URL=your_alchemy_or_infura_url
PRIVATE_KEY=your_private_key
ETHERSCAN_API_KEY=your_etherscan_api_key
COINMARKETCAP_API_KEY=your_coinmarketcap_api_key

<h2>⚙️ Compiling & Deploying the Contract</h2>
🔹 Compile the Smart Contract

yarn hardhat compile

🔹 Deploy to a Local Hardhat Network

yarn hardhat deploy

🔹 Deploy to Sepolia Testnet

yarn hardhat deploy --network sepolia

<h2>✅ Running Tests</h2>

yarn hardhat test

<h2>🔍 Verifying the Contract on Etherscan</h2>

yarn hardhat verify --network sepolia DEPLOYED_CONTRACT_ADDRESS




