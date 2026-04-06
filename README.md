<div align="center">

<br/>

# 🔐 Solidity Portfolio

### Real-world smart contracts. Production-ready. Fully documented.

A curated collection of Solidity smart contracts covering tokens, DeFi primitives,
NFTs and advanced patterns — each in its own repo with tests, deployment and full docs.

<br/>

[![Solidity](https://img.shields.io/badge/Solidity-0.8.28-363636?style=for-the-badge&logo=solidity&logoColor=white)](https://soliditylang.org/)
[![Hardhat](https://img.shields.io/badge/Hardhat-3.x-f7df1e?style=for-the-badge)](https://hardhat.org/)
[![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-5.x-4e5ee4?style=for-the-badge&logo=openzeppelin&logoColor=white)](https://openzeppelin.com/)
[![Ethers.js](https://img.shields.io/badge/Ethers.js-v6-2535a0?style=for-the-badge)](https://ethers.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-c792ea?style=for-the-badge)](LICENSE)

<br/>

> Each contract lives in its **own independent repository** with full documentation:
> `README.md` · `STEPS.md` · `EXPLANATION.md` · `EXAMPLE.md`

<br/>

</div>

---

## 💼 Looking to hire?

I build **production-ready smart contracts** — tested, documented, and verified on-chain.

If you need any of the following, you're in the right place:

- 🪙 **ERC-20 tokens** — standard, mintable, burnable, or with transfer tax
- 🔒 **Vesting & escrow** — cliff schedules, trustless multi-party agreements
- 📈 **Staking contracts** — deposit/reward mechanics for your protocol
- 🖼️ **NFT collections** — ERC-721 with IPFS metadata, royalties, or Merkle whitelist presale
- 🏛️ **DAO & governance** — on-chain proposals and voting
- ⚡ **Flash loan integrations** — Aave V3 receivers and arbitrage logic
- 🔐 **Security-first code** — reentrancy guards, access control, gas optimization

Every contract in this portfolio is **open source, fully tested with Hardhat, and verified on Etherscan/BscScan**.

> 📩 Available for freelance work — [Upwork](#) · [Fiverr](#) · [LinkedIn](https://linkedin.com/in/hectorob)

---

## ⚙️ Global Prerequisites

Before diving into any contract repo, make sure you have:

| Requirement | Version | Notes |
|-------------|---------|-------|
| [Node.js](https://nodejs.org/) | v22+ | Required by Hardhat 3 |
| npm | v7+ | Comes with Node.js |
| Terminal | Any | PowerShell, bash or zsh |
| [MetaMask](https://metamask.io/) | Latest | Testnet wallet for deployments |
| [Alchemy](https://alchemy.com/) account | Free tier | RPC endpoint for testnets |
| [Etherscan](https://etherscan.io/) API key | Free tier | Contract verification |
| Sepolia ETH | Any amount | [Get free ETH here](https://cloud.google.com/application/web3/faucet/ethereum/sepolia) |

> Each repo has its own `STEPS.md` with exact setup commands from scratch.

---

## 🗂️ Repository Structure

```
HEO-80/
├── solidity-portfolio/          ← This repo (index + links)
│
├── 📦 Block 1 — Tokens
│   ├── erc20-custom/            ✅ done
│   ├── erc20-tax-token/         ✅ done
│   └── deploy-verify-guide/     ✅ done
│
├── 📦 Block 2 — DeFi Contracts
│   ├── token-vesting/           ✅ done
│   ├── escrow-simple/           ✅ done
│   └── staking-contract/        ✅ done
│
├── 📦 Block 3 — NFTs
│   ├── erc721-basic/            ✅ done
│   ├── nft-royalties/           ✅ done
│   └── nft-whitelist-merkle/    ✅ done
│
└── 📦 Block 4 — Advanced
    ├── multisig-wallet/         ✅ done
    ├── dao-voting/              ✅ done
    └── flashloan-receiver/      ✅ done
```

---

## 📦 Block 1 — Tokens

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| ERC-20 Custom | Mintable, burnable token with ownership control | ✅ Done | [erc20-custom](https://github.com/HEO-80/erc20-custom) |
| ERC-20 Tax Token | Transfer tax with configurable treasury wallet | ✅ Done | [erc20-tax-token](https://github.com/HEO-80/erc20-tax-token) |
| Deploy & Verify Guide | Step-by-step Etherscan verification walkthrough | ✅ Done | [deploy-verify-guide](https://github.com/HEO-80/deploy-verify-guide) |

---

## 📦 Block 2 — DeFi Contracts

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| Token Vesting | Cliff + linear release, multi-beneficiary | ✅ Done | [token-vesting](https://github.com/HEO-80/token-vesting) |
| Escrow Simple | Trustless escrow between two parties | ✅ Done | [escrow-simple](https://github.com/HEO-80/escrow-simple) |
| Staking Contract | Deposit tokens, earn time-based rewards | ✅ Done | [staking-contract](https://github.com/HEO-80/staking-contract) |

---

## 📦 Block 3 — NFTs

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| ERC-721 Basic | NFT collection with IPFS metadata | ✅ Done | [erc721-basic](https://github.com/HEO-80/erc721-basic) |
| NFT Royalties | On-chain royalties via ERC-2981 standard | ✅ Done | [nft-royalties](https://github.com/HEO-80/nft-royalties) |
| NFT Whitelist Merkle | Presale minting with Merkle tree whitelist | ✅ Done | [nft-whitelist-merkle](https://github.com/HEO-80/nft-whitelist-merkle) |

---

## 📦 Block 4 — Advanced

| Contract | Description | Status | Repo |
|----------|-------------|--------|------|
| Multisig Wallet | M-of-N multi-signature wallet | ✅ Done | [multisig-wallet](https://github.com/HEO-80/multisig-wallet) |
| DAO Voting | On-chain governance with proposals and voting | ✅ Done | [dao-voting](https://github.com/HEO-80/dao-voting) |
| Flash Loan Receiver | Aave V3 flash loan integration | ✅ Done | [flashloan-receiver](https://github.com/HEO-80/flashloan-receiver) |

---

## 🧰 Each Repository Contains

```
contract-name/
├── contracts/
│   └── ContractName.sol      # Main contract
├── test/
│   └── ContractName.test.js  # Full test suite
├── README.md                 # Overview and quickstart
├── STEPS.md                  # Exact commands used
├── EXPLANATION.md            # How the contract works in detail
└── EXAMPLE.md                # Real-world use case and scenario
```

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white"/>
<img src="https://img.shields.io/badge/Hardhat-f7df1e?style=for-the-badge&logoColor=black"/>
<img src="https://img.shields.io/badge/OpenZeppelin-4e5ee4?style=for-the-badge&logo=openzeppelin&logoColor=white"/>
<img src="https://img.shields.io/badge/Ethers.js-2535a0?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Mocha-8d6748?style=for-the-badge&logo=mocha&logoColor=white"/>
<img src="https://img.shields.io/badge/Chai-a30701?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Aave-b6509e?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Sepolia-6f3ff5?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Etherscan-21325b?style=for-the-badge"/>

</div>

---

## 📊 Portfolio Stats

| Metric | Value |
|--------|-------|
| Total contracts | 12 |
| Total tests | 74+ passing |
| Blocks covered | 4 |
| Standards implemented | ERC-20, ERC-721, ERC-2981 |
| Protocols integrated | Aave V3, OpenZeppelin, MerkleTree |

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

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-c792ea?style=for-the-badge)](LICENSE)

---

<div align="center">

*Built contract by contract. Tested. Documented. Deployed.*

</div>
