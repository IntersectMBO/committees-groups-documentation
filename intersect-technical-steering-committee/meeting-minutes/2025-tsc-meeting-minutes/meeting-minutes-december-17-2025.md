# Meeting Minutes December 17, 2025

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Empty Seat        | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Benjamin Hart
* James Meidinger
* Ryan Williams

**Youtube recording:** [https://youtu.be/-cDw\_cgPwIQ](https://youtu.be/-cDw_cgPwIQ)

**Recording:** [Technical Steering Committee - 2025/12/17 - Recording](https://drive.google.com/file/d/133t_q55tQSdiBhQZAH2dHk5tER4-HNPn/view)

**Transcript:** [Technical Steering Committee - 2025/12/17 - Transcript](https://docs.google.com/document/d/1OrsszQSrakWZdEzPcigr5E3g6tcv9xhwSCU2KBV8j3M/edit?tab=t.0#heading=h.epb983napx8r)

**Chat Transcript:** [Technical Steering Committee - 2025/12/17 - Chat Transcript](https://drive.google.com/file/d/19z3JMf8zZxE8qOT-Jzg0Gzzxvg-diMwm/view)

## Intros

Bosko: Senior Project Manager, Intersect Staff, TSC Secretary\
Duncan: TBD\
Alex: TBD\
Kevin:  Kevin Hammond, TSC chair, Founder at Ensurable Systems\
Leo: Developer@KeyPackt/AnetaV2/GenWealth single pool SPO, CEO LnLlabs, TSC member\
Neil: TSC, Network Params, PNSol Ltd\
Nicolas: Nicolas Biri, TSC voting member, Director of Software Architecture, IOG\
Ryan: Ryan Wiley, TSC voting member, Cybersecurity Penetration Tester.\
Sebastian: Sebastian Nagel, TSC voting member, Technical Architect, nCoding, IOE\
Tex: Terence 'Tex' McCutcheon - Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Liaison&#x20;

## Agenda 12.17.25

* Actions from the last meeting - Bosko
* Response on Nested Transactions - Bosko - [https://committees.docs.intersectmbo.org/intersect-technical-steering-committee/reviews/tsc-review-on-nested-transactions-inquiry](https://committees.docs.intersectmbo.org/intersect-technical-steering-committee/reviews/tsc-review-on-nested-transactions-inquiry)&#x20;
* Chain Incident Partition Working Group Update - Ryan/Neil/Kevin
  * Report expected by year end
* Hard Fork Working Group Update - Leandros/Sebastian/Kevin
  * Proposed name: van Rossem after Max van Rossem - we are asked to confirm this
* Ideal Number of CC members - Alex
* Timing of Governance Actions - Alex
* TSC operational budget  - Kevin
  * Increased Intersect focus on technical coordination in 2026
* 2030 Vision - Kevin
  * Vision is here: [https://product.cardano.intersectmbo.org/vision/](https://product.cardano.intersectmbo.org/vision/)&#x20;
* Vice-Chair - Bosko
* AOB

## Decisions/Actions

Decisions

* Hard Fork Naming: The committee officially voted (7 Yes, 1 Abstain) to name the Protocol Version 11 hard fork van Rossem after Max van Rossem.
* KPI Review Strategy: It was decided to pause the review of the 2030 Vision KPIs and instead hold a dedicated joint session with the Product Committee.
* Chain Partition Report: The technical view of the incident was finalized, confirming that the ledger remains consistent despite the orphan blocks.
* Governance Communication: The committee decided to use its social media presence to inform the community about technical logic hazards (e.g., voting thresholds and treasury withdrawal timing).

Actions

* Kevin: Draft an outline for the 2026 TSC Operational Budget and share it with the group by the end of the week.
* Alexander: Write a short blog post or X (Twitter) thread explaining the mathematical impact of increasing the Constitution Committee size to eight members.
* Bosko: Send a formal invitation to the Product Committee to attend the TSC meeting on January 7th, 2026.
* Ryan (Williams), Kevin Hammond & Ryan (Cerkoryn): Finalize the Chain Partition Incident Report for community distribution before the holiday break.
* TSC Members: Review the Product Committee’s 2030 Vision document, specifically the strategy and KPI sections, in preparation for the January meeting.
* TSC Members: Consider and submit nominations for the Vice Chair position.

<br>

| Topic                            | Discussion                                                                                                                                                                         | Notes                                                                                                            |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum                 | Kevin opened the final meeting of 2025. Attendance was noted, including late arrivals from Nicolas and Sebastian.                                                                  | Quorum was confirmed for voting later in the meeting.                                                            |
| Action Items Review              | Bosko reviewed status: hard fork tracking repo updated, TSC response on nested transactions sent, and 2026 roadmap PR provided.                                                    | Actions from previous sessions were largely completed or in progress.                                            |
| Chain Partition Incident Report  | Ryan (Cerkoryn) and Ryan (Williams) discussed the draft report regarding the recent chain fork. Analysis showed two contiguous orphan blocks prior to the incident.                | No "nasties" found; ledger remains consistent. Final report targeted for end-of-year community release.          |
| Transaction Analysis             | Kevin clarified that \~500 transactions appeared only on the non-preferred chain, with \~29 from the "bad block" not resubmitted.                                                  | Corrected data will be included in the technical report to provide a clear timeline.                             |
| Hard Fork Working Group (HFWG)   | Discussion on earmarking scope for the "Dickra" era. Proposal for a four-step process involving CIPs, shortlists, and DRep voting.                                                 | Future hard forks aim to be more open to community-driven contributions.                                         |
| Hard Fork Naming Vote            | The committee voted on naming the Protocol Version 11 hard fork after Max van Rossum, a prominent Cardano ambassador who recently passed.                                          | Motion Passed: 7 "Yes", 1 "Abstain". Max’s family expressed gratitude for the tribute.                           |
| TSC Operational Budget 2026      | Kevin and Bosko discussed the need for a dedicated TSC budget for technical coordination, incident management, and rewarding volunteer experts.                                    | Kevin to draft a small budget proposal for 2026 by the end of the week.                                          |
| Constitution Committee (CC) Size | Alexander raised concerns about increasing CC members to eight. Due to 2/3 rounding, 6/8 is harder to achieve than 5/7, potentially slowing ratification.                          | Alexander to write a short educational post/thread for the TSC X (Twitter) account.                              |
| Governance Timing Risks          | Alexander noted a potential clash between electing a new CC member and a treasury withdrawal action; late ratification could cause the withdrawal to be dropped.                   | Observed as a "logic hazard" in the current governance system; community should be informed of sequencing risks. |
| Parameter Update Sequencing      | Ryan (Cerkoryn) highlighted dependencies for upcoming 2026 updates (CC size, Plutus limits, and cost models).                                                                      | Successful updates require hashes of preceding proposals; tracking is required to avoid DRep confusion.          |
| 2030 Vision & KPIs               | The Product Committee submitted a vision document with KPIs for adoption, reliability, and revenue. Neil and Duncan critiqued the current "reliability" metrics as poorly defined. | TSC will invite the Product Committee to the first meeting of 2026 (Jan 7th) for a deep dive.                    |
| Vice Chair Vacancy               | Kevin called for nominations for the TSC Vice Chair position. Sebastian declined; no other members have stepped forward yet.                                                       | Members encouraged to consider the role; election policy from Intersect is being finalized.                      |
| Meeting Close                    | Kevin thanked the group for their hard work throughout the year.                                                                                                                   | Meeting adjourned with holiday wishes.                                                                           |
