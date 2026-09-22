---
description: A report for ADA holders on how the ecosystem grows in the DeFi vertical
hidden: true
---

# Growing Cardano DeFi

## **Before you read**

<details>

<summary>What this report is</summary>

You hold ADA and you want the ecosystem to grow. This report explains, with pinned data, where Cardano DeFi stands against rival ecosystems, what mechanically drives DeFi volume, what the newly enacted Cardano PRIME program changes, and how to tell whether any of it is working. Each section stands alone.

</details>

<details>

<summary>What this report is NOT</summary>

No price commentary or predictions about ADA or any token. No endorsement of any proposal, proposer, protocol, or vendor — including PRIME, which is described here as an enacted fact of the landscape, not a recommendation. Ecosystem growth is the subject; token price is not.

</details>

<details>

<summary>Data snapshot: September 8, 2026</summary>

Pulled from the DefiLlama API. Refresh before publication if this slips materially.

</details>

<details>

<summary>v5 changes (review by Sinan Kajan, Product Marketing Specialist, Cardano Foundation)</summary>

(1) RealFi corrected to its two-token model — USDr is the fully reserved, non-yield-bearing base stablecoin; sUSDr is the staked yield-bearing instrument. Earlier versions described USDr itself as yield-bearing, which was wrong; (2) RealFi mainnet date confirmed: 1 October 2026, announced publicly on 2 September, now used throughout; (3) sequencing restored and re-anchored to real dates — Phase 1 to Q4, Phase 2 to the 1 October mainnet and the Leios year-end target, Phase 3 into H1 2027; (4) scoreboard split into ecosystem KPIs and intervention KPIs with named owners (Sinan's suggestion, on Marco Moshi's attribution point); (5) project-closure claim re-sourced to the closures themselves rather than a personality quote; (6) Hyperliquid/Ethereum ratio made precise.



_Earlier: v4 added Cardano PRIME and refreshed all data to September; v3 added the rival-ecosystem benchmark at Laura's request. Laura's "update with the AlphaGrowth" comment is addressed in_

</details>

### 1. Executive Summary

Two things happened since the July draft, and they point in opposite directions.

**First, the numbers got worse.** Between July 7 and September 8, Cardano's DeFi TVL fell from $86.1M to $65.0M (−24.5%) and its rank slipped from #29 to #34 of 466 chains — while the global DeFi market grew from $74.1B to $87.8B (+18.5%). Stablecoin supply flatlined at $66.9M (from $67.6M), ending the +44% run that v3 highlighted as the strongest growth signal in the report. Headline 30-day DEX volume appears up 109%, but 83% of it comes from a single protocol (Dano Finance, $151.8M of $183.7M) in a burst that has already collapsed — its 7-day volume is down 60% week-over-week. Excluding it, Cardano's DEX volume fell from \~$73M to \~$32M, roughly −56%, during a market-wide volume surge in which Solana rose 38%, Ethereum 27% and Tron 24%. Cardano did not participate in an industry-wide up-move. That is the single most important fact in this report.

**Second, ₳120,000,000 was approved to address exactly this.** On August 13, 2026 the Cardano PRIME treasury withdrawal was ratified and enacted — a 12-month program executed by AlphaGrowth under Operating Group oversight, with Intersect as Constitutional Administrator managing the funds. Its explicit purpose is to improve DeFi protocol readiness, responsibly activate incentives, and grow durable liquidity. DReps approved it 76.15% to 23.85%.

**And one date is now fixed.** RealFi launches on Cardano mainnet on 1 October 2026 (announced 2 September). Its public testnet drew 3,600+ participants and 40,000+ transactions. RealFi uses a two-token model: USDr, a fully reserved dollar-pegged stablecoin backed 1:1 by real-world assets, and sUSDr, the staked yield-bearing instrument, with yield sourced from money market funds, corporate floating-rate bonds and direct fintech lending rather than token emissions. This is the nearest dated catalyst in the calendar and the first real test of whether Cardano can retain liquidity that arrives.

**What this means for the report's argument.** v3 said Cardano's binding constraint was the size of the liquidity base, and that the GMC could not fix it — only narrate it. That is now half-obsolete: the liquidity base has a funded owner for the first time. The GMC's role shifts to (a) making the ecosystem's real condition legible, honestly, while a large program spends against it, and (b) supplying narrative and distribution around milestones that are genuinely earned. It also creates an institutional tension worth naming up front: Intersect administers PRIME, and the GMC sits inside Intersect. The committee's credibility depends on not becoming PRIME's marketing department.

**Five headline findings:**

1. **The position deteriorated while the market rose.** Ex-anomaly volume −56%, TVL −24.5%, stablecoins flat, rank down five places, against a market up 18.5%. Any communication that opens with "momentum" will be checked and will fail.
2. **PRIME's own diagnosis matches this report's** — that the problem "is not simply low headline TVL" but fragmented and inefficient liquidity, thin advanced products, and low external distribution. Two independent analyses converging is a genuine signal.
3. **One protocol swung chain-level volume by \~3x in a month.** That is a direct warning about PRIME's performance fee, which is tied to "verified qualifying TVL growth." The attribution methodology deserves public scrutiny before Phase 3 (§3.3).
4. **The derivatives gap remains the structural ceiling.** Hyperliquid still clears more perps volume monthly than most chains' entire spot ecosystems, on a small TVL base. PRIME funds liquidity, not venues.
5. **Separate ecosystem KPIs from intervention KPIs.** Stablecoin supply and volume show whether the ecosystem is growing; they do not show whether any specific action caused it. §10 now splits them, with named owners on the second table.

### 2. What Changed Since July 2026

| **Metric**                          | **Jul 7, 2026** | **Sep 8, 2026** | **Change**   |
| ----------------------------------- | --------------- | --------------- | ------------ |
| Cardano DeFi TVL                    | $86.1M          | **$65.0M**      | −24.5%       |
| Chain rank by DeFi TVL              | #29 of 455      | **#34 of 466**  | −5 places    |
| Stablecoin supply on Cardano        | $67.6M          | **$66.9M**      | −1.0% (flat) |
| 30-day DEX volume (headline)        | $56.1M          | **$183.7M**     | +227%        |
| 30-day DEX volume (ex-Dano Finance) | \~$73.5M\*      | **\~$32.0M**    | −56%         |
| Global DeFi TVL                     | $74.1B          | **$87.8B**      | +18.5%       |

_\*Prior-period comparison uses the same 30-day windows reported by DefiLlama, with Dano Finance removed from both._

**On the volume anomaly.** Dano Finance recorded $151.8M of Cardano's $183.7M 30-day volume — a 945% month-over-month increase — while its 7-day volume fell 60% week-over-week and its 14-day-prior window ($32.3M) dwarfs its last 7 days ($4.1M). Whatever produced it (an incentive program, a migration, a one-off event, or wash activity — this report does not have the data to say which, and does not accuse anyone) it was concentrated, brief, and is over. Reporting Cardano's volume as "up 227%" without this context would be misleading and would be corrected in public within a day.

A comparable spike appears on XRPL (+146% month-over-month, also fading). August was genuinely a strong month for DeFi volume across the industry. Cardano's underlying activity moved the other way.

### 3. Cardano PRIME — What Was Approved

Governance Action ID 529dccaa…dc96d7#0. Submitted July 10, 2026 (epoch 642); concluded August 13, 2026 (epoch 649). Status: Ratified, Enacted. Author: Intersect. Source: [GovTool outcome page](https://gov.tools/outcomes/governance_actions/529dccaadaa000746c22f1682574cb3f436eeba4d19710b90791a54226dc96d7).

#### 3.1 The facts

<details>

<summary>Amount</summary>

**₳120,000,000** (USD figures in the proposal are planning references only, at a $0.16/ADA assumption)

</details>

<details>

<summary>Purpose</summary>

12-month community-overseen program to improve DeFi protocol readiness, responsibly activate incentives, and grow durable liquidity

</details>

<details>

<summary>Executor</summary>

AlphaGrowth, under Operating Group oversight.

</details>

<details>

<summary><strong>Custodian</strong></summary>

Intersect, as Constitutional Administrator, holding funds in a separate auditable account

</details>

<details>

<summary>Structure</summary>

Phase 1: public current-state audit → Phase 2: integration/product/ecosystem gap identification → Phase 3: incentives and capital deployment, released only after the Operating Group affirms the Phase 3 plan (Month 4 release gate)

</details>

<details>

<summary>Assurance</summary>

Dedicated **₳2,000,000** independent audit/assurance allocation

</details>

<details>

<summary>Safeguards</summary>

Six return-to-treasury triggers for unused, unearned, unreleased or excess funds; abstain delegation while funds are held; published recommendations and disbursement records; quarterly financial and ecosystem impact reporting

</details>

<details>

<summary>Performance fee</summary>

Tied to verified qualifying TVL growth, with ADA price effects and non-PRIME-attributable TVL excluded under a stated attribution methodology

</details>

<details>

<summary>Conditionality</summary>

Contingent on an applicable Net Change Limit under TREASURY-01a having capacity at enactment

</details>

<details>

<summary>Tooling</summary>

Sundae Labs treasury management smart contracts (TxPipe and MLabs audit reports published)

</details>

<details>

<summary>Prior funding</summary>

AlphaGrowth has not received Cardano Treasury funding in the prior 24 months

</details>

**The vote.** DReps: **76.15% yes (₳3.68B)** / **23.85% no (₳1.15B)**, against ₳10.30B abstaining and ₳15.14B total active stake. Constitutional Committee: 6 yes, 0 no, **6 did not vote** (12 active members). This passed with a clear DRep majority and meaningful dissent — nearly a quarter of participating stake opposed it, and half the CC did not vote. Communication that treats PRIME as settled community consensus will alienate the people who voted no or abstained.

#### 3.2 Why it matters to this report's argument

PRIME's stated motivation independently reaches the same conclusion as §5: infrastructure progress (it names USDCx, LayerZero, Pyth, Dune) has not converted into durable liquidity, and _"the core problem is not simply low headline TVL. It is fragmented liquidity, inefficient liquidity, limited advanced liquidity products, limited risk and insurance tooling, and low external distribution."_

That is the same diagnosis this report reached from the turnover data, and two separately-produced analyses converging on it is worth noting for DReps. PRIME also cites \~$90M TVL and \~$45M stablecoin supply as of June 2026; our September DefiLlama pull shows $65.0M and $66.9M. The TVL gap is two months of decline; the stablecoin gap is methodological (PRIME's figure appears narrower than DefiLlama's aggregate). **Anyone comparing PRIME's baseline to later results must use one methodology consistently** — something the program's own reporting should settle publicly and early.

**Lever 1 now has an owner.** v3 assigned "deepen the stablecoin and liquidity base" to "liquidity fund, Circle, RealFi, protocols" and concluded the GMC could only narrate it. PRIME is roughly four times the size of the $30M liquidity fund referenced in earlier drafts and is aimed squarely at that lever.

#### 3.3 The attribution problem

PRIME's performance fee is tied to verified qualifying TVL growth, excluding ADA price effects and non-PRIME-attributable TVL. That design is thoughtful and the exclusions are the right ones in principle. §2 shows why implementation will be hard:

* A single protocol moved chain-level 30-day DEX volume by roughly 3x in one month, then reversed.
* Cardano's TVL is small enough that ordinary protocol-level events swing chain-level percentages dramatically.
* Distinguishing PRIME-attributable liquidity from liquidity that would have arrived anyway (RealFi mainnet on 1 October, Cardinal bridge inflows, Leios, a market-wide rally) is genuinely difficult on a base this size — and the RealFi mainnet lands three weeks into PRIME's Phase 1, which makes clean attribution harder from the start, not later.

**The practical questions for DReps and ADA holders:** Is the attribution methodology published in full before Phase 3 capital deploys? Does it measure at protocol level with named sources, or at chain level? Does it distinguish incentivised TVL from retained TVL after incentives end? Does it survive a month like August 2026? These are answerable, with a defined deadline — the Month 4 gate, around **December 2026.**

This is not a criticism of PRIME's design. It is the observation that PRIME's own success metric sits on a base where measurement is unusually fragile, and that saying so early is more useful than saying so afterwards.

### 4. Where Cardano DeFi Stands Today

#### 4.1 Protocol inventory (September 8, 2026)

| **Protocol**                          | **Category**   | **30d DEX volume** | **Note**                                            |
| ------------------------------------- | -------------- | ------------------ | --------------------------------------------------- |
| Dano Finance                          | DEX            | $151.8M            | 83% of chain volume; +945% m/m, now collapsing (§2) |
| SundaeSwap V2                         | DEX            | $16.6M             | −66% m/m                                            |
| Minswap                               | DEX            | $7.7M              | −58% m/m; still the largest by TVL                  |
| WingRiders                            | DEX            | $7.4M              | +32% m/m                                            |
| Splash                                | DEX            | $0.26M             | <p><br></p>                                         |
| Liqwid                                | Lending        | —                  | Primary money market                                |
| Indigo                                | Synthetics/CDP | —                  | iUSD, iBTC                                          |
| FluidTokens                           | Lending/BTCfi  | —                  | Building the first BTC–ADA bridge                   |
| DeltaDeFi, Saturn, MuesliSwap, others | Mixed          | minimal            | Long tail                                           |
| Chain total                           | <p><br></p>    | $183.7M            | $32.0M excluding Dano                               |

Cardano DeFi remains **spot-DEX-dominated, with a thin lending layer, no perps venue of scale, and a volume profile one protocol can dominate.**

#### 4.2 Stablecoins — the growth stalled

$47M (March) → $67.6M (July) → $66.9M (September). The USDC-driven expansion that made v3's most encouraging chart has flattened. USDCx remains the largest stablecoin on the chain; USDM, USDA, DJED and iUSD make up the rest.

**RealFi's tokens are not yet in these figures.** USDr and sUSDr remain on testnet until 1 October 2026. When they arrive, note the distinction for reporting purposes: USDr is the fully reserved, non-yield-bearing dollar unit and will show up in stablecoin supply; sUSDr is the staked yield-bearing instrument and is a different thing to count. Conflating them — as earlier drafts of this report did — will produce wrong numbers in the scoreboard.

Stablecoin supply is the precondition for everything in §5, it is flat, and it is the metric PRIME is best positioned to move. It belongs at the top of the scoreboard.

#### 4.3 The honest negatives

* TVL −24.5% in two months while the market rose 18.5%.
* Underlying DEX volume roughly −56% ex-anomaly during an industry-wide volume surge.
* Stablecoin growth stalled.
* Chain rank down five places to #34.
* Consolidation is observable, not predicted: EMURGO wound down SecondFi earlier in 2026, and the long tail in §4.1 shows several protocols with negligible volume. The closure trend is evidenced by the closures themselves.
* Developer base remains small (\~672 active, \~276 full-time per Electric Capital's 2024 data) against 16,000+ new Ethereum and 11,500+ new Solana developers in Jan–Sep 2025 alone.

These are stated plainly because ADA holders will find them anyway, and because a report that only surfaces good news is worth nothing when PRIME's results are being judged.

### 5. What Actually Drives DeFi Volume

* **Liquidity depth → volume.** Traders route where slippage is lowest; thin pools punish size. This is why liquidity is the first lever, and why PRIME targeting it is the right target.
* **Stablecoins → everything.** Deep stable pairs are the precondition for market makers, arbitrage and derivatives collateral.
* **Derivatives multiply volume** — §6.3.
* **Catalysts spike, retention keeps.** August's Dano episode is a live demonstration: a spike that does not persist leaves nothing behind. RealFi's 1 October mainnet and PRIME's Phase 3 incentives both face this test.
* **Turnover beats TVL as a measure** — with the caveat in §6.2 that it is a crude proxy, and easily distorted on a small base.

### 6. How Cardano Compares

_All figures September 8, 2026, DefiLlama API, same methodology across chains._

#### 6.1 The benchmark table

| **Ecosystem**  | **DeFi TVL** | **Stablecoin supply** | **30d DEX volume**                  | **Turnover**             | **30d vol change**        |
| -------------- | ------------ | --------------------- | ----------------------------------- | ------------------------ | ------------------------- |
| Ethereum       | $49.46B      | $147.06B              | $36.09B                             | 0.73x                    | +27.2%                    |
| Solana         | $5.90B       | $16.31B               | $65.03B                             | 11.03x                   | +38.2%                    |
| TRON           | $5.30B       | $93.76B               | $1.29B                              | 0.24x                    | +23.7%                    |
| Hyperliquid L1 | $1.46B       | $7.08B                | (perps: \~$180–200B/mo, Q1–Q2 data) | \~120x                   | —                         |
| Stellar        | $0.253B      | $0.884B               | $29.77M                             | 0.12x                    | −40.5%                    |
| XRPL           | $42.0M       | $1.11B                | $246.5M                             | 5.87x                    | +145.6% (spike, fading)   |
| Cardano        | $65.0M       | $66.9M                | $183.7M (ex-anomaly $32.0M)         | 2.83x (ex-anomaly 0.49x) | +108.8% (ex-anomaly −56%) |

#### 6.2 What the comparison says now

**The turnover finding from v3 has weakened.** In July, Cardano turned over 0.65x against Ethereum's 0.64x — evidence that capital on Cardano worked as hard as capital anywhere. Today the honest ex-anomaly figure is 0.49x against Ethereum's 0.73x. The headline 2.83x is an artifact. The v3 claim should not be repeated in outbound material without this correction.

**A methodological caveat, raised by Marco Moshi in review and worth stating rather than burying.** Turnover is a crude proxy. What actually determines whether liquidity converts into usable volume is depth at price, spreads, liquidity concentration, routing quality, collateral mobility and execution quality — none of which the DefiLlama aggregate exposes. A chain can show respectable turnover while offering poor execution on any trade of size. Adding these measures properly needs per-pool order-book and slippage data; the monthly liquidity page (§7, Lever 1) is the natural place to build them, and doing so would make the comparison genuinely rigorous rather than merely consistent.

**Cardano still leads most of its peer set on TVL** ($65.0M vs XRPL $42.0M, Algorand $32.0M) but Stellar has pulled ahead at $253M, four times Cardano's — a reversal from July.

**XRPL remains the mirror image:** $1.11B of stablecoins, 17x Cardano's, supporting $246M of monthly DEX volume on just $42M of DeFi TVL. Large float, minimal application layer.

**TRON still shows the payments-only ceiling:** $93.8B in stablecoins, 0.24x turnover. "Attract stablecoins" remains necessary but visibly insufficient — directly relevant to how PRIME's success gets defined.

**Solana is the volume benchmark:** $65.0B monthly DEX volume on $5.9B TVL, turnover 11x. Capital that moves constantly — a UX-and-asset-velocity outcome, not a TVL outcome.

#### 6.3 Hyperliquid and the derivatives gap

Hyperliquid holds \~$1.46B in chain TVL — **under 3% of Ethereum's $49.46B** — while clearing roughly $180–200B per month in perps volume, with \~274,000 monthly active traders and \~$9B open interest (Q1–Q2 2026 third-party reporting; not from the September pull). Implied turnover is on the order of 120x.

The lesson is unchanged, and PRIME does not address it: a chain does not need a large liquidity base to generate enormous volume; it needs a venue people want to trade on. PRIME funds liquidity and protocol readiness, not venue construction. If Cardano's volume ceiling is structural, PRIME raises the floor without raising the ceiling — worth stating plainly, because expectations set now will be judged in twelve months.

#### 6.4 The honest peer set

For outbound communication the credible comparison set remains XRPL, Stellar, Algorand and Polkadot. Cardano now trails Stellar on TVL and leads XRPL and Algorand. Framing against Ethereum or Solana invites a comparison Cardano loses on every axis.

### 7. The Growth Levers

#### Lever 1 — Deepen the liquidity base (now funded: PRIME, ₳120M; GMC role is transparency, not execution)

The base is flat at $66.9M and PRIME exists to change that. The GMC's highest-value contribution is not amplification — it is a monthly, public, protocol-level state-of-liquidity page: stablecoin supply by issuer (counting USDr and sUSDr separately once live), TVL by protocol, DEX volume by protocol with anomalies flagged, and — per §6.2 — depth and spreads on top pairs as the data becomes available. Two reasons. Market makers evaluating Cardano need current numbers without doing archaeology; and a ₳120M program spending against these metrics needs an independent public record that predates its own reporting.

#### Lever 2 — Ride the catalyst calendar (highest direct GMC leverage)

{% stepper %}
{% step %}
### Aug 13, 2026

PRIME ratified and enacted
{% endstep %}

{% step %}
### Q3 2026

PRIME Phase 1 public current-state audit
{% endstep %}

{% step %}
### Oct 1, 2026

RealFi mainnet - USDr and sUSDr live
{% endstep %}

{% step %}
### H2 2026

Cardinal Bitcoin bridge - BTC inflow channel
{% endstep %}

{% step %}
### Dec 2026

PRIME Month 4 - Phase 3 release gate
{% endstep %}

{% step %}
### Late 2026

Leios mainnet target - throughput ceiling lifted
{% endstep %}

{% step %}
### H1 2027

PRIME Phase 3 deployment and measurement
{% endstep %}
{% endstepper %}

**RealFi's 1 October mainnet is the nearest dated catalyst and the most consequential near-term test.** The testnet drew 3,600+ participants and 40,000+ transactions, and the product is integrated with Lace. The explainer needs to get the mechanics right — USDr as the reserve-backed dollar unit, sUSDr as the staked yield instrument earning from money market funds, corporate floating-rate bonds and direct fintech lending rather than emissions. That distinction is the story: yield from real-world credit, not token printing. Getting it wrong in public would be worse than saying nothing, and earlier drafts of this report got it wrong.

PRIME's **Phase 1 public audit** is the other near-term content moment, and it requires no spin at all.

#### Lever 3 — Open the Bitcoin capital channel (owned by Cardinal/FluidTokens; amplified by GMC)

BTCfi (\~$4.1B, volatile) remains the largest liquidity pool Cardano can realistically tap, and Cardinal's trust-minimized design is a real differentiator against custodial wrapped BTC. Caution carried forward: one BTCfi segment contracted 74% within months, and §2 shows Cardano cannot currently retain a volume spike. Inflow without retention is a headline, not growth.

#### Lever 4 — Name the derivatives gap (structural; builders + future DRep decisions)

§6.3 is the argument. The GMC cannot build a perps venue and PRIME does not fund one. What the committee can do is keep the gap visible and evidenced for builders and DReps evaluating the next funding cycle. Interim substitutes within reach of current teams: synthetic exposure (Indigo) and structured products built on sUSDr yield once it is live.

#### Lever 5 — Activation and retention (GMC + protocols)

* **Aggregator-first UX messaging** — first-trade slippage is where chains lose newcomers permanently.
* **Yield legibility** — one public page, monthly, every yield source with risks stated: Liqwid rates, LP APRs, and sUSDr once live. Yield is why liquidity stays.
* **Objection kit** — the liquidity tracker with peer context, armed to ambassadors, builders and DReps. It must carry the bad months too.
* **Incentives discipline** — PRIME's Phase 3 will deploy incentives. The committee's test applies and is now concrete: do they test real demand, or rent temporary TVL? §2 is the cautionary case study.

#### Lever 6 — Narrative consolidation (GMC-owned)

One concentrated story beats ten diffuse ones. Cardano's credible frame remains **"the chain that never went down is becoming a liquid one"** — reliability, deterministic fees, a funded liquidity program, and from 1 October a yield product backed by real-world credit. Never argue "ghost chain" head-on; replace it with dated, verifiable milestones, including the negative ones. With ₳120M deployed and a two-month decline on the record, selective reporting is the fastest way to lose the audience this report is written for.

### 8. Sequencing

_Re-anchored to confirmed dates following review._

&#x20; P1 --> P2 --> P3<br>

* **Phase 1 (now → Q4 2026)** — legibility and pre-positioning while catalysts are still ahead. The liquidity page must exist before PRIME's Phase 3 spends, or there is no independent baseline.
* **Phase 2 (catalyst windows)** — anchored to the 1 October RealFi mainnet and the Leios year-end target, with PRIME's Month 4 gate (\~December) falling inside this window.
* **Phase 3 (H1 2027)** — retention and measurement. This is where PRIME's results become legible and where the difference between growth and rented liquidity shows up.

Skipping Phase 1 and simply "doing marketing" at launches produces spikes that decay to baseline — the standard failure mode, and one Cardano demonstrated in August.

### 9. Risks

| **Risk**                                          | **Consequence**                                                                          | **Mitigation**                                                                                                                |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| PRIME under-delivers visibly                      | A ₳120M spend with weak results becomes the definitive "ghost chain" datapoint for years | Set expectations on mechanism and milestones, never TVL targets; report monthly regardless of direction                       |
| Attribution methodology contested after the fact  | Performance-fee disputes; governance damage; DRep trust erosion                          | Push for full publication before Phase 3 capital deploys (§3.3)                                                               |
| RealFi mechanics misdescribed in public           | USDr/sUSDr confusion undermines the one clean story Cardano has this quarter             | Explainers reviewed against primary sources before publication; this report got it wrong twice before v5                      |
| Incentives rent TVL that leaves                   | Treasury cost without durable growth                                                     | Track retained vs incentivised TVL separately from Phase 3 onward                                                             |
| GMC perceived as PRIME's marketing arm            | Committee credibility collapses; DRep-education mandate compromised                      | Intersect administers PRIME and the GMC sits inside Intersect — report on PRIME, not for it, and say so in published material |
| A single protocol distorts headline metrics again | Misleading claims corrected in public                                                    | Report protocol-level always; flag anomalies in the same paragraph as the headline                                            |
| Volume decline continues through Phase 1–2        | Narrative hardens before PRIME can deploy                                                | Communicate the phase structure early so a quiet Q4 reads as designed, not as failure                                         |
| RealFi's ₳1B TVL target missed                    | A second falsifiable target missed in the same year                                      | Anchor on mechanism and shipped milestones; never repeat targets as promises                                                  |
| Peer comparisons cherry-picked                    | Credibility loss on correction                                                           | Use the §6.4 peer set; never claim parity with Ethereum or Solana                                                             |

### 10. The Scoreboard

Split into two tables following Marco Moshi's point that growth metrics do not show causation, and Sinan Kajan's suggested structure. Table A tells you whether the ecosystem is growing. Table B tells you whether the GMC did its job. They are not the same question, and conflating them is how marketing takes credit for markets.

#### Table A — Ecosystem KPIs (outcomes; no single owner)

Published monthly, negatives included, protocol-level. Independently checkable on DefiLlama and GovTool.

| **Metric**                     | **Baseline (Sep 8, 2026)**           | **Why it matters**                                             |
| ------------------------------ | ------------------------------------ | -------------------------------------------------------------- |
| Stablecoin supply on Cardano   | $66.9M (flat since July)             | The precondition; USDr counted separately from sUSDr once live |
| Cardano DeFi TVL               | $65.0M (−24.5% since July)           | Liquidity base; necessary, not sufficient                      |
| 30-day DEX volume, by protocol | $183.7M headline / $32.0M ex-Dano    | Headline alone is not evidence (§2)                            |
| Turnover, ex-anomaly           | 0.49x (Ethereum 0.73x, Solana 11.0x) | Capital productivity; crude proxy — see §6.2                   |
| Depth and spreads on top pairs | not yet measured                     | The measure that actually predicts usable volume               |
| Rank vs peer set               | Leads XRPL/Algorand; trails Stellar  | Honest comparables                                             |
| Retained vs incentivised TVL   | n/a until PRIME Phase 3              | The difference between growth and rented liquidity             |
| BTC bridged via Cardinal       | 0 (pre-launch)                       | Bitcoin channel adoption                                       |

#### Table B — Intervention KPIs (GMC outputs; named owner per line)

These are within the committee's control. Failure here is the committee's failure, and cannot be blamed on market conditions.

| **Intervention KPI**                               | **Target**                                                  | **Owner**                            |
| -------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------ |
| Explainers published ahead of each catalyst window | RealFi (before 1 Oct), Cardinal, Leios, PRIME Phase 1 audit | Content pipeline (Lara)              |
| First-trade activation paths live at launch        | Published day one of each catalyst                          | Content pipeline + protocol partners |
| State-of-liquidity page publication streak         | Unbroken monthly from Phase 1 onward                        | DeFi vertical lead (Andy)            |
| Tier-one media and analyst pickup vs baseline      | Baseline set in first monthly report                        | Analyst relations pillar             |
| Objection-kit distribution                         | Ambassadors, builders, DReps — tracked, not assumed         | GMC comms                            |
| Unprompted awareness of ≥2 pipeline milestones     | Baseline via Q3 community survey; re-run in two quarters    | Surveys (Thyme / Marco)              |
| Monthly recap includes negatives                   | Every edition, no exceptions                                | Monthly recap (Thyme)                |

**Realistic 12-month expectations.** With PRIME deploying and RealFi live, a credible success looks like: stablecoin supply in the low hundreds of millions, TVL recovering past its July level and beyond, ex-anomaly turnover above 1.0x, retained TVL materially exceeding incentivised TVL after Phase 3 incentives taper, and Cardano clearly leading its peer set. Not parity with Solana. Nothing here implies a token-price outcome, and PRIME's approval is not a prediction of its success — 23.85% of participating stake voted against it.

***

## Appendix — Data & Method Notes

* **TVL, stablecoin supply, DEX volume:** DefiLlama API (/v2/chains, /overview/dexs/{chain}, stablecoins.llama.fi/stablecoinchains), pulled September 8, 2026. Identical endpoints and methodology across every chain in §6. Chain TVL excludes liquid staking and double-counted categories.
* **Variance against other public reporting.** Reporting circulating around 7 September put Cardano TVL near $65.3M and stablecoin supply near $64.5M, against this report's $65.0M and $66.9M. The TVL figures agree within rounding; the stablecoin gap reflects which issuers are counted. Whichever source is used, it must be used consistently across periods — the same point that applies to PRIME's baseline (§3.2).
* **"Ex-anomaly" / "ex-Dano" figures** subtract Dano Finance's reported 30-day volume from Cardano's chain total in both current and prior windows. This is the report's own adjustment, not a DefiLlama metric, and is always shown alongside the unadjusted figure.
* **Turnover** = 30-day DEX volume ÷ chain DeFi TVL. Computed here for comparability; a crude proxy, with limitations set out in §6.2.
* **30-day windows** used throughout; Cardano's daily volume is too lumpy for 24-hour figures to mean anything.
* **RealFi:** mainnet date (1 October 2026, announced 2 September), two-token model (USDr reserve-backed and non-yield-bearing; sUSDr staked and yield-bearing, targeting up to 9% APY from money market funds, corporate floating-rate bonds and direct fintech lending), testnet participation (3,600+ participants, 40,000+ transactions) and Lace integration all verified against launch reporting and primary channels following review by Sinan Kajan (Cardano Foundation). Earlier versions of this report incorrectly described USDr itself as yield-bearing.
* **PRIME details:** GovTool outcome page for governance action 529dccaadaa000746c22f1682574cb3f436eeba4d19710b90791a54226dc96d7#0, read September 8, 2026 — amount, phases, safeguards, vote tallies and quoted motivation from on-chain metadata as displayed there. The full AlphaGrowth proposal PDF (IPFS-linked from that page) has not been read; §3 should be re-checked against it before publication.
* **Hyperliquid perps volume, trader counts, open interest:** Q1–Q2 2026 third-party reporting, not the September pull; dated separately and not comparable to the spot-DEX column.
* **Developer counts:** Electric Capital (2024 report; 2025 partial-year new-developer figures for Ethereum/Solana).
* **Project closures:** sourced to observable closures (EMURGO/SecondFi, 2026) rather than forward-looking commentary.

_Reviewers: Laura Mattiucci, Marco Moshi, Sinan Kajan (Cardano Foundation). Outstanding review items are listed in the handover note accompanying this version._

_References: DefiLlama (defillama.com); GovTool (gov.tools) governance action 529dccaa…dc96d7#0; RealFi (realfi.co, @realfi\_co) and 1 October mainnet launch reporting; "Cardano from Capability to Greater Adoption" (GMC, June 2026); Cardano Enterprise Adoption Strategic Framework; GMC 2026–2027 Strategic Pillars sheet; Electric Capital Developer Report; public reporting on Leios/Musashi Dojo, Cardinal/BitVMX, USDC-on-Cardano, and Hyperliquid perps market share._
