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

