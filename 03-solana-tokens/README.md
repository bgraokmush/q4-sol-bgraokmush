# Solana Tokens Library 🚀

This repository contains a library for managing **SPL Tokens** and **NFTs** on the Solana blockchain. It provides a comprehensive suite of utilities for minting, initializing, fetching metadata, and working with images of tokens and NFTs.

## Prerequisites 📋

Before using this library, make sure you have the following dependencies installed:

- **Node.js**: Ensure you have the latest stable version of Node.js installed. You can download it from [Node.js official website](https://nodejs.org/).
- **Solana CLI**: Required to interact with the Solana blockchain network. Installation instructions can be found [here](https://docs.solana.com/cli/install-solana-cli-tools).
- **TypeScript**: Install TypeScript globally via npm:

  ```bash
  npm install -g typescript
  ```

## Dependencies

Add the following dependencies to your `package.json` file to use this library:

```json
"dependencies": {
  "@coral-xyz/anchor": "0.29.0",
  "@metaplex-foundation/mpl-token-metadata": "3.1.1",
  "@metaplex-foundation/umi": "^0.8.10",
  "@metaplex-foundation/umi-bundle-defaults": "^0.8.10",
  "@metaplex-foundation/umi-uploader-irys": "^0.10.0-beta.0",
  "@solana/spl-token": "^0.3.9",
  "@solana/web3.js": "^1.87.6",
  "@types/node": "^20.9.3",
  "@types/prompt": "^1.1.8",
  "bs58": "^5.0.0",
  "prompt": "^1.3.0",
  "typescript": "^5.3.2"
}
```

## Getting Started

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/bgraokmush/q4-sol-bgraokmush
cd solana-tokens
npm install
```

### Commands Overview

The library provides several methods for working with NFTs and SPL tokens. Below are the available scripts and their functionality:

#### 1. **NFT Image Management** 🖼️

- Extract images from NFTs:

  ```bash
  npm run nft_image
  ```

#### 2. **NFT Metadata** 🔍

- Fetch metadata associated with an NFT:

  ```bash
  npm run nft_metadata
  ```

#### 3. **NFT Minting** 🪙

- Mint a new NFT on the Solana blockchain:

  ```bash
  npm run nft_mint
  ```

#### 4. **SPL Token Initialization** 🛠️

- Initialize a new SPL token:

  ```bash
  npm run spl_init
  ```

#### 5. **SPL Token Metadata** 📝

- Fetch metadata for an SPL token:

  ```bash
  npm run spl_metadata
  ```

#### 6. **SPL Token Minting** 💰

- Mint a new SPL token:

  ```bash
  npm run spl_mint
  ```

## Example Transactions 🔍

- **NFT Minting**: https://explorer.solana.com/tx/<transaction-id>?cluster=devnet
- **SPL Token Metadata Fetch**: https://explorer.solana.com/tx/<transaction-id>?cluster=devnet

Replace `<transaction-id>` with your specific transaction ID to view details on the Solana Explorer.

## Running Tests 🧪

Each functionality is validated with test scripts. To run the tests, simply execute:

```bash
npm test
```

This will verify NFT and SPL token minting, metadata fetching, and related processes.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing 🤝

We welcome contributions! Feel free to submit issues, fork the repo, and create pull requests. For major changes, please open an issue first to discuss what you would like to change.
