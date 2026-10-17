# ChainLedger Web

Paste a wallet address, get a Koinly-ready CSV. Runs entirely in your browser — no account, no API key, no server, no upload.

**Live:** https://kaminariouji.github.io/chainledger-web/

## What it does

- Reads ERC-20 `Transfer` events and native transactions for one address on one chain
- Writes a Koinly CSV and a raw CSV
- Talks directly to the chain's public Blockscout instance from your tab; your address goes only there, from your own IP

Supported: Base, Ethereum, Optimism, Polygon, Arbitrum.

## What it does not do

- No cost-basis or trade classification. Ambiguous rows are left unlabelled rather than guessed.
- One wallet, one chain per run, up to 20 pages of history.
- Native transfers only appear where the explorer exposes them.

## Why it exists

Most crypto tax tools charge by transaction count, and the free explorers do not export in a shape Koinly accepts. This is the smallest thing that closes that gap without a backend.

## Full version

The command-line version handles many wallets, every chain and full history, offline, for a one-time $19: https://ko-fi.com/s/f8dcae9582

## Licence

MIT.
