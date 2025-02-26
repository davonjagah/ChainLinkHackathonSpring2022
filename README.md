# Chainlink Converters
Repository for the Spring 2022 [ChainLink Hackathon](https://chain.link/hackathon).

# Overview

Linking blockchains is a hard problem, with a great solution – Chainlink. Chainlink is a series of Decentralized Oracle Networks (DONs), which are information systems maintained by a committee of nodes.[[1]](https://chain.link/whitepaper)  DONs act as powerful abstraction layers, offering interfaces for smart contracts, and decentralized off-chain computing resources.  Building with Chainlink, this Project provides a new solution to the interoperability problem, which refers to the ability of blockchains to seamlessly integrate with one another.

Hackathon White Paper available on [GitHub](https://github.com/Bhaney44/ChainLinkHackathonSpring2022) and [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4116942).

# Problem
How do we create an interchain protocol between ChainLink and Algorand? The problem requires creating a collatoral form of LINK on Algorand. The collatoralized LINK will allow Chainlink smart contracts to recieve data from Algorand enabling Chainlink smart contracts to use Algorand data in automating asset distributions. 

# Solution
Invent a converter for Algorand and Ethereum using Chainlink. The converter will allow interoperability between the two blockchains. A keystone to the converter is goLink.

# goLink

The token goLink is collatoralized LINK on Algorand. goLink is availible on both the Algorand MainNet and TestNet.

[Algorand MainNet goLink](https://algoexplorer.io/asset/743260106)

[Algorand TestNet goLink](https://testnet.algoexplorer.io/asset/89483596)

LINK Logo added to Algorand Network via [Pull Request #465](https://github.com/tinymanorg/asa-list/pull/465).

<img width="200" alt="icon" src="https://user-images.githubusercontent.com/43055154/168509951-955fb454-a5e6-4aeb-aa69-97972b6f9b87.png">


# Contributors
- [Samuel Tosin](https://github.com/samuellyworld)
- [David Kazeem](https://github.com/davonjagah)
- [Brian Haney](https://github.com/bhaney44)
- [Eugene Nnamdi](https://github.com/eugenennamdi)

# Additional Resources
[Chainlink: Deploy Your First Smart Contract](https://docs.chain.link/docs/deploy-your-first-contract/)

[Chainlink: Consuming Data Feeds](https://docs.chain.link/docs/consuming-data-feeds/)

[Chainlink: Getting Help](https://docs.chain.link/docs/getting-help/)

[Chainlink: Acquire testnet LINK](https://docs.chain.link/docs/acquire-link/)

[Chainlink: Running a Chainlink Node](https://docs.chain.link/docs/running-a-chainlink-node/)

[Chainlink: Fullfilling Requests](https://docs.chain.link/docs/fulfilling-requests/)

[Chainlink: Configuring Chainlink Nodes](https://docs.chain.link/docs/configuration-variables/)

[Chainlink: Building External Adapters](https://docs.chain.link/docs/developers/)

[Chainlink: Bridges: Adding External Adapters to Nodes](https://docs.chain.link/docs/node-operators/)

[Chainlink: Webhook Jobs](https://docs.chain.link/docs/jobs/types/webhook/)

[Chainlink: Building and Using External Adapters](https://blog.chain.link/build-and-use-external-adapters/)

[Open Zeppelin: ERC 20](https://docs.openzeppelin.com/contracts/4.x/erc20)

[Algorand: Create your Own Coin on TestNet](https://developer.algorand.org/tutorials/create-laylacoin/)



