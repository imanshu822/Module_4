# DegenToken Solidity Contract

## Overview

DegenToken is a basic ERC20 token contract written in Solidity. It allows for token creation, transfer, minting, burning, and a redemption function.

### Contract Details
- **Name**: DegenToken
- **Symbol**: DGN

## Features

1. **Token Creation and Ownership**: 
   - The contract creator initializes the token with an initial supply.
   - The creator is set as the owner of the contract.

2. **Token Transfer**:
   - Users can transfer tokens to another address.

3. **Token Minting**:
   - Only the contract owner can mint new tokens.

4. **Token Burning**:
   - Users can burn their own tokens, reducing the total supply.

5. **Token Redemption**:
   - Users can redeem tokens for a specific purpose, marking the redemption status.

## Getting Started

To interact with the DegenToken contract:
1. Deploy the contract using Solidity compiler targeting version ^0.8.18.
2. Use a wallet or script to interact with contract functions:
   - Transfer tokens (`transfer` function)
   - Mint new tokens (`mint` function)
   - Burn tokens (`burn` function)
   - Redeem tokens (`Redeem` function)

## Deployment

Deploy the contract to a supported Ethereum Virtual Machine (EVM) environment.

## Usage

- **Token Transfer**: Use the `transfer` function to send tokens.
- **Token Minting**: Use the `mint` function (requires owner access).
- **Token Burning**: Use the `burn` function to reduce the token supply.
- **Token Redemption**: Use the `Redeem` function to redeem tokens for a specific purpose.

## Example

Example deployment and interaction code snippets can be found in the `examples/` directory.

## License

This contract is licensed under the MIT License. See `LICENSE` for more details.
