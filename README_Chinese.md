# 以太坊开发者工具列表

这是一份关于在以太坊上开发应用程序的优质工具清单指南，其中包含一些工具、组件、应用、平台以及服务等。

该列表的创建受到ConsenSys产品经理的推动，他们认为有必要在初级开发与经验丰富的区块链开发人员之间更好地共享工具，开发模式和组件。

该资源旨在专注于开发人员工具，但还包括一些生态系统资源：

[以太坊生态系统资源](EcosystemResources_Chinese.md)，关于有用的DApp，教育资源，钱包和服务。


## 欢迎捐款！

可以随意拉取并提交请求，补充您想要添加（或删除！）的工具。如果添加新工具，请添加您认为新开发人员会理解的简短描述。

感谢众多贡献者包括@corbpage和@pakaplace为Meridio做出的贡献，并感谢@jpantunes以更合理的方式重组清单列表。

- 没有有效产品的项目将不会被添加。

- 不推荐使用或不再维护的项目将被删除。

- 没有开放源代码或开发者审核发现是付费/受限制服务的项目将得到进一步审查。

^以上规则公平吗？在此处分享您的想法： 

https://github.com/ConsenSys/ethereum-developer-tools-list/pull/70
 

## 目录
- [以太坊开发者工具列表](#以太坊开发者工具列表)
  - [欢迎捐款！](#欢迎捐款！)
  - [目录](#目录)
  - [新开发者从这里开始](#新开发者从这里开始)
  - [开发者工具](#开发者工具)
    - [开发智能合约](#开发智能合约)
      - [智能合约语言](#智能合约语言)
      - [框架](#框架)
      - [集成开发环境](#集成开发环境)
    - [其他工具](#其他工具)
    - [测试区块链网络](#测试区块链网络)
      - [测试以太币水龙头](#测试以太币水龙头)
    - [与以太坊通信](#与以太坊通信)
      - [前端以太坊API](#前端以太坊API)
      - [后端以太坊API](#后端以太坊API)
      - [开箱即用工具](#开箱即用工具)
      - [以太坊ABI（应用程序二进制接口）工具](#以太坊ABI（应用程序二进制接口）工具)
      - [模式和最佳做法](#模式和最佳做法)
        - [智能合约开发的模式](#智能合约开发的模式)
        - [可升级性](#可升级性)
    - [基础设施](#基础设施)
      - [以太坊客户端](#以太坊客户端)
      - [存储](#存储)
      - [讯息传递](#讯息传递)
    - [测试工具](#测试工具)
    - [安全工具](#安全工具)
    - [监控方式](#监控方式)
    - [其他杂项工具](#其他杂项工具)
    - [智能合约标准和类库](#智能合约标准和类库)
      - [ERC-以太坊评论提案库](#ERC-以太坊评论提案库)
      - [流行的智能合约库](#流行的智能合约库)
    - [第二层基础架构开发人员指南](#第二层基础架构开发人员指南)
      - [可扩展性](#可扩展性)
      - [付款渠道](#付款渠道)
      - [Plasma](#Plasma)
      - [侧链](#侧链)
      - [隐私/保密](#隐私/保密)
        - [zkSNARKs](#zkSNARKs)
      - [预建的UI组件](#预建的UI组件)

## 新开发者从这里开始
* [Solidity](https://solidity.readthedocs.io/en/latest/) - 最受欢迎的智能合约语言。
* [Truffle](https://trufflesuite.com/) - 最受欢迎的智能合约开发，测试和部署框架。通过npm安装cli，然后从此处开始编写您的第一个智能合约。
* [Metamask](https://metamask.io/) - Chrome扩展程序钱包，可与Dapps进行交互。
* [Truffle boxes](https://trufflesuite.com/boxes) - 以太坊生态系统的打包组件。
* [OpenZeppelin Starter Kits](https://openzeppelin.com/starter-kits/) - 开发人员的多合一入门组件，可快速启动其受智能合约支持的应用程序。包括Truffle，OpenZeppelin SDK，OpenZeppelin / contracts-ethereum-package EVM经审核的智能合约EVM软件包，react-app和rimble，易于设计。
* [EthHub.io](https://docs.ethhub.io/) - 以太坊的全面信息概述-它的历史，治理，未来计划和开发资源。
* [EthereumDev.io](https://ethereumdev.io) - 关于以太坊智能合约编程入门的权威指南。
* [Cobra](https://github.com/cobraframework/cobra) - 一个快速，灵活，简单的以太坊智能合约开发环境的框架。将智能合约，测试和部署到以太坊虚拟机（EVM）上。
* [Kauri.io](https://kauri.io/) - 基于Web3的社区和新兴技术的知识平台。分享精选内容，并就最新，高质量的技术文章和系列进行协作。 请查看[“入门”社区](https://kauri.io/community/5d9b16fc890d310001b66e1b)以学习基础知识。
* [dfuse](https://dfuse.io) - Slick 区块链 API 可以构建世界一流的应用程序。
* [Biconomy](https://biconomy.io) - 通过使用简单易用的SDK启用元交易来在dapp中进行无Gas交易。

## 开发者工具
### 开发智能合约
#### 智能合约语言
* [Solidity](https://solidity.readthedocs.io/en/latest/) - 以太坊智能合约编程语言。
* [Vyper](https://vyper.readthedocs.io/en/latest/) - 新的实验性类python编程语言。

#### 框架
* [Truffle](https://trufflesuite.com/) - 最受欢迎的智能合约开发，测试和部署框架。Truffle套件包括 Truffle, [Ganache](https://github.com/trufflesuite/ganache), 和 [Drizzle](https://github.com/truffle-box/drizzle-box). [在这里深入了解松露](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Embark](https://github.com/embark-framework/embark) - DAPP开发框架
* [Waffle](https://getwaffle.io/) - 先进的智能合同开发和测试框架，体积小，灵活，快捷（基于ethers.js）
* [Dapp](https://dapp.tools/dapp/) - DApp开发的框架，DApple的继承者
* [Etherlime](https://github.com/LimeChain/etherlime) - 基于ethers.js的框架用于Dapp部署
* [Parasol](https://github.com/Lamarkaz/parasol) - 敏捷的智能合同开发环境，测试，部署INFURA，合约文件等。它具有灵活，不受限制的设计以及无限的可定制性。
* [0xcert](https://github.com/0xcert/framework/) - 用于构建去中心化应用程序的JavaScript框架
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - OpenZeppelin SDK：一套工具，可帮助您开发，编译，升级，部署智能合约并与之交互。
* [sbt-ethereum](https://sbt-ethereum.io/) - 一个基于选项卡的，基于文本的控制台，用于智能合约的交互和开发，包括钱包和ABI管理，ENS支持和高级Scala集成。
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie是一个Python框架，用于部署，测试以太坊智能合约并与之交互。
* [Cobra](https://github.com/cobraframework/cobra) - 一个快速，灵活，简单的开发环境的框架，用于以太坊智能合约的测试和部署。

#### 集成开发环境
* [Remix](https://remix.ethereum.org/) - 具有内置静态分析功能的Web IDE，测试区块链虚拟机。
* [Ethereum Studio](https://studio.ethereum.org/) - Web IDE。浏览器内置区块链虚拟机，集成Metamask（一键部署到Testnet / Mainnet），事务记录器和实时编码Web App等众多其他功能。
* [Atom](https://atom.io/) - Atom 编辑器包含 [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom), [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), and [language-solidity](https://atom.io/packages/language-solidity) 等包。
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Vim 语法文件支持Solidity。
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code插件，增加了对Solidity的支持。
* [Ethcode](https://marketplace.visualstudio.com/items?itemName=quantanetwork.ethcode) - Visual Studio Code插件，用于编译，执行和调试Solidity＆Vyper程序。
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/)（免费/商业）的开源插件，具有语法突出显示，格式设置，代码补全等功能。 
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - 基于Eclipse的IDE插件。具有上下文相关的代码补全和帮助提示，代码导航，语法着色，内置编译器，快速修复和模板的功能。
* [Eth Fiddle](https://ethfiddle.com/) - 由[The Loom Network](https://loomx.io/)开发的IDE ，可让您编写，编译和调试智能合约。易于共享和查找代码片段。

### 其他工具
* [Atra Blockchain Services](https://console.atra.io) - Atra提供Web服务来帮助您在以太坊区块链上构建，部署和维护去中心化应用程序。
* [Buidler](https://buidler.dev/) - 可扩展的开发人员工具，可通过可靠地整合所需工具来帮助智能合约开发人员提高生产率。
* [Azure Blockchain Dev Kit for Ethereum for VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain) - VS Code 插件允许创建智能合约并将其部署到区块链中。

### 测试区块链网络
* [ethnode](https://github.com/vrde/ethnode) - 运行以太坊节点（Geth）进行开发，简单执行 `npm i -g ethnode && ethnode`.
* [Ganache](https://github.com/trufflesuite/ganache) - 具备UI和日志的区块链测试应用
* [Kaleido](https://kaleido.io/) - 使用Kaleido来建立联盟区块链网络。非常适合PoC和测试
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - 在Docker容器中运行Besu节点的专用网络[Orion](https://github.com/PegaSysEng/orion) -PegaSys进行私人交易的组件 [Artemis](https://github.com/PegaSysEng/artemis) - PegaSys的以太坊2.0信标链的Java实现。
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - 使用类似于真实区块链网络的docker实例简化智能合约应用程序的集成和测试
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - 在Docker容器中运行本地Raiden网络以进行演示和测试
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - 专用PoA网络的现成部署脚本
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - 专用PoW网络的现成部署脚本
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain/templates/ethereum-poa-deployment) - 联盟以太坊PoA网络的部署和治理
* [Ethereum on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - 基于工作量证明构建以太坊网络
* [Infura](https://infura.io/) -以太坊API访问以太坊网络（Mainnet，Ropsten，Rinkeby，Goerli，Kovan）
* [CloudFlare Distributed Web Gateway](https://cloudflare.com/distributed-web-gateway/) - 通过Cloudflare提供对以太坊网络的访问，而不是运行自己的节点
* [Chainstack](https://chainstack.com/) - 共享和专用的以太坊节点即服务（Mainnet，Ropsten）

#### 测试以太币水龙头
* [Rinkeby 水龙头](https://faucet.rinkeby.io/)
* [Kovan 水龙头](https://github.com/kovan-testnet/faucet)
* [Ropsten 水龙头](https://faucet.metamask.io/)
* [Goerli 水龙头](https://goerli-faucet.slock.it/)
* [Universal 水龙头](https://faucets.blockxlabs.com/)
* [Nethereum 水龙头](https://github.com/Nethereum/Nethereum.Faucet) - 一个 C#/.NET 水龙头

### 与以太坊通信
#### 前端以太坊API
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
* [Eth.js](https://github.com/ethjs) - Javascript Web3替代者
* [Ethers.js](https://github.com/ethers-io/ethers.js/) - Javascript Web3替代，有用的实用程序和钱包功能
* [light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js) 为轻客户端优化的高级反应式JS库。
* [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper) - Typescript Web3替代者
* [Ethereumjs](https://github.com/ethereumjs/) - 以太坊的实用程序功能集合，例如[ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util)和[ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)
* [flex-contract](https://github.com/merklejerk/flex-contract) 和 [flex-ether](https://github.com/merklejerk/flex-ether) - 零配置的高级库，用于与智能合约进行交互并进行交易。
* [ez-ens](https://github.com/merklejerk/ez-ens) - ens-简单的零配置以太坊域名服务地址解析器。
* [web3x](https://github.com/xf00f/web3x) - web3.js的TypeScript端口。好处包括小巧的构造和全类型的安全性，包括与合同进行交互时的安全性。
* [Nethereum](https://github.com/Nethereum/) - 跨平台的以太坊开发框架
* [dfuse](https://github.com/dfuse-io/client-js) - 使用TypeScript实现的[dfuse Ethereum API](https://dfuse.io) 以太坊API库 
* [Drizzle](https://github.com/truffle-box/drizzle-box) - Redux库将前端连接到区块链
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) -一个React Native库，使用在移动端与以太坊进行交互。
* [Subproviders](https://0x.org/docs/tools/subproviders) - 与[Web3-provider-engine](https://github.com/MetaMask/web3-provider-engine)  结合使用的几个有用的子提供商（包括用于向您的dApp添加Ledger硬件钱包）
* [ethvtx](https://github.com/ticket721/ethvtx) - 支持以太坊＆框架无关的Redux存储配置。[文档](https://ticket721.github.io/ethvtx/)
* 严格类型-Javascript 替代者
    * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
    * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
* [ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer) - 使用单个界面与不同的区块链（包括以太坊）进行通信。
* [Delphereum](https://github.com/svanas/delphereum) - 以太坊区块链的Delphi接口，允许开发适用于Windows，macOS，iOS和Android的dApp开发。
* [Torus](https://tor.us/) - 源SDK构建dapps的无缝衔接的UX
* [Fortmatic](https://fortmatic.com/) - 一种易于使用的SDK，无需扩展或下载即可构建web3 dApp。
* [Portis](https://portis.io/) - 具有SDK的非托管钱包，可轻松与DApp进行交互而无需安装任何东西。

#### 后端以太坊API
* [Web3.py](https://github.com/ethereum/web3.py) - Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/komputing/KEthereum) - Kotlin Web3
* [Eventeum](https://github.com/ConsenSys/eventeum) - A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - Elixir JSON-RPC client for the Ethereum blockchain
* [Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway) - A gateway that allows you to run multiple Ethereum nodes for redundancy and load-balancing purposes. Can be ran as an alternative to (or on top of) Infura. Written in Golang. 
* [EthContract](https://github.com/AgileAlpha/eth_contract) - A set of helper methods to help query ETH smart contracts in Elixir
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - A MESG Service to interact with any Ethereum contract based on its address and ABI.
* [Ethereum Service](https://github.com/mesg-foundation/service-ethereum) - A MESG Service to interact with events from Ethereum and interact with it.
* [Marmo](https://marmo.io/) - Python, JS, and Java SDK for simplifying interactions with Ethereum. Uses relayers to offload transaction costs to relayers.

#### Bootstrap/Out-of-Box tools
* [Truffle boxes](https://trufflesuite.com/boxes) - Packaged components for the Ethereum ecosystem
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - Run a private network of Besu nodes in a Docker container
* [Testchains](https://github.com/Nethereum/TestChains) - Pre-configured .NET devchains for fast response (PoA) 
** [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - Wasm blockchain explorer (functional sample)
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - Step-by-Step tutorial for building a PoA test chain with 2 nodes with Parity authority round consensus
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks
* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium blockchain network. Great for PoCs and testing
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [aragonCLI](https://github.com/aragon/aragon-cli) - aragonCLI is used to create and develop Aragon apps and organizations.
* [ColonyJS](https://github.com/JoinColony/colonyJS) - JavaScript client that provides an API for interacting with the Colony Network smart contracts.
* [ArcJS](https://github.com/daostack/arc.js) - Library that facilitates javascript application access to the DAOstack Arc ethereum smart contracts.
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - JavaScript client that provides an API for interacting with Arkane Network, a wallet provider for building user-friendly dapps.
* [Blocknative](https://blocknative.com) - Assist.js is an embeddable widget that improves Dapp usability. The tool programmatically identifies and outlines clear actions for end-users to follow when interacting with MetaMask to overcome — and even prevent — common pitfalls and obstacles.
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - React framework for building single-page Ethereum dApps

#### Ethereum ABI (Application Binary Interface) tools
* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - library for decoding data params and events from Ethereum transactions
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen) - Generate Typescript contract wrappers from contract ABI's.
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Auto-generate UI form field definitions and associated validators from an Ethereum contract ABI
* [headlong](https://github.com/esaulpaugh/headlong/) - type-safe Contract ABI and Recursive Length Prefix library in Java
* [One Click dApp](https://oneclickdapp.com) - Instantly create a dApp at a unique URL using the ABI.
* [Truffle Pig](https://npmjs.com/package/trufflepig) - a development tool that provides a simple HTTP API to find and read from Truffle-generated contract files, for use during local development. Serves fresh contract ABIs over http.
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - A MESG Service to interact with any Ethereum contract based on its address and ABI.
* [Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - A web based generator which creates a Nethereum based C# Interface and Service based on Solidity Smart Contracts.

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
* [EIP-2535 Diamond Standard](https://eips.ethereum.org/EIPS/eip-2535)
    * Organize contracts so they share the same contract storage and Ethereum address.
    * Solves the 24KB max contract size limit.
    * Upgrade diamonds by adding/replacing/removing any number of functions in a single transaction.
    * Upgrades are transparent by recording them with a standard event.
    * Get information about a diamond with events and/or four standard functions.

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
* [Besu](https://besu.hyperledger.org/en/latest/) - an open-source Ethereum client developed under the Apache 2.0 license and written in Java. The project is hosted by Hyperledger.
* [Geth](https://geth.ethereum.org/docs/) - Go client
* [Parity](https://www.parity.io/ethereum/) - Rust client
* [Aleth](https://github.com/ethereum/aleth) - C++ client
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core client
* [Infura](https://infura.io/) - A managed service providing Ethereum client standards-compliant APIs
* [Trinity](https://trinity.ethereum.org/) - Python client using [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"
* [Mustekala](https://github.com/musteka-la/mustekala) - Ethereum Light Client project of Metamask
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir client
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - Energy Web Foundation client for the Tobalaba test network
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://jpmorgan.com/quorum)
* [Mana](https://github.com/mana-ethereum/mana) - Ethereum full node implementation written in Elixir.
* [Chainstack](https://chainstack.com/) - A managed service providing shared and dedicated Geth nodes
* [QuikNode](https://quiknode.io/) - Blockchain developer cloud with API access and node-as-a-service.


#### Storage
* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
   * [Mahuta](https://github.com/ConsenSys/Mahuta) - IPFS Storage service with added search capability, formerly IPFS-Store
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralised database on top of IPFS
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - A client library for the IPFS HTTP API, implemented in JavaScript
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - Easy to use API into IPFS and other distributed/decentralised storage protocols
   * [PINATA](https://pinata.cloud) - The Easiest Way to Use IPFS
* [Swarm](https://swarm-gateways.net/) - Distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack
* [Infura](https://infura.io/) - A managed IPFS API Gateway and pinning service
* [3Box Storage](https://docs.3box.io/api/storage) - An api for user controlled, distrubuted storage. Built on top of IPFS and Orbitdb.


#### Messaging
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack
* [DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer
* [3Box Threads](https://docs.3box.io/api/messaging) - API to allow developers to implement IPFS persisted, or in memory peer to peer messaging.

### Testing Tools
* [Truffle Teams](https://trufflesuite.com/teams) - Zero-Config continuous integration for truffle projects
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - Alternative and updated Solidity smart contract profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - Speed up your development with human readable stack traces
* [Solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation
* [Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in Solidity, formerly Solium
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - An npm package with additional assertions and utilities used in testing Solidity smart contracts with truffle. Most importantly, it adds the ability to assert whether specific events have (not) been emitted.
* [Psol](https://github.com/Lamarkaz/psol) - Solidity lexical preprocessor with mustache.js-style syntax, macros, conditional compilation and automatic remote dependency inclusion.
* [solpp](https://github.com/merklejerk/solpp) - Solidity preprocessor and flattener with a comprehensive directive and expression language, high precision math, and many useful helper functions.
* [Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) – Decode and publish raw ethereum tx. Similar to https://live.blockcypher.com/btc-testnet/decodetx/
* [Doppelgänger](https://getdoppelganger.io/) - a library for mocking smart contract dependencies during unit testing.
* [rocketh](https://github.com/wighawag/rocketh) - A simple lib to test ethereum smart contract that allow to use whatever web3 lib and test runner you choose.
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - PyTest plugin for testing smart contracts for Ethereum blockchain.

### Security Tools
* [MythX](https://mythx.io/) - Security verification platform and tools ecosystem for Ethereum developers
* [Mythril](https://github.com/ConsenSys/mythril) - Open-source EVM bytecode security analysis tool
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.chainsecurity.com/) - Security scanner for Ethereum smart contracts
* [SmartCheck](https://tool.smartdec.net/) - Static smart contract security analyzer
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Slither](https://github.com/crytic/slither) - A Solidity static analysis framework
* [Adelaide](https://github.com/sec-bit/adelaide) - The SECBIT static analysis extension to Solidity compiler
* [solc-verify](https://github.com/SRI-CSL/solidity/) - A modular verifier for Solidity smart contracts
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Free smart contract security audits from Callisto Network
* [Piet](https://piet.slock.it) - A visual Solidity architecture analyzer

### Monitoring
* [Alethio](https://aleth.io/) - An advanced Ethereum analytics platform that provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search. Real-time market information and trading activities across Ethereum's decentralized exchanges can also be explored.
* [amberdata.io](https://amberdata.io) - Provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search.
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Scout](https://scout.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum
* [Tenderly](https://tenderly.co/) - A platform that gives users reliable smart contract monitoring and alerting in the form of a web dashboard without requiring users to host or maintain infrastructure
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Explore smart contracts with decoded transaction data, see how the contract is used and search transactions with specific function calls
* [BlockScout](https://github.com/poanetwork/blockscout) - A tool for inspecting and analyzing EVM based blockchains. The only full featured blockchain explorer for Ethereum networks.
* [Terminal](https://terminal.co/) - A control panel for monitoring dapps. Terminal can be used to monitor your users, dapp, blockchain infrastructure, transactions and more.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - An extensible framework written in Golang for listening to on-chain events and doing something in response.

### Other Miscellaneous Tools
* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - a decentralized package manager powered by aragonOS and Ethereum. aragonPM enables decentralized governance over package upgrades, removing centralized points of failure.
* [Truffle boxes](https://www.trufflesuite.com/boxes) - Packaged components for building DApps fast.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html) - Solidity compiler
* [Sol-compiler](https://sol-compiler.com/) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternative, merges all imports into single file for solidity contracts
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [eth-cli](https://github.com/protofire/eth-cli) - A collection of CLI tools to help with ethereum learning and development
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://py-eth.com) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Typescript bindings for Ethereum smartcontracts
* [EthSum](https://ethsum.netlify.com) - A Simple Ethereum Address Checksum Tool
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - allows indexing blocks or listening to Events in PHP
* [Purser](https://github.com/JoinColony/purser) - JavaScript universal wallet tool for Ethereum-based wallets. Supports software, hardware, and Metamask -- brings all wallets into a consistent and predictable interface for dApp development.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - Connect to MetaMask from node.js
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Export Ethereum blockchain data to CSV or JSON files
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for formatting Solidity code
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Ethereum and Unity integration demo
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Ethereum and Unity integration demo/sample
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum business rules engine demo/sample
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - A set of tools to standarize Solidity import and artifact resolution in frameworks.
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - A node and browser tool to inspect transactions - decoding where possible the method, event logs and any revert reasons using ABIs found online. 
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - A useful library written in Golang to reliably send a transaction — abstracting away some of the tricky low level details such as gas optimization, nonce calculations, synchronization, and retries.
* [truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Seamlessly verify contract source code on Etherscan from the Truffle command line.

### Smart Contract Standards & Libraries
#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository
* Tokens
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Original token contract for fungible assets
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - Token standard for non-fungible assets
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - An improved token standard for fungible assets
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - Mineable Token Standard
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - Creates a standard method to publish and detect what interfaces a smart contract implements.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - Proxy contract for key management and execution, to establish a Blockchain identity.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - A standard interface for ownership of contracts

#### Popular Smart Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - Contains tested reusable smart contracts like SafeMath and OpenZeppelin SDK [library](https://github.com/OpenZeppelin/openzeppelin-sdk) for smart contract upgradeability
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - A collection of Solidity libraries for building secure and gas-efficient smart contracts on Ethereum.
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) - A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol. Contains [aragonOS smart contract framework](https://github.com/aragon/aragonOS) with focus on upgradeability and governance
* [ARC](https://github.com/daostack/arc) - an operating system for DAOs and the base layer of the DAO stack.
* [0x](https://github.com/0xProject) - DEX protocol
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - Contains correctness proofs of token contracts wrt. given specifications and high-level properties
* [Provable API](https://github.com/provable-things/ethereum-api) - Provides contracts for using the Provable service, allowing for off-chain actions, data-fetching, and computation
* [ABDK Libraries for Solidity](https://github.com/abdk-consulting/abdk-libraries-solidity) - Fixed-point (64.64 bit) and IEEE-754 compliant quad precision (128 bit) floating-point math libraries for Solidity


### Developer Guides for 2nd Layer Infrastructure

#### Scalability



#### Payment/State Channels
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Ethereum Payment Channel in 50 lines of code
* [µRaiden Documentation](https://microraiden.readthedocs.io) - Guides and Samples for µRaiden Sender/Receiver Use Cases

#### Plasma
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - Website as Node application that was started at the 2018 IC3-Ethereum Crypto Boot Camp at Cornell University, covering all Plasma variants (MVP/Cash/Debit)
* [Plasma MVP](https://github.com/omisego/plasma-contracts) - OmiseGO's research implementation of Minimal Viable Plasma
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Golang implementation and extension of the Minimum Viable Plasma specification
* [Plasma Guard](https://github.com/mesg-foundation/plasma-guard) - Automatically watch and challenge or exit from Omisego Plasma Network when needed.
* [Plasma OmiseGo Watcher](https://github.com/mesg-foundation/service-plasma-omisego-watcher) - Interact with Plasma OmiseGo network and notifies for any byzantine events.

#### Side-Chains
* [POA Network](https://www.poa.network/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)
* [Matic Network](https://docs.matic.network/)

#### Privacy / Confidentiality

##### ZK-SNARKs
* [ZoKrates](https://github.com/Zokrates/ZoKrates) - A toolbox for zkSNARKS on Ethereum
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - Confidential transactions on the Ethereum network, implementation is live on the Ethereum main-net
* [Nightfall](https://github.com/EYBlockchain/nightfall) - Make any ERC-20 / ERC-721 token private - open source tools & microservices
* Proxy Re-encryption (PRE)
** [NuCypher Network](https://github.com/nucypher/nucypher) - A proxy re-encryption network to empower data privacy in decentralized systems
** [pyUmbral](https://github.com/nucypher/pyumbral) - Threshold proxy re-encryption cryptographic library
* Fully Homomorphic Encryption (FHE)
** [NuFHE](https://github.com/nucypher/nufhe) - GPU accelerated FHE library

#### Scalability + Privacy

#### ZK-STARKs
* [StarkWare](https://github.com/starkware-industries) and [StarkWare Resources](https://github.com/starkware-libs) - StarkEx scalability engine storing state transitions on-chain

#### Prebuilt UI Components
* [aragonUI](https://ui.aragon.org) - A React library including Dapp components
* [components.bounties.network](https://components.bounties.network) - A React library including Dapp components
* [ui.decentraland.org](https://github.com/decentraland/ui) - A React library including Dapp components
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Reusable React Dapp components
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React Components
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - A cross-platform hybrid hosting mechanism for web based decentralised applications
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - Cross-platform desktop wallet sample
* [eth-button](https://eth-button.github.io/eth-button/) - Minimalist donation button
* [Rimble Design System](https://rimble.consensys.design/) - Adaptable components and design standards for decentralized applications.
* [3Box Plugins](https://docs.3box.io/build/plugins) - Drop in react components for social functionality. Including comments, profiles and messaging.
