# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```

For BCOS network

```shell
# copy .env.example to .env 
cp cp .env.example .env

# deploy contract
npx hardhat ignition deploy ./ignition/modules/Lock.js --network bcosnet

# test contract
npx hardhat test --network bcosnet
```
