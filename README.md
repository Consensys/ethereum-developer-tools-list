# ethereum-developer-tools-list
A guide to available tools, components, patterns, and platforms for developing on Ethereum.

## Intro

Creation of this list was spurred by product managers at ConsenSys who saw a need for better sharing of tools, development patterns, and components amongst both new and experienced blockchain developers.

## Contributions are welcome!

Feel free to submit a pull request, with anything from small fixes to tools you'd like to add.

See the [issues](https://github.com/ConsenSysLabs/ethereum-developer-tools-list/issues) for topics that need to be covered or updated.


### Infrastructure
#### Clients  
* [Geth](https://github.com/ethereum/go-ethereum/wiki/geth) - Go
* [Parity](https://www.parity.io/) - Rust
* [Cpp-ethereum](https://github.com/ethereum/cpp-ethereum) - C++
* [Pyethapp](https://github.com/ethereum/pyethapp) - Python client using [pyethereum](https://github.com/ethereum/pyethereum)
* [Trinity](https://github.com/ethereum/trinity) - Python client using [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Ethereumj](https://github.com/ethereum/ethereumj) - Java client by the Ethereum Foundation
* [Harmony](https://github.com/ether-camp/ethereum-harmony) - Java client by EtherCamp
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"
* [Mustekala](https://github.com/MetaMask/mustekala) - Ethereum Light Client project of Metamask.
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://www.jpmorgan.com/quorum)
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir

#### Storage
* [Swarm](http://swarm-gateways.net/) - Swarm is a distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack
* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
* [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - IPFS Storage service with added search capability

#### Messaging
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other
* [DEVp2p Wire Protocol](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer

#### Wallets
* [Metamask](https://metamask.io/) - Easiest way to get started using a dapp. Chrome extension Ether wallet
* [Gnosis multisig wallet](https://github.com/gnosis/MultiSigWallet)
* [Mist](https://github.com/ethereum/mist) - Browse and use Dapps on the Ethereum network

#### Mobile Wallets
* [Toshi](https://github.com/toshiapp) - [Mobile](https://itunes.apple.com/us/app/toshi-ethereum-wallet/id1278383455?mt=8) Dapp explorer and wallet
* [Cypher](https://www.cipherbrowser.com/) - Mobile Dapp explorer
* [Trust](https://github.com/TrustWallet/trust-wallet-ios) - [Mobile](https://trustwalletapp.com/) wallet for ERC tokens
* [Status](https://github.com/status-im/status-react) - A free open-source, mobile OS for Ethereum

#### Block explorers
* [Etherscan](https://etherscan.io/) - most popular centralised way to view Eth transactions and contract code
* [Etherchain lite](https://github.com/gobitfly/etherchain-light)- Lightweight blockchain explorer for your private Ethereum chain

#### Services
* [MyEtherWallet](https://github.com/MyEtherWallet) - Open-source [tools](https://www.myetherwallet.com/) for interacting with the blockchains easily & securely
* [MyCrypto](https://github.com/MyCryptoHQ) - open-source, client-side [tool](https://mycrypto.com/account) for generating ether wallets, handling ERC-20 tokens, and interacting with the blockchain more easily
* [Portis](https://portis.io/) - web-based wallet for easy user on-boarding to your DApp, no download required
* [Oracalize](http://www.oraclize.it/)- oracle service for your smart contracts.
* [Infura](https://infura.io/) - API gateway so you don’t have to host your own ETH node
* [EthGasStation](https://ethgasstation.info/) - website for estimating tx prices vs times
* [Supermax](https://www.supermax.cool/)- A live data feed of the activities and event logs of your smart contracts on Ethereum
* [Eventeum](https://github.com/ConsenSys/eventeum) - A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri.
* [Regis](https://regis.nu/) - Registry Framework for Digital Assets
* [Viant](https://viant.io/) - Just consider using Viant as your backend if the use case is business process oriented.
* [uPort](https://www.uport.me/) - Total identity solution.
* [Ether Address Lookup](https://chrome.google.com/webstore/detail/etheraddresslookup/pdknmigbbbhmllnmgdfalmedcmcefdfn?hl=en-GB) - Chrome extension for phishing protection and Eth address highlighting
* [Netstats](https://github.com/cubedro/eth-netstats) - Ethereum Network [Stats](https://ethstats.net/)
* [Supermax](https://www.supermax.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum
* [ENS](https://github.com/ensdomains) - ENS offers a secure & decentralised way to address resources both on and off the blockchain using simple, human-readable [names](https://ens.domains/)
* [Name Bazaar](https://namebazaar.io/) - A peer-to-peer marketplace for the exchange of names registered via the Ethereum Name Service

#### Test faucets
* [Rinkeby faucet](https://faucet.rinkeby.io/)
* [Kovan faucet](https://github.com/kovan-testnet/faucet)

### Development
#### Languages
* [Solidity](http://solidity.readthedocs.io/en/latest/)- Ethereum smart contracting language
* [Bamboo](https://github.com/pirapira/bamboo) - A morphing smart contract language
* [Vyper](https://github.com/ethereum/vyper) - New experimental programming language

#### Tools
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - Solidity compiler
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
* [Ganache](https://github.com/trufflesuite/ganache) - App for test Ethereum blockchain with visual UI and logs
* [SpankCard](https://github.com/SpankChain/SpankCard) - An in-browser Ethereum wallet with support for payment channels
* [Parity signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions

#### Middleware
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
* [Web3.py ](https://github.com/ethereum/web3.py)- Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Eth.js](https://github.com/ethjs) - Javascript Web3 alternative
* [Ethers.js](https://github.com/ethers-io/ethers.js/)- Javascript Web3 alternative
* [Pyethereum](https://github.com/ethereum/pyethereum) - The Python core library of the Ethereum project.
* [Drizzle](https://github.com/truffle-box/drizzle-box) -  Redux library to connect a frontend to a blockchain

#### Frameworks
* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework
* [Embark](https://github.com/embark-framework/embark) - Framework for DApp development
* [Dapp](https://github.com/dapphub/dapptools/tree/master/src/dapp) - Framework for DApp development, successor to DApple
* [Populus](https://github.com/ethereum/populus) - The Ethereum development framework with the most cute animal pictures

#### Smart-Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - Contains tested reusable smart contracts like [SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html) and ZeppelinOS [library](https://github.com/zeppelinos/zos-lib) for smart contract upgradeability
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) -  A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol
* [0x](https://github.com/0xProject) - DEX protocol

#### IDEs
* [Remix](https://remix.ethereum.org/) - Web IDE with built in static analysis, test blockchain VM.
* [Atom](https://atom.io/) - Atom editor with [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom)
[autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), and [language-solidity](https://atom.io/packages/language-solidity) packages
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Vim syntax file for solidity

#### Testing
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Cliquebait simplifies integration and accepting testing of smart contract applications by offering a clean ephemeral testing environment that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts

#### Security
* [Mythril](https://github.com/ConsenSys/mythril) - Static smart contract security analysis
* [Oyente](https://github.com/melonproject/oyente)- Alternative static smart contract security analysis
* [Porosity](https://github.com/comaeio/porosity) - Decompiler and Security Analysis tool for Blockchain-based Ethereum Smart-Contracts
* [Ethersplay](https://github.com/trailofbits/ethersplay) - EVM disassembler
* [evmdis](https://github.com/Arachnid/evmdis) - alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns

### Knowledge
* [CryptoZombies](https://cryptozombies.io/) - The best undead tutorial in the world.
* [Solidity idiosyncrasies](https://github.com/miguelmota/solidity-idiosyncrasies) - Solidity gotchas, pitfalls, limitations, and idiosyncrasies
* [Ethereum development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little [book](https://goethereumbook.org) on Ethereum Development with Golang
* [Consensys Academy](https://consensys.net/academy/resources/) - Courses
* [B9Lab](https://academy.b9lab.com/) - Courses
* [Blockgeeks](https://courses.blockgeeks.com/) - Courses
* [Chainshot building blocks](https://www.chainshot.com/) - Courses
* [Delegate call](https://delegatecall.com/) - Q&A
* [Stackexchange](https://ethereum.stackexchange.com) - Q&A
* [Ethernaut](https://github.com/OpenZeppelin/ethernaut) - Web3/Solidity based wargame

#### Reference
* [Wiki](https://github.com/ethereum/wiki/wiki) - Ethereum wiki covering all things related to Ethereum
* [Yellow Paper](https://github.com/ethereum/yellowpaper) - The "Yellow Paper": Ethereum's formal specification
* [Beige Paper](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf) - Rewrite of the yellow paper in non-yellow-paper syntax
* [EthOn](https://github.com/ConsenSys/EthOn) - An ontology is a formalisation of concepts and relations within a domain. EthOn is written in RDF and OWL
* [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - by Andreas M. Antonopoulos, Gavin Wood
* [EVM opcodes](https://github.com/trailofbits/evm-opcodes) - Ethereum opcodes and instruction reference
* [EVM illustrated](http://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf) - This is an illustrated document about the Ethereum Virtual Machine
* [4bytes](https://github.com/ethereum-lists/4bytes) - List of 4byte identifiers to common smart contract functions [function signatures](https://www.4byte.directory/)

#### Best practices
* [Smart contract best practices](https://github.com/ConsenSys/smart-contract-best-practices) - by ConsenSys
* [Safety wiki](https://github.com/ethereum/wiki/wiki/Safety) - Ethereum Foundation wiki on safety

#### Governance
* [ethresear.ch](https://ethresear.ch/) - Semi-public forum for participating in Ethereum’s research efforts, including but not limited to: Casper, Sharding, EVM improvements, Crytpeconomics, Plasma and State-channels
* [Fellowship of Ethereum Magicians](https://ethereum-magicians.org/) - This discussion board facilitates meaningful communications among individuals throughout the Ethereum community
* [EIPs](http://eips.ethereum.org/) - The Ethereum Improvement Proposal repository

#### Standards
* [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository
* [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Fungible assets
* [ERC-721](https://github.com/ethereum/eips/issues/721) - A peek into debate and consensus-reaching on a token standard for non-fungible assets

#### Scaling
* [Comprehensive Medium article](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4) on various solutions to scale Ethereum

### Other
#### Bootstrap/out of box tools
* [Ethereum client binaries](https://github.com/ethereum/ethereum-client-binaries) - Download Ethereum client binaries for your OS
* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem
* [Solutions PoC starter app](https://github.com/ConsenSys/solutions-poc-starter) - Simple MERN stack with built in token use case, uPort signing, and more
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks
* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium network. Great for PoCs and testing.

#### Awesome lists
* [Awesome Cryptoeconomics](https://github.com/jpantunes/awesome-cryptoeconomics) - A curated list of cryptoeconomic research and learning materials
* [Awesome Solidity](https://github.com/bkrem/awesome-solidity) - A curated list of awesome Solidity resources, libraries, tools and more
* [Awesome EVM](https://github.com/pirapira/awesome-ethereum-virtual-machine) - Ethereum Virtual Machine Awesome List
* [Awesome State-Channels](https://github.com/machinomy/awesome-state-channels) - Curated list of resources regarding state channels on Ethereum.
* [DEX protocols](https://github.com/evbots/dex-protocols) - A list of protocols for decentralised exchange

#### Decentralised exchanges
* [Airswap](https://www.airswap.io/) - Decentralised token exchange
* 0x protocol based decentralised exchanges
    * [Radar relay](https://app.radarrelay.com/)
    * [ERC Dex](https://ercdex.com/)
* [Opensea.io](http://Opensea.io) -  Decentralised exchange of crypto-collectibles
* [Bancor](https://www.bancor.network/) - Decentralised exchange with stablecoin mechanism
* [Kyber](https://www.kyber.network) - Decentralised token exchange
* [Gnosis Dutch Exchange](https://github.com/gnosis/dx-contracts) - Decentralised token exchange with the Dutch auction principle

#### KYC/AML On-boarding
* SmartAML protospoke
* Third party centralised versions

#### Broken links and vaporware
* [ConsenSys clients](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)
* [Pantheon](https://github.com/ConsenSys/pantheon)
* [Paris Solutions stack](https://docs.google.com/presentation/d/1jpGX4tGlXHwRJXVKyM4fKEebxPZBiy2xgtidrGcbQng/edit) - Very private chain focused but production ready solution.
* [Alethio EthStats 2.0](https://media.consensys.net/alethio-lighting-up-the-blockchain-with-real-time-stats-a80bb30576db) - coming soon
* [Trustology](https://www.trustology.io/) - Under development. Institutional custody.
