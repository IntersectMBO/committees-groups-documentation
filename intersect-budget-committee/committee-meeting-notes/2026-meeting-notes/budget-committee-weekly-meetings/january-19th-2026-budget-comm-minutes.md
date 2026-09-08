# January 19th, 2026 Budget Comm Minutes

## **Budget Committee Weekly Meeting — January 19th, 2026**

**Date:** January 19, 2026\
**Time:** 07:58 EST

**Attendees:** Christina Gianelloni, Colleen O’Beirne, Dimitri (Dynamic Strategies), Eric Helms (SCATDAO), Georgia Hutton (Delivery Assurance), Kriss Baird, Kristijan (Chris) Kowalsky, Lloyd Duhon, Megan Hess (Chair), Nicolas Cerny, Rita Mistry, Shunsuke Murasaki, Simo Simovic (+ “Simo Simovic’s Presentation”)

**Quorum:** Confirmed at start of meeting.

***

### **1. Opening and Key Priorities**

Lloyd opened the meeting, welcomed members and guests, and confirmed quorum.

#### **Primary priorities discussed**

1. **Finalize the PRD / technical specification** for the proposal submission + feedback loop tooling (time-sensitive).
2. Continue refining the **Budget Process Info Action (BPIA)** (including adding rationale to each phase/step).
3. Continue progress on the **budget template** workstream (Rita + Nico draft underway).
4. Track and respond to **NCL on-chain voting status** and “no” vote rationales.

***

### **2. Net Change Limit Voting Status**

Lloyd reviewed current NCL progress:

* **\~40.38% approval** (reported during meeting)
* **\~2.29B ADA voting “yes”**
* Several “no” votes were present; Lloyd has been requesting **rationales** from “no” voters and noted most “no” votes now include rationale.

**Next step:** Lloyd will pull rationale comments into a short report for Wednesday so the committee can assess whether any misconceptions or messaging issues need to be addressed.

***

### **3. Budget Process Info Action (BPIA) — Rationale-by-Step Work**

Simo provided a working session recap and task coordination:

* Rationale additions were assigned by step during the Wednesday working session.
* Progress noted:
  * Simo completed **Step 1** rationale.
  * Eric contributed on **Step 4** and **Step 3** (per Simo’s comments).
  * Lloyd is assigned to complete additional rationale work during the week (Simo stated Lloyd is “Step 3,” and asked Lloyd to complete it this week).

Simo emphasized the need to also **define dates and timeline** associated with publishing the BPIA.

***

### **4. Tooling Decision Context: PRDMS vs Ecclesia (Funding and Risk Mitigation)**

#### **4.1 Where tooling stands (Lloyd)**

* Lloyd described an internal dev effort (funded personally as a “gift” effort) that progressed significantly but stalled due to lack of continued funding.
* The **Open Source Committee** expressed interest and has funding via the **Paid Open Source model**, but:
  * Funding release and contracting have been delayed.
  * Participation/burnout challenges have slowed execution.
* Lloyd’s dev estimate: \~90% of PRD requirements are already covered by prior work; remaining \~10% could be completed and tested in time for March **if funded**.

#### **4.2 Parallel mitigation plan (Simo)**

Simo outlined a contingency plan so the process is not blocked:

* Proceed with PRD finalization this week.
* Work with **Ecclesia (Adam)** to build the needed submission + feedback loop functionality within **\~5 weeks**, enabling:
  * Late Feb completion
  * Early March testing
  * Readiness for a **March proposal window** (target dates referenced: testing/approval by \~March 18; readiness by \~March 23).
* Simo is awaiting Ecclesia’s formal estimate (“their ask”) and timing confirmation.

#### **4.3 Committee clarity request (Nico)**

Nico requested clarity on which tool is being used, noting that process discussion is unproductive without tooling clarity.

**Outcome:** Committee acknowledged both tracks remain possible, but agreed the immediate priority is **finalizing the PRD**, so either development path has a stable specification.

***

### **5. PRD / Technical Specification Review**

Simo shared the technical specification and requested committee review and (ideally) approval.

#### **5.1 Key clarifications and edits requested**

* **Deposits vs Treasury fee:**
  * Lloyd instructed to remove any “deposit lock-up” requirement and instead use:
    * A **field for tracking treasury fee / donation transaction hash**, and
    * A validation step to ensure the hash is present/valid before publication.
* **Ranking support:**
  * Dimitri asked about ranking (highest-to-lowest).
  * Lloyd clarified ranking is part of the **voting phase** (Ecclesia capability), while PRD focus is the **submission + feedback loop**.

#### **5.2 Dynamic template fields and comparability (Rita + Nico)**

Rita described the evolving template approach:

* Users select a **Focus Area** which automatically populates:
  * Pillar description
  * Thematic area
  * Enhancement description\
    (reduces proposer workload, prevents inconsistent framing)
* Add **KPIs and 2030 targets** as dynamic elements:
  * Align proposals to the 2030 strategy
  * Support comparability across proposals
* Multi-year vs annual logic:
  * If proposer enters 12 months → annual plan fields
  * If multi-year → require year-by-year plans and budget breakdowns

Nico presented how template is grounded in the Cardano 2030 strategy:

* Five pillars, multiple focus areas (stated as \~33)
* Nine KPIs (with three “core” KPIs noted)
* Proposers must map proposals to relevant KPIs and targets.

#### **5.3 Implementation approach and scope control (Chris Baird)**

Chris Baird cautioned against scope creep:

* Dynamic behavior implies JSON-driven configuration or template variants.
* Admin consoles are costly; JSON configuration is feasible for a 5-week build.
* Maintain focus on “what can be done in five weeks.”

#### **5.4 Feedback loop privacy and communications (Eric)**

Eric requested support for private communications:

* Public comments are valuable, but some topics require private follow-up.

Consensus direction:

* Ensure **proposer contact info** is available to DReps (and/or via authenticated DRep view), enabling off-platform follow-up through preferred channels.
* DMs may be optional; at minimum, provide contact channels and structured visibility controls.

#### **5.5 “Stretch goals” structure**

Lloyd proposed including “stretch goals” so the PRD:

* Captures a credible MVP for five weeks,
* While signaling longer-term enhancements (e.g., vetted subject matter expert accounts, committee-badged feedback).

Nico supported the stretch goals concept and emphasized:

* Dev teams should explicitly state what is feasible within five weeks.
* The committee should identify “must-haves” vs “nice-to-haves.”

Rita suggested the committee internally prioritize with a must/should/could framework to reduce delivery risk.

***

### **6. Budget Template Progress**

* Lloyd acknowledged strong progress by **Rita + Nico** on the budget template draft.
* Several members were tagged to begin commenting asynchronously.
* Plan to revisit later in the call if time allowed; primary focus remained PRD completion and BPIA progress.

***

### **7. Decision Checkpoint**

A formal approval vote on the PRD did **not** occur in this session.

* Chris Baird stated for the record that he would vote **“no” today** because edits were still being made live.
* The committee agreed to aim for a **vote during Wednesday working session**, provided quorum.

***

### **8. Action Items**

| Action                                                                                 | Owner                        | Notes                                                       |
| -------------------------------------------------------------------------------------- | ---------------------------- | ----------------------------------------------------------- |
| Compile “no” vote rationales on NCL and summarize for committee                        | Lloyd                        | Review for messaging gaps and outreach targets              |
| Complete assigned BPIA rationale section(s)                                            | Lloyd (and assigned members) | Add rationale per step for clarity and institutional memory |
| Finalize PRD text edits: remove deposit lock-up; use treasury fee tx hash + validation | Simo + Lloyd                 | Ensure PRD matches process (fee-to-treasury model)          |
| Add “validation checks” section above “stretch goals”                                  | Lloyd                        | Keep stretch goals last; clarify MVP vs future enhancements |
| Define must-have vs nice-to-have priorities (MoSCoW) for PRD                           | Committee                    | Reduce scope creep; enable 5-week delivery                  |
| Provide Ecclesia team updated template details and PRD after edits                     | Simo                         | Pending estimate/ask from Ecclesia                          |
| Confirm Open Source Committee funding timeline (paid open source)                      | Lloyd + OSC liaisons         | Parallel option; not assumed                                |
| Prepare for PRD vote on Wednesday                                                      | All voting members           | Target approval so dev work can start immediately           |

***

### **9. Adjournment**

Lloyd closed by emphasizing urgency:

* Finalize the PRD by Wednesday if possible,
* Approve and hand to whichever development path is funded so delivery can begin immediately.

Meeting ended after **01:13:06**.
