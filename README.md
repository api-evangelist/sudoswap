# Sudoswap

Sudoswap is a minimal, gas-efficient automated market maker (AMM) protocol for NFTs. It facilitates NFT-to-token and NFT-to-NFT swaps using customizable bonding curves (Linear, Exponential, XYK, and GDA). The protocol supports ERC-721 and ERC-1155 NFTs alongside ETH and ERC-20 tokens, and is deployed on Ethereum, Base, Arbitrum, Berachain, Sanko, and other EVM-compatible networks.

## APIs

This repository catalogs three developer-facing interfaces:

1. **Smart Contract API** — Permissionless on-chain interface via LSSVMPairFactory, LSSVMPair, VeryFastRouter, and bonding curve contracts. No API keys required; only gas fees apply.
2. **Subgraph API** — GraphQL subgraph on The Graph that indexes pool creation, swap events, and protocol statistics for off-chain querying.
3. **SDK (sudo-defined-quoter)** — TypeScript npm package that wraps the Defined (Codex) API to return real-time bid/ask quotes for NFT collections across supported chains.

## Key Contract Addresses (Mainnet)

| Contract | Address |
|---|---|
| Pair Factory | `0xA020d57aB0448Ef74115c112D18a9C231CC86000` |
| Very Fast Router | `0x090C236B62317db226e6ae6CD4c0Fd25b7028b65` |
| Linear Curve | `0xe5d78fec1a7f42d2F3620238C498F088A866FdC5` |
| Exponential Curve | `0xfa056C602aD0C0C4EE4385b3233f2Cb06730334a` |
| XYK Curve | `0xc7fB91B6cd3C67E02EC08013CEBb29b1241f3De5` |
| GDA Curve | `0x1fD5876d4A3860Eb0159055a3b7Cb79fdFFf6B67` |

## Links

- Website: https://sudoswap.xyz/
- Documentation: https://docs.sudoswap.xyz/
- GitHub: https://github.com/sudoswap
- Blog: https://blog.sudoswap.xyz/
- SDK: https://github.com/sudoswap/sudoswap-sdk
- Subgraph: https://github.com/sudoswap/subgraph-swaps

## Governance

The protocol is governed by the $SUDO token. Holders with at least 300,000 SUDO delegated can submit on-chain proposals to adjust fees, add bonding curves, and update routers.

---

Maintained by [API Evangelist](https://apievangelist.com/)
