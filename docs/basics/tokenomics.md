---
description: RON token quick facts, distribution breakdown, and release schedule
---

import distribution from './assets/distribution.png';
import totalSupply from './assets/total-supply.png';

# Tokenomics

### Ronin token - RON
RON is the ecosystem token of the Ronin blockchain. The RON token enables users to pay for transactions on Ronin, includes decentralized finance (DeFi) features like community governance, and utility via staking through validators to earn rewards.

Ronin validators need to hold and stake RON to participate in validating blocks. They are rewarded with newly issued RON. This rewards are divided up among a validator and its delegators based on the RON they have staked with the validator. 

### RON release schedule
The max total supply is 1,000,000,000 and it can potentially be unlocked after 108 months if every token that is unlocked is issued. RON tokens were first unlocked on January 27, 2023. While the unlock schedule provides a view of RON tokens unlocked at quarterly time periods, tokens are unlocked on a continuous basis rather than having large unlocks at a specific date every quarter for the actual implementation.

<img src={totalSupply} width={800} />

There is a difference between *unlocked supply* (found in the public unlock schedule) and *circulating supply* (tokens that are issued out into circulation). Unlocked tokens may not be immediately circulated into the market and it usually depends on a program budget that is planned in advance. 
* Circulating supply increases in the event that tokens are distributed from the original allocations or staking contracts as rewards to users and other parties.
* It may also decrease in the case where RON is bought back from the market and placed into the treasury.
* Circulating supply will never be higher than the unlocked supply.
* Circulating supply of RON can be queried at the [supply API endpoint](https://supply-api.roninchain.com/info/ron?q=circulatingSupply).

### RON allocation
The quantity of RON reserved for various network functions, as a percentage of the total existing token supply, follows this distribution:

## Token distribution
The quantity of RON reserved for various network functions, as a percentage of the total existing token supply, follows this distribution:
* Staking rewards: 25%
* Community incentives: 30%
* Sky Mavis: 30%
* Ecosystem fund: 15%

<img src={distribution} width={800} />

### Staking rewards
Ronin allocates 25% of its total supply to fund the staking rewards. This is to ensure that the network is seeded well enough until transaction fees gain traction. These rewards are primarily meant to jump-start the network, while the protocol in the long run is intended to sustain itself on the basis of transaction fees.

| Year                    | Staking reward       | Bridge reward     |
|-------------------------|----------------------|-------------------|
| 1 (Starting April 2023) | 30,000,000           | 1,000,000         |
| 2                       | 30,000,000           |                   | 
| 3                       | 30,000,000           |                   | 
| 4                       | 28,000,000           |                   | 
| 5                       | 24,000,000           |                   | 
| 6                       | 18,000,000           |                   | 
| 7                       | 14,000,000           |                   | 
| 8                       | 6,000,000            |                   | 