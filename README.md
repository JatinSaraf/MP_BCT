# A Decentralized Auction House for Fine Art 
## Description
This repository contains the Soldity, JavaScript, and HTML/CSS code for a Auction Decentralized Application for deployment on the Ethereum blockchain. Some of the deployment code was referenced from the [Ethereum Pet Shop tutorial](https://www.trufflesuite.com/tutorials/pet-shop).

## Instructions for Local Deployment
1. Download the prerequisites to run the application. (Ganache,MetaMask,Truffle,lite-server)

2. Compile the contracts `Auction.sol` and `Migrations.sol` located in `contracts/`
```
$ truffle compile
```
3. Migrate the contract to your local server through Ganache. The contract needs to be compiled (Step 7) before it can be migrated
```
$ truffle migrate
```
4. Run the local server
```
$ npm run dev
```

## Authors
- [Jatin Saraf](www.linkedin.com/in/jatin-saraf)
- [Sargam Mahajan](https://www.linkedin.com/in/sargam-mahajan-a07a31212/)
