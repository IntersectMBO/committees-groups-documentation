# November 3rd, 2025 Budget Comm Minutes

## **Budget Committee Weekly Meeting — November 3rd, 2025**

**Date:** November 3, 2025\
**Time:** Weekly Budget Committee call (time not specified in transcript)\
**Attendees:**

* **Budget Committee:**
  * Kris Kowalski – Chair
  * Megan Hess – Vice Chair
  * Shunsuke Murasaki – Member
  * Dimitri – Member
  * Jose Velazquez – Member
  * Lloyd Duhon – Budget Secretary
* **Guests / Contributors:**
  * Simo Simovic – Project Manager, Budget Process
  * Jack Briggs – Interim Executive Director, Intersect
  * Giorgio Zanetti – Cardano Foundation (CTO)
  * Nicolas (Nico) Cerny – Governance Lead, Cardano Foundation
  * Danielle (IOG / MVG)
  * Dave (advisor/observer)

**Regrets / Not present:**

* Rita Mistry

Quorum was confirmed once Jose joined the call.

***

### **1. Opening and Context**

* Lloyd opened the meeting, welcomed committee members and guests, and confirmed **quorum** for any decisions if needed.
* Quick update:
  * **Committee elections** are on track; results expected in a little over a week following audit and validation.
  * This meeting is primarily dedicated to **Net Change Limit (NCL)** discussions, building on earlier work.

***

### **2. Net Change Limit (NCL) – Modeling and Findings**

#### 2.1 Dimitri’s NCL Modeling

Dimitri presented his earlier NCL work (originally prepared around 12 October):

**Key assumptions / parameters used:**

* Max ADA supply: **45B**
* Current circulating supply: \~**38B** ADA
* Remaining ADA in reserves; distributed each epoch via monetary expansion
* Treasury balance: assumed approx. **1.5B** ADA
* Monetary expansion: \~**0.3% of reserves per epoch**
  * **20%** of expansion → Treasury
  * **80%** → staking rewards
* Fees per epoch: modeled at **80,000 ADA/epoch**, with scenarios at 160,000 and 800,000 ADA/epoch
* Starting NCL test value: **275M ADA/year**

**Core results and conclusions:**

* Treasury receives roughly **4M ADA per epoch** from reserves (20% of expansion), declining over time as reserves shrink.
* Fees currently contribute only a **small fraction** compared to reserve-based inflows.
* With an **annual NCL of \~275M ADA** and a multi-year horizon (e.g., 5 years):
  * Year 1 shows a **small deficit** (\~5M ADA).
  * Over \~5 years the cumulative deficit is on the order of **\~450M ADA**.
  * That would reduce the Treasury from \~1.5B to \~1.0B ADA (approximately a **30% reduction** over 5 years).
* Even if fees **double** (80k → 160k ADA/epoch), the impact on Treasury balance is still **immaterial** vs. reserves.
* Even at **10x fees** (80k → 800k ADA/epoch), fee inflows remain relatively small compared to reserve-driven inflows and do not fully offset a high NCL.
* Modeling fee growth over time (e.g., 100% yearly growth) still does **not materially change** the medium-term deficit pattern at a 275M ADA NCL.

**High-level conclusions:**

1. To **fully match** Treasury inflows with outflows purely from current reserve + fee assumptions, the **NCL would need to decline over time**, not remain fixed.
2. Setting a **fixed NCL above replenishment** (e.g., 275M ADA) implies a **planned reduction** in Treasury over time, which may be acceptable if seen as **investment** rather than “dwindling.”
3. Other revenue streams (e.g., **yield from investments, loans like SNEK, structured Treasury strategies**) are **not yet modeled** and could materially change the picture.
4. The model is an **approximation**, but adequately captures the **principal dynamics** of the monetary expansion and Treasury mechanics.

***

#### 2.2 Strategic Framing: Investment vs. “Dwindling”

Several participants (Jack, Kris, Lloyd, Jose, Dave) responded to Dimitri’s analysis:

* **Finite resource reality:**
  * The model is a reminder that Cardano’s Treasury is **finite** under current assumptions; without new income sources, it will be drawn down over time.
* **Framing matters:**
  * Kris cautioned against a purely “dwindling Treasury” narrative:
    * Even after a 5-year horizon and a 30% drawdown, a Treasury of **\~1B ADA** is still substantial.
    * The core question is whether the ecosystem is _using_ its resources to **grow** the network or letting them sit idle.
* **Sovereign wealth fund analogy:**
  * Lloyd drew parallels to **Dubai’s sovereign wealth fund**, founded with a significant cash position that was **actively invested**, not hoarded:
    * They strategically invested down cash into technologies and assets that generated outsized returns.
    * Cardano should similarly treat the Treasury as a **sovereign wealth fund**—investing wisely to grow the ecosystem and generate **long-term returns**, not just protecting nominal principal.
* **Household / mattress analogy:**
  * Dave compared the Treasury to **cash under a mattress**:
    * Without deployment into productive assets, funds are effectively idle.
    * In his own investing behavior: minimal long-term cash balances, preferring deployment into startups, equities, crypto, and hedging instruments.
    * Core point: treasury capital should be deployed into **value-creating initiatives**, particularly those that directly strengthen network metrics (e.g., transactions, usage).
* **Fee-based sustainability is unrealistic in the short term:**
  * Giorgio later reinforced that **matching the NCL purely with fees** would require roughly a **500x increase in transaction fees**, which is not realistic short term.
  * However, Cardano has a **built-in Treasury mechanism** (unlike many chains), so there is at least a **light at the end of the tunnel** if usage grows.

***

### **3. Treasury Yield, Investment Vehicles & Risk Management**

#### 3.1 Need for Yield & Investment Structures

Discussion shifted to **how** the Treasury could generate yield and be managed more like a sovereign wealth fund:

* Dimitri and Lloyd noted that the **Dubai example** illustrates the transition from cash to diversified investment portfolios.
* To replicate this, Cardano would likely need:
  * An **investment committee** or specialized **Treasury management entity**.
  * Clear **mandates** and **guardrails** (asset classes, risk tolerances, geographic diversification, etc.).
  * Repeatable processes for **deploying capital** and **returning yield** to Treasury.
* Giorgio described Cardano Foundation’s own practice:
  * CF has its **own treasury** diversified across ADA, Bitcoin, stocks, and bonds.
  * They model scenarios where, at current burn rates, funds could be depleted in **\~8 years**, and then calibrate 3-year budgets accordingly.
  * This thinking (finite runway, multi-year budget horizons) could inform Cardano’s **on-chain Treasury strategy**.

#### 3.2 Possible Structures (SPVs, Custodians, DeFi, etc.)

Jack and Lloyd explored possible structural approaches:

* **Off-chain SPVs / treasury companies**:
  * One option: form **limited-purpose entities** in major financial centers (e.g., London, New York, Asia) entrusted with executing low-risk strategies (e.g., **stable pairs**, yield instruments).
  * These would be **licensed, bonded custodians** with strong regulatory accountability.
  * Legal structures would be in place to ensure **returns flow back to Treasury**.
* **On-chain DeFi strategies:**
  * Longer-term ambition is for Treasury to deploy directly into **on-chain DeFi**, but:
    * Current Treasury technical design is “**unsophisticated**” (simple ledger, no direct yield-bearing functionality).
    * Delegated authority or intermediating entities are required until on-chain governance and technical solutions mature.
* **Risk vs. governance trade-offs:**
  * Using global custodians (e.g., equivalent to those serving major asset managers) could offer robust **risk management** and **compliance**.
  * However, community expectations and decentralization ethos require careful **education** and **transparent governance** around any off-chain arrangements.
* **Related ecosystem precedents:**
  * Giorgio referenced the **stablecoin liquidity initiative**, which faced substantial governance pushback and ultimately required a **DRep recourse smart contract** instead of a simple multisig.
  * Jack mentioned **Avalanche’s treasury company** as an example of a chain spinning up a formal treasury entity; Cardano is comparatively mature in governance, but will still need to navigate similar design choices.

***

### **4. NCL Path Forward – Interim vs 2026-Only**

#### 4.1 Jack’s Question: Next Steps on NCL

Jack summarized the decision problem:

* Board had previously indicated interest in a **temporary NCL** to “keep the lights on” for a six-month period, plus a separate NCL accompanying the full **2026 budget process**.
* Proposal for the committee to consider:
  * Use Dimitri’s modeling as the **baseline** (e.g., 275M ADA NCL).
  * Overlay a **strategic investment premium** (e.g., higher NCL in 2026 to reflect intentional front-loaded investments).
  * Decide on **concrete NCL numbers and framing** in time for on-chain governance (ideally before the December holiday period).

#### 4.2 Giorgio’s Recommendation

Giorgio offered a strong recommendation:

* **Avoid an interim NCL** and go **directly to a 2026 NCL**:
  * Two separate NCL ballots (temporary + annual) would **complicate governance**, increase cognitive load and fatigue.
  * Better to design one coherent **annual NCL**, clearly justified by investment strategy and Treasury modeling.
* He also provided current-year context:
  * As of late 2025, roughly **272M ADA** had been withdrawn from the Treasury.
  * By year-end, approximately **270M ADA** would be replenished (reserves + fees), leaving the Treasury roughly **flat** vs. the start of the year.
  * Of this, fees contributed only \~**0.5M USD** equivalent – underscoring how small the fee component remains today.

#### 4.3 Process / Timeline

* Simo proposed using the **Wednesday weekly call** (following this meeting) to:
  * Deep-dive NCL options and **agree a committee recommendation**.
  * Consider travel constraints (Cardano Summit) and quorum issues; Wednesday may offer better availability than the next Monday call.
* Jack will:
  * **Return to the Intersect Board** with:
    * The committee’s emerging preference for a **single annual NCL** (rather than a temporary one).
    * Context from Dimitri’s modeling and the **investment-forward narrative**.
  * Clarify that there are now **three evolving innovation areas** (see Section 6).

***

### **5. Yuta’s Constitutional Amendment Proposal**

The second major agenda item concerned **Yuta’s proposed Constitution amendment**, which notably:

* **Removes the requirement for separate Budget Info Actions**, allowing budget proposals to go straight to Treasury withdrawal with a single governance action.
* **Tightens** or changes the language around **independent audits** for Treasury withdrawals.
* Adjusts definitions and removes or modifies some existing guardrails (dispute resolution, rights language, etc.).

#### 5.1 High-Level Overview (Nico)

Nico summarized the key changes:

* Primary change: **merge Budget Info Actions and Treasury Withdrawals**:
  * Avoids duplicative voting (first on Info Action, then on Treasury Withdrawal) for essentially the **same proposal**.
  * Streamlines governance and reduces proposal and voter fatigue.
* Current Constitution vs. proposed language on audits:
  * **Current Constitution:**
    * Any governance action requesting ADA from Treasury must include an allocation for **independent audit costs**.
  * **New proposal:**
    * Requires that Treasury withdrawal processes explicitly **appoint independent auditors** and specify **oversight processes**.
    * More explicit that an **auditor** (not just “some audit”) must be involved.
  * Nico’s view: conceptually similar obligations, but with slightly different wording and emphasis.

#### 5.2 Concerns Raised (Murasaki, Dave, Lloyd, Jack)

**Murasaki’s and Emurgo’s concerns:**

* Wording such as “**appoint independent auditors**” is **ambiguous**:
  * Who exactly appoints them? Intersect? The project team? Another institution?
  * Ambiguity could lead to **conflicting interpretations** by different Constitutional Committee members or governance actors.
* Additional issues spotted by Dave and colleagues on a quick review:
  * Some **definitions** (e.g., of NCL) appear less precise than current language, potentially allowing Treasury withdrawals outside a clearly bounded NCL framework.
  * **Dispute resolution** requirements appear weakened or removed, increasing risk if disagreements arise.
  * Some language could be read as **reducing rights of ADA holders using third-party custody**, which may or may not be intended policy.
  * Small wording “nits” can become **large sources of contention** in constitutional interpretation.

**Audit scope and roles (Lloyd & Jack):**

* Positive change: the amendment explicitly references **financial audits**, which avoids prior confusion over whether the Constitution was demanding **technical audits** for _all_ proposals.
* However, clarity is needed on:
  * Distinction between **administrator’s role** (e.g., Intersect as process administrator reviewing milestone reports) and **independent auditor’s role** (deep financial audit).
  * Expectations of the community around **how far Intersect must go** into recipient bookkeeping – current practice focuses on **work delivered**, not full forensic accounting.
  * Potential need for explicit language that:
    * Intersect is an **administrator**, not the auditor.
    * Technical audits are only required in specific cases (e.g., parameter changes, hard forks), which are already captured in **guardrail scripts**.

#### 5.3 Yuta’s Position & Process

* Murasaki reported that in direct conversation, **Yuta was receptive** to feedback and even open to dropping or refining parts of the audit wording if necessary.
* Nico noted:
  * If this proposal **fails** in its current form, Yuta has indicated he would **incorporate feedback** (e.g., from CF, Emurgo, Civics) and **resubmit** an improved version.
  * Yuta is deeply motivated to improve the Constitution and is willing to iterate.
* Civics Committee and Constitutional Amendment Working Group:
  * They have already started a more **formal amendment process** and intend to **loop Utah in** more closely.
  * Over time, this should lead to amendments that:
    * Preserve the **benefits** (e.g., removal of Budget Info Actions).
    * Resolve **ambiguities** and tighten definitions to avoid unnecessary escalations to the Constitutional Committee.

#### 5.4 Committee Sentiment

* Overall sentiment is **supportive of the intent**:
  * Strong support for **removing Budget Info Actions** and reducing governance friction.
  * Acknowledgement that some ambiguities may ultimately be resolved by the **Constitutional Committee**, which is part of the design.
* At the same time, committee members:
  * Want to avoid **unintended consequences** arising from small language changes.
  * Prefer that **feedback from CF, Emurgo, Civics, and Budget Committee** be incorporated into future iterations.

***

### **6. Additional Budget Process Topics**

#### 6.1 Vision 2030 – Funding Innovation in Governance & Smart Contracts

* Lloyd and Jack noted recurring constraints related to **smart contract tooling for funding and Treasury governance**:
  * Examples: DRep recourse contracts, Treasury management contracts, clawback mechanisms, improved DRIPS-like contracts.
* The committee would like to **explicitly contribute** to Vision 2030 by recommending:
  * A dedicated program/fund for **innovation in funding mechanisms and governance smart contracts**.
  * This could include a **Catalyst Fund 16 category** focused on **stablecoin liquidity** and other financial primitives feeding back yield to Treasury (as referenced by Giorgio and Jack).

#### 6.2 Proposal Deposit / Fee and NCL Minimum Thresholds

Lloyd summarized evolving thinking based on DRep feedback:

* **Deposit / fee concept for 2026 budget process:**
  * Simple **fee in ADA** (e.g., **500–1,000 ADA**) per proposal.
  * Paid **directly to the Treasury**, not to Intersect.
  * Proposer includes the **transaction hash** in their proposal as proof.
  * This acts as a **financial spam filter** while avoiding additional overhead for Intersect (no need to manage or re-route funds).
* **DRep feedback:**
  * Broad support among DReps for a **fee in the 500–1,000 ADA range**.
  * Individual suggestions ranged from **250 ADA** up to **5,000 ADA**, but most cluster around 500–1,000 ADA.
* **Non-monetary and monetary thresholds:**
  * Consider also a **minimum threshold** for Treasury withdrawals (e.g., 50,000–500,000 ADA) as a **monetary spam filter** for NCL-related actions.
  * Combined with process guardrails, this creates both:
    * **Non-monetary filters** (e.g., qualification questions, documentation), and
    * **Monetary filters** (proposal fee, minimum request) to protect governance bandwidth.

Lloyd requested that Jack include these three evolving **innovation items** in his conversations with the Board:

1. **NCL structure:**
   * Preference for a **single annual NCL** (not a short-term interim plus a separate 2026 NCL).
2. **Proposal deposit / fee:**
   * Direct fee from proposers to **Treasury**, with TX ID included in proposals; Intersect does **not** hold the funds.
3. **NCL minimum threshold:**
   * A **minimum ADA value** per Treasury withdrawal or per NCL action to discourage low-value spam and align incentives.

Jack agreed and will raise these topics with the Board.

***

### **7. Decisions & Action Items**

#### 7.1 Decisions (Informal Consensus)

* The committee **welcomes** Dimitri’s NCL modeling as the baseline analytical tool.
* There is **broad support** for framing the Treasury as a **sovereign wealth fund**, focused on **smart investment** rather than purely preserving nominal balance.
* The committee is **supportive in principle** of:
  * Removing **Budget Info Actions** via constitutional amendment.
  * Introducing a **proposal fee** paid directly to Treasury.
  * Exploring a **single annual NCL** rather than a short interim plus separate annual NCL.

Formal decisions on concrete numbers and constitutional positions are deferred to future meetings.

#### 7.2 Action Items

| Action                                                                                 | Owner                                       | Notes                                                                                                                         |
| -------------------------------------------------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Refine NCL recommendation (annual vs interim, level, framing) using Dimitri’s model    | Budget Committee (lead: Lloyd & Dimitri)    | Use upcoming **Wednesday** call to aim for a consensus NCL figure and narrative.                                              |
| Present NCL and process innovations to Intersect Board                                 | Jack                                        | Cover annual NCL preference, strategic investment overlay, proposal fee, and NCL minimum threshold.                           |
| Provide clear task breakdown / homework for NCL decision                               | Simo & Lloyd                                | Prepare post-call outline of steps and responsibilities so committee members can prepare for Wednesday.                       |
| Continue engagement with Utah on constitutional amendment feedback                     | Civics / CF (Nico, Murasaki)                | Share concerns on audit wording, definitions, and dispute resolution; coordinate with Constitutional Amendment working group. |
| Integrate “funding innovation in governance smart contracts” into Vision 2030 feedback | Budget Committee                            | Include references to Treasury governance, DRIPS-like contracts, and funding mechanisms in Vision 2030 submissions.           |
| Explore Catalyst category for stablecoin liquidity / Treasury-yield experiments        | Jack & Giorgio (coordination with Catalyst) | Use Catalyst Fund 16 (or later) as a venue for experimentation and community education.                                       |

***

### **8. Adjournment**

* Jack noted he needed to join another call, and the meeting moved toward close.
* Lloyd thanked all participants, especially external guests (Giorgio, Nico, Dave, etc.), for their contributions.
* The next major working discussion on the **NCL decision** is scheduled for the **Wednesday weekly call**.
* Meeting adjourned with a reminder to prepare for Wednesday’s deeper NCL working session.
