# Blockchain Developer Nanodegree Program: Project 5 Decentralized Star Notary

## Introduction

This project is a decentralized star registry service that allows users to register stars using ERC-721 tokens and to look up star registration entries by token IDs. It is implemented based on the Truffle box `webpack` and OpenZeppelin's ERC-721 contract template `ERC721.sol`.
  * **Truffle v.5.0.8** and **OpenZeppelin v.2.1.3** were used in the project.
  * The ERC-721 Token Name is **"Star Registry Token"**.
  * The ERC-721 Token Symbol is **"SRT"**.
  * For project evaluation, the token contract was deployed to the Rinkeby Network with Token Address **0x69bD266748afFf40672E90c884B8e1aD03612D47**.

## Installation

1. Unzip the package to a directory.

If necessary to redeploy the token contract, also do the following:

2. Open the package **package-lock.json** and verify that the dependency `truffle-hdwallet-provider` is installed.
  *  `truffle-hdwallet-provider` is necessary to connect to the Ethereum network when deploying the token contract and can be installed using the command `npm install --save truffle-hdwallet-provider`.
3. Deploy the token contract to Ethereum's Rinkeby test network by running `truffle migrate --reset --network rinkeby`. Deployment to other networks can be enabled by modifying the configuration file `truffle-config.js` and the contract migration contract accordingly.

## Running the app

To run the front end of the application, enter the `app` subdirectory, run `npm run dev`, and open `http://localhost:8080/` using your web browser.

## Star registration

To register a star, enter the Star Name and the Star ID in the **Create a Star** section of the front end and click **Create Star**.

## Star lookup

To look up a star, enter the Star ID in the **Look up a Star** section of the front end and click **Look Up a Star**.

## Project Review

The results of the project review are in the file `Project Review.pdf`.
