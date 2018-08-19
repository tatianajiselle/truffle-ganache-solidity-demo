# truffle-ganache-solidity-demo
  
---

Pre-Requisites:
- [Node](https://nodejs.org/en/) - You need npm
- [Ganache](https://truffleframework.com/ganache) - A personal chain for Ethereum development
- [MetaMask](https://metamask.io) - In browser wallet that connects to multiple testnets and main ethereum net

---

When running this application, please make sure you have created a MetaMask account using the seed phrase located on Ganache upon launch,  
as well as setting up a Custom RPC using the following localhost: 
> http://127.0.0.1:7545      
and hitting save. *DO NOT USE ON THE MAINNET.*  

--- 
## How to launch your local environment


To install Truffle:
> npm install -g truffle  


To compile the app:
> truffle compile


*Launch Ganache*


To migrate the code to the blockchain:
> truffle migrate


To test the app:
> truffle test


*Launch MetaMask w/ Custom RPC*


To start the local lite-server: 
> npm run dev 




