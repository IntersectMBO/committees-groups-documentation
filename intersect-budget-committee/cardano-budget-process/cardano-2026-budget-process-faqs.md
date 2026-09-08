# Cardano 2026 Budget Process - FAQs

{% hint style="info" %}
This FAQs are about the budget process Approved in **this Info Action**  [**"**&#x43;ardano Budget Process Framework (facilitated by Intersect)"](https://gov.tools/governance_actions/e9693ed6b6465b2b46daaf641486a12b4b2946081634b5967b9d98897b0598fa#0)&#x20;
{% endhint %}

April 2026

_In short: This Info Action does not approve any spending. It asks one question: Should we use this structured framework to run the 2026 budget cycle? Actual spending requires separate on-chain votes by DReps._

## General Questions

<details>

<summary><strong>What is this Info Action, and what does a YES vote mean?</strong></summary>

The Info Action submitted Mar 5 2026 asks DReps whether the Cardano ecosystem should adopt a defined framework for coordinating the 2026 budget cycle. It records the Budget Process Framework on-chain.

A YES vote signals support for using this process to run the 2026 cycle. It does not approve spending, select any proposals for funding, or change the Constitution. Actual treasury spending only happens through separate Treasury Withdrawal Governance Actions (TWGAs), which DReps vote on individually later.

</details>

<details>

<summary><strong>Why are we suggesting this process?</strong></summary>

The proposed Budget Process Framework is intended to provide a structured, transparent, and predictable way to coordinate funding requests from the Cardano Treasury.

During the previous budget cycle, one of the funded initiatives was “Facilitate strategy, roadmap, and budget processes.” As part of that initiative, Intersect committed to rebuilding a coordinated budget process for 2026 and supporting the delivery and on-chain submission of a 2026 ecosystem budget.

The framework presented here is the result of that work. It builds on the lessons learned from the 2025 DRep-led budget process and incorporates feedback from DReps, vendors, and community participants.

The process introduces improvements such as clearer proposal guidance, alignment with the Vision 2030 strategic framework, minimum thresholds for funding requests, proposal deposits to discourage spam submissions, and a more efficient structure for preparing Treasury Withdrawal governance actions.

Importantly, the framework also helps lower barriers for smaller teams and grassroots innovators. Under the Cardano governance model, submitting a Treasury Withdrawal governance action directly on-chain requires a 100,000 ada deposit, which can be a significant barrier for smaller ecosystem participants. By coordinating proposals through the Intersect budget process, Intersect can aggregate approved proposals and submit Treasury Withdrawal governance actions on behalf of those that pass the approval threshold, allowing innovative ideas from smaller contributors to participate in the funding process without needing to independently meet the full governance deposit requirement.

<br>

</details>

<details>

<summary><strong>Why put this on-chain? Why is it an Info Action and not a constitutional amendment?</strong></summary>

Publishing the framework on-chain creates a verifiable signal of community support and a shared reference point for all participants. Future revisions are submitted as new Info Actions, building a transparent audit trail over time.

It is an Info Action - not a constitutional amendment - because it doesn't change the Cardano Constitution or any governance rules. It documents a process and signals community support for using it. An Info Action is the appropriate and sufficient mechanism for that purpose.

</details>

<details>

<summary><strong>Why does this only need 51% support to pass?</strong></summary>

51% is the on-chain constitutional threshold for Info Actions. This is a procedural vote about how the ecosystem runs its budget cycle, not a spending decision. The higher 67% bar applies later, when DReps are evaluating individual funding proposals in the off-chain Ekklesia poll, reflecting the stronger consensus required before proposals advance to Treasury Withdrawal Actions.

</details>

<details>

<summary><strong>Why do we need a vision/strategy info action AND a budget process info action each cycle? That seems like a lot.</strong></summary>

Each is a distinct governance decision. The vision/strategy provides long-term direction and KPIs. The Net Change Limit (NCL) sets the fiscal guardrail. This Budget Process Info Action establishes the procedural rules. Together they provide direction, constraint, and a fair process - and they answer different questions.

They don't necessarily need to be resubmitted from scratch each year. The framework specifies that amendments are made by submitting a new Info Action, so if the process is largely working, future cycles may only require lighter updates.

</details>

<details>

<summary><strong>What happens if it passes?</strong></summary>

Intersect begins implementing the process - publishing templates, opening the submission platform, running the review and feedback phases, organising off-chain DRep voting on Ekklesia, and preparing TWGAs for proposals that meet the required thresholds. The framework itself does not allocate funding; it defines the process used to evaluate proposals before they move to the on-chain stage.

</details>

<details>

<summary><strong>What happens if it fails?</strong></summary>

The budgeting process would not move forward in its current form. Intersect and the Budget Committee would review DRep feedback and either revise and resubmit the framework or explore alternative approaches. A rejection doesn't prevent treasury withdrawals - anyone can still submit TWGAs independently on-chain at any time.

</details>

<details>

<summary><strong>What has changed from 2025</strong></summary>



* Standardised proposal template - all proposals follow the same structure, making comparison easier
* Strategic alignment requirement - proposals must map to Cardano Vision 2030 and identify relevant KPIs
* Structured refinement loop - private drafting, community feedback, and deep review before proposals are locked for voting
* Clearer thresholds - the 67% off-chain approval bar is explicitly defined, with two tiers of consolidated TWGAs
* Treasury donation requirement - 1,000 ada non-refundable donation to reduce spam submissions
* NCL compliance checks - proposals are ranked by DRep support and allocated against the available Net Change Limit in order

Waiting list mechanism - proposals that meet the 67% threshold but can't fit within the NCL are held rather than rejected outright

</details>

<details>

<summary><strong>What is Ekklesia and why is Hydra voting done first?</strong></summary>

Ekklesia is the platform used for proposal submission, feedback, and DRep advisory polling during Stages 1 and 2. The hydra polling stage helps prioritise proposals before they reach the blockchain, reducing governance congestion and allowing the community to compare initiatives more easily. Final funding decisions still occur on-chain. DReps vote independently on any TWGAs submitted.

</details>

<details>

<summary><strong>Why are there two approval tiers (67% and 75%), and how do they work?</strong></summary>

The framework separates proposals into two groups to reflect different levels of DRep confidence: ≥75% support and ≥67% to <75% support. These are then consolidated into two separate Treasury Withdrawal Governance Actions:

1. Tier 1 TWGA - proposals with ≥75% DRep support, ranked by support level and allocated up to the available NCL
2. Tier 2 TWGA - proposals with ≥67% to <75% support, ranked by support level and allocated against remaining NCL

In both cases, proposals are ranked in order. If including a proposal would exceed the remaining NCL, it goes on a waiting list rather than being rejected - it may still be submitted if higher-ranked proposals fall away or NCL headroom increases.

</details>

<details>

<summary><strong>What exactly counts as "participating stake" for the 67% threshold?</strong></summary>

The 67% threshold is calculated against the **total stake of all DReps who participated in the Ekklesia pol**l, not just those who voted on a specific proposal.

In practice: based on the 2025 cycle, approximately 4 billion ada participated in the Ekklesia poll. Under 2026 parameters, a proposal would therefore need approximately **2.68 billion ADA in YES** votes to pass.

This means DReps who participate in the round but don't vote on a specific proposal effectively dilute that proposal's YES percentage. Being present in the poll is not the same as voting YES.

### Rules

ONLY DReps who have signed in to Ekklessia and cast a yes or no vote on at least one proposal contribute to the participating stake calculation of the poll.

ONCE a DRep casts a yes or no vote on at least one proposal, their stake is included in the participating stake calculation for all proposals in the poll.

WHEN a DRep casts an abstain vote their stake amount is subtracted from the total participating stake for that proposal.<br>

</details>

<details>

<summary><strong>Why does not voting effectively act like a “No” vote?</strong></summary>

For Cardano governance actions, approval requires a majority of the active voting stake to support the proposal. This means the required threshold is measured against the total voting power that could participate, not just the votes that are cast.

Because of this, not voting does not contribute toward reaching the approval threshold. In practice, this has the same effect as a “No” vote: it makes it harder for the proposal to gather the level of support required to pass.

This design helps ensure that governance actions only pass when there is clear and meaningful support across the ecosystem, rather than being approved by a small number of active voters during periods of low participation.In simple terms:

* Yes → counts toward the proposal reaching the approval threshold
* Abstain → signals participation without supporting or opposing
* Not voting → provides no support toward the threshold, which has the same practical effect as a “No” vote

This is why active participation matters. If DReps want to influence outcomes, casting a vote, whether Yes, No, or Abstain, is the most effective way to signal their position.

</details>

<details>

<summary><strong>How does the Net Change Limit (NCL) work with this process, and what happens if proposals exceed it?</strong></summary>

The NCL caps how much can be withdrawn from the treasury in a given period. The 2026 NCL is **350 million ada**. Proposals are ranked by DRep support and allocated in order until the NCL is reached. Proposals that meet the 67% threshold but can't fit within the remaining NCL are placed on a waiting list and may be submitted later if capacity becomes available. If community appetite supports it, Intersect may submit a new NCL governance action.

</details>

## **For DReps**

<details>

<summary><strong>What am I actually endorsing with a YES vote, and what am I NOT endorsing?</strong></summary>

You are signalling that Intersect should proceed with facilitating a structured, community-reviewed budgeting cycle for 2026. You are not pre-approving any spending, endorsing any specific proposals, or delegating your governance authority. You retain full discretion on all future treasury withdrawal votes - including the ability to vote NO on any TWGA regardless of how it performed in the off-chain process.

</details>

<details>

<summary><strong>What if I vote NO or abstain?</strong></summary>

A NO vote signals you don't support using this framework for the 2026 cycle. An abstain counts toward quorum but not toward the 51% threshold. Note that DReps who are active but don't vote effectively reduce the YES percentage - their delegated stake counts as not supporting the action. If you have specific concerns, sharing your rationale publicly gives the community and Intersect the opportunity to address them in a future revision.

</details>

<details>

<summary><strong>I'm concerned about Intersect having too much control. Should I vote NO?</strong></summary>

This is a fair question. A few points to consider: Intersect is a facilitator and Administrator,  it doesn’t decide which proposals get funded. Final funding decisions rest entirely with DReps through on-chain governance. The process is optional, proposers can submit TWGAs independently at any time. The independent Oversight Committee (NMKR, Dquadrant, SundaeLabs, Xerberus, and the Cardano Foundation) provides checks on Intersect's administrative actions via multi-sig smart contracts.

If the framework fails, there is no alternative structured process,  only uncoordinated independent submissions. The framework is designed to constrain Intersect's role, not expand it.

</details>

<details>

<summary><strong>Does this give Intersect control of the treasury?</strong></summary>

No. The treasury can only be spent through TWGAs approved by DReps under constitutional requirements. This framework describes how proposals are organised and administered and grants Intersect no authority over treasury funds. Even after a proposal passes the off-chain review, it must still pass an on-chain vote. Intersect's role is to carry out decisions DReps have already made, not to make those decisions.

</details>

<details>

<summary><strong>When does voting close?</strong></summary>

Check[ GovTool](https://gov.tools/) for the current status and expiration date of this governance action.

</details>

## **For Proposers and Vendors**

<details>

<summary><strong>Do I have to use this process? Can I bypass it completely?</strong></summary>

No, participation is optional. Anyone can submit Treasury Withdrawal Governance Actions directly on-chain at any time, outside this framework entirely. Those proposals still need to follow constitutional rules and require DRep endorsement and a constitutionality check. Note that direct on-chain TWGA submission requires a 100,000 ADA governance deposit, which the Intersect process helps smaller teams avoid by aggregating proposals into shared actions.

</details>

<details>

<summary><strong>What is the 1,000 ada treasury donation, and how was the amount decided?</strong></summary>

The 1,000 ada donation is a non-refundable payment to the Cardano Treasury (not to Intersect) required to enter the process. It must be paid from the same wallet used to submit your proposal, so reviewers can verify identity and wallet ownership. One donation per proposal,  multiple submissions require separate donations.

The requirement originated from DReps, not Intersect, and has strong support from both DReps and vendors. The 1,000 ada figure balances discouraging low-effort submissions without being prohibitive. This requirement only applies to this process - direct on-chain submissions don't require it.

**Making the donation does not guarantee** proposal approval, on-chain execution, funding, or that Intersect will act as Administrator.

</details>

<details>

<summary><strong>Why is there a 100,000 ada minimum proposal size?</strong></summary>

Based on direct engagement with the top 50 DReps and major vendors during framework development, stakeholders suggested a minimum range of 50,000–500,000 ada. The 100,000 ada minimum reflects that feedback. It focuses the process on strategically meaningful initiatives. The risk of budget inflation is mitigated by the required detailed cost breakdown, which lets reviewers benchmark across proposals. Smaller projects can still submit independently outside this process.

</details>

<details>

<summary><strong>When can I submit a proposal?</strong></summary>

The proposal window opens in early April, with community feedback and refinement running April through May, and off-chain DRep advisory voting in mid-to-late May.

</details>

<details>

<summary><strong>What strategic framework should I align with?</strong></summary>

Proposals must align with Cardano Vision 2030 - selecting a specific Strategic Pillar and linking to relevant ecosystem KPIs. Stating your work is "good for Cardano" is not sufficient. You need to explain specifically how your proposal drives measurable impact against those KPIs.

</details>

<details>

<summary><strong>What if Intersect declines to act as Administrator for my proposal?</strong></summary>

You as the proposer would be responsible for preparing and submitting the TWGA, confirming Administrator obligations, and obtaining DRep endorsement. Intersect's administrative role is optional support, not a requirement.

</details>

## **About Intersect's Role and Oversight**

<details>

<summary><strong>What exactly is Intersect's role in this process?</strong></summary>

Intersect facilitates and administers, it does not govern. Its responsibilities cover publishing templates, reviewing proposals for completeness, consolidating approved proposals into TWGAs, onboarding vendors, handling compliance and legal checks, supporting milestone payments, and providing transparent reporting. It does not decide which proposals receive funding.

</details>

<details>

<summary><strong>Who is on the Oversight Committee and what do they actually do?</strong></summary>

The independent Oversight Committee consists of NMKR, Dquadrant, SundaeLabs, Xerberus, and the Cardano Foundation. They participate in the multi-sig smart contract framework and act as a check on Intersect's administrative actions - for example, blocking a disbursement if the amount differs from what was approved. Their mandate is strictly limited to that check-and-balance role. They have no say in which proposals receive funding.

Treasury funds are held in smart contracts requiring multi-sig authorisation - not unilaterally controlled by Intersect. All activity is transparent and auditable on-chain. The contracts were built by SundaeLabs ([GitHub repository](https://github.com/SundaeSwap-finance/treasury-contracts)).

</details>

## **Cardano Vision 2030 alignment**

<details>

<summary><strong>What is Cardano Vision 2030?</strong></summary>

The Cardano Vision 2030 is a strategic framework recently approved by the community, setting long-term goals and ecosystem KPIs across infrastructure, adoption, and governance. Proposals in the 2026 budget process are expected to align with it, ensuring treasury funds are deployed towards outcomes the community has already endorsed rather than reactively.

<br>

</details>

## **Reference materials**

<details>

<summary><strong>Where can I find the full Cardano Budget Process Framework document?</strong></summary>



* IPFS anchor: `ipfs://bafkreidkxk3akjqukgyuxp65g2pesfbhk2miepg7cd6tq7u2hujxmxqzvu`
* Governance Action ID: `e9693ed6b6465b2b46daaf641486a12b4b2946081634b5967b9d98897b0598fa#0`
* CIP-129 ID: `gov_action1a95na44kgedjk3k64ajpfp4p9d9jj3sgzc6tt9nmnkvgj7c9nraqq7g4d2u`
* Intersect article:[ Building a 2026 Ecosystem Budget for Cardano](https://intersectmbo.org/news/building-a-2026-ecosystem-budget-for-cardano)
* GovTool: [Link to info action](/broken/pages/wQ1mBs0wLKrD9aTyacM3) "Cardano Budget Process Framework (facilitated by Intersect)"

</details>

