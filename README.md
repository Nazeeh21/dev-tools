# Dev Tools comparison Chart

| Tool Name   | Ethereum   | Fuel   | Solana      |
| ----------- | ---------- | ------ | ----------- |
| Smart Contract Language   | Solidity, Vyper       | Rust (with Anchor)   | Sway (based on Rust)        |
| IDE & Code Editors | Remix IDE | Sway Playground | Solana Playground |
| Smart Contract Standards | OpenZeppelin SDK | Sway Standards | Solana SDK (dummy value) |
|  Wallet Interaction | MetaMask, WalletConnect | Wallet SDK | Phantom, Sollet |
| Frontend  APIs      | Ethers.js, Wagmi     | TS SDK    | Lorem ipsum |
| Rust API   | [Rust-Web3](https://github.com/tomusdrw/rust-web3)       |  Rust SDK | Lorem Ipsum   |

| Wallet SDK  | C++        | GPL    | Amet        |
| GraphQL API | JavaScript | BSD    | Consectetur |
| Deployment tools | Truffle, Hardhat, Foundry | Fuelup | Solana CLI |
| Forc        | d          | d      | d           |
| Fuelup           | d          | d      | d           |
| sway playground| d          | d      | d           |
| npm create fuels  | d          | d      | d           |

Sway VScode extension
To develop in Sway on the Fuel blockchain you want to have the Fuel toolchain installed. fuelup is the official package manager for the Fuel toolchain. The take away here is what you get with fuelup is forc (the fuel orchestrator), fuel-core as well as a bunch of other tools.

forc provides a variety of tools and commands for developers working with the Fuel ecosystem, from a simple way to scaffold a new project to formatting, running scripts, deploying contracts, testing contracts, and more. forc is to Fuel, what cargo is to Rust or what pip is to Python. fuel-core lets you spin up an local Fuel node to run tests against during your Sway development.
