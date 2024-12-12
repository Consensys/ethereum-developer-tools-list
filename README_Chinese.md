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
* [EVMTools](https://evmtools.xyz) - 面向Web3和Solidity开发者的EVM工具包，所有开发工具集中在一个地方。它有20多个实用工具，并且经常添加新的工具。

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
* [Holesky 水龙头](https://stakely.io/en/faucet/ethereum-holesky-testnet-eth)
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
* [useMetamask](https://github.com/mdtanrikulu/use-metamask) - 一个自定义的React Hook来管理以太坊ĐApp项目中的Metamask
* [WalletConnect](https://walletconnect.org/) - 用于将电子钱包连接到分散应用程序（DApp）的开放协议
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
* [ethers-kt](https://github.com/Kr1ptal/ethers-kt) - 用于与基于EVM的区块链交互的异步、高性能Kotlin库。面向JVM和Android平台。
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/komputing/KEthereum) - Kotlin Web3
* [web3dart](https://github.com/xclud/web3dart) - Dart Web3
* [Eventeum](https://github.com/ConsenSys/eventeum) - 由Kauri用Java编写的以太坊智能合约事件和后端微服务之间的桥梁
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - 以太坊区块链的Elixir JSON-RPC客户端
* [Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway) - 一个网关，允许您运行多个以太坊节点以实现冗余和负载平衡。可以作为Infura的替代品（或在其之上）运行。用Golang写的。
* [EthContract](https://github.com/AgileAlpha/eth_contract) - 一组帮助在Elixir中查询ETH智能合约的助手方法
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - 一种MESG服务，可根据其地址和ABI与任何以太坊合约进行交互。
* [Ethereum Service](https://github.com/mesg-foundation/service-ethereum) - 一种MESG服务，用于与以太坊中的事件进行交互并与其进行交互。
* [Marmo](https://marmo.io/) - Python，JS和Java SDK，以简化与以太坊的交互。使用中继器将交易成本分担给中继器。

#### 开箱即用工具
* [Truffle boxes](https://trufflesuite.com/boxes) - 以太坊生态系统的打包组件
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - 在Docker容器中运行Besu节点的专用网络
* [Testchains](https://github.com/Nethereum/TestChains) - 用于快速响应（PoA）的预配置由.NET开发
* [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - Wasm区块链浏览器（功能示例）
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - 在Docker容器中运行本地Raiden网络以进行演示和测试
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - 专用PoA网络的现成部署脚本
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - 分步教程，用于构建具有2个节点且具有Parity授权回合共识的PoA测试链
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - 专用PoW网络的现成部署脚本
* [Kaleido](https://kaleido.io/) - 使用Kaleido来建立联盟区块链网络。非常适合PoC和测试
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties API和智能合约的本地沙盒实现，可以作为松露盒使用
* [aragonCLI](https://github.com/aragon/aragon-cli) - aragonCLI用于创建和开发Aragon应用程序和组织。
* [ColonyJS](https://github.com/JoinColony/colonyJS) - JavaScript客户端，提供用于与Colony Network智能合约进行交互的API。
* [ArcJS](https://github.com/daostack/arc.js) - 便于javascript应用程序访问DAOstack Arc以太坊智能合约的库。
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - JavaScript客户端，提供用于与Arkane Network进行交互的API，Arkane Network是用于构建用户友好的dapp的钱包提供商。
* [Blocknative](https://blocknative.com) - Assist.js是可嵌入的小部件，可提高Dapp的可用性。该工具以编程方式识别并概述了清晰的操作，供最终用户在与MetaMask进行交互时应遵循的操作，以克服（甚至防止）常见的陷阱和障碍。
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - 用于构建单页以太坊dApp的React框架

#### 以太坊ABI（应用程序二进制接口）工具
* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - 用于解码以太坊交易中的数据参数和事件的库
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen) - gen-从合同ABI生成Typescript合同包装。
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - UI-从以太坊合约ABI自动生成UI表单字段定义和相关的验证器
* [headlong](https://github.com/esaulpaugh/headlong/) - Java中类型安全的合约ABI和递归长度前缀库
* [One Click dApp](https://oneclickdapp.com) - 使用ABI在唯一的URL上快速的创建dApp前端页面。
* [Truffle Pig](https://npmjs.com/package/trufflepig) - 一种开发工具，提供简单的HTTP API来查找和读取Truffle生成的合同文件，以便在本地开发期间使用。通过http提供新的合同ABI。
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - 一种MESG服务，可根据其地址和ABI与任何以太坊合约进行交互。
* [Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - CodeGenerator-基于Web的生成器，可基于Solidity智能合约创建基于Nethereum的C＃接口和服务。

#### 模式和最佳做法

##### 智能合约开发的模式
* [Dappsys：安全，简单和灵活的以太坊合约构建模块](https://github.com/dapphub/dappsys)
    * 有针对以太坊/Solidity常见问题的解决方案，例如。
        * [白名单](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [可升级的ERC20代币](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-令牌库](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [验证（RBAC）](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...更多...](https://github.com/dapphub/dappsys)
    * 为[MakerDAO](https://github.com/makerdao/maker-otc)或[The TAO](https://github.com/ryepdx/the-tao)提供构建块
    * 在创建自己的未经测试的解决方案之前，应咨询该公司
    * [Dapp-a-day 1-10](https://steemit.com/@nikolai) 和 [Dapp-a-day 11-25](https://steemit.com/@nexusdev)中描述了用法
* [OpenZeppelin合同：以Solidity语言编写的可重用和安全智能合同的开放框架。](https://github.com/OpenZeppelin/openzeppelin-contracts)
    * 可能是使用最广泛的安全库和智能合约库
    * 与Dappsys相似，更多地集成到Truffle框架中了
    * [有关安全审核最佳做法的博客](https://blog.openzeppelin.com/)
* [装配高级车间](https://github.com/androlo/solidity-workshop)
* [更简单的以太坊Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - 特点是 _Benefits_
* [CryptoFin Solidity审核清单](https://github.com/cryptofinlabs/audit-checklist) - 常见发现清单，以及审核主网启动合同时要注意的问题。
* [aragonOS：用于构建DAO，Dapp和协议的智能合约框架](https://hack.aragon.org/docs/aragonos-intro.html)
    * 可升级性：智能合约可以升级到新版本
    * 权限控制：通过使用`auth`和`authP`修饰符，您可以保护功能，以便只有其他应用或实体才能访问它
    * 转发器：aragonOS应用程序可以将其执行操作的意图发送给其他应用程序，以便在满足一组要求的情况下转发意图
* [EIP-2535钻石标准](https://eips.ethereum.org/EIPS/eip-2535)
    * 组织合同，使它们共享相同的合同存储和以太坊地址。
    * 解决最大24KB的合同大小限制。
    * 通过在单个事务中添加/替换/删除任意数量的功能来升级钻石。
    * 通过使用标准事件记录升级，透明性是透明的。
    * 获取有关具有事件和/或四个标准功能的钻石的信息。

##### 可升级性
* [博客von Elena Dimitrova，开发者位于Colony.io](https://blog.colony.io/author/elena/)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Aragon 研究博客](https://blog.aragon.org/tag/research/)
    * [开发库及其发展](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
    * [先进的Solidity代码部署技术](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelin on Proxy Libraries](https://blog.openzeppelin.com/proxy-libraries-in-solidity-79fbe4b970fd/)

### 基础设施
#### 以太坊客户端
* [Besu](https://besu.hyperledger.org/en/latest/) - 在Apache 2.0授权开发和用Java编写的开源以太坊客户端。该项目由Hyperledger托管。
* [Geth](https://geth.ethereum.org/docs/) - Go客户端
* [Parity](https://www.parity.io/ethereum/) - Rust客户端
* [Aleth](https://github.com/ethereum/aleth) - C++ 客户端
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET 客户端
* [Infura](https://infura.io/) - 一种托管服务，提供符合以太坊客户端标准的API
* [Trinity](https://trinity.ethereum.org/) -使用Python客户端 [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - 使用[ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)的JS客户端
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth是一个以太坊客户端工具，就像“命令行的MetaMask”一样
* [Mustekala](https://github.com/musteka-la/mustekala) - Metamask的以太坊轻客户端项目
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir客户
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - Tobalaba测试网络的Energy Web Foundation客户端
* [Quorum](https://github.com/jpmorganchase/quorum) -  [JP Morgan](https://jpmorgan.com/quorum)授权的以太坊支持数据隐私的实现 
* [Mana](https://github.com/mana-ethereum/mana) - 用Elixir写的以太坊全节点实现。
* [Chainstack](https://chainstack.com/) - 提供共享和专用Geth节点的托管服务
* [QuikNode](https://quiknode.io/) - 具有API访问和节点即服务的区块链开发云。


#### 存储
* [IPFS](https://ipfs.io/) - 分散存储和文件引用
   * [Mahuta](https://github.com/ConsenSys/Mahuta) - 具有附加搜索功能的IPFS存储服务，以前是IPFS-Store
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - IPFS之上的分散式数据库
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - 使用JavaScript实现的IPFS HTTP API客户端库
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - 易于在IPFS和其他分布式/分散式存储协议中使用的API
   * [PINATA](https://pinata.cloud) - 使用IPFS的最简单方法
* [Swarm](https://swarm-gateways.net/) - 分布式存储平台和内容分发服务，以太坊的数据存储服务层
* [Infura](https://infura.io/) -托管IPFS API网关和固定服务
* [3Box Storage](https://docs.3box.io/api/storage) - 用于用户控制的分布式存储的api。建立在IPFS和Orbitdb之上。


#### 讯息传递
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - DApp相互通信的通信协议，这是以太坊web3堆栈的基础层服务
* [DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - 运行以太坊/低语的节点之间的对等通信
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - RLPx网络层的Python实现
* [3Box Threads](https://docs.3box.io/api/messaging) - API，使开发人员能够持久地实现IPFS，或在内存中实现对等消息传递。
* [GroupFi](https://github.com/TanglePay/GroupFi-Chatbox/blob/dev/packages/sdk/README.md) - GroupFi 聊天框 SDK 使开发者能够轻松将 GroupFi 的聊天框集成到他们基于 EVM 链的 dApp 中。


### 测试工具
* [Truffle Teams](https://trufflesuite.com/teams) - 零配置持续集成松露项目
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity代码覆盖率工具
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Solidity 智能合约的代码覆盖率
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity 合约功能分析器
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - 替代和更新的Solidity智能合约分析器
* [Espresso](https://github.com/hillstreetlabs/espresso) - 快速，并行，热加载的Solidity测试框架
* [Eth tester](https://github.com/ethereum/eth-tester) - 用于测试以太坊应用程序的工具套件
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - 使用与真实区块链网络非常相似的Docker实例简化智能合约应用程序的集成和接受测试
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - hevm项目是以太坊虚拟机（EVM）的实现，专门用于单元测试和调试智能合约
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity 图形化调试器
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - 通过可读的堆栈跟踪加快开发速度
* [Solhint](https://github.com/protofire/solhint) - 为Solidity智能合约验证提供安全性，样式指南和最佳实践规则
* [Ethlint](https://github.com/duaraghav8/Ethlint) - 用于识别和修复Solidity（以前为Solium）中的样式和安全问题
* [Decode](https://github.com/hacker-DOM/decode) - npm软件包，它将tx提交到本地testrpc节点的解析，使它们更具可读性和易懂性
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - 一个npm软件包，其中包含其他断言和实用程序，用于测试带有松露的Solidity智能合约。最重要的是，它增加了断言是否已发出特定事件的能力。
* [Psol](https://github.com/Lamarkaz/psol) - 具有mustache.js样式的语法，宏，条件编译和自动远程依赖关系包含的Solidity词法预处理器。
* [solpp](https://github.com/merklejerk/solpp) -具有全面指令和表达式语言，高精度数学和许多有用的辅助函数的Solidity预处理器和帮助插件。
* [Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) – 解码和发布原始的以太坊TX。类似于https://live.blockcypher.com/btc-testnet/decodetx/
* [Doppelgänger](https://getdoppelganger.io/) - 一个用于在单元测试期间模拟智能合约依赖关系的库。
* [rocketh](https://github.com/wighawag/rocketh) - 一个简单的库来测试以太坊智能合约，允许使用任何web3库和测试运行器。
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - PyTest插件，用于测试以太坊区块链的智能合约。

### 安全工具
* [MythX](https://mythx.io/) - 以太坊开发人员的安全验证平台和工具生态系统
* [Mythril](https://github.com/ConsenSys/mythril) - 开源EVM字节码安全性分析工具
* [Oyente](https://github.com/melonproject/oyente) - 替代静态智能合约安全性分析
* [Securify](https://securify.chainsecurity.com/) - 安全扫描器以太坊智能合约
* [SmartCheck](https://tool.smartdec.net/) - 静态智能合约安全分析器
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM反汇编程序
* [Evmdis](https://github.com/Arachnid/evmdis) - 替代EVM反汇编程序
* [Hydra](https://github.com/IC3Hydra/Hydra) - 框架cryptoeconomic合同的安全性，分散的治安悬赏
* [Solgraph](https://github.com/raineorshine/solgraph) - 可视化Solidity控制流程以进行智能合约安全性分析
* [Manticore](https://github.com/trailofbits/manticore) - 智能合约和二进制文件上的符号执行工具
* [Slither](https://github.com/crytic/slither) - 一个Solidity静态分析框架
* [Adelaide](https://github.com/sec-bit/adelaide) - SECBIT静态分析扩展到Solidity编译器
* [solc-verify](https://github.com/SRI-CSL/solidity/) - 用于Solidity智能合约的模块化验证器
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - 已知攻击媒介和常见反模式的完整列表
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) -受影响的代币中ERC20智能合约中的漏洞的集合
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Callisto Network提供的免费的智能合约安全审核
* [Piet](https://piet.slock.it) - 可视化Solidity体系结构分析器
* [Kontrol](https://github.com/runtimeverification/kontrol) - 通过 Foundry 属性测试对 Solidity 智能合约进行形式验证 

### 监控方式
* [Alethio](https://aleth.io/) - 一个先进的以太坊分析平台，提供实时监控，洞察和异常检测，令牌指标，智能合约审计，图形可视化和区块链搜索。还可以探索以太坊去中心化交易所的实时市场信息和交易活动。
* [amberdata.io](https://amberdata.io) - 提供实时监控，洞察力和异常检测，令牌指标，智能合约审计，图形可视化和区块链搜索。
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - 一种监视大量智能合约和交易的工具
* [Scout](https://scout.cool/) - 以太坊上智能合约的活动和事件日志的实时数据馈送
* [Tenderly](https://tenderly.co/) - 一种平台，可通过Web仪表板的形式为用户提供可靠的智能合约监控和警报，而无需用户托管或维护基础架构
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - 使用已解码的交易数据探索智能合约，查看合约的使用方式以及通过特定功能调用搜索交易
* [BlockScout](https://github.com/poanetwork/blockscout) - 一种用于检查和分析基于EVM的区块链的工具。唯一以太坊网络的功能齐全的区块链浏览器。
* [Terminal](https://terminal.co/) - 用于监视dapp的控制面板。终端可用于监视用户，dapp，区块链基础设施，交易等。 infrastructure, transactions and more.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - 用Golang编写的可扩展框架，用于侦听链上事件并做一些响应。

### 其他杂项工具
* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - 由aragonOS和Ethereum支持的去中心化软件包管理器。aragonPM支持对软件包升级进行分散式管理，从而消除集中式故障点。
* [Truffle boxes](https://www.trufflesuite.com/boxes) - 用于快速构建DApp的打包组件
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties API和智能合约的本地沙盒实现，可以作为松露盒使用
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html) - Solidity 编译器
* [Sol-compiler](https://sol-compiler.com/) -项目级Solidity编译器
* [Solidity cli](https://github.com/pubkey/solidity-cli) - 更快，更轻松，更可靠地编译Solidity代码
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Solidity项目组合到平面文件实用程序。对于可视化导入的合同或在Etherscan上验证合同很有用
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - 替代方案，将所有导入合并到单个文件中以签订固定合同
* [RLP](https://github.com/ethereumjs/rlp) - JavaScript中的递归长度前缀编码
* [eth-cli](https://github.com/protofire/eth-cli) - 一系列CLI工具的帮助以太坊学习和开发
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal是用于管理以太坊中常见任务的命令行工具
* [Eth crypto](https://github.com/pubkey/eth-crypto) - 以太坊的加密javascript函数以及将其与web3js和solidity结合使用的教程
* [Parity Signer](https://github.com/paritytech/parity-signer) - 移动应用程序允许签署交易
* [py-eth](http://py-eth.com) - 以太坊生态系统的Python工具集合
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - 合并在Truffle框架下开发的Solidity的所有依赖项
* [Decode](https://github.com/hacker-DOM/decode) - npm软件包，它将tx提交到本地testrpc节点的解析，使它们更具可读性和易懂性
* [TypeChain](https://github.com/ethereum-ts/TypeChain) -  以太坊智能合约的Typescript绑定
* [EthSum](https://ethsum.netlify.com) - 一个简单的以太坊地址校验和工具
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - 允许索引块或侦听PHP中的事件
* [Purser](https://github.com/JoinColony/purser) - JavaScript的基于以太坊的钱包通用钱包工具。支持软件，硬件和Metamask-使所有钱包进入dApp开发的一致且可预测的界面。
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - 从node.js连接到MetaMask
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Solidity项目的文档生成器
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - 将以太坊区块链数据导出到CSV或JSON文件
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - solidity-用于格式化Solidity代码的漂亮插件
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - 以太坊和Unity集成演示
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - 以太坊和Unity集成演示/样本
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum业务规则引擎演示/样本
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - 一组用于标准化框架中Solidity导入和工件解析的工具。
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - 检查事务的节点和浏览器工具-使用在线找到的ABI尽可能解码方法，事件日志和任何还原原因。
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) -一个用Golang编写的有用的库，用于可靠地发送交易-提取一些棘手的底层细节，例如气体优化，随机数计算，同步和重试。
* [truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - 从Truffle命令行在Etherscan上无缝验证合同源代码。

### 智能合约标准和类库
####  [ERCs](https://eips.ethereum.org/erc) - 以太坊评论提案库
* 代币
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - 同质化资产的原始代币合同
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - 非同质化资产的代币标准
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - 替代资产的改进令牌标准
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - 可采矿代币标准
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - 创建一种标准方法来发布和检测智能合约实现的接口。
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - 密钥管理和执行的代理合同，用于建立区块链身份。
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - 合同所有权的标准接口

#### 流行的智能合约库
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - 包含经过测试的可重用智能合约，例如SafeMath和[OpenZeppelin SDK](https://github.com/OpenZeppelin/openzeppelin-sdk) 库，以实现智能合约的可升级性 
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - 一组Solidity库，用于在以太坊上构建安全且节约Gas的智能合约。
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) -一组使用以太坊虚拟机在区块链上使用的软件包
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - 节省Gas的Solidity日期和时间库
* [Aragon](https://github.com/aragon/aragon) - DAO协议。包含 [aragonOS smart contract framework](https://github.com/aragon/aragonOS) 智能合约框架，重点关注可升级性和治理 
* [ARC](https://github.com/daostack/arc) - DAO和DAO堆栈基础层的操作系统。
* [0x](https://github.com/0xProject) - DEX协议
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - 包含令牌合同的正确性证明。给定的规格和高级属性
* [Provable API](https://github.com/provable-things/ethereum-api) - 提供使用Provable服务的合同，允许进行链下操作，数据获取和计算
* [ABDK Libraries for Solidity](https://github.com/abdk-consulting/abdk-libraries-solidity) - 用于Solidity的定点（64.64位）和IEEE-754兼容四精度（128位）浮点数学库


### 第二层基础架构开发人员指南

#### 可扩展性



#### 付款渠道
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - 50行代码实现的的以太坊支付通道
* [µRaiden Documentation](https://microraiden.readthedocs.io) - µRaiden发送者/接收者用例的指南和示例

#### Plasma
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - 网站作为节点应用程序，始于康奈尔大学的2018 IC3-以太坊加密新手训练营，涵盖所有Plasma用例（MVP /现金/借记）  
* [Plasma MVP](https://github.com/omisego/plasma-contracts) - OmiseGO的最小可行Plasma研究实施
* [Plasma MVP Golang](https://github.com/kyokan/plasma) -Golang实施和最小可行Plasma规范的扩展
* [Plasma Guard](https://github.com/mesg-foundation/plasma-guard) - 在需要时自动观察和挑战或退出Omisego Plasma网络。
* [Plasma OmiseGo Watcher](https://github.com/mesg-foundation/service-plasma-omisego-watcher) - 与Plasma OmiseGo网络互动并通知任何拜占庭事件。

#### 侧链
* [POA Network](https://www.poa.network/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)
* [Matic Network](https://docs.matic.network/)

#### 隐私/保密

##### zkSNARKs
* [ZoKrates](https://github.com/Zokrates/ZoKrates) - 以太坊上的zkSNARKS的工具箱
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - 以太坊网络上的机密交易，在以太坊主网上实时实施
* [Nightfall](https://github.com/EYBlockchain/nightfall) - 将任何ERC-20 / ERC-721令牌设为私人-开源工具和微服务
* Proxy Re-encryption (PRE)
** [NuCypher Network](https://github.com/nucypher/nucypher) - 代理重新加密网络，可在分散系统中实现数据保密
** [pyUmbral](https://github.com/nucypher/pyumbral) -门限代理重新加密密码库
** [NuFHE](https://github.com/nucypher/nufhe) - NuFHE -GPU加速的FHE库

#### 可扩展性+隐私

#### ZK-STARKs
* [StarkWare](https://github.com/starkware-industries) 和 [StarkWare Resources](https://github.com/starkware-libs) - StarkEx可扩展性引擎在链上存储状态转换

#### 预建的UI组件
* [aragonUI](https://ui.aragon.org) - 一个包含Dapp组件的React库
* [components.bounties.network](https://components.bounties.network) - 一个包含Dapp组件的React库
* [ui.decentraland.org](https://github.com/decentraland/ui) - 一个包含Dapp组件的React库
* [dapparatus](https://github.com/austintgriffith/dapparatus) - 可重用的React Dapp组件
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React组件
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - 用于基于Web的分散式应用程序的跨平台混合托管机制
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - 跨平台桌面钱包示例
* [eth-button](https://eth-button.github.io/eth-button/) - 极简主义捐赠按钮
* [Rimble Design System](https://rimble.consensys.design/) - 适用于分散应用的组件和设计标准。
* [3Box Plugins](https://docs.3box.io/build/plugins) - 用于社交功能的react组件。包括评论，个人资料和消息。
