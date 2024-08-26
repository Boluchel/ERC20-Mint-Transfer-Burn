# ERC20 Token Contract

## Overview
This contract implements a basic ERC20 token with minting, burning, and transferring capabilities. It utilizes OpenZeppelin's libraries for secure and efficient development.

## Description
This project demonstrates the creation and deployment of an ERC20 token using Hardhat. The contract includes three primary functions:
* Mint: Creates new tokens and assigns them to a specified address.
* Burn: Removes tokens from circulation, reducing the total supply.
* Transfer: Allows tokens to be transferred between addresses.

## Getting Started

### Installation
```
* git clone https://github.com/Boluchel/ERC20-Mint-Transfer-Burn.git
* npm install
```
### Deployment
```
npx hardhat compile
```

## Contract Details
* Contract Name: Tokens
* Token Name: Bolu
* Token Symbol: BO

## Functions
### mint(address to, uint256 amount)
* Access: OnlyOwner
* Description: Creates new tokens and assigns them to the specified address.

### burn(address from, uint256 amount)
* Access: Public
* Description: Removes tokens from circulation, reducing the total supply.

### transfer(address _from, address _to, uint256 _amount)
* Access: Public
* Description: Transfers tokens between addresses.

## Authors
Banwo Boluwatife

## License

This project is licensed under the MIT License
