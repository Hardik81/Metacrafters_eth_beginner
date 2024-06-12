# Creating a token

This is the part of final assessment of Ethereum beginner course from metacrafters academy. In this project we have to create a token on remix editor ethereum and define some functions for minting as well as burning the tokens we make.

## Description

This program is a simple contract named "mytoken" is written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a variables such as tokenname,tokenabbrv and totalsupply that is the number of tokens available for transaction. The contract also have two functions named mint and burn that takes address and values as arguments and update the values for balance of the address taken and total suppply accordingly. This progrm teaches us how to work with solidity and ethereum
## Getting Started

### Executing program

1. Open remix ethereum IDE an online solidity compiler.
2. Define the solidity version like pragma solidity 'version'
3. Define a contract. In my case it I made a contract MyToken
4. Give the details of your token. Here we use the variables tokenname,tokenabbrv and totalsupply in which we store the details about our own token.
5. Map the address to balances
6. Define a mint function that takes two parameters: an address and a value. This function will increase the total supply by that number(value in our case) and increases the balance of the address argument by that value.
7. Define a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then decrease the value from the total supply and from the balance of the address parameter passed .
8. The thing we need to care of is when we are burning the token there should be equal or more number of tokens available as balaance of the address than the tokens to be burnt. For this we use conditional statement.

## Authors

Contributors names and contact info

Hardik  
hardikxibscience238@gmail.com
