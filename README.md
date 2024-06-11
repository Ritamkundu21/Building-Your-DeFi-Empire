# Building-Your-DeFi-Empire

## DeFi Kingdom Clone Setup Guide

This repository contains all the necessary resources and instructions to set up your own DeFi Kingdom clone on a custom EVM subnet using the Avalanche network.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Setup Instructions](#setup-instructions)
    1. [Set up your EVM Subnet](#set-up-your-evm-subnet)
    2. [Define your Native Currency](#define-your-native-currency)
    3. [Connect to MetaMask](#connect-to-metamask)
    4. [Deploy Basic Building Blocks](#deploy-basic-building-blocks)
4. [Testing](#testing)
5. [Useful Links](#useful-links)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This guide will walk you through the process of setting up a custom EVM subnet on the Avalanche network, defining your native currency, connecting your subnet to MetaMask, and deploying the basic building blocks of your game using Solidity and Remix. By the end of this guide, you will have a functional clone of DeFi Kingdom that you can customize further.

## Prerequisites

Before you begin, make sure you have the following:

- Node.js and npm installed
- MetaMask installed in your browser
- Basic understanding of Solidity and smart contracts
- Familiarity with Avalanche CLI and Remix IDE

## Setup Instructions

### 1. Set up your EVM Subnet

Follow our guide and the [Avalanche documentation](https://docs.avax.network) to create a custom EVM subnet on the Avalanche network.

1. Install the Avalanche CLI:
   ```sh
   npm install -g avalanche
   ```

2. Initialize your subnet:
   ```sh
   avalanche subnet create <subnet-name>
   ```

3. Configure the subnet according to your needs.

### 2. Define your Native Currency

You can set up your own native currency, which will be used as the in-game currency for your DeFi Kingdom clone. This involves defining the parameters for your currency within your EVM subnet configuration.

### 3. Connect to MetaMask

To connect your EVM Subnet to MetaMask, follow these steps:

1. Open MetaMask and go to `Settings` > `Networks` > `Add Network`.
2. Fill in the network details using the information from your EVM subnet.
3. Save the network and switch to it.

### 4. Deploy Basic Building Blocks

Using Solidity and Remix, deploy the basic building blocks of your game, such as smart contracts for battling, exploring, and trading. These contracts will define the game rules, such as liquidity pools, tokens, and more.

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Connect Remix to your MetaMask wallet by selecting `Injected Web3` as the environment.
3. Write and compile your smart contracts in Solidity.
4. Deploy the contracts using the Remix interface.

## Testing

Once your contracts are deployed, test your application:

1. Use Remix to interact with your deployed contracts.
2. Deploy tokens, liquidity pools, and other necessary components.
3. Verify the functionality of your game rules and interactions.

## Useful Links

- [Avalanche Documentation](https://docs.avax.network)
- [MetaMask](https://metamask.io/)
- [Remix IDE](https://remix.ethereum.org/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

By following these instructions, you will have your own DeFi Kingdom clone up and running on a custom EVM subnet on the Avalanche network. Happy building!
