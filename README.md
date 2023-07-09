# Degen Token
## Description
The Degen Token is an ERC20-compliant token smart contract written in Solidity. It allows users to transfer and manage tokens on the Ethereum blockchain. The contract supports functionalities such as transferring tokens, approving token transfers, minting new tokens, redeeming tokens, and burning tokens.

## Features
The Degen Token contract provides the following features:

* Transferring tokens: Users can transfer tokens to other addresses on the Ethereum blockchain.
* Approving token transfers: Users can approve other addresses to spend a specified amount of tokens on their behalf.
* Minting tokens: The contract owner has the ability to mint new tokens and distribute them to specific addresses.
* Redeeming tokens: Users can redeem their tokens, reducing their token balance and the total supply.
* Burning tokens: Users can burn (destroy) their tokens, reducing their token balance and the total supply.
## Getting Started
To use the Degen Token contract or deploy it to the Ethereum blockchain, follow these steps:

1. Set up your development environment with an Ethereum-compatible wallet, such as MetaMask.
2. Compile the Degen Token contract using a Solidity compiler, ensuring that the version is compatible (e.g., Solidity ^0.8.0).
3. Deploy the contract to the Ethereum blockchain by sending a deployment transaction. Wait for the transaction to be confirmed on the blockchain.
4. Once the contract is deployed, note down the contract address and other relevant details.
5. Interact with the deployed contract by calling its functions using a wallet or other smart contracts.
## Contract Details
Contract Name: DegenToken <br>
Token Name: Degen <br>
Symbol: DGN
## Examples
Here are some example interactions with the Degen Token contract:

1. Transferring tokens:

* Call the transfer function, providing the recipient's address and the amount of tokens to be transferred.
2. Approving token transfers:

* Use the approve function, specifying the spender's address and the allowed token amount.
3. Minting tokens:

* Call the mint function (only callable by the contract owner), specifying the recipient's address and the number of tokens to be minted.
4. Redeeming tokens:

* Call the redeem function, passing the amount of tokens to be redeemed.
5. Burning tokens:

* Call the burn function, specifying the amount of tokens to be burned.
For detailed information on function parameters and return values, refer to the contract's source code.

## License
#### MIT License

Please note that this README file provides a basic overview of the Degen Token contract and its usage. You can customize the README file according to your specific requirements and add any additional information that you think would be helpful for users of your Degen Token contract.

## Author
Kislay Kaushal
