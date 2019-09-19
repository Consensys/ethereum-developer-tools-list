
# Ethereum Developer Tools List
A guide to available tools, components, patterns, and platforms for developing applications on Ethereum.

Creation of this list was spurred by product managers at ConsenSys who saw a need for better sharing of tools, development patterns, and components amongst both new and experienced blockchain developers.

This resource is meant to be focused on developer tools, but the repo also includes:
* [Ethereum Ecosystem Resources](EcosystemResources.md) for useful DApps, educational resources, wallets, and services.

## Contributions are welcome!

Feel free to submit a pull request, with anything from small fixes to tools you'd like to add (or remove!). If adding a new tool, **please add a brief description** that you think new developers would understand.

Many thanks to the ~100 contributors including [@corbpage](https://twitter.com/corbpage) and  [@pakaplace](https://twitter.com/Parker_Place) of [Meridio](https://meridio.co) for curating, and @jpantunes for restructuring the list in a more logical way.
* Projects that do not have a working product will not be added.
* Projects that are deprecated or no longer maintained will be removed.
* Projects that are paid/restricted services without open source code or developer reviews will be further vetted.

^Is the above fair? Share your input here - https://github.com/ConsenSysLabs/ethereum-developer-tools-list/pull/70

## Table of Contents
- [New developers start here](#new-developers-start-here)
- [Developer Tools](#developer-tools)
   - [Smart Contract Languages](#smart-contract-languages)
   - [Frameworks](#frameworks)
   - [IDEs](#ides)
   - [Test blockchain networks](#test-blockchain-networks)
   - [Test Ether faucets](#test-ether-faucets)
- [Communicating with Ethereum](#communicating-with-ethereum)
   - [Frontend Ethereum APIs](#frontend-ethereum-apis)
   - [Backend Ethereum APIs](#backend-ethereum-apis)
   - [Bootstrap/out of box tools](#bootstrapout-of-box-tools)
   - [Ethereum ABI (Application Binary Interface) tools](#ethereum-abi-application-binary-interface-tools)
- [Patterns & Best Practices](#patterns--best-practices)
   - [Patterns for Smart Contract Development](#patterns-for-smart-contract-development)
   - [Upgradeability](#upgradeability)
- [Infrastructure](#infrastructure)
   - [Ethereum Clients](#ethereum-clients)
   - [Storage](#storage)
   - [Messaging](#messaging)
- [Testing Tools](#testing-tools)
- [Security Tools](#security-tools)
- [Monitoring](#monitoring)
- [Other Miscellaneous Tools](#other-miscellaneous-tools)
- [Smart Contract Standards & Libraries](#smart-contract-standards--libraries)
   - [ERCs - The Ethereum Request for Comment repository](#ercs---the-ethereum-request-for-comment-repository)
   - [Popular Smart Contract Libraries](#popular-smart-contract-libraries)
- [Developer Guides for 2nd Layer Infrastructure](#developer-guides-for-2nd-layer-infrastructure)
   - [Scalability](#scalability)
   - [Payment/State Channels](#paymentstate-channels)
   - [Plasma](#plasma)
   - [Side-Chains](#side-chains)
- [Privacy / Confidentiality](#privacy--confidentiality)
   - [zkSNARKs](#zksnarks)
- [Prebuilt UI Components](#prebuilt-ui-components)

## New developers start here
* [Solidity](https://solidity.readthedocs.io/en/latest/) - The most popular smart contract language.
* [Truffle](https://truffleframework.com) - Most popular smart contract development, testing, and deployment framework. Install the cli via npm and start here to write your first smart contracts.
* [Metamask](https://metamask.io/) - Chrome extension wallet to interact with Dapps.
* [Truffle boxes](https://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem
* [OpenZeppelin Starter Kits](https://openzeppelin.com/starter-kits/) - An all-in-one starter box for developers to jumpstart their smart contract backed applications. Includes Truffle, OpenZeppelin SDK, the OpenZeppelin/contracts-ethereum-package EVM package of audited smart contract, a react-app and rimble for easy styling. 
* [EthHub.io](https://docs.ethhub.io/) - Comprehensive crowdsourced overview of Ethereum- its history, governance, future plans and development resources. 
* [Cobra](https://github.com/cobraframework/cobra) - A fast, flexible and simple development environment framework for Ethereum smart contract, testing and deployment on Ethereum virtual machine(EVM).
* [Fortmatic](https://fortmatic.com/) - A simple to use SDK to build web3 dApps without extensions or downloads.
* [Portis](https://portis.io/) - A non-custodial wallet with an SDK that enables easy interaction with DApps without installing anything.

## Developer Tools
### Developing Smart Contracts
#### Smart Contract Languages
* [Solidity](https://solidity.readthedocs.io/en/latest/) - Ethereum smart contracting language
* [Bamboo](https://github.com/pirapira/bamboo) - A morphing smart contract language
* [Vyper](https://github.com/ethereum/vyper) - New experimental pythonic programming language
* [Flint](https://docs.flintlang.org/) - New language under development with security features including asset types, state transition, and safe integers

#### Frameworks
* [Truffle](https://truffleframework.com) - Most popular smart contract development, testing, and deployment framework. The Truffle suite includes Truffle, [Ganache](https://github.com/trufflesuite/ganache), and [Drizzle](https://github.com/truffle-box/drizzle-box). [Deep dive on Truffle here](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Embark](https://github.com/embark-framework/embark) - Framework for DApp development
* [Waffle](https://getwaffle.io/) - Framework for advanced smart contract development and testing, small, flexible, fast (based on ethers.js)
* [Dapp](https://dapp.tools/dapp/) - Framework for DApp development, successor to DApple
* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.js based framework for Dapp deployment
* [Parasol](https://github.com/Lamarkaz/parasol) - Agile smart contract development environment with testing, INFURA deployment, automatic contract documentation and more. It features a flexible and unopinionated design with unlimited customizability
* [0xcert](https://github.com/0xcert/framework/) - JavaScript framework for building decentralized applications 
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - OpenZeppelin SDK: A suite of tools to help you develop, compile, upgrade, deploy and interact with smart contracts.
* [sbt-ethereum](https://www.sbt-ethereum.io/) - A tab-completey, text-based console for smart-contract interaction and development, including wallet and ABI management, ENS support, and advanced Scala integration.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie is a Python framework for deploying, testing and interacting with Ethereum smart contracts.
* [Cobra](https://github.com/cobraframework/cobra) - A fast, flexible and simple development environment framework for Ethereum smart contract, testing and deployment on Ethereum virtual machine(EVM).

#### IDEs
* [Remix](https://remix.ethereum.org/) - Web IDE with built in static analysis, test blockchain VM.
* [Superblocks Lab](https://superblocks.com/lab/) - Web IDE. Built in browser blockchain VM, Metamask integration (one click deployments to Testnet/Mainnet), transaction logger and live code your WebApp among many other features.
* [Atom](https://atom.io/) - Atom editor with [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom), [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), and [language-solidity](https://atom.io/packages/language-solidity) packages
* [Pragma](https://www.withpragma.com/) - Very simple web IDE for solidity, and auto-generated interfaces for smart contracts.
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Vim syntax file for solidity
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code extension that adds support for Solidity
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - Open-source plug-in for [JetBrains IntelliJ Idea IDE](https://www.jetbrains.com/idea/) (free/commercial) with syntax highlighting, formatting, code completion etc.
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - Eclipse based IDE. Features context sensitive code completion and help, code navigation, syntax coloring, build in compiler, quick fixes and templates.
* [Eth Fiddle](https://ethfiddle.com/) - IDE developed by [The Loom Network](https://loomx.io/) that allows you to write, compile and debug your smart contract. Easy to share and find code snippets.

### Other tools
* [Atra Blockchain Services](https://console.atra.io) - Atra provides web services to help you build, deploy, and maintain decentralized applications on the Ethereum blockchain.
* [Buidler](https://github.com/nomiclabs/buidler) - Extensible developer tool that helps smart contract developers increase productivity by reliably bringing together the tools they want.

### Test blockchain networks
* [ethnode](https://github.com/vrde/ethnode) - Run an Ethereum node (Geth or Parity) for development, as easy as `npm i -g ethnode && ethnode`.
* [Ganache](https://github.com/trufflesuite/ganache) - App for test Ethereum blockchain with visual UI and logs
* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium blockchain network. Great for PoCs and testing
* [Pantheon Private Network](https://docs.pantheon.pegasys.tech/en/latest/Getting-Started/Private-Network-Quickstart/) - Run a private network of Pantheon nodes in a Docker container
** [Orion](https://github.com/PegaSysEng/orion) - Component for performing private transactions by PegaSys
** [Artemis](https://github.com/PegaSysEng/artemis) - Java implementation of the Ethereum 2.0 Beacon Chain by PegaSys
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain-workbench/ethereum-poa-deployment) - Deployment and governance of consortium Ethereum PoA networks
* [getho](https://getho.io) - DApp development platform including PoA private blockchain and Smart Contract testing tool. 
* [Ethereum on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - Build Ethereum network based on Proof of Work
* [Infura](https://infura.io/) - Ethereum API access to Ethereum networks (Mainnet, Ropsten, Rinkeby, Goerli, Kovan)
* [Chainstack](https://chainstack.com/) - Shared and dedicated Ethereum nodes as a service (Mainnet, Ropsten)

#### Test Ether faucets
* [Rinkeby faucet](https://faucet.rinkeby.io/)
* [Kovan faucet](https://github.com/kovan-testnet/faucet)
* [Ropsten faucet](http://faucet.ropsten.be:3001/)
* [Goerli faucet](https://goerli-faucet.slock.it/)
* [Universal faucet](https://faucets.blockxlabs.com/)
* [Nethereum.Faucet](https://github.com/Nethereum/Nethereum.Faucet) - A C#/.NET faucet

### Communicating with Ethereum
#### Frontend Ethereum APIs
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
    * [Eth.js](https://github.com/ethjs) - Javascript Web3 alternative
    * [Ethers.js](https://github.com/ethers-io/ethers.js/) - Javascript Web3 alternative, useful utilities and wallet features
    * [light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js) A high-level reactive JS library optimized for light clients.
    * [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/web3-wrapper) - Typescript Web3 alternative
    * [Ethereumjs](https://github.com/ethereumjs/) - A collection of utility functions for Ethereum like [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)
    * [flex-contract](https://github.com/merklejerk/flex-contract) and [flex-ether](https://github.com/merklejerk/flex-ether) Modern, zero-configuration, high-level libraries for interacting with smart contracts and making transactions.
    * [ez-ens](https://github.com/merklejerk/ez-ens) Simple, zero-configuration Ethereum Name Service address resolver.
    * [web3x](https://github.com/xf00f/web3x) - A TypeScript port of web3.js. Benefits includes tiny builds and full type safety, including when interacting with contracts. 
* [Nethereum](https://github.com/Nethereum/) - Cross-platform Ethereum development framework 
* [Drizzle](https://github.com/truffle-box/drizzle-box) - Redux library to connect a frontend to a blockchain
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) - A JavaScript SDK for making native mobile Ethereum dapps using React Native
* [Subproviders](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/subproviders) - Several useful subproviders to use in conjunction with [Web3-provider-engine](https://github.com/MetaMask/provider-engine/) (including a LedgerSubprovider for adding Ledger hardware wallet support to your dApp)
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - React framework for building single-page Ethereum dApps
* [Vortex](https://github.com/Horyus/vortex) - A Dapp-ready Redux Store. Smart and Dynamic background data refresh thanks to WebSockets. Works with [Truffle](https://github.com/Horyus/vortex-demo) and [Embark](https://github.com/Horyus/vortex-demo-embark).
* Strictly Typed - Javascript alternatives
    * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
    * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
* [ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer) - Communicate with different blockchains (including Ethereum) using a single interface.
* [Delphereum](https://github.com/svanas/delphereum) - a Delphi interface to the Ethereum blockchain that allows for development of native dApps for Windows, macOS, iOS, and Android.

#### Backend Ethereum APIs
* [Web3.py](https://github.com/ethereum/web3.py) - Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/walleth/kethereum) - Kotlin Web3
* [Pyethereum](https://github.com/ethereum/pyethereum) - The Python core library of the Ethereum project
* [Eventeum](https://github.com/ConsenSys/eventeum) - A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - Elixir JSON-RPC client for the Ethereum blockchain
* [EthContract](https://github.com/AgileAlpha/eth_contract) - A set of helper methods to help query ETH smart contracts in Elixir
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - A MESG Service to interact with any Ethereum contract based on its address and ABI.
* [Ethereum Service](https://github.com/mesg-foundation/service-ethereum) - A MESG Service to interact with events from Ethereum and interact with it.

#### Bootstrap/out of box tools
* [Truffle boxes](https://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem
* [Pantheon Private Network](https://docs.pantheon.pegasys.tech/en/latest/Getting-Started/Private-Network-Quickstart/) - Run a private network of Pantheon nodes in a Docker container
* [Testchains](https://github.com/Nethereum/TestChains) - Pre-configured .NET devchains for fast response (PoA) 
** [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - Wasm blockchain explorer (functional sample)

* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - Step-by-Step tutorial for building a PoA test chain with 2 nodes with Parity authority round consensus
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks
* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium blockchain network. Great for PoCs and testing
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [aragonCLI](https://hack.aragon.org/docs/cli-usage.html) - aragonCLI is used to create and develop Aragon apps and organizations.
* [ColonyJS](https://github.com/JoinColony/colonyJS) - JavaScript client that provides an API for interacting with the Colony Network smart contracts.
* [ArcJS](https://github.com/daostack/arc.js) - Library that facilitates javascript application access to the DAOstack Arc ethereum smart contracts.
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - JavaScript client that provides an API for interacting with Arkane Network, a wallet provider for building user-friendly dapps.
* [Blocknative](https://blocknative.com) - Assist.js is an embeddable widget that improves Dapp usability. The tool programmatically identifies and outlines clear actions for end-users to follow when interacting with MetaMask to overcome — and even prevent — common pitfalls and obstacles. 

#### Ethereum ABI (Application Binary Interface) tools
* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - library for decoding data params and events from Ethereum transactions
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/abi-gen) - Generate Typescript contract wrappers from contract ABI's.
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Auto-generate UI form field definitions and associated validators from an Ethereum contract ABI
* [headlong](https://github.com/esaulpaugh/headlong/) - type-safe Contract ABI and Recursive Length Prefix library in Java
* [One Click dApp](https://oneclickdapp.com) -  Instantly create a dApp at a unique URL using the ABI. 
* [Truffle Pig](https://www.npmjs.com/package/trufflepig) - a development tool that provides a simple HTTP API to find and read from Truffle-generated contract files, for use during local development. Serves fresh contract ABIs over http.
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - A MESG Service to interact with any Ethereum contract based on its address and ABI.

#### Patterns & Best Practices

##### Patterns for Smart Contract Development
* [Dappsys: Safe, simple, and flexible Ethereum contract building blocks](https://github.com/dapphub/dappsys)
    * has solutions for common problems in Ethereum/Solidity, eg.
        * [Whitelisting](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Upgradable ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Authentication (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...several more...](https://github.com/dapphub/dappsys)
    * provides building blocks for the [MakerDAO](https://github.com/makerdao/maker-otc) or [The TAO](https://github.com/ryepdx/the-tao)
    * should be consulted before creating own, untested, solutions
    * usage is described in [Dapp-a-day 1-10](https://steemit.com/@nikolai) and [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [OpenZeppelin Contracts: An open framework of reusable and secure smart contracts in the Solidity language.](https://github.com/OpenZeppelin/openzeppelin-contracts)
    * Likely the most widely-used libraries and smart contracts
    * Similar to Dappsys, more integrated into Truffle framework
    * [Blog about Best Practices with Security Audits](https://blog.openzeppelin.com/)
* [Advanced Workshop with Assembly](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especially section _Benefits_
* [CryptoFin Solidity Auditing Checklist](https://github.com/cryptofinlabs/audit-checklist) - A checklist of common findings, and issues to watch out for when auditing a contract for a mainnet launch.
* [aragonOS: A smart contract framework for building DAOs, Dapps and protocols](https://hack.aragon.org/docs/aragonos-intro.html)
    * Upgradeability: Smart contracts can be upgraded to a newer version
    * Permission control: By using the `auth` and `authP` modifiers, you can protect functionality so only other apps or entities can access it
    * Forwarders: aragonOS apps can send their intent to perform an action to other apps, so that intent is forwarded if a set of requirements are met

##### Upgradeability
* [Blog von Elena Dimitrova, Dev at colony.io](https://blog.colony.io/author/elena/)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Aragon research blog](https://blog.aragon.org/tag/research/)
    * [Library driven development](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
    * [Advanced Solidity code deployment techniques](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelin on Proxy Libraries](https://blog.openzeppelin.com/proxy-libraries-in-solidity-79fbe4b970fd/)

### Infrastructure
#### Ethereum Clients
* [Pantheon](https://docs.pantheon.pegasys.tech/en/latest/) - Java client by PegaSys
* [Geth](https://github.com/ethereum/go-ethereum/wiki/geth) - Go client
* [Parity](https://www.parity.io/) - Rust client
* [Aleth](https://github.com/ethereum/aleth) - C++ client
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core client
* [Pyethapp](https://github.com/ethereum/pyethapp) - Python client using [pyethereum](https://github.com/ethereum/pyethereum)
* [Infura](https://infura.io/) - A managed service providing Ethereum client standards-compliant APIs
* [Trinity](https://github.com/ethereum/trinity) - Python client using [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Ethereumj](https://github.com/ethereum/ethereumj) - Java client by the Ethereum Foundation
* [Harmony](https://github.com/ether-camp/ethereum-harmony) - Java client by EtherCamp
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"
* [Mustekala](https://github.com/musteka-la/mustekala) - Ethereum Light Client project of Metamask.
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir client
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - Energy Web Foundation client for the Tobalaba test network
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://www.jpmorgan.com/quorum)
* [Mana](https://github.com/mana-ethereum/mana) - Ethereum full node implementation written in Elixir.
* [Chainstack](https://chainstack.com/) - A managed service providing shared and dedicated Geth nodes

#### Storage
* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
   * [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - IPFS Storage service with added search capability
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralised database on top of IPFS
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - A client library for the IPFS HTTP API, implemented in JavaScript.
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - Easy to use API into IPFS and other distributed/decentralised storage protocols
* [Swarm](https://swarm-gateways.net/) - Distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack
* [Infura](https://infura.io/) - A managed IPFS API Gateway and pinning service


#### Messaging
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack
* [DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/devp2p.md) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer

### Testing Tools
* [Truffle Teams](https://truffleframework.com/teams) - Zero-Config continuous integration for truffle projects.
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - Alternative and updated Solidity smart contract  profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - Speed up your development with human readable stack traces
* [Solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation
* [Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in Solidity, formerly Solium
* [Decode](https://github.com/dteiml/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - An npm package with additional assertions and utilities used in testing Solidity smart contracts with truffle. Most importantly, it adds the ability to assert whether specific events have (not) been emitted.
* [Psol](https://github.com/Lamarkaz/psol) - Solidity lexical preprocessor with mustache.js-style syntax, macros, conditional compilation and automatic remote dependency inclusion.
* [solpp](https://github.com/merklejerk/solpp) - Solidity preprocessor and flattener with a comprehensive directive and expression language, high precision math, and many useful helper functions.
* [Decode and Publish](https://flightwallet.org/decode-eth-tx/) – Decode and publish raw ethereum tx. Similar to https://live.blockcypher.com/btc-testnet/decodetx/
* [Doppelgänger](https://getdoppelganger.io/) - a library for mocking smart contract dependencies during unit testing.
* [rocketh](https://github.com/wighawag/rocketh) - A simple lib to test ethereum smart contract that allow to use whatever web3 lib and test runner you choose.
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - PyTest plugin for testing smart contracts for Ethereum blockchain. 

### Security Tools
* [MythX](https://mythx.io/) - Security verification platform and tools ecosystem for Ethereum developers
* [Mythril Classic](https://github.com/ConsenSys/mythril-classic) - Open-source EVM bytecode security analysis tool
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.chainsecurity.com/) - Security scanner for Ethereum smart contracts
* [SmartCheck](https://tool.smartdec.net/) - Static smart contract security analyzer
* [Porosity](https://github.com/comaeio/porosity) - Decompiler and Security Analysis tool for Blockchain-based Ethereum Smart-Contracts
* [Ethersplay](https://github.com/trailofbits/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Slither](https://github.com/trailofbits/slither) - A Solidity static analysis framework
* [Adelaide](https://github.com/sec-bit/adelaide) - The SECBIT static analysis extension to Solidity compiler
* [solc-verify](https://github.com/SRI-CSL/solidity/) - A modular verifier for Solidity smart contracts
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Free smart contract security audits from Callisto Network

### Monitoring
* [amberdata.io](https://amberdata.io) - Provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search.
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Scout](https://scout.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum
* [Tenderly](https://tenderly.dev/) - A platform that gives users reliable smart contract monitoring and alerting in the form of a web dashboard without requiring users to host or maintain infrastructure
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Explore smart contracts with decoded transaction data, see how the contract is used and search transactions with specific function calls
* [BlockScout](https://github.com/poanetwork/blockscout) - A tool for inspecting and analyzing EVM based blockchains. The only full featured blockchain explorer for Ethereum networks.

### Other Miscellaneous Tools
* [aragonPM](https://hack.aragon.org/docs/apm.html) - a decentralized package manager powered by aragonOS and Ethereum. aragonPM enables decentralized governance over package upgrades, removing centralized points of failure.
* [Truffle boxes](https://truffleframework.com/boxes/) - Packaged components for building DApps fast.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - Solidity compiler
* [Sol-compiler](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-compiler) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternative, merges all imports into single file for solidity contracts
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [eth-cli](https://github.com/protofire/eth-cli) - A collection of CLI tools to help with ethereum learning and development
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://py-eth.com) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/alcuadrado/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/dteiml/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Typescript bindings for Ethereum smartcontracts
* [EthSum](https://ethsum.netlify.com) - A Simple Ethereum Address Checksum Tool
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - allows indexing blocks or listening to Events in PHP
* [Purser](https://github.com/JoinColony/purser) - JavaScript universal wallet tool for Ethereum-based wallets. Supports software, hardware, and Metamask -- brings all wallets into a consistent and predictable interface for dApp development.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - Connect to MetaMask from node.js
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Export Ethereum blockchain data to CSV or JSON files
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for formatting Solidity code
* [EthToolbox](https://eth-toolbox.com) - A web app with off-chain tools for Ethereum developers. EC recovery, address formatter, unit converter, hash functions, keys generator, etc.
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Ethereum and Unity integration demo
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Ethereum and Unity integration demo/sample
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum business rules engine demo/sample
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - A set of tools to standarize Solidity import and artifact resolution in frameworks.

### Smart Contract Standards & Libraries
#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository
* Tokens
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Original token contract for fungible assets
  * [ERC-721](https://github.com/ethereum/eips/issues/721) - Token standard for non-fungible assets
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - An improved token standard for fungible assets
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - Mineable Token Standard
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) -  Creates a standard method to publish and detect what interfaces a smart contract implements.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) -  Proxy contract for key management and execution, to establish a Blockchain identity.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - A standard interface for ownership of contracts

#### Popular Smart Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - Contains tested reusable smart contracts like [SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html) and ZeppelinOS [library](https://github.com/zeppelinos/zos) for smart contract upgradeability
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - A collection of Solidity libraries for building secure and gas-efficient smart contracts on Ethereum.
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) -  A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol. Contains [aragonOS smart contract framework](https://github.com/aragon/aragonOS) with focus on upgradeability and governance
* [ARC](https://github.com/daostack/arc) - an operating system for DAOs and the base layer of the DAO stack.
* [0x](https://github.com/0xProject) - DEX protocol
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - Contains correctness proofs of token contracts wrt. given specifications and high-level properties
* [Provable API](https://github.com/provable-things/ethereum-api) - Provides contracts for using the Provable service, allowing for off-chain actions, data-fetching, and computation


### Developer Guides for 2nd Layer Infrastructure

#### Scalability

#### Payment/State Channels
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Ethereum Payment Channel in 50 lines of code
* [µRaiden Documentation](https://microraiden.readthedocs.io) - Guides and Samples for µRaiden Sender/Receiver Use Cases

#### Plasma
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - Website as Node application that was started at the 2018 IC3-Ethereum Crypto Boot Camp at Cornell University, covering all Plasma variants (MVP/Cash/Debit)
* [Plasma MVP](https://github.com/omisego/plasma-mvp) - OmiseGO's research implementation of Minimal Viable Plasma
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Golang implementation and extension of the Minimum Viable Plasma specification
* [Plasma Cash](https://github.com/omisego/plasma-cash) - Simple Plasma Cash implementation
* [Plasma Exit](https://github.com/mesg-foundation/application-plasma-exit) - Automatically watch and challenge or exit from Omisego Plasma Network when needed.
* [Plasma OmiseGo Watcher](https://github.com/mesg-foundation/service-plasma-omisego-watcher) - Interact with Plasma OmiseGo network and notifies for any byzantine events.

#### Side-Chains
* [POA Network](https://poa.net/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)

#### Privacy / Confidentiality

##### zkSNARKs
* [ZoKrates](https://github.com/Zokrates/ZoKrates) - A toolbox for zkSNARKS on Ethereum
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - Confidential transactions on the Ethereum network, implementation is live on the Ethereum main-net
* Proxy Re-encryption (PRE)
** [NuCypher Network](https://github.com/nucypher/nucypher) - A proxy re-encryption network to empower data privacy in decentralized systems
** [pyUmbral](https://github.com/nucypher/pyumbral) - Threshold proxy re-encryption cryptographic library
* Fully Homomorphic Encryption (FHE)
** [NuFHE](https://github.com/nucypher/nufhe) - GPU accelerated FHE library


#### Prebuilt UI Components
* [aragonUI](https://ui.aragon.org) - A React library including Dapp components
* [components.bounties.network](https://components.bounties.network) - A React library including Dapp components
* [lorikeet.design](https://lorikeet.design) - A React library including Dapp components
* [ui.decentraland.org](https://github.com/decentraland/ui) - A React library including Dapp components
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Reusable React Dapp components
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React Components
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) -  A cross-platform hybrid hosting mechanism for web based decentralised applications
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - Cross-platform desktop wallet sample
* [eth-button](https://eth-button.github.io/eth-button/) - Minimalist donation button
* [Rimble Design System](https://rimble.consensys.design/) - Adaptable components and design standards for decentralized applications.
