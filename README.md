# final-project-hyqiu

This is the submission repo for the Consensys Academy Developer's Program 2019.

# Project Documentation

* Project description : https://docs.google.com/document/d/1zwJ7NHm3kzYCB-VVPoxrDVtCFVXr2wuTwtEQvOV5g7c/edit?usp=sharing
* dApp functioning process : https://docs.google.com/presentation/d/1Vy7sgw3CK5oGi2UX00JY4Sm9sXU_NCc8OJjHkjsT99Q/edit?usp=sharing

## Prerequisites

* Truffle v5.0.0 (core: 5.0.0)
* Solidity v0.5.0 (solc-js)
* Node v8.10.0
* Web3 ^1.0.0-beta.35
* Ganache-CLI v6.2.5

## Local Run

### Setup 
* Clone the repository and initialize npm, 
```bash
npm install
```
* Navigate to client folder and initialize npm 
```bash
cd client
npm install
```
* Initialize ganache-cli, preferably with your metamask accounts, on port 8545
```bash
ganache-cli -m "your mnemonic"
```

### Unit testing
The unit tests are located in the `test` folder. 
* Go to project root and migrate with truffle
```bash
truffle migrate --reset --all
```
* Run tests
```bash
truffle test
```

### dApp

* Go to `client` folder and run 
```bash
npm run start
```
* Follow the instructions in the documentation (dApp functioning process)


## Used libraries
* "openzeppelin-solidity": "2.1.2"

## Files of interest 

* `deployed_addresses.txt`: File listing the deployed contracts on Rinkeby testnet (id: 4) that can be on https://rinkeby.etherscan.io/
* `avoiding_common_attacks.md`: File listing 4 risks associated to the contracts as deployed.
* `design_patterns.md`: File listing the design patterns involved in the project
