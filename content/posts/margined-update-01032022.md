+++
title = "Margined Protocol Update 03/2022"
date = "2022-03-01"
author = "Margined Protocol"
+++

Margined Protocol is building perpetuals for the CosmWasm eco-system - starting with Terra.

In this post we layout the key features of our v0, but also look past that to additional features and innovations that Margined Protocol will implement in the future releases.

* v0 Release
  * Minimal Viable Perpetuals
* Future Releases
  * v1 Release
    * Governance and Community
    * Permissionless Markets
    * Cross-Margining
    * Liquidity

## Roadmap Overview

{{< image src="/img/margined-roadmap.png" alt="Margined Protocol Roadmap" position="center" style="border-radius: 0px;" >}}

### v0 Release

The v0 release of Margined Protocol aims simply to deliver the perpetuals onto the Terra network. Margined Protocol's v0 release will be modelled on the successful examples of perpetuals deployed on other networks such as Perpetual and Drift Protocols.

## v1 Release

Once the v0 release is deployed future releases of the Margined Protocol intends to offer a different perpetuals product to users of Terra that maximises the capabilities of CosmWasm networks.

### Governance

A key part of the Margined Protocol is the community governance through the `$MRG` token. Where strong coupling and alignment of the token holder incentives to protocol development will deliver long-term results.

Holders of the `$MRG` token will be able to participate in governance decisions that include,

* Creation of new markets
* Acceptance of additional eligible collateral
* Protocol upgrades and updates

Additionally fees generated by the Margined Protocol will be in part paid back to the `$MRG` tokens holders providing incentive to maximise protocol volumes.

Margined Protocol will allow permissionless market creation by users, for assets that have existing price feeds. Token holders will be able to perform governance actions to enable the integration of new oracles and price feeds to the Margined Protocol.

### Cross-Margining

Margined Protocol will also enable cross-margining, allowing users to open positions using their account balance as a common pool of collateral. Additionally it will be possible for users to use multiple assets as collateral. For example this would allow a user to use aUST as the collateral to open a long position on the BTC-UST perpetual market.

The design will mirror that commonly found on centralised exchanges with the benefit of being non-custodial and permissionless.

### Liquidity

A key issue in both standard and _virtual_ AMMs is liquidity and capital efficiency. As in Uniswap v1 where liquidity is evenly spread across the entire constant product function `x * y = k`. This as mentioned means capital is deposited by Liquidity Providers (LPs) that is never used to trade. Whilst in vAMMs there is no capital deposited by LPs the liquidity is still defined by the constant product formula and can cause high-slippage for large orders.

Other perpetual products, such as Perpetual Protocol, have integrated the vAMM with the Uniswap v3 using concentrated liquidity pools. Whilst this does increase liquidity efficiency across the entire curve it can do so at the expense of liquidity outside those bounds.

At Margined Protocol we therefore will implement a _dynamic_ vAMM. The dynamic vAMM enables rebasing of the constant product formula over time to provide users less slippage and a better execution price whilst also reducing imbalance risk that occurs if the oracle and spot price diverge too much.

## Summary

In short Margined Protocol is going to bring Perps to Terra! We think that the core characteristics that CosmWasm allows protocols, such as strong governance and upgradeability, mean that Margined Protocol can iterate rapidly on creating the best perpetual product in the wider market place.

To learn more or to just say hi find us:

* [Discord](discord.gg/NsmHWB8vaJ)
* [Twitter](https://twitter.com/margined_io)
* **Boomer Style** <contact@mrgnd.io>
