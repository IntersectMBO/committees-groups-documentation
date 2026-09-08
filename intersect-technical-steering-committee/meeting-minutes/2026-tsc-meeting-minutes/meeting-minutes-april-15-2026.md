# Meeting Minutes April 15, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | No         | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | No         | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Markus Gufler
* Vinay Devabhakthuni
* Christian Taylor



Recording: [Technical Steering Committee - 2026/04/15 15:58 CEST - Recording](https://drive.google.com/file/d/12JVZuaNh313vX8unjL8JipP6qierNjO9/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/04/15 15:58 CEST - Transcript](https://docs.google.com/document/d/1XQ0sAWguj5CuYIbCJOq0oGga51x-E1YtP64nXQN4hEk/edit?usp=drive_link)

Chat Transcript: Not available at the moment due to Google technical issue

## Agenda 15th April 2026

* Actions from the last meeting
* Intersect Elections
* TSC Budget Proposal
* van Rossem Hard Fork
* 2030 KPI Review
* Dijkstra Hard Fork Scope
* Parameter Committee Update
* AOB

## Decisions/Actions

**Decisions**

* **Meeting Schedule:** Provisionally agreed to join the Linear Leios monthly meeting in two weeks and cancel that week's TSC meeting to avoid overlap.
* **Budget Finalization:** The TSC proposal is considered done; Kevin will finalize it assuming no further verbal objections are raised.
* **Dijkstra Polling:** Agreed to promote a broad "maximalist" list of CIPs for community prioritization before narrowing scope based on implementation feasibility.

**Actions**

* **Kevin:** Finalize and submit the 2026 TSC budget proposal.
* **Neil:** Create an outline for a "Professional Technical Review" process to ensure higher due diligence standards for Intersect projects.
* **Bosko:** Execute the plan to make specific Discord channels read-only for the public to improve technical communication.
* **Ryan:** Coordinate with Ryan Williams to finalize the "maximal list" of forkable CIPs for the Dijkstra survey.
* **Kevin:** Raise the guardrail script testing requirement (for the new Plutus cost model) with Mike Hornan on Preview.
* **All Members:** Review the parameter committee documents on K=1000 and minPoolCost=75 via the links shared in chat.

| Topic                    | Discussion                                                                                                                                                   | Notes                                                                                                     |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum         | Kevin opened the meeting, confirming six voting members present. The committee is quorate.                                                                   | <p><br></p>                                                                                               |
| Committee Elections      | There are 5 open TSC positions with 4 applicants so far. Applications close tomorrow (April 16). Voting begins next Monday.                                  | Kevin encouraged members to reach out to qualified technical candidates.                                  |
| TSC Budget Proposal      | The budget was trimmed to four work packages, totaling \~$400,000. It includes support for the Security Council and 10 technical workshops (mostly virtual). | The proposal is being merged into Intersect’s omnibus budget ($7M–$10M).                                  |
| Technical Review Rates   | Kevin increased the proposed community technical review rate from $150 to $250 per proposal to better reflect the effort required.                           | Neil noted that professional due diligence for multi-million dollar projects is a non-trivial task.       |
| 2030 Vision KPIs         | Leandros and Kevin met with the Product Committee. They are near finalization on metrics for protocol revenue, TVL, and chain quality.                       | A session with the Product Committee is scheduled immediately after this call to finalize the list.       |
| Chain Quality Metric     | Discussion on measuring chain density during "Genesis windows" vs "per-epoch" to better identify risks from long-range attacks.                              | <p><br></p>                                                                                               |
| Van Rossom Hard Fork     | Node v10.7.0 was released but discovered to have serious performance issues (50% CPU increase) and a rare consensus bug.                                     | A new version, 10.7.1, is required to fix these issues before Mainnet readiness.                          |
| Node v11 / Integration   | Integration with DREPs is already underway against v10.7.0. The official hard fork node will likely be v11 (derived from v10.7.2).                           | Current "cautiously pessimistic" forecast for enactment is late June/early July.                          |
| Plutus Cost Model Risk   | Neil warned that increasing primitive costs could cause existing DApp scripts to fail if they don't have sufficient fee headroom.                            | Kevin will test the guardrail script on Preview once the new cost model is enacted to ensure no lockouts. |
| Dijkstra (Next HF) Scope | Ryan shared a draft for an on-chain survey (CIP-179) to prioritize which SIPs to include in the Dijkstra era.                                                | Leios, nested transactions, and incentive changes are high-priority candidates.                           |
| CIP Triage Process       | The committee debated how to narrow a "wish list" into a "short list." Sebastian noted that implementation "champions" are required for any CIP to progress. | <p><br></p>                                                                                               |
| Incentives Ballot        | An incentives-specific ballot is launching in the next two weeks, potentially overlapping with the Dextra survey.                                            | Frames will be used to clarify: one ballot for "support" and the other for "prioritization."              |
| Net Change Limit (NCL)   | Ryan discussed the technical challenge of the ledger tracking a rolling window of 73 epochs (\~1 year) of revenue/withdrawals.                               | The committee leaned toward ledger-level enforcement at enactment rather than at submission.              |
| Parameter Committee      | Alexander is soliciting expert feedback on increasing K to 1000 and reducing the minPoolCost to 75 ADA.                                                      | The CC minimum size reduction is ready but waiting for the Plutus cost model update to clear.             |
| Discord Openness         | Bosko is pushing to make technical Discord channels (e.g., Hard Fork Working Group) read-only for non-Intersect members.                                     | This aims to improve transparency without requiring a membership "gate."                                  |
