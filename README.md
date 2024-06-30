# Eth-Avax-Module2-Project
# Solidity smart contract 
A Solidity smart contract named "Assessment" and a React frontend for interacting with the contract using the MetaMask wallet. The contract allows users to deposit and withdraw funds, check their balance, and perform some more operations. The frontend provides a simple interface for users to interact with the contract functions.
# Description 
## 1. Solidity Smart Contract (Assessment.sol):
This contract embodies the core functionality of a fundamental cryptocurrency wallet. It facilitates the actions of depositing and withdrawing ETH tokens for users. Additionally, individuals have the capability to verify their account balance by linking their Metamask wallet to the application. The interface also enables users to view a record of their transaction history and ascertain the presently active account for these transactions.

## 2.  React Frontend (HomePage.jsx):
* The frontend uses React and MetaMask to interact with the deployed "Assessment" smart contract.
* The user interface displays the connected MetaMask account, the account balance, and the contract owner's name.
* Users can deposit and withdraw 1 ETH from their account using the provided buttons.
* The frontend communicates with the contract using the contract's address and ABI (Application Binary Interface)
## Pre-Requisites

1. You should be proficient in HTML, React, Node, and Solidity.
2. You should have a strong understanding of HTML, React, Node, and Solidity.
3. You should be able to use HTML, React, Node, and Solidity to build web applications.
4. You should be able to understand and implement Solidity smart contracts.

# Execution (Steps to execute):
After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

# Authors 
Jaya Singh
# Video Walkthrough


