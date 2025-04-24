# SmarDex Contracts

[![Tests](https://github.com/SmarDex-Ecosystem/dex-smart-contracts/actions/workflows/ci.yml/badge.svg)](https://github.com/SmarDex-Ecosystem/dex-smart-contracts/actions/workflows/ci.yml)

## Description

Uniswap-like dex protocol that allow a better incentivization for liquidity providers.
This repo includes an SDEX pool (rewards comes from the dex) and farming capabilities (rewards requires external income source).

## Website

https://smardex.io

## Documentation

See the link to the technical paper or visit the Smardex Developer docs

- https://www.academia.edu/98332701/The_SMARDEX_Protocol_A_Novel_Solution_to_Impermanent_Loss_in_Decentralized_Finance
- https://docs.smardex.io

## Getting Started

### Installation

### Foundry

To install Foundry, run the following commands in your terminal:

```bash
curl -L https://foundry.paradigm.xyz | bash
source ~/.bashrc
foundryup
```

### Dependencies

To install existing dependencies, run the following commands:

```bash
forge soldeer install
npm install
```

### Compile

`forge compile`

## Foundry Documentation

For comprehensive details on Foundry, refer to the [Foundry book](https://book.getfoundry.sh/).

## Contributors

Implemented by [Stéphane Ballmer](https://github.com/sballmer), [Paul-Alexandre Tessier](https://github.com/Paulalex85), [Côme Pecorari](https://github.com/cpecorari), [Léo Fasano](https://github.com/Yashiru), [Yoan Capron](https://github.com/CapronYoan), [Sami Darnaud](https://github.com/samooyo)

## Licensing

The primary license for Smardex is the Business Source License 1.1 (BUSL-1.1), see [LICENSE](LICENSE). However, smart-contract files imported from other projects do respect their original license (GPL-3, GPL-2, MIT, ...)

- All files under `periphery` are GPL-2
- All files under `core` except `core/libraries/SmardexLibrary.sol` are GPL-2
- `contracts/rewards/FarmingRange.sol` is licensed under MIT, fork from Alpaca Finance
