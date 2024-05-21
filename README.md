# Rhinestone Sandbox

**A frontend playground building and testing smart account modules**

> The Sandbox is in active development and is subject to breaking changes. If you spot a bug, please take out an issue and we will fix it as soon as we can.

![sandbox dashboard](./public/dashboard.png)

## Using the Sandbox

### Installation

```bash
yarn install
```

### Usage

1. Create a `.env` file based on the `.env.example` file
2. Run `yarn dev` to start the development server

### Custom network

To add a new network, add an entry to the `networks` object in `src/domains/Network/api/networks.ts`.

## Features

- [x] Create an ERC-7579 smart account using either an EOA or a passkey as a signer
- [x] Multi-account support and switcher
- [x] Utility functions for interacting with the smart account
- [x] Complete abstraction of ERC-4337 flows
- [x] Activity log using [Jiffyscan](https://jiffyscan.xyz/)
- [x] Faucet for testnet tokens
- [x] Support for transfering ERC-20 tokens
- [ ] Add an indexer to dynamically fetch all assets and balances
- [ ] Switch active validator

## Using this repo

To install the dependencies, run:

```bash
yarn install
```

To start the development server, run:

```bash
yarn dev
```

## Contributing

For feature or change requests, feel free to open a PR, start a discussion or get in touch with us.
