# BUIDL Token Whitepaper  
*Rewarding Open Source Contributions on the Voi Blockchain*  

**Version:** 1.1  
**Last Updated:** September 26, 2025  

---

## Abstract

The BUIDL Token is a decentralized, community-driven incentive mechanism deployed on the Voi blockchain. It rewards meaningful contributions to open source software — a critical yet often underfunded pillar of the digital world. By aligning incentives with actual contributions, BUIDL fosters a more sustainable, inclusive, and efficient model for growing the open source economy.  

To ensure long-term value stability, BUIDL is paired with **Build Voi (bVOI)**, a wrapped VOI token that backs emissions and stabilizes the BUIDL/VOI liquidity pool. This dual-token design aligns contributor rewards with economic sustainability, creating a self-reinforcing ecosystem.  

---

## Introduction

Open source software powers the internet, the tools we use daily, and the foundations of Web3. Despite its impact, most contributors receive little or no compensation for their time and expertise.

The BUIDL Token exists to change that.

It provides a transparent, programmable reward system for contributors—whether writing code, designing UX, fixing bugs, reviewing pull requests, creating documentation, testing, or supporting governance/community efforts. BUIDL empowers builders and strengthens the long-term health of open source ecosystems.  

---

## Vision

**Empower builders. Sustain open source. Grow together.**

---

## Token Overview

- **Name**: BUIDL Token ([View on Voiager](https://voiager.xyz/token/419744))  
- **Description**: BUIDL is a reward token for open source contributions, designed to incentivize participation and maintain a sustainable contributor economy within the Voi ecosystem.  
- **Contract ID**: 419744  
- **Symbol**: BUIDL  
- **Type**: Utility / Reward Token  
- **Chain**: Voi  
- **Decimals**: 8  
- **Total Supply**: 100,000,000 BUIDL  

---

## Build Voi (bVOI) Overview

- **Name**: Build Voi ([View on Voiager](https://voiager.xyz/token/8471125))  
- **Description**: bVOI is a wrapped version of VOI used to stabilize the BUIDL token economy by backing the BUIDL/VOI liquidity pool and regulating emissions.  
- **Contract ID**: 8471125  
- **Symbol**: bVOI  
- **Type**: Wrapped VOI Token  
- **Chain**: Voi  
- **Decimals**: 6  
- **Function**: Acts as a gatekeeper for BUIDL emissions by requiring users to hold bVOI in proportion to their payouts. Also used to rebalance liquidity when BUIDL deviates from its 1:1 peg with VOI.  
- **Sustainable Supply**: 22,000,000 bVOI (as of 14 May 2025)

---

## Relationship Between BUIDL and Build Voi (bVOI)

BUIDL and bVOI work together to form a closed-loop system for incentives and value stability.

- **BUIDL** rewards contributors.  
- **bVOI** backs BUIDL issuance and liquidity.

Key dynamics:

- **Peg Enforcement**: A BUIDL/VOI liquidity pool uses bVOI to maintain a soft 1:1 peg.  
- **Distribution Control**: Contributors must hold bVOI to receive ongoing BUIDL rewards.  
- **Feedback Loop**: More BUIDL issued → higher demand for bVOI. Price deviations are corrected using buys/sells.  
- **Aligned Governance**: BUIDL holders govern the DAO. bVOI holders safeguard the system’s stability.  

---

## Utility & Use Cases

- Contributor Rewards (automated or manual)  
- Project Bounties (via community or DAO)  
- Retroactive Funding (for completed work)  
- Governance Participation  
- Contribution Reputation System  

---

## Reward Mechanisms

1. Automated GitHub/GitLab Recognition  
2. Community-Led Bounties  
3. DAO-Led Curation and Voting  
4. Retroactive Reward Drops  

---

## Payout Adjustments

Weekly payouts are **adjusted proportionally** to fit within the weekly budget, based on the total unadjusted payout amounts for that week. If the total eligible rewards exceed the 100,000 BUIDL emission cap, each contributor receives a reduced share proportional to their original reward.

To limit the impact of large individual rewards on the weekly pool, each contributor's **unadjusted payout is capped at 50,000 BUIDL** per week before proportional adjustment. This ensures broader distribution and prevents outsized claims from distorting the reward cycle.

Weekly emissions are split **50/50** between:  
- **Outgoing Payments**: Distributed to contributors without rollover requirements.  
- **Rollover Pool**: Reserved for contributors meeting bVOI balance requirements, distributed proportionally among eligible rollover claims.  

Any **unused tokens from Outgoing Payments** are automatically redirected into the **Rollover Pool** for that week.  

Any undistributed BUIDL after both allocations is **rolled over** into the following week's budget, increasing the available emissions for future payouts.  

---

## Distribution

- **Total Supply**: 100,000,000 BUIDL  
- **Contributor Rewards**: 100%  
- **Weekly Emissions**: 100,000 BUIDL  
- **Unclaimed Rewards**: Rolled into the Treasury  
- **Team/Advisor/Investor Allocation**: None  
- **Weekly Cap**: Maximum BUIDL per user is limited by their bVOI balance  
- **Individual Payout Cap**: Each contributor's unadjusted weekly payout is capped at **50,000 BUIDL** to ensure fairness and reduce distortion during proportional adjustments  

---

## Price Stability Mechanism

To maintain a soft peg of 1 BUIDL = 1 VOI, the protocol introduces Build Voi (bVOI), a wrapped VOI token used to fund and stabilize the BUIDL/VOI liquidity pool.

**If BUIDL < 1 VOI**:  
- Block rewards are used to buy BUIDL from the market.

**If BUIDL > 1 VOI**:  
- Treasury sells BUIDL for VOI.  
- VOI is rewrapped as bVOI and added back to liquidity.  

**Weekly Cap**:  
- Users can only receive BUIDL up to their bVOI balance each week.

### bVOI Balance Requirement

Contributors can receive their first BUIDL payout without holding bVOI.  
Starting with the second payout, they must hold bVOI equal to **at least 25%** of the total BUIDL they've received to date.  

**Example**: If a contributor has received 1,000 BUIDL, they must maintain a balance of 250 bVOI to continue receiving new BUIDL rewards.  

**BUIDL Voi held in approved lending protocols also counts toward satisfying this balance requirement**, ensuring that contributors who provide liquidity or participate in DeFi with their bVOI are not penalized.  

This model encourages long-term participation and economic alignment while lowering the barrier for first-time contributors.  

---

## Governance

The BUIDL ecosystem is governed by the BUIDLDAO:

- **Members**: BUIDL holders. Propose and vote on upgrades, treasury use, and policy.  
- **Patrons**: bVOI holders. Influence weekly distributions and support price stability.  

Governance begins with a multisig structure and evolves toward a full DAO over time.  

---

## Funding Policy

To ensure fairness and avoid double compensation:

- Contributions rewarded by BUIDLDAO are ineligible for additional retroactive grants from the Voi ecosystem.  
- Contributors receiving BUIDL agree their work is part of the DAO's collective effort.  
- Retroactive proposals to third parties (e.g., Voi) will be submitted by BUIDLDAO on behalf of contributors.  
- If external grants are received:  
  - First: Reimburse the BUIDL Treasury.  
  - Remainder: 90% to the contributor, 10% to the DAO.

**Compliance**:  
- Violations may result in blacklisting from BUIDL rewards.  
- Contributors can restore eligibility by sending improperly received funds back to the DAO Treasury.  

---

## Roadmap

**Q1 2025**  
- Launch BUIDL Token on Voi  
- Deploy Bounty Board MVP  

**Q2 2025 and Beyond**  
- GitHub Integration MVP  
- DAO Activation  
- Contributor Dashboard  
- Strategic Partnerships  
- Multi-Repo Support  
- Developer Tool Integrations  
- Contributor Scoring System  
- DAO Grant Program  

---

## Conclusion

BUIDL transforms open source from a volunteer effort into a sustainable economy.  
Built on the fast, low-cost Voi blockchain, it rewards contributors and maintains value stability via Build Voi (bVOI).  
Together, they create a flywheel of aligned incentives for builders and backers alike.

**Join us — and BUIDL together.**  

---

## Changelog

**v1.1 — September 26, 2025**  
- Added **versioning and Last Updated** date fields.  
- Clarified **50/50 emissions split** between Outgoing Payments and Rollover Pool.  
- Added rule that **unused Outgoing Payments flow into Rollover Pool**.  
- Expanded **bVOI Balance Requirement**: BUIDL Voi held in approved lending protocols counts toward the balance.  
- Minor clarity edits in Abstract and Introduction.  

**v1.0 — Initial Release (April 2025)**  
- Original publication of the BUIDL Token Whitepaper.  
