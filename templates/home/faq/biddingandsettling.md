---
title: Bidding and Settling
order: 2
---

**Bids**

Once an auction starts, everyone has 5 minutes to bid. Anyone can bid an amount at/above 0.0001 eth. The Amount bid is returned to bidder if they lose the auction (minus gas spent on bid transaction).
Bids at the very last minute increase the auction time by 1 and a half minutes. Sometimes, multiple bids are sent at the same time. This may result in bids coming in and winning an auction at the very last minute/seconds (irrespective of time increase).

**Bid Refunds**

Unsuccessful bids are refunded in full. The timing of refunds may be offset by 1 bidder. This means that a refund is processed for an unsuccessful bid, when a higher bid is submitted.

**Settlement**

When an auction ends, a gas-only transaction is required to mint the current bitNoun to the winners wallet and start the next auction. Anyone can settle an auction. As gas price fluctuates, the cost of settlement also fluctuates.
Settlement gas price of every 9th bitNoun is higher. This is due to the transaction also triggering 2 free bitNoun mints: The bitNounders mint and The Lil Nouns DAO mint.


**FAQ: How do I start the next auction?**

Connect your ethereum wallet. Hit "settle auction" and pay the small gas fee to begin the next auction. 
