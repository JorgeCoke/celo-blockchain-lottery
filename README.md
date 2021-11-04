# Celo Lottery Smart Contract

A lottery platform built on top of Celo Blockchain 🔦

## Rules are simple

- Anyone can create a lottery and therefore, becomes the owner of the lottery
- The owner can not play in his own lotteries
- Only the owner can finish a lottery
- Minimum amount of participants: 2 (for development purposes, the same user can buy both tickets and the lottery can be finished by the owner)

## Install

```

npm install

```

## Start

```

npm run dev

```

## Build

```

npm run build

```

## Usage

1. Install the [CeloExtensionWallet](https://chrome.google.com/webstore/detail/celoextensionwallet/kkilomkmpmkbdnfelcpgckmpcaemjcdh?hl=en) from the google chrome store.
2. Create a wallet.
3. Go to [https://celo.org/developers/faucet](https://celo.org/developers/faucet) and get tokens for the alfajores testnet.
4. Switch to the alfajores testnet in the CeloExtensionWallet.
5. Run: npm run dev
6. Go to: [http://0.0.0.0:3000](http://0.0.0.0:3000)
