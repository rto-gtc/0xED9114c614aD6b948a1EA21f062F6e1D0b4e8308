# Verified Ethereum Contract Source Code (Mainnet)

This repository contains the verified source code and ABI interface of an ERC-20 contract, directly obtained from [Etherscan.io](https://etherscan.io).

## Contract Details

- **Contract Address:** `0xED9114c614aD6b948a1EA21f062F6e1D0b4e8308`
- **Network:** Ethereum Mainnet (Chain ID: 1)
- **Verification:** Etherscan
- **Type:** ERC-20 (likely)
- **Etherscan Link:** [View on Etherscan](https://etherscan.io/address/0xED9114c614aD6b948a1EA21f062F6e1D0b4e8308)

## Repository Contents

- **`ABI.json`** – Binary Application Interface (ABI), required for interacting with the contract using web3 tools (e.g., web3.js, ethers.js).  
- **`contracts/Fox24coin.sol`** (or other main file) – Main Solidity source code file.  
- **`@openzeppelin/...`** – Library files imported by the main contract, included for completeness.

## Publishing Tools

The code was published using a custom PowerShell script `git-publish-only.ps1`, which automates the process:

1. Verifies the existence of local source files.  
2. Initializes a local Git repository (if needed).  
3. Forces the main branch `main` on GitHub to ensure immediate visibility of the files.
