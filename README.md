# eth-supplychain

## Description

A supplychain smart contract written in Solidity. This Smart contract demonstrates how supply chains can improve authenticity, efficiency and privacy between seller and buyer.

## Quick Start
 
- cd into project repro

- download node libraries

```
 npm install
```

- Download/Start ganache

https://truffleframework.com/ganache

- Compiling contracts

 ```
 truffle compile
 ```
- Migrating to ganache

Note depending on ganache cli/ui you my need to change truffle.js port settings Current listing on port : 7545

   ```
   truffle migrate --network development  --reset --all
   ```

- Testing on ganache

 ```
 truffle test
 ```

- Start Front End 

```
cd ..
cd client
npm run dev
```
