# Decentralized Banking System (DeFi Bank)
This repository focuses on development of a decentralized banking system which is a DApp built on Ethereum blockchain with smart contract on solidity.


DeFi Bank provides Witdraw, borrow and payoff fucntionalities. All the data and business logic are stored and run on Ethereum blockchain by smart contracts.


## Installation

### Setup

- **Node.js**

      sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
      nvm install 12.18.3
      node -v

- **Truffle**

      sudo npm install -g truffle@5.1.39 --unsafe-perm=true

- **Ganache** installation guide can be found in [here](https://www.trufflesuite.com/ganache).

- **MetaMask** installation guide can be found in [here](https://metamask.io/).

### Commands

- Install necessarily Node.js packages

      npm install

- Deploy smart contracts to the Ethereum blockchain

      truffle migrate --reset
      
- Deploy and run the front-end application

      npm start run
      
- Run the scripts to issue tokens

      truffle exec scripts/issue-tokens.js


## Citation
If you use this code for your publications, please cite it as:

    @ONLINE{
        author = "Ahmet Özlü",
        title  = "DeFi Banking System",
        year   = "20212,
        url    = "https://github.com/ahmetozlu/decentralized_banking_system"
    }

