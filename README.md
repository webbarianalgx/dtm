# DeFi Token Manager

## What is this?

Defi Token Manager aims to become a modular, multi-chain DeFi asset management platform that allows individuals and teams to securely manage, monitor, and operate on-chain tokens and DeFi positions through a unified interface.

In simple words:
The goal is to build a professional-grade DeFi control center — not just for sending tokens, but for managing assets, permissions, risks, and DeFi activity across multiple blockchains.

## Install & run (PowerShell)

Node.js (LTS): https://nodejs.org/

1. Install dependencies

```powershell
npm install
```

2. Start the development server

```powershell
npm run dev
```

Open http://localhost:3000 in your browser. The app will hot-reload on changes.

## Technologies you should use:

- Nextjs or Vite.
- Router/dom.
- useConext or Redux (Actions/Thunks, Reducer, Selectors).
- Viem / Wagmi.
- Rainbowkit/Rabbykit/Blocknative/Web3modal.
- Prettier/Linter.
- TypeScript.

## Tools:

- How to use etherscan: Etherscan is really usefull to develop since you can see the actual contract and check the read/write methods that this contracts has, also use them (read methods are free to use, write of course you will need to pay for the tx).

# Sepolia:

- Get Testnet ETH: https://www.alchemy.com/faucets/ethereum-sepolia
- Sepolia ERC20 contracts:
  - 18 decimals: 0x1D70D57ccD2798323232B2dD027B3aBcA5C00091 [DAI]
  - 6 decimals: 0xC891481A0AaC630F4D89744ccD2C7D2C4215FD47 [USDC]
