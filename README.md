Creating a Token
Creating a token using Solidity allows you to define and manage digital assets on the Ethereum blockchain. These tokens can represent a variety of assets, from currencies to property or even access rights.

Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. This Solidity smart contract, MyToken, defines a basic token system on the Ethereum blockchain. It includes public variables to store the token's name ("CRYPTOGEM"), abbreviation ("CRYGM"), and total supply. It uses a mapping to keep track of each address's balance. The contract provides a mint function that increases the total supply and the balance of a specified address, effectively creating new tokens. Conversely, the burn function reduces the total supply and the balance of a specified address, destroying tokens, but only if the address has a sufficient balance. This ensures secure and controlled token management within the contract.

Getting Started
Executing Program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., First.sol). Copy and paste the following given code into the created file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile First.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar.
