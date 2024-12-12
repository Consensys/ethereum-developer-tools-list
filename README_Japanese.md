※この日本語訳は[d4ed743](https://github.com/ConsenSys/ethereum-developer-tools-list/commit/d4ed743361802cb69a8367752960818c43da2a5c)時点のものです。

# Ethereum Developer Tools List
Ethereum開発で利用可能なツール、コンポーネント、パターン、プラットフォームのガイドです。

このリストは経験のあるブロックチェーン開発者から未経験の開発者まで、ツールや開発パターン、コンポーネントをもっと共有するべきだと感じたConsenSysのプロダクトマネージャにより作成が開始されました。

このリソースは開発用ツールにフォーカスしていますが、

* [Ethereum Ecosystem Resources](EcosystemResources_Japanese.md) は有用なDApps、学習リソース、ウォレット、サービスをまとめています。

## Contributions 大歓迎!

あなたが追加(または削除!)したいツールについて、小さな修正であっても気軽にプルリクエストを送ってください。ツールを追加する場合は、開発者の理解を助ける**短い説明文を付加してください**。

発起人の[@corbpage](https://twitter.com/corbpage)、キュレーションと拡大へ貢献してくれた[@pakaplace](https://twitter.com/Parker_Place)、よりロジカルにリストを再構築してくれた@jpantunesを含む20人以上のコントリビュータに感謝します。

* 実稼働するプロダクトが無いプロジェクトは追加しない
* 重複している、あるいはもうメンテナンスされていないツールは除却する
* 有償、または限定サービスで、かつオープンソースでもなく開発者レビューの無いプロジェクトはさらなる審査を要します

このルールはフェアでしょうか？ あなたの意見を聞かせてください: https://github.com/ConsenSysLabs/ethereum-developer-tools-list/pull/70

## 新規の開発者はこちらから
* [Solidity](http://solidity.readthedocs.io/en/latest/) - もっともポピュラーなスマートコントラクト用言語
* [Truffle](http://truffleframework.com) - もっともポピュラーなスマートコントラクトの開発、テスト、デプロイ用フレームワーク。npmでインストールしこのツールで最初のスマートコントラクトを書いてみてください。
* [Metamask](https://metamask.io/) - DAppsと連携するChrome拡張ウォレット。
* [Truffle boxes](http://truffleframework.com/boxes/) - Ethereumエコシステムのためのパッケージされたコンポーネント。
* [dfuse](https://dfuse.io) - 世界クラスのアプリケーションを構築するための滑らかなブロックチェーンAPI。

## 開発ツール
### スマートコントラクト開発
#### スマートコントラクト用言語
* [Solidity](http://solidity.readthedocs.io/en/latest/)- Ethereumのスマートコントラクト用言語。
* [Bamboo](https://github.com/pirapira/bamboo) - モーフィング・スマートコントラクト用言語
* [Vyper](https://github.com/ethereum/vyper) - 新しい実験的プログラミング言語
* [LLL](https://media.consensys.net/an-introduction-to-lll-for-ethereum-smart-contract-development-e26e38ea6c23) - Lispライクな低レベル言語

#### フレームワーク
* [Truffle](http://truffleframework.com) - もっともポピュラーなスマートコントラクトの開発、テスト、デプロイ用フレームワーク。TruffleスイートはTruffle、[Ganache](https://github.com/trufflesuite/ganache)、[Drizzle](https://github.com/truffle-box/drizzle-box)を含みます。参考: [Deep dive on Truffle here](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Embark](https://github.com/embark-framework/embark) - DApps開発フレームワーク
* [Dapp](https://dapp.tools/dapp/) - DApps開発フレームワーク。DAppleの後継。
* [Populus](https://github.com/ethereum/populus) - もっともかわいい動物写真を含むEthereum開発フレームワーク。 
* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.jsベースのDApps開発フレームワーク。
* [EVMTools](https://evmtools.xyz) - Web3およびSolidity開発者のためのEVMツールキット。すべての開発ツールを一箇所にまとめました。20以上のユーティリティがあり、さらに頻繁に追加されています。

#### IDEs
* [Remix](https://remix.ethereum.org/) - 静的解析とブロックチェーンVMによるテスト機能を含むWeb IDE。
* [Atom](https://atom.io/) - Atomエディタ + [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom)
* [Pragma](https://www.withpragma.com/) - スマートコントラクトのインターフェイス自動生成機能を含む非常にシンプルなSolidity Web IDE。
* [Superblocks Studio](https://superblocks.com/studio/) - Superblocks Studioはスマートコントラクトのコーディング、ビルド、デプロイを支援します。
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Solidity用Vimシンタックスファイル。
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio CodeのSolidity用エクステンション。 
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - シンタックスハイライト、フォーマット、コード補完等の機能を含むオープンソースの[JetBrains IntelliJ Idea IDE](https://www.jetbrains.com/idea/) (フリー/商用)プラグイン。
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - EclipseベースのIDE。コンテクストに応じたコード補完とヘルプ、コードナビゲーション、シンタックスハイライト、ビルド、クイックフィックス＆テンプレート。
* [Eth Fiddle](https://ethfiddle.com/) - [The Loom Network](https://loomx.io/)製のIDE。スマートコントラクトの作成、コンパイル、デバッグが可能。シェアが容易。

### テスト用ブロックチェーンネットワーク
* [Ganache](https://github.com/trufflesuite/ganache) - GUIとログ基盤を持つEthereumブロックチェーンのテストアプリケーション。
* [Kaleido](https://kaleido.io/) -  コンソーシアムブロックチェーンを効率よく利用するためのツール。PoCや検証に最適。
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - 本物のブロックチェーンに近いDockerベースのシンプルなスマートコントラクト・アプリケーションのテスト環境。  
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - デモやテストのためにDockerコンテナ上でRaidenを可動させる環境。 
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - プライベートPoAチェーン構築のためのクリエイティブなスクリプト。  
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - プライベートPoWチェーン構築のためのクリエイティブなスクリプト。  
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain-workbench/ethereum-poa-deployment) - コンソーシアムEthereumネットワークの構築とガバナンス。
* [getho](https://getho.io) - PoAプライベートプロックチェーンとスマートコントラクトのテスティングツールを持つDApp開発プラットフォーム

#### テスト用のEther faucets
* [Rinkeby faucet](https://faucet.rinkeby.io/)
* [Kovan faucet](https://github.com/kovan-testnet/faucet)
* [Ropsten faucet](http://faucet.ropsten.be:3001/)
* [Goerli faucet](https://goerli-faucet.slock.it/)
* [Holesky faucet](https://stakely.io/en/faucet/ethereum-holesky-testnet-eth)
* [Universal faucet](https://faucets.blockxlabs.com/)

### Ethereumを利用するためのクライアント
#### フロントエンドEthereum API
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
    * [Eth.js](https://github.com/ethjs) - Javascript Web3 その2
    * [Ethers.js](https://github.com/ethers-io/ethers.js/)- Javascript Web3 その3、便利なユーティリティとウォレット機能も。
    * [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/web3-wrapper)- Typescript Web3
    * [Ethereumjs](https://github.com/ethereumjs/) - [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) や [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)のようなEthereumのユーティリティ集

* [Drizzle](https://github.com/truffle-box/drizzle-box) -  フロントエンドからブロックチェーンに繋ぐためのReduxライブラリ
* [dfuse](https://github.com/dfuse-io/client-js) - [dfuse Ethereum API](https://dfuse.io)を使用するTypeScriptライブラリ
* [useMetamask](https://github.com/mdtanrikulu/use-metamask) - イーサリアム自律分散型アプリケーション（EthereumĐApp）プロジェクトでメタマスク（Metamask）を管理するカスタムReact Hook。
* [WalletConnect](https://walletconnect.org/) - ウォレットを分散型アプリケーション（DApp）に接続するためのオープンプロトコル。
* [Subproviders](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/subproviders) - [Web3-provider-engine](https://github.com/MetaMask/provider-engine/) と接続するためのいくつかの便利なsubproviders(ハードウェアウォレットLedgerサポートをdAppに追加するためのLedgerSubproviderを含む)
* [web3-webpacked](https://github.com/NoahHydro/web3-webpacked) - Web3を利用するためのJSフレームワーク。
* [Vortex](https://github.com/Horyus/vortex) - DApp対応したReduxストア。WebSocketでスマートでダイナミックなバックグラウンドデータの更新が可能。 [Truffle](https://github.com/Horyus/vortex-demo)と[Embark](https://github.com/Horyus/vortex-demo-embark)で利用可能。
* 静的型付けALT JS言語
    * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
    * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)

#### バックエンドEthereum API
* [Web3.py](https://github.com/ethereum/web3.py)- Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [ethers-kt](https://github.com/Kr1ptal/ethers-kt) - EVMベースのブロックチェーンと対話するための非同期、高性能Kotlinライブラリ。JVMおよびAndroidプラットフォームを対象としています。
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Web3.hs](http://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/walleth/kethereum) - Kotlin Web3
* [web3dart](https://github.com/xclud/web3dart) - Dart Web3
* [Pyethereum](https://github.com/ethereum/pyethereum) - The Python core library of the Ethereum project
* [Eventeum](https://github.com/ConsenSys/eventeum) - Kauri作成のEthereumのスマートコントラクト・イベントと バックエンドのマイクロサービスを繋ぐブリッジ。JAVA製。
* [Ethereumex](https://github.com/exthereum/ethereumex) - Elixir製のEthereumブロックチェーン用JSON-RPCクライアント 
* [EthContract](https://github.com/AgileAlpha/eth_contract) - ElixirからEthereumのスマートコントラクトへクエリを投げるためのヘルパーメソッド。 

#### ブートストラップ
* [Truffle boxes](http://truffleframework.com/boxes/) - Ethereumエコシステムのためのパッケージされたコンポーネント。
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - デモやテストのためにDockerコンテナ上でRaidenを可動させる環境。
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - プライベートPoAチェーン構築のためのクリエイティブなスクリプト。
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - 2ノードによるParity PoAテストネットを構築するためのチュートリアル。 
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - プライベートPoWチェーン構築のためのクリエイティブなスクリプト。
* [Kaleido](https://kaleido.io/) -  コンソーシアムブロックチェーンを効率よく利用するためのツール。PoCや検証に最適。
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties APIとスマートコントラクトのためのローカル・サンドボックス実装。Truffle Boxで利用可能。 
* [Aragon CLI](https://hack.aragon.org/docs/cli-usage.html) - Aragonアプリケーション構築のためのCLIツール。 

#### Ethereum ABI (Application Binary Interface) ツール
* [ABI r](https://github.com/ConsenSys/abi-r) - Ethereumトランザクションのデータ、パラメータ、イベントのデコーダ・ライブラリ。 
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/abi-gen) - コントラクトのABIからTypescriptのコントラクト・ラッパーを生成。 
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - EthereumのコントラクトABIのフィールド定義と関連するバリデータからUIフォームを生成。
* [headlong](https://github.com/esaulpaugh/headlong/) - Javaの型安全コントラクトABIと再帰ライブラリ。 

#### パターン ＆ ベストプラクティス

##### スマートコントラクトのパターン
* [Dappsys: Safe, simple, and flexible Ethereum contract building blocks](https://github.com/dapphub/dappsys)
    * EthereumとSolidityの一般的な問題への解決方法。以下は例:
        * [Whitelisting](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Upgradable ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Authentication (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...several more...](https://github.com/dapphub/dappsys)
    * [MakerDAO](https://github.com/makerdao/maker-otc)や[The TAO](https://ryepdx.github.io/the-tao/)のbuilding blocksを提供
    * 独自のテストされていないソリューションを作成する前に相談すべきです  
    * 使い方は[Dapp-a-day 1-10](https://steemit.com/@nikolai)や[Dapp-a-day 11-25](https://steemit.com/@nexusdev)を参照
* [OpenZeppelin: Solidity用の再利用可能でセキュアなオープン・フレームワーク](http://zeppelin-solidity.readthedocs.io/en/latest/)
    * もっとも利用されているスマートコントラクトライブラリ 
    * Dappsysに似ていますが、よりTruffleに統合されています。 
    * [Security Auditsのベストプラクティス](https://medium.com/zeppelin-blog)
* [Assemblyを深掘りしたワークショップ](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - 特に _Benefits_ セクションは必見。
* [CryptoFin Solidity Auditing Checklist](https://github.com/cryptofinlabs/audit-checklist) - コントラクトをメインネットにローンチする際の検証に! 一般的な問題と発見のチェックリスト。
* [aragonOS: DAO,DApp,protocol作成用のスマートコントラクト・フレームワーク](https://hack.aragon.org/docs/aragonos-intro.html)
    * Upgreadability: 新しいバージョンへ更新できるスマートコントラクト。
    * Permission control: `auth` と `authP` のmodifierを利用することで、関数へのアクセスを制限。
    * Forwarders: aragonOSアプリは他のアプリを利用するためのintentを送信可能なため、一連の要件が満たされた場合にintentが転送されます

##### Upgradebility
* [colony.io開発者Elena Dimitrovaによるブログ](https://blog.colony.io/@elena_di)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Aragonテックブログ](https://blog.aragon.org/tag/development/)
    * [ライブラリ駆動開発](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
    * [Solidity開発テクニック](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelinのProxyライブラリ](https://medium.com/zeppelin-blog/proxy-libraries-in-solidity-79fbe4b970fd)

### インフラ
#### Ethereum クライアント
* [Geth](https://github.com/ethereum/go-ethereum/wiki/geth) - Goクライアント
* [Parity](https://www.parity.io/) - Rustクライアント
* [Cpp-ethereum](https://github.com/ethereum/cpp-ethereum) - C++クライアント
* [Pyethapp](https://github.com/ethereum/pyethapp) - [pyethereum](https://github.com/ethereum/pyethereum)を利用したPythonクライアント
* [Trinity](https://github.com/ethereum/trinity) - [py-evm](https://github.com/ethereum/py-evm)を利用したPythonクライアント
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)を利用したJSクライアント
* [Ethereumj](https://github.com/ethereum/ethereumj) - Ethereum FoundationによるJavaクライアント
* [Harmony](https://github.com/ether-camp/ethereum-harmony) - EtherCampによるJavaクライアント
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - "コマンドラインのためのMetaMask" のようなクライアントツール。 
* [Mustekala](https://github.com/MetaMask/mustekala) - MetamaskのEthereum Light Clientプロジェクト。
* [Exthereum](https://github.com/exthereum/blockchain) - Elixirクライアント
* [EWF Parity](https://github.com/energywebfoundation/energyweb-client) - Tobalaba test network用のEnergy Web Foundationクライアント
* [Quorum](https://github.com/jpmorganchase/quorum) - [JP Morgan](https://www.jpmorgan.com/quorum)によるデータ・プライバシーをサポートした認証されたEthereum実装。

#### ストレージ
* [IPFS](https://ipfs.io/) - 分散ストレージとファイル参照
   * [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - 検索機能を追加したIPFSストレージサービス 
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - IPFS上の分散データベース 
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-api) - IPFSのHTTP API JSライブラリ
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - IPFSとその他の分散ストレージプロトコルを容易に利用できるAPI 
* [Swarm](http://swarm-gateways.net/) - Ethereum web3スタックのネイティブ・ベース・レイヤーの分散ストレージ、ファイルディストリビューションサービス

#### メッセージング
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Ethereum web3スタックのネイティブ・ベース・レイヤーの、DApps間のコミュニケーションプロトコル
* [DEVp2p Wire Protocol](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) - Ethereum/Whisperが稼働するノード間のP2Pコミュニケーション 
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - RLPxネットワークレイヤーのPython実装
* [GroupFi](https://github.com/TanglePay/GroupFi-Chatbox/blob/dev/packages/sdk/README.md) - GroupFi Chatbox SDKにより、開発者はGroupFiのチャットボックスをEVMチェーン上のdAppsに簡単に 
統合できます。

### テストツール
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - Solidityコードカバレッジツール
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Solidityコードカバレッジツール・その2
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidityコントラクトのfunctionプロファイラ
* [Espresso](https://github.com/hillstreetlabs/espresso) - 迅速、並列処理、 ホットリロードを特徴としたSolidityテストフレームワーク
* [Eth tester](https://github.com/ethereum/eth-tester) - Ethereumアプリケーション用テストスイート
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - 本物のブロックチェーンに似せた、テスト可能なスマートコントラクトが統合されたDockerインスタンス
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - テストとデバッグのためのEVM実装 
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidityのグラフィカルデバッガ
* [Solhint](https://github.com/protofire/solhint) - セキュリティ、スタイルガイド、ベストプラクティスをチェックできるスマートコントラクト・バリデーションのためのSolidity linter
* [Solium](https://github.com/duaraghav8/Solium) - スタイルとセキュリティの問題を検出するためのSolidity linter
* [](https://github.com/dteiml/) - ローカルのtestrpcノードにsubmitされたトランザクションをよりリーダブルで理解を容易にするためのnpmパッケージ 

### セキュリティ・ツール
* [Mythril](https://github.com/ConsenSys/mythril) - スマートコントラクトの静的解析
* [Oyente](https://github.com/melonproject/oyente) - スマートコントラクトの静的解析・その2
* [Securify](https://securify.ch) - Ethereumスマートコントラクトのセキュリティ・スキャナ
* [Porosity](https://github.com/comaeio/porosity) - Ethereumスマートコントラクトのデコンパイラとセキュリティチェックツール 
* [Ethersplay](https://github.com/trailofbits/ethersplay) - EVMディスアセンブラ
* [Evmdis](https://github.com/Arachnid/evmdis) - EVMディスアセンブラ・その2
* [Hydra](https://github.com/IC3Hydra/Hydra) - Cryptoeconomicコントラクトのセキュリティと分散バウンティ・フレームワーク 
* [Solgraph](https://github.com/raineorshine/solgraph) - スマートコントラクトのセキュリティ検証のためのSolidityコントロールフローの可視化 
* [Manticore](https://github.com/trailofbits/manticore) - スマートコントラクトとバイナリのためのSymbolic executionツール  
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - 既知の攻撃手法と一般的なアンチパターンの包括的なリスト  
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - ERC20トークン・スマートコントラクトの脆弱性コレクション 
* [Kontrol](https://github.com/runtimeverification/kontrol) - Foundryのプロパティテストを通じたSolidityスマートコントラクトの形式的検証

### モニタリング
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - 多くのスマートコントラクト、トランザクションを監視するためのツール
* [Supermax](https://www.supermax.cool/) - Ethereumスマートコントラクトのアクティビティ、Event logのライブデータフィード 

### その他のツール
* [Truffle boxes](http://truffleframework.com/boxes/) - Ethereumエコシステムのためのパッケージされたコンポーネント。
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties APIとスマートコントラクトのためのローカル・サンドボックス実装。Truffle Boxで利用可能。  
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - Solidityコンパイラ
* [Sol-compiler](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-compiler) - プロジェクトレベルのSolidityコンパイラ
* [Solidity cli](https://github.com/pubkey/solidity-cli) - より信頼でき、簡単に、迅速にSolidityコードをコンパイル 
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Solidityプロジェクトを1ファイルに集約。importしたコントラクトを可視化したり、Etherscanで検証可能としたりする際に便利 
* [RLP](https://github.com/ethereumjs/rlp) - RLP(Recursive Length Prefix)のJSエンコーダ
* [eth-cli](https://github.com/protofire/eth-cli) - Ethereumの習熟・開発時に便利なCLIツールのコレクション 
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereumの一般的なタスクを管理するためのCLIツール 
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Ethereum用JS暗号関数とそれをweb3.js & Solidityで使用するためのチュートリアル 
* [Parity Signer](https://github.com/paritytech/parity-signer) - トランザクションに署名できるモバイルアプリ 
* [py-eth](http://py-eth.com) - EthereumエコシステムのためのPythonツールのコレクション 
* [truffle-flattener](https://github.com/alcuadrado/truffle-flattener) - Truffleで開発されたSolidityファイルを全ての依存関係を含め結合  
* [](https://github.com/dteiml/) - ローカルのtestrpcノードにsubmitされたトランザクションをよりリーダブルで理解を容易にするためのnpmパッケージ
* [TypeChain](https://github.com/Neufund/TypeChain) - Ethereumスマートコントラクト用のTypescriptバインディング 
* [EthSum](https://ethsum.netlify.com) - シンプルなEthereumアドレス用Checksumツール 
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - PHPでブロックをインデックスしたりEventを監視 

### スマートコントラクトの規格とライブラリ Smart Contract Standards & Libraries
#### [ERCs](https://eips.ethereum.org/erc) - Ethereum版RFCのリポジトリ
* トークン
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Fungibleな資産のためのトークンコントラクト 
  * [ERC-721](https://github.com/ethereum/eips/issues/721) - Non Fungibleな資産のためのトークン規格
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - 採掘可能なトークンの規格
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - スマートコントラクトがどのインターフェースを実装するかを公開＆検出するための標準メソッドを作成    
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - ブロックチェーンのアイデンティティを確立するためのキー管理＆実行Proxyコントラクト  
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - コントラクトの所有権のためのインターフェース規格 

#### 主要なスマートコントラクトライブラリ
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - 検証された再利用可能な[SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html)やスマートコントラクトのupgradeabilityのためのZeppelinOS [library](https://github.com/zeppelinos/zos-lib)を包含
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - セキュアでgasを抑えたEthereumスマートコントラクト開発のためのSolidityライブラリ 
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) - EVMを利用するブロックチェーンで使用するためのパッケージ集   
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - gas抑制効果のあるSolidity用のdate & timeライブラリ 
* [Aragon](https://github.com/aragon/aragon) - DAOプロトコル. ガバナンスとupgradeabilityにフォーカスした[aragonOS smart contract framework](https://github.com/aragon/aragonOS)を包含
* [0x](https://github.com/0xProject) - DEXプロトコル
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - トークンコントラクトのcorrectness proofsに関する、高品質な仕様と特性を包含 


### 2ndレイヤのインフラ開発のためのガイド

#### スケーラビリティ

#### Payment/State Channels
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - 50行で実装されたEthereumのPayment Channel 
* [µRaiden Documentation](http://microraiden.readthedocs.io) - μRaidenのSender/Receiverユースケースのガイドとサンプル 

#### Plasma
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - コーネル大学の2018 IC3-Ethereum Crypto Boot Campで始まったNode.jsによるWebアプリケーション。Plasmaの全ての種類をカバー(MVP/Cash/Debit) 
* [Plasma MVP](https://github.com/omisego/plasma-mvp) - Omise Goが実装したMinimal Viable Plasma 
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Go言語で実装されたMinimal Viable Plasmaとその拡張 
* [Plasma Cash](https://github.com/mkchungs/plasma-cash) - シンプルなPlasma Cashの実装

#### Side-Chains
* [POA Network](https://poa.net/)
  * [POA Bridge](http://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)

#### Privacy

##### zkSNARKs
* [ZoKrates](https://github.com/JacobEberhardt/ZoKrates) - EthereumのzkSNARKSのツールボックス
