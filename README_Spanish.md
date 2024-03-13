 
# Lista de herramientas para desarrollador de Ethereum
 
Una guía de herramientas, componentes, patrones y plataformas disponibles para desarrollar aplicaciones en Ethereum.
 
La creación de esta lista fue impulsada por los gerentes de productos de ConsenSys que vieron la necesidad de compartir mejor las herramientas, patrones de desarrollo y componentes entre los desarrolladores de blockchain nuevos y experimentados.
 
Este recurso está destinado a centrarse en herramientas para desarrolladores, pero el repositorio también incluye:
- [Recursos del Ecosistema de Ethereum](EcosystemResources_Spanish.md) para DApps útiles, recursos educativos, billeteras y servicios.
 
## ¡Las contribuciones son bienvenidas!
 
Siéntase libre de enviar un pull request, con cualquier cosa, desde pequeñas correcciones hasta herramientas que le gustaría agregar (¡o eliminar!). Si agrega una nueva herramienta, **agregue una breve descripción** que crea que los nuevos desarrolladores entenderán.
 
Muchas gracias a los ~100 contribuidores, incluidos [@corbpage](https://twitter.com/corbpage) y [@pakaplace](https://twitter.com/Parker_Place) de [Meridio](https://www.meridio.co/) para la curar los datos y @jpantunes por reestructurar la lista de manera más lógica.
* Proyectos que no tengan un producto funcional, no serán agregados.
* Proyectos que estén descontinuados o no sean mantenidos, serán removidos.
* Proyectos que sean servicios de pago y/o restringidos, sin código libre o revisiones de desarrolladores, serán examinados más a fondo.
 
¿Es justo lo anterior? Comparta su opinión aquí - https://github.com/ConsenSys/ethereum-developer-tools-list/pull/70
 
## Tabla de contenido
- [Lista de herramientas para desarrollador de Ethereum](#Lista-de-herramientas-para-desarrollador-de-Ethereum)
 - [¡Las contribuciones son bienvenidas!](#¡Las-contribuciones-son-bienvenidas!)
 - [Tabla de contenido](#tabla-de-contenido)
 - [Nuevos desarrollador: comenzar aquí](#Nuevos-desarrollador:-comenzar-aquí)
 - [Herramientas para desarrollador](#Herramientas-para-desarrollador)
   - [Desarrollando Contratos Inteligentes](#Desarrollando-contratos-inteligentes)
     - [Lenguajes de Contratos Inteligentes](#Lenguajes-de-Contratos-Inteligentes)
     - [Frameworks](#frameworks)
     - [Entornos de Desarrollo Integrado (IDE)](#Entornos-de-Desarrollo-Integrado-(IDE))
   - [Otras Herramientas](#Otras-Herramientas)
   - [Prueba Redes de Cadenas de Bloques (Blockchain)](#Prueba-redes-de-cadenas-de-bloques-(blockchain))
     - [Prueba Grifos (Faucets) de Ether](#Prueba-Grifos-(Faucets)-de-Ether)
   - [Comunicación con Ethereum](#Comunicación-con-Ethereum)
     - [APIs de Ethereum para el Frontend](#APIs-de-Ethereum-para-el-Frontend)
     - [APIs de Ethereum para el Backend](#APIs-de-Ethereum-para-el-Backend)
     - [Herramientas Listas para Usar](#Herramientas-Listas-para-Usar)
     - [Herramientas ABI (interfaz binaria de aplicación) para Ethereum](#Herramientas-ABI-interfaz-binaria-de-aplicación-para-Ethereum)
     - [Patrones y Mejores Prácticas](#Patrones-y-Mejores-Prácticas)
       - [Patrones para el Desarrollo de Contratos Inteligentes](#Patrones-para-el-Desarrollo-de-Contratos-Inteligentes)
       - [Mejorabilidad](#Mejorabilidad)
   - [Infraestructura](#Infraestructura)
     - [Clientes de Ethereum](#Clientes-de-Ethereum)
     - [Almacenamiento](#Almacenamiento)
     - [Mensajería](#Mensajería)
   - [Herramientas para Pruebas](#Herramientas-para-Pruebas)
   - [Herramientas de Seguridad](#Herramientas-de-Seguridad)
   - [Monitoreo](#Monitoreo)
   - [Otras Herramientas misceláneas](#Otras-Herramientas-misceláneas)
   - [Estándares de Contratos Inteligentes y Librerías](#Estándares-de-Contratos-Inteligentes-y-Librerías)
     - [ERCs - La solicitud de Ethereum para un Repositorio de Comentario](#ercs---La-solicitud-de-Ethereum-para-un-Repositorio-de-Comentario)
     - [Librerías populares para Contratos Inteligentes](#Librerías-populares-para-Contratos-Inteligentes)
   - [Guías de Desarrollador para Infraestructura de 2da Capa](#Guías-de-Desarrollador-para-Infraestructura-de-2da-Capa)
     - [Escalabilidad](#Escalabilidad)
     - [Canales de Pago/Estado](#Canales-de-Pago/Estado)
     - [Plasma](#plasma)
     - [Cadenas Laterales](#Cadenas-Laterales)
     - [Privacidad / confidencialidad](#Privacidad--confidencialidad)
       - [ZK-SNARKs](#zk-snarks)
     - [Escalabilidad + Privacidad](#Escalabilidad--Privacidad)
     - [ZK-STARKs](#zk-starks)
     - [Componentes de UI pre-construidos](#Componentes-de-UI-pre-construidos)
 
## Nuevos desarrollador: comenzar aquí
* [Solidity](https://soliditylang.org/) - el lenguaje de contratos inteligentes más popular.
* [Metamask](https://metamask.io/) - Extensión de Chrome para tener una billetera e interactuar con Dapps.
* [Truffle](https://trufflesuite.com/) - el framework de implementación, prueba y desarrollo de contratos inteligentes más popular. Instale el cli a través de npm y comience aquí para escribir sus primeros contratos inteligentes.
* [Truffle boxes](https://trufflesuite.com/boxes) - componentes empaquetados para el ecosistema Ethereum.
* [Hardhat](https://hardhat.org/) - Entorno de desarrollo flexible, extensible y rápido, para Ethereum.
* [Cryptotux](https://cryptotux.org/) - Una imagen de Linux lista para ser importada en VirtualBox que incluye las herramientas de desarrollo mencionadas anteriormente.
* [Kit de Inicio de OpenZeppelin](https://openzeppelin.com/starter-kits/) - Una caja de inicio todo en uno para que los desarrolladores pongan en marcha sus aplicaciones respaldadas por contratos inteligentes. Incluye Truffle, OpenZeppelin SDK, el paquete EVM OpenZeppelin/contract-ethereum-package de contrato inteligente auditado, una aplicación de React y Rimble para estilizar facilmente.
* [EthHub.io](https://docs.ethhub.io/) - Descripción crowdsourced general de Ethereum- su historia, gobernanza, planes a futuros y recursos de desarrollo.
* [EthereumDev.io](https://ethereumdev.io) - la guía definitiva para comenzar con la programación de contratos inteligentes de Ethereum.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie es un framework de Python para implementar, probar e interactuar con contratos inteligentes de Ethereum.
* [Ethereum Stack Exchange](https://ethereum.stackexchange.com/) - publique y busque preguntas para ayudar a su ciclo de vida de desarrollo.
* [dfuse](https://dfuse.io) - Eficiente blockchain API para crear aplicaciones de clase mundial.
* [Biconomy](https://biconomy.io) - realice transacciones sin gas en su dapp habilitando meta-transacciones utilizando un SDK fácil de usar.
* [Blocknative](https://blocknative.com) - eventos de Blockchain antes de que sucedan. El portafolio de desarrolladores de Blocknative facilita la creación con datos mempool.
 
## Herramientas para desarrollador
### Desarrollando Contratos Inteligentes
#### Lenguajes de Contratos Inteligentes
* [Solidity](https://docs.soliditylang.org/en/latest/) - Lenguaje de Contratos Inteligentes de Ethereum.
* [Vyper](https://vyper.readthedocs.io/en/latest/) - Nuevo lenguaje de programación pitónico.
 
#### Frameworks
* [Truffle](https://trufflesuite.com/) - el framework de implementación, prueba y desarrollo de contratos inteligentes más popular. La suite Truffle incluye Truffle, [Ganache](https://github.com/trufflesuite/ganache) y [Drizzle](https://github.com/truffle-box/drizzle-box). [Profundización en Truffle aquí](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9).
* [Hardhat](https://hardhat.org/) - Entorno de desarrollo flexible, extensible y rápido, para Ethereum.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie es un framework de Python para implementar, probar e interactuar con contratos inteligentes de Ethereum.
* [Embark](https://github.com/embark-framework/embark) - Framework para el desarrollo de DApp.
* [Waffle](https://getwaffle.io/) - Framework para pruebas y desarrollo de contratos inteligentes avanzados, pequeño, flexible, rápido (basado en ethers.js).
* [Dapp](https://dapp.tools/dapp/) - Framework para el desarrollo de DApp, sucesor de DApple.
* [Etherlime](https://github.com/LimeChain/etherlime) - Framework basado en ethers.js para la implementación de Dapp.
* [Parasol](https://github.com/Lamarkaz/parasol) - Entorno ágil de desarrollo de contratos inteligentes con pruebas, implementación con INFURA, documentación automática de contratos y más. Cuenta con un diseño flexible y no dogmático con personalización ilimitada.
* [0xcert](https://github.com/0xcert/framework/) - Framework de JavaScript para crear aplicaciones descentralizadas.
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - OpenZeppelin SDK: un conjunto de herramientas para ayudarlo a desarrollar, compilar, actualizar, implementar e interactuar con contratos inteligentes.
* [sbt-ethereum](https://sbt-ethereum.io/) - Una consola tab-completa, basada en texto,  para la interacción y el desarrollo de contratos inteligentes, que incluye administración de billetera y ABI, soporte de ENS e integración avanzada de Scala.
* [Cobra](https://github.com/cobraframework/cobra) - Un framework de entorno de desarrollo rápido, flexible y simple para el contrato inteligente de Ethereum, pruebas y implementación en la máquina virtual de Ethereum (EVM).
* [Epirus](https://docs.epirus.io/sdk/) - Framework de Java para la creación de contratos inteligentes.
 
#### Entornos de Desarrollo Integrado (IDE)
* [Remix](https://remix.ethereum.org/) - Web IDE con análisis estático y pruebas de blockchain VM, integradas.
* [Ethereum Studio](https://studio.ethereum.org/) - Web IDE. Viene integrado con un navegador de blockchain VM, Metamask (un solo clic para implementación a Testnet/Mainnet), registrador de transacciones y programe su aplicación en vivo, dentro de muchas otras características.
* [Atom](https://atom.io/) - Editor de Atom con [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom), [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), y paquetes [language-solidity](https://atom.io/packages/language-solidity).
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Archivo sintáctico de Vim para Solidity.
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Extensión de Visual Studio Code que agrega soporte para Solidity.
* [Ethcode](https://marketplace.visualstudio.com/items?itemName=quantanetwork.ethcode) - Extensión de Visual Studio Code que compila, ejecuta y depura programas de Solidity y Vyper.
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - Complemento de código libre para [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/) (gratis/comercial) con resaltado de sintaxis, formatización, completación de código, etc.
* [Herramientas de Solidity de YAKINDU](https://github.com/Yakindu/solidity-ide) - IDE basada en Eclipse. Contiene completación de código y ayuda sensible al contexto, navegación por el código, coloreado de la sintaxis (código), construir en el compilador, arreglos rápidos y plantillas.
* [Eth Fiddle](https://ethfiddle.com/) - IDE desarrollada por [La Red Loom](https://loomx.io/) que te permite escribir, compilar y depurar tus contratos inteligentes. Fácil de compartir y encontrar fragmentos de código.
 
### Otras Herramientas
* [Serviceios de Blockchain de Atra](https://console.atra.io) - Atra provee servicios web para ayudarle a construir, implementar y mantener, aplicaciones descentralizadas en la blockchain de Ethereum.
* [Kit Blockchain de Desarrollador de Azure para VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain) - Extensión de VSCode que permite crear contratos inteligentes y implementarlos dentro de Visual Studio Code.
 
### Prueba Redes de Cadenas de Bloques (Blockchain)
* [ethnode](https://github.com/vrde/ethnode) - Ejecuta un nodo de Ethereum (Geth or Parity) para desarrollo, tan facil como `npm i -g ethnode && ethnode`.
* [Ganache](https://github.com/trufflesuite/ganache) - aplicación para probar el blockchain de Ethereum con UI visual y registros.
* [Kaleido](https://kaleido.io/) - Utliza Kaleido para poner en marcha una red de consorcio blockchain. Estupendo para Prueba de Conceptos (PoCs) y pruebas generales.
* [Red Privada Besu](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - Ejecute una red privada de nodos de Besu dentro de contenedores Docker.
* [Orion](https://github.com/PegaSysEng/orion) - Componente para realizar transacciones privadas por PegaSys.
* [Artemis](https://github.com/PegaSysEng/artemis) - Implementación Java de la cadena Ethereum 2.0 Beacon de PegaSys.
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifica la integración y la aceptación de pruebas de aplicaciones de contrato inteligente con instancias de Docker que se asemeja mucho a una red blockchain real.
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Ejecute una red local de Raiden en contenedores Docker con fines de demostración y prueba.
* [Scripts de Implementación de Redes Privadas](https://github.com/ConsenSys/private-networks-deployment-scripts) - Scripts de implementación listos para usar para redes de PoA privadas.
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Scripts de implementación listos para usar para redes privadas de PoW.
* [Ethereum en Azure](https://docs.microsoft.com/en-us/azure/blockchain/templates/ethereum-poa-deployment) - Implementación y gobernanza de las redes de PoA de Ethereum del consorcio.
* [Ethereum en Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - Cree una red Ethereum basada en Prueba de Trabajo (PoW).
* [Infura](https://infura.io/) - Acceso de la API de Ethereum a las redes de Ethereum (Mainnet, Ropsten, Rinkeby, Goerli, Kovan).
* [Puerta de Enlace Web Distribuida de CloudFlare](https://cloudflare.com/distributed-web-gateway/) - Proporciona acceso a la red Ethereum a través de Cloudflare en lugar de ejecutar su propio nodo.
* [Chainstack](https://chainstack.com/) - Nodos de Ethereum compartidos y dedicados como servicio (Mainnet, Ropsten).
* [Alchemy](https://alchemyapi.io/) - Plataforma de Blockchain para desarrolladores, API de Ethereum y servicio de nodo (Mainnet, Ropsten, Rinkeby, Goerli, Kovan).
* [ZMOK](https://zmok.io/) - API JSON-RPC de Ethereum (Mainnet, Rinkeby, Mainnet de ejecución frontal).
 
#### Prueba Grifos (Faucets) de Ether
* [Grifo Rinkeby](https://faucet.rinkeby.io/)
* [Grifo Kovan](https://github.com/kovan-testnet/faucet)
* [Grifo Ropsten (MetaMask)](https://faucet.metamask.io/)
* [Grifo Ropsten (rpanic)](https://faucet.rpanic.com)
* [Grifo Goerli](https://goerli-faucet.slock.it/)
* [Grifo Holesky](https://stakely.io/en/faucet/ethereum-holesky-testnet-eth)
* [Grifo Universal](https://faucets.blockxlabs.com/)
* [Nethereum.Faucet](https://github.com/Nethereum/Nethereum.Faucet) - A C#/.NET faucet
 
### Comunicación con Ethereum
#### APIs de Ethereum para el Frontend
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3.
* [Eth.js](https://github.com/ethjs) - Alternativa Javascript Web3.
* [Ethers.js](https://github.com/ethers-io/ethers.js/) - Alternativa a Javascript Web3, utilidades útiles y funciones de billetera.
* [light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js) Una biblioteca JS reactiva de alto nivel optimizada para clientes ligeros.
* [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper) - Alternativa a Typescript Web3.
* [Ethereumjs](https://github.com/ethereumjs/) - Una colección de funciones de utilidad para Ethereum como [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) y [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx).
* [Alchemy-web3.js](https://github.com/alchemyplatform/alchemy-web3) - Contenedor Javascript Web3 con reintentos automáticos, acceso a [APIs mejoradas de Alchemy](https://docs.alchemyapi.io/documentation/alchemy-web3/enhanced-web3-api), y conexiones robustas a websockets.
* [flex-contract](https://github.com/merklejerk/flex-contract) y [flex-ether](https://github.com/merklejerk/flex-ether) - Moderno, configuración cero, alto -bibliotecas de nivel para interactuar con contratos inteligentes y realizar transacciones.
* [ez-ens](https://github.com/merklejerk/ez-ens) - Resolución de direcciones de Ethereum Name Service simple y sin configuración.
* [web3x](https://github.com/xf00f/web3x) - Un puerto de TypeScript a web3.js. Los beneficios incluyen construcciones pequeñas y seguridad completa, incluso al interactuar con contratos.
* [Nethereum](https://github.com/Nethereum/) - Framework de desarrollo multiplataforma de Ethereum.
* [dfuse](https://github.com/dfuse-io/client-js) - Una librería de TypeScript para usar [dfuse Ethereum API](https://dfuse.io).
* [Drizzle](https://github.com/truffle-box/drizzle-box) - Librería de Redux para conectarse al frontend de una blockchain.
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) - Un SDK de JavaScript para hacer dapps de Ethereum móviles nativas usando React Native.
* [useMetamask](https://github.com/mdtanrikulu/use-metamask) - Un React Hook personalizado para administrar Metamask en proyectos Ethereum ĐApp.
* [WalletConnect](https://walletconnect.org/) - Protocolo abierto para conectar billeteras a Dapps.
* [Subproviders](https://0x.org/docs/tools/subproviders) - Varios subproveedores útiles para usar junto con [Web3-provider-engine](https://github.com/MetaMask/web3-provider-engine) (incluyendo un LedgerSubprovider para agregar soporte a la billetera de hardware Ledger, a su dApp).
* [ethvtx](https://github.com/ticket721/ethvtx) - configuración almacenada de Redox lista para Ethereum y framework-agnóstica. [docs](https://ticket721.github.io/ethvtx/)
* Strictly Typed - Alternativas a Javascript
   * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
   * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
* [ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer) - Comuníquese con diferentes blockchains (incluido Ethereum) utilizando una sola interfaz.
* [Delphereum](https://github.com/svanas/delphereum) - una interfaz Delphi a la blockchain de Ethereum que permite el desarrollo de Dapps nativas para Windows, macOS, iOS y Android.
* [Torus](https://tor.us/) - SDK de código abierto para crear Dapps con una experiencia de usuario integrada perfecta.
* [Fortmatic](https://fortmatic.com/) - Un SDK fácil de usar para crear dApps web3 sin extensiones ni descargas.
* [Portis](https://portis.io/) - Una billetera no custodiada con un SDK que permite una fácil interacción con DApps sin instalar nada.
* [create-eth-app](https://github.com/paulrberg/create-eth-app) - Cree aplicaciones front-end impulsadas por Ethereum con un solo comando.
* [Scaffold-ETH](https://github.com/austintgriffith/scaffold-eth) - Github forkeable, apto para principiantes para comenzar a construir contratos inteligentes.
* [Notify.js](https://blocknative.com/notify) - Entregue notificaciones en tiempo real a sus usuarios. Con soporte integrado para aceleraciones y cancelaciones, Blocknative Notify.js ayuda a los usuarios a realizar transacciones con confianza. Notify.js es fácil de integrar y rápido de personalizar.
 
#### APIs de Ethereum para el Backend
* [Web3.py](https://github.com/ethereum/web3.py) - Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [ethers-kt](https://github.com/Kr1ptal/ethers-kt) - Biblioteca Kotlin asíncrona de alto rendimiento para interactuar con blockchains basadas en EVM. Orientada a plataformas JVM y Android.
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [rust-web3](https://github.com/tomusdrw/rust-web3) - Rust Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/komputing/KEthereum) - Kotlin Web3
* [web3dart](https://github.com/xclud/web3dart) - Dart Web3
* [Eventeum](https://github.com/ConsenSys/eventeum) - Un puente entre los eventos de contratos inteligentes de Ethereum y los microservicios del backend, escrito en Java por Kauri.
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - Cliente Elixir JSON-RPC para la blockchain de Ethereum.
* [Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway) - Una puerta de enlace que permite ejecutar varios nodos Ethereum con fines de redundancia y equilibrio de carga. Se puede ejecutar como alternativa a (o sobre) Infura. Escrito en Golang.
* [EthContract](https://github.com/AgileAlpha/eth_contract) - Un conjunto de métodos auxiliares para ayudar a consultar contratos inteligentes ETH en Elixir.
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - Un servicio MESG, para interactuar con cualquier contrato de Ethereum en función de su dirección y ABI.
* [Ethereum Service](https://github.com/mesg-foundation/service-ethereum) - Un servicio MESG, para interactuar con eventos de Ethereum e interactuar con él.
* [Marmo](https://marmo.io/) - Python, JS y Java SDK para simplificar las interacciones con Ethereum. Utiliza retransmisores para descargar los costos de transacción a los retransmisores.
* [Ethereum Logging Framework](https://bitbucket.csiro.au/users/kli039/repos/ethereum-logging-framework/browse) - proporciona capacidades de registro avanzadas para aplicaciones y redes de Ethereum, incluido un lenguaje de consulta, procesador de consultas y generación de código de registro.
 
#### Herramientas Listas para Usar
* [Truffle boxes](https://trufflesuite.com/boxes) - componentes empaquetados para el ecosistema Ethereum.
* [Create Eth App](https://github.com/paulrberg/create-eth-app) - Cree aplicaciones frontend impulsadas por Ethereum con un solo comando.
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - ejecuta una red privada de nodos Besu en un contenedor Docker.
* [Testchains](https://github.com/Nethereum/TestChains) - Devchains .NET preconfigurados para una respuesta rápida (PoA).
* [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - Explorador de cadenas de bloques Wasm (muestra funcional).
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - ejecute una red local de Raiden en contenedores Docker con fines de demostración y prueba.
* [Scripts de Implementación de Redes Privadas](https://github.com/ConsenSys/private-networks-deployment-scripts) - Scripts de implementación listos para usar para redes de PoA privadas.
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - Tutorial paso a paso para construir una cadena de prueba de PoA con 2 nodos con consenso de ronda de autoridad de paridad.
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Scripts de implementación listos para usar para redes privadas de PoW.
* [Kaleido](https://kaleido.io/) - Usa Kaleido para crear una red de blockchain de consorcio. Excelente para pruebas y PoC.
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - una implementación local de sandbox de la API de CryptoKitties y contratos inteligentes, disponible como Truffle Box.
* [aragonCLI](https://github.com/aragon/aragon-cli) - aragonCLI se utiliza para crear y desarrollar aplicaciones y organizaciones de Aragón.
* [ColonyJS](https://github.com/JoinColony/colonyJS) - cliente JavaScript que proporciona una API para interactuar con los contratos inteligentes de Colony Network.
* [ArcJS](https://github.com/daostack/arc.js) - biblioteca que facilita el acceso de la aplicación javascript a los contratos inteligentes DAOstack Arc ethereum.
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - cliente JavaScript que proporciona una API para interactuar con Arkane Network, un proveedor de billeteras para crear dapps fáciles de usar.
* [Onboard.js](https://blocknative.com/onboard) - Blocknative Onboard es la forma rápida y fácil de agregar soporte para múltiples billeteras a su proyecto. Con módulos integrados para más de 20 billeteras de hardware y software exclusivas, Onboard le ahorra tiempo y dolores de cabeza.
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - Framework de React para crear dApps Ethereum de una sola página.

#### Herramientas ABI (interfaz binaria de aplicación) para Ethereum
* [Decodificador ABI](https://github.com/ConsenSys/abi-decoder) - librería para decodificar parámetros de datos y eventos de transacciones Ethereum.
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen) - Genere envoltorios de contratos de Typecript a partir de ABI de contratos.
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Genere automáticamente definiciones de campo de formulario de interfaz de usuario y validadores asociados de un contrato de Ethereum ABI.
* [headlong](https://github.com/esaulpaugh/headlong/) - ABI de contrato con seguridad de tipos y librería de prefijos de longitud recursiva en Java.
* [EasyDapper](https://www.easydapper.com) - Genera dapps a partir de artefactos Truffle, implementa contratos en redes públicas/privadas, ofrece una página pública personalizable en vivo para interactuar con contratos.
* [One Click dApp](https://oneclickdapp.com) - cree instantáneamente una dApp en una URL única utilizando la ABI.
* [Truffle Pig](https://npmjs.com/package/trufflepig) - una herramienta de desarrollo que proporciona una API HTTP simple para buscar y leer archivos de contratos generados por Truffle, para su uso durante el desarrollo local. Sirve ABI de contrato nuevo a través de http.
* [Servicio de contrato de Ethereum](https://github.com/mesg-foundation/service-ethereum-contract) - un servicio MESG para interactuar con cualquier contrato de Ethereum en función de su dirección y ABI.
* [Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - Un generador basado en web que crea una interfaz y un servicio C # basado en Nethereum basado en contratos inteligentes de Solidity.

#### Patrones y Mejores Prácticas

##### Patrones para el Desarrollo de Contratos Inteligentes
* [Dappsys: bloques de construcción de contratos Ethereum seguros, simples y flexibles](https://github.com/dapphub/dappsys)
    * Tiene soluciones para problemas comunes en Ethereum/Solidity, por ejemplo.
        * [Lista blanca](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Token ERC20 actualizable](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Autenticación (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [... varios más ...](https://github.com/dapphub/dappsys)
    * Proporciona bloques de construcción para [MakerDAO](https://github.com/makerdao/maker-otc) o [The TAO](https://github.com/ryepdx/the-tao)
    * Debe ser consultado antes de crear soluciones propias, no probadas
    * El uso se describe en [Dapp-a-day 1-10](https://steemit.com/@nikolai) y [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [Contratos OpenZeppelin: un framework abierto de contratos inteligentes reutilizables y seguros en el lenguaje de Solidity.](Https://github.com/OpenZeppelin/openzeppelin-contracts)
    * Probablemente las librerías y los contratos inteligentes más utilizados.
    * Similar a Dappsys, más integrado en el framework Truffle.
    * [Blog sobre prácticas recomendadas con auditorías de seguridad](https://blog.openzeppelin.com/)
* [Taller avanzado con montaje](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especialmente la sección _Benefits_
* [Lista de verificación de auditoría de Solidity de CryptoFin](https://github.com/cryptofinlabs/audit-checklist) - una lista de verificación de hallazgos comunes y problemas a tener en cuenta al auditar un contrato para el lanzamiento de una red principal.
* [aragonOS: un framework de contrato inteligente para crear DAO, Dapps y protocolos](https://hack.aragon.org/docs/aragonos-intro.html)
    * Capacidad de actualización: los contratos inteligentes se pueden actualizar a una versión más reciente.
    * Control de permisos: al usar los modificadores `auth` y` authP`, puede proteger la funcionalidad para que solo otras aplicaciones o entidades puedan acceder a ella.
    * Reenviadores: las aplicaciones aragonOS pueden enviar su intención de realizar una acción a otras aplicaciones, de modo que esa intención se reenvíe si se cumplen una serie de requisitos.
* [EIP-2535 Diamond Standard](https://eips.ethereum.org/EIPS/eip-2535)
    * Organice los contratos para que compartan el mismo almacenamiento de contrato y la misma dirección de Ethereum.
    * Resuelve el límite máximo de tamaño de contrato de 24 KB.
    * Actualice los diamantes agregando/reemplazando/eliminando cualquier cantidad de funciones en una sola transacción.
    * Las actualizaciones son transparentes registrándolas con un evento estándar.
    * Obtener información sobre un diamante con eventos y/o cuatro funciones estándar.

##### Mejorabilidad
* [Blog von Elena Dimitrova, Dev en colony.io](https://blog.colony.io/author/elena/)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Blog de investigación de Aragón](https://blog.aragon.org/tag/research/)
    * [Desarrollo impulsado por librerías](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
    * [Técnicas avanzadas de implementación de código de Solidity](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelin en librerías de proxy](https://blog.openzeppelin.com/proxy-libraries-in-solidity-79fbe4b970fd/)

### Infraestructura
#### Clientes de Ethereum
* [Besu](https://besu.hyperledger.org/en/latest/) - un cliente Ethereum de código abierto desarrollado bajo la licencia Apache 2.0 y escrito en Java. El proyecto está alojado por Hyperledger.
* [Geth](https://geth.ethereum.org/docs/) - Cliente del lenguaje de Go.
* [OpenEthereum](https://github.com/openethereum/openethereum) - Cliente de Rust, anteriormente llamado Parity.
* [Aleth](https://github.com/ethereum/aleth) - cliente C ++
* [Nethermind](https://github.com/NethermindEth/nethermind) - cliente de .NET Core.
* [Infura](https://infura.io/) - un servicio administrado que proporciona API compatibles con los estándares del cliente Ethereum.
* [Trinity](https://trinity.ethereum.org/) - Cliente Python que usa [py-evm](https://github.com/ethereum/py-evm).
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - Cliente JS usando [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth es una herramienta cliente de Ethereum, como una "MetaMask para la línea de comandos".
* [Mustekala](https://github.com/musteka-la/mustekala) - Proyecto Ethereum Light Client de Metamask.
* [Exthereum](https://github.com/exthereum/blockchain) - Cliente Elixir.
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - cliente de Energy Web Foundation para la red de prueba de Tobalaba.
* [Quorum](https://github.com/jpmorganchase/quorum) - una implementación autorizada de Ethereum que respalda la privacidad de los datos por [JP Morgan](https://jpmorgan.com/quorum).
* [Mana](https://github.com/mana-ethereum/mana) - Implementación de nodo completo de Ethereum escrita en Elixir.
* [Chainstack](https://chainstack.com/) - un servicio administrado que proporciona nodos Geth compartidos y dedicados.
* [QuikNode](https://quiknode.io/) - nube para desarrolladores de Blockchain con acceso a API y nodo como servicio.


#### Almacenamiento
* [IPFS](https://ipfs.io/) - almacenamiento descentralizado y referenciación de archivos.
   * [Mahuta](https://github.com/ConsenSys/Mahuta) - Servicio de almacenamiento IPFS con capacidad de búsqueda adicional, anteriormente IPFS-Store.
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - Base de datos descentralizada sobre IPFS.
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - una librería cliente para la API HTTP de IPFS, implementada en JavaScript.
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - API fácil de usar en IPFS y otros protocolos de almacenamiento distribuidos/descentralizados.
   * [PINATA](https://pinata.cloud) - la forma más fácil de usar IPFS.
* [Swarm](https://swarm-gateways.net/) - plataforma de almacenamiento distribuido y servicio de distribución de contenido, un servicio de capa base nativo de la pila Ethereum web3.
* [Infura](https://infura.io/) - una puerta de enlace IPFS API administrada y un servicio de fijación.
* [3Box Storage](https://docs.3box.io/api/storage) - una API para almacenamiento distribuido y controlado por el usuario. Construido sobre IPFS y Orbitdb.
* [Aleph.im](https://aleph.im/) - un proyecto en la nube de igual a igual incentivado fuera de la cadena (base de datos, almacenamiento de archivos, informática y DID) compatible con Ethereum e IPFS.


#### Mensajería
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Protocolo de comunicación para que las DApps se comuniquen entre sí, un servicio de capa base nativo de la pila Ethereum web3.
* [Protocolo de cable DEVp2p](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - comunicaciones de igual a igual entre nodos que ejecutan Ethereum/Whisper.
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - implementación de Python de la capa de red RLPx.
* [3Box Threads](https://docs.3box.io/api/messaging) - API que permite a los desarrolladores implementar IPFS persistente o en la memoria de mensajes de igual a igual.

### Herramientas para Pruebas
* [Truffle Teams](https://trufflesuite.com/teams) - Integración continua Zero-Config para proyectos de truffle.
* [Cobertura de código de Solidity](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Herramienta de cobertura de código de Solidity.
* [Cobertura de Solidity](https://github.com/sc-forks/solidity-coverage) - Cobertura de código alternativo para los contratos inteligentes de Solidity.
* [Profiler de función de Solidity](https://github.com/EricR/sol-function-profiler) - Profiler de función de contrato de Solidity.
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - Generador de perfiles de contrato inteligente de Solidity alternativo y actualizado.
* [Espresso](https://github.com/hillstreetlabs/espresso) - framework de prueba de Solidity de recarga en caliente, rápido y en paralelo.
* [Eth tester](https://github.com/ethereum/eth-tester) - conjunto de herramientas para probar aplicaciones Ethereum.
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - simplifica la integración y la aceptación de pruebas de aplicaciones de contrato inteligente con instancias de Docker que se asemeja mucho a una red blockchain real.
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - el proyecto hevm es una implementación de la máquina virtual Ethereum (EVM) hecha específicamente para pruebas unitarias y depuración de contratos inteligentes.
* [Depurador de gráficos Ethereum](https://github.com/fergarrui/ethereum-graph-debugger) - Depurador gráfico de Solidity.
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - Acelera tu desarrollo con trazas de pila legibles por humanos.
* [Solhint](https://github.com/protofire/solhint) - linter de Solidity que proporciona seguridad, guía de estilo y reglas de mejores prácticas para la validación inteligente de contratos.
* [Ethlint](https://github.com/duaraghav8/Ethlint) - Linter para identificar y solucionar problemas de estilo y seguridad en Solidity, anteriormente Solium.
* [Decode](https://github.com/hacker-DOM/decode) - paquete npm que analiza las transacciones enviadas a un nodo testrpc local para hacerlos más legibles y fáciles de entender.
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - un paquete npm con afirmaciones y utilidades adicionales que se utilizan para probar los contratos inteligentes de Solidity con truffle. Lo más importante es que agrega la capacidad de afirmar si se han emitido (no) eventos específicos.
* [Psol](https://github.com/Lamarkaz/psol) - Preprocesador léxico de Solidity con sintaxis estilo mustache.js, macros, compilación condicional e inclusión automática de dependencia remota.
* [solpp](https://github.com/merklejerk/solpp) - preprocesador y acoplador de Solidity con un amplio lenguaje de directivas y expresiones, matemáticas de alta precisión y muchas funciones auxiliares útiles.
* [Decodificar y publicar](https://flightwallet.github.io/decode-eth-tx/) - Decodificar y publicar transacciones de ethereum sin formato. Similar a https://live.blockcypher.com/btc-testnet/decodetx/.
* [Doppelgänger](https://getdoppelganger.io/) - una librería para simular las dependencias de contratos inteligentes durante las pruebas unitarias.
* [rocketh](https://github.com/wighawag/rocketh) - una librería simple para probar el contrato inteligente de ethereum que permite usar cualquier lib web3 y el corredor de prueba que elija.
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - complemento de PyTest para probar contratos inteligentes para la blockchain de Ethereum.

### Herramientas de Seguridad
* [MythX](https://mythx.io/) - plataforma de verificación de seguridad y ecosistema de herramientas para desarrolladores de Ethereum.
* [Mythril](https://github.com/ConsenSys/mythril) - herramienta de análisis de seguridad de código de bytes EVM de código abierto.
* [Oyente](https://github.com/melonproject/oyente) - Análisis de seguridad de contrato inteligente estático alternativo.
* [Securify](https://securify.chainsecurity.com/) - Escáner de seguridad para contratos inteligentes de Ethereum.
* [SmartCheck](https://tool.smartdec.net/) - Analizador de seguridad de contrato inteligente estático.
* [Ethersplay](https://github.com/crytic/ethersplay) - desensamblador EVM.
* [Evmdis](https://github.com/Arachnid/evmdis) - Desensamblador EVM alternativo.
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework para la seguridad de contratos criptoeconómicos, recompensas de seguridad descentralizadas.
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualice el flujo de control de Solidity para análisis de seguridad de contratos inteligentes.
* [Manticore](https://github.com/trailofbits/manticore) - herramienta de ejecución simbólica en contratos inteligentes y binarios.
* [Slither](https://github.com/crytic/slither) - un framework de análisis estático de Solidity.
* [Adelaide](https://github.com/sec-bit/adelaide) - la extensión de análisis estático SECBIT para el compilador Solidity.
* [solc-verify](https://github.com/SRI-CSL/solidity/) - un verificador modular para contratos inteligentes Solidity.
* [Blog de seguridad de Solidity](https://github.com/sigp/solidity-security-blog) - lista completa de vectores de ataque conocidos y antipatrones comunes.
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - una colección de vulnerabilidades en contratos inteligentes ERC20 con tokens afectados.
* [Auditoría de seguridad de contrato inteligente gratuita](https://callisto.network/smart-contract-audit/) - Auditorías de seguridad de contrato inteligente gratuitas de Callisto Network.
* [Piet](https://piet.slock.it) - un analizador visual de arquitectura de Solidity.
* [Kontrol](https://github.com/runtimeverification/kontrol) - Verificación formal de contratos inteligentes Solidity mediante pruebas de propiedades de Foundry.

### Monitoreo
* [Alethio](https://aleth.io/) - una plataforma de análisis avanzada de Ethereum que proporciona monitoreo en vivo, información y detección de anomalías, métricas de tokens, auditorías de contratos inteligentes, visualización de gráficos y búsqueda de blockchain. También se puede explorar la información de mercado en tiempo real y las actividades comerciales en los intercambios descentralizados de Ethereum.
* [amberdata.io](https://amberdata.io) - proporciona monitoreo en vivo, información y detección de anomalías, métricas de token, auditorías de contratos inteligentes, visualización de gráficos y búsqueda de blockchain.
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - una herramienta para monitorear una serie de contratos y transacciones inteligentes.
* [Scout](https://scout.cool/) - una fuente de datos en vivo de las actividades y registros de eventos de sus contratos inteligentes en Ethereum.
* [Tenderly](https://tenderly.co/) - una plataforma que brinda a los usuarios monitoreo y alertas confiables de contratos inteligentes en forma de un panel web sin requerir que los usuarios alojen o mantengan la infraestructura.
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Explore contratos inteligentes con datos de transacciones decodificados, vea cómo se usa el contrato y busque transacciones con llamadas a funciones específicas.
* [BlockScout](https://github.com/poanetwork/blockscout) - una herramienta para inspeccionar y analizar cadenas de bloques basadas en EVM. El único explorador de blockchain con todas las funciones para las redes Ethereum.
* [Terminal](https://terminal.co/) - Un panel de control para monitorear dapps. La terminal se puede usar para monitorear a sus usuarios, dapp, infraestructura blockchain, transacciones y más.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - un framework extensible escrito en Golang para escuchar eventos en cadena y hacer algo en respuesta.
* [Alchemy Notify](https://docs.alchemyapi.io/guides/alchemy-notify) - notificaciones de transacciones minadas y eliminadas, cambios en el precio del gas y actividad de direcciones para las direcciones deseadas.
* [Blocknatve Mempool Explorer](https://www.blocknative.com/explorer) - supervise cualquier contrato o dirección de billetera y obtenga la transmisión de eventos de mempool para cada etapa del ciclo de vida, incluidos caídas, confirmaciones, aceleraciones, cancelaciones y más. Decodifica automáticamente las transacciones internas confirmadas. Y filtra exactamente como quieras. Reciba eventos en nuestra interfaz visual, sin código, o asócielos con su clave API para obtener eventos a través de un webhook. Mempool Explorer ayuda a los intercambios, protocolos, billeteras y comerciantes a monitorear y actuar sobre las transacciones en tiempo real.
* [Ethernal](https://www.tryethernal.com) - explorador de bloques Ethereum para cadenas privadas. Explore transacciones, decodifique llamadas a funciones, datos de eventos o valores de variables de contrato en su cadena de ejecución local.

### Otras Herramientas misceláneas
* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - un administrador de paquetes descentralizado impulsado por aragonOS y Ethereum. aragonPM permite una gobernanza descentralizada sobre las actualizaciones de paquetes, eliminando los puntos centralizados de falla.
* [Truffle boxes](https://www.trufflesuite.com/boxes) - Componentes empaquetados para construir DApps rápidamente.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - una implementación local de sandbox de la API de CryptoKitties y contratos inteligentes, disponible como Truffle Box.
* [Solc](https://docs.soliditylang.org/en/latest/using-the-compiler.html) - compilador de Solidity.
* [Sol-compiler](https://sol-compiler.com/) - compilador de Solidity a nivel de proyecto.
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile el código de Solidity más rápido, más fácil y más confiable.
* [Acoplador de Solidity](https://github.com/poanetwork/solidity-flattener) - combina el proyecto de Solidity con la utilidad de archivo plano. Útil para visualizar contratos importados o para verificar su contrato en Etherscan.
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternativa, fusiona todas las importaciones en un solo archivo para contratos de Solidity.
* [RLP](https://github.com/ethereumjs/rlp) - Codificación de prefijo de longitud recursiva en JavaScript.
* [eth-cli](https://github.com/protofire/eth-cli) - una colección de herramientas CLI para ayudar con el aprendizaje y el desarrollo de ethereum.
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal es una herramienta de línea de comandos para administrar tareas comunes en Ethereum.
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Funciones javascript criptográficas para Ethereum y tutoriales para usarlas con web3js y Solidity.
* [Firmante de paridad](https://github.com/paritytech/parity-signer) - la aplicación móvil permite firmar transacciones
* [py-eth](http://py-eth.com) - Colección de herramientas de Python para el ecosistema Ethereum.
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Concats archivos de Solidity desarrollados bajo Truffle con todas sus dependencias.
* [Decode](https://github.com/hacker-DOM/decode) - paquete npm que analiza los tx enviados a un nodo testrpc local para hacerlos más legibles y fáciles de entender.
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Enlaces de mecanografiado para contratos inteligentes de Ethereum
* [EthSum](https://ethsum.netlify.com) - Una herramienta de suma de comprobación de direcciones de Ethereum simple.
* [Indexador de Blockchain basado en PHP](https://github.com/digitaldonkey/ethereum-php-eventlistener) - permite indexar bloques o escuchar eventos en PHP.
* [Purser](https://github.com/JoinColony/purser) - Herramienta de billetera universal de JavaScript para billeteras basadas en Ethereum. Admite software, hardware y Metamask: trae todas las billeteras a una interfaz consistente y predecible para el desarrollo de dApp.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - Conéctese a MetaMask desde node.js.
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Generador de documentación para proyectos Solidity.
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Exporta datos de la blockchain Ethereum a archivos CSV o JSON.
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Complemento más bonito para formatear el código de Solidity.
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Demostración de integración de Ethereum y Unity.
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Demostración/muestra de integración de Ethereum y Unity.
* [Wonka](https://github.com/Nethereum/Wonka) - Demostración/muestra del motor de reglas comerciales de Nethereum.
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - un conjunto de herramientas para estandarizar la importación de Solidity y la resolución de artefactos en frameworks.
* [eth-revel](https://github.com/justinjmoses/eth-reveal) - una herramienta de nodo y navegador para inspeccionar transacciones, decodificando cuando sea posible el método, los registros de eventos y cualquier motivo de reversión utilizando ABI que se encuentran en línea.
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - una librería útil escrita en Golang para enviar una transacción de manera confiable, abstrayendo algunos de los detalles complicados de bajo nivel, como el gas optimización, cálculos nonce, sincronización y reintentos.
* [truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Verifique sin problemas el código fuente del contrato en Etherscan desde la línea de comandos de Truffle.
* [Blocknative Gas Platform](https://www.blocknative.com/gas) - Estimación de gas para constructores, por constructores. Gas Platform aprovecha la infraestructura de datos mempool en tiempo real de Blocknative para estimar de manera precisa y consistente las tarifas de transacción de Ethereum. Esto proporciona a los constructores y comerciantes una API de tarifa de gas actualizada al momento.

### Estándares de Contratos Inteligentes y Librerías
#### ERCs - La solicitud de Ethereum para un Repositorio de Comentario
* Fichas
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Contrato de token original para activos fungibles.
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - Estándar de token para activos no fungibles.
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - un estándar de token mejorado para activos fungibles.
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - Estándar de token extraíble.
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - crea un método estándar para publicar y detectar qué interfaces implementa un contrato inteligente.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - Contrato de proxy para la gestión y ejecución de claves, para establecer una identidad Blockchain.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - una interfaz estándar para la propiedad de los contratos.

#### Librerías populares para Contratos Inteligentes
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - contiene contratos inteligentes reutilizables probados como SafeMath y OpenZeppelin SDK [librería](https://github.com/OpenZeppelin/openzeppelin-sdk) para capacidad de actualización del contrato.
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - una colección de librerías Solidity para crear contratos inteligentes seguros y eficientes en gas en Ethereum.
* [Librerías modulares](https://github.com/Modular-Network/ethereum-libraries) - un grupo de paquetes creados para su uso en cadenas de bloques que utilizan la máquina virtual Ethereum.
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - una librería de fecha y hora de Solidity que ahorra gas.
* [Aragón](https://github.com/aragon/aragon) - Protocolo DAO. Contiene [framework de contrato inteligente de aragonOS](https://github.com/aragon/aragonOS) con enfoque en la capacidad de actualización y la gobernanza.
* [ARC](https://github.com/daostack/arc) - un sistema operativo para DAO y la capa base de la pila de DAO.
* [0x](https://github.com/0xProject) - protocolo DEX
* [Librerías de tokens con pruebas](https://github.com/sec-bit/tokenlibs-with-proofs) - contiene pruebas de corrección de los contratos de tokens wrt. dadas especificaciones y propiedades de alto nivel.
* [API demostrable](https://github.com/provable-things/ethereum-api) - proporciona contratos para utilizar el servicio demostrable, lo que permite acciones fuera de la cadena, obtención de datos y cálculo.
* [Librerías ABDK para Solidity](https://github.com/abdk-consulting/abdk-libraries-solidity) - Librerías matemáticas de punto flotante de punto fijo (64,64 bits) y de precisión cuádruple (128 bits) que cumplen con IEEE-754 para Solidity.

### Guías de Desarrollador para Infraestructura de 2da Capa

#### Escalabilidad



#### Canales de Pago/Estado
* [Canal de pago de Ethereum](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Canal de pago de Ethereum en 50 líneas de código.
* [Documentación de µRaiden](https://microraiden.readthedocs.io) - Guías y ejemplos para casos de uso de µRaiden Sender/Receiver.

#### Plasma
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - sitio web como aplicación de nodo que se inició en el 2018 IC3-Ethereum Crypto Boot Camp en la Universidad de Cornell, que cubre todas las variantes de Plasma (MVP/Cash/Débito).
* [Plasma MVP](https://github.com/omisego/plasma-contracts) - Implementación de la investigación de OmiseGO de Plasma Mínimo Viable.
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Implementación de Golang y extensión de la especificación de Plasma Mínimo Viable.
* [Plasma Guard](https://github.com/mesg-foundation/plasma-guard) - Mire y desafíe o salga automáticamente de Omisego Plasma Network cuando sea necesario.
* [Plasma OmiseGo Watcher](https://github.com/mesg-foundation/service-plasma-omisego-watcher) - interactúa con la red Plasma OmiseGo y notifica cualquier evento bizantino.

#### Cadenas Laterales
* [Red de POA](https://www.poa.network/)
  * [Puente de POA](https://bridge.poa.net/)
  * [Interfaz de usuario de POA Bridge](https://github.com/poanetwork/bridge-ui)
  * [Contratos de puente de POA](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)
* [Red Matic](https://docs.matic.network/)

#### Privacidad / confidencialidad

##### ZK-SNARKs
* [Red de POA](https://www.poa.network/)
  * [Puente de POA](https://bridge.poa.net/)
  * [Interfaz de usuario de POA Bridge](https://github.com/poanetwork/bridge-ui)
  * [Contratos de puente de POA](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)
* [Red Matic](https://docs.matic.network/)

#### Escalabilidad + Privacidad

#### ZK-STARKs
* [StarkWare](https://github.com/starkware-industries) y [StarkWare Resources](https://github.com/starkware-libs) - motor de escalabilidad StarkEx que almacena las transiciones de estado en cadena.

#### Componentes de UI pre-construidos
* [aragonUI](https://ui.aragon.org) - Una librería React que incluye componentes Dapp.
* [components.bounties.network](https://components.bounties.network) - una librería React que incluye componentes Dapp.
* [ui.decentraland.org](https://github.com/decentraland/ui) - una librería de React que incluye componentes de Dapp.
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Componentes reutilizables de React Dapp.
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Componentes de Metamask React
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - un mecanismo de alojamiento híbrido multiplataforma para aplicaciones descentralizadas basadas en web.
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - muestra de billetera de escritorio multiplataforma.
* [eth-button](https://eth-button.github.io/eth-button/) - Botón de donación minimalista.
* [Rimble Design System](https://rimble.consensys.design/) - Componentes adaptables y estándares de diseño para aplicaciones descentralizadas.
* [Complementos de 3Box](https://docs.3box.io/build/plugins) - agregue los componentes de React para la funcionalidad social. Incluyendo comentarios, perfiles y mensajes.