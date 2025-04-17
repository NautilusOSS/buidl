# BUIDL Token Whitepaper

*Rewarding Open Source Contributions on the Voi Blockchain*

## Abstract

The BUIDL Token is a decentralized, community-driven incentive mechanism deployed on the Voi blockchain. It is designed to reward meaningful contributions to open source software - a critical but often underfunded pillar of the modern digital ecosystem. By aligning incentives with actual contributions, BUIDL aims to create a more sustainable, inclusive, and efficient model for growing the open source economy.

## Introduction

Open source software powers the internet, the tools we use every day, and the foundations of Web3. Despite its significance, most open source contributors receive little to no compensation for their time and expertise.

The BUIDL Token exists to change that.

By providing a transparent and programmable reward system for contributors - whether they’re writing code, designing UX, fixing bugs, reviewing pull requests, or creating documentation - BUIDL empowers builders and ensures the long-term health of open source ecosystems.

## Vision

Empower builders. Sustain open source. Grow together.

## Token Overview

- Name: BUIDL Token ([View on Voiager](https://voiager.xyz/token/419744))
- Description: BUIDL is a reward token for open source contributions, designed to incentivize participation and maintain a sustainable contributor economy within the Voi ecosystem.
- Contract ID: 419744
- Symbol: BUIDL
- Type: Utility / Reward Token
- Chain: Voi
- Decimals: 8
- Total Supply: 100,000,000 BUIDL

## Build Voi (bVOI) Overview

- Name: Build Voi ([View on Voiager](https://voiager.xyz/token/8471125))
- Description: bVOI is a wrapped version of VOI used to stabilize the BUIDL token economy by backing the BUIDL/VOI liquidity pool and regulating reward distribution.
- Contarct ID: 8471125
- Symbol: bVOI
- Type: Wrapped VOI Token
- Chain: Voi
- Decimals: 6
- Function: Acts as a gatekeeper for BUIDL emissions by requiring users to hold bVOI in proportion to their payouts. Also used to rebalance liquidity when BUIDL deviates from its 1:1 peg with VOI.
- Sustainable Supply: 17,000,000 bVOI (as of 9 Apr 2025)

## Relationship Between BUIDL and Build Voi (bVOI)

BUIDL and bVOI are designed to function in tandem, forming a closed-loop incentive and stabilization system for the BUIDL ecosystem.

- **BUIDL** is the token used to reward contributors to open source projects.
- **bVOI** is a wrapped VOI token that governs BUIDL issuance and helps stabilize its value.

Key aspects of the relationship include:

- **Peg Enforcement**: bVOI is used in a liquidity pool to maintain the target value of 1 BUIDL = 1 VOI.
- **Distribution Gatekeeping**: bVOI acts as a throttle, requiring contributors to hold it in order to receive BUIDL rewards.
- **Economic Feedback Loop**: As more BUIDL is distributed, demand for bVOI increases. If BUIDL supply exceeds peg, bVOI is used to buy BUIDL. If BUIDL trades above peg, more BUIDL is sold for VOI and converted into bVOI.
- **Governance Synergy**: BUIDL holders govern the ecosystem, while bVOI holders back its stability—creating a system where contributors and patrons are both aligned.

This model ensures that distribution and valuation of BUIDL are tied directly to real economic support within the Voi ecosystem.

## Utility & Use Cases

- Contributor Rewards
- Bounties
- Retroactive Funding
- Governance
- Reputation Layer

## Reward Mechanisms

1. GitHub/GitLab Automation
2. Project-Led Bounties
3. DAO-Based Curation
4. Retroactive Drops

## Distribution

Total Supply: 100,000,000 BUIDL

- Contributor Rewards: 100%

Notes:

- 100,000 BUIDL released per week.
- If no contributions are made, tokens are added to the treasury.
- No team/advisor/investor allocation.
- Maximum weekly BUIDL per user is limited by their bVOI balance.

## Price Stability Mechanism

To maintain a soft peg of 1 BUIDL = 1 VOI, the protocol introduces Build Voi (bVOI), a wrapped VOI token used to fund and stabilize the BUIDL/VOI liquidity pool.

If BUIDL < 1 VOI:

- Block rewards are used to buy BUIDL from the market.

If BUIDL > 1 VOI:

- Treasury sells BUIDL for VOI.
- VOI is rewrapped as bVOI and added back to liquidity.

Weekly cap:

- Users can only receive BUIDL up to their bVOI balance each week.

### bVOI Balance Requirement

To encourage onboarding while maintaining economic alignment, bVOI balance requirements follow a simplified model:

- **1st payout**: No bVOI required.
- **2nd payout and onward**: The contributor must maintain a bVOI balance equal to **at least 25%** of the total BUIDL they have received to date.

For clarity, this means that if a contributor has received a total of 1,000 BUIDL over time, they must maintain a balance of at least 250 bVOI to continue receiving new BUIDL distributions.

This structure ensures participants are economically invested in the system while providing a smoother ramp-up for new contributors.

Sustainable Supply: 17,000,000 bVOI

## Governance

The BUIDL ecosystem is governed by the BUIDLDAO:

- BUIDL holders are members of the DAO.
- bVOI holders are patrons who support liquidity and reward limits.

Members (BUIDL holders): Propose and vote on upgrades, treasury use, and policy.
Patrons (bVOI holders): Influence weekly distribution by backing contributors.

Governance starts with multisig and evolves to full DAO.

## Funding Policy

To maintain fairness and avoid double compensation, the following rules apply:

- Recognized contributions rewarded by BUIDLDAO are not eligible for Voi retroactive grant proposals.
- By receiving BUIDL tokens, contributors explicitly agree that their work is part of the DAO’s collective effort.
- Retroactive grant proposals to external ecosystems (e.g., Voi) will be submitted on behalf of contributors by BUIDLDAO.
- Any tokens received from these grants will first be used to reimburse the BUIDL Treasury. Any remaining tokens will be split 90/10 between the contributor and the BUIDL Treasury.

Compliance & Enforcement:

- Failure to abide by this funding policy will result in blacklisting from future BUIDLDAO rewards and participation.
- Remediation may be made by sending the improperly received funds to the DAO treasury to restore standing.

## Roadmap

Q1 2025:

- Token launch on Voi
- Bounty board

Q2 2025 and beyond:

- GitHub integration MVP
- DAO activation
- Contributor dashboard
- Partnerships
- Multi-repo support
- Developer tool integrations
- Contributor score
- DAO grants

## Conclusion

BUIDL transforms open source from a volunteer effort into a sustainable system. Built on Voi, it leverages fast, low-cost infrastructure to reward contributors and maintain economic stability. The use of Build Voi ensures price alignment while bVOI balances regulate distribution. Join us - and BUIDL together.
