+++
title = "Carry on Clearing"
date = "2021-05-11"
author = "Margined Protocol"
+++

_In this article we explain the consequences of concentration risk in financial markets. Following this we explain why the Margined Protocol wants to facilitate the adoption of public blockchain networks and DeFi applications by traditional financial institutions to reduce contractration risks. Achieving this through enabling a wider array of end-users to clear and settle directly._

Post the Global Financial Crisis (GFC) derivatives trading has been transformed. When Lehman Brothers collapsed in September 2008 bilateral markets stopped functioning correctly, notably the cleared markets ploughed on. Indeed, the cleared trades made by Lehman were hedged or neutralised within a week whereas bilateral trades took far longer to unwind [1]. Naturally since the GFC there has been an increased push towards central clearing.

Whilst central clearing has provided material benefits to markets, the share of open interest held by the largest market participants has increased substantially. Concretely, in the last 2 decades the number of Futures Commision Merchants (FCM) declined by almost two-thirds - from 177 in June 2006 to a mere 63 in March 2021 [2]. This has resulted in the top 5 and 10 FCMs holding approximately 60 and 80 percent of all open interest [3].

**What is the problem?**

Having an extremely concentrated set of clearing members poses significant systemic risks, especially during times of stress. The, so-called, first law of clearing states:

_“...within a clearing system the number of long positions must always equal the number of short positions for the same instrument”_ [4]

When a default occurs the defaulting party must be replaced in order to maintain a balanced book. In a Central Counterparty (CCP) the defaulting parties position is auctioned to the other clearing members. If the block of trades needing to be replaced is large and concentrated, a sale can have a significant market impact leading and be procyclical. Moreover, as the number of clearing members reduces and the size of open interest held by each market participant increases, the ability to absorb mutualised losses decreases.

Having seen what happens when a leveraged but still small family office gets liquidated the consequences of an individual clearing member’s insolvency should not be ignored! [5]

Whilst the chances of a clearing member default are considered remote, due to the interconnected nature of CCPs a default would have systemic impact.

**What would a different world look like?**

Fundamentally all trades are bilateral between a buyer and seller - regardless of whether the transaction is a coconut for a shekel or an interest rate derivative. Broadening access to direct clearing and settlement between market participants would provide material benefits to the wider system.

In normal times the benefits are somewhat less glamorous but nevertheless desirable. For example for buy-side market participants direct clearing could lower the overall cost of trading through far higher levels of automation; provide an increased number of market participants through a lower barrier to entry; and remove the asymmetries in the collateral management processes reducing time spent both over- and under-collateralised.

In the case of sell-side market participants direct clearing could provide more significant benefits such as reducing the capital requirements on banks. This would be possible as client’s positions would no longer be reflected on the banks’ balance sheet reducing the leverage of the bank [6]. Moreover the internal brokerage divisions could focus on the more profitable parts of the value chain such as credit provision.

In contrast during times of market stress the impact would be greater.

Firstly, overall lower levels of concentration makes the case of default much easier to manage. If open interest is spread between more participants than a single default is far smaller and less impactful. Similarly, increasing the number of participants involved in the clearing network would provide additional capacity to purchase defaulting parties positions - potentially improving auction results. Additionally, in the current state the case of a clearing member default the end-users face a significant operational burden in moving their positions to another clearing member which would not be the case in a more bilateral environment.

**How is Margined Protocl building this world?**

Clearing as a business operation is defined as:

_‘clearing’ means the process of establishing positions, including the calculation of net obligations, and ensuring that financial instruments, cash, or both, are available to secure the exposures arising from those positions;_ [7]

In both professional and academic literature a less concentrated and decentralised clearing and settlement system has been discussed for some time now. Technology, until recently, has not been able to realise this. In the client-server architecture of financial markets it has fallen upon a third-party service provider to perform the clearing and reconciliation of positions - with other parties performing the settlement operations.

The Margined Protocol uses public Turing-complete blockchain and smart contracts to allow market participants to both clear and settle without intermediation by trusted third-party. The platform provides counterparties with the tools and infrastructure to manage their positions on a completely bilateral basis. Using deterministic and verifiable protocols, enforced by a smart Financial Collateral Arrangement (FCA), to automatically calculate the amount of both initial and variation margin due.

Previous attempts to enable direct clearing at CCPs and other bilateral clearing and settlement services have faced challenges. In the past direct clearing would place significant operational burden on end-users. Equally the management of defaults would have required large manual interaction by the end-users. Margined Protocol’s smart FCA automates these processes, only requiring end-user interaction on creation of a new trading relationship and to manage edge-scenarios. 

This is enabled using deterministic and verifiable protocols that auto execute, while the cryptographic guarantees of the blockchain ensure end-users are able to verify that any operation has been carried out correctly.

**Conclusion**

Concentration risk is a significant and real risk to financial stability which should be taken seriously. Whilst capital markets aren’t complete monopolies the interconnected nature of the largest market participants, especially given the overlapping membership of the clearing institutions, means that a default by a systemically important participant would likely spread across the wider system.

Blockchains and DeFi protocols show a way to create Financial Market Infrastructure that doesn’t make tradeoffs between centralisation and efficiency using smart contracts and digital assets to automate the management of clearing and settlement.

**Bibliography**

[1]: Norman, Peter, 2011, The Risk Controllers: Central Counterparty Clearing in Globalised Financial Markets
[2]: https://www.cftc.gov/MarketReports/financialfcmdata/index.htm 
[3]: Alvarez, Nahiomy, McPartland, John, 2020, https://www.risk.net/journal-of-financial-market-infrastructures/7695641/concentration-in-cleared-derivatives-the-case-for-broadening-access-to-direct-central-counterparty-clearing
[4]:McPartland, John, 2003, https://secure.fia.org/downloads/Outlook/OpenArchitectureClearing.pdf 
[5]: https://www.ft.com/content/8062ef53-790f-4470-99d5-265335a72334 
[6]: Alvarez, Nahiomy, McPartland, John, 2019, The concentration of cleared derivatives: Can access to direct CCP clearing for end-users address the challenge?
[7]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32012R0648&from=EN 
