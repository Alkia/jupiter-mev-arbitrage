# jupiter-mev-arbitrage
Arbitrage Bot on Solana. An arbitrage is considered successful if you start with an amount of token A, and end up with more of it than you started. 

We're going to be writing this bot with typescript and using Jupiter's aggregator sdk  [Jupiter Core SDK](https://www.npmjs.com/package/@jup-ag/core).

## Integrate with React instead?
The quickest way to integrate Jupiter with your React UI, use [Jupiter React Hook instead](https://www.npmjs.com/package/@jup-ag/react-hook).

## React Native?
Checkout [Jupiter React Native Example](https://github.com/mercurial-finance/jupiter-react-native).

## Documentanion
[Jupiter Documentation](https://docs.jup.ag/).

## Getting started
- We recommend `yarn` due to `resolutions`
- Add a `.env` to root
- Populate these values
```
CLUSTER=mainnet-beta
WALLET_PRIVATE_KEY=<wallet private key> ## or set it up in src/constants
```
- yarn
- yarn start
