# Hacker Starter Kit

## Getting Help

The [Connext discord](https://discord.gg/7VVWguNx5J) is the best place to get support if you run into issues while developing with Connext. 

## Developer Resources

### What is Connext?

Connext is public infrastructure powering fast, trust-minimized communication between blockchains. Built as a modular interoperability stack, Connext solves the interoperability trilemma, introduces the quadrilemma, and sits in the ideal position within the trade-off space for cross-chain bridges.

Developers can send an xcall and the protocol will then split actions between a Liquidity Layer (Connext) and a Messaging Layer.

### Guides

The [Developer Quickstart](https://docs.connext.network/developers/quickstart) walks developrs through creating a simple crosschain dapp. You'll learn how to use `xcall` and `xreceive` to deploy two contacts- on the source and destination chain.

[xapp-starter](https://github.com/connext/xapp-starter) provides an overview and reference code to get started building crosschain applications. [This workshop](https://www.youtube.com/watch?v=a5vKOVCozqY) walks developers through working with the xapp-starter repo.

[Bridging tokens and data guide](https://ethglobal.com/guides/bridging-tokens-and-data-adzmk#introduction) is a 101 level resource to understanding bridging as a concept, different types of bridges and their security, Connext's modular architecture, and the `xcall` method.  

The [developer section](https://docs.connext.network/developers/intro) of the Connext docs walks developers through tracking xcalls, estimating fees, authentication, and more.

### Connext Contracts

When implementing the constructor on your smart contract that uses `xcall`, you'll need to pass in the address of the deployed Connext diamond contract on the same chain that this contract will be deployed. Reference the list of core connext contracts and TEST asset contracts [here](https://docs.connext.network/resources/deployments).

### Supported Chains

You can find a current list of supported chains [here](https://docs.connext.network/resources/supported-chains).

## Project Ideas

| Name | Description |
|---|---|
|  Crosschain DAO Voting | Execute the outcome of DAO votes across chains
|  Token bridging | Lock-and-mint or burn-and-mint token bridging
|  DEX Liquidity | Aggregate DEX liquidity across chains in a single seamless transaction |
|  Crosschain vault strategy| Crosschain vault zaps and vault strategy management|
|  Crosschain Loans | Lend funds on one chain and borrow on another|
|  Crosschain NFTs | NFT bridging and chain-agnostic NFT marketplaces|

