# CryptoBank

This is a Crypto bank running on Ganache.

## Features

* Staking mDAI Tokens
* Earn Dapp Tokens
* Unstake mDai Tokens 

## Prerequisites

Be sure you have the following installed on your development machine:

+ node.js
+ Ganache
+ Truffle
+ MetaMask Chrome extension

## Project Installation

To setup a local development environment:

### Install development dependencies,
Install Node.js from https://nodejs.org/en/ and Ganache from https://www.trufflesuite.com/ganache
```bash
npm install --g truffle@5.1.39
```
Set up MetaMask extension for second Account of Ganache


### Clone GitHub Project,
```bash
git clone https://github.com/siDcover/CryptoBank CryptoBank
```

### Migrate and Deploy,
```bash
truffle migrate
```
or,
```bash
truffle migrate --reset
```

### Run the web application locally,
```bash
npm run start
```

### Issue Dapp Tokens for staking,
```bash
truffle exec scripts/issue-tokens.js
```
