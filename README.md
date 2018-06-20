# ethereum-developer-tools-list
A guide to available tools, components, patterns, and platforms for developing on Ethereum.

## Intro

Creation of this list was spurred by product managers at Consensys who saw a need for better sharing of tools, development patterns, and components amongst both new and experienced blockchain developers.

## Contributions are welcome!

Feel free to submit a pull request, with anything from small fixes to tools you'd like to add. If adding a new tool, **please add a brief description** that you think new developers would understand.


### Development frameworks

* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework

* [Embark](https://github.com/embark-framework/embark)- Framework for DApp development

* [Infura](https://infura.io/) - API gateway so you don’t have to host your own ETH node

### Security and analysis tools

* [Mythril](https://github.com/ConsenSys/mythril) - Static smart contract security analysis

* [Oyente](https://github.com/melonproject/oyente)- Static smart contract security analysis

* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - solidity code coverage tool

* [Quantstamp](https://quantstamp.com) A service that offers automated and manual smart contract security audits for a fee

### Decentralized storage

* [IPFS](https://ipfs.io/) - Decentralized storage and file referencing

* [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralized database on top of IPFS

### Developer IDE's and tools

* [Remix-](https://remix.ethereum.org/) Web IDE with built in static analysis, test blockchain VM.

* [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter)[-](https://atom.io/packages/etheratom) Atom package for Solidity linting

* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code extension that adds support for Solidity

* [Solc](https://solidity.readthedocs.io/en/v0.4.21/using-the-compiler.html?highlight=bin) - Solidity compiler

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graph debugger

* [py-eth](http://www.py-eth.com) - Collection of Python tools for the Ethereum ecosystem

### Programming Languages (for writing smart contracts, compiles to Ethereum Virtual Machine Bytecode)

* [Solidity](http://solidity.readthedocs.io/en/v0.4.24/) - Ethereum smart contracting language. Read the docs, play [CryptoZombies](https://cryptozombies.io/) and [Chainshot building blocks](https://www.chainshot.com/), or checkout [Consensys Academy](https://consensys.net/academy/resources/)

* [Vyper](https://vyper.readthedocs.io/en/latest/) - Experimental pythonic smart contracting language. Alternative to Solidity, but still under development.


### Front end Libraries

* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript

* [Ethers.js](https://github.com/ethers-io/ethers.js) - Javascript Ethereum wallet implementation and utilities

* [Eth.js](https://github.com/ethjs) - Lightweight alternative

* [Web3j](https://github.com/web3j/web3j) - Java

* [Nethereum](https://nethereum.com/) - .Net

* [Web3.py ](https://github.com/ethereum/web3.py)- python implementation of web3.js

* [Pyethereum](https://github.com/ethereum/pyethereum) - Python version of web3

* [Ethers.js](https://github.com/ethers-io/ethers.js/)- Web3 Alternative

* [Drizzle](https://github.com/trufflesuite/drizzle) -  Redux library to connect a frontend to a blockchain

* [Web3.hs](http://hackage.haskell.org/package/web3) - Haskell implementation of Web3


### Bootstrap/out of box tools

* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem

* [Solutions PoC Starter app](https://github.com/ConsenSys/solutions-poc-starter) - Simple MERN stack with built in token use case, uPort signing, and more.

* [Paris Solutions stack](https://docs.google.com/presentation/d/1jpGX4tGlXHwRJXVKyM4fKEebxPZBiy2xgtidrGcbQng/edit) - Very private chain focused but production ready solution.

* [Viant](https://viant.io/) - Just consider using Viant as your backend if the use case is business process oriented.

* [Kaleido](https://www.prnewswire.com/news-releases/consensys-unveils-kaleido-in-collaboration-with-amazon-web-services-to-simplify-enterprise-blockchain-adoption-300648209.html) - Use Kaleido for spinning up a consortium network. Great for PoCs and testing.

* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box

### Wallets

* [Metamask](https://metamask.io/) - Easiest way to get started using a dapp. Chrome extension Ether wallet.

* [Ether Address Lookup](https://chrome.google.com/webstore/detail/etheraddresslookup/pdknmigbbbhmllnmgdfalmedcmcefdfn?hl=en-GB) - Chrome extension for phishing protection and Eth address highlighting

* [Portis](https://portis.io/) - web-based wallet for easy user onboarding to your DApp, no download required

* [uPort](https://www.uport.me/) - Total identity solution.

* [Cypher](https://www.cipherbrowser.com/) - Mobile dapp explorer

* [Trust](https://trustwalletapp.com/)

* [Toshi](https://itunes.apple.com/us/app/toshi-ethereum-wallet/id1278383455?mt=8)

* [MyEtherWallet](https://www.myetherwallet.com/)

* [MyCrypto](https://mycrypto.com) - Ethereum blockchain interface. Access your wallet locally. Contract interaction and deployment. Swaps. Transaction status lookup. Testnet and 3rd-party ETH-based chain support.

* [Trustology](https://www.trustology.io/) - Under development. Institutional custody.

* [Jaxx](https://jaxx.io) Both a mobile and a desktop wallet. Has integrated Shapeshift support

* [Exodus](https://www.exodus.io) Desktop wallet with Shapeshift integration

* Gnosis multisig wallet

* [WallETH](https://walleth.org) - native Android Ethereum Wallet

* Hardware wallets

    * [Trezor](https://trezor.io) The original hardware wallet

    * [Ledger](https://www.ledgerwallet.com)

    * [KeepKey](https://www.keepkey.com)


### Ethereum clients

1. [Geth](https://github.com/ethereum/go-ethereum/wiki/geth)

2. [Parity](https://www.parity.io/)

3. [Quorum](https://www.jpmorgan.com/global/Quorum)

4. [Exthereum](https://gitter.im/exthereum/exthereum)

5. [Cpp-ethereum](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

6. [Pyethapp](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

7. [Py-evm](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

8. [Ethereumjs-vm](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

9. [Harmony/ethereumj (Java)](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

10. [ConsenSys clients](https://github.com/ethereum/wiki/wiki/Clients,-tools,-dapp-browsers,-wallets-and-other-projects#ethereum-clients)

    1. [Pantheon](https://github.com/ConsenSys/pantheon)

### Ethereum (test) faucets

* [Ropsten faucet](http://faucet.ropsten.be:3001/)

* [Rinkeby faucet](https://faucet.rinkeby.io/)

* [Kovan Faucet](https://github.com/kovan-testnet/faucet)

### Storage, Middleware, Etc.

* [Mustekala](https://github.com/MetaMask/mustekala) - blockchain services framework

* [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - IPFS Storage service with added search capability

* [Eventeum](https://github.com/ConsenSys/eventeum) - A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri.


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

* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)- contains tested reusable smart contracts like [SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html)

* [Aragon](https://github.com/aragon/aragon)

* [0x](https://github.com/0xProject)


### Other

* Block explorers
    * [Etherscan](https://etherscan.io/) - most popular centralized way to view Eth transactions and contract code

    * [POA Explorer](https://github.com/poanetwork/poa-explorer) - Open Source Ethereum Block explorer, funded by [Ethprize](ethprize.io) and developed by [POA](https://poa.net)

    * [Ganache](https://github.com/trufflesuite/ganache)- App for test Ethereum blockchain with visual UI and logs

    * [Etherchain lite](https://github.com/gobitfly/etherchain-light)- Lightweight blockchain explorer for your private Ethereum chain

    * [Alethio EthStats 2.0](https://media.consensys.net/alethio-lighting-up-the-blockchain-with-real-time-stats-a80bb30576db) coming soon

    * [Supermax](https://www.supermax.cool/)- A live data feed of the activities and event logs of your smart contracts on Ethereum

* Gas price calculators

   * [EthGasStation](https://ethgasstation.info/) - website for estimating tx prices vs times

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


## Ethereum knowledge

### Security best practices

* [Safety wiki](https://github.com/ethereum/wiki/wiki/Safety)- Ethereum Foundation wiki on safety

* [Smart contract best practices](https://github.com/ConsenSys/smart-contract-best-practices) - " “ published by Consensys

### Governance

 * [ERC-721](https://github.com/ethereum/eips/issues/721) - A peek into debate and consensus-reaching on a token standard for non-fungible assets
 * [Eth Research Chat](https://ethresear.ch) - Gitter-like forum for ongoing Ethereum Foundation research projects

### DApp development

 * [Ethereum Development with Go](https://goethereumbook.org/) - A guide on getting started on Ethereum DApp development with Golang.

## Scaling

 * [Comprehensive Medium article](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4) on various solutions to scale Ethereum
