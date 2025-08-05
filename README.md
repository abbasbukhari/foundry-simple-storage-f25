# Solidity Smart Contract Project — Foundry + Cyfrin Course

This repository contains my first professional Solidity project built while following **Patrick Collins' Cyfrin Foundry & Smart Contract Development Course**.  
It serves as both a **learning sandbox** and the foundation for my journey into **smart contract auditing** and **DeFi security**.

---

## 🚀 About the Project

This project is a hands-on implementation of Ethereum smart contracts using **Foundry**, a fast and modern toolkit for Solidity development.  
I am building, testing, and deploying contracts while applying professional development workflows such as **version control, gas optimization, and security best practices**.

Key goals for this project:
- Learn and apply **Solidity fundamentals** in a professional environment.
- Use **Foundry** for development, testing, and deployment.
- Practice **secure smart contract patterns**.
- Prepare for **real-world DeFi auditing** work.

---

## 🛠 Tech Stack

- **Foundry** (Forge, Cast, Anvil, Chisel)
- **Solidity** (^0.8.x)
- **Ethereum Virtual Machine (EVM)**
- **GitHub** for version control & collaboration

---

## 📦 Foundry Toolkit Overview

- **Forge**: Ethereum testing framework (like Hardhat/Truffle).
- **Cast**: CLI tool for interacting with contracts & sending transactions.
- **Anvil**: Local Ethereum test node.
- **Chisel**: Solidity REPL for quick experiments.

---

## 📚 Resources
- [Foundry Documentation](https://book.getfoundry.sh/)
- [Cyfrin Solidity Course](https://updraft.cyfrin.io/)

---

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
