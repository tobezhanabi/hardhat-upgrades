# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

WHAT DOES THE PROJECT DO
we are creating a upgrade box contract

we have box and boxv2 with a slight difference
we will use proxy contract to point
proxy box
boxv2

we will use hardhat-deploy's built in proxies in this contract but there are other upgrades like Openzeppelin etc
