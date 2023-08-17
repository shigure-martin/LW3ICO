# Start a Hardhat Project

```shell
npm init
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat

npm install dotenv
```

to fix the hardhat compiling bug, you should execute these command:
```shell
npm install --save-dev @nomicfoundation/hardhat-toolbox @nomicfoundation/hardhat-network-helpers @nomicfoundation/hardhat-chai-matchers @nomiclabs/hardhat-ethers @nomiclabs/hardhat-etherscan chai ethers hardhat-gas-reporter solidity-coverage @typechain/hardhat typechain @typechain/ethers-v5 @ethersproject/abi @ethersproject/providers
```

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
address on the goerli: 0x377c45A45EF24829cA289Ad76FcdAbCb759Ed898


