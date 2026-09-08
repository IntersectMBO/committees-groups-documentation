# RFP 07: L2 Adoption and Interoperability Demand Study

Tender type: Request for Proposals

Issued by: Cardano Product Committee / Intersect

Research portfolio: Product Research Initiatives

Final publication date, submission deadline, clarification window, expected project period, submission method, and contact will be confirmed on the Product Research Initiatives - Grants page before the call opens.

***

## 1. Executive Summary

### Strategic question

Which Layer 2 and interoperability investments would unlock validated Cardano application demand, and which cross-chain pathways create net-new or mutual value for Cardano rather than mainly increasing dependency on larger or more liquid ecosystems?

### Evidence gap

Cardano has credible signs of demand for Layer 2 infrastructure and cross-chain interoperability. Several applications and use cases appear to be delayed pending better scaling, settlement, bridge, partner-chain, wallet, or cross-chain capabilities. However, Cardano stakeholders do not yet have a decision-ready map of what is actually blocked, which capabilities are required, which blockers are technical versus commercial, and which interoperability pathways would create durable Cardano-side value.

The evidence gap is not whether L2s or interoperability are useful in the abstract. The gap is whether specific applications, workflows, builders, operators, providers, or partners are waiting on identifiable capabilities; whether those capabilities would unlock measurable adoption; and whether specific interoperability pathways would bring users, liquidity, applications, transaction activity, or strategic partners into Cardano.

This research should also test a more difficult question: interoperability can create value, but it can also create asymmetric dependency. Some cross-chain pathways may help Cardano attract net-new users, liquidity, applications, or partners. Others may primarily make it easier for value to leave Cardano or for Cardano activity to depend on stronger ecosystems. Cardano stakeholders need a way to distinguish these outcomes before funding, prioritizing, or promoting interoperability work.

### Decision unlocked

This research should enable Cardano stakeholders to decide:

* which L2 blockers should be addressed first;
* which applications or use cases justify near-term L2 investment because deployment is genuinely blocked;
* which interoperability features builders and operators request most, and why;
* which bridge, partner-chain, wallet, messaging, liquidity, or cross-chain pathways should be prioritized;
* which interoperability paths are value-accretive, mutual-value, neutral-access, dependency-risk, or value-leakage risk for Cardano;
* whether blockers require engineering, documentation, wallet support, bridge/provider partnerships, liquidity coordination, commercial incentives, builder activation, or no action;
* what evidence should be required before Cardano stakeholders fund future L2 or interoperability proposals.

### Expected outputs

The selected vendor will produce an L2 barrier analysis, L2 demand map, interoperability requirements register, interoperability value-flow assessment, provider and partner opportunity analysis, blocked-demand case register, negative-case and non-Cardano evidence summary, investment sequencing recommendation, evidence threshold framework, methodology appendix, executive decision memo, final research report, final presentation, public summary, and cross-RFP handoff memo.

Vendors may combine deliverables where sensible, provided that every decision gate is answered and every required output is covered.

### Requirement priority

The required core is to answer the decision gates with traceable evidence and produce the required decision outputs. Optional methods, templates, or stretch work should be separated from the core scope and budget. This RFP is not L2 protocol design, bridge implementation, liquidity incentive design, technical roadmap authorship, or generic ecosystem advocacy.

***

## 2. Strategic Context

The Cardano Product Committee has received funding to commission a portfolio of product research initiatives aligned with Cardano's long-term product direction and Strategy 2030 priorities. The purpose of the portfolio is to define the evidence Cardano needs before making product, adoption, funding, partnership, and strategic decisions.

This RFP focuses on L2 adoption and interoperability demand. The purpose is to understand which scaling and cross-chain capabilities would unlock real application deployment, which barriers are delaying that deployment, and which interoperability pathways would create Cardano-side value.

Layer 2 infrastructure can matter for throughput, cost, latency, privacy, application-specific execution, settlement patterns, and user experience. Interoperability can matter for asset movement, liquidity access, cross-chain messaging, partner-chain connectivity, wallet flows, identity or data portability, and access to users or applications in other ecosystems.

However, technical capability alone does not prove adoption value. A missing L2 feature is only a strategic blocker if a real application, workflow, user group, or commercial pathway is waiting on it. A bridge or cross-chain integration is only strategically useful if it creates measurable value for Cardano or a credible mutual benefit with another ecosystem.

The research should inform the Cardano Product Committee and the broader Cardano ecosystem, including L2 and scaling teams, bridge and interoperability providers, partner-chain teams, wallet teams, application builders, infrastructure teams, business development teams, grant allocators, technical roadmap contributors, and future research vendors.

***

## 3. Research Problem Statement

Cardano lacks a decision-ready view of L2 demand, interoperability requirements, deployment blockers, provider incentives, and cross-chain value-flow implications.

Current discussion can collapse several different claims into one broad statement that Cardano "needs L2s" or "needs more interoperability." That framing is not sufficient for investment decisions. Cardano stakeholders need to know:

* which applications and workflows are actually blocked by missing L2 capability;
* whether the blocker is throughput, cost, latency, privacy, settlement, state management, composability, developer tooling, wallet support, liquidity, commercial uncertainty, or another factor;
* which use cases would deploy, scale, or become commercially viable if the blocker were addressed;
* which interoperability features operators and builders request most;
* what prevents bridge, interoperability, partner-chain, wallet, or infrastructure providers from prioritizing Cardano;
* which cross-chain pathways would bring net-new users, liquidity, applications, transactions, or partner access into Cardano;
* which pathways create asymmetric dependency or value-leakage risk;
* what actions should be funded, coordinated, partnered, monitored, deferred, or rejected.

Without this evidence, Cardano risks:

* funding technically interesting work without validated adoption demand;
* treating builder preference as deployment evidence;
* misclassifying liquidity, wallet, tooling, UX, commercial, or coordination blockers as L2 engineering problems;
* prioritizing bridge or partner-chain opportunities because they are visible rather than because they create Cardano-side value;
* subsidizing interoperability that primarily benefits a larger or more liquid ecosystem;
* failing to support applications that are genuinely blocked by missing infrastructure;
* duplicating adjacent research on use cases, stablecoin liquidity, enterprise/RWA readiness, government entry, delivery partners, or AI positioning.

The selected vendor must close this evidence gap by producing demand-grounded, decision-oriented research that ranks blockers, maps use cases, identifies requirements, classifies value-flow outcomes, and recommends investment sequencing.

***

## 4. Definitions

For this RFP:

**Layer 2** or **L2** means infrastructure that supports execution, scaling, settlement, privacy, throughput, latency, cost reduction, application-specific operation, or other off-main-chain capabilities while remaining connected to Cardano in a way relevant to adoption or value creation.

**Interoperability** means the ability for users, applications, assets, messages, data, identities, liquidity, wallets, partner chains, or infrastructure to interact across Cardano and other ecosystems or execution environments.

**Interoperability pathway** means a bridge corridor, cross-chain messaging path, partner-chain integration, wallet or user-flow integration, liquidity route, asset-transfer mechanism, identity or data portability mechanism, or other cross-chain mechanism proposed or assessed by the applicant.

**Operator** means a builder, application team, L2 team, bridge provider, interoperability provider, wallet team, infrastructure provider, liquidity provider, enterprise, partner-chain team, integrator, or other actor making practical deployment, integration, scaling, or chain-support decisions.

**Blocked demand** means a specific application, workflow, user segment, commercial opportunity, or operator decision that cannot proceed, scale, or justify deployment until a defined L2 or interoperability capability exists.

**Value-accretive interoperability** means a cross-chain pathway likely to bring net-new users, liquidity, applications, transaction activity, revenue pathways, strategic partners, or other measurable value into Cardano.

**Mutual-value interoperability** means a pathway that creates credible bidirectional benefit for Cardano and another ecosystem.

**Neutral-access interoperability** means a pathway that improves connectivity but has unclear, limited, or unproven adoption impact for Cardano.

**Dependency-risk interoperability** means a pathway that improves connectivity but increases Cardano's reliance on a larger, more liquid, or more commercially dominant ecosystem without clear Cardano-side retention or strategic benefit.

**Value-leakage risk** means a pathway likely to enable outflow of users, liquidity, applications, transaction activity, or strategic leverage from Cardano without sufficient compensating benefit.

**Adoption signal** means evidence that an L2 or interoperability capability would support measurable deployment, recurring usage, transaction activity, retained users, retained liquidity, commercial integration, partner commitment, or another decision-relevant outcome.

**Cosmetic signal** means activity that appears useful but does not demonstrate adoption, such as social media demand, vague partnership announcements, non-binding interest, demos without users, feature wish lists, or isolated claims that are not tied to a deployment decision.

The selected vendor may refine these definitions during the research design phase, but revised definitions must remain measurable, decision-useful, and evidence-based.

***

## 5. Objectives

The selected vendor will be expected to:

1. Identify which Cardano applications, workflows, or use cases are genuinely blocked by missing L2 or interoperability capability.
2. Classify L2 and interoperability blockers by type, severity, adoption impact, urgency, owner/workstream, and evidence confidence.
3. Determine which L2 capabilities would unlock the most immediate adoption value.
4. Produce a demand map of applications and use cases waiting on L2 or interoperability, with indicative scale ranges, timing assumptions, and confidence levels.
5. Identify and rank interoperability features requested by builders, operators, bridge providers, infrastructure teams, and other relevant stakeholders.
6. Assess why bridge, interoperability, partner-chain, wallet, or infrastructure providers do or do not prioritize Cardano.
7. Classify priority interoperability pathways as value-accretive, mutual-value, neutral-access, dependency-risk, or value-leakage risk.
8. Recommend which L2 and interoperability actions should be funded now, coordinated, partnered, monitored, deferred, or rejected.
9. Produce an evidence threshold framework for future L2 and interoperability grant, partnership, and roadmap decisions.
10. Identify dependencies and handoff findings for adjacent RFPs or workstreams.

***

## 6. Decision Gates

Applicants must design their methodology around the following decision gates. A proposal that does not map methods and deliverables to these gates will be considered weak fit for this RFP.

| Decision Gate                                                                             | Evidence Required                                                                                                                                                                                                               | YES Means                                                                                    | NO Means                                                                                                  | Action Unlocked                                                                                                                  |
| ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Which applications or use cases are actually blocked by missing L2 capability?            | Named or category-level application evidence, builder/operator interviews, deployment blockers, current workaround analysis, and evidence of why L1 alone is insufficient                                                       | There is validated demand for L2 capacity tied to concrete applications or workflows         | L2 is being used as a broad explanation for problems that may sit elsewhere                               | Prioritize L2 investment around validated blocked demand rather than abstract infrastructure preference                          |
| What type of L2 capability would unlock the most immediate adoption value?                | Ranked requirements across throughput, latency, cost, privacy, state/channel design, app-specific execution, settlement, developer tooling, UX, and integration burden                                                          | Cardano can identify which L2 features matter most for deployment decisions                  | The ecosystem risks funding technically interesting work without clear adoption pull                      | Sequence L2 roadmap, grants, ecosystem support, or technical coordination around highest-impact requirements                     |
| Which L2 blockers are technical, commercial, ecosystem, or coordination problems?         | Barrier analysis separating protocol/tooling gaps, implementation maturity, documentation, liquidity, wallet support, integrations, partner access, incentives, and business-case uncertainty                                   | Blockers can be routed to the right owner or workstream                                      | Funding may target technical buildout when the real blocker is commercial, liquidity, UX, or coordination | Decide whether to fund engineering, documentation, partnerships, liquidity support, builder activation, or no action             |
| Which applications waiting on L2 represent meaningful demand at scale?                    | Demand map with indicative user type, transaction pattern, potential usage range, revenue or value pathway, deployment timeline, confidence level, and evidence source                                                          | Some L2-dependent opportunities justify near-term investment or coordination                 | Claimed demand is too small, too speculative, or too weakly evidenced to drive priority decisions         | Rank applications/use cases for investment sequencing and define thresholds for future support                                   |
| What interoperability features do builders and operators actually need?                   | Requirements register based on operator interviews, bridge provider input, wallet/infrastructure needs, current pain points, requested assets or chains, frequency, blocker status, and urgency                                 | Cardano can prioritize interoperability features around observed demand                      | Interoperability work may follow assumptions rather than operator requirements                            | Prioritize bridge, messaging, asset-transfer, wallet, identity, liquidity, partner-chain, or developer tooling features          |
| Which interoperability pathways are net-positive for Cardano?                             | Value-flow assessment showing expected users, liquidity, transaction activity, application deployment, partner access, strategic dependency, and direction of value movement                                                    | A pathway likely brings net-new or mutual value to Cardano                                   | A pathway may create access but not meaningful Cardano-side adoption                                      | Fund, partner, promote, or coordinate around value-accretive interoperability paths                                              |
| Which interoperability pathways create asymmetric dependency or value-leakage risk?       | Analysis of whether liquidity, users, applications, or transaction activity primarily move out of Cardano; comparison of ecosystem size, liquidity depth, switching incentives, and retention mechanisms                        | The risk can be managed or avoided through sequencing, design, incentives, or partner choice | Cardano may subsidize infrastructure that primarily benefits another ecosystem                            | Deprioritize, redesign, or condition support for high-risk pathways                                                              |
| Which bridge, partner-chain, or cross-chain partners should Cardano prioritize?           | Partner opportunity assessment covering reachable counterparties, technical feasibility, demand evidence, mutual incentives, integration cost, maintenance burden, and value-flow classification                                | Cardano has a shortlist of partners or corridors worth pursuing                              | Partnership effort remains opportunistic or visibility-driven                                             | Set BD, grant, technical collaboration, or ecosystem funding priorities                                                          |
| What is preventing bridge and interoperability providers from prioritizing Cardano today? | Interviews with bridge providers, interoperability protocols, infrastructure teams, exchanges or liquidity providers where relevant, and analysis of perceived demand, integration cost, risk, incentives, and opportunity cost | Cardano can address the actual reasons providers have not prioritized it                     | The ecosystem may assume technical blockers where the provider decision is commercial or demand-based     | Decide whether to offer funding, technical support, demand aggregation, liquidity commitments, documentation, or no intervention |
| What evidence should be required before funding L2 or interoperability proposals?         | Proposed evidence thresholds tied to validated demand, blocker severity, expected adoption, value-flow impact, user/application commitments, and measurable post-funding KPIs                                                   | Future proposals can be judged against a reusable evidence standard                          | Funding may continue relying on narratives, technical appeal, or ecosystem enthusiasm                     | Create decision criteria for grants, partnerships, pilots, and roadmap prioritization                                            |
| Which findings should be handed to adjacent RFPs or workstreams?                          | Dependency map across stablecoin liquidity, use-case positioning, enterprise/RWA readiness, government markets, delivery partners, wallets, DevX, and technical roadmap workstreams                                             | RFP #7 stays focused while routing non-L2 blockers correctly                                 | Scope expands into a general ecosystem strategy study                                                     | Keep the research decision-oriented and prevent duplication across the RFP portfolio                                             |

***

## 7. Scope of Work

### In scope

The selected vendor should cover:

* L2 blocker analysis;
* L2 demand mapping;
* application and use-case screening;
* interoperability requirements mapping;
* bridge, partner-chain, wallet, and infrastructure provider analysis;
* interoperability value-flow assessment;
* negative-case and non-Cardano evidence gathering;
* investment sequencing recommendation;
* evidence threshold framework for future proposals;
* cross-RFP handoff notes;
* public and confidential reporting.

### Screening-first scope

Applicants should propose a screening phase before deep-dive research. The screening phase should identify which applications, use cases, interoperability pathways, bridge corridors, partner-chain candidates, or provider opportunities deserve deeper analysis.

The RFP does not require every possible L2 design, bridge corridor, partner chain, wallet flow, or cross-chain feature to receive equal research depth. A narrower proposal with credible respondent access, clear evidence standards, and strong decision value may be stronger than a broad proposal that covers many pathways superficially.

For each screened area, the vendor should assess:

* claimed blocker;
* affected application or workflow;
* current workaround;
* evidence of demand;
* expected Cardano-side value;
* dependency risk;
* respondent access;
* available public or private evidence;
* relevance to Cardano 2030 adoption goals;
* decision value of deeper research.

### Out of scope and handoff boundaries

This RFP should remain focused on demand, use cases, blocker prioritization, interoperability requirements, value-flow assessment, and investment sequencing. It may identify findings relevant to other Product Research Initiatives or technical workstreams, but it should not attempt to fully answer those initiatives.

| Topic                           | In Scope for This RFP                                                           | Out of Scope for This RFP                                                  |
| ------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| L2 technical architecture       | Requirements and blockers that affect adoption decisions                        | Designing or selecting a full L2 protocol architecture                     |
| Developer experience            | DevX issues where they directly block L2 or interoperability adoption           | Full developer tooling audit                                               |
| Stablecoins and liquidity       | Liquidity as a dependency for L2/interoperability demand or value-flow analysis | Stablecoin liquidity incentive design or market-maker strategy             |
| Use-case landscape              | Use cases where L2 or interoperability is a claimed blocker                     | Broad vertical prioritization unrelated to L2/interoperability             |
| Enterprise and RWA              | Enterprise/RWA blockers related to L2, settlement, privacy, or interoperability | Full enterprise readiness, compliance, or production conversion assessment |
| Government and emerging markets | Regional or public-sector use cases only where L2/interoperability is a blocker | Country-level entry playbooks or government strategy                       |
| Delivery partners               | Partner dependency where it affects deployment                                  | Full partner certification or delivery network design                      |
| Bridge security                 | Security concerns as decision factors and diligence triggers                    | Formal security audit or legal review                                      |
| Legal/regulatory                | Identification of diligence questions or uncertainty                            | Legal advice or regulatory conclusions                                     |

Findings that materially affect another research initiative or workstream should be captured in the Cross-RFP Handoff Memo rather than expanded inside this RFP.

### Optional / nice-to-have stretch scope

Applicants may propose optional stretch scope, priced separately, such as:

* deeper peer ecosystem benchmarking;
* deeper analysis of specific bridge corridors or partner-chain candidates;
* additional non-Cardano or negative-case interviews;
* wallet and UX dependency assessment where it directly affects interoperability adoption;
* light technical feasibility review by qualified technical reviewers;
* public workshop or ecosystem briefing;
* reusable annual refresh model for L2/interoperability demand and value-flow assessment.

***

## 8. Required Methodology

The selected vendor must use a mixed-method research design. Desk research alone is not sufficient.

The methodology should include:

* existing evidence review;
* screening phase;
* builder and operator interviews;
* bridge, interoperability, partner-chain, wallet, and infrastructure provider interviews;
* non-Cardano and negative-case respondent coverage;
* demand mapping;
* blocker classification;
* interoperability requirements register;
* value-flow assessment;
* evidence confidence ratings;
* triangulation or explicit confidence labeling for major findings;
* cross-RFP dependency mapping.

### Core research hypotheses

Applicants should test, refine, or reject hypotheses such as:

| Hypothesis                                                                                   | What Must Be Tested                                                                                                                                                                                  | Decision Relevance                                                                                                             |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Some Cardano applications are genuinely blocked by missing L2 capability                     | Whether named applications, use cases, or operator categories can identify specific L2 requirements and deployment blockers                                                                          | Determines whether L2 investment should be prioritized around validated demand                                                 |
| L2 demand is not uniform                                                                     | Whether different use cases need different combinations of throughput, latency, cost, privacy, settlement, state management, composability, developer tooling, or UX support                         | Prevents one generic L2 roadmap from being treated as the answer to all demand                                                 |
| Some apparent L2 blockers are actually non-L2 blockers                                       | Whether delays are caused by liquidity, wallets, integrations, tooling, commercial uncertainty, compliance, partner access, or user demand rather than scaling itself                                | Routes blockers to the right workstream instead of misallocating technical investment                                          |
| Interoperability demand is feature-specific                                                  | Whether operators need asset bridging, message passing, liquidity routing, partner-chain integration, wallet UX, identity/data portability, settlement interoperability, or another specific feature | Guides which interoperability capabilities should be prioritized                                                               |
| Interoperability pathways differ in Cardano-side value                                       | Whether specific corridors or partnerships bring net-new users, liquidity, applications, revenue, transactions, or strategic access to Cardano, or mainly increase dependence on larger ecosystems   | Determines which pathways should be funded, partnered, sequenced, redesigned, or deprioritized                                 |
| Bridge and interoperability providers have identifiable reasons for not prioritizing Cardano | Whether blockers are demand, integration cost, technical complexity, liquidity, security risk, incentive misalignment, commercial opportunity cost, or lack of ecosystem support                     | Defines whether Cardano should offer technical support, funding, demand aggregation, liquidity commitments, or no intervention |
| A reusable evidence standard can improve future funding decisions                            | Whether proposal quality can be assessed through validated demand, blocker severity, expected Cardano-side value, and measurable adoption outcomes                                                   | Helps CPC and broader ecosystem evaluate future L2 and interoperability proposals                                              |

### Required evidence types

| Evidence Type                                                    | Required Use                                                                                                                                   | Notes                                                            |
| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Builder and application operator interviews                      | Validate which applications are blocked, what requirements they have, and what deployment decision is pending                                  | Required                                                         |
| Bridge, interoperability, and infrastructure provider interviews | Understand why providers do or do not prioritize Cardano, and what would change that                                                           | Required                                                         |
| Use-case demand mapping                                          | Identify applications and workflows waiting on L2 or interoperability                                                                          | Required                                                         |
| Requirements register                                            | Translate operator needs into ranked technical/commercial requirements                                                                         | Required                                                         |
| Value-flow assessment                                            | Classify interoperability pathways by Cardano-side value and dependency risk                                                                   | Required                                                         |
| Desk research                                                    | Establish current L2/interoperability landscape, public roadmaps, available infrastructure, peer ecosystem approaches, and candidate providers | Required                                                         |
| On-chain or product data                                         | Validate demand or activity where available and meaningful                                                                                     | Required where relevant; limitations must be stated              |
| Peer ecosystem benchmarking                                      | Compare how other ecosystems convert L2/interoperability into adoption                                                                         | Recommended, or required for any provider/partner recommendation |
| Negative-case evidence                                           | Capture stalled deployments, abandoned integrations, rejected Cardano support, or cases where interoperability failed to produce value         | Required                                                         |
| Expert review                                                    | Validate technical feasibility and value-flow logic                                                                                            | Recommended, especially where claims are technically complex     |

### Primary research expectations

Applicants must include primary validation. The proposal should explain:

* who will be interviewed;
* why those respondents are relevant;
* how respondents map to proposed use cases and pathways;
* how bridge, provider, or partner-chain respondents will be reached;
* how non-Cardano and negative-case respondents will be included;
* how insider bias and provider self-interest will be controlled;
* how confidential builder, provider, roadmap, or commercial evidence will be handled.

Indicative interview expectations:

| Interview Category                                                              | Indicative Range | Purpose                                                                                        |
| ------------------------------------------------------------------------------- | ---------------: | ---------------------------------------------------------------------------------------------- |
| Cardano application builders/operators claiming L2 or interoperability needs    |         \[15-25] | Validate blocked demand, requirements, deployment timelines, and scale                         |
| Cardano infrastructure, L2, scaling, wallet, or partner-chain teams             |          \[8-15] | Understand current capabilities, blockers, roadmap assumptions, and implementation constraints |
| Bridge, interoperability, cross-chain messaging, or liquidity-routing providers |          \[8-15] | Identify why Cardano is or is not prioritized and what would change that                       |
| Non-Cardano or cross-chain application operators                                |          \[5-10] | Compare demand patterns and detect assumptions unique to Cardano insiders                      |
| Ecosystem experts, security reviewers, integrators, or liquidity/DeFi operators |          \[5-10] | Validate feasibility, risk, and value-flow classifications                                     |
| Total suggested range                                                           |         \[40-75] | Applicant may propose a different range if justified by scope and budget                       |

Applicants may propose a different sample size or respondent mix, but they must explain why it is sufficient to answer the decision gates.

The sample should not rely mainly on teams already seeking funding for L2 or interoperability work. Those respondents may be included, but their claims must be separated from independent demand evidence.

### Survey requirements

A survey is optional, not mandatory.

A survey may be useful if the applicant can reach a relevant builder/operator population and use it to quantify requirement frequency. If used, the survey should:

* segment respondents by builder type, application category, infrastructure role, and Cardano/non-Cardano status;
* ask about specific blockers and deployment decisions, not generic interest;
* separate must-have requirements from nice-to-have preferences;
* include confidence labels and recruitment source disclosure;
* avoid treating social media respondents or general community sentiment as demand evidence.

### Benchmarking requirements

Benchmarking should be used only where it helps answer decisions.

Useful benchmarks may include:

* L2 adoption pathways in peer ecosystems;
* bridge/provider prioritization criteria in peer ecosystems;
* examples of value-accretive interoperability;
* examples of interoperability that mainly enabled outflow or dependency;
* technical/commercial models used to attract bridge providers or cross-chain applications;
* evidence thresholds used by other ecosystems before funding interoperability infrastructure.

Benchmarking should not become a generic competitor report. It should explain what Cardano can learn, adapt, avoid, or test.

### Data sources to validate

Potential sources include:

* public documentation and roadmaps from Cardano L2, partner-chain, bridge, wallet, and interoperability projects;
* interviews with named or confidential operators;
* public app activity data where available;
* on-chain transaction, liquidity, bridge, or wallet data where relevant;
* developer documentation and integration friction evidence;
* bridge/provider integration requirements;
* ecosystem grant or funding proposal history where available;
* peer ecosystem case studies;
* proprietary datasets or paid expert calls, if justified.

Any proprietary, paid, or non-public data should be labeled with access conditions, publication limits, and whether CPC can inspect it.

### Evidence standards

Major findings should be triangulated where feasible using more than one evidence type. If triangulation is not possible, the vendor must label the finding with an appropriate confidence level and explain the limitation.

Demand estimates should be presented as indicative ranges, assumptions, and confidence ratings. Vendors should not invent precise market sizing or adoption forecasts where the evidence does not support that precision.

Value-flow findings should state:

* what the pathway is expected to bring into Cardano;
* what may leave Cardano;
* what retention mechanism or Cardano-side benefit exists;
* what dependency risk exists;
* what evidence supports the classification;
* what confidence level applies.

### What should not count as evidence

The following do not count as sufficient evidence on their own:

* roadmap existence;
* technical possibility;
* community sentiment;
* conference or event interest;
* informal Telegram or Discord enthusiasm;
* unverified "many builders need this" claims;
* single-team self-attestation without triangulation;
* generic market-size statistics;
* total value locked without user-flow interpretation;
* bridge volume without source/destination and retention analysis;
* competitor narratives without operator or product evidence;
* interoperability for its own sake.

***

## 9. Expected Deliverables

The selected vendor should produce the following deliverables. Vendors may combine deliverables where sensible, provided that every decision gate is answered and every required output is covered.

| Deliverable                                    | Description                                                                                                    | Purpose                                                                                            |
| ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| L2 Barrier Analysis                            | Ranked analysis of what is blocking L2-dependent deployment on Cardano                                         | Identify which blockers should be addressed first                                                  |
| L2 Demand Map                                  | Map of applications and use cases waiting on L2 capability                                                     | Show where validated demand exists and how strong it is                                            |
| Interoperability Requirements Register         | Ranked register of requested interoperability features                                                         | Identify which cross-chain capabilities operators actually need                                    |
| Interoperability Value-Flow Assessment         | Classification of priority cross-chain pathways by Cardano-side value and dependency risk                      | Determine which interoperability paths are value-accretive, mutual-value, neutral-access, or risky |
| Provider and Partner Opportunity Analysis      | Assessment of bridge, interoperability, partner-chain, wallet, or infrastructure providers relevant to Cardano | Identify which providers or partners should be prioritized                                         |
| Blocked-Demand Case Register                   | Documented cases where applications, workflows, or operators are waiting on L2/interoperability                | Ground demand claims in specific cases                                                             |
| Negative-Case and Non-Cardano Evidence Summary | Evidence from stalled deployments, rejected integrations, competitor choices, or non-Cardano operators         | Avoid insider bias and all-positive conclusions                                                    |
| Investment Sequencing Recommendation           | Recommended order of L2 and interoperability actions                                                           | Convert research into funding and coordination decisions                                           |
| Evidence Threshold Framework                   | Reusable standard for assessing future L2/interoperability proposals                                           | Improve future grant, partnership, and roadmap decisions                                           |
| Technical and Commercial Blocker Taxonomy      | Reusable classification system for blockers                                                                    | Ensure blockers are routed correctly                                                               |
| Research Methodology Appendix                  | Full methodology, sources, respondent categories, instruments, limitations, and confidence model               | Make findings auditable                                                                            |
| Cross-RFP Handoff Memo                         | Routing of findings to adjacent RFPs or workstreams                                                            | Prevent scope creep while preserving useful dependencies                                           |
| Executive Decision Memo                        | Short decision-ready summary                                                                                   | Support fast review and prioritization                                                             |
| Final Research Report                          | Complete research report for CPC and approved stakeholders                                                     | Provide the full evidence base and recommendations                                                 |
| Final Presentation                             | Presentation of findings and recommended actions                                                               | Support review, questioning, and alignment                                                         |
| Public Summary                                 | Non-confidential summary suitable for publication                                                              | Share useful findings with the Cardano ecosystem                                                   |

***

## 10. Acceptance Criteria

Acceptance criteria must be concrete and tied to decision gates.

| Deliverable                                    | Acceptance Criteria                                                                                                                                                                                   | Decision Enabled                                                                                                     | Failure Modes                                                                                                 |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| L2 Barrier Analysis                            | Separates technical, commercial, ecosystem, liquidity, UX, coordination, and unknown blockers; includes evidence source, affected use case, severity, confidence level, and proposed owner/workstream | Decide whether to fund engineering, documentation, partnerships, liquidity support, builder activation, or no action | Treats all blockers as technical; lacks evidence source; ranks barriers without explaining impact             |
| L2 Demand Map                                  | Includes application/use-case category, blocked workflow, required L2 capability, deployment condition, expected adoption pathway, indicative scale range, timing, confidence, and source basis       | Prioritize L2 investments around validated demand                                                                    | Lists speculative ideas; relies on self-reported demand only; includes no deployment condition or scale logic |
| Interoperability Requirements Register         | Classifies requested features by user/operator type, chain/corridor, frequency, urgency, blocker status, adoption consequence, evidence source, and confidence                                        | Prioritize bridge, messaging, asset transfer, wallet, partner-chain, identity, liquidity, or tooling investments     | Produces a generic feature wish list; does not distinguish must-have from nice-to-have requirements           |
| Interoperability Value-Flow Assessment         | Assesses expected inflows/outflows of users, liquidity, applications, transactions, partner access, retention mechanism, dependency risk, and confidence; uses agreed categories                      | Decide which pathways to fund, partner into, redesign, monitor, or deprioritize                                      | Treats every connection as positive; ignores outflow risk; lacks source/destination or retention logic        |
| Provider and Partner Opportunity Analysis      | Includes provider/partner type, current Cardano status, integration blocker, commercial incentive, technical effort, demand evidence, mutual benefit, risk, and recommended action                    | Decide where BD, technical collaboration, funding, or no action is appropriate                                       | Lists providers without decision logic; ignores why providers have not prioritized Cardano                    |
| Blocked-Demand Case Register                   | Includes applicant-justified number of cases; distinguishes named, confidential, and anonymized evidence; includes blocker, decision pending, source, and confidence                                  | Validate whether demand is real enough to justify investment                                                         | Uses vague "builders say" claims; no confidence labels; no blocked decision                                   |
| Negative-Case and Non-Cardano Evidence Summary | Includes negative cases, non-Cardano comparisons, or stalled/rejected pathways; explains what Cardano should learn or avoid                                                                           | Decide what not to fund, where assumptions are weak, and where peer approaches are not transferable                  | Omits losses and rejections; relies only on positive Cardano cases                                            |
| Investment Sequencing Recommendation           | Ranks actions by validated demand, impact, urgency, dependency, cost driver, owner/workstream, confidence, expected Cardano-side value, and action type                                               | Decide near-term, medium-term, and deferred investment priorities                                                    | Produces broad recommendations without sequencing; does not connect actions to evidence or decision gates     |
| Evidence Threshold Framework                   | Defines minimum evidence required for demand, blocker severity, value-flow benefit, adoption pathway, and measurable outcomes                                                                         | Set evidence requirements for future funding and partnership proposals                                               | Repeats generic evaluation language; does not help reviewers distinguish strong from weak proposals           |
| Research Methodology Appendix                  | Lists respondent categories, recruitment method, interview/survey instruments where appropriate, evidence limits, proprietary data restrictions, and confidence rubric                                | Allow CPC and ecosystem readers to evaluate evidence quality                                                         | Hides methods; does not explain limitations or respondent bias                                                |
| Cross-RFP Handoff Memo                         | Maps dependencies to RFP #2, #3, #5, #6, #8, #9, DevX, wallets, liquidity, governance, or technical roadmap workstreams                                                                               | Decide what should be handled outside RFP #7                                                                         | Absorbs adjacent RFPs into scope; fails to identify dependencies                                              |
| Final Research Report                          | Answers all decision gates; includes methods, findings, confidence levels, limitations, deliverables, and recommended actions                                                                         | Enable final prioritization and funding decisions                                                                    | Long narrative with no decision answers; recommendations unsupported by evidence                              |
| Executive Decision Memo                        | States top findings, recommended sequence, investment implications, unresolved questions, and no-go/deprioritization findings                                                                         | Support fast decision-making without reading the full report first                                                   | Summarizes activity but not decisions; omits tradeoffs and weak evidence                                      |
| Public Summary                                 | Includes methodology overview, publishable findings, high-level recommendations, caveats, and confidentiality limits; excludes sensitive respondent or commercial information                         | Inform builders, funders, and ecosystem teams while preserving trust                                                 | Too vague to be useful; exposes confidential details; omits methodology caveats                               |

### Required value-flow categories

The vendor must classify interoperability pathways using the following model:

| Category           | Meaning                                                                                              | Example Decision Consequence                                      |
| ------------------ | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Value-accretive    | Likely brings net-new users, liquidity, applications, transactions, or strategic access into Cardano | Prioritize for funding, BD, or technical support                  |
| Mutual-value       | Creates credible bidirectional benefit for Cardano and another ecosystem                             | Explore partnership, shared incentives, or co-development         |
| Neutral-access     | Improves connectivity but has unclear or limited adoption impact                                     | Monitor or support only if low-cost or strategically necessary    |
| Dependency-risk    | Increases reliance on a larger or more liquid ecosystem without clear Cardano-side retention         | Redesign, sequence later, or require stronger safeguards          |
| Value-leakage risk | Likely enables outflow of users, liquidity, or activity with insufficient compensating benefit       | Deprioritize unless mitigations or strategic rationale are strong |

### General acceptance criteria

Every deliverable should:

* map to at least one decision gate;
* identify evidence sources;
* include confidence levels;
* distinguish direct evidence from vendor interpretation;
* distinguish Cardano insider claims from external or independent evidence;
* separate technical feasibility from demand evidence;
* identify limitations and unresolved questions;
* state what decision the finding supports;
* include public/confidential treatment where relevant.

***

## 11. Vendor Eligibility

Applicants may be research firms, strategy consultancies, technical research teams, ecosystem intelligence teams, academic groups, infrastructure specialists, or consortia with relevant expertise.

Strong teams should demonstrate:

* market and operator research capability;
* Web3 infrastructure literacy;
* understanding of L2, bridge, interoperability, partner-chain, wallet, or cross-chain systems;
* qualified technical reviewer or advisor capacity proportionate to the proposed scope;
* ability to interview builders, operators, infrastructure providers, and non-Cardano stakeholders;
* ability to distinguish technical feasibility from adoption demand;
* experience producing decision-ready research for funding, product, partnership, or ecosystem strategy decisions;
* experience handling confidential or commercially sensitive respondent evidence;
* ability to disclose and manage conflicts of interest.

Subcontracting is allowed if roles, responsibilities, costs, and conflicts are clearly disclosed.

Applicants do not need to be Cardano-native, but they must demonstrate enough Cardano context to avoid generic blockchain conclusions. Teams with deep technical expertise but no credible demand research capability, or strong research capability but no infrastructure fluency, should explain how they will close that gap.

***

## 12. Proposal Submission Requirements

Applicants must follow the shared Submission Pack and include the common documents: cover letter, technical proposal, budget proposal, team credentials, evidence access plan, ethics/data handling statement, and conflicts declaration.

Applicants bidding on multiple Product Research Initiative RFPs must disclose shared staffing, shared respondent recruitment, shared evidence collection, and any assumptions that could create respondent fatigue or duplicated outreach.

For this RFP, the technical proposal must also include:

* L2 blocker analysis approach;
* demand map method for applications or workflows waiting on L2/interoperability;
* interoperability requirements register approach;
* provider, bridge, wallet, or partner-chain access plan;
* value-flow classification approach;
* evidence threshold framework for future L2/interoperability proposals.

Budgets should explain how cost relates to technical review, provider access, non-Cardano or negative-case research, proprietary data, and decision value.

## 13. Evaluation Guidance

Proposals will be assessed using the CPC standard research grant evaluation framework: Fit to Grant Objectives, Team Capability, Proposal Quality and Execution Plan, and Cost Efficiency. The full scoring framework is maintained on the shared evaluation page.

For this RFP, strong fit means the proposal can show which L2 and interoperability work is pulled by validated adoption demand, which blockers are technical versus commercial or ecosystem problems, and which pathways create Cardano-side value.

A strong proposal should include builder/operator and provider-side evidence; use a screening-first approach; classify value-flow outcomes; and define evidence thresholds for future L2 or interoperability proposals. It should not become a technical architecture selection.

Proposals should score lower if they rely on abstract technical advocacy, feature wish lists, social-media demand, or assumptions that interoperability is automatically positive for Cardano.

Cost should be judged against evidence value, not lowest price. Higher-cost proposals may be justified by stronger technical review, provider access, non-Cardano or negative-case research, proprietary data with clear value, or stronger decision outputs.

## 14. Timeline and Milestones

Final calendar dates will be confirmed on the Product Research Initiatives - Grants page before the call opens.

| Milestone                     | Target Date / Timing      | Purpose                                                                                                                                                 |
| ----------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RFP publication               | Confirmed on grants page  | Open call for proposals                                                                                                                                 |
| Clarification window opens    | Confirmed on grants page  | Applicants may submit questions                                                                                                                         |
| Clarification window closes   | Confirmed on grants page  | Final clarification responses issued                                                                                                                    |
| Proposal deadline             | Confirmed on grants page  | Applicant submissions due                                                                                                                               |
| Award notification            | Confirmed on grants page  | Selected vendor notified                                                                                                                                |
| Kickoff                       | Project week 1            | Confirm objectives, decision gates, scope, workplan, communication cadence, confidentiality expectations, and public-summary expectations               |
| Research design alignment     | Applicant-proposed timing | Align on respondent categories, instruments, blocker taxonomy, value-flow classification, evidence confidence model, and data handling before fieldwork |
| Screening review              | Applicant-proposed timing | Review candidate use cases, blockers, pathways, providers, and deep-dive selection                                                                      |
| Stakeholder access check      | Applicant-proposed timing | Surface recruitment issues, weak access, missing provider categories, confidentiality constraints, or substitutions needed                              |
| Early demand signal review    | Applicant-proposed timing | Review initial blocked-demand cases, possible false positives, non-L2 blockers, and early evidence gaps                                                 |
| Interim findings review       | Applicant-proposed timing | Test whether evidence is answering the decision gates and whether scope needs adjustment                                                                |
| Draft deliverables review     | Applicant-proposed timing | Review L2 barrier analysis, demand map, interoperability requirements register, value-flow assessment, provider analysis, and investment sequencing     |
| Final report and presentation | Applicant-proposed timing | Present final findings, confidence levels, limitations, decisions enabled, and recommended actions                                                      |
| Public summary review         | Applicant-proposed timing | Confirm what can be published and what should remain confidential                                                                                       |
| Public summary                | Applicant-proposed timing | Publish non-confidential summary                                                                                                                        |

Applicants should propose a timeline appropriate to their methodology. Unrealistic timelines should be avoided, especially where primary external validation, bridge/provider engagement, non-Cardano research, or technically complex value-flow assessment is proposed.

***

## 15. Governance, Reporting, and Communication

The selected vendor will participate in structured checkpoints. The process should protect research quality without turning the work into committee-managed consulting.

| Checkpoint                 | Purpose                                                                                                                                                                  |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Kickoff                    | Confirm objectives, decision gates, scope, workplan, communication cadence, confidentiality expectations, and public-summary expectations                                |
| Research Design Review     | Align on respondent categories, interview/survey instruments, blocker taxonomy, value-flow classification, evidence confidence model, and data handling before fieldwork |
| Screening Review           | Review candidate use cases, blockers, pathways, providers, and deep-dive selection                                                                                       |
| Stakeholder Access Check   | Surface recruitment issues, weak access, missing provider categories, confidentiality constraints, or substitutions needed                                               |
| Early Demand Signal Review | Review initial blocked-demand cases, possible false positives, non-L2 blockers, and early evidence gaps                                                                  |
| Interim Findings Review    | Test whether evidence is answering the decision gates and whether scope needs adjustment                                                                                 |
| Draft Deliverables Review  | Review L2 barrier analysis, demand map, interoperability requirements register, value-flow assessment, provider analysis, and investment sequencing                      |
| Final Presentation         | Present final findings, confidence levels, limitations, decisions enabled, and recommended actions                                                                       |
| Public Summary Review      | Confirm what can be published and what should remain confidential                                                                                                        |

Before primary fieldwork begins, the vendor should align with CPC or a designated review group on:

* respondent categories;
* recruitment strategy;
* proposed interview or survey instruments;
* blocker classification model;
* value-flow classification model;
* minimum evidence standard;
* data handling and confidentiality approach;
* treatment of commercially sensitive or roadmap-sensitive evidence;
* public-summary boundaries.

This review should protect research quality without directing the findings. The vendor should retain methodological independence and should be expected to report inconvenient or negative findings.

The vendor should not wait until the final report to disclose:

* weak respondent access;
* unsupported demand claims;
* technical feasibility uncertainty;
* provider non-responsiveness;
* evidence that L2 is not the main blocker;
* evidence that a favored interoperability path creates dependency risk;
* conflicts of interest;
* scope creep into adjacent RFPs.

***

## 16. Risks, Bias Controls, and Safeguards

Applicants must include a research integrity plan.

| Risk                                       | Required Control                                                                              |
| ------------------------------------------ | --------------------------------------------------------------------------------------------- |
| Cardano insider bias                       | Separate Cardano, non-Cardano, provider, and negative-case evidence                           |
| Technical roadmap bias                     | Test roadmap assumptions against builder/operator demand                                      |
| Provider self-interest                     | Label evidence from providers seeking funding, integration support, or market advantage       |
| False L2 demand                            | Require specific blocked workflows and deployment decisions                                   |
| Misclassified blockers                     | Separate technical, commercial, liquidity, UX, tooling, compliance, and coordination blockers |
| Interoperability optimism bias             | Require value-flow classification, including dependency-risk and value-leakage risk           |
| False precision                            | Use confidence levels and source notes for scale, timing, and adoption estimates              |
| Bridge/security sensitivity                | Avoid publishing details that create security or commercial risk                              |
| Weak access                                | Disclose recruitment limits early and adjust confidence levels                                |
| Scope creep                                | Use cross-RFP handoff logic for adjacent research areas                                       |
| Conflicted recommendations                 | Require conflict declarations and source labeling                                             |
| Confidentiality reducing public usefulness | Produce confidential full evidence plus publishable anonymized themes                         |

The final report must include a limitations section explaining what the research can and cannot support.

***

## 17. Clarification Process

Applicants may submit clarification questions during the clarification window.

Questions may address:

* L2 scope and definition;
* interoperability scope and pathway classification;
* expected respondent categories;
* treatment of confidential builder, provider, or roadmap evidence;
* minimum evidence standards;
* value-flow assessment method;
* bridge/provider access expectations;
* non-Cardano and negative-case evidence;
* on-chain, bridge, liquidity, or product data limitations;
* public versus confidential outputs;
* budget format;
* overlap with other Product Research Initiative RFPs.

Responses should be maintained in a rolling Q\&A log where practical so applicants receive consistent information. If a clarification materially changes scope, deadline, eligibility, or deliverables, the RFP timeline may be adjusted.

The clarification process also helps assess applicant judgment. Strong questions may demonstrate methodological specificity, technical realism, understanding of demand validation, and awareness of value-flow tradeoffs.

***

## 18. Data Handling, Confidentiality, and Public Summary

The selected vendor must provide a data handling plan covering:

* informed consent for interviews, expert calls, workshops, or surveys;
* recording and transcription policy;
* anonymization approach;
* raw notes and transcript handling;
* storage and access controls;
* retention and deletion plan;
* treatment of sensitive roadmap, commercial, security, or integration information;
* treatment of proprietary, paid, or respondent-provided data;
* separation of public findings, confidential findings, and raw data;
* publication boundaries.

Research outputs should distinguish:

* public findings suitable for ecosystem publication;
* confidential findings suitable only for CPC or approved reviewers;
* sensitive respondent information that should not be published;
* raw data that should not be published;
* proprietary data that CPC can inspect but may not publish;
* vendor judgment where primary data cannot be disclosed.

A public summary is expected unless specific findings cannot be published for justified confidentiality reasons.

The public summary should include:

* methodology overview;
* respondent category summary;
* high-level demand findings;
* high-level L2 blocker findings;
* high-level interoperability requirements;
* publishable value-flow themes;
* recommended investment sequencing where publishable;
* limitations and evidence caveats.

The public summary should not expose:

* confidential respondent identities;
* unreleased technical roadmap details;
* commercially sensitive provider information;
* security-sensitive bridge or infrastructure details;
* confidential integration plans;
* proprietary data restrictions;
* details that could undermine respondent trust.

If proprietary, paid, respondent-provided, or locally restricted data is used, the vendor must state:

* source;
* access conditions;
* whether CPC can inspect it;
* whether it can be cited publicly;
* what limitations apply;
* whether it can be retained after project completion.

If a finding depends heavily on data CPC cannot inspect, the vendor must label the confidence level accordingly.

***

## 19. Human Subject Research Ethics

Because this RFP requires interviews or surveys with builders, operators, infrastructure teams, providers, and potentially commercially sensitive stakeholders, the selected vendor must apply basic human-subject safeguards.

At minimum, the vendor should:

* tell respondents the purpose of the research;
* explain who the research is for;
* state how information may be used;
* ask whether comments are attributable, anonymized, or confidential;
* obtain consent before recording;
* avoid publishing sensitive respondent information without permission;
* allow respondents to clarify attribution status;
* avoid misleading respondents about the purpose or audience of the work;
* avoid exposing respondents to employment, commercial, security, regulatory, or competitive risk.

***

## 20. Conflicts of Interest

Applicants and subcontractors must disclose any actual, potential, or perceived conflicts of interest, including:

* paid work for Cardano ecosystem entities;
* paid work for peer-chain ecosystems;
* advisory roles;
* governance roles;
* financial exposure to Cardano or competitor ecosystem assets;
* relationships with L2 teams, bridge providers, interoperability protocols, partner-chain teams, wallets, liquidity providers, infrastructure vendors, application teams, or respondents;
* ownership or commercial interest in a product, protocol, chain, bridge, tooling provider, or integration that may be affected by the research;
* intent to apply for future funding connected to the findings;
* subcontractor conflicts.

Declared conflicts do not automatically disqualify an applicant, but they must be managed. Undisclosed conflicts may be grounds for rejection, non-award, payment holdback, or termination.

Research outputs should separate:

* evidence from conflicted respondents;
* evidence from teams seeking funding;
* independent operator or provider evidence;
* vendor interpretation;
* commercially sensitive findings.

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
* [ ] L2 demand validation plan
* [ ] Interoperability requirements plan
* [ ] Value-flow assessment plan
* [ ] Stakeholder access plan
* [ ] Bridge/provider engagement plan
* [ ] Non-Cardano and negative-case plan
* [ ] Data sources
* [ ] Workplan
* [ ] Deliverables plan
* [ ] Team qualifications
* [ ] Relevant experience
* [ ] Risk and bias mitigation plan
* [ ] Confidentiality and data handling approach
* [ ] Ethics approach
* [ ] Timeline
* [ ] Budget breakdown
* [ ] Conflicts declaration
* [ ] Prior work examples, if applicable

***

## 23. Appendix B: Suggested L2 Barrier Analysis Template

| Barrier    | Affected Use Case / Application | Barrier Type                                                                               | Severity               | Evidence Source | Confidence             | Owner / Workstream | Recommended Action                                               |
| ---------- | ------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------- | --------------- | ---------------------- | ------------------ | ---------------------------------------------------------------- |
| \[Barrier] | \[Use case]                     | \[Technical / Commercial / Liquidity / UX / Tooling / Coordination / Compliance / Unknown] | \[High / Medium / Low] | \[Source]       | \[High / Medium / Low] | \[Owner]           | \[Fund now / Coordinate / Partner / Monitor / Defer / No action] |

***

## 24. Appendix C: Suggested L2 Demand Map Template

| Application / Use Case  | Blocked Workflow | Required L2 Capability | Current Workaround | Deployment Condition | Indicative Scale Range  | Timing      | Evidence Source | Confidence             |
| ----------------------- | ---------------- | ---------------------- | ------------------ | -------------------- | ----------------------- | ----------- | --------------- | ---------------------- |
| \[Application/use case] | \[Workflow]      | \[Capability]          | \[Workaround]      | \[Condition]         | \[Range and assumption] | \[Timeline] | \[Source]       | \[High / Medium / Low] |

***

## 25. Appendix D: Suggested Interoperability Requirements Register

| Requested Feature | User / Operator Category | Chain / Corridor / Pathway | Frequency          | Urgency                | Blocker Status                                   | Adoption Consequence | Evidence Source | Confidence             |
| ----------------- | ------------------------ | -------------------------- | ------------------ | ---------------------- | ------------------------------------------------ | -------------------- | --------------- | ---------------------- |
| \[Feature]        | \[Category]              | \[Pathway]                 | \[Count/frequency] | \[High / Medium / Low] | \[Blocking / Important / Nice-to-have / Unknown] | \[Consequence]       | \[Source]       | \[High / Medium / Low] |

***

## 26. Appendix E: Suggested Interoperability Value-Flow Template

| Pathway    | Expected Cardano Inflow                       | Potential Outflow | Retention Mechanism | Cardano-Side Benefit | Dependency Risk        | Classification                                                                            | Evidence Source | Recommended Action                                               |
| ---------- | --------------------------------------------- | ----------------- | ------------------- | -------------------- | ---------------------- | ----------------------------------------------------------------------------------------- | --------------- | ---------------------------------------------------------------- |
| \[Pathway] | \[Users/liquidity/apps/transactions/partners] | \[Outflow risk]   | \[Mechanism]        | \[Benefit]           | \[High / Medium / Low] | \[Value-accretive / Mutual-value / Neutral-access / Dependency-risk / Value-leakage risk] | \[Source]       | \[Fund now / Coordinate / Partner / Monitor / Defer / No action] |

***

## 27. Appendix F: Suggested Provider and Partner Opportunity Template

| Provider / Partner  | Type                                                           | Current Cardano Status | Integration Blocker | Commercial Incentive | Technical Effort       | Demand Evidence | Mutual Benefit | Risk    | Priority               | Recommended Action |
| ------------------- | -------------------------------------------------------------- | ---------------------- | ------------------- | -------------------- | ---------------------- | --------------- | -------------- | ------- | ---------------------- | ------------------ |
| \[Provider/partner] | \[Bridge / Messaging / Wallet / Partner chain / Infra / Other] | \[Status]              | \[Blocker]          | \[Incentive]         | \[High / Medium / Low] | \[Evidence]     | \[Benefit]     | \[Risk] | \[High / Medium / Low] | \[Action]          |

***

## 28. Appendix G: Suggested Evidence Threshold Template

| Proposal / Opportunity Type                                             | Minimum Demand Evidence | Minimum Blocker Evidence | Minimum Value-Flow Evidence | Required KPIs | Decision Recommendation                                          |
| ----------------------------------------------------------------------- | ----------------------- | ------------------------ | --------------------------- | ------------- | ---------------------------------------------------------------- |
| \[L2 / Bridge / Partner chain / Wallet integration / Messaging / Other] | \[Evidence]             | \[Evidence]              | \[Evidence]                 | \[KPIs]       | \[Fund now / Coordinate / Partner / Monitor / Defer / No action] |
