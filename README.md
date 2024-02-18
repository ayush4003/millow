# Real Estate NFT DApp

## Problem Statement
Traditional property transactions often lack transparency and security, leading to issues such as fraud, disputes, and unequal bargaining power between parties. Buyers may worry about transferring funds without assurance of receiving the property title, while sellers may be concerned about not receiving payment after transferring ownership.

## Solution
To address these challenges, we're developing a decentralized application (DApp) using Web3 technologies. Our DApp leverages blockchain's immutability, transparency, and smart contract functionality to create a secure and efficient platform for property transactions.

## Escrow Implementation
One of the key features of our DApp is the integration of an escrow service. Escrow acts as a trusted intermediary, holding funds or assets in a secure manner until predefined conditions are met. Here's how we're incorporating escrow to ensure fairness in property deals:

1. Secure Fund Handling
Buyers deposit funds into the escrow smart contract, which holds them until both parties fulfill their obligations. This eliminates the risk of fraudulent transactions or default by either party.

2. Conditional Release
The escrow smart contract releases funds to the seller only after predefined conditions, such as title transfer confirmation or property inspection, are met. This ensures that both parties fulfill their obligations before the transaction is finalized.

3. Dispute Resolution
In case of disputes, the escrow smart contract provides a mechanism for arbitration or resolution. This could involve third-party mediation or predefined dispute resolution terms coded into the smart contract.

4. Transparency and Accountability
All transaction details, including fund movements and condition fulfillment, are recorded on the blockchain, ensuring transparency and accountability for all parties involved.


## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`


Properties listed 
![prop2](https://github.com/ayush4003/millow/assets/158837482/961aa8ba-81fb-46f5-8a00-943b5d549af9)
