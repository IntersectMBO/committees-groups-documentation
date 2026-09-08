# RFP 03: Stablecoin Liquidity Incentive and Activation Strategy

Tender type: Request for Proposals

Issued by: Cardano Product Committee / Intersect

Research portfolio: Product Research Initiatives

Final publication date, submission deadline, clarification window, expected project period, submission method, and contact will be confirmed on the Product Research Initiatives - Grants page before the call opens.

***

## 1. Executive Summary

### Strategic question

What stablecoin liquidity should Cardano stakeholders pay to create, in which venues, through which incentive mechanisms, and under what measurable conditions to produce durable depth rather than temporary mercenary capital?

### Evidence gap

Cardano has a growing stablecoin stack, including USDCx, USDM, USDA, DJED, and iUSD, but liquidity depth remains thin across major assets and venues. Slippage at meaningful trade sizes remains a barrier for DeFi users, enterprise settlement, payments in emerging markets, and RWA-related activity. Applicants should verify the current status, backing model, issuer, venue access, and liquidity conditions of each asset as of submission.

The evidence gap is not whether more stablecoin liquidity would be useful. The live gap is operational: where liquidity is missing, which users and use cases actually require it, whether the bottleneck is on-chain depth, centralized exchange access, market-maker participation, demand weakness, or venue fragmentation, and which incentive design would be least gameable.

### Decision unlocked

This research should enable Cardano stakeholders to decide whether to fund, defer, condition, or reject stablecoin liquidity incentives, what outcomes to pay for, which assets and venues to prioritize, what KPI thresholds should trigger funding or renewal, and when incentive spending should be withheld because demand, venue access, or monitoring quality is insufficient.

### Expected outputs

The selected vendor will produce a stablecoin liquidity baseline, venue and asset gap analysis, peer benchmark, market-maker and exchange access assessment, incentive model comparison, liquidity incentive scorecard, demand-side validation memo, implementation roadmap, monitoring framework, executive decision memo, final research report, public summary, and cross-RFP handoff memo. The executive decision memo must treat defer or no-fund recommendations as valid outcomes where evidence does not support incentive spending.

### Requirement priority

The required core is to answer the decision gates with traceable evidence and produce the required decision outputs. Optional methods, templates, or stretch work should be separated from the core scope and budget. This RFP is research and strategy work. It is not the liquidity incentive pool itself.

***

## 2. Strategic Context

The Cardano Product Committee has received funding to commission a portfolio of product research initiatives aligned with Cardano's long-term product direction and Strategy 2030 priorities. The purpose of the portfolio is to define the evidence Cardano needs before making product, adoption, funding, partnership, and strategic decisions.

Stablecoin liquidity is a cross-cutting prerequisite for several adoption pathways. DeFi users require low-slippage swap routes and reliable stable pairs. Enterprise settlement and RWA activity may require predictable stable-value settlement, sufficient depth, and credible off-ramp or exchange access. Emerging-market payments use cases may require stablecoin availability at transaction sizes that matter to merchants, consumers, remittance flows, or local operators.

This RFP should not become a generic stablecoin market report. The purpose is to determine what concrete liquidity outcomes Cardano stakeholders should fund, which venues matter, what measurable KPI should be used, and how to avoid paying for activity that disappears as soon as rewards stop.

The research should inform the Cardano Product Committee and the broader Cardano ecosystem, including DeFi protocols, liquidity providers, market makers, stablecoin issuers, exchanges, wallet teams, enterprise and RWA teams, emerging-market payment operators, grant allocators, and future research vendors.

***

## 3. Research Problem Statement

Cardano lacks a decision-ready view of stablecoin liquidity depth, venue constraints, incentive options, and demand-side requirements.

Liquidity discussions often collapse several different problems into one claim that Cardano "needs more stablecoin liquidity." That framing is not sufficient for procurement or funding decisions. Cardano stakeholders need to know:

* which stablecoin assets and pairs lack depth;
* whether the relevant venue is DeFi pools, centralized exchange order books, market-maker arrangements, bridges, wallets, payment rails, or another access point;
* what slippage and spread thresholds matter at defined trade or settlement sizes;
* whether incentives should target TVL, slippage, quoted depth, spreads, volume, transactions, user retention, integrations, or outcome milestones;
* whether the real blocker is supply-side liquidity, weak demand, fragmented venues, missing exchange access, pool design, asset trust, issuer constraints, or commercial terms;
* what monitoring method can distinguish durable liquidity from reward-seeking capital that exits once incentives stop.

This creates a strategic problem:

* incentive funding may reward raw TVL without improving usable depth;
* market-maker or exchange arrangements may be pursued without clear KPI triggers;
* DeFi liquidity may improve while enterprise or payment needs remain unserved;
* stablecoin assets may be treated as interchangeable even where trust, backing, venue access, or use case differs;
* apparent liquidity growth may be driven by short-term incentives rather than sustained demand;
* adjacent RFPs may assume stablecoin liquidity is available without specifying the depth, venue, or reliability required.

The selected vendor must close this evidence gap by producing a practical liquidity incentive and activation strategy grounded in measurable depth, venue requirements, demand validation, peer comparison, and anti-gaming controls.

***

## 4. Definitions

For this RFP:

**Stablecoin liquidity** means the ability to buy, sell, swap, settle, or use stablecoin assets at relevant trade or transaction sizes with acceptable slippage, spread, reliability, and venue access.

**Depth** means available executable liquidity at defined price impact or spread thresholds. Depth should not be treated as identical to TVL unless the vendor explains why TVL is a valid proxy for the decision being made.

**Slippage** means the difference between expected and executed price for a swap or trade at a defined size.

**Spread** means the difference between quoted buy and sell prices, especially relevant to order-book or market-maker environments.

**Venue** means the location or mechanism where stablecoin liquidity is accessed, including DeFi pools, centralized exchange order books, market makers, OTC arrangements, bridges, wallets, payment rails, or aggregator routes.

**Liquidity incentive** means any funding, reward, subsidy, commercial arrangement, or program designed to increase stablecoin depth, reduce slippage, improve spread availability, increase reliable execution, or support adoption tied to stablecoin usage.

**Mercenary liquidity** means liquidity that enters primarily to capture rewards and exits when rewards end, without producing durable depth, recurring usage, or stronger market structure.

**Demand-side validation** means evidence that specific users, applications, operators, or use cases require stablecoin liquidity at defined depth, asset, and venue conditions.

The selected vendor may refine these definitions during the research design phase, but revised definitions must remain measurable and decision-useful.

***

## 5. Objectives

The selected vendor will be expected to:

1. Establish a stablecoin liquidity baseline across major Cardano stablecoin assets, pairs, pools, routes, and relevant venues.
2. Identify the depth, slippage, spread, reliability, and access requirements for priority Cardano use cases, including DeFi, enterprise settlement, emerging-market payments, and RWA-related activity.
3. Diagnose whether liquidity constraints are primarily on-chain, centralized exchange-related, market-maker-related, issuer-related, demand-side, or venue-fragmentation problems.
4. Benchmark Cardano's stablecoin liquidity conditions against relevant peer ecosystems where comparable evidence is available.
5. Evaluate incentive models, including TVL targets, slippage reduction, quoted spread availability, transaction volume, volume quality, retained depth, integrations, or outcome-based milestones.
6. Recommend which KPI or KPI bundle Cardano stakeholders should pay for, by asset and venue where relevant.
7. Define anti-gaming safeguards and monitoring methods that can detect wash activity, circular volume, short-term reward farming, and liquidity exit after incentives end.
8. Validate which user segments and use cases actually require stablecoin liquidity, at what depth, in which venues, and on what timeline.
9. Produce a 6, 12, and 24-month implementation roadmap with depth targets, candidate activation pathways, funding triggers, review points, and stop conditions.
10. Identify findings that should be handed to adjacent Product Research Initiative RFPs.

***

## 6. Decision Gates

Applicants must design their methodology around the following decision gates. A proposal that does not map methods and deliverables to these gates will be considered weak fit for this RFP.

| Decision Gate                                                                                                                                           | Evidence Required                                                                                                                                                                           | YES Means                                                                                  | NO Means                                                               | Action Unlocked                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| What stablecoin liquidity depth does Cardano need for priority use cases?                                                                               | Use-case-specific transaction or settlement size assumptions, slippage and spread thresholds, operator interviews, DeFi usage evidence, enterprise/RWA/payment requirements where available | Priority use cases can be translated into measurable liquidity requirements                | Liquidity needs remain too vague to justify incentive spending         | Define target depth and execution thresholds by use case                    |
| Where is stablecoin liquidity missing today?                                                                                                            | Asset, pair, route, pool, exchange, and market-maker baseline with data sources, dates, and limitations                                                                                     | Cardano has a measurable current-state liquidity map                                       | The ecosystem cannot tell which gaps matter most                       | Prioritize assets, venues, and routes for intervention                      |
| Is the main bottleneck on-chain liquidity, centralized exchange access, market-maker participation, issuer constraints, venue fragmentation, or demand? | Venue analysis, stakeholder interviews, issuer and market-maker evidence, CEX access assessment, user demand evidence                                                                       | The problem can be segmented by constraint type                                            | A single broad incentive program risks paying for the wrong problem    | Choose the right intervention type by venue and asset                       |
| Which incentive model is least gameable and most tied to useful depth?                                                                                  | Comparison of TVL, slippage, spread, quoted depth, retained liquidity, transaction volume, integration, and outcome-based models                                                            | CPC can pay for outcomes that improve usable liquidity                                     | Incentives may reward vanity metrics or short-term farming             | Select KPI design, monitoring method, and funding trigger                   |
| Which venues should Cardano prioritize first?                                                                                                           | DeFi pool analysis, centralized exchange and market-maker feasibility, user route analysis, cost and execution assessment                                                                   | Some venues have higher decision value and feasibility                                     | Venue selection remains speculative or politically driven              | Sequence DeFi, CEX, market-maker, wallet, bridge, or payment interventions  |
| Which stablecoin assets should be prioritized for activation?                                                                                           | Asset-by-asset liquidity, trust, issuer status, venue access, demand, and use-case relevance                                                                                                | Priority assets can be identified with evidence                                            | Asset selection risks fragmenting incentives or ignoring user trust    | Allocate attention and incentives by asset and pair                         |
| Is there enough demand to justify liquidity incentives?                                                                                                 | Demand-side validation from DeFi users, protocols, enterprise/RWA operators, payment use cases, wallets, exchanges, and relevant external comparators                                       | Incentives can be tied to use cases with plausible recurring usage                         | Liquidity incentives risk creating supply without users                | Decide whether to fund, defer, or condition incentives on demand milestones |
| What 6, 12, and 24-month roadmap should Cardano follow?                                                                                                 | Depth targets, venue sequencing, candidate programs, KPI thresholds, budget scenarios, monitoring plan, and stop/renewal conditions                                                         | CPC can move from research to fundable activation                                          | Findings do not support an implementation plan                         | Approve a staged liquidity activation strategy                              |
| Which findings should be handed to other RFPs?                                                                                                          | Boundary analysis across customer segmentation, use-case landscape, government/emerging markets, enterprise/RWA, L2/interoperability, brand, and delivery partners                          | Adjacent RFPs receive stablecoin assumptions and constraints without duplicating this work | Stablecoin findings remain siloed or scope creeps across the portfolio | Produce clean cross-RFP handoffs                                            |

***

## 7. Scope of Work

### In scope

The selected vendor should cover:

* stablecoin liquidity baseline across major Cardano stablecoin assets and relevant venues;
* asset, pair, route, pool, and venue analysis;
* slippage and depth benchmarks at defined transaction sizes;
* spread and quoted depth analysis where order-book or market-maker evidence is available;
* peer ecosystem comparison where comparable evidence can be obtained;
* DeFi, centralized exchange, market-maker, issuer, bridge, wallet, and payment access constraints;
* demand-side validation for priority use cases;
* incentive model comparison;
* monitoring and anti-gaming framework;
* 6, 12, and 24-month implementation roadmap;
* cross-RFP handoff notes;
* public and confidential reporting.

### Venue scope guidance

Applicants should propose a venue taxonomy and explain how it supports the decision gates.

Relevant venues may include:

* Cardano DeFi pools;
* aggregators and route providers;
* centralized exchange order books;
* market-maker or OTC arrangements;
* issuer-side liquidity or redemption mechanisms;
* bridge or wrapped-asset routes where relevant;
* wallet or payment access layers;
* merchant, remittance, or settlement flows where relevant.

The RFP does not require equal depth across every possible venue. Applicants should explain which venues receive deep analysis, which receive light screening, and why.

For each analyzed venue, the vendor should assess:

* current liquidity condition;
* relevant asset and pair coverage;
* slippage, spread, or executable depth where measurable;
* data availability and reliability;
* user or operator demand;
* feasibility of intervention;
* likely cost driver;
* gaming or retention risk;
* monitoring method;
* recommended funding trigger or stop condition.

### Out of scope and handoff boundaries

This RFP should remain focused on stablecoin liquidity depth, venue strategy, incentive design, demand validation, and implementation sequencing. It may identify findings relevant to other Product Research Initiatives, but it should not attempt to fully answer those initiatives.

| Topic                           | In Scope for This RFP                                                                             | Out of Scope for This RFP                                                       |
| ------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Customer segmentation           | Identify stablecoin-dependent user and operator groups where needed for demand validation         | Full customer segmentation and persona model                                    |
| Use-case landscape              | Identify use cases that require stablecoin depth and define their liquidity needs                 | Full vertical landscape or chain-by-chain use-case audit                        |
| Enterprise and RWA              | Stablecoin depth and venue requirements for enterprise/RWA settlement where evidence is available | Full enterprise readiness, compliance, SLA, or production-conversion assessment |
| Government and emerging markets | Stablecoin liquidity requirements for payments, remittances, or settlement in relevant markets    | Country-level strategy, regulatory playbooks, or government entry strategy      |
| L2 and interoperability         | Bridge or cross-chain venue constraints where they affect stablecoin liquidity                    | Full interoperability demand study or technical bridge strategy                 |
| Brand awareness                 | Trust or credibility issues only where they affect stablecoin adoption or asset preference        | Full awareness or perception study                                              |
| Delivery partners               | Partner/channel needs only where they affect liquidity activation or market access                | Full delivery partner network design                                            |
| Incentive program execution     | Define incentive design, KPI triggers, and monitoring requirements                                | Running the liquidity incentive program unless separately commissioned          |

Findings that materially affect another research initiative should be captured in the Cross-RFP Handoff Memo rather than expanded inside this RFP.

### Optional / nice-to-have stretch scope

Applicants may propose optional stretch scope, priced separately, such as:

* deeper exchange or market-maker commercial feasibility research;
* more extensive peer ecosystem benchmarking;
* detailed simulation of incentive models under different liquidity behavior assumptions;
* design of a pilot incentive program template;
* dashboard specification for ongoing liquidity monitoring;
* additional interviews with emerging-market payment operators or RWA/enterprise counterparties;
* public workshop or ecosystem briefing on liquidity KPI design.

***

## 8. Required Methodology

The selected vendor must use a mixed-method research design. Desk research alone is not sufficient.

The methodology should include:

* liquidity pool and route analysis;
* venue mapping;
* slippage, spread, and depth measurement at defined sizes;
* peer benchmarking where comparable evidence is available;
* primary research with DeFi protocols, stablecoin issuers, liquidity providers, market makers, exchanges, wallets, enterprise/RWA operators, payment operators, or relevant user groups;
* demand-side validation;
* incentive model analysis;
* anti-gaming and monitoring design;
* evidence confidence ratings;
* decision-gate mapping.

### Core research hypotheses

Applicants should test, refine, or reject hypotheses such as:

| Hypothesis                                                             | What Must Be Tested                                                                                                                           | Decision Relevance                                     |
| ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| Stablecoin liquidity needs differ by use case                          | Whether DeFi, enterprise settlement, payments, and RWA activity require different assets, venues, depth, spreads, and slippage thresholds     | Prevents a one-size-fits-all incentive program         |
| Cardano's liquidity problem differs by asset and venue                 | Whether each stablecoin faces different depth, trust, access, issuer, market-maker, or demand constraints                                     | Guides asset and venue prioritization                  |
| Raw TVL is not a sufficient KPI                                        | Whether TVL correlates with usable depth, low slippage, recurring usage, and post-incentive retention                                         | Avoids paying for misleading metrics                   |
| Market-maker or exchange access may be as important as DeFi pool depth | Whether order-book depth, spreads, integrations, or market-maker arrangements are required for priority use cases                             | Shapes intervention type and budget logic              |
| Demand may be the limiting factor in some venues                       | Whether more liquidity would produce actual usage or sit idle without demand-side activation                                                  | Prevents incentives from creating supply without users |
| Incentives can be designed to reduce gaming risk                       | Whether KPI design, measurement windows, retention tests, and payment triggers can limit wash activity, circular volume, and liquidity flight | Makes funding conditions enforceable                   |
| A staged roadmap is preferable to a single large program               | Whether evidence supports pilot, scale, and renewal gates over 6, 12, and 24 months                                                           | Enables phased funding and stop conditions             |

### Required evidence types

| Evidence Type                    | Required Use                                                                               | Notes                                                 |
| -------------------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------- |
| Liquidity baseline data          | Establish current state by asset, pair, pool, route, and venue                             | Required                                              |
| Slippage and depth analysis      | Measure executable liquidity at defined transaction sizes                                  | Required where data is available                      |
| Spread and quoted depth analysis | Assess CEX or market-maker quality where relevant                                          | Required where order-book or MM evidence is available |
| Peer benchmark                   | Compare Cardano with relevant ecosystems where comparable data exists                      | Required where comparable evidence can be obtained    |
| Stakeholder interviews           | Explain constraints, demand, venue feasibility, and incentive risks                        | Required                                              |
| Demand-side validation           | Confirm which users and use cases require stablecoin liquidity at what depth               | Required                                              |
| Incentive model comparison       | Compare KPI options, gaming risk, cost logic, and monitoring burden                        | Required                                              |
| Public-source triangulation      | Check claims against dashboards, pool data, exchange data, documentation, or other sources | Required where possible                               |
| Proprietary or paid data         | May improve analysis if access and limitations are disclosed                               | Optional; requires validation                         |

### Primary research expectations

Applicants must include primary validation. The proposal should explain:

* who will be interviewed;
* why those respondents are relevant;
* how respondents map to assets, venues, or use cases;
* how non-Cardano or peer ecosystem perspectives will be included where useful;
* how commercially sensitive information will be handled;
* how conflicting incentives among issuers, liquidity providers, protocols, exchanges, and market makers will be managed.

Indicative respondent categories may include:

| Respondent Category                                      | Indicative Range | Purpose                                                                                        |
| -------------------------------------------------------- | ---------------: | ---------------------------------------------------------------------------------------------- |
| Cardano DeFi protocols, aggregators, or liquidity venues |          \[8-15] | Understand current pool depth, routing, demand, incentive history, and measurement constraints |
| Stablecoin issuers or issuer-adjacent stakeholders       |           \[3-8] | Understand asset-specific constraints, trust, redemption, supply, and venue access             |
| Market makers, liquidity providers, or trading firms     |          \[5-10] | Assess commercial terms, KPI design, spread/depth requirements, and gaming risks               |
| Centralized exchange, listing, or order-book experts     |           \[3-8] | Assess CEX access, quoted depth, market structure, and integration constraints                 |
| Demand-side users and operators                          |         \[10-20] | Validate depth requirements for DeFi, enterprise/RWA, payments, or emerging-market use cases   |
| Peer ecosystem or external experts                       |           \[3-8] | Benchmark incentive models and liquidity activation patterns                                   |
| Total suggested range                                    |         \[32-69] | To be justified by applicant scope and budget                                                  |

Applicants may propose a different sample, but they must explain why it is sufficient to answer the decision gates.

### Liquidity measurement requirements

The vendor should define and justify measurement methods for:

* slippage at defined trade sizes;
* executable depth at defined price impact thresholds;
* pool depth by asset and pair;
* route quality through aggregators where relevant;
* order-book depth and spreads where accessible;
* stablecoin pair fragmentation;
* liquidity retention over time;
* volume quality and suspected wash or circular activity;
* relationship between liquidity depth and actual usage.

Every metric must include source, date or measurement window, method, and limitations.

Applicants must not invent Cardano ecosystem statistics. If a data source is incomplete, unavailable, paid, proprietary, or uncertain, the proposal must mark it "requires validation."

### Benchmarking requirements

The benchmark should compare Cardano's stablecoin liquidity conditions with relevant peer ecosystems where data is comparable. Peers may include Ethereum mainnet, Ethereum L2s, Solana, Avalanche, Cosmos chains, or other ecosystems where justified by stablecoin venue relevance.

Applicants must explain:

* why each peer was selected;
* which assets, venues, or routes are being compared;
* what transaction sizes or spread/depth thresholds are used;
* what evidence supports each comparison;
* where data is public versus proprietary;
* what confidence level should be attached to each benchmark;
* what limitations apply.

The benchmark must compare practical liquidity conditions, not just public narratives about ecosystem size or DeFi maturity.

### Incentive model analysis

The vendor should compare incentive models such as:

* TVL or supplied liquidity targets;
* slippage reduction at defined trade sizes;
* quoted depth at defined price bands;
* maximum spread availability;
* volume or transaction targets;
* retained liquidity after incentive periods;
* integration or route availability milestones;
* market-maker service-level arrangements;
* outcome-based milestones tied to use-case activation;
* hybrid models combining depth, usage, retention, and anti-gaming controls.

For each model, the vendor should assess:

* what it pays for;
* what behavior it may induce;
* how it can be gamed;
* how it can be monitored;
* what data is required;
* whether it fits DeFi, CEX, market-maker, payment, or enterprise/RWA contexts;
* whether payment should be upfront, milestone-based, time-weighted, or renewal-based;
* what stop condition should apply.

### Adoption and retention signal standard

The research must distinguish durable liquidity from cosmetic or temporary activity.

Examples of stronger liquidity and adoption signals include:

* lower slippage at defined trade sizes over a sustained measurement window;
* quoted depth or spread availability that persists beyond incentive periods;
* recurring stablecoin swaps tied to identifiable use cases;
* retained liquidity after rewards step down;
* increased route reliability through wallets, aggregators, or payment flows;
* market-maker commitments with measurable service levels;
* stablecoin usage by DeFi protocols, enterprises, RWA operators, payment operators, or merchants;
* new integrations that produce recurring transactions rather than announcements only;
* reduced execution friction for operators who previously avoided Cardano due to stablecoin depth.

Examples of weak or cosmetic signals include:

* TVL growth without executable depth;
* volume that appears circular, wash-like, or reward-farming driven;
* short-lived deposits that exit immediately after rewards;
* liquidity concentrated in routes users do not use;
* one-off transactions or campaigns without retention;
* announcements of liquidity programs without measurable depth or usage;
* market-maker claims without auditable service-level evidence;
* demand claims based only on Cardano insider sentiment.

### Bias controls

Applicants must describe controls for:

* Cardano insider bias;
* issuer or asset favoritism;
* protocol self-interest;
* market-maker conflict of interest;
* exchange access opacity;
* paid or proprietary data limitations;
* TVL overinterpretation;
* wash activity and circular volume;
* overclaiming from thin usage data;
* treating liquidity supply as proof of demand.

Required controls should include:

* separation of public evidence, confidential evidence, and vendor judgment;
* confidence labels for major findings;
* source traceability;
* clear data limitations;
* stakeholder conflict disclosure;
* independent triangulation where possible;
* explicit rejected or deferred recommendations.

### What should not count as evidence

The following should not be treated as sufficient evidence:

* generic claims that Cardano needs more liquidity;
* raw TVL without executable depth or slippage analysis;
* volume without user, route, or quality interpretation;
* market-maker assertions without KPI or monitoring method;
* exchange access claims without commercial or operational specificity;
* Cardano community sentiment presented as demand-side validation;
* peer comparisons based only on ecosystem narratives;
* incentive recommendations without gaming-risk analysis;
* all-positive asset recommendations;
* recommendations that do not map to decision gates;
* statistics without source, date, methodology, and limitations.

***

## 9. Expected Deliverables

Deliverables are grouped into core decision outputs, supporting research outputs, and public/community-facing outputs.

### Core decision outputs

| Deliverable                            | Description                                                                                                     | Format                           | Purpose                                                                                   | Acceptance Criteria                                                                                                                                                                   |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------- | -------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Executive Decision Memo                | Short synthesis of what Cardano should fund, defer, or avoid                                                    | PDF/doc, max \[8] pages          | Give CPC and ecosystem stakeholders the decision answer without requiring the full report | States recommended intervention type, priority assets and venues, KPI triggers, stop conditions, cost logic, confidence level, and next actions                                       |
| Stablecoin Liquidity Baseline          | Current-state map of stablecoin liquidity by asset, pair, route, pool, and relevant venue                       | Spreadsheet/table plus narrative | Establish the factual baseline of current stablecoin liquidity conditions                 | Includes source, date, method, slippage/depth measures where available, data limitations, and confidence label for each major asset or venue                                          |
| Use-Case Liquidity Requirements Matrix | Definition of liquidity requirements for priority use cases                                                     | Matrix/table                     | Translate DeFi, enterprise/RWA, payments, and other use cases into measurable depth needs | Defines relevant asset, venue, transaction or settlement size assumption, slippage/spread threshold, reliability requirement, evidence source, and confidence level                   |
| Venue and Bottleneck Gap Analysis      | Diagnosis of whether constraints are on-chain, CEX, market-maker, issuer, demand-side, or fragmentation-related | Table plus narrative             | Select the right intervention type                                                        | Each gap includes affected asset/venue, evidence basis, likely constraint, feasible intervention, dependency, and confidence level                                                    |
| Incentive Model Comparison             | Comparison of potential incentive mechanisms and KPI designs                                                    | Scored table plus memo           | Decide what Cardano stakeholders should pay for                                           | Compares TVL, slippage, depth, spread, volume, retention, integration, market-maker SLA, and outcome-based models; includes gaming risk, monitoring method, cost logic, and venue fit |
| Liquidity Incentive Scorecard          | Recommended incentive type by venue and asset                                                                   | Decision scorecard               | Turn research into fundable program design                                                | Includes target KPI, measurement method, payment trigger, renewal trigger, stop condition, anti-gaming safeguard, required data, and risk rating                                      |
| Demand-Side Validation Memo            | Evidence on which users and use cases actually need stablecoin liquidity                                        | Memo plus evidence table         | Prevent supply-side incentives without demand                                             | Identifies user segments/use cases, required asset and venue, depth threshold, evidence source, adoption dependency, and weak/rejected demand claims                                  |
| Implementation Roadmap                 | 6, 12, and 24-month staged activation plan                                                                      | Roadmap table plus narrative     | Sequence pilots, scaling, monitoring, and renewal decisions                               | Includes depth targets, candidate activation pathways, budget scenarios, dependencies, review cadence, KPI thresholds, and anti-gaming checks                                         |

### Supporting research outputs

| Deliverable                                 | Description                                                                    | Format               | Purpose                                                 | Acceptance Criteria                                                                                                                                                                                    |
| ------------------------------------------- | ------------------------------------------------------------------------------ | -------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Research Methodology Appendix               | Full explanation of methods, samples, data sources, and limitations            | Appendix             | Make findings auditable                                 | Lists measurement methods, respondent categories, sample counts, data sources, source limitations, bias controls, and analysis method                                                                  |
| Peer Benchmark Appendix                     | Comparison against relevant peer ecosystems                                    | Appendix/table       | Show practical competitive gap in stablecoin liquidity  | Explains peer selection, comparable assets/venues, metrics, data sources, confidence levels, and limitations                                                                                           |
| Market-Maker and Exchange Access Assessment | Assessment of MM, LP, OTC, and CEX constraints                                 | Memo/table           | Identify commercial and operational routes to depth     | Separates verified evidence from vendor judgment; includes commercial feasibility, likely constraints, monitoring options, and confidentiality treatment                                               |
| Monitoring and Anti-Gaming Framework        | Measurement design for incentive oversight                                     | Framework/table      | Make incentive spending enforceable                     | Defines data inputs, metric formulas or logic, wash/circular activity checks, retention windows, audit cadence, dashboard needs, and escalation triggers                                               |
| Evidence Register                           | Source-by-source record supporting major claims                                | Spreadsheet/table    | Preserve traceability                                   | Every major factual claim in core outputs maps to a source, interview, dataset, or explicit vendor judgment                                                                                            |
| Cross-RFP Handoff Memo                      | Findings that should inform other Product Research Initiative RFPs             | Memo, max \[5] pages | Keep RFP 3 focused while preserving useful dependencies | Maps findings to customer segmentation, use-case landscape, enterprise/RWA, government/emerging markets, L2/interoperability, brand, or delivery partner research; explains why the issue is a handoff |
| Final Research Report                       | Full research report covering methods, findings, evidence, and recommendations | PDF/doc              | Provide the complete research record                    | Includes executive summary, methodology, baseline, demand validation, venue gaps, incentive comparison, scorecard, roadmap, monitoring plan, limitations, and recommendations                          |

### Public and community-facing outputs

| Deliverable       | Description                                                    | Format                       | Purpose                                                                 | Acceptance Criteria                                                                                                                                                                           |
| ----------------- | -------------------------------------------------------------- | ---------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Presentation Deck | Decision-ready presentation for CPC and ecosystem stakeholders | Slide deck                   | Support review, discussion, and communication                           | Covers strategic question, baseline, venue gaps, incentive options, demand validation, roadmap, risks, and recommended actions                                                                |
| Public Summary    | Non-confidential version suitable for publication              | Markdown/PDF, max \[5] pages | Share useful findings while protecting sensitive commercial information | Includes key findings, methodology overview, public liquidity and incentive recommendations, evidence caveats, and excludes confidential commercial terms or sensitive respondent information |

***

## 10. Acceptance Criteria

Each deliverable must be decision-useful, evidence-based, and traceable.

All deliverables must meet the following standards:

* every factual claim must be traceable to a source, interview, dataset, or explicit vendor judgment;
* Cardano evidence must be separated from peer ecosystem evidence;
* public evidence, confidential evidence, and vendor interpretation must be clearly distinguished;
* liquidity metrics must include source, date or measurement window, method, and limitations;
* slippage, spread, depth, TVL, and volume must not be treated as interchangeable;
* recommendations must specify affected asset, venue, KPI, measurement method, funding trigger, and stop condition;
* demand-side claims must identify who needs the liquidity, at what depth, in which venue, and for what use case;
* incentive designs must include anti-gaming safeguards;
* roadmap recommendations must include 6, 12, and 24-month review logic;
* weak, unsupported, deferred, or no-fund recommendations must be explicitly identified where evidence requires them.

A submission should fail acceptance review if it:

* only says Cardano needs more stablecoin liquidity;
* recommends incentives without a KPI and monitoring method;
* treats TVL as sufficient evidence of usable liquidity;
* omits demand-side validation;
* ignores centralized exchange, market-maker, or venue-specific constraints where relevant;
* provides all-positive asset or venue recommendations;
* does not identify gaming risks;
* makes claims based on data CPC cannot inspect without labeling confidence and access limitations;
* does not map findings to decision gates;
* duplicates adjacent RFP scopes without handoff boundaries.

CPC may reject final deliverables if the vendor cannot show sufficient evidence for recommended funding triggers, unless the absence of evidence is itself clearly explained and leads to a defer or no-fund recommendation.

***

## 11. Vendor Eligibility

Applicants may be research firms, consultancies, ecosystem analysts, DeFi analytics teams, market-structure specialists, independent researchers, academic teams, or consortia. Subcontracting is permitted where responsibilities are clearly defined.

Applicants should demonstrate:

* Web3 liquidity, DeFi, market structure, or exchange research capability;
* ability to analyze liquidity pools, routes, slippage, spreads, and depth;
* understanding of stablecoin assets, issuers, venues, and market-maker dynamics;
* ability to conduct primary research with commercially sensitive respondents;
* ability to compare Cardano against relevant peer ecosystems;
* ability to design measurable incentive KPIs and monitoring controls;
* ability to translate research into fundable program design;
* ability to communicate findings for both CPC and public ecosystem audiences.

Preferred but not mandatory capabilities include:

* prior stablecoin liquidity or DeFi incentive research;
* market-maker, liquidity provider, or exchange access;
* dashboard or analytics design experience;
* emerging-market payments or enterprise/RWA settlement experience;
* experience assessing incentive gaming, wash activity, or retention.

Cardano ecosystem familiarity is useful but not sufficient. Teams must also show market-structure knowledge and willingness to test Cardano assumptions against external evidence.

***

## 12. Proposal Submission Requirements

Applicants must follow the shared Submission Pack and include the common documents: cover letter, technical proposal, budget proposal, team credentials, evidence access plan, ethics/data handling statement, and conflicts declaration.

Applicants bidding on multiple Product Research Initiative RFPs must disclose shared staffing, shared respondent recruitment, shared evidence collection, and any assumptions that could create respondent fatigue or duplicated outreach.

For this RFP, the technical proposal must also include:

* liquidity measurement plan covering depth, slippage, spreads, routes, and retention where relevant;
* asset and venue analysis plan;
* demand-side validation plan;
* incentive model assessment approach;
* monitoring and anti-gaming design;
* treatment of proprietary, paid, exchange, market-maker, issuer, or protocol data.

Budgets should explain how cost relates to data access, market-maker or exchange access, analytics tooling, specialist expertise, and decision value.

## 13. Evaluation Guidance

Proposals will be assessed using the CPC standard research grant evaluation framework: Fit to Grant Objectives, Team Capability, Proposal Quality and Execution Plan, and Cost Efficiency. The full scoring framework is maintained on the shared evaluation page.

For this RFP, strong fit means the proposal can measure current stablecoin liquidity conditions, identify bottlenecks by asset and venue, validate which use cases need what depth, compare incentive models, and recommend measurable funding triggers with anti-gaming controls.

A strong proposal should define depth, slippage, spread, TVL, volume, and retention clearly; compare DeFi, CEX, market-maker, issuer, bridge, wallet, and payment constraints where relevant; include demand-side validation; and include stop conditions as well as funding triggers.

Proposals should score lower if they assume the answer is simply to fund more liquidity, treat TVL or volume as sufficient evidence, omit demand validation, avoid weak/no-fund recommendations, or fail to disclose data limitations and conflicts.

Cost should be judged against evidence value, not lowest price. Higher-cost proposals may be justified by stronger data access, better market-maker or exchange access, deeper peer benchmarking, or stronger monitoring design.

## 14. Timeline and Milestones

Final calendar dates will be confirmed on the Product Research Initiatives - Grants page before the call opens.

| Milestone                        | Target Date / Timing      | Purpose                                                                                                                                      |
| -------------------------------- | ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| RFP publication                  | Confirmed on grants page  | Open call for proposals                                                                                                                      |
| Clarification window opens       | Confirmed on grants page  | Applicants may submit questions                                                                                                              |
| Clarification window closes      | Confirmed on grants page  | Final clarification responses issued                                                                                                         |
| Proposal deadline                | Confirmed on grants page  | Applicant submissions due                                                                                                                    |
| Award notification               | Confirmed on grants page  | Selected vendor notified                                                                                                                     |
| Kickoff                          | Project week 1            | Confirm objectives, decision gates, workplan, communication cadence, and confidentiality expectations                                        |
| Research design alignment        | Applicant-proposed timing | Align on assets, venues, metrics, data sources, respondent categories, benchmark approach, and confidentiality expectations before fieldwork |
| Liquidity baseline review        | Applicant-proposed timing | Review current-state liquidity map, data gaps, measurement constraints, and confidence levels                                                |
| Demand and venue evidence review | Applicant-proposed timing | Review early demand-side findings, venue bottlenecks, market-maker/CEX constraints, and weak evidence                                        |
| Interim findings review          | Applicant-proposed timing | Test whether evidence is answering the decision gates and whether scope needs adjustment                                                     |
| Draft deliverables review        | Applicant-proposed timing | Review baseline, incentive comparison, scorecard, demand memo, monitoring framework, and roadmap                                             |
| Final report and presentation    | Applicant-proposed timing | Present final findings, confidence levels, limitations, decisions enabled, and recommended actions                                           |
| Public summary                   | Applicant-proposed timing | Publish non-confidential summary                                                                                                             |

Applicants should propose a timeline appropriate to their methodology. Unrealistic timelines should be avoided, especially where market-maker, exchange, or proprietary data access is required.

***

## 15. Governance, Reporting, and Communication

The selected vendor will participate in structured checkpoints. The process should support research quality without becoming unnecessarily restrictive. CPC or a designated review group will align with the vendor on research design, assets, venues, metrics, data handling, and confidentiality expectations, while leaving room for the vendor to adapt methods as evidence and access constraints emerge.

| Checkpoint                       | Purpose                                                                                                                                 |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Kickoff                          | Confirm objectives, decision gates, workplan, communication cadence, and confidentiality expectations                                   |
| Research Design Review           | Align on asset scope, venue scope, metrics, respondent categories, benchmark approach, data sources, and bias controls before fieldwork |
| Liquidity Baseline Review        | Review current-state data, measurement choices, source limitations, and confidence levels                                               |
| Demand and Venue Evidence Review | Surface early demand validation, bottleneck diagnosis, market-maker/CEX constraints, and data gaps                                      |
| Interim Findings Review          | Test whether evidence is answering the decision gates and whether scope needs adjustment                                                |
| Draft Deliverables Review        | Review baseline, incentive model comparison, liquidity incentive scorecard, demand memo, monitoring framework, and roadmap              |
| Final Presentation               | Present final findings, confidence levels, limitations, decisions enabled, and recommended next actions                                 |
| Public Summary Review            | Confirm what can be published and what must remain confidential                                                                         |

The reporting cadence should be proportionate to project length, but at least one interim findings review and one draft deliverables review are required.

The vendor should not wait until the final report to reveal weak data access, unresponsive market participants, unclear venue definitions, or findings that suggest incentive spending should be deferred.

***

## 16. Risks, Bias Controls, and Safeguards

Applicants must include a research integrity plan.

| Risk                              | Required Control                                                                                 |
| --------------------------------- | ------------------------------------------------------------------------------------------------ |
| Cardano insider bias              | Separate Cardano ecosystem views from demand-side operator evidence and peer evidence            |
| Issuer or asset favoritism        | Disclose relationships and evaluate assets against common criteria                               |
| Protocol self-interest            | Separate protocol claims from measured liquidity, route quality, and user demand                 |
| Market-maker conflict of interest | Require conflict disclosure and triangulate commercial claims where possible                     |
| Exchange access opacity           | Label data limitations and distinguish verified evidence from vendor judgment                    |
| TVL overinterpretation            | Require slippage, depth, spread, retention, or usage interpretation before using TVL as evidence |
| Wash or circular activity         | Define volume quality checks and suspicious-pattern controls                                     |
| Mercenary liquidity               | Include retention windows, step-down analysis, and post-incentive monitoring                     |
| Demand weakness                   | Validate user/operator need before recommending supply-side incentives                           |
| False precision in benchmarks     | Include evidence notes, confidence labels, and limitations for each benchmark                    |
| Proprietary data dependency       | State access conditions, inspectability, publication limits, and confidence implications         |
| Scope creep                       | Use cross-RFP handoff logic for adjacent research areas                                          |
| Sensitive commercial information  | Separate public findings, confidential findings, and raw data                                    |

The final report must include a limitations section explaining what the research can and cannot support.

***

## 17. Clarification Process

Applicants may submit clarification questions during the clarification window.

Questions may address:

* asset and venue scope;
* liquidity measurement expectations;
* data access and limitations;
* market-maker, exchange, or issuer confidentiality;
* peer benchmark selection;
* demand-side respondent categories;
* incentive KPI design;
* anti-gaming safeguards;
* public versus confidential outputs;
* budget format;
* overlap with other Product Research Initiative RFPs.

Responses should be maintained in a rolling Q\&A log where practical so applicants receive consistent information. If a response materially changes scope, deadline, or eligibility, the RFP timeline may be adjusted.

The clarification process also helps assess applicant judgment. Strong questions may demonstrate specificity, market-structure awareness, methodological discipline, and realistic tradeoff thinking.

***

## 18. Data Handling, Confidentiality, and Public Summary

The selected vendor must provide a data handling plan covering:

* informed consent process;
* interview recording and transcript handling;
* anonymization approach;
* storage and access controls;
* retention and deletion plan;
* treatment of commercially sensitive market-maker, exchange, issuer, or protocol information;
* treatment of raw interview notes;
* treatment of proprietary or paid data;
* separation of public and confidential findings;
* process for seeking permissioned public attribution where useful.

Research outputs should distinguish:

* public findings suitable for community publication;
* confidential findings suitable only for CPC/internal review;
* raw data that should not be published;
* proprietary data that CPC can inspect but may not publish;
* vendor judgment where primary data cannot be disclosed.

A public summary is expected unless specific findings cannot be published for confidentiality reasons. The public summary should include useful methodology notes, high-level liquidity findings, recommended KPI logic where publishable, and caveats. It should not expose confidential commercial terms, market-maker strategies, exchange negotiations, sensitive issuer information, or respondent identities without consent.

If proprietary, paid, or respondent-provided data is used, the vendor must state:

* source;
* access conditions;
* whether CPC can inspect it;
* whether it can be cited publicly;
* what limitations apply;
* whether the data can be retained after project completion.

If a finding depends heavily on data CPC cannot inspect, the vendor must label the confidence level accordingly.

***

## 19. Human Subject Research Ethics

Because this RFP requires interviews, the selected vendor must apply basic human-subject research safeguards.

At minimum, the vendor should:

* tell respondents the purpose of the research;
* explain who the research is for;
* state how information may be used;
* ask whether comments are attributable, anonymized, or confidential;
* obtain consent before recording;
* avoid publishing commercially sensitive information without permission;
* allow respondents to clarify attribution status;
* avoid misleading respondents about the purpose or audience of the work.

***

## 20. Conflicts of Interest

Applicants must disclose any actual, potential, or perceived conflicts of interest, including:

* paid work for Cardano ecosystem entities;
* paid work for peer-chain ecosystems;
* advisory roles;
* governance roles;
* financial exposure to Cardano, stablecoin assets, DeFi protocols, or competitor ecosystem assets;
* relationships with stablecoin issuers, DeFi protocols, market makers, liquidity providers, exchanges, wallets, payment operators, or RWA/enterprise teams included in the research;
* relationships with projects that may benefit from liquidity incentives;
* subcontractor conflicts.

Declared conflicts do not automatically disqualify an applicant, but they must be managed. Undisclosed conflicts may be grounds for rejection, non-award, payment holdback, or termination.

***

## 21. Terms and Conditions

Standard terms and conditions will be provided through the shared tender process before award. Applicants should assume that final award terms will cover ownership and permitted publication of deliverables, confidentiality, payment milestones, termination, data protection, subcontractor approval, warranties or disclaimers, and the governing process.

***

## 22. Appendix A: Proposal Checklist

Applicants should confirm that their proposal includes:

* [ ] Cover letter
* [ ] Understanding of the brief
* [ ] Proposed methodology
* [ ] Decision gate mapping
* [ ] Liquidity measurement plan
* [ ] Venue analysis plan
* [ ] Incentive model assessment plan
* [ ] Demand-side validation plan
* [ ] Peer benchmark plan
* [ ] Monitoring and anti-gaming approach
* [ ] Data sources
* [ ] Workplan
* [ ] Team qualifications
* [ ] Relevant experience
* [ ] Risk and bias mitigation plan
* [ ] Confidentiality and data handling approach
* [ ] Timeline
* [ ] Budget breakdown
* [ ] Conflicts declaration
* [ ] Ethics approach
* [ ] Prior work examples, if applicable

***

## 23. Appendix B: Suggested Liquidity Baseline Template

| Asset         | Pair / Route  | Venue    | Metric                              | Measurement Window | Current Value | Data Source | Limitation    | Confidence             |
| ------------- | ------------- | -------- | ----------------------------------- | ------------------ | ------------- | ----------- | ------------- | ---------------------- |
| \[Stablecoin] | \[Pair/route] | \[Venue] | \[Depth/slippage/spread/TVL/volume] | \[Window]          | \[Value]      | \[Source]   | \[Limitation] | \[High / Medium / Low] |

***

## 24. Appendix C: Suggested Incentive Scorecard Template

| Asset / Venue    | Target KPI | Funding Trigger | Payment Logic | Monitoring Method | Gaming Risk            | Safeguard    | Renewal / Stop Condition |
| ---------------- | ---------- | --------------- | ------------- | ----------------- | ---------------------- | ------------ | ------------------------ |
| \[Asset / venue] | \[KPI]     | \[Trigger]      | \[Logic]      | \[Method]         | \[High / Medium / Low] | \[Safeguard] | \[Condition]             |

***

## 25. Appendix D: Suggested Demand Validation Template

| User Segment / Use Case | Stablecoin Need | Required Asset / Venue | Depth or Execution Requirement | Evidence Source | Confidence             | Implication                           |
| ----------------------- | --------------- | ---------------------- | ------------------------------ | --------------- | ---------------------- | ------------------------------------- |
| \[Segment/use case]     | \[Need]         | \[Asset/venue]         | \[Requirement]                 | \[Source]       | \[High / Medium / Low] | \[Fund / defer / handoff / no action] |

***

## 26. Appendix E: Suggested Roadmap Template

| Horizon   | Target Outcome | Asset / Venue Focus | Candidate Intervention | KPI Threshold | Monitoring Method | Funding Decision | Stop Condition |
| --------- | -------------- | ------------------- | ---------------------- | ------------- | ----------------- | ---------------- | -------------- |
| 6 months  | \[Outcome]     | \[Focus]            | \[Intervention]        | \[Threshold]  | \[Method]         | \[Decision]      | \[Condition]   |
| 12 months | \[Outcome]     | \[Focus]            | \[Intervention]        | \[Threshold]  | \[Method]         | \[Decision]      | \[Condition]   |
| 24 months | \[Outcome]     | \[Focus]            | \[Intervention]        | \[Threshold]  | \[Method]         | \[Decision]      | \[Condition]   |
