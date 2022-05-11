# awesome-cryptos

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme)

> Inspired by [awesome-openzepplin](https://github.com/OpenZeppelin/awesome-openzeppelin/tree/d6190b6fdf099476648eebd0f6bfb50e31597016), resources for a better understanding in cryptos.

Learning is hard, especially in cryptos, please take you time and enjoy.

## Table of Contents

- [awesome-cryptos](#awesome-cryptos)
  - [Table of Contents](#table-of-contents)
  - [101](#101)
    - [Concept](#concept)
    - [Programming Languages](#programming-languages)
  - [Practical](#practical)
  - [Learn By Example](#learn-by-example)
  - [Advanced](#advanced)
    - [Bitcoin](#bitcoin)
    - [Ethereum](#ethereum)
  - [Security](#security)
  - [Further Reading](#further-reading)

## [101][101]

[101]: https://en.wikipedia.org/wiki/101_(slang)

### Concept

- [Foundational topics](https://ethereum.org/en/developers/docs/intro-to-ethereum/), the basic concept of ethereum.
- [what is ethereum](https://ethereum.org/en/what-is-ethereum/)

### Programming Languages

- [Solidity](https://docs.soliditylang.org/en/latest/), an object-oriented, high-level language for implementing smart contracts.
- [Vyper](https://vyper.readthedocs.io/en/stable/), a contract-oriented, pythonic programming language that targets the Ethereum Virtual Machine (EVM).
- [Yul](https://docs.soliditylang.org/en/latest/yul.html), an intermediate language that can be compiled to bytecode for different backends.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) / [TypeScript](https://www.typescriptlang.org/docs/handbook/intro.html), the front-end language for DAPP, an interface to interact with smart contract.
- Advanced:
  - [Rust](https://www.rust-lang.org/learn)
  - [Go](https://go.dev/doc/)
  - [WASM](https://webassembly.org/getting-started/developers-guide/)

## [Practical](https://en.wiktionary.org/wiki/practical)

- Toolkits
  - [Truffle](https://trufflesuite.com/docs/truffle/quickstart/), oldest one, not recommand.
  - [Hardhat](https://hardhat.org/getting-started/), faster and wild used.
  - [Brownie](https://eth-brownie.readthedocs.io/en/stable/), build with python.
  - [Foundry](https://book.getfoundry.sh/), build with rust, the fastest one, with debug mode.

- Books
  - [区块链以太坊DApp开发实战](https://github.com/oneforalone/awesome-cryptos/res/blockchain-dapp-development.pdf), by 林冠宏. Most focus on building an Ethereum Relayer.

- Posts
  - Hello World Series, by Albert
    - [Part 1 - Hello World](https://docs.alchemy.com/alchemy/tutorials/hello-world-smart-contract)
    - [Part 2 - Interacting with a Smart Contract](https://docs.alchemy.com/alchemy/tutorials/hello-world-smart-contract/interacting-with-a-smart-contract)
    - [Part 3 - Submitting your Smart Contract to Etherscan](https://docs.alchemy.com/alchemy/tutorials/hello-world-smart-contract/submitting-your-smart-contract-to-etherscan)
  - [OpenZeppelin guide for developing smart contract](https://docs.openzeppelin.com/learn/), by OpenZeppelin.
  - [Best Practices for Smart Contract Development](https://yos.io/2019/11/10/smart-contract-development-best-practices/), by Yos Riady.

- Videos
  - Hello World Series, by Albert
    - [Part 1 - Hello World](https://youtu.be/g73EGNKatDw)
    - [Part 2 - Interacting with a Smart Contract](https://youtu.be/sQJ-XQBzEuc)
    - [Part 3 - Submitting your Smart Contract to Etherscan](https://youtu.be/x1a5lrW-9fo)
  - [Solidity in 2 hours](https://youtu.be/ipwxYa-F1uY), by Gregory.
  - [Solidity, Blockchain, and Smart Contract Course](https://youtu.be/M576WGiDBdQ), by Patrick Collins.

## [Learn By Example](https://en.wikipedia.org/wiki/Learning-by-doing)

- [CryptosZombies](https://cryptozombies.io/en/course), by Loom. A tutorial teaching how to build a game on Ethereum using solidity step by step.

## [Advanced](https://en.wiktionary.org/wiki/advance)

### Bitcoin

- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook), by Andreas Antonopoulos. Covers the fundamentals of Bitcoin.
- [Learn me a bitcoin](https://learnmeabitcoin.com/), by Greg Walker. Demonstrates Bitcoin details with charts.
- [Bitcoin Developer Guides](https://developer.bitcoin.org/devguide/index.html), by Bitcoin Project Team. Developer view of Bitcoin.
- [Bitcoin Reference](https://developer.bitcoin.org/reference/index.html), by Bitcoin Project Team. Official reference.

### Ethereum

- Books
  - [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook), by Andreas Antonopoulos. Covers the fundamentals of Ethereum.

- Posts
  - Ethereum in Depth series, by OpenZeppelin. A brief introduce of a Solidity Contract with EVM OPCODES.
    - [Part 1 - Basics](https://blog.openzeppelin.com/ethereum-in-depth-part-1-968981e6f833)
    - [Part 2 - Data Management](https://blog.openzeppelin.com/ethereum-in-depth-part-2-6339cf6bddb9/)

  - Deconstructing a Solidity Contract series, by OpenZeppelin. An deep overview of a Solidity Contract, explains the construct of a smart contract in low-level language, i.e. EVM OPCODES.
    - [Part 1 - Introduction](https://blog.openzeppelin.com/deconstructing-a-solidity-contract-part-i-introduction-832efd2d7737/)
    - [Part 2 - Runtime v.s Creation Bytecode](https://blog.zeppelin.solutions/deconstructing-a-solidity-contract-part-ii-creation-vs-runtime-6b9d60ecb44c)
    - [Part 3 - Function Selector](https://blog.zeppelin.solutions/deconstructing-a-solidity-contract-part-iii-the-function-selector-6a9b6886ea49)
    - [Part 4 - Function Wrappers](https://blog.zeppelin.solutions/deconstructing-a-solidity-contract-part-iv-function-wrappers-d8e46672b0ed)
    - [Part 5 - Function Bodies](https://blog.zeppelin.solutions/deconstructing-a-solidity-contract-part-v-function-bodies-2d19d4bef8be)
    - [Part 6 - The Metadata Hash](https://blog.zeppelin.solutions/deconstructing-a-solidity-contract-part-vi-the-swarm-hash-70f069e22aef)

  - EVM Deep Dives series, by noxx. A brief view of contract in EVM OPCODES, detailed in function selector, memory and storage in EVM.
    - [Part 1 - Function Selector Deep Dive](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy?s=r)
    - [Part 2 - Memory in the EVM](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-d6b?s=r)
    - [Part 3 - Storage in the EVM](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-3ea?s=r)
    - [Part 4 - Storage Opcodes in Geth](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-5a5?s=r)

  - [A Playdate with the EVM](https://femboy.capital/evm-pt1), by Femboy Capital. A blogpost that give a basic overview of the EVM, explaining how stack machines work before showing us how to write some assembly.

  - [EVM Assembly](https://jeancvllr.medium.com/solidity-tutorial-all-about-assembly-5acdfefde05c), by Jeancvllr. A brief introduce of EVM Assembly.

  - [Understanding Ethereum Smart Contract Storage](https://programtheblockchain.com/posts/2018/03/09/understanding-ethereum-smart-contract-storage/), by program the blockchain. A blogpost that gives a great overview of the data structures of contract storage.

- Videos
  - [EVM Explained](https://youtu.be/kCswGz9naZg), by Jordan McKinney. An video explanation of the EVM both from an individual contract level & the overall world state of Ethereum.
  - [Solidity to Bytecode, Memory & Storage](https://youtu.be/RxL_1AfV7N4), by Peter Robinson. An video run-through of how a contract is compiled to bytecode, handles its memory/storage & is interpreted by the EVM.
  - [Ethereum Under The Hook: Algorithms And Data Structures](https://youtu.be/OxofT39TJgg)

- Presentation Slides
  - [Ethereum EVM illustrated](https://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf), by Takenobu T. A brief introduction of Ethereum.

- Misc
  - [EVM Playground for OPCODES](https://www.evm.codes/), by comitylabs. An interactive website & EVM playground. One of the most valuable tools for EVM developers. It contains a list of all opcodes, as well as description and a playground where you can observe how they work.
  - [EVM puzzles](https://github.com/fvictorio/evm-puzzles), by Fvictorio. A collection of interactive EVM puzzles on GitHub, these are great to help consolidate your learnings from other resources.

## [Security](https://en.wikipedia.org/wiki/Computer_security)

- Books
  - [区块链黑暗森林自救手册](https://github.com/slowmist/Blockchain-dark-forest-selfguard-handbook) by 余弦. A selfguard handbook to teach you master the security of your cryptocurrency.

- Posts
  - [Ethereum is a Dark Forest](https://www.paradigm.xyz/2020/08/ethereum-is-a-dark-forest), by Dan Robinson, Georgios Konstantopoulos. A brief introduction about Security in Ethereum.
  - [Escaping the Dark Forest](https://samczsun.com/escaping-the-dark-forest/), by samczsun. A journal of a hacker(samczsun) who rescue over 25,000 Ether from a vulnerable smart contract.
  - [Maximal Extractable Value (MEV)](https://ethereum.org/en/developers/docs/mev/), by ethereum contributors. An introduction of MEV.

## [Further Reading](https://en.wikipedia.org/wiki/Wikipedia:Further_reading)

- [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
- [Ethereum Yellowpaper](https://ethereum.github.io/yellowpaper/paper.pdf)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
- [Polkadot](https://wiki.polkadot.network/docs/getting-started)
- [Cosmos](https://docs.cosmos.network/main/intro/overview.html)
- [Substrate](https://docs.substrate.io/v3/getting-started/overview/)
- [LayerZero](https://layerzero.network/)
- [NEAR](https://near.org/papers/the-official-near-white-paper/)
- [Solana](https://docs.solana.com/)
- [Blockchain Oracle](https://chain.link/education/blockchain-oracles)
- [ChainLink](https://research.chain.link/whitepaper-v2.pdf)
