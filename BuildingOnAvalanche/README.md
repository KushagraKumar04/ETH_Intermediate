# MyToken Smart Contract

## Introduction

MyToken is a simple yet powerful smart contract designed for minting and burning tokens on the Ethereum blockchain. It serves as an educational tool for understanding fundamental token management and smart contract development.

## Description

The MyToken contract implements a basic ERC20-like token in Solidity. It allows for tracking the total supply and balances of individual addresses, minting new tokens, and burning existing tokens. This contract is ideal for those who want to learn about token creation and management in the Ethereum ecosystem.

## Features

- **Token Information**: Stores information about the token, such as its name and abbreviation.
- **Balance Mapping**: Tracks the token balance of each address.
- **Minting and Burning**: Functions to create and destroy tokens with necessary validations.
- **Redeeming Tokens**: Allows users to redeem tokens.
- **Token Transfers**: Facilitates token transfers between addresses.
- **Balance Queries**: Enables querying of token balances and redeemed items.

## Contract Details

### Variables

- **tokenName (string)**: The name of the token. (e.g., "DEGEN")
- **tokenAbbrv (string)**: The abbreviation of the token. (e.g., "DGN")
- **totalSupply (uint)**: The total supply of tokens.

### Mapping

- **balances**: Maps addresses to their respective token balances.
- **redeemedItems**: Maps addresses to their redeemed items.

### Functions

- **mint(address to, uint256 amount)**: Mints new tokens to the specified address.
- **burn(uint256 amount)**: Burns tokens from the caller's balance.
- **redeem(uint256 amount)**: Redeems tokens, reducing the caller's balance and recording the redemption.
- **getRedeemedItems(address account)**: Returns a list of redeemed items for the specified address.
- **printRedeemedTokens(address account)**: Returns a string representation of redeemed tokens for the specified address.
- **checkBalance(address account)**: Returns the token balance of the specified address.
- **transferTokens(address from, address to, uint256 amount)**: Transfers tokens from one address to another.

## Usage

### Deployment

To deploy the contract, use the "Deploy" option in your preferred Ethereum development environment.


