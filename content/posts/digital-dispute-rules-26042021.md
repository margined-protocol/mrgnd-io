+++
title = "Digital Dispute Resolution Rules: Why, What and When"
date = "2021-04-26"
author = "Margined Protocol"
+++

In this blog post we examine the “Digital Dispute Resolution Rules” - published by the UK Jurisdiction Taskforce (UKJT) [1]. These rules provide the foundations for automated dispute resolution mechanisms built into smart contracts. In particular, these rules are relevant for _smart_ Financial Collateral Arrangement to enable the automation of dispute resolution in post-trade operations. Doing so by providing deterministic mechanisms that automate clearing and settlement of collateral - therefore reducing the occurrence of disputes.

**What are the Digital Dispute Resolution Rules?**

The Digital Dispute Resolution Rules (DDRR) are the follow on from the UKJT’s “Statement on Cryptoassets and Smart Contracts” [2]. The aim of these rules is to create the legal basis of dispute resolution in digital business relationships - which includes blockchain networks.

In the words of the UKJT they are providing the grounding to:

_“...facilitate the rapid and cost-effective resolution of commercial disputes, particularly those involving novel digital technology such as cryptoassets, cryptocurrency, smart contracts, distributed ledger technology…”_

As such the UKJT provides a number of avenues for dispute resolution to occur on in digital business relationships. The mechanisms relevant to smart contracts and blockchain technologies fall into two categories:

* Automated dispute resolution
* Vote based arbitration

An automated dispute resolution mechanism could be encoded into a smart contract protocol and be executed autonomously. Whereas a vote based arbitration mechanism may require active interaction from a number of different parties to resolve a dispute - an prominent example being Kleros [3]. However, dispute resolutions rules would not apply automatically. Therefore parties wishing to use an on-chain mechanism to resolve a dispute would need to show their explicit agreement.

With the UKJT DDRR stating: 

_"The Rules do not apply automatically; they must be agreed to in writing by the parties"_

In addition to the use of on-chain arbitration mechanisms the rules make clear that on-chain data is admissible as evidence in legal proceedings. This is important as even with smart contracts parties will likely still want to be able to use traditional legal methods if an on-chain resolution mechanism did not function as intended.

**Why is this important?**

Smart contracts enable the automation and encoding of business and legal processes. In order to automate post-trade processes we propose to create a smart Financial Collateral Arrangement (FCA).

The smart FCA is a smart contract that defines the trading relationship of two market participants. For example, users must specify in the contract the eligible collateral they accept - similar to the ISDA master agreement. However the users also define the dispute and default resolution mechanisms which they agree to follow - should such situations arise.

Moreover, the protocols encoded by the smart FCA enable the valuation and settlement of users collateral obligations using the deterministic mechanisms and cryptographically verifiable market data.

Therefore users do not only agree to the dispute mechanisms, but, also the pricing and reconciliation methodologies used to determine the value of initial and variation margin. Furthermore the platform enables the counterparties to continually reconcile and enforce settlement to occur at agreed intervals.

Using deterministic mechanisms the protocol is able to reduce the number of disputes that occur in the trade lifecycle. In the current such disputes occur frequently as market participants are using both different inputs and methodologies to their reconciliation engines.

Frequent disputes between market participants leads to an increase in systemic risk and costs to market participants. Indeed the frictions caused by disputes over margin calculations can lead to significant periods of time where counterparties are either over- and under- collateralised.

Providing the infrastructure to perform transparent calculations using verifiable market data to market participants, the reconciliation of an entire portfolio can be completed without dispute arising. The UKJT DDRR gives the assurance that decisions the smart FCAs make are legally enforceable and that any collateral a counterparty receives in a dispute resolution cannot be clawed back by other off-chain mechanisms.

**But what about edge scenarios?**

Above we described how the DDRR could be used to provide deterministic mechanisms in the happy path scenarios. However, the most important situations where legal certainty is required are the edge scenarios - such as events of default.

Using the smart Financial Collateral Arrangement, in an edge-case such as default, the grieved counterparty is able to trigger a resolution period. During this resolution period the defaulting counterparty has the ability to respond and the counterparties may resolve the default or dispute bilaterally. Upon expiration of the resolution period, 1pm the following business day, the deterministic mechanisms and verifiable market data can be used by the grieved counterparty to perform the close-out netting.

At which point the grieved user is able to make claim to the initial margin, pledged into the smart FCA by their counterparty, in order to cover any losses they may have incurred during the close-out netting.

[1]: https://35z8e83m1ih83drye280o9d1-wpengine.netdna-ssl.com/wp-content/uploads/2021/04/Lawtech_DDRR_Final.pdf 
[2]: https://www.judiciary.uk/announcements/the-chancellor-of-the-high-court-sir-geoffrey-vos-launches-legal-statement-on-the-status-of-cryptoassets-and-smart-contracts
[3]: https://kleros.io/ 