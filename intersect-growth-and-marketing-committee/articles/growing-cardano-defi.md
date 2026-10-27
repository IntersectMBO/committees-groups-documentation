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

No price commentary or predictions about ADA or any token. No endorsement of any proposal, proposer, protocol, or vendor, including PRIME, which is described here as an enacted fact of the landscape, not a recommendation. Ecosystem growth is the subject; token price is not.

</details>

<details>

<summary>Data snapshot: 27 October 2026</summary>

Pulled from the DefiLlama API. Refresh before publication if this slips materially.

</details>

<details>

<summary>v6 changes </summary>

**Corrections**

* USDr → USDrf, sUSDr → sUSDrf throughout, per docs.realfi.co.
* RealFi rewritten to past tense; launch outcome added (shipped on schedule, bump reversed in four weeks).
* All data refreshed to 27 October.<br>

**Data movement since 8 September**

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Metric</td><td>Sep 8</td><td>Oct 27</td></tr><tr><td>TVL</td><td>$65.0M</td><td>$58.3M</td></tr><tr><td>Rank</td><td>#34</td><td>#35</td></tr><tr><td>Stablecoins</td><td>$66.9M</td><td>$69.1M</td></tr><tr><td>30d volume</td><td>$183.7M (anomalous)</td><td>$42.53M (clean)</td></tr><tr><td>Turnover</td><td>0.49x ex-anomaly</td><td>0.73x</td></tr><tr><td>Global TVL</td><td>$87.8B</td><td>$88.5B</td></tr></tbody></table>



New findings: Dano anomaly fully resolved (now $17.0M vs Minswap $17.9M); Algorand's stablecoin supply ($100.8M) has passed Cardano's; Stellar's stablecoins fell to $410M; Hyperliquid data refreshed to Q3/October (Q3 perps volume $688.7B, 56% of on-chain OI).<br>

**Removed for publication**

* Version changelog and all "v3 said / v4 added" cross-references.
* Reviewer names and the handover-note reference.
* "Refresh before publication if this slips materially."
* The admission that the AlphaGrowth PDF hadn't been read (replaced with a positive statement of what §3 is sourced from — the GovTool metadata).
* Self-critical asides: "this report got it wrong twice before v5", "as earlier drafts did", etc.
* Table B owners changed from personal names (Lara, Andy, Thyme, Marco) to roles, pending consent to publish individual accountability.<br>

**Kept deliberately**

* The conflict-of-interest statement, moved up into the header. It is the reason a reader should trust the report and belongs in public.
* All negative findings, including the new one that Algorand has overtaken us on stablecoins.
* The §3.3 attribution scrutiny of PRIME's performance fee.
* The 23.85% dissent on the PRIME vote.<br>

**Formatting**

* All mermaid diagrams removed and rebuilt as tables and prose, since GitBook destroyed both of them. Nothing in v6 depends on diagram rendering.
* Byline restored: committee, version, date.

\
_&#x76;5 modifications:_

(1) RealFi corrected to its two-token model — USDr is the fully reserved, non-yield-bearing base stablecoin; sUSDr is the staked yield-bearing instrument. Earlier versions described USDr itself as yield-bearing, which was wrong; (2) RealFi mainnet date confirmed: 1 October 2026, announced publicly on 2 September, now used throughout; (3) sequencing restored and re-anchored to real dates — Phase 1 to Q4, Phase 2 to the 1 October mainnet and the Leios year-end target, Phase 3 into H1 2027; (4) scoreboard split into ecosystem KPIs and intervention KPIs with named owners (Sinan's suggestion, on Marco Moshi's attribution point); (5) project-closure claim re-sourced to the closures themselves rather than a personality quote; (6) Hyperliquid/Ethereum ratio made precise.



_Earlier: v4 added Cardano PRIME and refreshed all data to September; v3 added the rival-ecosystem benchmark at Laura's request. Laura's "update with the AlphaGrowth" comment is addressed in_

</details>

### 1. Executive summary

Three things have happened since the summer, and they do not point the same way.<br>

Cardano DeFi has kept shrinking. TVL is $58.3M, down from $65.0M in early September and $86.1M in early July — a 32% fall across the period — and the chain now ranks #35 by DeFi TVL. Over the same stretch the global DeFi market grew from $74.1B to $88.5B. Cardano has been losing ground in absolute terms and in share.<br>

RealFi shipped on schedule, and the launch bump has already gone. RealFi reached Cardano mainnet on 1 October 2026, on the date announced a month earlier — a milestone delivered when promised, which is worth saying plainly. Launch-period reporting put the lift to Cardano's TVL at roughly 8–9%, to around $70–71M. Four weeks later TVL is $58.3M: below the pre-launch level. Stablecoin supply did rise modestly, from $66.9M to $69.1M, consistent with USDrf arriving while other capital left. This is the report's "catalysts spike, retention keeps" thesis playing out in real time, on Cardano's most significant launch of the year.<br>

Trading activity, though, improved — and that is new. Cardano's 30-day DEX volume is $42.5M, up 47.7% on the prior 30 days, in a month when Ethereum's fell 14%, Solana's 22% and TRON's 23%. The August volume anomaly this report flagged has fully resolved: Dano Finance is now $17.0M against Minswap's $17.9M, ordinary concentration rather than a 945% spike. And because volume held up while TVL fell, Cardano's capital turnover is back to 0.73x against Ethereum's 0.77x — near parity. That ratio improving partly because its denominator shrank is not unambiguously good news, but the numerator moved the right way against a falling market, and this is the first clearly positive signal in four versions of this report.<br>

Five findings:

1. The liquidity base is still eroding — TVL −32% since July while the market grew \~19%. This remains the binding constraint and nothing in the quarter changed it.
2. A launch alone does not retain liquidity. RealFi delivered on time and the TVL it attracted did not stay four weeks. Any plan that assumes catalysts produce durable growth is now disproved on Cardano's own data.
3. Volume and turnover are genuinely improving, against the market's direction, on clean data with the anomaly resolved.
4. The derivatives gap is the unchanged structural ceiling. Hyperliquid cleared roughly $689B of perps in Q3 on a $2.4B TVL base. PRIME funds liquidity, not venues.
5. Judge PRIME on intervention outcomes, not chain metrics. §10 separates ecosystem KPIs from intervention KPIs for exactly this reason.

***

### 2. What has changed

| Metric                       | 7 Jul 2026 | 8 Sep 2026 | 27 Oct 2026 |
| ---------------------------- | ---------- | ---------- | ----------- |
| Cardano DeFi TVL             | $86.1M     | $65.0M     | $58.3M      |
| Chain rank by DeFi TVL       | #29        | #34        | #35         |
| Stablecoin supply on Cardano | $67.6M     | $66.9M     | $69.1M      |
| 30-day DEX volume            | $56.1M     | $183.7M\*  | $42.5M      |
| Turnover (volume ÷ TVL)      | 0.65x      | 0.49x\*    | 0.73x       |
| Global DeFi TVL              | $74.1B     | $87.8B     | $88.5B      |

<br>

\*September's headline volume was distorted by a single protocol; the comparable ex-anomaly figures were \~$32.0M and 0.49x. October's figures need no adjustment.<br>

The September anomaly has resolved. Dano Finance recorded $151.8M of Cardano's $183.7M September volume, a 945% month-on-month spike. It now stands at $17.0M over 30 days, beside Minswap's $17.9M. The spike was transient, as this report said at the time, and the current volume distribution is ordinary.<br>

What RealFi's launch did and did not do. Mainnet went live 1 October. Stablecoin supply rose $2.2M across the period. TVL fell $6.7M. Reporting around the launch described an 8–9% TVL lift that has since fully reversed. The report does not have protocol-level attribution data to separate RealFi's contribution from other flows, and does not claim it: what can be said is that total TVL is lower than before the launch, and that the launch did not arrest the decline.<br>

***

### 3. Cardano PRIME

Governance Action 529dccaa…dc96d7#0. Submitted 10 July 2026 (epoch 642); concluded 13 August 2026 (epoch 649). Status: Ratified, Enacted. Author: Intersect. Details below are taken from the on-chain governance metadata published on [GovTool](https://gov.tools/outcomes/governance_actions/529dccaadaa000746c22f1682574cb3f436eeba4d19710b90791a54226dc96d7).

#### 3.1 What was approved

| Item            | Detail                                                                                                                                                                                                                                  |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Amount          | ₳120,000,000 (USD figures in the proposal are planning references at a $0.16/ADA assumption)                                                                                                                                            |
| Purpose         | 12-month community-overseen program to improve DeFi protocol readiness, responsibly activate incentives, and grow durable liquidity                                                                                                     |
| Executor        | AlphaGrowth, under Operating Group oversight                                                                                                                                                                                            |
| Custodian       | Intersect, as Constitutional Administrator, holding funds in a separate auditable account                                                                                                                                               |
| Structure       | Phase 1 public current-state audit → Phase 2 integration, product and ecosystem gap identification → Phase 3 incentives and capital deployment, released only after the Operating Group affirms the Phase 3 plan (Month 4 release gate) |
| Assurance       | Dedicated ₳2,000,000 independent audit and assurance allocation                                                                                                                                                                         |
| Safeguards      | Six return-to-treasury triggers for unused, unearned, unreleased or excess funds; abstain delegation while funds are held; published recommendations and disbursement records; quarterly financial and ecosystem impact reporting       |
| Performance fee | Tied to verified qualifying TVL growth, with ADA price effects and non-PRIME-attributable TVL excluded under a stated attribution methodology                                                                                           |
| Conditionality  | Contingent on an applicable Net Change Limit under TREASURY-01a having capacity at enactment                                                                                                                                            |
| Tooling         | Sundae Labs treasury management smart contracts (TxPipe and MLabs audit reports published)                                                                                                                                              |
| Prior funding   | AlphaGrowth has not received Cardano Treasury funding in the prior 24 months                                                                                                                                                            |

The vote. DReps: 76.15% yes (₳3.68B) / 23.85% no (₳1.15B), against ₳10.30B abstaining and ₳15.14B total active stake. Constitutional Committee: 6 yes, 0 no, 6 did not vote of 12 active members. PRIME passed with a clear DRep majority and meaningful dissent — nearly a quarter of participating stake opposed it, and half the Constitutional Committee did not vote. It should not be described as settled community consensus.

#### 3.2 Where PRIME and this report agree

PRIME's stated motivation reaches the same conclusion this report reached independently from the turnover data: infrastructure progress — it names USDCx, LayerZero, Pyth and Dune — has not converted into durable liquidity, and "the core problem is not simply low headline TVL. It is fragmented liquidity, inefficient liquidity, limited advanced liquidity products, limited risk and insurance tooling, and low external distribution."

<br>

Two separately produced analyses converging on that diagnosis is a signal worth weighing. PRIME cites roughly $90M TVL and $45M stablecoin supply as of June 2026; this report's October pull shows $58.3M and $69.1M. The TVL gap is four months of decline. The stablecoin gap is methodological — PRIME's figure counts a narrower set of issuers than DefiLlama's aggregate. Whichever source is used, it must be used consistently across periods, and the program's own reporting should state which it uses.

#### 3.3 Where the attribution problem sits

PRIME's performance fee is tied to verified qualifying TVL growth, excluding ADA price effects and non-PRIME-attributable TVL. The design is careful and the exclusions are the right ones in principle. The difficulty is measurement, and the last two months have demonstrated it twice:



* One protocol moved chain-level 30-day volume roughly threefold in September, then reversed entirely by October.
* RealFi's mainnet launch coincided with a reported 8–9% TVL lift that disappeared inside four weeks, with no public protocol-level breakdown to attribute either direction.
* On a $58M base, ordinary protocol events move chain-level percentages more than most interventions will.



The questions that matter, with a deadline. Is the attribution methodology published in full before Phase 3 capital deploys? Does it measure at protocol level with named sources, or at chain level? Does it separate incentivised TVL from TVL retained after incentives end? Would it have produced a defensible answer for September or for October? PRIME's Month 4 gate falls around December 2026, which makes these answerable now rather than in arrears.



This is not a criticism of PRIME's design. It is the observation that PRIME's success metric sits on a base where measurement is unusually fragile, and that the fragility is better addressed before the money moves.

***

### 4. Where Cardano DeFi stands

#### 4.1 Protocol inventory, 30-day DEX volume (27 October 2026)

| Protocol                   | Category         | 30d volume | Share       | Change m/m           |
| -------------------------- | ---------------- | ---------- | ----------- | -------------------- |
| Minswap                    | DEX              | $17.94M    | 42%         | +98.6%               |
| Dano Finance               | DEX              | $16.98M    | 40%         | +31.9%               |
| WingRiders                 | DEX              | $2.89M     | 7%          | −56.4%               |
| SundaeSwap V3              | DEX              | $2.37M     | 6%          | new adapter          |
| SundaeSwap V4              | DEX              | $1.89M     | 4%          | new adapter          |
| Splash                     | DEX              | $0.33M     | <1%         | +81.7%               |
| SundaeSwap V2              | DEX              | $0.08M     | <1%         | +30.1%               |
| Saturn, MuesliSwap, others | DEX              | $0.05M     | <1%         | —                    |
| Liqwid                     | Lending          | —          | —           | primary money market |
| Indigo                     | Synthetics / CDP | —          | —           | iUSD, iBTC           |
| FluidTokens                | Lending / BTCfi  | —          | —           | BTC–ADA bridge work  |
| Chain total                | <p><br></p>      | $42.53M    | <p><br></p> | +47.7%               |

<br>

Cardano DeFi remains spot-DEX dominated, with a thin lending layer and no perpetuals venue of scale. The concentration problem has eased — two protocols at roughly 40% each rather than one at 83% — but the chain still has no venue in the product category that generates most of DeFi's trading volume.

#### 4.2 Stablecoins

$47M (March) → $67.6M (July) → $66.9M (September) → $69.1M (October). Supply is up 3.3% on the quarter and up 47% on the year, but the steep USDC-driven climb of the spring has not resumed.

RealFi's tokens are now live, and the naming matters. RealFi uses a dual-token model, and the tickers carry an "f":

* USDrf — a reserve-backed digital dollar built for capital stability, operational liquidity and everyday transactions. This is the unit that appears in stablecoin supply.
* sUSDrf — the staked efficiency layer. Staking USDrf into the protocol gives exposure to yield generated from a diversified portfolio of real-world assets, rather than from token emissions.

These are two different instruments and must be counted separately in any scoreboard. The distinction — yield from real-world credit rather than inflationary rewards — is also the substance of the story, and getting the mechanics right is worth more than getting them out quickly.

#### 4.3 The negatives, stated plainly

* TVL down 32% since July while the global market grew about 19%.
* Chain rank down six places since July, to #35.
* The RealFi launch bump reversed inside four weeks, leaving TVL below its pre-launch level.
* Stablecoin growth has slowed to a 3.3% quarterly crawl.
* Algorand's stablecoin supply, at $100.8M, now exceeds Cardano's $69.1M — Cardano no longer leads its nearest peer on the metric that gates everything else.
* Consolidation is observable rather than forecast: EMURGO wound down SecondFi earlier in 2026, and the long tail in §4.1 shows several protocols with negligible volume.
* The developer base remains small: roughly 672 active and 276 full-time on Electric Capital's 2024 figures, against 16,000+ new Ethereum developers and 11,500+ new Solana developers in January–September 2025 alone.

These are published because readers will find them anyway, and because a report that surfaces only good news is worth nothing when a ₳120M program's results are being judged against it.

***

### 5. What actually drives DeFi volume

Volume is produced by a small number of forces, each with a precondition:

| Driver                           | Precondition                          | Why it matters here                                                                                                                               |
| -------------------------------- | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Liquidity depth                  | Deep stablecoin supply                | Traders route where slippage is lowest; thin pools punish size. This is why liquidity is the first lever, and why PRIME aims at the right target. |
| Market makers and arbitrage      | Liquidity depth                       | Depth is what makes quoting profitable; without it, no one quotes.                                                                                |
| Derivatives and perpetuals       | Deep stable collateral, fast finality | Perps generate multiples of spot volume per dollar of TVL — §6.3.                                                                                 |
| New assets and launch moments    | A pipeline of things to trade         | Catalysts create spikes. Whether volume stays depends on yield and UX — and October shows it did not stay.                                        |
| Active traders and aggregator UX | Access and good execution             | First-trade slippage is where chains lose newcomers permanently.                                                                                  |



Turnover is the useful summary measure — volume divided by TVL, showing how productive the capital is — with the caveat in §6.2 that it is a crude proxy and easily distorted on a small base.

***

### 6. How Cardano compares

All figures 27 October 2026 from the DefiLlama API, same endpoints and methodology across chains.

#### 6.1 Benchmark

| Ecosystem      | DeFi TVL | Stablecoin supply | 30d DEX volume  | Turnover | 30d volume change |
| -------------- | -------- | ----------------- | --------------- | -------- | ----------------- |
| Ethereum       | $48.47B  | $142.69B          | $37.14B         | 0.77x    | −14.0%            |
| Solana         | $5.71B   | $15.61B           | $61.13B         | 10.70x   | −22.1%            |
| TRON           | $5.43B   | $93.94B           | $1.64B          | 0.30x    | −23.2%            |
| Hyperliquid L1 | $2.40B   | $6.89B            | perps, see §6.3 | \~96x    | —                 |
| Stellar        | $230.4M  | $410.0M           | $80.42M         | 0.35x    | +26.4%            |
| XRPL           | $39.3M   | $1.04B            | $164.79M        | 4.19x    | −17.8%            |
| Cardano        | $58.3M   | $69.1M            | $42.53M         | 0.73x    | +47.7%            |
| Algorand       | $32.7M   | $100.8M           | —               | —        | —                 |

#### 6.2 What it says

Cardano's capital productivity is back near Ethereum's. 0.73x against 0.77x, on clean data with no anomaly adjustment. In September the comparable figures were 0.49x against 0.73x. The caveat is that a ratio can improve because its denominator shrank, and Cardano's TVL did shrink — but volume rose 47.7% in a month when the three largest chains all fell double digits, so the numerator moved on its own merits.

A methodological limit, worth stating rather than burying. Turnover is a crude proxy. What actually determines whether liquidity becomes usable volume is depth at price, spreads, liquidity concentration, routing quality, collateral mobility and execution quality — none of which a chain-level aggregate exposes. A chain can post respectable turnover while offering poor execution on any trade of size. Measuring this properly requires per-pool order-book and slippage data; the monthly liquidity page in §7 is the natural place to build it.

Cardano's position within its peer set has weakened. Stellar holds four times Cardano's TVL. XRPL does nearly four times Cardano's monthly volume on two-thirds of its TVL. And Algorand's stablecoin supply has now passed Cardano's. On TVL, Cardano still leads XRPL and Algorand; on the stablecoin base it now trails both Algorand and Stellar.

TRON still marks the ceiling of the payments-only model — $93.9B of stablecoins, 0.30x turnover. Attracting stablecoins is necessary and visibly insufficient, which is directly relevant to how PRIME's success gets defined.

Solana remains the volume benchmark — $61.1B monthly on $5.7B of TVL, turnover 10.7x. Capital that moves constantly, which is a UX and asset-velocity outcome rather than a TVL outcome.

#### 6.3 Hyperliquid and the derivatives gap

Hyperliquid holds about $2.40B in chain TVL — under 5% of Ethereum's — and cleared roughly $688.7B of perpetuals volume in Q3 2026, about 38.6% of all on-chain perpetuals volume. As of 26 October it held about 56% of on-chain perpetuals open interest at roughly $7.55B, and its share of global perpetuals open interest including centralised venues reached a record 11.8% in early October. Implied turnover is on the order of 96x.

The lesson is unchanged, and PRIME does not address it: a chain does not need a large liquidity base to generate enormous volume; it needs a venue people want to trade on. PRIME funds liquidity and protocol readiness, not venue construction. If Cardano's volume ceiling is structural, PRIME raises the floor without raising the ceiling.

The honest counterweight is that perpetuals volume is reflexive and concentrated, Hyperliquid's own open interest is down 6.6% over 30 days, and building a competitive venue requires deep stable collateral, fast finality, serious risk engineering and a committed team. This is a direction of travel, not a shortcut.

#### 6.4 The honest peer set

For outbound communication the credible comparison set is XRPL, Stellar, Algorand and Polkadot — chains of similar DeFi scale. Cardano leads some of that set on TVL and trails it on stablecoin supply. Framing Cardano against Ethereum or Solana invites a comparison it loses on every axis.

***

### 7. The growth levers

#### Lever 1 — Deepen the liquidity base

Funded: PRIME, ₳120M. The committee's role here is transparency, not execution.

The base is $69.1M and crawling; PRIME exists to change that. The committee's highest-value contribution is not amplification but a monthly, public, protocol-level state-of-liquidity page: stablecoin supply by issuer with USDrf counted separately from sUSDrf, TVL by protocol, volume by protocol with anomalies flagged in the same line as the headline, and depth and spreads on top pairs as that data becomes available. Market makers assessing Cardano need current numbers without doing archaeology, and a ₳120M program measured on these metrics needs an independent public record that predates its own reporting.

#### Lever 2 — Work the catalyst calendar

| Date        | Event                                            | Status                                            |
| ----------- | ------------------------------------------------ | ------------------------------------------------- |
| 13 Aug 2026 | PRIME ratified and enacted                       | Done                                              |
| Q3 2026     | PRIME Phase 1 public current-state audit         | Due; not yet publicly visible as of this snapshot |
| 1 Oct 2026  | RealFi mainnet — USDrf and sUSDrf live           | Delivered on schedule                             |
| H2 2026     | Cardinal Bitcoin bridge — BTC inflow channel     | Pending                                           |
| Dec 2026    | PRIME Month 4 — Phase 3 release gate             | Upcoming                                          |
| Late 2026   | Leios mainnet target — throughput ceiling lifted | Target                                            |
| H1 2027     | PRIME Phase 3 deployment and measurement         | Upcoming                                          |

The lesson from 1 October is the one to carry forward. RealFi shipped on the date it promised and the liquidity it attracted did not stay a month. Launch amplification without a retention path produces a chart that returns to where it started. The next two catalysts — the Cardinal bridge and Leios — should each ship with a published first-trade path and a reason to stay, not only an announcement.

PRIME's Phase 1 audit is the other near-term moment, and it requires no spin at all. Its publication is itself a checkable milestone.

#### Lever 3 — Open the Bitcoin capital channel

Owned by the Cardinal and FluidTokens teams; amplified by the committee.

BTCfi remains the largest liquidity pool Cardano can realistically reach, and Cardinal's trust-minimised design is a genuine differentiator against custodial wrapped BTC. The caution now has local evidence: Cardano did not retain the RealFi launch inflow, and one BTCfi segment contracted 74% within months elsewhere. Inflow without retention is a headline, not growth.

#### Lever 4 — Name the derivatives gap

Structural; depends on builders and future DRep funding decisions.

§6.3 is the argument. The committee cannot build a perpetuals venue and PRIME does not fund one. What the committee can do is keep the gap visible and evidenced for builders and for DReps assessing the next funding cycle. Interim substitutes within reach of existing teams: synthetic exposure through Indigo, and structured products built on sUSDrf yield now that it is live.

#### Lever 5 — Activation and retention

* Aggregator-first routing in all onboarding material — first-trade slippage is where chains lose newcomers permanently.
* Yield legibility — one public page, refreshed monthly, covering every yield source with its risks stated: Liqwid rates, LP APRs, and sUSDrf.
* Objection kit — the liquidity tracker with peer context, distributed to ambassadors, builders and DReps, carrying the bad months as well as the good.
* Incentives discipline — PRIME's Phase 3 will deploy incentives. The test is concrete and now evidenced twice: do they test real demand, or rent temporary TVL?

#### Lever 6 — Narrative consolidation

One concentrated story beats ten diffuse ones. Cardano's defensible frame is a chain that has never halted, now building the liquidity to match — reliability, deterministic fees, a funded liquidity program, and a live yield product backed by real-world credit rather than emissions. The "ghost chain" label should not be argued with head-on; it should be answered with dated, verifiable milestones, including the ones that went the wrong way. With ₳120M committed and a 32% TVL decline on the record, selective reporting is the fastest way to lose the readers this report is written for.

***

### 8. Sequencing

Phase 1 — now to end of Q4 2026. Legibility and pre-positioning. The state-of-liquidity page must exist before PRIME's Phase 3 spends, or there is no independent baseline to measure against. Deliverables: liquidity page live and monthly, objection kit distributed, Cardinal explainer prepared, PRIME Phase 1 audit covered on publication.

Phase 2 — catalyst windows, Q4 2026 into Q1 2027. Anchored to the Cardinal bridge and the Leios year-end target, with PRIME's Month 4 gate around December falling inside this window. Every catalyst ships with a published first-trade path and a retention story, which is the specific lesson of 1 October.

Phase 3 — H1 2027. Retention and measurement. Retained versus incentivised TVL reported separately; PRIME Phase 3 outcomes reported independently of PRIME's own reporting; the derivatives-gap case put to builders and DReps.

Skipping Phase 1 and simply marketing the launches produces spikes that decay to baseline. Cardano has now demonstrated that twice in two months.

***

### 9. Risks

| Risk                                             | Consequence                                                                            | Mitigation                                                                                                                           |
| ------------------------------------------------ | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| PRIME under-delivers visibly                     | A ₳120M spend with weak results becomes the defining "ghost chain" datapoint for years | Set expectations on mechanism and milestones, never on TVL targets; report monthly regardless of direction                           |
| Attribution methodology contested after the fact | Performance-fee disputes, governance damage, erosion of DRep trust                     | Publish the methodology in full before Phase 3 capital deploys (§3.3)                                                                |
| Incentives rent TVL that leaves                  | Treasury cost without durable growth                                                   | Track retained versus incentivised TVL separately from Phase 3 onward                                                                |
| Committee perceived as PRIME's marketing arm     | Credibility collapses; the DRep-education mandate is compromised                       | Intersect administers PRIME and this committee sits inside Intersect — report on PRIME, not for it, and say so in published material |
| Launch amplification without retention           | Repeats 1 October: a bump that reverses in weeks                                       | Every catalyst ships with a first-trade path and a reason to stay                                                                    |
| A single protocol distorts headline metrics      | Misleading claims corrected in public                                                  | Report at protocol level always; flag anomalies in the same line as the headline                                                     |
| Token mechanics misdescribed                     | USDrf and sUSDrf confusion undermines the clearest story Cardano has                   | Verify against primary documentation before publishing, not after                                                                    |
| Peer comparisons cherry-picked                   | Credibility loss on correction                                                         | Use the §6.4 peer set; never claim parity with Ethereum or Solana                                                                    |

***

### 10. The scoreboard

Growth metrics show whether the ecosystem is growing. They do not show whether any particular action caused it. The two tables below are kept separate for that reason: Table A reports outcomes no single party controls, Table B reports work this committee is accountable for. Conflating them is how marketing takes credit for markets.

#### Table A — Ecosystem KPIs

Published monthly, negatives included, at protocol level. Independently checkable on DefiLlama and GovTool.

| Metric                           | Baseline (27 Oct 2026)                                                          | Why it matters                                         |
| -------------------------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------ |
| Stablecoin supply on Cardano     | $69.1M (+3.3% on the quarter)                                                   | The precondition; USDrf counted separately from sUSDrf |
| Cardano DeFi TVL                 | $58.3M (−32% since July)                                                        | The liquidity base; necessary, not sufficient          |
| 30-day DEX volume, by protocol   | $42.53M (+47.7%)                                                                | Headline alone is not evidence (§2)                    |
| Turnover                         | 0.73x (Ethereum 0.77x, Solana 10.7x)                                            | Capital productivity; a crude proxy — see §6.2         |
| Depth and spreads on top pairs   | not yet measured                                                                | The measure that actually predicts usable volume       |
| Rank within peer set             | Leads XRPL and Algorand on TVL; trails both Stellar and Algorand on stablecoins | Honest comparables                                     |
| Retained versus incentivised TVL | n/a until PRIME Phase 3                                                         | The difference between growth and rented liquidity     |
| BTC bridged via Cardinal         | 0 (pre-launch)                                                                  | Bitcoin channel adoption                               |

#### Table B — Intervention KPIs

Within the committee's control. Failure here cannot be attributed to market conditions.

| Intervention KPI                                        | Target                                                   | Owner                                   |
| ------------------------------------------------------- | -------------------------------------------------------- | --------------------------------------- |
| Explainers published ahead of each catalyst window      | Cardinal, Leios, PRIME Phase 1 audit                     | Content pipeline                        |
| First-trade activation path live at launch              | Published day one of each catalyst                       | Content pipeline with protocol partners |
| State-of-liquidity page publication streak              | Unbroken monthly from Phase 1 onward                     | DeFi vertical lead                      |
| Tier-one media and analyst pickup against baseline      | Baseline set in the first monthly report                 | Analyst relations                       |
| Objection-kit distribution                              | Ambassadors, builders, DReps — tracked, not assumed      | Committee communications                |
| Unprompted awareness of two or more pipeline milestones | Baseline via community survey; re-run after two quarters | Community surveys                       |
| Monthly recap includes negatives                        | Every edition, without exception                         | Monthly recap                           |

What success would look like in twelve months. Stablecoin supply in the low hundreds of millions; TVL recovered past its July level and climbing; turnover sustained above 1.0x; retained TVL materially exceeding incentivised TVL once Phase 3 incentives taper; and Cardano clearly leading its peer set rather than trailing parts of it. Not parity with Solana. Nothing here implies a token-price outcome, and PRIME's approval is not a prediction of its success — 23.85% of participating stake voted against it.

***

### Appendix — data and method

* TVL, stablecoin supply and DEX volume: DefiLlama API (/v2/chains, /overview/dexs/{chain}, stablecoins.llama.fi/stablecoinchains), pulled 27 October 2026. Identical endpoints and methodology across every chain in §6. Chain TVL excludes liquid staking and double-counted categories.
* Turnover = 30-day DEX volume ÷ chain DeFi TVL. Computed here for comparability; it is not an official DefiLlama metric and its limitations are set out in §6.2.
* 30-day windows are used throughout. Cardano's daily volume is too concentrated for 24-hour figures to carry meaning.
* September's anomaly adjustment, referenced in §2, subtracted Dano Finance's reported 30-day volume from the chain total in both the current and prior windows. October's figures require no adjustment.
* RealFi: mainnet launch date and the USDrf / sUSDrf dual-token model are taken from RealFi's own documentation at docs.realfi.co. Launch-period TVL impact is from third-party reporting and is not independently verified at protocol level.
* PRIME: amount, phases, safeguards, vote tallies and the quoted motivation are from the on-chain governance metadata published on GovTool for action 529dccaadaa000746c22f1682574cb3f436eeba4d19710b90791a54226dc96d7#0.
* Hyperliquid: Q3 2026 perpetuals volume and volume share from quarterly reporting published 21 October 2026; open interest and share as of 26 October 2026 from Castle Labs' perpetuals DEX tracker; global open-interest share from reporting dated 4 October 2026. These are third-party figures, not from the DefiLlama pull, and are not directly comparable to the spot-DEX column.
* Developer counts: Electric Capital (2024 report, with 2025 partial-year new-developer figures for Ethereum and Solana).
* Project closures: sourced to observable closures rather than forward-looking commentary.



References: DefiLlama; GovTool; RealFi documentation (docs.realfi.co); Castle Labs perpetuals DEX rankings; "Cardano from Capability to Greater Adoption" (Growth & Marketing Committee, June 2026); Cardano Enterprise Adoption Strategic Framework; Electric Capital Developer Report.
