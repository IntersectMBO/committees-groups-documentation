# Meeting Minutes July 29, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | No         | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | No         | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ken-Erik Ølmheim
* Geoff Watson
* Jack Briggs
* Musa Ridwan Itopa
* Simo Simovic



Recording: [Technical Steering Committee - 2026/07/29 - Recording](https://drive.google.com/file/d/1NH8afZFFP_OhIOPPA8HhRhcxzWp_Vytl/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/07/29 - Transcript](https://docs.google.com/document/d/1K64gaj1-xtfIm_u4cROsPrBaAJysrUDyQd-6poPDn44/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/07/29 - Chat Transcript](https://drive.google.com/file/d/1vbhX5PkwtbxNTG3vk5gpB23OLBlttaPE/view?usp=drive_link)

## Intros

**Ryan (Cerkoryn):** Ryan Wiley, TSC Member, Cybersecurity Professional, Incentives Researcher\
**Kevin Hammond:** Kevin Hammond, TSC Chair. CEO of Ensurable Systems\
**Neil Davies:** Neil Davies, TSC, Param Cmmte, PNSol

## Agenda 29th July 2026

* Actions from the Previous Meeting
* Linear Leios: Scope, Questions, Hard Fork Timing
* Technical Steering Committee Budget Action
* minPoolCost Reduction/Plutus mem limits increase
* Post Quantum Cryptography
* Ryan Williams is Leaving Intersect
* AOB

## Decisions/Actions

**Decisions**

* **Budget Currency Conversion:** Convert $52,000 USD worth of ADA at current market rates to secure fixed funding for Travel/Events and Technical Reports.
* **Work Package Denominations:**
  * Denominated in USD: Travel/Events, Technical Reports.
  * Denominated in ADA: CIP Editors, Proposal Reviewers, Parameter Committee, and Hard Fork Working Group support.
* **Scope Inclusions:** Agreed to include CIP-23 (Part 1) and CIP-50 in the Dijkstra era scope.
* **Decoupling Peras:** Approved including Peras code in the mainnet December hard fork build but delaying its network activation until 2027.
* **Meeting Agenda:** Deferred remaining minor agenda items to the next weekly meeting to allow full focus on the Leios rollout discussion.

**Actions**

* **Bosko / Christian:** Draft a 1-page formal budget document outlining the approved USD/ADA currency allocations for async committee vote and sign-off.
* **Kevin:** Add Christian to the Discord channel and organize a meeting with Robert, Ryan, and CIP editors to establish payment preferences and procedures.
* **Geoff:** Share the detailed IOG Leios project plan dashboard link and low-level details with the TSC.
* **Geoff:** Provide a finalized spreadsheet by the end of the week listing all in-scope features/CIPs for the Dijkstra era.
* **Geoff & IOG Team:** Maintain a living Q\&A response document with the TSC to address technical maturity, risk mitigation, and simulator validation concerns.
* **Kevin, Geoff, & Product Committee:** Hold an alignment meeting with the Product Committee to merge divergent roadmaps into a single source of truth.
* **Christian:** Take over chairing and organizing the TSC meetings for the next two weeks during Kevin’s absence.

| Topic                                              | Discussion                                                                                                       | Notes                                                                                                                                              |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| BLS Keys & Linear Leios Fallbacks                  | Discussion on using BLS keys as a fallback option and concerns about relying on fallbacks as a primary strategy. | Ryan noted it was discussed as a fallback. Neil cautioned against planning on fallbacks as primary paths.                                          |
| High CPU Usage Investigation                       | Update on high CPU usage reports from SPO channels on 1rom.                                                      | Bosko reported passing details to node engineering. No CPU issues were observed on the past boundary; investigation remains open.                  |
| CIP-50 Implementation                              | Status update on the implementation of CIP-50 (rewards calculation, governance, guardrails, and tests).          | Ryan confirmed Jared finished the implementation. Alexey reviewed the code favorably, and it is ready to merge.                                    |
| TSC Budget Approval & Enactment                    | Confirmation that the TSC budget proposal passed and funds have arrived in the target address.                   | Kevin, Bosko, and Matt met to discuss procedures; Jack confirmed Intersect main proposal funds are stabilized into stables.                        |
| ADA Volatility & Risk Mitigation Strategy          | Handling budget value drop due to ADA price decline (from $0.24 to \~$0.16).                                     | Neil suggested converting 1/3 to stables; Jack and Text supported denominating variable community initiatives in ADA and fixed expenses in USD.    |
| Budget Work Package Denomination                   | Deciding which TSC budget items to fix in USD versus keeping in ADA.                                             | Agreed to denominate Travel/Events and Technical Reports in USD ($52,000 total). CIP Editors, Reviews, and Committees remain in ADA.               |
| CIP Editor Funding Procedures                      | Establishing outreach and payout mechanisms for CIP editors.                                                     | Kevin will set up a meeting with Robert, Ryan, Christian, and CIP editors to align on payout preferences and operational procedures.               |
| Leios Rollout Proposal Overview                    | Presentation by Geoff on IOG's Leios delivery and project plan for 2026.                                         | Geoff presented high, medium, and low confidence plans targeting a December 2026 hard fork for Leios in the Dijkstra era.                          |
| Leios Phase Separation & Peras Decoupling          | Decoupling Peras implementation from the initial Leios hard fork.                                                | Peras (handled by Modus) code will be included in the December hard fork, but activation will occur later in 2027 for safety.                      |
| CIPs Included in Dijkstra Era                      | Clarifying scope and CIP inclusions for the upcoming Dijkstra era release.                                       | Confirmed inclusion of CIP-23 (Part 1) and CIP-50 alongside Leios in the Dijkstra era scope.                                                       |
| Hard Fork Timeline Realism & Historical Comparison | Evaluating the feasibility of a December 2026 hard fork against historical data.                                 | Kevin and Neil presented van Rossem data (took 156 days from code readiness) arguing the schedule is overly compressed for exchanges/SPOs.         |
| Definition of Hard Fork Candidate                  | Establishing criteria for when a build is officially ready for community rollout tracking.                       | Candidate must be fully integrated, feature-complete (all parameters included), performance-tested, and without major blocking bugs.               |
| IOG Delivery Milestones & Benchmarking             | Current IOG target dates for Leios candidate delivery and test generation.                                       | Geoff target dates: Production-grade Leios candidate by Aug 31; Node integration by Sept 30. Marcin confirmed traffic generator is already active. |
| SPO Hardware & Incentive Considerations            | Resource impact of Leios on Stake Pool Operators (SPOs) and hardware requirements.                               | Leios demands higher CPU, SSD, and bandwidth specs. Geoff noted IOG is exploring an SPO incentive plan to cover initial setup costs.               |
| Product Committee Plan Alignment                   | Resolving discrepancies between IOG’s proposed schedule and the Product Committee’s proposal.                    | Kevin noted three hard forks in a year is excessive; IOG and Product Committee need to align on a single, unified roadmap.                         |
