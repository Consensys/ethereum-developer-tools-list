# ethereum-developer-tools-list
A guide to available tools, components, patterns, and platforms for developing on Ethereum.

## Intro

Creation of this list was spurred by product managers at Consensys who saw a need for better sharing of tools, development patterns, and components amongst both new and experienced blockchain developers.

## Contributions are welcome!

Feel free to submit a pull request, with anything from small fixes to tools you'd like to add. If adding a new tool, **please add a brief description** that you think new developers would understand.


### Development frameworks

* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework
**[Ganache](https://github.com/trufflesuite/ganache)- App for test Ethereum blockchain with visual UI and logs


* [Embark](https://github.com/embark-framework/embark)- Framework for DApp development

* [Infura](https://infura.io/) - API gateway so you don’t have to host your own ETH node

* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.js based framework for Dapp deployment

* [Dapp](https://github.com/dapphub/dapptools/tree/master/src/dapp) - Framework for DApp development, successor to DApple

* [Populus](https://github.com/ethereum/populus) - The Ethereum development framework with the most cute animal pictures


### Security and analysis tools

* [Mythril](https://github.com/ConsenSys/mythril) - Static smart contract security analysis

* [Oyente](https://github.com/melonproject/oyente)- Static smart contract security analysis

* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - solidity code coverage tool

* [Quantstamp](https://quantstamp.com) A service that offers automated and manual smart contract security audits for a fee

* [Manticore](https://github.com/trailofbits/manticore) Symbolic execution tool on Smart Contracts and Binaries

* [SmartCheck](https://tool.smartdec.net/) - Static analysis of Solidity source code for security vulnerabilities and best practices.

* [Porosity](https://github.com/comaeio/porosity) - Decompiler and Security Analysis tool for Blockchain-based Ethereum Smart-Contracts

* [Ethersplay](https://github.com/trailofbits/ethersplay) - EVM disassembler

* [evmdis](https://github.com/Arachnid/evmdis) - alternative EVM disassembler

* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties

* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis

* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts

* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler


### Decentralized storage

* [IPFS](https://ipfs.io/) - Decentralized storage and file referencing

* [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralized database on top of IPFS

* [Swarm](http://swarm-gateways.net/) - Swarm is a distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack

### Developer IDE's and tools

* [Remix-](https://remix.ethereum.org/) Web IDE with built in static analysis, test blockchain VM.

* [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter)[-](https://atom.io/packages/etheratom) Atom package for Solidity linting

* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code extension that adds support for Solidity

* [Solc](https://solidity.readthedocs.io/en/v0.4.21/using-the-compiler.html?highlight=bin) - Solidity compiler

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger

* [py-eth](http://www.py-eth.com) - Collection of Python tools for the Ethereum ecosystem

* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable

* [Ethereumjs](https://github.com/ethereumjs/) - A collection of utility functions for Ethereum like [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)

* [Ethjs](https://github.com/ethjs) - Simple JS modules for the Ethereum ecosystem.

* [Eth lightwallet](https://github.com/ConsenSys/eth-lightwallet) - Lightweight JS Wallet for Node and the browser

* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript

* [Solium](https://github.com/duaraghav8/Solium) - Linter to identify and fix style & security issues in Solidity

* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum.

* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - library for decoding data params and events from Ethereum transactions

* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Auto-generate UI form field definitions and associated validators from an Ethereum contract ABI

* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity

* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility

* [JS IPFS API](https://github.com/ipfs/js-ipfs-api) - A client library for the IPFS HTTP API, implemented in JavaScript.

* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework

* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications

* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Cliquebait simplifies integration and accepting testing of smart contract applications by offering a clean ephemeral testing environment that closely resembles a real blockchain network

* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts


### Programming Languages (for writing smart contracts, compiles to Ethereum Virtual Machine Bytecode)

* [Solidity](http://solidity.readthedocs.io/en/v0.4.24/) - Ethereum smart contracting language. Read the docs, play [CryptoZombies](https://cryptozombies.io/) and [Chainshot building blocks](https://www.chainshot.com/), or checkout [Consensys Academy](https://consensys.net/academy/resources/)

* [Vyper](https://vyper.readthedocs.io/en/latest/) - Experimental pythonic smart contracting language. Alternative to Solidity, but still under development.

* [Bamboo](https://github.com/pirapira/bamboo) - A morphing smart contract language

### Front end Libraries

* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript

* [Ethers.js](https://github.com/ethers-io/ethers.js) - Javascript library for ethereum wallet implementation and utilities

* [Eth.js](https://github.com/ethjs) - Lightweight alternative

* [Web3j](https://github.com/web3j/web3j) - Java

* [Nethereum](https://nethereum.com/) - .Net

* [Web3.py ](https://github.com/ethereum/web3.py)- python implementation of web3.js

* [Pyethereum](https://github.com/ethereum/pyethereum) - Python version of web3

* [Drizzle](https://github.com/trufflesuite/drizzle) -  Redux library to connect a frontend to a blockchain

* [Web3.hs](http://hackage.haskell.org/package/web3) - Haskell implementation of Web3

* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3

* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3



### Bootstrap/out of box tools

* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem

* [Solutions PoC Starter app](https://github.com/ConsenSys/solutions-poc-starter) - Simple MERN stack with built in token use case, uPort signing, and more.

* [Paris Solutions stack](https://docs.google.com/presentation/d/1jpGX4tGlXHwRJXVKyM4fKEebxPZBiy2xgtidrGcbQng/edit) - Very private chain focused but production ready solution.

* [Viant](https://viant.io/) - Just consider using Viant as your backend if the use case is business process oriented.

* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium network. Great for PoCs and testing.

* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box

* [Ethereum client binaries](https://github.com/ethereum/ethereum-client-binaries) - Download Ethereum client binaries for your OS

* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes

* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks

* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks


### Wallets

* [Metamask](https://metamask.io/) - Easiest way to get started using a dapp. Chrome extension Ether wallet.

* [Ether Address Lookup](https://chrome.google.com/webstore/detail/etheraddresslookup/pdknmigbbbhmllnmgdfalmedcmcefdfn?hl=en-GB) - Chrome extension for phishing protection and Eth address highlighting

* [Portis](https://portis.io/) - web-based wallet for easy user onboarding to your DApp, no download required

* [uPort](https://www.uport.me/) - Total identity solution.

* [imToken](https://token.im/) - imToken is a feature-rich digital asset mobile wallet enabling multi-chain asset management, DApp browsing and secure, private exchange of value.

* [Cypher](https://www.cipherbrowser.com/) - Mobile dapp explorer

* [Trust](https://trustwalletapp.com/)

* [Toshi](https://itunes.apple.com/us/app/toshi-ethereum-wallet/id1278383455?mt=8)

* [MyEtherWallet](https://www.myetherwallet.com/)

* [MyCrypto](https://mycrypto.com) - Ethereum blockchain interface. Access your wallet locally. Contract interaction and deployment. Swaps. Transaction status lookup. Testnet and 3rd-party ETH-based chain support.

* [Trustology](https://www.trustology.io/) - Under development. Institutional custody.

* [Jaxx](https://jaxx.io) Both a mobile and a desktop wallet. Has integrated Shapeshift support

* [Exodus](https://www.exodus.io) Desktop wallet with Shapeshift integration

* [Gnosis multisig wallet](https://github.com/gnosis/MultiSigWallet)

* [WallETH](https://walleth.org) - native Android Ethereum Wallet

* Hardware wallets

    * [Trezor](https://trezor.io) The original hardware wallet

    * [Ledger](https://www.ledgerwallet.com)

    * [KeepKey](https://www.keepkey.com)

* [Mist](https://github.com/ethereum/mist) - Browse and use Dapps on the Ethereum network

* [Status](https://github.com/status-im/status-react) - A free open-source, mobile OS for Ethereum

### Ethereum clients

1. [Geth](https://github.com/ethereum/go-ethereum/wiki/geth)

2. [Parity](https://www.parity.io/)

3. [Quorum](https://www.jpmorgan.com/global/Quorum)

4. [Exthereum](https://gitter.im/exthereum/exthereum)

5. [Cpp-ethereum](https://github.com/ethereum/cpp-ethereum)

6. [Pyethapp](https://github.com/ethereum/pyethapp) - Python client using [pyethereum](https://github.com/ethereum/pyethereum)

7. [Trinity](https://github.com/ethereum/trinity) - Python client using [py-evm](https://github.com/ethereum/py-evm)

8. [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)

9. [Ethereumj](https://github.com/ethereum/ethereumj) - Java client by the Ethereum Foundation

10. [Harmony](https://github.com/ether-camp/ethereum-harmony) - Java client by EtherCamp

11. [ConsenSys clients](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

    1. [Pantheon](https://github.com/ConsenSys/pantheon)

12. [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"


### Ethereum (test) faucets

* [Ropsten faucet](http://faucet.ropsten.be:3001/)

* [Rinkeby faucet](https://faucet.rinkeby.io/)

* [Kovan Faucet](https://github.com/kovan-testnet/faucet)

### Storage, Middleware, Etc.

* [Mustekala](https://github.com/MetaMask/mustekala) - blockchain services framework

* [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - IPFS Storage service with added search capability

* [Eventeum](https://github.com/ConsenSys/eventeum) - A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri.

* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other

* [DEVp2p Wire Protocol](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) - Peer-to-peer communications between nodes running Ethereum/Whisper

* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer

### Front end Libraries

* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript

    * [Eth.js](https://github.com/ethjs) - Lightweight alternative

* [Web3j](https://github.com/web3j/web3j) - Java

* [KEthereum](https://github.com/walleth/kethereum) - Kotlin

* [Nethereum](https://nethereum.com/) - .Net

* [Pyethereum](https://github.com/ethereum/pyethereum) - Python

* [Ethers.js](https://github.com/ethers-io/ethers.js/)- Web3 Alternative

* [Drizzle](https://github.com/truffle-box/drizzle-box) -  Redux library to connect a frontend to a blockchain

### Example Smart Contract Repos and reusuable libraries

* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - Contains tested reusable smart contracts like [SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html) and ZeppelinOS [library](https://github.com/zeppelinos/zos-lib) for smart contract upgradeability

* [Aragon](https://github.com/aragon/aragon)

* [0x](https://github.com/0xProject)

* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) -  A group of packages built for use on blockchains utilising the Ethereum Virtual Machine

* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library


### Other

* Block explorers
    * [Etherscan](https://etherscan.io/) - most popular centralized way to view Eth transactions and contract code

    * [POA Explorer](https://github.com/poanetwork/poa-explorer) - Open Source Ethereum Block explorer, funded by [Ethprize](ethprize.io) and developed by [POA](https://poa.net)

    * [QuickBlocks](https://github.com/Great-Hill-Corporation/quickBlocks)- QuickBlocks is a collection of software libraries, applications, tools, and examples that allow you to retrieve Ethereum blockchain data (a) more quickly, (b) with higher information content, (c) in an fully decentralized way, (d) in a fully automated way, and (e) in a highly maintenance free way.)

    * [Etherchain lite](https://github.com/gobitfly/etherchain-light)- Lightweight blockchain explorer for your private Ethereum chain

    * [Alethio EthStats 2.0](https://media.consensys.net/alethio-lighting-up-the-blockchain-with-real-time-stats-a80bb30576db) coming soon

    * [Supermax](https://www.supermax.cool/)- A live data feed of the activities and event logs of your smart contracts on Ethereum

* Gas price calculators and tools

   * [EthGasStation](https://ethgasstation.info/) - website for estimating tx prices vs times

   * [Petrometer](https://github.com/makerdao/petrometer)- petrometer is a tool which summarizes daily and total gas consumption of all transactions sent from a specified Ethereum address.

   * [CryptoProf](https://github.com/doc-ai/cryptoprof)- Gas profiler for smart contracts

* [Netstats](https://github.com/cubedro/eth-netstats) - Ethereum Network [Stats](https://ethstats.net/)

* [ENS](https://github.com/ensdomains) - ENS offers a secure & decentralised way to address resources both on and off the blockchain using simple, human-readable [names](https://ens.domains/)

* [Name Bazaar](https://namebazaar.io/) - A peer-to-peer marketplace for the exchange of names registered via the Ethereum Name Service   

* Contract Standards

    * Tokens
        * [ERC-20](https://eips.ethereum.org/EIPS/eip-20): A standard interface for tokens. Used in ICOs and crowdfunding.
        * [ERC-721](https://eips.ethereum.org/EIPS/eip-721): A standard interface for implementing non-fungible tokens (NFTs) used in DApps such as Cryptokitties.

    * Utilities
        * [ERC-165](https://eips.ethereum.org/EIPS/eip-165): Creates a standard method to publish and detect what interfaces a smart contract implements.
        * [ERC-725](https://eips.ethereum.org/EIPS/eip-725): Proxy contract for key management and execution, to establish a Blockchain identity.
        * [ERC-173](https://eips.ethereum.org/EIPS/eip-173): A standard interface for ownership of contracts

* Side-Chains
    * [POA Network](https://poa.net/)
        * [POA Bridge] (http://bridge.poa.net/)
        * [POA Bridge UI] (https://github.com/poanetwork/bridge-ui)
        * [POA Bridge Contracts] (https://github.com/poanetwork/poa-bridge-contracts)
    * [Loom Network](https://github.com/loomnetwork)

* [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository

* Decentralized Exchanges

    * [Airswap](https://www.airswap.io/) - decentralized token exchange

    * 0x protocol based decentralized exchanges

        * [Radar relay](https://app.radarrelay.com/)

        * [ERC Dex](https://ercdex.com/)

        * [DDEX](https://ddex.io)

        * [Ethfinex](https://www.ethfinex.com)

        * [Shark Relay](https://app.sharkrelay.com)

        * [Bamboo Relay](https://www.bamboorelay.com)

        * [Instex](https://app.instex.io)

        * [Starbit](https://www.starbitex.com)

    * [Opensea.io](http://Opensea.io)-  decentralized exchange of cryptocollectibles
    * [Bancor](https://www.bancor.network/)
    * [Kyber](https://www.kyber.network)
    * [Gnosis Dutch Exchange](https://github.com/gnosis/dx-contracts)

* KYC/AML Onboarding

    * SmartAML protospoke

    * Third party centralized versions

* Registry Framework for Digital Assets

    * [Regis](https://regis.nu/)

* Oracles

    * [Oracalize](http://www.oraclize.it/)- oracle service for your smart contracts.

* Incentivization / Monetization Tools

    * [Gitcoin](https://gitcoin.co)- Bounty network for funding Open Source or finding Open Source work
    * [CodeFund](https://codefund.io)- Ethical Adveritsing Platform for Open Source

* Hash calculator tool
    * [MD4 Online Hash Function](https://emn178.github.io/online-tools/md4.html) - Tool to hash input with a variety of hashing algorithm options

## Ethereum knowledge
* [Wiki](https://github.com/ethereum/wiki/wiki) - Ethereum wiki covering all things related to Ethereum
* [Yellow Paper](https://github.com/ethereum/yellowpaper) - The "Yellow Paper": Ethereum's formal specification
* [Beige Paper](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf) - Rewrite of the yellow paper in non-yellow-paper syntax
* [EthOn](https://github.com/ConsenSys/EthOn) - An ontology is a formalisation of concepts and relations within a domain. EthOn is written in RDF and OWL
* [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - by Andreas M. Antonopoulos, Gavin Wood
* [EVM opcodes](https://github.com/trailofbits/evm-opcodes) - Ethereum opcodes and instruction reference
* [EVM illustrated](http://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf) - This is an illustrated document about the Ethereum Virtual Machine
* [4bytes](https://github.com/ethereum-lists/4bytes) - List of 4byte identifiers to common smart contract functions [function signatures](https://www.4byte.directory/)
* [Solidity idiosyncrasies](https://github.com/miguelmota/solidity-idiosyncrasies) - Solidity gotchas, pitfalls, limitations, and idiosyncrasies
* [Delegate call](https://delegatecall.com/) - Q&A
* [Stackexchange](https://ethereum.stackexchange.com) - Q&A
* [Ethernaut](https://github.com/OpenZeppelin/ethernaut) - Web3/Solidity based wargame


### Security best practices

* [Safety wiki](https://github.com/ethereum/wiki/wiki/Safety) - Ethereum Foundation wiki on safety

* [Smart contract best practices](https://github.com/ConsenSys/smart-contract-best-practices) - Standard published by ConsenSys

* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns

### Known Vulnerabilities

* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected

### Governance

 * [ERC-721](https://github.com/ethereum/eips/issues/721) - A peek into debate and consensus-reaching on a token standard for non-fungible assets
 * [Eth Research Chat](https://ethresear.ch) - Gitter-like forum for ongoing Ethereum Foundation research projects
 * [Fellowship of Ethereum Magicians](https://ethereum-magicians.org/) - This discussion board facilitates meaningful communications among individuals throughout the Ethereum community
 * [EIPs](http://eips.ethereum.org/) - The Ethereum Improvement Proposal repository

### DApp development

 * [Ethereum Development with Go](https://goethereumbook.org/) - A guide on getting started on Ethereum DApp development with Golang.

## Scaling

 * [Comprehensive Medium article](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4) on various solutions to scale Ethereum
