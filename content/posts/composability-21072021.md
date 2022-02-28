+++
title = "Composability: What is it and why should you care?"
date = "2021-06-26"
author = "Margined Protocol"
+++

While many might have heard of Non Fungible Tokens (NFTs), Decentralized Autonomous Organizations (DAOs) or Decentralized Finance (DeFi), all these applications are made possible through smart contracts, which is the major innovation of Ethereum.

However, you may ask:

_“What are smart contracts?”_

The term “smart contract” was first coined in the 1990s by computer scientist, lawyer and cryptographer Nick Szabo, who defined a smart contract as:

“A set of promises, specified in digital form, including protocols within which the parties perform on the other promises” [1]

Since then, the concept has evolved with the introduction of Turing-complete blockchain networks like Ethereum. Generally the term is used to refer to computer programs that can run deterministically on blockchain networks like Ethereum and Solana - to name a few.

However, smart contracts go beyond simply being isolated computer programs run on a blockchain network. Through the account based design the Ethereum smart contracts are able to interact with other smart contracts. The ability for one contract to run the code and alter the state of another is what is commonly referred to as composability. Through this ability of contracts to interact with one another we have seen the development of DeFi.

**But what exactly is Composability?**

Put simply, it’s the ability to use existing smart contract applications as building blocks to create more complex use cases. This is the power behind DeFi as developers are free to focus on developing new use-cases by leveraging already existing protocols - leading to compounding innovation through the rapid development cycle.

In essence each smart contract becomes an open API that anyone and any contract can interact with. This is made even easier with the increased standardisation of contract interfaces. This is exemplified by the ERC20 standard that has seen massive adoption since its inception and becoming the base for popular assets like USDC, USDT and DAI [3].

Another interesting use-case of ERC20 is wrapped Ether (WETH) which allows users to trade ETH as if it was an ERC20 token - this makes integrating ETH into protocols that support ERC20 simple as it can be treated as any other ERC20 asset.

The Margined Protocol uses smart contract composability to show how the future of capital markets will benefit from the ability of protocols to interact. Specifically we allowed users of our smart Financial Collateral Arrangement (FCA) to lend their initial margin to the Compound lending protocol. This lets users earn a yield on their collateral whilst remaining pledged for use in the event of default.

Smart contract composability allows this as the IM that is pledged between the counterparties in a smart FCA is then lent on Compound which mints interest-bearing assets, cUSDC, that can later be redeemed for the original lent amount plus the interest earned until that point in the original form of eligible collateral - USDC in our example.

{{< image src="/img/jaime-diagram.png" alt="Hello Friend" position="center" style="border-radius: 0px;" >}}

The important aspect here is how we have created a new feature for our application by leveraging composability and simply integrating against a permissionless lending protocol such as Compound.

- [1]: N. Szabo, “Smart Contracts: Building Blocks for Digital Markets”, Extropy nr. 16 (1996)
- [2]: Matthew N, O. Sadiku, G. Eze: “Smart Contracts: A Primer” (2018)
- [3]: ERC20 Standard - https://ethereum.org/en/developers/docs/standards/tokens/erc-20/ 
