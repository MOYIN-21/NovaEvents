# NovaEvents Utility Scripts

This directory contains automation scripts for deploying and verifying the NovaEvents Soroban smart contract.

## Available Scripts

| Script | Purpose |
|---|---|
| [`deploy-testnet.sh`](./deploy-testnet.sh) | Builds the contract WASM, deploys it to the Stellar testnet, initializes it with admin and token addresses, and prints the deployed contract ID. |
| [`e2e_lifecycle.sh`](./e2e_lifecycle.sh) | Runs an end-to-end integration test driving a complete event lifecycle (deploy, init, ticket sales, transfers, redemption, sponsorship, and payouts) against a local sandbox or testnet. |

## Usage

Each script includes embedded help and configuration flags. Pass `--help` to any script for full usage details and available environment variables:

```bash
# View deployment options and flags
scripts/deploy-testnet.sh --help

# View end-to-end lifecycle test options
scripts/e2e_lifecycle.sh --help
```
