MyERCToken - Simple ERC-20 Token Contract
Description:
MyERCToken is a basic Ethereum ERC-20 token contract designed to manage a simple token with minting and burning functionalities. This contract allows you to create, transfer, and destroy tokens while ensuring that the balances are properly managed.

Contract Details
Token Name: DEFIX
Token Abbreviation: DFX
Total Supply: 0 (initially)
Public Variables
tokenName: A public string representing the name of the token (DEFIX).

tokenAbbrv: A public string representing the abbreviation of the token (DFX).

totalSupply: A public unsigned integer indicating the total supply of tokens.

Mapping
balances: A mapping of Ethereum addresses to their respective token balances.

Functions
mint(address _address, uint _value): This function allows the creation of new tokens. It takes two parameters: _address (recipient address) and _value (number of tokens to mint). It increases the total supply and adds tokens to the balance of the specified address.

burn(address _address, uint _value): This function enables the destruction of tokens. It takes two parameters: _address (sender address) and _value (number of tokens to burn). It decreases the total supply and deducts tokens from the balance of the specified address. It checks if the sender's balance is sufficient to burn the specified amount.
