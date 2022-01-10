+++
title = "Infrastructure and Initial Margin"
date = "2021-03-23"
author = "Margined Protocol"
+++

In 2009 at the G20 summit in Pittsburgh the largest global economies took a long hard look at themselves and asked the question - ‘how do we stop that happening again?’.

Of course, they were talking about the global financial crash and the failure of Lehman Brothers.

Whilst the analysis of what caused the crisis remains debated to this day, what was clear at the time is that OTC derivatives trading practises certainly didn’t help. Indeed, the difficulty identifying who owed what to whom led to the extended uncertainty in the aftermath of the crisis.

What is clear, however, is the regulatory response to the crash. Now, wherever possible, trades should be cleared. If trades are uncleared, market participants are to pledge segregated collateral to their counterparties - in order to cover any losses in the case of default. These rules were first laid out by the Bank for International Settlement in the Margin Requirements for Uncleared Derivatives and then implemented in Dodd-Frank and EMIR in the United States and Europe respectively [1].

Commonly known as the uncleared margin rules (UMR) they have been implemented through a number of phases. Initially, only the largest banks and financial institutions were in scope. However, as time has passed, more and more institutions have become subject to the requirements of UMR. Respectively from September 2021 and 2022 phases 5 and 6 of the UMR rules will come into effect - bringing hundreds and then thousands of market participants into scope.

**What are the consequences?**

In addition to the requirement to exchange variation margin, which was commonplace before, UMR adds the need for market participants to exchange security collateral, or initial margin, on a bilateral basis. This collateral is intended to cover the losses incurred should either counterparty default and therefore must be held in a segregated account.

In the current state this is enabled through two models:

* Tri-party agent
* Third-party custodian

Regardless of which model firms choose to implement they both have the same problem - namely onboarding delays [2]. This is largely due to the significant difference in scale from phases 1-4 in comparison with phases 5-6.

Where initially only approximately 50 institutions were subject to UMR, in phases 5 and 6 the number is estimated to increase 20x to around 1000 firms [3]. This significant increase in firms affected will result in over 9000 new collateral arrangements to be created [4].

Simply put, current state operations are struggling to scale sufficiently to meet the demand!

**Oh dear**

Legacy collateral management solutions are highly operationally intense and burdensome to deploy. Creating new arrangements requires significant changes to internal processes, requiring firms to adopt set of completely new operations.

Maybe there is another way.

Using smart contracts and programmable money, the Margined Protocol provides the tools and infrastructure for smart Financial Collateral Arrangements (FCA). Using the smart FCA users can clear and settle their variation margin obligations on an intraday basis. Additionally they are able to pledge initial margin directly to one another - without the need for a third party to be involved. The smart FCA enables counterparties to disburse the pledged collateral under a set of deterministic mechanisms - which are defined prior to contract creation. These protocols are able to cover a number of different scenarios including disputes and events of default.

Smart contracts provide the ability to create, alter and terminate agreements rapidly reducing the operational overhead associated with FCAs. Moreover, using smart contracts to define the terms of agreements allows users to know a priori how a scenario will be executed. Reducing the uncertainty associated with dispute resolution.

[1]: https://www.bis.org/bcbs/publ/d499.pdf 
[2]: https://www.globalcustodian.com/industry-associations-urge-regulators-postpone-upcoming-initial-margin-phases/ 
[3]: https://www.capco.com/Intelligence/Capco-Intelligence/Umr-Phase-5-And-6-Delay-A-Perspective-From-Capco-And-Acadiasoft 
[4]: https://www.euroclear.com/newsandinsights/en/Format/Articles/umr-this-time-is-different.html 
