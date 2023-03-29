Decentralized Storage Project
This is a decentralized storage project. The project allows users to store and retrieve data on a decentralized network, making it more secure and resistant to censorship.

Installation
To install the project, follow these steps:

Clone the repository to your local machine
Navigate to the project directory and run npm install to install all the necessary dependencies.
Usage
To use the project, follow these steps:

Start a local blockchain network using Hardhat. Run npx hardhat node to start a local network and npx hardhat deploy to deploy the smart contract to the local network.
Interact with the smart contract using the provided functions. For example, you can use the addFile function to store data on the network and the retrieveData function to retrieve data from the network.
Smart Contract
The smart contract is written in Solidity and is responsible for storing and retrieving data on the decentralized network. It uses IPFS to store the actual data, and the smart contract only stores the IPFS hash.

Tests
To run the tests, follow these steps:

Start a local blockchain network using Hardhat. Run npx hardhat node to start a local network.
Run the tests using npx hardhat test.﻿