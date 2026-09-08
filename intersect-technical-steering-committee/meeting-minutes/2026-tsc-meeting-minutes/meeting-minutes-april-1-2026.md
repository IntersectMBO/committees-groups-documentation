# Meeting Minutes April 1, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | No         | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | No         | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | No         | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Adam Rusch
* Ian Hartwell
* Ryan Williams
* Thomas Lindseth



Recording: [Technical Steering Committee - 2026/04/01 - Recording](https://drive.google.com/file/d/1PMUaviVAY8B1W9AzZsN7N6IZ_W9Pbx7U/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/04/01 - Transcript](https://docs.google.com/document/d/1b7ylI3WyJQDBAe2shL5L2EeS8d_KAs00pFHAgdH-Gm4/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/04/01 - Chat Transcript](https://drive.google.com/file/d/1boub-3GkJ2aNaVUkqICYmQPE2nn0J9n7/view?usp=drive_link)

## Agenda 1st April 2026

* Actions from the last meeting
* ccMinSize
* Timing - is there a sensible gap now
* TSC Budget Proposal
* Updated to new template
* van Rossem Hard Fork
* Node 10.7.0 performance issue
* 10.7.1 expected in 1-2 weeks
* Risk Register
* Plutus Cost Model
* Possible Preview Submission this week
* Any further communication needed?
* From CIP Farm to Hard Fork
* CIP-179
* Net Change Limit Governance Actions
* CIP-173
* X Spaces/Town Halls
* Intersect Steering Committee Quarterly Review
* Committee Elections
* AOB

## Decisions/Actions

**Decisions**

* **Governance Ordering:** Provisional agreement to prioritize the Plutus cost model upgrade ahead of the Constitutional Committee (CC) minimum size reduction.
* **KPI Measurement:** Adopted the recommendation to measure chain quality over a rolling Genesis window for improved long-range security.
* **Budget Ratification:** The committee approved the revised 4-work-package budget structure for submission to the Intersect Board.

**Actions**

* **Kevin:** Sync up with Udai to clarify the final division of the security budget between the TSC and OSC.
* **Kevin & Bosko:** Coordinate a Doodle poll to schedule the private technical deep-dive on Linear Leios risk management with Sebastian.
* **Ryan:** Prepare a maximal list of "forkable" CIPs in coordination with Ryan Williams for the upcoming community poll.
* **Leandros:** Update the 2030 KPI document with the "Genesis range window" implementation details and share it in Slack.
* **TSC Account:** Promote the April election applications via X (Twitter), specifically targeting prospective technical candidates.
* **Neil:** Finalize the "Professional Technical Review" proposal draft to address the $150/review rate concerns before the budget is final.
* **Bosko:** Investigate the feasibility of an RSS feed for technical parameter updates to improve developer communication.

| Topic                      | Discussion                                                                                                                                          | Notes                                                                                                                        |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum           | Kevin opened the meeting, noting that only four voting members were present. All decisions made require ratification outside the meeting.           | Guest attendees included Thomas and Adam.                                                                                    |
| Security Budget Alignment  | Discussion on items related to the Security Council and budget overlaps between the TSC, OSC, and Intersect central funds.                          | Alignment reached: OSC will not request bug bounty or incident officer funds as they are in the Intersect proposal.          |
| Bug Bounty Oversight       | TSC and OSC members will jointly oversee the disbursement of the bug bounty program, despite Intersect being the budget holder.                     | <p><br></p>                                                                                                                  |
| 2030 KPIs: Chain Quality   | Leandros met with IOG researchers to refine "Chain Quality." The recommendation is to use a "Genesis range window" rather than per-epoch.           | This provides a better indicator of security against long-range attacks.                                                     |
| Technical Communication    | Bosko is investigating the feasibility of an RSS feed for TSC updates to improve accessibility for the technical community.                         | The request for a dedicated TSC communications officer was lifted to the Intersect level.                                    |
| CC Minimum Size            | Thomas reported that the Civics Committee voted to support a governance action to reduce the committee minimum size from 7 to 5.                    | Submission is targeted for the current epoch if it does not conflict with the Plutus cost model update.                      |
| Plutus Cost Model Risks    | Neil expressed concern that the upcoming cost increases for pre-existing primitives might cause "lazy" transactions to fail at the epoch boundary.  | <p><br></p>                                                                                                                  |
| Governance Sequence        | The committee debated the order of parameter changes. Adam suggested the Plutus cost model is less controversial than the CC size change.           | Final decision: Plutus cost model first, followed by CC minimum size two epochs later.                                       |
| TSC Budget Proposal        | Kevin presented the revised budget of \~$400,000, reduced to four work packages. $20,000 was added for security council member support.             | Work packages cover community coordination, security, protocol governance, and technical review.                             |
| Workshop Strategy          | The budget includes 10 technical workshops. Based on feedback, the majority will be virtual, with four face-to-face events collocated with summits. | Topics include Layer 2, node performance, and post-quantum cryptographic resilience.                                         |
| Technical Review Pilot     | A pilot "Independent Technical Review Program" is planned for 2026 to build a pool of experts for the 2027 budget cycle.                            | The proposed rate is $150 per review, which Neil argued is too low for high-stakes delivery projects.                        |
| Hard Fork Risk: Node v10.7 | Node v10.7.0 was found to have serious performance issues and rare consensus failure conditions. It is not Mainnet ready.                           | Focus has shifted to Node v10.7.1; the tentative hard fork forecast is now June 2026.                                        |
| SIP-179: Surveys & Polls   | Thomas and Ryan demonstrated a tool for on-chain surveys via metadata. This will be used to shortlist SIPs for the Dextra hard fork.                | The tool is integrated with CGov and allow DReps to vote on specific hard fork content.                                      |
| Net Change Limit (SIP)     | Ryan discussed the technical feasibility of an on-ledger Net Change Limit (NCL). It requires the ledger to track revenue history for 73 epochs.     | Consensus is shifting toward ledger-level enactment at the point of withdrawal rather than a guardrail script at submission. |
