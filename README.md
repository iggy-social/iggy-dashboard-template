# Iggy Dashboard Template

This is a template that allows you to rapidly set up a dashboard to manage your smart contracts, or to develop a web app for end users.

## Delete mirror.yml in .github/workflows

This file is for backup purposes only.

## Managers

This template has a built-in support for contract managers. Smart contract needs to use this extension to support managers: [OwnableWithManagers.sol](https://github.com/iggy-social/iggy-contracts/blob/main/contracts/access/OwnableWithManagers.sol)

## Domain instead of contract address

The field for entering contract address can also accept domain names. So if your contract owns a [punk domain](https://docs.punk.domains/) (in a form of an NFT), you can access it by entering that domain instead of the address.

## Theme

You can pick another theme from [Bootswatch](https://bootswatch.com) by replacing the existing bootstrap.css in `src/assets/css` with the one from another theme.

## Features
- [Vue 3](https://v3.vuejs.org/guide/introduction.html#what-is-vue-js) as the foundation
- [Bootstrap](https://getbootstrap.com/) for styling
- [Vite](https://vitejs.dev/guide/) for faster builds
- [ethers.js](https://docs.ethers.io/v5/) for interacting with Ethereum
- [vue-dapp](https://github.com/chnejohnson/vue-dapp) for the wallet connect
