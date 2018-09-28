※この日本語訳は[c5bd220](https://github.com/ConsenSys/ethereum-developer-tools-list/commit/d4ed743361802cb69a8367752960818c43da2a5c)時点のものです。

# Ecosystem Resources
Ethereumエコシステムを学習・理解するためのDApps、サービス、テキスト、ナレッジベースのガイドです。  
このリソースはエコシステムの開発にフォーカスしていますが、このリポジトリには以下も含まれます:
* [Ethereum Developer Tools List](README_Japanese.md)

## Contributions 大歓迎!

あなたが追加(または削除!)したいツールについて、小さな修正であっても気軽にプルリクエストを送ってください。ツールを追加する場合は、開発者の理解を助ける**短い説明文を付加してください**。

発起人の[@corbpage](https://twitter.com/corbpage)、キュレーションと拡大へ貢献してくれた[@pakaplace](https://twitter.com/Parker_Place)、よりロジカルにリストを再構築してくれた@jpantunesを含む20人以上のコントリビュータに感謝します。

## リソース
### ウォレット
* [Metamask](https://metamask.io/) - ERCトークンをサポートするChrome拡張ウォレット。
* [Gnosis multisig wallet](https://github.com/gnosis/MultiSigWallet) - Audit済のマルチ・シグ・ウォレット
* [Mist](https://github.com/ethereum/mist) - Ethereumネットワーク上でのDAppsの検索と利用 
* [Exodus](https://www.exodus.io) - Shapeshift統合されたデスクトップウォレット 
* [Nifty Wallet](https://github.com/poanetwork/metamask-extension) - 現実世界のアプリケーションにフォーカスしたEthereumのブラウザ拡張 

#### Web ウォレット
* [MyEtherWallet](https://github.com/MyEtherWallet) - ブロックチェーンに接続できる安全かつ堅牢な[オープンソースツール](https://www.myetherwallet.com/)
* [Ether Address Lookup](https://chrome.google.com/webstore/detail/etheraddresslookup/pdknmigbbbhmllnmgdfalmedcmcefdfn?hl=en-GB) - フィッシング詐欺帽子とETHアドレスのハイライト機能を持つChrome拡張 
* [MyCrypto](https://github.com/MyCryptoHQ) - 安全かつ堅牢にブロックチェーンに接続でき、ETHウォレット作成やERCトークン管理の機能を持つ[オープンソース・クライアントサイド・ツール](https://mycrypto.com/account)
* [Portis](https://portis.io/) - ユーザにDAppの利用を習熟してもらうためのWebベースのウォレット 
* [Eth lightwallet](https://github.com/ConsenSys/eth-lightwallet) - Node.jsとブラウザのための軽量JSウォレット 
* [SpankCard](https://github.com/SpankChain/SpankCard) - ペイメントチャネルをサポートしたEthereum Webウォレット 
* [Mnemonic generator](https://iancoleman.io/bip39/) - 公開鍵・秘密鍵に関連付けたニーモニック・ワードを作成。Ethereumアドレスを生成するためには"Ethereum"を対象コインとして選択する。truffle-hd-walletで利用すると便利。

#### モバイルウォレット
* [Toshi](https://github.com/toshiapp) - モバイルDAppエクスプローラと[ウォレット](https://itunes.apple.com/us/app/toshi-ethereum-wallet/id1278383455?mt=8) 
* [Cypher](https://www.cipherbrowser.com/) - モバイルDAppエクスプローラ
* [Trust](https://github.com/TrustWallet/trust-wallet-ios) - ERCトークンのための[モバイルウォレット](https://trustwalletapp.com/)
* [Status](https://github.com/status-im/status-react) - Ethereum用のフリーでオープンソースなモバイルOS 
* [imToken](https://token.im/) - DAppsを検索でき、堅牢でプライベートな資産の交換と複数のブロックチェーンの資産管理が可能な、機能豊富なモバイルウォレット
* [Jaxx](https://jaxx.io) - モバイルとデスクトップで利用可能なウォレット。Shapeshiftに対応 
* [WallETH](https://walleth.org) - ネイティブ実装のAndroid Ethereumウォレット
+ [eth-wallet-light](https://github.com/NoahHydro/eth-wallet-light) - モバイルに最適化された軽量JSウォレット  


#### ハードウェアウォレット
* [Trezor](https://trezor.io) - 元祖ハードウェアウォレット
* [Ledger](https://www.ledgerwallet.com) - 複数の暗号通貨やトークンをサポート 
* [KeepKey](https://www.keepkey.com) - シンプルなハードウェアウォレット

### ブロック・エクスプローラ
* [Etherscan](https://etherscan.io/) - もっとも有名なEthereumのトランザクションとコントラクトのコードが確認可能な手段(中央集権) 
* [Etherchain Light](https://github.com/gobitfly/etherchain-light) - Ethereumのプライベートチェーン用の軽量ブロックチェーン・エクスプローラ 
* [POA Explorer](https://github.com/poanetwork/poa-explorer) - [POA](https://poa.net)により開発され、[Ethprize](http://ethprize.io)に資金を提供されたオープンソースのEthereumブロック・エクスプローラ
* [QuickBlocks](https://github.com/Great-Hill-Corporation/quickBlocks) - Ethereumブロックチェーンからデータを引き出すためのライブラリ、アプリケーション、ツール、サンプル集のコレクション 

### gas計算&ツール
* [EthGasStation](https://ethgasstation.info/) - トランザクションの価格と時間を見積もるWebサイト  
* [Petrometer](https://github.com/makerdao/petrometer) - 特定のEthereumアドレスから送信された全てのトランザクションの日時のgas総消費量 
* [CryptoProf](https://github.com/doc-ai/cryptoprof) - スマートコントラクトのgasプロファイラ 

### サービス
* [Oracalize](http://www.oraclize.it/) - スマートコントラクトのためのOracleサービス 
* [Infura](https://infura.io/) - EthereumのAPIゲートウェイ。自分のEthereumホストを立ち上げなくて済む
* [Quiknode](https://quiknode.io/) - Parity/Gethのノードをスピンアップするサービス
* [Regis](https://regis.nu/) - デジタル資産の登録サービス 
* [Viant](https://viant.io/) - ビジネスプロセスの用途ならViantをバックエンドに利用することを検討してください 
* [uPort](https://www.uport.me/) - 総合IDソリューション 
* [Ether Address Lookup](https://chrome.google.com/webstore/detail/etheraddresslookup/pdknmigbbbhmllnmgdfalmedcmcefdfn?hl=en-GB) - フィッシング詐欺帽子とETHアドレスのハイライト機能を持つChrome拡張 
* [Netstats](https://github.com/cubedro/eth-netstats) - Ethereumネットワークの[ステータス](https://ethstats.net/)
* [ENS](https://github.com/ensdomains) - ENSはシンプルで人間が読める[名前](https://ens.domains/)を使って、ブロックチェーン内外のリソースに対応させるセキュアで非中央集権な方法を提供
* [Name Bazaar](https://namebazaar.io/) - ENSで登録されたドメイン名のマーケットプレイス 
* [Quantstamp](https://quantstamp.com) - フィーを伴う自動または手動の、スマートコントラクトのSecurity Auditsを提供するサービス
* [SmartCheck](https://tool.smartdec.net/) - Solidityコードの脆弱性とベストプラクティスの分析のための静的解析サービス 
* [MD4 Online Hash Function](https://emn178.github.io/online-tools/md4.html) - 様々なハッシュ化アルゴリズムをサポートする、入力データをハッシュ化するツール
* [iExec SDK](https://github.com/iExecBlockchainComputing/iexec-sdk) - オフチェーンのアプリケーションをスマートコントラクトから実行。いかなる既存アプリケーションでもサポートし、Dockerイメージとして提供される 
* [dAppBridge](https://dAppBridge.com/) - スマートコントラクト用のインテリジェントなOracleと`setTimeout`サービス 
* [Solidstamp](https://www.solidstamp.com) - スマートコントラクトAudits用のオンチェーン・レジストリ 
* [Incentivai](http://incentivai.co) - スマートコントラクト・エコノミーを機械学習エージェントでのシミュレーションを用いてテスト 

### ナレッジ・学習
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - ERC20トークン・スマートコントラクトの脆弱性コレクション
* [Solidity idiosyncrasies](https://github.com/miguelmota/solidity-idiosyncrasies) - Solidityの罠、落とし穴、制限、そして特異性 
* [Ethereum development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - EthereumをGoで開発するための短い[本](https://goethereumbook.org) 
* [Consensys Academy](https://consensys.net/academy/resources/) - コース
* [B9Lab](https://academy.b9lab.com/) - 有料コース
* [Blockgeeks](https://courses.blockgeeks.com/) - Solidity/DApp開発のための有料コース 
* [Chainshot building blocks](https://www.chainshot.com/) - 無料のプロジェクトベースのコースと問題集 
* [Kauri](https://beta.kauri.io/) - 公開されたコミュニティのナレッジベースとチュートリアル 
* [Delegate call](https://delegatecall.com/) - Q&Aサイト
* [Stackexchange](https://ethereum.stackexchange.com) - Q&Aサイト
* [r/EthDev](https://www.reddit.com/r/ethdev/) - サブreddit
* [Ethernaut](https://github.com/OpenZeppelin/ethernaut) - Web3/Solidityベースの戦争ゲーム
* [Reducing Gas Fees](https://medium.com/@STKtoken/research-of-the-week-reducing-gas-fees-9061d19cc171) - Tips and tricks to reducing gas spent on execution
* [Dapp University](http://www.dappuniversity.com) - Free Video Tutorials
* [Attacks on Smart Contracts](https://www.cryptologie.net/article/423/attacks-on-ethereum-smart-contracts/)
* [Zastrin](https://www.zastrin.com) - Paid courses on Solidity/Dapp Development


#### Security best practices
* [Smart contract best practices](https://github.com/ConsenSys/smart-contract-best-practices) - by ConsenSys
* [Safety wiki](https://github.com/ethereum/wiki/wiki/Safety) - Ethereum Foundation wiki on safety

#### Solidity Games!
* [OpenZeppelin Ethernaut](https://ethernaut.zeppelin.solutions)
* [Cryptozombies](https://cryptozombies.io/) - The best undead tutorial in the world
* [Capture the Ether](https://capturetheether.com/)

#### Scaling
* [Comprehensive Medium article](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4) on various solutions to scale Ethereum
* [Using Multitoken Payment Channels to sign off-chain transactions](https://github.com/STKtoken/Multi-Token-smart-contracts)

### Reference
* [Wiki](https://github.com/ethereum/wiki/wiki) - Ethereum wiki covering all things related to Ethereum
* [Yellow Paper](https://github.com/ethereum/yellowpaper) - Ethereum's formal specification
* [Beige Paper](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf) - Rewrite of the yellow paper in non-yellow-paper syntax
* [EthOn](https://github.com/ConsenSys/EthOn) - An ontology is a formalisation of concepts and relations within a domain. EthOn is written in RDF and OWL
* [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - by Andreas M. Antonopoulos, Gavin Wood, and many others
* [EVM opcodes](https://github.com/trailofbits/evm-opcodes) - Ethereum opcodes and instruction reference
* [EVM illustrated](http://takenobu-hs.github.io/downloads/ethereum_evm_illustrated.pdf) - This is an illustrated document about the Ethereum Virtual Machine
* [4bytes](https://github.com/ethereum-lists/4bytes) - List of 4byte identifiers to common smart contract functions [function signatures](https://www.4byte.directory/)
* [Solidity cheat sheet](https://topmonks.github.io/solidity_quick_ref/) - Quick overview of Solidity syntax

### Governance
* [Ethresear.ch](https://ethresear.ch/) - Semi-public forum for participating in Ethereum’s research efforts, including but not limited to: Casper, Sharding, EVM improvements, Crytpeconomics, Plasma and State-channels
* [Fellowship of Ethereum Magicians](https://ethereum-magicians.org/) - This discussion board facilitates meaningful communications among individuals throughout the Ethereum community
* [EIPs](http://eips.ethereum.org/) - The Ethereum Improvement Proposal repository
* [Aragon Research Forum](https://research.aragon.org/) - Long-form discussions related to Aragon's research efforts including governance, economics, and token engineering

### Block explorers
* [Etherscan](https://etherscan.io/) - most popular centralized way to view Eth transactions and contract code
* [POA Explorer](https://github.com/poanetwork/poa-explorer) - Open Source Ethereum Block explorer, funded by [Ethprize](http://ethprize.io) and developed by [POA](https://poa.net)
* [QuickBlocks](https://github.com/Great-Hill-Corporation/quickBlocks)- QuickBlocks is a collection of software libraries, applications, tools, and examples that allow you to retrieve Ethereum blockchain data (a) more quickly, (b) with higher information content, (c) in an fully decentralized way, (d) in a fully automated way, and (e) in a highly maintenance free way.)
* [Etherchain lite](https://github.com/gobitfly/etherchain-light)- Lightweight blockchain explorer for your private Ethereum chain
* [Alethio EthStats 2.0](https://media.consensys.net/alethio-lighting-up-the-blockchain-with-real-time-stats-a80bb30576db) coming soon
* [Supermax](https://www.supermax.cool/)- A live data feed of the activities and event logs of your smart contracts on Ethereum

### Decentralized Exchanges
* [Airswap](https://www.airswap.io/) - decentralized token exchange
* 0x protocol based decentralized exchanges
* [Radar relay](https://app.radarrelay.com/)
* [ERC Dex](https://ercdex.com/)
* [DDEX](https://ddex.io)
* [Ethfinex](https://www.ethfinex.com)
* [Shark Relay](https://app.sharkrelay.com)
* [LedgerDex](https://www.ledgerdex.com)
* [Bamboo Relay](https://www.bamboorelay.com)
* [Instex](https://app.instex.io)
* [Starbit](https://www.starbitex.com)
* [Opensea.io](http://Opensea.io)-  decentralized exchange of cryptocollectibles
* [Bancor](https://www.bancor.network/)
* [Kyber](https://www.kyber.network)
* [Gnosis Dutch Exchange](https://github.com/gnosis/dx-contracts)


 ### Incentivisation / Monetisation Tools
* [Gitcoin](https://gitcoin.co) - Bounty network for funding Open Source or finding Open Source work
* [CodeFund](https://codefund.io) - Ethical Advertising Platform for Open Source


### Awesome lists
* [Awesome Cryptoeconomics](https://github.com/jpantunes/awesome-cryptoeconomics) - A curated list of cryptoeconomic research and learning materials
* [Awesome Solidity](https://github.com/bkrem/awesome-solidity) - A curated list of awesome Solidity resources, libraries, tools and more
* [Awesome EVM](https://github.com/pirapira/awesome-ethereum-virtual-machine) - Ethereum Virtual Machine Awesome List
* [Awesome State-Channels](https://github.com/machinomy/awesome-state-channels) - Curated list of resources regarding state channels on Ethereum.
* [DEX protocols](https://github.com/evbots/dex-protocols) - A list of protocols for decentralised exchange
* [Ethereum Token Standards](https://github.com/PhABC/ethereum-token-standards-list) - An exhaustive list of Ethereum Token Standards
