+++
title = "Getting Rekt - Archegos and Systemic Risk"
date = "2021-03-30"
author = "Margined Protocol"
+++

In this post we look at the consequences of the Archegos saga and ask ourselves:

* What happened?
* Why did it happen?
* What do we want to do about it?

**What happened?**

On Friday (26/03/2021) murmurs that a large fund was going pop started to surface. As many people have already discussed, Archegos Capital Management received a margin call which it could not fund and its prime brokers started to unwind its positions.

The ensuing fire sale of their position, worth over $20bn, caused a sell-off, induced panic and sparked debate as everyone tried to understand what was happening and who was affected.

Archegos had amassed a significant synthetic derivative position with over 10 banks, specifically Total Return Swaps - for a nice description see here. Unfortunately these positions went sour resulting in a margin call from Archegos’ prime brokers which they were unable to fund. Leading to the unwinding of their positions and the massive block sell-offs that spooked the market on Friday.

Due to the extraordinary size of the position the sell-off became a massive game of musical chairs, with those left standing when the music stopped facing huge losses. Both Credit Suisse’s and Nomura’s prime brokerage divisions stand to have lost $2bn and counting. Wiping out any profits they stood to have made in H1 2021.

**Why did they make these trades?**

The question arises why were these banks enabling a fund to amass such a huge position?

In short it’s because they wanted to make money.

Prime brokers (PB) charge their clients fees for their positions and take a slice of their profits. Whilst they might ask for some collateral it is typically not very significant as the PB takes the view they will simply unwind the position should the losses get too serious. This does typically work. However, when the position can become too-big-to-unwind, as in the case of Archegos, the unwinding becomes pro-cyclical and increases the losses as the market naturally responds to the sell off.

Here shown in plain sight is the lack of moral hazard for these institutions.

The PBs run the risk/reward calculation that it is worth it and enable these huge bets to be placed with big bonuses if it pays off and little downside if it fails. Except this time it failed much more spectacularly than they could have imagined.

The regulatory response will, as ever, be for greater amounts of centralisation.

Indeed would this situation have occurred in 12 months time then it is likely that Archegos’ position would have been economically unviable. This is as the equity swaps traded by Archegos would be in scope of phase 5 of the Uncleared Margin Rules (UMR) coming into force in September this year. Whereby Archegos and their PBs would have been required to post collateral to one another on a bilateral basis.

**What would have this changed?**

Imagining for a moment that this blow-up had occurred under the UMR regime what would be different? Had the UMR been in force Archegos would have been required to post regulatory collateral to their counterparties (i.e. the prime brokers) and vice-versa.

However, would it have been enough?

To calculate the amount of Initial Margin that each counterparty would be required to post as collateral then we could use the schedule as defined in the BIS UMR paper. This would have required 15% of the notional exposure to be set aside as initial margin - given they were equity trades. Using the much bandied around figure of $20bn this would imply that Archegos and their PB would have had to post a total of $3bn in collateral to one another - giving a total of $6bn.

A substantial amount.

Likely they wouldn’t have used the schedule as it is capital inefficient so let us assume the margin model used was the more capital efficient ISDA SIMM. ISDA SIMM is a little complicated to calculate in a short blog post but we can assume it is not 100x more capital efficient so assuming it is 10x more capital efficient then this means Archegos would have had to pledge $300mn of initial margin to maintain their position.

This would likely make the position untenable as this would be an excessive cost to Archegos, but definitely to any PB on the other side of the trade.

Imagining that they had pledged sufficient collateral even in this scenario these onerous amounts of initial margin may only have partially covered the losses. Given that Nomura and Credit Suisse are saying they are sitting on a total loss of $3-4bn, net any profits the had made elsewhere, indicating the amount of collateral needed may have been gre

**What should be done?**

The Uncleared Margin Rules are not only designed to ensure there is sufficient collateral posted for OTC derivative trades rather they intend to push market participants to centrally clear their trades.

This is largely a good thing.

However, whilst using a central counterparty (CCP) has clear benefits for the market including risk mitigation there are two core issues.

Centralisation increases standardisation
What happens when the CCP defaults

The momentum towards central clearing is gaining, standardisation of derivative contracts is an inevitable result. Leading to a smaller set of risks which market participants are able to hedge against. Though it is likely that there will always be a need and appetite for uncleared derivatives for niche hedges this will be a much smaller set of participants.

Secondly, whilst the waterfall models of CCPs are robustly designed and will likely cover most default scenarios we should keep the physics maxim “everything not forbidden is compulsory" in mind. Therefore, the scenario that default funds are insufficient should be an a priori consideration.

Moreover, as the Archegos saga goes to show, there are always plenty of individuals ready to press the manual override on the risk management system. Meaning whatever risk management practises are in place whether on purpose or not they will likely get broken. Couple this to the knack of traders to find a way to get the most leverage they possibly can from the tools they have available and eventually someone will find a way to truly get rekt.

So, shouldn’t we design our Financial Market Infrastructure with the inevitability of large defaults in mind?

Therefore, enabling market participants to trade on a wholly bilateral basis not only increases the moral hazard of trading institutions but makes the system more “antifragile”. If the only recourse upon default of your counterparty is the collateral pledged directly to you, as opposed to the knowledge that there is a default fund that will cover your losses, this would have extreme effects on trading patterns and risk management practises.

The DeFi world is showing the way in this area with the regular liquidation of positions not causing the market to crumble and teaching some the hard way about risk management before the issues become systemic. This will enable a return to a less centralised and “antifragile” market structure, that should prove more resilient to and prevent contagion of massive blow ups when they inevitably happen.
