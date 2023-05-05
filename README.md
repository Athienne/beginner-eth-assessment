MyCoin
This Solidity program is a for the Metacrafters Beginner's Asessment. The purpose of this program is to practice the basic components of Solidity. Present in this program are the discussed topics in the Module 1 of the Metacrafters Beginner's Course in Solidity.

Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The overall function of this contract is to create a simple original token with 2 functions that is able to alter the said token. These functions are the "mint" function, wherein the program may create a number of token(s) based on the given value, and the "burn" function, wherein the program can delete a number of tokens(s) based on the given value. The "burn" function can only burn the said value of tokens if the balance of the sender and the total supply of the tokens are greater than the number of value that will deleted. Otherwise, the function will cease to execute the code.

Getting Started
Executing program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

pragma solidity ^0.8.4;

contract HelloWorld {
    function sayHello() public pure returns (string memory) {
        return "Hello World!";
    }
}

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile MyCoin.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyCoin" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "HelloWorld" contract in the left-hand sidebar, and then click on the "sayHello" function. Finally, click on the "transact" button to execute the function and retrieve the "Hello World!" message.
