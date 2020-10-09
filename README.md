# Blockchain CryptoStar Dapp

* Implement missing features for project 5 in udacity Blockchain nanodegree
* Implement stubbed contract tests
* Implement front end updates for new features

-[Etherscan Link](https://rinkeby.etherscan.io/tx/0x8fc34dfae2c505161d9969e72e955233e8f7d89e23238ceaeec0ff28fa33bfed)

## Token Info

* ERC-721 token name : "CryptoStar"

* ERC-721 token symbol : "STNT"

* Contract Address : 0x52B335273530e49cE56CAC30DeFbc467363E6D26

### Transaction Info 
#### Rinkeby Network : 0x52B335273530e49cE56CAC30DeFbc467363E6D26

  ```
     Deploying 'StarNotary'
   ----------------------
   > transaction hash:    0x8fc34dfae2c505161d9969e72e955233e8f7d89e23238ceaeec0ff28fa33bfed
   > Blocks: 0            Seconds: 12
   > contract address:    0x52B335273530e49cE56CAC30DeFbc467363E6D26
   > block number:        7336743
   > block timestamp:     1602207674
   > account:             0xD566D2bb69655Ea8533442CF0F7DAea4c1b6A88f
   > balance:             2.9478072
   > gas used:            2342040 (0x23bc98)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.0468408 ETH
  ```

  

## Getting Started

Project Details to compile and test contract

### Dependancies

1. Node.js v12.18.4
2. Truffle v5.1.47  
3. Openzeppelin 2.3
3. https://infura.io

If you want deploy the smart contract to Rinkeby network, you need to the following:

1. Your Metamask's seed phrase.
2. [Infura](https://infura.io/) Project ID

### Installing

Local development procedures:

```
npm install --save @truffle/hdwallet-provider
npm install --save openzeppelin-solidity@2.3
```

Run the truffle develope. *Truffle Develop started at http://127.0.0.1:9545/*

```
truffle develop
```

Type compile on truffle(develope) console. This compiles the smart contract.

```
compile
```

Deploy the smart contract on the your private network.

```
migrate --reset
```

To run the front-end of the Dapp, You have to type following command on New Terminal.

```
cd app
```

Start the front end.  *Project is running at http://localhost:8080/*

```
npm run dev
```

Open that url in your browser to access the front-end of the Dapp.



### Deploy the Smart Contract to Rinkeby Network

If you want deploy the smart contract to Rinkeby network, you need to the following:

* You have to type your infura Project ID to `const infuraKey = {Infura POJECT ID}` in truffle-config.js file.
* Type Metamask's backup phrase to `const mnemonic = {METAMASK SEED}` in truffle-config.js file.
* Type `truffle migrate —reset —network rinkeby` on the terminal.



## Running the tests

Using the Truffle enviornment to run the contract tests

* Type `test` command on truffle console.

```
truffle(develop)> test
Using network 'develop'.


Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.



  ✓ can Create a Star (546ms)
  ✓ lets user1 put up their star for sale (679ms)
  ✓ lets user1 get the funds after the sale (877ms)
  ✓ lets user2 buy a star, if it is put up for sale (968ms)
  ✓ lets user2 buy a star and decreases its balance in ether (941ms)
  ✓ can add the star name and star symbol properly (518ms)
  ✓ lets 2 users exchange stars (1090ms)
  ✓ lets a user transfer a star (690ms)
  ✓ lookUptokenIdToStarInfo test (421ms)

  9 passing (7s)
```



## Built With

* [Node.js](https://nodejs.org/en/) v12.18.4 - The JavaScript used.
* [Truffle](https://truffleframework.com/) v5.0.26 - A development framework for Ethereum.
* [openzeppelin-solidity]() v2.3 - Library for secure smart contract development.

## Works Cited

* **Mingu Kang** - [Github](https://github.com/minqukanq)
* This readme and some code is based on the git repository [https://github.com/minqukanq/build-cryptostar-dapp-on-etereum](https://github.com/minqukanq/build-cryptostar-dapp-on-etereum)
* [https://www.trufflesuite.com/docs/truffle/overview](https://www.trufflesuite.com/docs/truffle/overview)
* [https://docs.openzeppelin.com/openzeppelin/](https://docs.openzeppelin.com/openzeppelin/)

## Author

* **Joseph Mitchell** - [Github](https://github.com/Business-Art-Technology-MAN)