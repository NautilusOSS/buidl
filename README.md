# BUIDL Token Whitepaper  
*Rewarding Open Source Contributions on the Voi Blockchain*  

**Version:** 1.3  
**Last Updated:** October 25, 2025  

---

## Abstract  

The **BUIDL Token** is a decentralized, community-driven incentive mechanism deployed on the Voi blockchain. It rewards meaningful contributions to open source software — a critical yet underfunded foundation of the digital economy.  

By pairing with **Build Voi (bVOI)**, a wrapped VOI token that stabilizes liquidity, and **BUIDL Lifetime Rewards (bLFR)**, a non-transferable ARC-200 token that tracks lifetime payouts, BUIDL aligns contributor rewards with long-term stability and accountability.  

The emission system is fully **proportional and gated by each contributor’s bVOI balance**, ensuring that rewards scale with commitment and ecosystem participation. This tri-token model creates a self-reinforcing economy for builders and backers alike.  

---

## Introduction  

Open source powers the internet, modern tools, and Web3 infrastructure. Yet most contributors receive little or no compensation for their time and expertise.  

The BUIDL Token changes this dynamic.  

It provides a transparent, programmable reward system for contributions — from writing code and fixing bugs to designing, testing, documenting, and supporting community governance. By rewarding contributors directly, BUIDL strengthens the sustainability of the open source economy.  

---

## Vision  

**Empower builders. Sustain open source. Grow together.**  

---

## Token Overview  

- **BUIDL (Reward Token)**  
  - Symbol: **BUIDL**  
  - Type: Utility / Reward Token  
  - Contract ID: 419744  
  - Decimals: 8  
  - Total Supply: 100,000,000 BUIDL  
  - Purpose: Transferable token distributed as contributor rewards.  

- **Build Voi (Stability Token)**  
  - Symbol: **bVOI**  
  - Type: Wrapped VOI Token  
  - Contract ID: 8471125  
  - Decimals: 6  
  - Purpose: Stabilizes BUIDL/VOI liquidity pool, gates ongoing emissions.  

- **BUIDL Lifetime Rewards (Tracking Token)**  
  - Symbol: **bLFR**  
  - Type: Non-transferable ARC-200 Token  
  - Decimals: 8  
  - Purpose: Permanent accounting of lifetime BUIDL rewards, used to enforce the bVOI minimum balance requirement.  

---

## BUIDL Lifetime Rewards (bLFR)  

bLFR is a **non-transferable token** minted 1:1 with every BUIDL reward distributed. It cannot be sold, transferred, or burned by contributors.  

Its sole function is to **track the lifetime total of BUIDL earned by each address**. This permanent record ensures the **bVOI minimum balance requirement** cannot be bypassed by moving tokens between wallets.  

- **Minting**: Equal to each BUIDL payout, issued automatically.  
- **Non-transferable**: bLFR cannot leave the contributor’s address.  
- **Verification**: Serves as the official on-chain record of lifetime contributions.  

---

## Relationship Between Tokens  

The system operates with **three interdependent tokens**:  

- **BUIDL** → Contributor rewards (transferable).  
- **bVOI** → Stability and peg enforcement (wrapped VOI, transferable).  
- **bLFR** → Lifetime accounting of rewards (non-transferable).  

### Dynamics  

- Contributors earn **BUIDL** for verified work.  
- Each payout mints matching **bLFR**, recording lifetime rewards.  
- Ongoing payouts require contributors to hold **bVOI equal to 25% of their bLFR balance**.  
- Weekly reward weighting is determined by each contributor’s **bVOI ratio**, ensuring proportional and sustainable distribution.  

Together, these tokens form a **closed-loop incentive system** that aligns individual rewards with long-term ecosystem stability.  

---

## Utility & Use Cases  

- Direct contributor rewards  
- Community or DAO-funded bounties  
- Retroactive recognition  
- Governance rights (via DAO)  
- Contribution-based reputation  

---

## Reward Mechanisms  

1. Automated GitHub/GitLab activity recognition  
2. Community-led bounty funding  
3. DAO-led curation and voting  
4. Retroactive reward drops  

---

## Payout Adjustments  

- **Weekly Emissions:** 100,000 BUIDL  
- **Distribution:** 100% distributed proportionally each week, gated by bVOI balance.  
- **Eligibility:** Contributors must maintain the required **bVOI coverage ratio** (25% of their bLFR balance) to receive full rewards.  

### Weighted Payout Model  

- Contributors’ weekly rewards are **weighted by their current bVOI ratio**, defined as:  

bVOI Ratio = held_bVOI / (0.25 × bLFR_total)

- **If ratio ≥ 1.0:** contributor receives their full eligible share.  
- **If ratio < 1.0:** payout is scaled linearly by the ratio (e.g., 0.8 ratio → 80% payout).  

### Allocation Logic  

- Weekly emission cap: **100,000 BUIDL**  
- Individual soft cap: **50,000 BUIDL** (pre-adjustment)  
- Rewards are normalized across all contributors so the total weekly output never exceeds the emission cap.  
- **Unclaimed portions** automatically roll into the next week’s emission pool.  

This unified mechanism replaces the prior “Outgoing Payments + Rollover Pool” split, simplifying distribution while maintaining sustainability and reinforcing the bVOI stability requirement.  

---

## Distribution  

- **Total Supply**: 100,000,000 BUIDL  
- **Contributor Rewards**: 100% allocation  
- **Weekly Cap**: 100,000 BUIDL  
- **Unclaimed Rewards**: Sent to Treasury  
- **Team/Advisor/Investor Allocation**: None  
- **Fairness Rule**: Individual cap (50,000 BUIDL unadjusted) + proportional adjustment ensures broad distribution  

---

## Price Stability Mechanism  

To sustain a **soft peg (1 BUIDL = 1 VOI)**:  

- **If BUIDL < 1 VOI** → protocol buys BUIDL with block rewards.  
- **If BUIDL > 1 VOI** → treasury sells BUIDL, wraps VOI as bVOI, and adds liquidity.  

### bVOI Requirement (Enforced via bLFR)  

- **First payout**: No bVOI required.  
- **Subsequent payouts**: Must hold **25% of total bLFR balance in bVOI**.  
- **Example**: If an address has 10,000 bLFR (lifetime rewards), it must hold at least 2,500 bVOI to continue receiving new BUIDL.  

**Note**: bVOI deposited in approved lending protocols also counts toward this requirement.  

---

## Governance  

The BUIDL ecosystem is managed through **BUIDLDAO**:  

- **Builders** (BUIDL holders): propose and vote on upgrades, treasury allocations, and policy changes.  
- **Patrons** (bVOI holders): safeguard stability and influence weekly distributions.  

Governance begins as a multisig → transitions to full DAO.  

---

## Funding Policy  

To prevent double compensation:  

- Work rewarded by BUIDLDAO is **not eligible** for separate Voi retroactive grants.  
- Retroactive proposals (to external parties) are submitted only by the DAO.  
- If external funds are received:  
- First: DAO Treasury reimbursed.  
- Remaining: 90% to contributor, 10% to DAO.  

**Enforcement**: Misuse leads to blacklisting, reversible only by returning funds.  

---

## Roadmap  

**Q1 2025**  
- Token launch  
- Bounty Board MVP  

**Q2 2025 and Beyond**  
- GitHub integration MVP  
- DAO activation  
- Contributor dashboard  
- Multi-repo support  
- Contributor scoring system  
- DAO grant program  
- Strategic partnerships  

---

## Conclusion  

BUIDL turns open source from volunteer work into a sustainable economy. Paired with bVOI for stability and bLFR for accountability, it balances rewards with sustainability and ensures contributors are recognized for their impact.  

**Join us — and let’s BUIDL together.**  

---

## Changelog  

**v1.3 — October 25, 2025**  
- Unified emissions model: replaced *Outgoing Payments + Rollover Pool* with a single **proportional distribution gated by bVOI**.  
- Added **Weighted Payout Model** and clarified proportional scaling logic.  
- Updated **Abstract** and **Relationship Between Tokens** to reflect unified emissions.  

**v1.2 — October 1, 2025**  
- Added **BUIDL Lifetime Rewards (bLFR)** as a non-transferable ARC-200 token.  
- Updated **Abstract** to reflect tri-token model (BUIDL, bVOI, bLFR).  
- Added full **bLFR section**.  
- Revised **bVOI Balance Requirement** to use **bLFR as the enforcement metric**.  
- Updated **Relationship Between Tokens** to reflect three-token system.  

**v1.1 — September 26, 2025**  
- Added emissions split (Outgoing Payments vs Rollover Pool).  
- Clarified unused Outgoing Payments → Rollover Pool.  
- Expanded bVOI Balance Requirement to include lending deposits.  

**v1.0 — April 2025**  
- Initial release of BUIDL Token Whitepaper.  
