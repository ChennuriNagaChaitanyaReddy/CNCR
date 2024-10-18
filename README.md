# MyToken Smart Contract

## Overview

The `MyToken` smart contract is a basic implementation of a token system on the Ethereum blockchain. It defines a token named **META** with the abbreviation **MIT**. The contract includes methods for minting new tokens, burning tokens, and keeping track of token balances for different addresses.

## Features

- **Token Metadata**: The contract holds the token’s name, abbreviation, and total supply.
- **Minting Tokens**: A function that allows tokens to be added to a specific address, increasing both the total supply and the balance of that address.
- **Burning Tokens**: A function that destroys tokens from a specific address, reducing both the total supply and the balance of the address.
- **Balance Management**: The contract maintains a mapping of token balances for all addresses.

## Code Walkthrough

### Token Details

```solidity
string public tokenName = "CHAITANYA";
string public tokenAbbrv = "CNCR";
uint public totalSupply = 0;
