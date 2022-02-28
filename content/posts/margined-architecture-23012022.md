+++
title = "Margined Protocol v1 Architecture"
date = "2022-01-23"
author = "Margined Protocol"
+++

Shown below is a high-level overview of the Margined Protocol v1 architecture.

{{< image src="/img/margined-architecture-block.png" alt="Margined Protocol v1 Architecture" position="center" style="border-radius: 0px;" >}}

1. Governance contract manages and execute proposals proposals made by governance token holders. Owner of the factory contract.
2. Factory contract manages margin engines, vAMMs and oracles used by protocol.
3. Users interact with margin engines to create, maintain and close  positions.
4. Margin engine interacts with vAMM to manage user positions.
5. Margin engine escrows users collateral as initial margin on creation of new positions.
6. Oracles feed data into both vAMMs and margin engines for valuation of collateral.
7. Liquidators watch positions held by users for liquidation events or to ensure funding payments occur.
8. Users are able to stake their governance tokens to create, participate and execute governance actions.

For more information or enquiries please reach out to us at <contact@mrgnd.io>.
