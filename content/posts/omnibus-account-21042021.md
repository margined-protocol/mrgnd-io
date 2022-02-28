+++
title = "How I Learned to Stop Worrying and Love the Omnibus Account"
date = "2021-04-23"
author = "Margined Protocol"
+++

_In this blog post we explain why creation of the omnibus account by the Bank of England is an important step and how it is relevant to a wide array of use-cases._

On 19/04/2021 the Bank of England released a statement on Central Bank Digital Currency (CBDC). Announcing the creation of CBDC engagement and technology forums the statement received a great deal of attention.

However, attached to the same email newsletter was a smaller piece of policy news titled - “Bank of England publishes policy for omnibus accounts in RTGS” [1].

This short piece of policy is, in our view, a far more radical and material change in central bank policy.

**What is RTGS and why does it matter?**

The Real-Time Gross Settlement (RTGS) service is the system that processes payments of central bank reserves between financial institutions. As the economy ticks over throughout the day and payments large and small are settled using this system.

Access to RTGS systems is not open to everyone. Rather access is restricted to only the largest financial institutions - such as banks and clearing houses. They use these systems to pay each other and settle in central bank reserves.

Operated directly by the central bank the RTGS service is the backbone of a country's economy and when it doesn’t work people notice. For example in february this year the American RTGS system, Fedwire, crashed preventing payments being made throughout the US.

**But why do banks settle using central bank reserves?**

When a payment made in the economy is not between accounts held at the same bank then an intermediary is needed to ensure that the credits and debits are applied correctly. The central bank provides this service via RTGS.

Moreover the reserves held by banks for use in RTGS settlement are where monetary policy and the real economy meet. The central bank applies the interest rate directly to the funds held.

Hence RTGS systems are not only important payment infrastructure but an integral part of monetary policy. Therefore the central banks do not want to increase resiliency of payments by creating alternatives as this would reduce the efficacy of setting interests rates as monetary policy.

**Why is the Omnibus Account important?**

So we have established that the RTGS system is how payments are settled in the economy. Then understood that central bank reserves are one tool that central banks use to implement monetary policy.

Given the changing nature of payments and technology central banks need to keep up. Opening the RTGS service to other payment systems is a way of fostering innovation. However, they need to do so in a way that does not disrupt or pose a risk to business as usual.

The omnibus model enables this.

Fundamentally the central bank operates a ledger and when payment instructions are received they debit the payer and credit the payee. Now let’s investigate the case where another system is able to interoperate with the RTGS service without using an omnibus account structure.

{{< image src="/img/rtgs-account.png" alt="Hello Friend" position="center" style="border-radius: 0px;" >}}

In figure 1 above we see a simple representation of a payments network interoperating with the RTGS service - without an omnibus account. In this model we see that Alice and Bob, two RTGS participants, have reserves balances of 10 and 15 respectively.

As payments are made on the interoperating system the changes must continually be updated in the RTGS accounts. If the two ledgers become out-of-sync then credit risk is introduced as Alice or Bob may be unable to settle payments they have made on the interoperating system.

This is where the omnibus account model steps in.

Shown below in figure 2 the omnibus account is a new account into which central bank reserves are transferred. Instead of synchronising the two accounts on the RTGS service and interoperating system any reserves that are used are placed in a single bucket - the omnibus account.

{{< image src="/img/omnibus-account.png" alt="Hello Friend" position="center" style="border-radius: 0px;" >}}

Each transfer into the bucket is then followed by a issuance of a synthetic or tokenised form of the central bank reserve on that interoperating system. The tokenised assets can then be transferred between system participants with the knowledge that every token is backed 1:1 by an asset in the omnibus account.

Therefore this simple construct removes the need for continued reconciliation between the two systems and the associated credit risk.

**How can other projects learn from this?**

This simple omnibus model of a single account from which digital assets are issued onto interoperating systems is not just relevant for central bank reserves and RTGS systems - the idea can apply more broadly to other projects trying to create digital assets.

In many blockchain and DLT projects we see the blockchain simply being used to record transfers of an asset. This leads to the introduction of settlement and credit risks - which we have shown an omnibus account structure can remove.

Alternative examples of this could be in the use-case of securities. Again the Central Securities Depository (CSD), rather than using blockchain to send settlement instructions to their internal ledger, issue the securities onto the ledger and use the omnibus account structure to ensure that the on-chain digital assets are always 1:1 backed by the “real-world” asset.

**What does this mean for smart Finacial Collateral Arrangements?**

Using smart Financial Collateral Arrangements our users will be able to pledge initial margin and settle variation margin payments - without the need for any third-parties.

Asset backed digital assets are a fundamental part of this and the omnibus account model enables the creation of tokenised digital assets that are 1:1 backed. This model increases efficiency of new technologies interoperating with legacy systems and removes the potential for credit risk occurring when two systems work together.

Adoption of the omnibus account model by multiple different use-cases will increase the speed and ability for blockchain and DLT technologies to integrate with existing systems and drive efficiency in capital markets.


[1]: https://www.bankofengland.co.uk/news/2021/april/boe-publishes-policy-for-omnibus-accounts-in-rtgs 
[2]: https://nypost.com/2021/02/24/fed-blames-operational-error-that-crashed-fedwire/ 