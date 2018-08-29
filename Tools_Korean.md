
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
* [Dapp](https://dapp.tools/dapp/) - DApple의 뒤를 잇는 탈중앙화 어플리케이션 개발 프레임 워크 입니다.
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
* [Eth Fiddle](https://ethfiddle.com/) - IDE developed by [The Loom Network](https://loomx.io/) that allows you to write, compile and debug your smart contract. Easy to share and find code snippets.

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
    * [웹3래퍼(Web3Wrapper)](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/web3-wrapper)- 타입스크립트 웹3 대안입니다.
    * [이더리움js(Ethereumjs)](https://github.com/ethereumjs/) - 이더리움이 좋아하는  [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) 와 [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) 를 위한 유틸리티 함수 모음 입니다.

* [드리즐(Drizzle)](https://github.com/truffle-box/drizzle-box) -  리덕스(Redux) 라이브러리 블록체인 프론트엔드와 연결합니다.
* [Subproviders](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/subproviders) - [웹3 프로바이더 엔진(Web3-provider-engine)](https://github.com/MetaMask/provider-engine/) 과 함께 사용되는 여러가지 유용한 subproviders 입니다. (당신의 탈중앙화 어플리케이션을 지원하는 렛저(Ledger) 하드웨어 월렛을 위한 LedgerSubprovider를 포함합니다.)
* [웹3-웹팩(web3-webpacked)](https://github.com/NoahHydro/web3-webpacked) - JS 프레임워크를 관리하기 위한 웹3 인젝션 입니다.
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
* [댑시스(Dappsys): 안전하고, 단순하며, 유연한 이더리움 컨트렉트 개발 블록](https://github.com/dapphub/dappsys)
    * 댑시스는 이더리움/솔리디티의 일반적인 문제들에 대한 해결책을 가지고 있습니다. 예로,
        * [화이트리스팅(Whitelisting)](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [향상 가능한 ERC20 토큰(Upgradable ERC20-Token)](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [RBAC 증명](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...몇가지 더...](https://github.com/dapphub/dappsys)
    * [메이커다오(MakerDAO)](https://github.com/makerdao/maker-otc) 와 [더타오(The TAO)](https://ryepdx.github.io/the-tao/) 를 위한 개발 블록들도 제공합니다.
    * own을 만들거나, 검증되지 않거나, 솔루션 전에 상의해야 합니다.
    * 사용 설명은 [Dapp-a-day 1-10](https://steemit.com/@nikolai) 과 [Dapp-a-day 11-25](https://steemit.com/@nexusdev) 입니다.
* [오픈제플린(OpenZeppelin): 솔리디티 언어의 재사용과 안전한 스마트 컨트렉트의 오픈 프레임워크](http://zeppelin-solidity.readthedocs.io/en/latest/)
    * 가장 널리 사용되는 라이브러리와 스마트 컨트렉트들 입니다.
    * 댑시스와 유사하고, 트러플 프레임워크에 더 통합됩니다.
    * [보안 검증(Audits)과 습관들에 대한 블로그](https://medium.com/zeppelin-blog)
* [어셈블리와 향상된 워크샵](https://github.com/androlo/solidity-workshop)
* [간단한 이더리움 멀티시그(Multisig)](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - 특히 _이득(Benefits)_ 부분

##### 고급과정(Upgradebility)
* [엘레나 디미트로바(Elena Dimitrova)의 블로그, 콜로니(colony.io) 개발자](https://blog.colony.io/@elena_di)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [아라곤(Aragon)의 기술블로그](https://blog.aragon.one/tagged/development)
    * [라이브러리 주도 개발(Library driven development)](https://blog.aragon.one/library-driven-development-in-solidity-2bebcaf88736)
* [오픈제플린 프록시 라이브러리](https://medium.com/zeppelin-blog/proxy-libraries-in-solidity-79fbe4b970fd)

### 기반시설
#### 이더리움 클라이언트들
* [게스(Geth)](https://github.com/ethereum/go-ethereum/wiki/geth) - 고(Go) 클라이언트 입니다.
* [패리티(Parity)](https://www.parity.io/) - 러스트(Rust) 클라이언트 입니다.
* [Cpp-ethereum](https://github.com/ethereum/cpp-ethereum) - C++ 클라이언트 입니다.
* [Pyethapp](https://github.com/ethereum/pyethapp) - [pyethereum](https://github.com/ethereum/pyethereum) 을 이용하는 파이썬 클라이언트 입니다.
* [트리니티(Trinity)](https://github.com/ethereum/trinity) - [py-evm](https://github.com/ethereum/py-evm) 을 이용하는 파이썬 클라이언트 입니다.
* [이더리움js(Ethereumjs)](https://github.com/ethereumjs/ethereumjs-client) - [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm) 을 이용하는 JS 클라이언트 입니다.
* [이더리움j(Ethereumj)](https://github.com/ethereum/ethereumj) - 이더리움 재단의 자바 클라이언트 입니다.
* [하모니(Harmony)](https://github.com/ether-camp/ethereum-harmony) - 이더캠프(EtherCamp)의 자바 클라이언트 입니다.
* [세스(Seth)](https://github.com/dapphub/dapptools/tree/master/src/seth) - 세스는 "커멘드 라인(command line)을 위한 메타마스크" 형태의 이더리움 클라이언트 도구 입니다.
* [머스테카라(Mustekala)](https://github.com/MetaMask/mustekala) - 메타마스크의 이더리움 라이트 클라이언트 프로젝트 입니다.
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir 클라이언트 입니다.
* [EWF 패리티](https://github.com/energywebfoundation/energyweb-client) - Tobalaba 테스트 네트워크를 위한 에너지 웹 재단 클라이언트 입니다.
* [큐럼(Quorum)](https://github.com/jpmorganchase/quorum) -
[제이피모건(JP Morgan)](https://www.jpmorgan.com/quorum)에 의해 데이터 프라이버시를 지원하는 이더리움의 승인받은 구현(permissioned implementation) 입니다.

#### 저장소
* [IPFS](https://ipfs.io/) - 탈중앙화 된 저장소와 파일 레퍼런스(referencing) 입니다.
   * [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - 검색 기능이 포함된 IPFS 저장소 서비스
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - IPFS의 최상단 탈중앙화 된 데이터베이스
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-api) - IPFS HTTP API를 위한 클라이언트 라이브러리, 자바스크립트로 실행
* [스웜(Swarm)](http://swarm-gateways.net/) - 분산화 된 저장소 플랫폼과 컨텐츠 분산 서비스, 이더리움 웹3 스택(stack)의 네이티브(native) 기초 계층 서비스 입니다.

#### 메세징
* [위스퍼(Whisper)](https://github.com/ethereum/wiki/wiki/Whisper) - 각각의 탈중앙화 어플리케이션들 통신을 위한 의사소통 프로토콜, 이더리움 웹3 스택의 네이티브 기초 계층 서비스 입니다.
* [데브p2p 와이어 프로토콜(DEVp2p Wire Protocol)](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) - 작동 중인 이더리움/위스퍼 노드간 피어-투-피어(Peer-to-peer) 통신 입니다.
* [파이데브p2p(Pydevp2p)](https://github.com/ethereum/pydevp2p) - RLPx 네트워크 계층의 파이썬 구현 입니다.

### 테스팅 도구들
* [솔리디티 코드 커버리지(Solidity code coverage)](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - 솔리디티 코드 커버리지 도구 입니다.
* [솔리디티 커버리지(Solidity coverage)](https://github.com/sc-forks/solidity-coverage) - 솔리디티 스마트 컨트렉트를 위한 코드 커버리지 대안 입니다.
* [솔리디티 함수 프로파일러(Solidity function profiler)](https://github.com/EricR/sol-function-profiler) - 솔리디티 컨트렉트 함수 프로파일러 입니다.
* [에스프레소(Espresso)](https://github.com/hillstreetlabs/espresso) - 빠르고, 병렬(parallelised) 방식이며, 핫 리로딩(hot-reloading)이 있는 솔리디티 테스트 프레임워크 입니다.
* [Eth tester](https://github.com/ethereum/eth-tester) - 테스팅 이더리움 어플리케이션들을 위한 도구 세트(Tool suite) 입니다.
* [클리끄베이트(Cliquebait)](https://github.com/f-o-a-m/cliquebait) - 실제 블록체인 네트워크와 유사한 도커(docker) 인스턴스를 사용해 스마트 컨트렉트 어플리케이션을 통합(integration)하고 테스팅을 합니다.
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - hevm 프로젝트는 단위 테스팅과 스마트 컨트렉트 디버깅을 위해 특별히 만들어진 이더리움 가상 머신(EVM) 구현체 입니다.
* [이더리움 그래프 디버거(Ethereum graph debugger)](https://github.com/fergarrui/ethereum-graph-debugger) - 솔리디티 그래픽적인 디버거 입니다.
* [솔리움(Solium)](https://github.com/duaraghav8/Solium) - 솔리디티 보안 이슈 & 식별과 스타일 수정을 린터(Linter)로 합니다.
* [디코드(Decode)](https://github.com/dteiml/decode) - 읽을 수 있고 쉽게 이해할 수 있도록 로컬 testrpc 노드에서 제출된 거래를 분석하는 npm 패키지 입니다.

### 보안 도구들
* [마이스릴(Mythril)](https://github.com/ConsenSys/mythril) - 정적(Static) 스마트 컨트렉트 보안 분석 입니다.
* [오옌테(Oyente)](https://github.com/melonproject/oyente) - 정적 스마트 컨트렉트 보안 분석 대안 입니다.
* [시큐리파이(Securify)](https://securify.ch) - 이더리움 스마트 컨트렉트를 위한 보안 스캐너 입니다.
* [포로시티(Porosity)](https://github.com/comaeio/porosity) - 블록체인을 기반으로 한 이더리움 스마트 컨트렉트를 위한 디컴파일러(Decompiler)와 보안 분석 도구 입니다.
* [이더스프레이(Ethersplay)](https://github.com/trailofbits/ethersplay) - EVM 역어셈블러(disassembler) 입니다.
* [Evmdis](https://github.com/Arachnid/evmdis) - EVM 역어셈블러 대안 입니다.
* [하이드라(Hydra)](https://github.com/IC3Hydra/Hydra) - 암호화폐경제학(cryptoeconomic) 컨트렉트 보안, 탈중앙화 보안 바운티를 위한 프레임워크 입니다.
* [솔그래프(Solgraph)](https://github.com/raineorshine/solgraph) - 스마트 컨트렉트 보안분석을 위해 시각적인 솔리디티 제어 흐름을 보여줍니다.
* [만티코어(Manticore)](https://github.com/trailofbits/manticore) - 스마트 컨트렉트와 바이너리(Binaries)의 심볼릭 실행 도구 입니다.
* [솔리디티 보안 블로그(Solidity security blog)](https://github.com/sigp/solidity-security-blog) - 알려진 공격 백터(vectors)와 일반적인 안티패턴(anti-patterns) 종합 리스트 입니다.
* [어썸 버기 ERC20 토큰(Awesome Buggy ERC20 Tokens)](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - 토큰에 영향을 주는 ERC20 스마트 컨트렉트의 취약성 모음 입니다.

### 모니터링
* [노이펀드(Neufund) - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - 스마트 컨트렉트와 거래의 수를 모니터하는 도구 입니다.
* [수퍼맥스(Supermax)](https://www.supermax.cool/) - 이더리움 안에서 당신의 스마트 컨트렉트의 이벤트 로그와 활동을 바로(live) 데이터 피드(data feed) 합니다.

### 그 밖에 다양한 도구들
* [트러플 박스(Truffle boxes)](http://truffleframework.com/boxes/) - 탈중앙화 어플리케이션을 빠르게 만들기 위한 패키지 컴포넌트 입니다.
   * [쳬셔(Cheshire)](https://github.com/endless-nameless-inc/cheshire) - 크립토키티(CryptoKitties) API와 스마트 컨트렉트의 로컬 샌드박스 도구이며, 트러플 박스로 이용 가능합니다.
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - 솔리디티 컴파일러 입니다.
* [솔컴파일러(Sol-compiler)](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-compiler) - 프로젝트 단계의 솔리디티 컴파일러 입니다.
* [Solidity cli](https://github.com/pubkey/solidity-cli) - 솔리디티 코드를 빠르고 쉽고, 더 믿을 수 있게 컴파일 합니다.
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - 솔리디티 프로젝트와 단층 파일(flat file) 유틸리티를 합쳐줍니다. 이더스캔(Etherscan)에서 컨트렉트 인증하거나 임포트(imported) 된 컨트렉트 시각화에 유용합니다.
* [RLP](https://github.com/ethereumjs/rlp) - 자바스크립트의 RLP(Recursive Length Prefix) 인코딩 입니다.
* [이더리얼(Ethereal)](https://github.com/wealdtech/ethereal) - 이더리얼은 이더리움에서 일반 작업 관리를 위한 커멘드 라인 도구 입니다.
* [Eth crypto](https://github.com/pubkey/eth-crypto) - web3js와 솔리디티를 사용하는 튜토리얼과 이더리움을 위한 암호적(Cryptographic) 자바스크립트 함수 입니다.
* [패리티 싸이너(Parity Signer)](https://github.com/paritytech/parity-signer) - 서명(signing) 거래를 모바일 어플리케이션으로 가능하게 합니다.
* [py-eth](http://www.pyeth.com) - 이더리움 생태계를 위한 파이썬 도구들 모음 입니다.
* [truffle-flattener](https://github.com/alcuadrado/truffle-flattener) - 트러플에서 개발 중인 솔리디티 파일의 의존성(dependencies)을 연결(concats)해 줍니다.
* [디코드(Decode)](https://github.com/dteiml/decode) - 읽을 수 있고 쉽게 이해할 수 있도록 로컬 testrpc 노드에서 제출된 거래를 분석하는 npm 패키지 입니다.
* [타입체인(TypeChain)](https://github.com/Neufund/TypeChain) - 이더리움 스마트 컨트렉트를 위한 타입스크립트 바인딩(bindings) 입니다.
* [EthSum](https://ethsum.netlify.com) - 간단하게 이더리움 주소를 검사합(Checksum)하는 도구 입니다.
* [PHP를 기반 블록체인 인덱서(PHP based Blockchain indexer)](https://github.com/digitaldonkey/ethereum-php-eventlistener) - PHP에서 이벤트 리스닝 또는 블록 인덱싱 해 줍니다.

### 스마트 컨트렉트 표준들 & 라이브러리들
#### [ERCs](https://eips.ethereum.org/erc) - 이더리움 주석 요청(Ethereum Request for Comment) 리포지토리(repository)
* 토큰들
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - 대체 가능 자산(fungible assets)의 토큰 컨트렉트 입니다.
  * [ERC-721](https://github.com/ethereum/eips/issues/721) - 대체 불가 자산(non-fungible assets) 토큰 기준 입니다.
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - 스마트 컨트렉트 도구 인터페이스 확인(detect)과 발행(publish)를 표준 방법으로 생성 합니다.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - 키 관리와 실행, 블록체인 아이덴티 구축을 위한 프록시 컨트렉트 입니다.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - 컨트렉트의 소유권(ownership)을 위한 표준 인터페이스 입니다.

#### 인기있는 스마트 컨트렉트 라이브러리들
* [제플린(Zeppelin)](https://github.com/OpenZeppelin/openzeppelin-solidity) - 스마트 컨트렉트 향상을 위한 제플린OS [라이브러리](https://github.com/zeppelinos/zos-lib) 와 [세이프매스(SafeMath)](https://openzeppelin.org/api/docs/math_SafeMath.html)와 같이 테스트 된 재사용가능 스마트 컨트렉트들이 포함되어 있습니다.
* [모듈러 라이브러리(Modular Libraries)](https://github.com/Modular-Network/ethereum-libraries) - 이더리움 가상 머신을 활용하는 블록체인 사용을 위한 개발 패키지 그룹 입니다.
* [데이트타임 라이브러리(DateTime Library)](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - 가스 효율이 좋은 솔리디티 일시(date and time) 라이브러리 입니다.
* [아라곤(Aragon)](https://github.com/aragon/aragon) - DAO 프로토콜 입니다.
* [0x](https://github.com/0xProject) - DEX 프로토콜 입니다.
* [프루프 토큰 라이브러리(Token Libraries with Proofs)](https://github.com/sec-bit/tokenlibs-with-proofs) - 주어진 사양(specifications)과 고차원 속성(high-level properties)에 관해 토큰 컨트렉트의 정확성(correctness) 증명을 포함합니다.

### 2번째 계층 구조(Infrastructure)를 위한 개발자 가이드들

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
