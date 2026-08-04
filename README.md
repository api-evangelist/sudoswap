# Sudoswap

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
