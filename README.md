#MyToken Smart Contract
This repository contains the implementation of a simple ERC20-like token on the Ethereum blockchain using Solidity. The contract includes basic functionalities such as minting and burning tokens. Below are the key features and how you can use this contract.

##Table of Contents
Introduction
Contract Details
Functions
Mint
Burn
License

##Introduction
This smart contract, MyToken, is a basic example of how to create and manage a custom token on the Ethereum blockchain. The contract includes:

Public variables to store token details (Token Name, Token Abbreviation, and Total Supply).
A mapping to keep track of each address's token balance.
Functions to mint and burn tokens.

##Contract Details:

Token Name: CRAFTERS
Token Abbreviation: CFT
Total Supply: 0 (initially)

##Functions

###Mint

The mint function allows you to create new tokens and assign them to a specific address.
Parameters:
addr: The address to which the minted tokens will be assigned.
value: The number of tokens to mint.

###Burn:

The burn function allows you to destroy tokens from a specific address, reducing the total supply.
Parameters:
addr: The address from which the tokens will be burned.
value: The number of tokens to burn.
Condition: The balance of the addr must be greater than or equal to the value to be burned.



