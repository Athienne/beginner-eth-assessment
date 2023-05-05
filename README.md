# MyCoin
This Solidity program is a for the Metacrafters Beginner's Asessment. The purpose of this program is to practice the basic components of Solidity. Present in this program are the discussed topics in the Module 1 of the Metacrafters Beginner's Course in Solidity.

## Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The overall function of this contract is to create a simple original token with two (2) functions that is able to alter the said token. The variables stated which are the "tokenName", "tokenAbbr" and "tokenSupply" are used to initialize the characteristic of the token. "tokenName" refers to the name of the token, "tokenAbbr" refers to the abbreviated name of the token, and "tokenSupply" is the total number of tokens present. 

The two (2) functions mentioned earlier are the "mint" function, wherein the program may create a number of token(s) based on the given value, and the "burn" function, wherein the program can delete a number of tokens(s) based on the given value. The "burn" function can only burn the said value of tokens if the balance of the sender and the total supply of the tokens are greater than the number of value that will deleted. Otherwise, the function will cease to execute the code.

## Getting Started
Executing program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyOtherCoin.sol). Copy and paste the code present in this repository called "MyCoin.sol".

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile MyOtherCoin.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyOtherCoin" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling some of the variables stated which are the "tokenName", "tokenAbbr" and "tokenSupply". Click the buttons on the left side to see that values of the variables. Furthermore, you can interact with the functions "mint" and "burn". To create new tokens, copy the address located on the top of the sidebar and paste it on the Address box of the "mint" function. Afterwards, enter the number of tokens that you want to create and click "Transact". This process is also the same with the "burn" function.

## Authors

Mark Anthony G. Mamauag
markmamauag35@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
