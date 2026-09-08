# Meeting Minutes April 8, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | No         | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Abid
* Ken-Erik Ølmheim



Recording: [Technical Steering Committee - 2026/04/08 - Recording](https://drive.google.com/file/d/1BJdgFswu8sPqqO8q33Dc5Wzit4ykW_Ts/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/04/08 - Transcript](https://docs.google.com/document/d/1tLsd2_Kdv2ttbD_zGdYSWCS4K6G-fKHqxAN0EC5udfc/edit?tab=t.0)

Chat Transcript: [Technical Steering Committee - 2026/04/08 - Chat Transcript](https://drive.google.com/file/d/1TvMgf1KEZYs0Zp_G3Q2ImXxSkaSL6_a4/view?usp=sharing)

## Agenda 8th April 2026

* Actions from the last meeting
* TSC Budget Proposal
  * Working to a deadline of April 13th
* van Rossem Hard Fork
  * Node 10.7.0
    * performance issue may have been identified
  * 10.7.1 in preparation
    * will include fixes
  * Overall timeline remains unchanged
* 2030 KPI Document
* Dijkstra Hard Fork Scope
* Leios Update
* Layer 2 Working Group
* Parameter Committee Update
  * Plutus Cost Model Metadata for Preview
* Intersect Elections
  * 5 Open TSC Positions
* AOB

## Decisions/Actions

**Decisions**

* **Committee Elections Neutrality**: The TSC will not "ping" or solicit individual candidates from the official account to maintain neutrality.
* **Budget Ratification:** The increase of the proposal review rate to $250 to better reflect the effort required for due diligence.
* **Governance Sequencing:** Confirmed that the Plutus cost model upgrade will proceed as the primary governance action, with the CC size reduction following in a subsequent epoch.

**Actions**

* **Kevin & Neil:** Finalize the "Professional Technical Review" outline and process document within the next week.
* **Bosko:** Launch a Doodle poll to schedule the private deep-dive session on Linear Leios risk management.
* **Ryan:** Sync with Ryan Williams (CIP Editor) to finalize a maximal list of "forkable" SIPs for the community survey.
* **Leandros:** Deliver the finalized 2030 KPI document to the Product Committee following today's follow-up call.
* **Kevin:** Finalize and submit the 2026 TSC budget proposal by Monday, April 13th.
* **Bosko:** Investigate technical requirements for an RSS feed to automate the communication of technical parameter changes.

| Topic                    | Discussion                                                                                                                                                         | Notes                                                                                                               |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum         | Kevin opened the meeting, confirming six voting members present, establishing a quorum. Issues with calendar link synchronization were noted.                      | Guests Thomas (Intersect) and Adam (IO) were welcomed.                                                              |
| Security Budget          | Discussion on the division of security funds between the Security Council, OSC, and TSC. OSC will not request bug bounty funds as Intersect is the central holder. | TSC/OSC will still oversee the review and program changes for the bug bounty.                                       |
| 2030 KPIs: Chain Quality | Leandros consulted IOG researchers to refine "Chain Quality." The recommendation is to use a "Genesis range window" rather than per-epoch.                         | This implementation improves monitoring of long-range security against potential attacks.                           |
| Election Outreach        | Discussion on a post to promote April election applications. Nicolas emphasized neutrality: the TSC account should promote the process, not specific individuals.  | <p><br></p>                                                                                                         |
| TSC Budget Update        | Kevin presented the final proposal with a revised review rate of $250 per proposal. Total requested budget is \~$400,000 for 2026.                                 | Deadline for final comments is Monday, April 13th.                                                                  |
| In-Person vs. Virtual    | The budget includes funding for 10 workshops. The plan was adjusted to prioritize virtual sessions with fewer in-person events to save costs.                      | Proposed topics include node performance, post-quantum crypto, and P2P topology.                                    |
| CC Minimum Size          | Kevin and Alex met with the Civics Committee. They agreed to move forward with reducing the CC minimum size from 7 to 5.                                           | This action is sequenced to follow the Plutus cost model update to prevent governance lockout.                      |
| Plutus Cost Model Risk   | Neil highlighted a risk: for the first time, some primitive costs are increasing. Transactions constructed with old pricing data may fail.                         | A one-month communication "blitz" is planned to warn DApp developers of the changes.                                |
| Node v10.7.1 Status      | AWS instances used for benchmarking fell over during evaluation, causing a delay in final performance data for the v10.7.0 fix.                                    | Node v10.7.1 is required to address a 6GB space leak and performance issues found in v10.7.0.                       |
| Linear Leios Prototype   | Sebastian shared progress on the Leios prototype, including a new transaction generating tool and early Grafana instrumentation.                                   | Endorsement Block (EB) diffusion is being modeled using Delta-Q to support the security argument.                   |
| Leios "Storm" Threats    | Discussion on "storms"—unfortunate timings of VRF elections that could spike network load to 625 MB in the worst case.                                             | <p><br></p>                                                                                                         |
| Economic Feasibility     | Neil raised concerns that high data exchange requirements for Leios might price out small stake pool operators.                                                    | The protocol is designed to be optimistic; failure to certify in "storms" is acceptable if the system remains safe. |
