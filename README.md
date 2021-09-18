# blockchain developer bootcamp final project - NFT Card 

This repository containts an Ethereum DApp that demonstrates a Card Battle Game base on NFT Cards (ERC721 Token) .
In this game there are different worlds that each of them have their own mythology and each card will represent a different god and goddess and other creatures.
Each card contains the power and level of the god and creature it belongs to. It can also be a special symbol representing an event or a specific god. Like the ancient mythology these creatures have their battles and relations and having a card or a collection of cards can result in obtaining another card for free as a trophy. The card will be choosen from the tales of the said creatures and ...  
.... To be Continue 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* *Ganache CLI* v6.12.2 (ganache-core: 2.13.2)
* *Truffle* v4.1.14 (core: 4.1.14)
* *Solidity* v0.4.24 (solc-js)
* *Node* v14.17.5
* *NPM* v6.14.10
* *Web3.js* v1.5.2
* *truffle-hdwallet-provider* 1.0.17

### Additional Libraries Used

-  **Truffle**: To compile, test and migrate contracts.
-  **Solidity**: To compile Solidity codes.  
-  **Web3**: To Connect on BlockChain.
-  **truffle-hdwallet-provider**: Used to Manage connection to Wallet from Truffle.
-  **Infura**: For Deploying Smart Contract.


### Installing

Clone this repository:

```
git clone https://github.com/baties/blockchain-developer-bootcamp-final-project.git
```

Then Install all requisite npm packages (as listed in ```package.json```):

```
npm install
```

Launch Ganache:

```
ganache-cli 
```

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Test smart contracts:

```
truffle test
```

All tests should pass.


In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.

## Acknowledgments

* Solidity  
* Ganache-cli
* Truffle


## Example workflow

* User identifies himself/herself with Metamask wallet
* User chooses his/her Battle type
* User set ready for start
* Smart-Contract Starts the battle  
* The result will be shown to the all users in the game
