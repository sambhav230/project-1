#Creating Tokens
The contract is made to create the tokens and to take a look on how transaction of these tokens (virtual coins) is takking place with the help of public variables to store the details about the token:
1. Tname: The name of the token.
2. TAbbrivation: The abbreviation of the token.
3. Supply: The total supply of the token.
4. Mapping of Addresses to Balances:

## Description
This program is a simple contract in Solidity, a programming language  for developing smart contracts on the Ethereum blockchain.
The contract uses a mapping to keep track of balances associated with each address. This is done using mapping(address => uint).
Mint Function:
It increases the total supply by the specified value.
It also increases the balance of the provided address by that value.

Burn Function:
The burn function works opposite to the mint function.
It takes two parameters: an address and a value.
It deducts the value from the total supply.


## Getting Started

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile SPDX-License-identifier MIT.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "project" contract from the dropdown menu, and then click on the "Deploy" button.The burn function includes conditionals to ensure the balance of the address is greater than or equal to the amount to be burned. This prevents burning more tokens than the address holds.

Once the contract is deployed, you can interact with it by calling the Tname function. Click on the "He" contract in the left-hand sidebar, and then click on the function. Finally, click on the "transact" button to execute the function and retrieve the  messages.
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

sambhav kapoor

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)


## License
This project is licensed under the MIT License - see the LICENSE.md file for details




It also deducts the value from the balance of the provided address.
Conditionals in Burn Function:


