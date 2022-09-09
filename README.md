

![Screenshot from 2022-09-10 00-59-40](https://user-images.githubusercontent.com/3880512/189429422-22182525-039f-4d13-80d4-19d3b52c6030.png)

https://gojuno.xyz/

https://docs.starknet.io/

https://docs.starknet.io/docs/L1-L2%20Communication/token-bridge

### Contents

- [Resources](#resources)
  - [Official](#official)
  - [Ecosystem](#ecosystem)
  - [Tutorials](#tutorials)
  - [Articles](#articles)
  - [Security](#security)
  - [Examples](#examples)
  - [Educational](#educational)
  - [Deployed on StarkNet Mainnet](#built--deployed-on-starknet)
  - [Templates](#templates)
  - [Books](#books)
  - [Practice](#practice)
  - [Jobs](#jobs)
- [Libraries](#libraries)
- [Tools](#tools)
  - [General](#general)
  - [Utility](#utility)
  - [Audit](#audit)
- [Editor Plugins](#editor-plugins)
  - [Vim](#vim)
  - [Visual Studio Code](#visual-studio-code)
- [License](#license)

## Resources

#### Official

- [StarkNet and Cairo Documentation](https://www.cairo-lang.org/docs/index.html) -
  Official Documentation.
- [Setting up the environment](https://www.cairo-lang.org/docs/quickstart.html) -
  How to install Cairo and StarkNet.
- [How Cairo Works](https://www.cairo-lang.org/docs/how_cairo_works/index.html) -
  Low-level explanation of Cairo's mechanics.
- [Hello StarkNet](https://www.cairo-lang.org/docs/hello_starknet/index.html) -
  Tutorial for writing and deploying a contract.
- [Hello Cairo](https://www.cairo-lang.org/docs/hello_cairo/index.html) -
  Tutorials for writing various simple Cairo contracts.
- [Cairo Reference](https://www.cairo-lang.org/docs/reference/index.html) -
  Explanation of Cairo's syntax
- [Cairo – a Turing-complete STARK-friendly CPU architecture](https://eprint.iacr.org/2021/1063.pdf) -
  Cairo Whitepaper
- [A verified algebraic representation of Cairo program execution](https://arxiv.org/abs/2109.14534) -
  Proof Cairo's soundness using the
  [Lean proof assistant](<https://en.wikipedia.org/wiki/Lean_(proof_assistant)>)
- [Cairo Playground](https://www.cairo-lang.org/playground/) - In-browser Cairo
  IDE, examples and puzzles
- [StarkNet Voting Workshop](https://starkware.notion.site/starkware/StarkNet-Voting-Workshop-b61ef5f4a62d45af86892cba3158f7e6) -
  End to end tutorial on building a voting app
- [YouTube channel](https://www.youtube.com/channel/UCnDWguR8mE2oDBsjhQkgbvg/playlists) - Official StarkWare YouTube channel.

#### Ecosystem

- [StarkNet Ecosystem](https://starknet-ecosystem.com) -
  A [community-driven](https://github.com/419Labs/starknet-ecosystem.com) initiative to showcase projects and teams building on StarkNet.

#### Tutorials
- [Full-Stack StarkNet](https://github.com/sambarnes/fullstack-starknet) - Tutorials introducing a little bit of everything in a DApp.
- [Interactive Tutorials for StarkNet Development](https://github.com/onlydustxyz/starklings) - Interactive tutorials teaching all the different concepts in Cairo from beginner to advanced.
- [Unit Testing in StarkNet](https://perama-v.github.io/cairo/examples/unit_test/) -
  Using [`pytest`](https://docs.pytest.org/en/6.2.x/) to test contracts
- [Managing StarkNet deployments using Nile ⛵️✨](https://medium.com/@martriay/manage-your-starknet-deployments-with-nile-%EF%B8%8F-e849d40546dd)
- [starknet-cairo-101](https://github.com/starknet-edu/starknet-cairo-101) - Interactive Cairo workshop using [Voyager](https://voyager.online/) with puzzles and tokens as prizes.
- [starknet-erc20](https://github.com/starknet-edu/starknet-erc20) - Learn about the ERC20 standard and how to deploy your own token, and collect points
- [starknet-erc721](https://github.com/starknet-edu/starknet-erc721) - Learn about the ERC721 standard and how to deploy your own NFT
- [starknet-messaging-bridge](https://github.com/starknet-edu/starknet-messaging-bridge) - Learn how to build your own bridge between Ethereum and StarkNet
- [starknet-accounts](https://github.com/starknet-edu/starknet-accounts) - Discover the wonders of account abstraction and create your own smart wallet
- [Debugging](https://github.com/starknet-edu/starknet-debug) - Debug contracts in an efficient way

#### Articles

- [Going all in - starknet](https://koopxyz.notion.site/going-all-in-starkware-f250983d562c454384384a5408bddf9c)
  Notion site of helpful resources  
- [Perama's Blog](https://perama-v.github.io/cairo/intro/) - Large set of
  educational StarkNet / Cairo resources
- [Practical StarkNet lessons learned](https://hackmd.io/@RoboTeddy/BJZFu56wF) -
  Helpful tips for new StarkNet/Cairo programmers
- [Cairo Common Library](https://perama-v.github.io/cairo/cairo-common-library/) -
  Docs for the Cairo Common Library (stdlib equivalent)

- [Cairo Concepts Overview](https://perama-v.github.io/cairo/description/) -
  High level overview of concepts encountered in the Cairo ecosystem (Ethereum,
  Smart Contracts, Decentralization, Scaling, L2, Rollups, ZKPs etc.)
- [Account Abstraction](https://perama-v.github.io/cairo/account-abstraction/) -
  Explanation of StarkNet's account abstraction
- [Test Accounts](https://perama-v.github.io/cairo/examples/test_accounts/) -
  Explanation of building test accounts

#### Security

- [ChainSecurity DAI Bridge Audit](https://chainsecurity.com/wp-content/uploads/2021/12/ChainSecurity_MakerDAO_StarkNet-DAI-Bridge_audit.pdf) - Audit of MakerDAO's DAI bridge by ChainSecurity.

#### Examples

- [Cairo by Example](https://perama-v.github.io/cairo/by-example/) - An
  introduction to [Cairo](https://www.cairo-lang.org/) with simple examples.
- [Skeleton for StarkNet](https://perama-v.github.io/cairo/examples/building_blocks/skeleton/program_starknet.html)
  - Quick example of a Minimum verifiable program
- [Skeleton for SHARP](https://perama-v.github.io/cairo/examples/building_blocks/skeleton/program_sharp.html)
  - SHARP programs differ from Cairo programs, this shows how to use
    SHARP for your own custom Cairo deploys (e.g. if you'd use StarkEx)

##### Educational

- [StarkWare | Scaling Ethereum, ZK-rollups, Layer 1's, and more!](https://youtu.be/aq7EV-4K7Vk) -
  Interview with Louis Guthmann, Ecosystem Lead @ StarkWare
- [StarkNet Basecamp](https://github.com/starknet-edu/basecamp) - Learn how Starks, Cairo and StarkNet work, from the ground up.

##### Built / Deployed on StarkNet

- [ZigZagExchange](https://github.com/ZigZagExchange/starknet-contracts) -
  Orderbook DEX
- [physics-puzzle](https://github.com/guiltygyoza/physics-puzzle-starknet) -
  Physics puzzle
- [RYO](https://github.com/dopedao/RYO) - Dope Wars game engine
- [qasr](https://github.com/mortimr/qasr) - ETH <> StarkNet NFT Bridge
- [starknet-dai-bridge](https://github.com/makerdao/starknet-dai-bridge) - ETH
  <> StarkNet DAI Bridge
- [rk4-starknet](https://github.com/guiltygyoza/rk4-starknet) - Runge Kutta 4th
  Order Method on StarkNet
- [stardrop](https://github.com/kobigurk/stardrop) - Anonymous rewards
- [tictactoe](https://github.com/guiltygyoza/tictactoe-on-starknet) - RL Agent
  playing Tic-Tac-Toe
- [tiny-dnn-on-starknet](https://github.com/guiltygyoza/tiny-dnn-on-starknet) -
  Deep Neural Net PoC
- [argent-contracts-starknet](https://github.com/argentlabs/argent-contracts-starknet) -
  [Argent](https://www.argent.xyz/)'s Account contracts
- [briq](https://github.com/briqNFT/briq-protocol) - NFT building & composability protocol
- [Empiric Network](https://github.com/42labs/Empiric) - Oracle providing decentralized, transparent and composable data.

#### Templates

- [Contracts Wizard for Cairo](https://wizard.openzeppelin.com/cairo) - Interactive smart contract generator based on OpenZeppelin Contracts for Cairo. 
- [starknet-hardhat-example](https://github.com/Shard-Labs/starknet-hardhat-example) -
  Example usage of the Starknet Hardhat plugin.
- [starknet-react-example](https://github.com/fracek/starknet-react-example) -
  Connect your ReactApp to StarkNet
- [vue-stark-boil](https://github.com/dontpanicdao/vue-stark-boil) - 
  Boilerplate for Argent-X/Vue.js.
- [starknet-scaffold](https://github.com/tarrencev/starknet-scaffold) - Cario development scaffold using nile and pytest

#### Books

#### Practice

#### Jobs
- [Dapp Developer at Shard labs](https://almanac.io/docs/starknet-dapp-developer-shard-labs-8UMOmydaLJX7jzQAZReYJTcC0o4RtE1m).
- [Open source developer at Open Zeppelin](https://openzeppelin.com/jobs/opening/?gh_jid=4554917003&gh_src=2742d3093us).
- [Cairo engineers at Immutable](https://discord.com/channels/793094838509764618/898210860030386178/898330663281905725).
- [Chainlink integration team](https://discord.com/channels/793094838509764618/898210860030386178/905842249840074783).
- [Blockchain software engineer at JellyFi](https://mango-cry-b61.notion.site/Blockchain-software-engineer-9634a0236c454e6ab7679a93478f2f8b).

## Libraries

- [get-starknet](https://github.com/starknet-community-libs/get-starknet) - wallet <-> dApp bridge.
- [starknet.js](https://github.com/seanjameshan/starknet.js) - Javascript
  library
- [starknet.py](https://github.com/software-mansion/starknet.py) - Python library
- [starknet-rs](https://github.com/xJonathanLEI/starknet-rs) - Rust library
- [starknet-hardhat-plugin](https://github.com/Shard-Labs/starknet-hardhat-plugin) -
  A plugin for integrating Starknet tools into Hardhat projects
- [starknet-jvm](https://github.com/software-mansion/starknet-jvm) - Library for JVM languages (java, kotlin and others).
- [cairo-contracts](https://github.com/OpenZeppelin/cairo-contracts) -
  OpenZeppelin Contracts written in Cairo
- [cairomate](https://github.com/a5f9t4/cairomate) - Structured, dependable legos for Starknet development. 
- [caigo](https://github.com/dontpanicdao/caigo) - Golang Library.
- [starknet-react](https://github.com/auclantis/starknet-react) - React hooks library.

## Tools

#### General
- [Braavos](https://chrome.google.com/webstore/detail/braavos-wallet/jnlgamecbpmbajjfhmmmlhejkemejdma) - Browser extension wallet.
- [argent-x](https://github.com/argentlabs/argent-x) - Browser extension wallet
- [cairo_kernel](https://github.com/ankitchiplunkar/cairo-jupyter) - Jupyter
  kernel for Cairo.
- [fossil](https://github.com/OilerNetwork/fossil) - L1 state verification with STARKs.
- [juno](https://github.com/NethermindEth/juno) - Client (GoLang).
- [nile](https://github.com/OpenZeppelin/nile) - CLI tool to develop StarkNet
  projects written in Cairo by OpenZeppelin
- [protostar](https://docs.swmansion.com/protostar/) - CLI tool for developing and testing contracts in Cairo.
- [starknet-devnet](https://github.com/Shard-Labs/starknet-devnet) - Local
  testnet
- [starkops](https://github.com/seanjameshan/starkops) - StarkNet CLI
- [voyager](https://voyager.online) - Block explorer.
- [starktx](https://starktx.info/) - StarkTx Transaction Decoder.
- [ape-cairo](https://github.com/ApeWorX/ape-cairo) - Compiler plugin for ape for the Cairo-lang.
- [ape-starknet](https://github.com/ApeWorX/ape-starknet) - Ape plugin for the StarkNet networks.

#### Utility

- [warp](https://github.com/NethermindEth/warp) - Solidity to cairo transpiler

#### Audit

## Editor Plugins

#### Vim

- [cairo.vim](https://github.com/miguelmota/cairo.vim) - (Outdated) vim syntax
  plugin for Cairo

#### Visual Studio Code

- [Cairo VS Code](https://www.cairo-lang.org/docs/quickstart.html#visual-studio-code-setup) -
  VS Code syntax support for Cairo (requires manual installation)
- [Cairo language support](https://marketplace.visualstudio.com/items?itemName=ericglau.cairo-ls) -
  Code assistance and compile error highlighting in VS Code.

---

