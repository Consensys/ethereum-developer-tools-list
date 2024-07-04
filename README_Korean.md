
# 이더리움 개발자 도구 리스트(Ethereum Developer Tools List)
이더리움 위에서 개발 어플리케이션을 위한 도구와 컴포넌트(components), 패턴(patterns), 플랫폼(platforms)의 사용 가이드 입니다.

신입과 경력있는 블록체인 개발자들 사이에서 도구와 개발 패턴, 컴포넌트의 더 좋은 공유를 원하는 컨센시스(ConsenSys)의 프로덕트 매니저에 의해 이 리스트가 만들어졌습니다.

이 자료는 개발자 툴에 집중하는 것뿐만 아니라, 유용한 탈중앙화 어플리케이션(DApps)과 교육적인 자료, 지갑, 서비스를 위한 [이더리움 생태계 자료들(Ethereum Ecosystem Resources)](EcosystemResources_Korean.md)도 포함되어 있습니다.

## 기여자들(Contributions)을 환영합니다!

작은 수정에서 부터 추가(삭제)하려는 툴까지 어느 것이든 자유롭게 풀리퀘스트(pull request)를 해주세요.
만약에 새로운 툴을 추가하면, 당신이 생각하기에 새로운 개발자들이 이해할 수 있도록 **간략한 설명을 적어주세요**

[@corbpage](https://twitter.com/corbpage) 와 [메리디오(Meridio)](https://meridio.co)를 큐레이팅하고 있는 [@pakaplace](https://twitter.com/Parker_Place) 그리고 좀 더 논리적인 방법으로 리스트를 재구축한 @jpantunes 를 포함해 100명이 넘는 기여자들에게 감사를 표합니다.

* 작동하지 않는 제품의 프로젝트는 추가할 수 없습니다.
* 더 이상 사용되지 않거나 유지되지 않는 프로젝트는 제거 되게 됩니다.
* 오픈소스 코드가 아니거나 개발자 리뷰가 없는 유료/제한 서비스 프로젝트들은 추가로 조사될 것 입니다.

^위 내용이 타당하죠? 당신의 생각을 말해주세요 - https://github.com/ConsenSysLabs/ethereum-developer-tools-list/pull/70

## 목차
 - [신입 개발자는 여기서부터 시작](#신입개발자는여기서부터시작)
 - [개발 도구](#개발도구)
    - [스마트 컨트렉트 언어](#스마트컨트렉트언어)
    - [프레임워크](#프레임워크)
    - [통합 개발 환경](#통합개발환경)
    - [블록체인 테스트 네트워크](#블록체인테스트네트워크)
    - [테스트 이더 파우셋](#테스트이더파우셋)
 - [이더리움과 정보 전달](#이더리움과정보전달)
    - [이더리움 프론트엔드 API](#이더리움프론트엔드API)
    - [이더리움 백엔드 API](#이더리움백엔드API)
    - [부트스트랩 / 실행 도구](#부트스트랩실행도구)
    - [이더리움 ABI(Application Binary Interface) 도구](#이더리움ABI도구)
 - [패턴 & 모범 사례](#패턴&모범사례)
    - [스마트 컨트렉트 개발을 위한 패턴](#스마트컨트렉트개발을위한패턴)
    - [고급과정](#고급과정)
 - [기반시설](#기반시설)
    - [이더리움 클라이언트](#이더리움클라이언트)
    - [저장소](#저장소)
    - [메세징](#메세징)
 - [테스팅 도구](#테스팅도구)
 - [보안 도구](#보안도구)
 - [모니터링](#모니터링)
 - [그 밖에 다양한 도구](#그밖에다양한도구)
 - [스마트 컨트렉트 표준 & 라이브러리](#스마트컨트렉트표준&라이브러리)
    - [ERCs - 이더리움 주석 요청(Ethereum Request for Comment) 저장소](#ERCs-이더리움주석요청저장소)
    - [인기있는 스마트 컨트렉트 라이브러리](#인기있는스마트컨트렉트라이브러리)
 - [2번째 계층 구조를 위한 개발자 가이드](#2번째계층구조를위한개발자가이드)
    - [확장성](#확장성)
    - [결제/상태 채널](#결제/상태채널)
    - [플라즈마](#플라즈마)
    - [사이드체인](#사이드체인)
 - [프라이버시 / 비밀보호](#프라이버시)
    - [zkSNARKs](#zksnarks)
 - [UI 컴포넌트 사전빌드](#ui)

<a name="신입개발자는여기서부터시작"></a>
## 신입 개발자는 여기서부터 시작
* [솔리디티(Solidity)](https://solidity.readthedocs.io/en/latest/) - 가장 유명한 스마트 컨트렉트 언어입니다.
* [트러플(Truffle)](https://truffleframework.com) - 가장 유명한 스마트 컨트렉트 개발, 테스팅, 배포(deployment) 프레임워크 입니다. npm에서 cli를 설치하고 당신의 첫번째 스마트 컨트렉트를 작성하세요.
* [메타마스크(Metamask)](https://metamask.io/) - 크롬 확장 지갑으로 탈중앙화 어플리케이션과 작동합니다.
* [트러플 박스(Truffle boxes)](https://truffleframework.com/boxes/) - 이더리움 생태계를 위한 패키지 컴포넌트 입니다.
* [EthHub.io](https://docs.ethhub.io/) - 이더리움의 개요 (역사, 거버넌스, 향후 계획, 개발 리소스)가 있는 종합적인 크라우드 소스(crowdsourced)입니다.
* [dfuse](https://dfuse.io) - 매끄러운 블록 체인 API로 세계적 수준의 애플리케이션을 구축하십시오.
<a name="개발도구"></a>
## 개발 도구

### 스마트 컨트렉트 개발
<a name="스마트컨트렉트언어"></a>
#### 스마트 컨트렉트 언어
* [솔리디티(Solidity)](https://solidity.readthedocs.io/en/latest/) - 이더리움 스마트 컨트렉트 언어 입니다.
* [밤부(Bamboo)](https://github.com/pirapira/bamboo) - 모핑 스마트 컨트렉트 언어 입니다.
* [바이퍼(Vyper)](https://github.com/ethereum/vyper) - 새롭게 시도되는 파이썬 프로그래밍 언어 입니다.
* [LLL](https://media.consensys.net/an-introduction-to-lll-for-ethereum-smart-contract-development-e26e38ea6c23) - Low-level Lisp-like Language, 저수준 프로그래밍 언어 입니다.
* [Flint](https://docs.flintlang.org/) - 자산 유형(asset types)과 상태 변환(state transition), 안전한 정수(safe integers)를 포함하고 보안 기능을 고려해 개발 중인 새로운 언어 입니다.
<a name="프레임워크"></a>
#### 프레임워크
* [트러플(Truffle)](https://truffleframework.com) - 가장 유명한 스마트 컨트렉트 개발, 테스팅, 배포 프레임워크 입니다. 트러플 세트(suite)는 트러플과 [가나쉬(Ganache)](https://github.com/trufflesuite/ganache), [드리즐(Drizzle)](https://github.com/truffle-box/drizzle-box)이 포함되어 있습니다. [트러플에 대한 보충설명](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [엠바크(Embark)](https://github.com/embark-framework/embark) - 탈중앙화 어플리케이션 개발을 위한 프레임워크 입니다.
* [와플(Waffle)](https://getwaffle.io/) - 진화한 스마트 컨트렉트 개발, 테스팅을 위한 프레임워크 입니다. ethers.js를 기반으로 작고 유연하며 빠릅니다.
* [Dapp](https://dapp.tools/dapp/) - DApple의 뒤를 잇는 탈중앙화 어플리케이션 개발 프레임 워크 입니다.
* [팝풀러스(Populus)](https://github.com/ethereum/populus) - 가장 귀여운 동물 사진들과 함께하는 이더리움 개발 프레임워크 입니다.
* [이더라임(Etherlime)](https://github.com/LimeChain/etherlime) - ethers.js를 기반으로 한 탈중앙화 어플리케이션 개발 프레임워크 입니다.
* [Parasol](https://github.com/Lamarkaz/parasol) - 테스팅과 인퓨라(INFURA) 배포, 자동 컨트렉트 문서 등 애자일(Agile)방식의 스마트 컨트렉트 개발 환경 입니다. 자유로운 사용자 정의(unlimited customizability)와 남을 생각하는(unopinionated) 디자인, 융통성(flexible) 있는 기능이 있습니다.
* [0xcert](https://github.com/0xcert/framework/) - 탈중앙화 어플리케이션 제작을 위한 자바스크립트 프레임워크 입니다.
<a name="통합개발환경"></a>
* [EVMTools](https://evmtools.xyz) - 웹3 및 솔리디티 개발자를 위한 EVM 도구 모음, 모든 개발 도구를 한 곳에서. 20개 이상의 유틸리티가 있으며, 더 많은 유틸리티가 자주 추가됩니다.

#### 통합 개발 환경
* [리믹스(Remix)](https://remix.ethereum.org/) - 블록체인 가상머신에서 테스트와 정적 분석(static analysis)이 포함된 웹 통합 개발 환경 입니다.
* [수퍼블록스 랩(Superblocks Lab)](https://superblocks.com/lab/) - 웹 통합 개발 환경입니다. 브라우저에 내장된 블록체인 가상머신, 메타마스크 통합 (테스트넷/메인넷에 클릭 한번으로 배포), 거래 기록과 웹앱(WebApp)의 다른 기능들간 라이브 코드 입니다.
* [아톰(Atom)](https://atom.io/) - [아톰 솔리디티 린터(Atom Solidity Linter)](https://atom.io/packages/atom-solidity-linter)와 [이더아톰(Etheratom)](https://atom.io/packages/etheratom) , [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), [language-solidity](https://atom.io/packages/language-solidity) 패키지가 있는 아톰 에디터 입니다.
* [프라그마(Pragma)](https://www.withpragma.com/) - 솔리디티를 위한 아주 간단한 웹 통합 개발 환경으로, 스마트 컨트렉트를 자동 생성 인터페이스 입니다. [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity)과  [language-solidity](https://atom.io/packages/language-solidity) 패키지가 있습니다.
* [빔 솔리디티(Vim solidity)](https://github.com/tomlion/vim-solidity) - 솔리디티를 위한 빔 문법 파일 입니다.
* [비주얼 스튜디오 코드(Visual Studio Code)](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - 비주얼 스튜디오 코드에서 솔리디티 지원 확장 프로그램 입니다.
* [인텔리j 솔리디티 플러그인(Intellij Solidity Plugin)](https://github.com/intellij-solidity/intellij-solidity/wiki) - [젯브레인 인텔리j 아이디어 통합개발환경(JetBrains IntelliJ Idea IDE)](https://www.jetbrains.com/idea/) (무료/상업용)으로 문법 강조, 형식, 코드 완성 등의 오픈소스 플러그인 입니다.
* [야킨두 솔리디티 도구(YAKINDU Solidity Tools)](https://github.com/Yakindu/solidity-ide) - 이클립스(Eclipse)를 기반으로 한 통합 개발 환경입니다. 문맥 완성이 민감하고 도움말, 코드 탐색, 문법 색구분, 컴파일러 빌딩, 빠른 수정, 템플릿이 특징입니다.
* [Eth Fiddle](https://ethfiddle.com/) - [룸 네트워크(The Loom Network)](https://loomx.io/)에서 개발한 통합개발환경(IDE)에서 스마트 컨트렉트를 작성, 컴파일과 디버깅을 할 수 있습니다. 공유하기 쉽고 코드 정보(snippets)를 확인할 수 있습니다.
<a name="블록체인테스트네트워크"></a>
### 블록체인 테스트 네트워크
* [가나쉬(Ganache)](https://github.com/trufflesuite/ganache) - 시각적인 UI와 로그들을 보여주는 테스트 이더리움 블록체인 어플리케이션 입니다.
* [칼레이도(Kaleido)](https://kaleido.io/) - 컨소시엄(consortium) 블록체인 네트워크를 돌릴때 사용하세요. 개념증명들(PoCs)과 테스팅에 좋습니다.
* [Pantheon Private Network](https://docs.pantheon.pegasys.tech/en/latest/Getting-Started/Private-Network-Quickstart/) - 도커(Docker) 컨테이너 안에서 판테온(Pantheon) 노드의 프라이빗 네트워크를 사용할 수 있습니다.
** [Orion](https://github.com/PegaSysEng/orion) - 페가시스(PegaSys)의 프라이빗 거래 수행을 위한 컴포넌트 입니다. 
** [Artemis](https://github.com/PegaSysEng/artemis) - 페가시스(PegaSys)의 이더리움 2.0 비콘 체인의 자바 구현물 입니다.
* [클리끄베이트(Cliquebait)](https://github.com/f-o-a-m/cliquebait) - 실제 블록체인 네트워크와 유사한 도커(docker) 인스턴스를 사용해 스마트 컨트렉트 어플리케이션을 통합(integration)하고 테스팅을 합니다.
* [로컬 라이덴(Local Raiden)](https://github.com/ConsenSys/Local-Raiden) - 데모(demo)와 테스트 목적으로 도커 컨테이너에서 로컬 라이덴 네트워크를 실행하세요.
* [개인 네트워크 배포 스크립트(Private networks deployment scripts)](https://github.com/ConsenSys/private-networks-deployment-scripts) - 개인 권위증명(PoA) 네트워크를 위한 배포 스크립트를 실행(Out-of-the-box) 합니다.
* [로컬 이더리움 네트워크(Local Ethereum Network)](https://github.com/ConsenSys/local_ethereum_network) - 개인 작업증명(PoW) 네트워크를 위한 배포 스크립트로 실행 합니다.
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain-workbench/ethereum-poa-deployment) - 이더리움 PoA 네트워크 컨소시엄의 거버넌스와 배포 네트워크 입니다.
* [getho](https://getho.io) - PoA 방식의 프라이빗 블록체인과 스마트 컨트렉트 테스팅 툴이 있는 DApp 개발 플랫폼 입니다.
* [Ethereum on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - 작업증명(Proof of Work)을 기반으로 한 이더리움 네트워크를 만들 수 있습니다. 
<a name="테스트이더파우셋"></a>
#### 테스트 이더 파우셋(faucets)
* [링크비 파우셋(Rinkeby faucet)](https://faucet.rinkeby.io/)
* [코반 파우셋(Kovan faucet)](https://github.com/kovan-testnet/faucet)
* [롭스텐 파우셋(Ropsten faucet)](http://faucet.ropsten.be:3001/)
* [홀레스키 파우셋(Holesky faucet)](https://stakely.io/en/faucet/ethereum-holesky-testnet-eth)
* [유니버셜 파우셋(Universal faucet)](https://faucets.blockxlabs.com/)
* [니더리움 파우셋(Nethereum Faucet)](https://github.com/Nethereum/Nethereum.Faucet) - C#/.NET 파우셋 입니다.
<a name="이더리움과정보전달"></a>
### 이더리움과 정보 전달
<a name="이더리움프론트엔드API"></a>
#### 이더리움 프론트엔드 API
* [Web3.js](https://github.com/ethereum/web3.js/) - 자바스크립트 웹3 입니다.
    * [Eth.js](https://github.com/ethjs) - 자바스크립트 웹3 대안입니다.
    * [Ethers.js](https://github.com/ethers-io/ethers.js/) - 자바스크립트 웹3 대안이고, 유용한 유틸리티들과 지갑 기능이 있습니다.
    * [웹3래퍼(Web3Wrapper)](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/web3-wrapper) - 타입스크립트 웹3 대안입니다.
    * [이더리움js(Ethereumjs)](https://github.com/ethereumjs/) - 이더리움이 좋아하는  [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) 와 [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) 를 위한 유틸리티 함수 모음 입니다.
    * [flex-contract](https://github.com/merklejerk/flex-contract) 와 [flex-ether](https://github.com/merklejerk/flex-ether) 는 최신이며, 제로 구성(zero-configuration), 스마트 컨트렉트와 트렌젝션을 만들때 상호작용을 위한 고수준 (high-level) 라이브러리 입니다.
    * [ez-ens](https://github.com/merklejerk/ez-ens) 간단하며, 제로 구성(zero-configuration) 이더리움 이름 서비스(Ethereum Name Service) 주소 해결책 입니다.
    * [web3x](https://github.com/xf00f/web3x) - web3.js의 타입스크립트 포트 입니다. 컨트렉트 상호작용이 포함되어 모든 타입의 보안(safety)과 작은 빌드의 이점이 있습니다.
* [드리즐(Drizzle)](https://github.com/truffle-box/drizzle-box) - 리덕스(Redux) 라이브러리 블록체인 프론트엔드와 연결합니다.
* [dfuse](https://github.com/dfuse-io/client-js) - [dfuse Ethereum API](https://dfuse.io)를 사용하는 TypeScript 라이브러리
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) - 리엑트 네이티브(React Native)를 사용하여 모바일 이더리움 dapps를 만들기 위한 자바스크립트 SDK 입니다.
* [useMetamask](https://github.com/mdtanrikulu/use-metamask) - 이더리움 분산 응용 프로그램(Ethereum ĐApp) 프로젝트에서 메타마스크(Metamask) 를 관리하는 사용자 정의 React Hook
* [WalletConnect](https://walletconnect.org/) - 월렛과 분산 애플리케이션 (DApp)을 연결하기위한 개방형 프로토콜
* [Subproviders](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/subproviders) - [웹3 프로바이더 엔진(Web3-provider-engine)](https://github.com/MetaMask/provider-engine/) 과 함께 사용되는 여러가지 유용한 subproviders 입니다. (당신의 탈중앙화 어플리케이션을 지원하는 렛저(Ledger) 하드웨어 월렛을 위한 LedgerSubprovider를 포함합니다.)
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - 싱글페이지(single-page) 이더리움 dApps를 빌딩하기 위한 리액트 프레임워크 입니다.
* [볼텍스(Vortex)](https://github.com/Horyus/vortex) - Dapp-ready 리덕스 Store 입니다. 웹소켓(WebSockets) 덕분에 효율적(Smart)이고 민첩(Dynamic)하게 백그라운드 데이터를 새로고침 합니다. [트러플](https://github.com/Horyus/vortex-demo) 과 [엠바크](https://github.com/Horyus/vortex-demo-embark)와 작동합니다.
* Strictly Typed - 자바스크립트 대안 입니다.
     * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
     * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
<a name="이더리움백엔드API"></a>
#### 이더리움 백엔드 API
* [Web3.py](https://github.com/ethereum/web3.py) - 파이썬 웹3 입니다.
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP 웹3 입니다.
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP 웹3 입니다.
* [Web3j](https://github.com/web3j/web3j) - 자바 웹3 입니다.
* [ethers-kt](https://github.com/Kr1ptal/ethers-kt) - EVM 기반 블록체인과 상호 작용하기 위한 비동기, 고성능 Kotlin 라이브러리입니다. JVM 및 Android 플랫폼을 대상으로 합니다.
* [Nethereum](https://nethereum.com/) - 닷넷 웹3 입니다.
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - 루비 웹3 입니다.
* [Web3.hs](https://hackage.haskell.org/package/web3) - 하스켈(Haskell) 웹3 입니다.
* [KEthereum](https://github.com/walleth/kethereum) - 코틀린(Kotlin) 웹3 입니다.
* [web3dart](https://github.com/xclud/web3dart) - 다트 웹3
* [Pyethereum](https://github.com/ethereum/pyethereum) - 이더리움 프로젝트의 파이썬 코어 라이브러리 입니다.
* [Eventeum](https://github.com/ConsenSys/eventeum) - 이더리움 스마트 컨트렉트 이벤트와 백엔드 마이크로서비스를 연결 합니다. Kauri가 자바로 작성했습니다.
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - 이더리움 블록체인을 위한 엘릭서(Elixir) JSON-RPC 클라이언트 입니다.
* [EthContract](https://github.com/AgileAlpha/eth_contract) - 엘릭서(Elixir) 언어로 된 이더리움 스마트 컨트렉트 쿼리를 도와주는 헬퍼 메소드(helper methods) 세트 입니다.
<a name="부트스트랩실행도구"></a>
#### 부트스트랩(Bootstrap) / 실행(out of box) 도구
* [트러플 박스(Truffle boxes)](https://truffleframework.com/boxes/) - 이더리움 생태계를 위한 패키지 컴포넌트 입니다.
* [Pantheon Private Network](https://docs.pantheon.pegasys.tech/en/latest/Getting-Started/Private-Network-Quickstart/) - 도커(Docker) 컨테이너 안에서 판테온(Pantheon) 노드의 프라이빗 네트워크를 사용할 수 있습니다.
* [Testchains](https://github.com/Nethereum/TestChains) - 빠른 반응을 위한 닷넷 데브체인(devchains) 사전구성(Pre-configured) 입니다(PoA). ** [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - 와즘(Wasm) 블록체인 익스플로러 입니다. (샘플 기능)
* [로컬 라이덴(Local Raiden)](https://github.com/ConsenSys/Local-Raiden) - 데모(demo)와 테스트 목적으로 도커 컨테이너에서 로컬 라이덴 네트워크를 실행 합니다.
* [개인 네트워크 배포 스크립트(Private networks deployment scripts)](https://github.com/ConsenSys/private-networks-deployment-scripts) - 개인 권위증명(PoA) 네트워크를 위한 배포 스크립트를 실행(Out-of-the-box) 합니다.
* [패리티 데모-권위증명 튜토리얼(Parity Demo-PoA Tutorial)](https://wiki.parity.io/Demo-PoA-tutorial.html) - 2개의 노드로 패리티 합의 인증 라운드와 PoA 테스트 체인을 만들기 위한 단계별 튜토리얼입니다.
* [로컬 이더리움 네트워크(Local Ethereum Network)](https://github.com/ConsenSys/local_ethereum_network) - 개인 작업증명(PoW) 네트워크를 위한 배포 스크립트로 실행 합니다.
* [칼레이도(Kaleido)](https://kaleido.io/) - 컨소시엄(consortium) 블록체인 네트워크를 돌릴때 사용하세요. 개념증명들(PoCs)과 테스팅에 좋습니다.
* [쳬셔(Cheshire)](https://github.com/endless-nameless-inc/cheshire) - 크립토키티(CryptoKitties) API와 스마트 컨트렉트의 로컬 샌드박스 도구이며, 트러플 박스로 이용 가능합니다.
* [Aragon CLI](https://hack.aragon.org/docs/cli-usage.html) - 아라곤(Aragon) CLI는 아라곤 앱 개발과 생성하는데 이용됩니다.
* [ColonyJS](https://github.com/JoinColony/colonyJS) - 콜로니 네트워크(Colony Network) 스마트 컨트렉트와 상호작용하는 API를 자바스크립트 클라이언트로 제공합니다.
* [ArcJS](https://github.com/daostack/arc.js) - 자바스크립트 어플리케이션을 이더리움 스마트 컨트렉트 DAOstack Arc로 접근을 가능하게 해주는 라이브러리 입니다.
<a name="이더리움ABI도구"></a>
#### 이더리움 ABI(Application Binary Interface) 도구
* [ABI 디코더(decoder)](https://github.com/ConsenSys/abi-decoder) - 이더리움 거래(transactions)의 데이터 매개변수 디코딩과 이벤트를 위한 라이브러리
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/abi-gen) - 컨트렉트 ABI의 타입스크립트 컨트렉트 래퍼(wrappers)를 생성합니다.
* [이더리움 ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - 이더리움 컨트렉트 ABI의 필드 정의와 관련 발리데이터(validators) UI를 자동 생성 합니다.
* [headlong](https://github.com/esaulpaugh/headlong/) - 프로그램의 동작이 잘 정의된(type-safe) 컨트렉트 ABI와 자바 언어로 된 RLP(Recursive Length Prefix) 라이브러리 입니다.
* [One Click dApp](https://oneclickdapp.com) -  ABI를 이용해 유일한 URL로 dApp를 즉시 생성 합니다.
* [Truffle Pig](https://www.npmjs.com/package/trufflepig) - 로컬로 개발할때 사용하도록, 간단한 HTTP API를 찾거나 트러플에서 생성된 컨트렉트 파일을 읽는 개발 툴 입니다. http를 통해 최신 컨트렉트 ABI를 제공합니다.
<a name="패턴&모범사례"></a>
#### 패턴 & 모범 사례(Best Practices)
<a name="스마트컨트렉트개발을위한패턴"></a>
##### 스마트 컨트렉트 개발을 위한 패턴
* [댑시스(Dappsys): 안전하고, 단순하며, 유연한 이더리움 컨트렉트 개발 블록](https://github.com/dapphub/dappsys)
    * 댑시스는 이더리움/솔리디티의 일반적인 문제들에 대한 해결책을 가지고 있습니다. 예로,
        * [화이트리스팅(Whitelisting)](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [향상 가능한 ERC20 토큰(Upgradable ERC20-Token)](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [RBAC 증명](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...몇가지 더...](https://github.com/dapphub/dappsys)
    * [메이커다오(MakerDAO)](https://github.com/makerdao/maker-otc) 와 [더타오(The TAO)](https://github.com/ryepdx/the-tao) 를 위한 개발 블록들도 제공합니다.
    * own을 만들거나, 검증되지 않거나, 솔루션 전에 상의해야 합니다.
    * 사용 설명은 [Dapp-a-day 1-10](https://steemit.com/@nikolai) 과 [Dapp-a-day 11-25](https://steemit.com/@nexusdev) 입니다.
* [오픈제플린(OpenZeppelin): 솔리디티 언어의 재사용과 안전한 스마트 컨트렉트의 오픈 프레임워크](https://github.com/OpenZeppelin/openzeppelin-solidity)
    * 가장 널리 사용되는 라이브러리와 스마트 컨트렉트들 입니다.
    * 댑시스와 유사하고, 트러플 프레임워크에 더 통합됩니다.
    * [보안 검증(Audits)과 습관들에 대한 블로그](https://medium.com/zeppelin-blog)
* [어셈블리와 향상된 워크샵](https://github.com/androlo/solidity-workshop)
* [간단한 이더리움 멀티시그(Multisig)](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - 특히 _이득(Benefits)_ 부분
* [크립토핀 솔리디티 감사 체크리스크(CryptoFin Solidity Auditing Checklist)](https://github.com/cryptofinlabs/audit-checklist) - 일반적인 조사 결과들(findings)과 메인넷 시작(launch)을 위한 컨트렉트 분석(auditing)때 주의해야 할 이슈의 체크리스트 입니다.
* [아라곤OS(aragonOS): DAO와 탈중앙화 어플리케이션, 프로토콜을 위한 스마트 컨트렉트 프레임워크](https://hack.aragon.org/docs/aragonos-intro.html)
     * 업그레이드가능(Upgradebility): 스마트 컨트렉트는 최신 버전으로 업그레이드 할 수 있습니다.
     * 승인 통제(Permission control): `auth` 와 `authP` 수정자를 사용함으로써, 다른 어플리케이션 또는 엔티티(entities)만 접근할 수 있도록 기능을 보호할 수 있습니다.
     * 촉진자(Forwarders): 아라곤OS 어플리케이션 다른 어플리케이션에게 실행(action)을 할 인텐트(intent)를 보내는데, 인텐트는 일련의 요구사항 충족이 되어야 전달됩니다.
<a name="고급과정"></a>
##### 고급과정(Upgradebility)
* [엘레나 디미트로바(Elena Dimitrova)의 블로그, 콜로니(colony.io) 개발자](https://blog.colony.io/author/elena/)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [아라곤(Aragon)의 연구블로그](https://blog.aragon.one/tagged/research/)
    * [라이브러리 주도 개발(Library driven development)](https://blog.aragon.one/library-driven-development-in-solidity-2bebcaf88736)
    * [Advanced Solidity code deployment techniques](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [오픈제플린 프록시 라이브러리](https://blog.zeppelin.solutions/proxy-libraries-in-solidity-79fbe4b970fd)
<a name="기반시설"></a>
### 기반시설
<a name="이더리움 클라이언트"></a>
#### 이더리움 클라이언트
* [판테온(Pantheon)](https://docs.pantheon.pegasys.tech/en/latest/) - 페가시스(PegaSys)의 자바 클라이언트 입니다.
* [게스(Geth)](https://github.com/ethereum/go-ethereum/wiki/geth) - 고(Go) 클라이언트 입니다.
* [패리티(Parity)](https://www.parity.io/) - 러스트(Rust) 클라이언트 입니다.
* [Aleth](https://github.com/ethereum/aleth) - C++ 클라이언트 입니다.
* [Pyethapp](https://github.com/ethereum/pyethapp) - [pyethereum](https://github.com/ethereum/pyethereum) 을 이용하는 파이썬 클라이언트 입니다.
* [트리니티(Trinity)](https://github.com/ethereum/trinity) - [py-evm](https://github.com/ethereum/py-evm) 을 이용하는 파이썬 클라이언트 입니다.
* [이더리움js(Ethereumjs)](https://github.com/ethereumjs/ethereumjs-client) - [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm) 을 이용하는 JS 클라이언트 입니다.
* [이더리움j(Ethereumj)](https://github.com/ethereum/ethereumj) - 이더리움 재단의 자바 클라이언트 입니다.
* [하모니(Harmony)](https://github.com/ether-camp/ethereum-harmony) - 이더캠프(EtherCamp)의 자바 클라이언트 입니다.
* [세스(Seth)](https://github.com/dapphub/dapptools/tree/master/src/seth) - 세스는 "커멘드 라인(command line)을 위한 메타마스크" 형태의 이더리움 클라이언트 도구 입니다.
* [머스테카라(Mustekala)](https://github.com/musteka-la/mustekala) - 메타마스크의 이더리움 라이트 클라이언트 프로젝트 입니다.
* [Exthereum](https://github.com/exthereum/blockchain) - 엘릭서(Elixir) 클라이언트 입니다.
* [EWF 패리티](https://github.com/energywebfoundation/energyweb-ui) - Tobalaba 테스트 네트워크를 위한 에너지 웹 재단 클라이언트 입니다.
* [큐럼(Quorum)](https://github.com/jpmorganchase/quorum) -
[제이피모건(JP Morgan)](https://www.jpmorgan.com/quorum)에 의해 데이터 프라이버시를 지원하는 이더리움의 승인받은 구현(permissioned implementation) 입니다.
* [Mana](https://github.com/mana-ethereum/mana) - 엘릭서(Elixir)로 쓰여진 이더리움 전체노드(full node) 구현체 입니다.
<a name="저장소"></a>
#### 저장소
* [IPFS](https://ipfs.io/) - 탈중앙화 된 저장소와 파일 레퍼런스(referencing) 입니다.
   * [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - 검색 기능이 포함된 IPFS 저장소 서비스
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - IPFS의 최상단 탈중앙화 된 데이터베이스
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - IPFS HTTP API를 위한 클라이언트 라이브러리, 자바스크립트로 실행
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - 다른 분산화/탈중앙화 저장소 프로토콜과 IPFS로 들어오는 API를 쉽게 이용
* [스웜(Swarm)](https://swarm-gateways.net/) - 분산화 된 저장소 플랫폼과 컨텐츠 분산 서비스, 이더리움 웹3 스택(stack)의 네이티브(native) 기초 계층 서비스 입니다.
<a name="메세징"></a>
#### 메세징
* [위스퍼(Whisper)](https://github.com/ethereum/wiki/wiki/Whisper) - 각각의 탈중앙화 어플리케이션들 통신을 위한 의사소통 프로토콜, 이더리움 웹3 스택의 네이티브 기초 계층 서비스 입니다.
* [데브p2p 와이어 프로토콜(DEVp2p Wire Protocol)](https://github.com/ethereum/devp2p/blob/master/devp2p.md) - 작동 중인 이더리움/위스퍼 노드간 피어-투-피어(Peer-to-peer) 통신 입니다.
* [파이데브p2p(Pydevp2p)](https://github.com/ethereum/pydevp2p) - RLPx 네트워크 계층의 파이썬 구현 입니다.
<a name="테스팅도구"></a>
### 테스팅 도구
* [솔리디티 코드 커버리지(Solidity code coverage)](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - 솔리디티 코드 커버리지 도구 입니다.
* [솔리디티 커버리지(Solidity coverage)](https://github.com/sc-forks/solidity-coverage) - 솔리디티 스마트 컨트렉트를 위한 코드 커버리지 대안 입니다.
* [솔리디티 함수 프로파일러(Solidity function profiler)](https://github.com/EricR/sol-function-profiler) - 솔리디티 컨트렉트 함수 프로파일러 입니다.
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - 업데이트 된 솔리디티 스마트 컨트렉트 프로파일러(profiler) 및 대안 입니다.
* [에스프레소(Espresso)](https://github.com/hillstreetlabs/espresso) - 빠르고, 병렬(parallelised) 방식이며, 핫 리로딩(hot-reloading)이 있는 솔리디티 테스트 프레임워크 입니다.
* [Eth tester](https://github.com/ethereum/eth-tester) - 테스팅 이더리움 어플리케이션들을 위한 도구 세트(Tool suite) 입니다.
* [클리끄베이트(Cliquebait)](https://github.com/f-o-a-m/cliquebait) - 실제 블록체인 네트워크와 유사한 도커(docker) 인스턴스를 사용해 스마트 컨트렉트 어플리케이션을 통합(integration)하고 테스팅을 합니다.
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - hevm 프로젝트는 단위 테스팅과 스마트 컨트렉트 디버깅을 위해 특별히 만들어진 이더리움 가상 머신(EVM) 구현체 입니다.
* [이더리움 그래프 디버거(Ethereum graph debugger)](https://github.com/fergarrui/ethereum-graph-debugger) - 솔리디티 그래픽적인 디버거 입니다.
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - 사람이 읽을 수 있는 스택 트레이스(stack traces)와 함께 개발속도를 빠르게 합니다.
* [솔힌트(Solhint)](https://github.com/protofire/solhint) - 보안을 제공하는 솔리디티 린터, 스타일 가이드와 스마트 컨트렉트 인증을 위한 모범 사례 규칙이 있습니다.
* [Ethlint](https://github.com/duaraghav8/Ethlint) - 솔리디티 보안 이슈 & 식별과 스타일 수정을 린터(Linter)로 합니다. 예전의 솔리움(Solium) 입니다.
* [디코드(Decode)](https://github.com/dteiml/decode) - 읽을 수 있고 쉽게 이해할 수 있도록 로컬 testrpc 노드에서 제출된 거래를 분석하는 npm 패키지 입니다.
* [트러플어설션(truffle-assertions)](https://github.com/rkalis/truffle-assertions) - 트러플의 솔리디티 스마트컨트렉트 테스팅에 사용되는 유틸리티와 추가적인 어설션(assertions) npm 패키지 입니다. 가장 중요한 부분은 특정 이벤트가 발생했는지(안했는지)를 확인하는 기능이 추가 되었습니다.
* [Psol](https://github.com/Lamarkaz/psol) - 매크로와 조건부 컴파일(conditional compilation), 자동 원격 종속성 포함, mustache.js형식 문법을 이용한 솔리디티 어휘 처리기 입니다.
* [solpp](https://github.com/merklejerk/solpp) - 포괄적인 지시문 및 표현식 언어, 복잡한() 수학 및 많이 유용한 도우미 기능을 제공하는 솔리디티 전처리기(preprocessor)와 플랫테너(flattener)입니다.
* [Decode and Publish](https://flightwallet.org/decode-eth-tx/) – 가공되지 않은 이더리움 트랜젝션을 복호(decode)하고 퍼블리시 합니다. https://live.blockcypher.com/btc-testnet/decodetx/ 와 유사합니다.
* [Doppelgänger](https://getdoppelganger.io/) - 유닛 테스팅 동안에 제작 중인(mocking) 스마트 컨트렉트 종속성(dependencies)을 위한 라이브러리 입니다.
* [rocketh](https://github.com/wighawag/rocketh) - 선택 가능한 테스트 실행기(test runner)와 web3 라이브러리를 허용하는 이더리움 스마트 컨트렉트 테스트를 위한 간단한 라이브러리 입니다.
<a name="보안도구"></a>
### 보안 도구
* [MythX](https://mythx.io/) - 보안 인증 플랫폼과 이더리움 개발자를 위한 환경 도구들 입니다.
* [마이스릴 클래식(Mythril Classic)](https://github.com/ConsenSys/mythril-classic) - 오픈소스 이더리움 가상머신 바이트코드 보안 분석 도구 입니다.
* [오옌테(Oyente)](https://github.com/melonproject/oyente) - 정적 스마트 컨트렉트 보안 분석 대안 입니다.
* [시큐리파이(Securify)](https://securify.chainsecurity.com/) - 이더리움 스마트 컨트렉트를 위한 보안 스캐너 입니다.
* [스마트체크(SmartCheck)](https://tool.smartdec.net/) - 고정(Static) 스마트 컨트렉트 보안 분석기 입니다.
* [포로시티(Porosity)](https://github.com/comaeio/porosity) - 블록체인을 기반으로 한 이더리움 스마트 컨트렉트를 위한 디컴파일러(Decompiler)와 보안 분석 도구 입니다.
* [이더스프레이(Ethersplay)](https://github.com/trailofbits/ethersplay) - EVM 역어셈블러(disassembler) 입니다.
* [Evmdis](https://github.com/Arachnid/evmdis) - EVM 역어셈블러 대안 입니다.
* [하이드라(Hydra)](https://github.com/IC3Hydra/Hydra) - 암호화폐경제학(cryptoeconomic) 컨트렉트 보안, 탈중앙화 보안 바운티를 위한 프레임워크 입니다.
* [솔그래프(Solgraph)](https://github.com/raineorshine/solgraph) - 스마트 컨트렉트 보안분석을 위해 시각적인 솔리디티 제어 흐름을 보여줍니다.
* [만티코어(Manticore)](https://github.com/trailofbits/manticore) - 스마트 컨트렉트와 바이너리(Binaries)의 심볼릭 실행 도구 입니다.
* [Slither](https://github.com/trailofbits/slither) - 솔리디티 정적(static) 분석 프레임워크 입니다.
* [Adelaide](https://github.com/sec-bit/adelaide) - 솔리디티 컴파일러를 위한 SECBIT 정적(static) 분석 익스텐션(extension) 입니다.
* [솔리디티 보안 블로그(Solidity security blog)](https://github.com/sigp/solidity-security-blog) - 알려진 공격 백터(vectors)와 일반적인 안티패턴(anti-patterns) 종합 리스트 입니다.
* [어썸 버기 ERC20 토큰(Awesome Buggy ERC20 Tokens)](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - 토큰에 영향을 주는 ERC20 스마트 컨트렉트의 취약성 모음 입니다.
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Callisto 네트워크의 무료 스마트 컨트렉브 보안 감사(audits) 입니다.
* [Kontrol](https://github.com/runtimeverification/kontrol) - Foundry 속성 테스트를 통한 Solidity 스마트 계약의 형식 검증.
<a name="모니터링"></a>
### 모니터링
* [노이펀드(Neufund) - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - 스마트 컨트렉트와 거래의 수를 모니터하는 도구 입니다.
* [Scout](https://scout.cool/) - 이더리움 안에서 당신의 스마트 컨트렉트의 이벤트 로그와 활동을 바로(live) 데이터 피드(data feed) 합니다.
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - 구체적인 함수 호출 거래를 검색할 수 있고 컨트렉트 작동 방법을 확인할 수 있습니다. 디코드 된 거래 데이터가 포함된 스마트 컨트렉트를 탐색할 수 있습니다.
<a name="그밖에다양한도구"></a>
### 그 밖에 다양한 도구
* [트러플 박스(Truffle boxes)](https://truffleframework.com/boxes/) - 탈중앙화 어플리케이션을 빠르게 만들기 위한 패키지 컴포넌트 입니다.
   * [쳬셔(Cheshire)](https://github.com/endless-nameless-inc/cheshire) - 크립토키티(CryptoKitties) API와 스마트 컨트렉트의 로컬 샌드박스 도구이며, 트러플 박스로 이용 가능합니다.
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - 솔리디티 컴파일러 입니다.
* [솔컴파일러(Sol-compiler)](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-compiler) - 프로젝트 단계의 솔리디티 컴파일러 입니다.
* [Solidity cli](https://github.com/pubkey/solidity-cli) - 솔리디티 코드를 빠르고 쉽고, 더 믿을 수 있게 컴파일 합니다.
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - 솔리디티 프로젝트와 단층 파일(flat file) 유틸리티를 합쳐줍니다. 이더스캔(Etherscan)에서 컨트렉트 인증하거나 임포트(imported) 된 컨트렉트 시각화에 유용합니다.
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - 대안이며, 솔리디티 컨트렉트를 위한 개별 파일을 가져와 병합(merges) 합니다.
* [RLP](https://github.com/ethereumjs/rlp) - 자바스크립트의 RLP(Recursive Length Prefix) 인코딩 입니다.
* [eth-cli](https://github.com/protofire/eth-cli) - 이더리움 학습과 개발을 도와주는 CLI 도구 모음집 입니다.
* [이더리얼(Ethereal)](https://github.com/wealdtech/ethereal) - 이더리얼은 이더리움에서 일반 작업 관리를 위한 커멘드 라인 도구 입니다.
* [Eth crypto](https://github.com/pubkey/eth-crypto) - web3js와 솔리디티를 사용하는 튜토리얼과 이더리움을 위한 암호적(Cryptographic) 자바스크립트 함수 입니다.
* [패리티 싸이너(Parity Signer)](https://github.com/paritytech/parity-signer) - 서명(signing) 거래를 모바일 어플리케이션으로 가능하게 합니다.
* [py-eth](http://www.py-eth.com) - 이더리움 생태계를 위한 파이썬 도구들 모음 입니다.
* [truffle-flattener](https://github.com/alcuadrado/truffle-flattener) - 트러플에서 개발 중인 솔리디티 파일의 의존성(dependencies)을 연결(concats)해 줍니다.
* [디코드(Decode)](https://github.com/dteiml/decode) - 읽을 수 있고 쉽게 이해할 수 있도록 로컬 testrpc 노드에서 제출된 거래를 분석하는 npm 패키지 입니다.
* [타입체인(TypeChain)](https://github.com/ethereum-ts/TypeChain) - 이더리움 스마트 컨트렉트를 위한 타입스크립트 바인딩(bindings) 입니다.
* [EthSum](https://ethsum.netlify.com) - 간단하게 이더리움 주소를 검사합(Checksum)하는 도구 입니다.
* [PHP를 기반 블록체인 인덱서(PHP based Blockchain indexer)](https://github.com/digitaldonkey/ethereum-php-eventlistener) - PHP에서 이벤트 리스닝 또는 블록 인덱싱 해 줍니다.
* [Purser](https://github.com/JoinColony/purser) - 이더리움 기반 지갑을 위한 자바스크립트 통합 지갑 도구입니다. 소프트웨어, 하드웨어, 메타마스크를 지원합니다. 탈중앙화 어플리케이션 개발을 위해 모든 지갑을 일관되고 예측 가능한 인터페이스로 가져옵니다.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - node.js로 부터 메타마스크를 연결 합니다.
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - 솔리디티 프로젝트를 위한 문서 생성기 입니다.
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - 이더리움 블록체인 데이터를 CSV 또는 JSON 파일로 내보냅니다.
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - 정형화 된 솔리디티 코드를 위한 Prettier 플러그인 입니다.
* [EthToolbox](https://eth-toolbox.com) - 이더리움 개발자를 위해 오프체인 도구가 있는 웹앱입니다. EC recovery, address formatter, unit converter, hash functions, keys generator 등의 기능이 있습니다.
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - 이더리움과 유니티 통합(integration) 데모 입니다.
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - 이더리움과 유니티 통합(integration) 데모/샘플 입니다.
* [Wonka](https://github.com/Nethereum/Wonka) - 니더리움(Nethereum) 비즈니스 방식 엔진 데모/샘플 입니다.
<a name="스마트컨트렉트표준&라이브러리"></a>
### 스마트 컨트렉트 표준 & 라이브러리
<a name="ERCs-이더리움주석요청저장소"></a>
#### [ERCs](https://eips.ethereum.org/erc) - 이더리움 주석 요청(Ethereum Request for Comment) 저장소
* 토큰들
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - 대체 가능 자산(fungible assets)의 토큰 컨트렉트 입니다.
  * [ERC-721](https://github.com/ethereum/eips/issues/721) - 대체 불가 자산(non-fungible assets) 토큰 기준 입니다.
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - 채굴 가능한(Mineable) 토큰 기준 입니다.
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - 스마트 컨트렉트 도구 인터페이스 확인(detect)과 발행(publish)를 표준 방법으로 생성 합니다.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - 키 관리와 실행, 블록체인 아이덴티 구축을 위한 프록시 컨트렉트 입니다.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - 컨트렉트의 소유권(ownership)을 위한 표준 인터페이스 입니다.
<a name="인기있는스마트컨트렉트라이브러리"></a>
#### 인기있는 스마트 컨트렉트 라이브러리
* [제플린(Zeppelin)](https://github.com/OpenZeppelin/openzeppelin-solidity) - 스마트 컨트렉트 향상을 위한 제플린OS [라이브러리](https://github.com/zeppelinos/zos) 와 [세이프매스(SafeMath)](https://openzeppelin.org/api/docs/math_SafeMath.html)와 같이 테스트 된 재사용가능 스마트 컨트렉트들이 포함되어 있습니다.
* [크립토핀 솔리디티(cryptofin-solidity)](https://github.com/cryptofinlabs/cryptofin-solidity) - 이더리움에서 가스 효율이 좋은 스마트 컨트렉트와 보안 구축을 위한 솔리디티 라이브러리 모음 입니다.
* [모듈러 라이브러리(Modular Libraries)](https://github.com/Modular-Network/ethereum-libraries) - 이더리움 가상 머신을 활용하는 블록체인 사용을 위한 개발 패키지 그룹 입니다.
* [데이트타임 라이브러리(DateTime Library)](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - 가스 효율이 좋은 솔리디티 일시(date and time) 라이브러리 입니다.
* [아라곤(Aragon)](https://github.com/aragon/aragon) - DAO 프로토콜 입니다. upgradeability와 거버넌스에 집중한 [아라곤OS 스마트 컨트렉트 프레임워크](https://github.com/aragon/aragonOS)도 포함 되었습니다.
* [ARC](https://github.com/daostack/arc) - 다오(DAOs)를 위한 운영시스템이며 다오 스택(DAO stack)의 기초 계층(base layer) 입니다.
* [0x](https://github.com/0xProject) - DEX 프로토콜 입니다.
* [프루프 토큰 라이브러리(Token Libraries with Proofs)](https://github.com/sec-bit/tokenlibs-with-proofs) - 주어진 사양(specifications)과 고차원 속성(high-level properties)에 관해 토큰 컨트렉트의 정확성(correctness) 증명을 포함합니다.
<a name="2번째계층구조를위한개발자가이드"></a>
### 2번째 계층 구조(Infrastructure)를 위한 개발자 가이드
<a name="확장성"></a>
#### 확장성(Scalability)
<a name="결제/상태채널"></a>
#### 결제/상태 채널(Payment/State Channels)
* [이더리움 결제 채널](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - 50 줄 코드의 이더리움 결제 채널 입니다.
* [뮤라이덴 문서(µRaiden Documentation)](https://microraiden.readthedocs.io) - 뮤라이덴 발신자/수신자 유스케이스(Use Cases)를 위한 샘플과 가이드 입니다.
<a name="플라즈마"></a>
#### 플라즈마(Plasma)
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - 코넬 대학교(Cornell University)에서 시작한 2018 IC3-Ethereum Crypto Boot Camp의 노드 어플리케이션 웹사이트로, 다양한(MVP/Cash/Debit) 플라즈마를 모두 포함합니다.
* [플라즈마 MVP](https://github.com/omisego/plasma-mvp) - 오미세고(OmiseGO)의 최소 실행 가능한 플라즈마의 연구 구현물 입니다.
* [플라즈마 MVP 고랭(Golang)](https://github.com/kyokan/plasma) - 최소 실행 가능한 플라즈마 규격 확장과 고랭 구현물 입니다.
* [플라즈마 캐시(Cash)](https://github.com/omisego/plasma-cash) - 간단한 플라즈마 캐시 구현물 입니다.
<a name="사이드체인"></a>
#### 사이드체인
* [POA Network](https://poa.net/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
* [룸 네트워크(Loom Network)](https://github.com/loomnetwork)
<a name="프라이버시"></a>
#### 프라이버시 / 비밀보
<a name="zksnarks"></a>
##### zkSNARKs
* [ZoKrates](https://github.com/Zokrates/ZoKrates) - 이더리움에서 zkSNARKS을 위한 툴박스 입니다.
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - 이더리움 네트워크 안에서 비밀 거래와 이더리움 메인넷에서 구현을 실시간으로 합니다.
<a name="ui"></a>
#### UI 컴포넌트 사전빌드
* [ui.aragon.org](https://ui.aragon.org) - Dapp 컴포넌트를 포함하는 리액트(React) 라이브러리 입니다.
* [components.bounties.network](https://components.bounties.network) - Dapp 컴포넌트를 포함하는 리액트(React) 라이브러리 입니다.
* [lorikeet.design](https://lorikeet.design) - Dapp 컴포넌트를 포함하는 리액트(React) 라이브러리 입니다.
* [ui.decentraland.org](https://github.com/decentraland/ui) - Dapp 컴포넌트를 포함하는 리액트(React) 라이브러리 입니다.
* [dapparatus](https://github.com/austintgriffith/dapparatus) - 재사용가능한 리액트 Dapp 컴포넌트 입니다.
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - 메타마스크 리액트 컴포넌트 입니다.
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - 웹을 기반으로 한 분산화 어플리케이션을 위한 하이브리드 호스팅 방식의 플랫폼 입니다.
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - 크로스 플랫폼 데스크탑 지갑 샘플입니다.
