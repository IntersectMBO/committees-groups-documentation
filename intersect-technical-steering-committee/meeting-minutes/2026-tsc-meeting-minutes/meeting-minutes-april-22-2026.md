# Meeting Minutes April 22, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | No         | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* None



Recording: [Technical Steering Committee - 2026/04/22 - Recording](https://drive.google.com/file/d/1jTGPhfaZU7hiiJtGEE3kGL4RX-qtQq4Y/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/04/15 - Transcript](https://docs.google.com/document/d/1XQ0sAWguj5CuYIbCJOq0oGga51x-E1YtP64nXQN4hEk/edit?usp=drive_link)

## Agenda 22nd April 2026

* Actions from the last meeting
* Update on committee election process
* TSC Budget Proposal
* van Rossem Hard Fork
* Parameter Committee Update
* Dijkstra Hard Fork Scope
* Leios Risks
* AOB

## Decisions/Actions

Decisions

* **Budget Strategy:** Agreed to wait for the final Intersect main proposal before submitting the revised (reduced) TSC budget to ensure no items fall through the gaps.
* **Leios Discussion:** Moved to conduct a "paper-based" technical exchange between Neil and the Leios team before reserving meeting time for a verbal deep-dive.

Actions

* **Bosko:** Coordinate with Terence to ensure the "updates" Discord channel is opened for public viewing alongside the HFWG channel.
* **Kevin:** Re-confirm the guardrail script testing requirement on Preview with Mike Hornan once the new cost model is enacted.
* **Kevin:** Coordinate with Leonard Hagerty to elevate communication with DApp developers regarding the Plutus cost model risks.
* **Neil:** Create a written summary of specific performance concerns to be sent to the Leios team; Sebastian/Team to respond in writing 48 hours before the May 6th session.
* **Kevin & Alex:** Monitor the Constitutional Committee (CC) member status to determine if the "chained" parameter update (Cost Model -> CC Min Size) needs to be re-ordered.

| Topic                   | Discussion                                                                                                                                                | Notes                                                                                                               |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum        | Kevin opened the meeting, confirming seven voting members present (Quorate). Discussions began regarding Daylight Savings shifts and local system issues. | European daylight savings started earlier than other regions, causing minor calendar confusion.                     |
| Discord Openness        | Terence and Bosko discussed making technical Discord channels (e.g., Hard Fork Working Group) read-only for the public.                                   | Current blockers involve organizational server rules. Updates will be made as organization changes process.         |
| TSC Elections           | Bosko reported 10 candidates for 5 open positions. Applications close tomorrow; voting begins next Monday.                                                | Neil and Alex are seeking re-election; Sebastian and Duncan have not reapplied.                                     |
| Election Events         | Terence shared links for upcoming events: Virtual Hub (April 23 & 30) and an X Space (April 28).                                                          | Candidates are encouraged to attend to meet voters.                                                                 |
| TSC Budget Alignment    | Kevin reported on a meeting with Intersect (Jack). Three items originally in the TSC budget were moved to the Intersect main budget.                      | The moved items are: Technical workshops, part-time meeting organizer, and Security Council member support.         |
| TSC Budget Total        | Moving these items reduces the TSC-specific budget request by approximately $150k–$200k.                                                                  | The revised TSC budget now focuses on two to three core items. Finalization is pending the Intersect main proposal. |
| Intersect Budget Model  | Intersect is reducing its central budget (\~$6–7M) by adding a surcharge to individual community proposals to cover administrative costs.                 | This is intended to create a more sustainable long-term financial model.                                            |
| Van Rossom Hard Fork    | Node 10.7.1 (Mainnet release) is out. Node v11 is expected early next week for testnet forking.                                                           | Performance issues found in 10.7.0 (50% CPU spike) have been largely resolved.                                      |
| Hard Fork Timeline      | Mainnet hard fork action submission is currently targeted for May 28, 2026, assuming sufficient stakeholder adoption.                                     | Technical risks are largely burning down; focus is shifting to social readiness and DApp testing.                   |
| Plutus Cost Model Risks | Discussion on the risk of locking out guardrail scripts or DApps due to cost model changes.                                                               | Leonard is coordinating with the top 10–20 DApp developers to ensure no breaking impacts.                           |
| Dextra Scoping          | Ryan presented a "maximalist" list of SIPs for the Dextra era. Many SIPs are already covered in other budget work packages.                               | The committee discussed how to prioritize without creating redundancy.                                              |
| Leios Performance       | Neil raised serious concerns about Leios performance feasibility based on an AI-assisted analysis of current throughput constraints.                      | Sebastian noted that the analysis may have missed recent documentation/claims from the Leios repository.            |
| 2030 Vision KPIs        | Leandros and Kevin are meeting with the Product Committee immediately after this call to finalize the baseline metrics.                                   | Discussion continues on whether to use Genesis range windows vs. per-epoch for security measurements.               |
