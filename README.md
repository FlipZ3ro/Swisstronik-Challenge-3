# LearnWeb3DAO <> Swisstronik Challenge 


This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.


# Introduction
### Token
```
Name   : ARAPZZ
Symbol : ARP
```
### Smart Contract
```
0x0225A5435833C3921B04FF6553E641318Aa4DAf2
```
### Function Mint 100 Tokens
```
function mint100tokens() public {
    _mint(msg.sender, 100*10**18);
}
```
### Explorer Deploy
```
https://explorer-evm.testnet.swisstronik.com/tx/0xb2578cdaa7faa1cdec14a4cca3f03925be930bebe54e8d3e4bb59242fb855b29
```
### Explorer Minting
```
https://explorer-evm.testnet.swisstronik.com/tx/0xb7b6e171857b51682eac37d4dc055de94397efc2e312fe146c626a96cf47a44f```
```
### Explorer Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0x01d302b4938f79c3ea1c8e706deb9317c8527cc06e45792895bb7e6f300a9e8c```
```

# Usage
```shell
npx hardhat test
npx hardhat run scripts/deploy.js
npx hardhat run scripts/mint.js
npx hardhat run scripts/transfer.js
```
