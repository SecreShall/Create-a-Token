<h1 align="center">ETH PROOF: Beginner EVM Course</h1>
<h1 align="center">Getting Started with Solidity Project: Create a Token</h1>

# MyToken Smart Contract

This project is a Solidity-based smart contract that simulates a basic cryptocurrency token with functionality to mint and burn tokens. Below, you will find a detailed explanation of its features and how to use it.

## Features

- **Token Information**: The contract includes public variables for the token's name, abbreviation, and total supply.
- **Balance Mapping**: A mapping to track balances of different addresses.
- **Minting**: A function to create new tokens and add them to an address's balance.
- **Burning**: A function to destroy tokens from an address's balance, ensuring the balance is sufficient before burning.

## Smart Contract Details

### Public Variables

- `tokenName`: The full name of the token (e.g., "Bitcoin").
- `tokenAbbrv`: The abbreviated symbol of the token (e.g., "BTC").
- `totalSupply`: The total number of tokens in existence.

### Balance Mapping

- `balances`: A mapping that stores the balance for each address.

### Mint Function

- `mint(address _address, uint _value)`: Increases the total supply of tokens and updates the balance of the specified address.

### Burn Function

- `burn(address _address, uint _value)`: Decreases the total supply of tokens and the balance of the specified address. Checks if the address has enough tokens before burning.


## Authors

Contributors names and contact info

- Clint Audrey Dela Cruz
- Github: SecreShall
