# ERC20 : GLDToken

## Introduction
This is a simple ERC-20 token smart contract designed to demonstrate the creation and deployment of a custom token on the Ethereum blockchain using OpenZeppelin's ERC-20 implementation.

## Description
The `GLDToken` smart contract is implemented in Solidity and showcases the use of OpenZeppelin's ERC-20 standard for creating fungible tokens. The purpose of this contract is to serve as a teaching tool for understanding basic ERC-20 token creation and management.

## Characteristics
- Implements a basic ERC-20 token using OpenZeppelin's libraries.
- Mints an initial supply of tokens to the contract deployer's address.

## Contract Details

### Functions

#### `constructor(uint256 initialSupply)`
This constructor initializes the ERC-20 token with the name "GLDToken" and the symbol "GLD". It mints the specified initial supply of tokens and assigns them to the deployer's address.

## Usage

- **Deployment:** Deploy the contract to the Ethereum blockchain using a compatible Ethereum wallet or development environment.
- **Token Name:** The token is named "GLDToken".
- **Token Symbol:** The token symbol is "GLD".
- **Initial Supply:** When deploying the contract, specify the initial supply of tokens which will be minted to the deployer's address.

This smart contract provides a straightforward example of creating an ERC-20 token using Solidity and OpenZeppelin's ERC-20 implementation.
