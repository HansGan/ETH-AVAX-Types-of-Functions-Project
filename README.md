# TYPES OF FUNCTIONS - ETH AVAX PROJECT

Create and Mint a custom token

## Description

The project revolves around creating contract that extends ERC20 to create a customized ERC20 token. In this case, the token is named as Htoken in the program. The program consists of a constructor (Produces the desired number of tokens and transfers it to the account that initiated the smart contract) and two functions: token_transfer to allow any user to transfer tokens and token_burn to allow any user to burn tokens in the contract.

The token_transfer function implements the require error handling method, this is to prevent the sender of the token to transfer more than the amount of account balance, it uses the transfer function to perform the transaction. Similarly, the token_ burn also implements the require function to prevent errors, it uses the _burn function to perform the transaction.

## Getting Started

### Executing program

Simply run the code in REMIX IDE. To test the code make sure to compile then deploy the smart contract. Choose the desired account that will take on the owner position. Moreover, carefully read each function (refer to the description for details), there are a total of 2 main functions that allows the transfer of tokens from one account to another within the smart contract and to burn token supply of the smart contract.

In other words, here are the steps:
1. Open Remix IDE at https://remix.ethereum.org/
2. Create a solidity file with a file extention of .sol
3. Copy the solidity code from the ETH-AVAX-PROJECT here in this repository
4. Paste the copied code to the file you have created in the Remix IDE
5. Open the solidity compiler and compile your code
6. Open the deploy tab to deploy the smart contract
7. Perform your desired transactions using the defined functions


## Authors
Hans Matthew N. Gan (hansmatthewniervagan@gmail.com)
