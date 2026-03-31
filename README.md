<div align="center">

<br/>

# 🔐 Solidity Portfolio

### Real-world smart contracts. Production-ready. Fully documented.

A curated collection of Solidity smart contracts covering tokens, DeFi primitives,  
NFTs and advanced patterns — each in its own repo with tests, deployment and full docs.

<br/>

[![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?style=for-the-badge&logo=solidity&logoColor=white)](https://soliditylang.org/)
[![Hardhat](https://img.shields.io/badge/Hardhat-3.x-f7df1e?style=for-the-badge&logo=hardhat&logoColor=black)](https://hardhat.org/)
[![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-5.x-4e5ee4?style=for-the-badge&logo=openzeppelin&logoColor=white)](https://openzeppelin.com/)
[![Ethers.js](https://img.shields.io/badge/Ethers.js-v6-2535a0?style=for-the-badge)](https://ethers.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-c792ea?style=for-the-badge)](LICENSE)

<br/>

> Each contract lives in its **own independent repository** with full documentation:  
> `README.md` · `STEPS.md` · `EXPLANATION.md` · `EXAMPLE.md`

<br/>

</div>

---

## 🗂️ Repository Structure

Each block groups contracts by category. Every contract is an independent GitHub repo:

```
HEO-80/
├── solidity-portfolio/          ← This repo (index + links)
│
├── 📦 Block 1 — Tokens
│   ├── erc20-custom/            ✅ done
│   ├── erc20-tax-token/         🔄 in progress
│   └── deploy-verify-guide/     coming soon
│
├── 📦 Block 2 — DeFi Contracts
│   ├── token-vesting/           coming soon
│   ├── escrow-simple/           coming soon
│   └── staking-contract/        coming soon
│
├── 📦 Block 3 — NFTs
│   ├── erc721-basic/            coming soon
│   ├── nft-royalties/           coming soon
│   └── nft-whitelist-merkle/    coming soon
│
└── 📦 Block 4 — Advanced
    ├── multisig-wallet/         coming soon
    ├── dao-voting/              coming soon
    └── flashloan-receiver/      coming soon
```

---

## 📦 Block 1 — Tokens

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| ERC-20 Custom | Mintable, burnable token with ownership control | ✅ Done | [erc20-custom](https://github.com/HEO-80/erc20-custom) |
| ERC-20 Tax Token | Transfer tax with configurable treasury wallet | 🔄 In progress | [erc20-tax-token](https://github.com/HEO-80/erc20-tax-token) |
| Deploy & Verify Guide | Step-by-step Etherscan verification walkthrough | ⏳ Soon | coming soon |

---

## 📦 Block 2 — DeFi Contracts

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| Token Vesting | Cliff + linear release, multi-beneficiary | ⏳ Soon | coming soon |
| Escrow Simple | Trustless escrow between two parties | ⏳ Soon | coming soon |
| Staking Contract | Deposit tokens, earn time-based rewards | ⏳ Soon | coming soon |

---

## 📦 Block 3 — NFTs

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| ERC-721 Basic | NFT collection with IPFS metadata | ⏳ Soon | coming soon |
| NFT Royalties | On-chain royalties via ERC-2981 standard | ⏳ Soon | coming soon |
| NFT Whitelist Merkle | Presale minting with Merkle tree whitelist | ⏳ Soon | coming soon |

---

## 📦 Block 4 — Advanced

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| Multisig Wallet | M-of-N multi-signature wallet | ⏳ Soon | coming soon |
| DAO Voting | On-chain governance with proposals and voting | ⏳ Soon | coming soon |
| Flash Loan Receiver | Aave V3 flash loan integration | ⏳ Soon | coming soon |

---

## 🧰 Each Repository Contains

```
contract-name/
├── contracts/
│   └── ContractName.sol      # Main contract
├── test/
│   └── ContractName.test.js  # Full test suite
├── ignition/
│   └── modules/              # Deployment scripts
├── README.md                 # Overview and quickstart
├── STEPS.md                  # Exact commands used (reproducible setup)
├── EXPLANATION.md            # How the contract works in detail
└── EXAMPLE.md                # Real-world use case and scenario
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Solidity 0.8.20](https://soliditylang.org/) | Smart contract language |
| [Hardhat 3](https://hardhat.org/) | Development environment |
| [OpenZeppelin 5](https://openzeppelin.com/) | Audited contract libraries |
| [Ethers.js v6](https://ethers.org/) | Blockchain interaction |
| [Mocha + Chai](https://mochajs.org/) | Testing framework |
| [Sepolia Testnet](https://sepolia.etherscan.io/) | Deployment and verification |

---

## ⏱️ Estimated Time per Contract

| Block | Contracts | Time each |
|-------|-----------|-----------|
| Block 1 — Tokens | 3 | 2–3h |
| Block 2 — DeFi | 3 | 3–4h |
| Block 3 — NFTs | 3 | 3–5h |
| Block 4 — Advanced | 3 | 4–6h |

---

## 👤 Author

**Héctor Oviedo** — Full Stack Developer & DeFi Researcher

[![GitHub](https://img.shields.io/badge/GitHub-HEO--80-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HEO-80)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hectorob-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hectorob)

---

<div align="center">

*Built contract by contract. Tested. Documented. Deployed.*

</div>
