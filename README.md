"EVOTE" is a decentralized blockchain-based electoral platform designed to revolutionize modern elections by ensuring security, transparency, and efficiency. Built on the Ethereum-based Volta blockchain, it integrates React.js, Solidity, and Metamask for a seamless and user-friendly voting experience. Utilizing Hardhat, ethers.js, and RPC nodes, the platform enables secure smart contract deployment and reliable blockchain interaction. EVOTE addresses challenges in traditional voting systems, such as ballot tampering and lack of transparency, by providing a tamper-proof, verifiable, and scalable solution that enhances electoral integrity and trustworthiness.
## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
