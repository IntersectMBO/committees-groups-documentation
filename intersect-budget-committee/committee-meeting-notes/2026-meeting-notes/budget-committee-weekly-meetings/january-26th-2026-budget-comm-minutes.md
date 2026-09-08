# January 26th, 2026 Budget Comm Minutes

## **Budget Committee Weekly Meeting — January 26th, 2026**

**Date:** January 26, 2026\
**Time:** 07:56 EST

**Attendees:**\
Christina Gianelloni, Colleen O’Beirne, Dimitri (Dynamic Strategies), Eric Helms (SCATDAO), Georgia Hutton (Delivery Assurance), Gintama, Jack Briggs (Executive Director), Kriss Baird, Kristijan (Chris) Kowalsky, Lloyd Duhon (Secretary), Megan Hess (Chair), Nicolas Cerny, Ossong, Otávio Lima, Simo Simovic (Project Manager)

**Quorum:** Confirmed.

***

### **1. Opening and Agenda**

Lloyd opened the meeting, confirmed quorum, and outlined two primary objectives:

1. **Status update and confirmation on the PRD and development agreement** for the budget tooling.
2. **Usability review of the budget proposal mockup** (template and flow) to provide concrete feedback to developers.

A secondary focus was continued refinement of the **Budget Process Info Action (BPIA)** and alignment on tentative timelines.

***

### **2. PRD Approval and Development Agreement Update**

#### **2.1 PRD Status**

* Simo confirmed that the **PRD was approved by the Budget Committee** in the prior Wednesday working session.
* The PRD defines:
  * Core features required for proposal submission and feedback loops
  * Roles (DRep, proposer, viewer, admin)
  * Validation rules (including treasury fee verification)
  * Open API requirements

#### **2.2 Development Agreement**

* Agreement reached with the **Ecclesia (Adam Dean) team** to begin development **this week**.
* Development plan:
  * \~6 weeks of development, targeting **late February / early March**
  * Iterative check-ins during development to review form behavior and usability
  * Separate QA review by an additional party (not the same team that builds the tool)
* Tool will be **open-sourced after this cycle**, benefiting the broader ecosystem.

**Funding**

* Development costs will be covered by **Intersect’s budget**.
* Final pricing was still being confirmed at the time of the meeting (pending confidentiality clearance).

***

### **3. Budget Proposal Mockup Walkthrough (Usability Review)**

Nico presented a **mockup of the proposal submission flow**, derived from the committee’s Excel template but rendered in a user-friendly format for developers.

#### **3.1 Proposal Intake and Identity**

* Proposers provide:
  * Project title and executive summary (intentionally short)
  * Legal entity details
  * Administrative and technical contact points
* Emphasis on collecting **delivery assurance–relevant data upfront** to reduce post-approval friction.

#### **3.2 Strategic Alignment**

* Proposers must select a **Focus Area** from the Cardano 2030 framework.
* Focus Area selection auto-populates:
  * Pillar
  * Thematic area
  * Description (static, non-editable)
* Committee consensus:
  * No “custom” focus areas; proposals must fit within existing 2030 scope.

#### **3.3 KPI Mapping**

* Proposers must map proposals to relevant **2030 KPIs**.
* For each KPI:
  * 2030 target is shown
  * Proposer specifies their **contribution toward that target**
* Discussion emphasized:
  * Comparability across proposals
  * Avoiding vague KPI claims
  * Clear accountability for outcomes

#### **3.4 Timeframe and Milestones**

* Supports **annual and multi-year proposals**:
  * Annual proposals: single-year plan
  * Multi-year proposals: year-by-year milestones and budgets
* Each milestone requires:
  * Objectives
  * Budget breakdown by category (e.g., dev, research, legal, marketing)

#### **3.5 Budget Summary and Context**

* Automatic summary view for DReps showing:
  * Total requested amounts
  * Category totals
* Additional required context:
  * New initiative vs continuation
  * Prior funding (constitutional requirement)
  * Potential suppliers

#### **3.6 Treasury Fee Verification**

* Proposers must submit:
  * **Transaction hash** proving treasury fee payment
* Tool logic:
  * Same wallet used for fee payment must authenticate into the tool
  * Prevents reuse of another party’s transaction

#### **3.7 Key Usability Feedback**

* Strong support for:
  * Short executive summaries (avoid “essay-length” submissions)
  * Dynamic fields reducing proposer workload
  * Clear comparability for DReps
* Delivery Assurance and Legal teams will review for contracting and compliance needs.

***

### **4. Key Discussion Points**

#### **4.1 Payment Denomination (ADA vs Stablecoins)**

* Current default: **ADA-denominated treasury withdrawals**.
* Stablecoin requests may be possible but require:
  * Legal review (risk of being considered a money processor)
* Decision deferred pending legal guidance.

#### **4.2 Incentives for DRep Participation**

* Ecclesia mentioned potential built-in incentive mechanisms.
* Committee concerns:
  * Incentives must not come from third parties without governance approval
  * Risk of skewed incentives toward large holders
* Consensus:
  * **Not in scope for this cycle**
  * Revisit after core process stabilizes

#### **4.3 Proposer Transparency and Track Record**

* Strong agreement that proposals must include:
  * Clear legal entity identity
  * Jurisdiction
  * Track record (“about” section)
* Goal: enable DReps to assess credibility, especially for first-time or external teams.

***

### **5. Budget Process Info Action (BPIA) — Review and Next Steps**

#### **5.1 Current State**

* Simo shared the updated BPIA draft with:
  * Expanded rationale for each stage (0–4)
  * Clarification of prerequisites and delegated authority
* Committee emphasized:
  * BPIA should describe **requirements**, not rigid dates
  * Process must be repeatable year-to-year

#### **5.2 Additional Transparency Request**

* Nico requested:
  * A **spreadsheet / CSV** summarizing 2025 funded proposals:
    * Status
    * Milestones
    * Paused or delayed items
* Jack confirmed:
  * Intersect is preparing a **DRep resource pack** and API for treasury data export.
  * This will be published ahead of the next budget cycle.

#### **5.3 Timeline Considerations**

* Tentative internal timeline shared (clearly labeled as **non-binding**).
* Chris Baird cautioned:
  * Timeline is aggressive
  * Tool readiness and communications must be solid before announcing dates
* Consensus:
  * Dates should be published **only after high confidence** in tooling and comms readiness.
  * Buffer time is essential to avoid 2025-style confusion.

***

### **6. Action Items**

| Action                                        | Owner                     | Notes                                   |
| --------------------------------------------- | ------------------------- | --------------------------------------- |
| Begin Ecclesia tool development per PRD       | Simo / Ecclesia team      | 6-week build + independent QA           |
| Share PRD link with all committee members     | Simo                      | Already posted in chat                  |
| Compile usability feedback from mockup        | Committee                 | Feed directly to dev team               |
| Delivery Assurance + Legal review of template | Georgia / Intersect teams | Contracting, compliance, data needs     |
| Prepare proposal status spreadsheet / CSV     | Intersect (Jack / team)   | DRep transparency ahead of budget cycle |
| Refine BPIA language (final edits)            | Committee                 | Target vote on Wednesday                |
| Reassess and finalize tentative timeline      | Committee                 | After tooling confidence improves       |

***

### **7. Adjournment**

Lloyd thanked the committee for their continued effort and emphasized the importance of stabilizing the process before scaling participation.

**Next steps:**

* Wednesday working session to finalize PRD-adjacent details and BPIA edits
* Aim to move BPIA toward board review once committee consensus is reached

Meeting adjourned at **01:01:07**.
