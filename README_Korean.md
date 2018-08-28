
# 이더리움 개발 도구(tools) 리스트
이더리움 위에서 개발 어플리케이션을 위한 툴과 컴포넌트(components), 패턴(patterns), 플랫폼(platforms)의 사용 가이드 입니다.

신입과 경력있는 블록체인 개발자들 사이에서 툴과 개발 패턴, 컴포넌트들의 더 좋은 공유를 원하는 컨센시스(ConsenSys)의 프로덕트 매니저에 의해 이 리스트가 만들어졌습니다.

이 자료(resource)는 개발자 툴에 집중하는 것 처럼 여겨지지만, 이 저장소에는 유용한 탈중앙화 어플리케이션(DApps)과 교육적인 자료들, 지갑들, 서비스들을 위한 [이더리움 생태계 자료들(Ethereum Ecosystem Resources)](EcosystemResources.md)도 포함되어 있습니다.

## 기여자들(Contributions)을 환영합니다!

작은 수정에서 부터 추가하려는 툴까지 어느 것이든 자유롭게 풀리퀘스트(pull request)를 해주세요.
만약에 새로운 툴을 추가하면, 당신이 생각하기에 새로운 개발자들이 이해할 수 있도록 **간략한 설명을 적어주세요**

Meridio를 설립한 [@corbpage](https://twitter.com/corbpage), 확장과 큐레이팅을 한 [@pakaplace](https://twitter.com/Parker_Place), 그리고 좀 더 논리적인 방법으로 리스트를 재구축한 @jpantunes 를 포함해 20명이 넘는 기여자들에게 감사를 표합니다.

* 작동하지 않는 제품이 없는 프로젝트는 추가할 수 없습니다.
* 더 이상 사용되지 않거나 유지되지 않는 프로젝트는 제거 되게 됩니다.
* 오픈소스 코드가 아니거나 개발자 리뷰가 없는 유료/제한 서비스 프로젝트들은 추가로 조사될 것 입니다.

^위 내용이 타당하죠? 당신의 생각을 말해주세요 - https://github.com/ConsenSysLabs/ethereum-developer-tools-list/pull/70

## 신입 개발자는 여기서부터 시작
* [솔리디티(Solidity)](http://solidity.readthedocs.io/en/latest/) - 가장 유명한 스마트 컨트렉트 언어입니다.
* [트러플(Truffle)](http://truffleframework.com) - 가장 유명한 스마트 컨트렉트 개발, 테스팅, 배포(deployment) 프레임워크 입니다. npm에서 cli를 설치하고 당신의 첫번째 스마트 컨트렉트를 작성하세요.
* [메타마스크(Metamask)](https://metamask.io/) - 크롬 확장 지갑으로 탈중앙화 어플리케이션과 작동합니다.
* [트러플 박스(Truffle boxes)](http://truffleframework.com/boxes/) - 이더리움 생태계를 위한 패키지 컴포넌트 입니다.

## 개발 도구들
### 스마트 컨트렉트 개발
#### 스마트 컨트렉트 언어들
* [솔리디티(Solidity)](http://solidity.readthedocs.io/en/latest/)- 이더리움 스마트 컨트렉트 언어 입니다.
* [밤부(Bamboo)](https://github.com/pirapira/bamboo) - 모핑 스마트 컨트렉트 언어 입니다.
* [바이퍼(Vyper)](https://github.com/ethereum/vyper) - 새롭게 시도되는 프로그래밍 언어 입니다.
* [LLL](https://media.consensys.net/an-introduction-to-lll-for-ethereum-smart-contract-development-e26e38ea6c23) - Low-level Lisp-like Language, 저수준 프로그래밍 언어 입니다.

#### 프레임워크들
* [트러플(Truffle)](http://truffleframework.com) - 가장 유명한 스마트 컨트렉트 개발, 테스팅, 배포 프레임워크 입니다. 트러플 세트(suite)는 트러플과 [가나쉬(Ganache)](https://github.com/trufflesuite/ganache), 드리즐이 포함되어 있습니다. [트러플에 대한 보충설명](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [엠바크(Embark)](https://github.com/embark-framework/embark) - 탈중앙화 어플리케이션 개발을 위한 프레임워크 입니다.
* [Dapp](https://github.com/dapphub/dapptools/tree/master/src/dapp) - DApple의 뒤를 잇는 탈중앙화 어플리케이션 개발 프레임 워크 입니다.
* [팝풀러스(Populus)](https://github.com/ethereum/populus) - 가장 귀여운 동물 사진들과 함께하는 이더리움 개발 프레임워크 입니다.
* [이더라임(Etherlime)](https://github.com/LimeChain/etherlime) - ethers.js를 기반으로 한 탈중앙화 어플리케이션 개발 프레임워크 입니다.
* [클리끄베이트(Cliquebait)](https://github.com/f-o-a-m/cliquebait) - 실제 블록체인 네트워크와 유사한 도커(docker) 인스턴스를 사용해 스마트 컨트렉트 어플리케이션을 통합(integration)하고 테스팅을 합니다.

#### 통합 개발 환경들
* [리믹스(Remix)](https://remix.ethereum.org/) - 블록체인 가상머신에서 테스트와 정적 분석(static analysis)이 포함된 웹 통합 개발 환경 입니다.
* [아톰(Atom)](https://atom.io/) - [아톰 솔리디티 린터(Atom Solidity Linter)](https://atom.io/packages/atom-solidity-linter)와 [이더아톰(Etheratom)](https://atom.io/packages/etheratom)이 있는 아톰 에디터 입니다.
* [프라그마(Pragma)](https://www.withpragma.com/) - 솔리디티를 위한 아주 간단한 웹 통합 개발 환경으로, 스마트 컨트렉트를 자동 생성 인터페이스 입니다. [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity)과  [language-solidity](https://atom.io/packages/language-solidity) 패키지가 있습니다.
* [수퍼블록 스튜디오(Superblocks Studio)](https://superblocks.com/studio/) - 수퍼블록 스튜디오는 당신의 코드와 빌드, 스마트 컨트렉트 배포를 도와줍니다.
* [빔 솔리디티(Vim solidity)](https://github.com/tomlion/vim-solidity) - 솔리디티를 위한 빔 문법 파일 입니다.
* [비주얼 스튜디오 코드(Visual Studio Code)](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - 비주얼 스튜디오 코드에서 솔리디티 지원 확장 프로그램 입니다.
* [인텔리j 솔리디티 플러그인(Intellij Solidity Plugin)](https://github.com/intellij-solidity/intellij-solidity/wiki) - Open-source plug-in for [젯브레인 인텔리j 아이디어 통합개발환경(JetBrains IntelliJ Idea IDE)](https://www.jetbrains.com/idea/) (무료/상업용)으로 문법 강조, 형식, 코드 완성 등의 오픈소스 플러그인 입니다.
* [야킨두 솔리디티 도구(YAKINDU Solidity Tools)](https://github.com/Yakindu/solidity-ide) - 이클립스(Eclipse)를 기반으로 한 통합 개발 환경입니다. 문맥 완성이 민감하고 도움말, 코드 탐색, 문법 색구분, 컴파일러 빌딩, 빠른 수정, 템플릿이 특징입니다.

### 블록체인 테스트 네트워크들
* [가나쉬(Ganache)](https://github.com/trufflesuite/ganache) - 시각적인 UI와 로그들을 보여주는 테스트 이더리움 블록체인 어플리케이션 입니다.
* [칼레이도(Kaleido)](https://kaleido.io/) - 컨소시엄(consortium) 블록체인 네트워크를 돌릴때 사용하세요. 개념증명들(PoCs)과 테스팅에 좋습니다.
* [로컬 라이덴(Local Raiden)](https://github.com/ConsenSys/Local-Raiden) - 데모(demo)와 테스트 목적으로 도커 컨테이너에서 로컬 라이덴 네트워크를 실행하세요.
* [개인 네트워크 배포 스크립트(Private networks deployment scripts)](https://github.com/ConsenSys/private-networks-deployment-scripts) - 개인 권위증명(PoA) 네트워크를 위한 배포 스크립트를 실행(Out-of-the-box) 합니다.
* [로컬 이더리움 네트워크(Local Ethereum Network)](https://github.com/ConsenSys/local_ethereum_network) - 개인 작업증명(PoW) 네트워크를 위한 배포 스크립트로 실행 합니다.

#### 테스트 이더 파우셋들(faucets)
* [링크비 파우셋(Rinkeby faucet)](https://faucet.rinkeby.io/)
* [코반 파우셋(Kovan faucet)](https://github.com/kovan-testnet/faucet)
* [롭스텐 파우셋(Ropsten faucet)](http://faucet.ropsten.be:3001/)

### 이더리움과 정보 전달
#### 이더리움 프론트엔드 API들
* [Web3.js](https://github.com/ethereum/web3.js/) - 자바스크립트 웹3 입니다.
    * [Eth.js](https://github.com/ethjs) - 자바스크립트 웹3 대안입니다.
    * [Ethers.js](https://github.com/ethers-io/ethers.js/)- 자바스크립트 웹3 대안이고, 유용한 유틸리티들과 지갑 기능이 있습니다.
    * [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/web3-wrapper)- 타입스크립트 웹3 대안입니다.
    * [Ethereumjs](https://github.com/ethereumjs/) - 이더리움이 좋아하는  [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) 와 [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) 를 위한 유틸리티 함수 모음 입니다.

* [드리즐(Drizzle)](https://github.com/truffle-box/drizzle-box) -  리덕스(Redux) 라이브러리 블록체인 프론트엔드와 연결합니다.
* [Subproviders](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/subproviders) - [웹3 프로바이더 엔진(Web3-provider-engine)](https://github.com/MetaMask/provider-engine/) 과 함께 사용되는 여러가지 유용한 subproviders 입니다. (당신의 탈중앙화 어플리케이션을 지원하는 렛저(Ledger) 하드웨어 월렛을 위한 LedgerSubprovider를 포함합니다.)
* [web3-webpacked](https://github.com/NoahHydro/web3-webpacked) - JS 프레임워크를 관리하기 위한 웹3 인젝션 입니다.
* [볼텍스(Vortex)](https://github.com/Horyus/vortex) - Dapp-ready 리덕스 Store 입니다. 웹소켓(WebSockets) 덕분에 효율적(Smart)이고 민첩(Dynamic)하게 백그라운드 데이터를 새로고침 합니다. [트러플](https://github.com/Horyus/vortex-demo) 과 [엠바크](https://github.com/Horyus/vortex-demo-embark)와 작동합니다.

#### 이더리움 백엔드 API들
* [Web3.py](https://github.com/ethereum/web3.py)- 파이썬 웹3 입니다.
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP 웹3 입니다.
* [Web3j](https://github.com/web3j/web3j) - 자바 웹3 입니다.
* [Nethereum](https://nethereum.com/) - 닷넷 웹3 입니다.
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - 루비 웹3 입니다.
* [Web3.hs](http://hackage.haskell.org/package/web3) - 하스켈(Haskell) 웹3 입니다.
* [KEthereum](https://github.com/walleth/kethereum) - 코틀린(Kotlin) 웹3 입니다.
* [Pyethereum](https://github.com/ethereum/pyethereum) - 이더리움 프로젝트의 파이썬 코어 라이브러리 입니다.
* [Eventeum](https://github.com/ConsenSys/eventeum) - 이더리움 스마트 컨트렉트 이벤트와 백엔드 마이크로서비스를 연결 합니다. Kauri가 자바로 작성했습니다.

#### 부트스트랩(Bootstrap) / 실행(out of box) 도구들
* [트러플 박스(Truffle boxes)](http://truffleframework.com/boxes/) - 이더리움 생태계를 위한 패키지 컴포넌트 입니다.
* [로컬 라이덴(Local Raiden)](https://github.com/ConsenSys/Local-Raiden) - 데모(demo)와 테스트 목적으로 도커 컨테이너에서 로컬 라이덴 네트워크를 실행 합니다.
* [개인 네트워크 배포 스크립트(Private networks deployment scripts)](https://github.com/ConsenSys/private-networks-deployment-scripts) - 개인 권위증명(PoA) 네트워크를 위한 배포 스크립트를 실행(Out-of-the-box) 합니다.
* [패리티 데모-권위증명 튜토리얼(Parity Demo-PoA Tutorial)](https://wiki.parity.io/Demo-PoA-tutorial.html) - 2개의 노드로 패리티 합의 인증 라운드와 PoA 테스트 체인을 만들기 위한 단계별 튜토리얼입니다.
* [로컬 이더리움 네트워크(Local Ethereum Network)](https://github.com/ConsenSys/local_ethereum_network) - 개인 작업증명(PoW) 네트워크를 위한 배포 스크립트로 실행 합니다.
* [칼레이도(Kaleido)](https://kaleido.io/) - 컨소시엄(consortium) 블록체인 네트워크를 돌릴때 사용하세요. 개념증명들(PoCs)과 테스팅에 좋습니다.
* [쳬셔(Cheshire)](https://github.com/endless-nameless-inc/cheshire) - 크립토키티(CryptoKitties) API와 스마트 컨트렉트의 로컬 샌드박스 도구이며, 트러플 박스로 이용 가능합니다.

#### 이더리움 ABI(Application Binary Interface) 도구들
* [ABI 디코더(decoder)](https://github.com/ConsenSys/abi-decoder) - 이더리움 거래(transactions)의 데이터 매개변수 디코딩과 이벤트를 위한 라이브러리
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/abi-gen) - 컨트렉트 ABI의 타입스크립트 컨트렉트 래퍼(wrappers)를 생성합니다.
* [이더리움 ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - 이더리움 컨트렉트 ABI의 필드 정의와 관련 발리데이터(validators) UI를 자동 생성 합니다.

#### 패턴들 & 습관들(Best Practices)

##### 스마트 컨트렉트 개발을 위한 패턴들
* [Dappsys: Safe, simple, and flexible Ethereum contract building blocks](https://github.com/dapphub/dappsys)
    * has solutions for common problems in Ethereum/Solidity, eg.
        * [Whitelisting](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Upgradable ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Authentication (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...several more...](https://github.com/dapphub/dappsys)
    * provides building blocks for the [MakerDAO](https://github.com/makerdao/maker-otc) or [The TAO](https://ryepdx.github.io/the-tao/)
    * should be consulted before creating own, untested, solutions
    * usage is described in [Dapp-a-day 1-10](https://steemit.com/@nikolai) and [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [OpenZeppelin: An open framework of reusable and secure smart contracts in the Solidity language.](http://zeppelin-solidity.readthedocs.io/en/latest/)
    * Likely the most widely-used libraries and smart contracts
    * Similar to Dappsys, more integrated into Truffle framework
    * [Blog about Best Practices with Security Audits](https://medium.com/zeppelin-blog)
* [Advanced Workshop with Assembly](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especially section _Benefits_

##### Upgradebility
* [Blog von Elena Dimitrova, Dev at colony.io](https://blog.colony.io/@elena_di)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Techblog von Aragon](https://blog.aragon.one/tagged/development)
    * [Library driven development](https://blog.aragon.one/library-driven-development-in-solidity-2bebcaf88736)
* [OpenZeppelin on Proxy Libraries](https://medium.com/zeppelin-blog/proxy-libraries-in-solidity-79fbe4b970fd)

### 기반시설
#### 이더리움 클라이언트들
* [Geth](https://github.com/ethereum/go-ethereum/wiki/geth) - Go client
* [Parity](https://www.parity.io/) - Rust client
* [Cpp-ethereum](https://github.com/ethereum/cpp-ethereum) - C++ client
* [Pyethapp](https://github.com/ethereum/pyethapp) - Python client using [pyethereum](https://github.com/ethereum/pyethereum)
* [Trinity](https://github.com/ethereum/trinity) - Python client using [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Ethereumj](https://github.com/ethereum/ethereumj) - Java client by the Ethereum Foundation
* [Harmony](https://github.com/ether-camp/ethereum-harmony) - Java client by EtherCamp
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"
* [Mustekala](https://github.com/MetaMask/mustekala) - Ethereum Light Client project of Metamask.
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir client
* [EWF Parity](https://github.com/energywebfoundation/energyweb-client) - Energy Web Foundation client for the Tobalaba test network
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://www.jpmorgan.com/quorum)

#### Storage
* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
   * [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - IPFS Storage service with added search capability
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralised database on top of IPFS
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-api) - A client library for the IPFS HTTP API, implemented in JavaScript.
* [Swarm](http://swarm-gateways.net/) - Distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack

#### Messaging
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack
* [DEVp2p Wire Protocol](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer

### Testing Tools
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger
* [Solium](https://github.com/duaraghav8/Solium) - Linter to identify and fix style & security issues in Solidity
* [Decode](https://github.com/dteiml/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand

### Security Tools
* [Mythril](https://github.com/ConsenSys/mythril) - Static smart contract security analysis
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.ch) - Security scanner for Ethereum smart contracts
* [Porosity](https://github.com/comaeio/porosity) - Decompiler and Security Analysis tool for Blockchain-based Ethereum Smart-Contracts
* [Ethersplay](https://github.com/trailofbits/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected

### Monitoring
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Supermax](https://www.supermax.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum

### Other Miscellaneous Tools
* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for building DApps fast.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - Solidity compiler
* [Sol-compiler](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-compiler) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://www.py eth.com) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/alcuadrado/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/dteiml/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/Neufund/TypeChain) - Typescript bindings for Ethereum smartcontracts

### Smart Contract Standards & Libraries
#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository
* Tokens
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Original token contract for fungible assets
  * [ERC-721](https://github.com/ethereum/eips/issues/721) - Token standard for non-fungible assets
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) -  Creates a standard method to publish and detect what interfaces a smart contract implements.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) -  Proxy contract for key management and execution, to establish a Blockchain identity.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - A standard interface for ownership of contracts

#### Popular Smart Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - Contains tested reusable smart contracts like [SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html) and ZeppelinOS [library](https://github.com/zeppelinos/zos-lib) for smart contract upgradeability
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) -  A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol
* [0x](https://github.com/0xProject) - DEX protocol


### Developer Guides for 2nd Layer Infrastructure

#### Scalability

#### Payment/State Channels
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Ethereum Payment Channel in 50 lines of code
* [µRaiden Documentation](http://microraiden.readthedocs.io) - Guides and Samples for µRaiden Sender/Receiver Use Cases

#### Plasma
* [Plasma MVP](https://github.com/omisego/plasma-mvp) - OmiseGO's research implementation of Minimal Viable Plasma
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Golang implementation and extension of the Minimum Viable Plasma specification
* [Plasma Cash](https://github.com/mkchungs/plasma-cash) - Simple Plasma Cash implementation

#### Side-Chains
* [POA Network](https://poa.net/)
  * [POA Bridge](http://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
  * [Loom Network](https://github.com/loomnetwork)

#### Privacy

##### zkSNARKs
* [ZoKrates](https://github.com/JacobEberhardt/ZoKrates) - A toolbox for zkSNARKS on Ethereum
