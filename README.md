# Metacraftera_EVM_Intermediate_Final_Module_2

# Description

The files index.js, MySmartContract.sol and deploy.js contains codes to practice interaction with smart contracts with front end interaction through a website . 

# Environment Setting for Execution the above files

Follow the steps below:

1. Above repository contains all necessary files to interact with our smartcontract. Here we have three files MySmartContract.sol file which should be put inside contracts folder , index.js in pages folder and deploy.js in scrips folder . 
   All these files of this repository should be replaced wih files of repository provided by SCM-Starter by Metacrafters . 
   
2. We Also Need to Install Metamask Browser Extension , to see live working of our project . 
3. Inside the project directory named (SCM-Starter), in the 1st terminal type: ```npm i```
4. Inside the project directory named (SCM-Starter), in the 2st terminal type: ```npx hardhat node```
5. Inside the project directory named (SCM-Starter), in the 3st terminal type: ```npx hardhat run --network localhost scripts/deploy.js```
6. ack in the first terminal, type ```npm run dev``` to launch the front-end. Now read the below account setting instructions before

# Setting up the local host network and a dummy account in your Metamask Wallet

1. Here we need to set a local dummy account in the Metamask wallet. Since, By default MetaMask wallet is set to your one of real account so don't wanna mess with it. Thats why setteing dummy account.
2. We need to set a local network witn the MetaMask wallet. otherwise Metamask will not be able to communicate with the local node. click on the MetaMask extension then click on the top middle button which is the network selection button.
3. click on (Add a Network)
4. click on (Add a Network Manually)
5. give the (Network name - whatever you want)
6. set the (New RPC URL - http://127.0.0.1:8545/ )
7. set the (Chain ID - 31337 )
8. set the (Currency symbol - ETH )
9. Now set the MetaMask wallet network to the newly created local network
10. to set a account you have to import a account with the accounts private key which you can find in the 2nd terminal where we have exevuted this command ```npx hardhat node``` . after hiting the enter you can see there are many account number with private key is written in the terminal just take any accounts correcponding private key to import it your Metamask Wallet.
11. Head to http://localhost:3000/ to start interacting with the Metamask Wallet.

Now Our Project is Good To Go !!! :)
