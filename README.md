# Awesome Fhenix 🔐

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Twitter Follow](https://img.shields.io/twitter/follow/fhenix?style=social)](https://twitter.com/fhenix)

> A curated list of amazing Fully Homomorphic Encryption (FHE) resources, tools, and projects for building privacy-preserving applications on Fhenix.

[Fhenix](https://www.fhenix.io/) is an R&D-driven Ethereum infrastructure company delivering a full-stack confidential compute tooling suite. Cofhe, an FHE coprocessor enables developers to build confidential smart contracts using Fully Homomorphic Encryption (FHE), allowing computations on encrypted data without ever revealing it.

## 🚀 Quick Start
- **New to FHE?** Start with [FHE & Cryptography Fundamentals](#fhe--cryptography-fundamentals)
- **Ready to build?** Jump to [Getting Started](#getting-started)
- **Looking for examples?** Check out [Code Examples](#-code-examples)
- **Need help?** Visit [Get Connected](#-get-connected)

## Contents

- [Official Resources](#-official-resources)
- [Core Libraries & SDKs](#-core-libraries--sdks)
- [Developer Tools](#-developer-tools)
- [Learning Resources](#-learning-resources)
- [Code Examples](#-code-examples)
- [Ecosystem Projects](#-ecosystem-projects)
- [Design Partners & Case Studies](#-design-partners--case-studies)
- [Research & Publications](#-research--publications)
- [Get Connected](#-get-connected)

---

## 📚 Official Resources

### Documentation
- [Fhenix Developer Docs](https://docs.fhenix.io/) - Complete developer documentation for building FHE-enabled smart contracts
- [CoFHE Architecture Guide](https://docs.fhenix.io/deep-dive/cofhe-components/overview) - Technical deep dive into CoFHE components
- [API Reference](https://docs.fhenix.io/fhe-library/reference/fhe-sol) - Complete FHE library API documentation

### Network Resources
Fhenix is live on the following testnets: **Base**, **Arbitrum**, and **Ethereum Sepolia**.

#### Faucets
- Base Sepolia Faucet - Base testnet tokens
  -  [Alchemy Base Sepolia](https://www.alchemy.com/faucets/base-sepolia) - Get 0.1 ETH
- Arbitrum Sepolia Faucet - Arbitrum testnet tokens
  - [Alchemy Arbitrum Sepolia](https://www.alchemy.com/faucets/arbitrum-sepolia) - Get 0.1 ETH 
- Ethereum Sepolia Faucet - Ethereum Sepolia testnet tokens
  - [Alchemy Sepolia](https://www.alchemy.com/faucets/ethereum-sepolia) - Get 0.5 ETH 
  - [Testnet Help Sepolia](https://testnet.help/en/ethfaucet/sepolia) - Get 0.0001 ETH 
  - [Google Cloud Sepolia](https://cloud.google.com/application/web3/faucet/ethereum/sepolia) - Get 0.05 ETH
#### Bridges Testnet
  - [Superchain](https://superbridge.app/base-sepolia) - A web interface for bridging assets across Superchain-based testnet networks such as Base Sepolia
  - [Arbitrum Bridge](https://portal.arbitrum.io/bridge) - The official bridge for transferring assets between Ethereum and Arbitrum networks
### GitHub
- [FhenixProtocol Organization](https://github.com/fhenixprotocol/) - Official GitHub organization
- [cofhe-contracts](https://github.com/FhenixProtocol/cofhe-contracts) - Solidity FHE library for smart contracts
- [cofhejs](https://github.com/FhenixProtocol/cofhejs) - JavaScript/TypeScript SDK for client-side encryption

---

## 💻 Core Libraries & SDKs

- [cofhe-contracts](https://github.com/FhenixProtocol/cofhe-contracts) - Solidity FHE library for performing operations on encrypted data in smart contracts
  - Related: [CoFHE Architecture Guide](https://docs.fhenix.io/deep-dive/cofhe-components/overview) | [API Reference](https://docs.fhenix.io/fhe-library/reference/fhe-sol)
- [cofhejs](https://github.com/FhenixProtocol/cofhejs) - JavaScript/TypeScript SDK for client-side encryption, permit management, and decryption

---

## 🛠️ Developer Tools

- [cofhe-hardhat-plugin](https://github.com/FhenixProtocol/cofhe-hardhat-plugin) - Hardhat integration for FHE development
- [cofhe-hardhat-starter](https://github.com/fhenixprotocol/cofhe-hardhat-starter) - Starter template for building FHE contracts with Hardhat
  - Related: [Quick Start Guide](https://docs.fhenix.io/fhe-library/introduction/quick-start)

### Vibe Coding
- [Neo FHE AI Assistant](https://fhenix.notion.site/neo-fhe-ai-assistant) - AI-powered coding assistant for FHE development
  - [GitHub Repository](https://github.com/marronjo/fhe-assistant)
  - [Documentation](https://cofhe-docs.fhenix.zone/get-started/build-with-ai/ai-assistant) - Build with AI guide

---

## 📖 Learning Resources

### FHE & Cryptography Fundamentals
*Foundational resources for understanding Fully Homomorphic Encryption and cryptographic concepts.*

- [Crypto 101](https://www.crypto101.io/) - An introductory book that explains fundamental cryptographic concepts in a clear and accessible way
- [Fully Homomorphic Encryption Textbook](https://fhetextbook.github.io/) - An open textbook providing a comprehensive introduction to fully homomorphic encryption, including mathematical foundations and constructions
- [Lattices in Cryptography Lecture Notes](https://github.com/cpeikert/LatticesInCryptography) - Graduate-level lecture notes from Chris Peikert’s seminar course covering lattice-based cryptography
- [Theory of Cryptography Lecture Notes](https://github.com/cpeikert/TheoryOfCryptography) - Lecture notes from Chris Peikert's graduate-level Theory of Cryptography course covering foundational cryptographic concepts

### Getting Started
- [Quick Start Guide](https://docs.fhenix.io/fhe-library/introduction/quick-start) - Set up your development environment and build your first FHE contract
- [Your First FHE Contract](https://docs.fhenix.io/tutorials/your-first-fhe-contract) - Beginner tutorial building an encrypted counter

### Intermediate
- [Adding FHE to Existing Contracts](https://docs.fhenix.io/tutorials/adding-fhe-to-existing-contract) - Migrate traditional contracts to use FHE
- [ACL Usage Examples](https://docs.fhenix.io/tutorials/acl-usage-examples) - Implement access control for encrypted data
- [Private Liquidity Tracker - Encrypted Uniswap V4 Hook Tutorial](https://fhenix.notion.site/Beginner-Hooks-Tutorial-27a8471c7c22806bbf34e7436656c66f) - Beginner tutorial for building encrypted Uniswap V4 hooks
  - Related: [Hooks & Integrations](#hooks--integrations) code example

### Advanced
- [CoFHE Deep Dive](https://docs.fhenix.io/deep-dive/cofhe-components/overview) - Understanding the CoFHE architecture
- [Gas Optimization](https://docs.fhenix.io/fhe-library/core-concepts/gas-and-benchmarks) - Best practices for efficient FHE operations

---

## 💻 Code Examples

### Confidential Tokens
- [FHERC20](https://github.com/FhenixProtocol/fhenix-confidential-contracts/tree/main/contracts) - Encrypted ERC20 token implementation with private balances

### Hooks & Integrations
- [Private Liquidity Tracker - Encrypted Uniswap V4 Hook Tutorial](https://fhenix.notion.site/Beginner-Hooks-Tutorial-27a8471c7c22806bbf34e7436656c66f) - Beginner tutorial for building encrypted Uniswap V4 hooks
  - Related: [Uniswap V4 Hooks Tutorial](#intermediate) in Learning Resources

### Voting & Governance
- [Private Voting Template](https://docs.fhenix.io/examples/) - Encrypted voting system example

### Auctions & DeFi
- [Blind Auction](https://docs.fhenix.io/examples/) - Privacy-preserving auction implementation

### Real-World Patterns
*Common patterns and architectural approaches for building FHE applications.*

- [FHERC20](https://github.com/FhenixProtocol/fhenix-confidential-contracts/tree/main/contracts) - Private token balances pattern
- [Blind Auction](https://docs.fhenix.io/examples/) - Privacy-preserving auction pattern
- [Private Voting Template](https://docs.fhenix.io/examples/) - Encrypted voting pattern

---

## 🏗️ Ecosystem Projects

*Projects and applications built on Fhenix will be listed here as they emerge.*

---

## 🌟 Design Partners & Case Studies

*Real-world implementations showcasing how partners are building privacy-preserving applications on Fhenix.*

- Private Prediction Market - Privacy-preserving prediction market implementation
  - [Case Study](https://x.com/fhenix/status/2008948922518294802)
- [AlphaEngine](https://www.alphaengine.trade/dashboard?view=builder) - Encrypted trading and computation platform
  - [Case Study](https://x.com/fhenix/status/1995556468586938439)
- [Fluton](https://testnet.fluton.io/) - Real-world FHE application showcase
  - [Case Study](https://x.com/fhenix/status/1981662128810467778)
- [Lunarys](https://dex-fhe.vercel.app/) - Decentralized exchange with FHE capabilities
- [Felend](https://app.felend.xyz/) - FHE-enabled application on Fhenix
- [Privara](https://privara.xyz/) - Privacy-preserving platform built on Fhenix

---

## 🔬 Research & Publications

*Academic papers and technical publications related to FHE and Fhenix.*

### Technical Papers
- [DBFV White Paper](https://eprint.iacr.org/2025/2321) - Distributed Bootstrapping for FHE in Verifiable Decryption
- [Threshold Decryption Network White Paper](https://eprint.iacr.org/2025/1781) - Decentralized threshold decryption protocol for FHE

### Articles & Analysis
- [The Different Stages of Privacy: A Taxonomy](https://www.fhenix.io/blog/the-different-stages-of-privacy-a-taxonomy) - By Guy Zyskind: Classification framework for privacy technologies

---

## 🤝 Get Connected

- [Twitter](https://twitter.com/fhenix) - Official Twitter account
- [Discord](https://discord.gg/fhenix) - Developer community
- [Telegram](https://t.me/+Sky3j5VKlGk5NjRh) - Fhenix Early Adopters group
- [GitHub Discussions](https://github.com/fhenixprotocol/awesome-fhenix/discussions) - Community discussions
- Devrel: [@laurenmxv](https://t.me/laurenmxv) - Contact for developer relations

---

## 📝 What's New

*Recent additions and updates to awesome-fhenix.*

- Added Theory of Cryptography lecture notes to FHE & Cryptography Fundamentals
- Added Hooks & Integrations subsection with Uniswap V4 tutorial
- Added Real-World Patterns section
- Added cross-references between related resources
- Improved navigation with quick start links

---

## 📋 Changelog

### 2025-01
- Added Neo FHE AI Assistant to Developer Tools
- Added Private Liquidity Tracker tutorial
- Added Design Partners & Case Studies section
- Added Research & Publications with technical papers
- Organized network resources for Base, Arbitrum, and Sepolia testnets

---

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[CC0-1.0](LICENSE)

