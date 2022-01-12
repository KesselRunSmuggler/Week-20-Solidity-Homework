# Week-20-Solidity-Homework

## Resources 
Remix Ethereum IDE - remix.ethereum.org 
Starter Code - See files

## Background
Our new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build 
smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and 
auditing practically automatic!
Fortunately, we've been learning how to program smart contracts with Solidity! What we will be doing this assignment is a 
ProfitSplitter contract. This contract will do several things:

Pay your Associate-level employees quickly and easily.

Distribute profits to employees.

# How the Contract Works

The equal split profit splitter code starts with defining the public variables for each employee. 

The deposit function then splits the profit amount by 3 (msg.value/3) and transfers the equal amounts to each employee.

The deposit function finishes with transferring any remaining wei back to the sender.

![Screen Shot 2022-01-12 at 3 29 08 pm](https://user-images.githubusercontent.com/87409108/149064862-829c7f0e-ff81-4a16-ae29-1755747f5ade.png)

## Testing the contract

After compiling, in the Deploy tab in Remix, deploy the contract to your local Ganache chain by connecting to Injected Web3 and ensure Metamask
is pointed to localhost:8545. By filling in the constructor parameters with the designated employee addresses, the contract can deposit the 
amounts to whichever addresses are entered. These addresses should be taken from your Ganache Chain.

In the Deployed Contracts drop-down, hitting deposit will send the values to the addresses. On your Ganache chain, you can then check the
various balances. 

![Screen Shot 2022-01-12 at 3 30 14 pm](https://user-images.githubusercontent.com/87409108/149069354-37363fa4-6d1d-45e5-b778-f7ec7a0b01a9.png)






