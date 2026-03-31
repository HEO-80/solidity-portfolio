# 🔐 Solidity Portfolio — HEO-80

Smart contracts portfolio showcasing real-world DeFi use cases.
Built with Hardhat 3, OpenZeppelin and deployed on testnets.

> Each contract lives in its own independent repository with full documentation:
> `README.md` · `STEPS.md` · `EXPLANATION.md` · `EXAMPLE.md`

---

## 📦 Block 1 — Tokens

| Contract | Description | Repo |
|----------|-------------|------|
| ERC-20 Custom | Mintable, burnable token with ownership control | [erc20-custom](https://github.com/HEO-80/erc20-custom) |
| ERC-20 Tax Token | Token with transfer tax and treasury wallet | [erc20-tax-token](https://github.com/HEO-80/erc20-tax-token) |
| Deploy & Verify Guide | Step-by-step guide to deploy and verify on Etherscan | coming soon |

---

## 📦 Block 2 — DeFi Contracts

| Contract | Description | Repo |
|----------|-------------|------|
| Token Vesting | Cliff + linear release, multi-beneficiary | coming soon |
| Escrow Simple | Trustless escrow between two parties | coming soon |
| Staking Contract | Deposit tokens, earn rewards | coming soon |

---

## 📦 Block 3 — NFTs

| Contract | Description | Repo |
|----------|-------------|------|
| ERC-721 Basic | NFT with IPFS metadata | coming soon |
| NFT Royalties | ERC-2981 royalty standard | coming soon |
| NFT Whitelist Merkle | Minting with Merkle tree whitelist | coming soon |

---

## 📦 Block 4 — Advanced

| Contract | Description | Repo |
|----------|-------------|------|
| Multisig Wallet | M-of-N signature wallet | coming soon |
| DAO Voting | On-chain governance with proposals | coming soon |
| Flash Loan Receiver | Aave V3 flash loan integration | coming soon |

---

## 🛠 Tech Stack

- Solidity 0.8.20
- Hardhat 3
- OpenZeppelin Contracts
- Ethers.js v6
- Mocha + Chai

---

## 👤 Author

**Héctor Oviedo** — Full Stack Developer & DeFi Researcher  
[GitHub](https://github.com/HEO-80) · [LinkedIn](https://linkedin.com/in/hectorob)

# Sample Hardhat Project

Smart contracts portfolio showcasing real-world use cases.
Built with Hardhat, OpenZeppelin and deployed on testnets.

## Blocks
- Block 1 - Tokens (ERC-20 custom, tax token)
- Block 2 - DeFi Contracts (vesting, escrow, staking)
- Block 3 - NFTs (ERC-721, royalties, whitelist)
- Block 4 - Advanced (multisig, DAO, flash loans)

Estructura propuesta:
Un repo paraguas llamado solidity-portfolio con carpetas por bloque, y dentro cada contrato su propia carpeta con Hardhat, tests y README.
solidity-portfolio/
├── README.md (índice general con links)
├── block1-tokens/
│   ├── erc20-custom/
│   ├── erc20-tax-token/
│   └── deploy-verify-guide/
├── block2-defi-contracts/
│   ├── token-vesting/
│   ├── escrow-simple/
│   └── staking-contract/
├── block3-nft/
│   ├── erc721-basic/
│   ├── nft-royalties/
│   └── nft-whitelist-merkle/
└── block4-advanced/
    ├── multisig-wallet/
    ├── dao-voting/
    └── flashloan-receiver/
Tiempo realista por contrato:

Bloque 1 → 2-3h cada uno
Bloque 2 → 3-4h cada uno
Bloque 3 → 3-5h cada uno
Bloque 4 → 4-6h cada uno

