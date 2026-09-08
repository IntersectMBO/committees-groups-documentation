# Meeting Minutes March 04, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | No         | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Benjamin Hart
* Mark Bùi<br>

Recording: [Technical Steering Committee - 2026/03/04 - Recording](https://drive.google.com/file/d/1ns7ioQKCe5LZJ683AZl5hkN-RqgKsyAF/view?usp=sharing)

Transcript: [Technical Steering Committee - 2026/03/04 - Transcript](https://docs.google.com/document/d/1VDTDsTPDyXacThLkNbGqlYbi3zwXxToGRyY_KLLIgXU/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/03/04 - Chat Transcript](https://drive.google.com/file/d/1g0CB8x-xMRnvXcFimJVreWpu-ue2VkH2/view?usp=sharing)<br>

## Agenda 03.04.26

* Actions from the last meeting
* dRep compensation paper
* van Rossem Hard Fork Status
  * development status
  * Enhanced comms: X space Thursday at 1500 UTC
  * Monthly SPO call Thursday @ 1600 UTC
  * Future HF planning (CIPS for Djikstra etc)
  * Including Amaru and other nodes
* Parameter Update Status
  * Updated Plutus V1/V2/V3 cost models to be reviewed this week
  * Metadata to be prepared
* TSC Budget Update
  * Miro Board: [https://miro.com/app/board/uXjVIn9rXG8=/](https://miro.com/app/board/uXjVIn9rXG8=/)
  * Budgets will need consolidation
* Constitution v2.4 Review
  * Summary
  * Forward to Civics Committee to progress
* AOB

## Decisions/Actions

**Decisions**

* **DRep Deposit Research:** Agreed to pull historical benchmarking results (e.g., load tests with 10,000 DREPs) to determine the technical impact of lowering the deposit to 5 ADA.
* **KPI Integration:** Confirmed that feedback from the Product Committee regarding TVL definitions (including deposits/min-UTXO) will be incorporated into the KPI document.

**Actions**

* **Ryan:** Collect feedback on the DRep Compensation paper from the committee in the background for a more detailed discussion next week.
* **Kevin & Neil:** Sync up to finalize the formal technical concern statement for the Civics Committee regarding Constitution v2.4.
* **Bosko:** Update the Miro board for the TSC budget based on Kevin’s feedback on Slack and clarify the feedback loop with Intersect.
* **Kevin:** Ask Mike Hornan to attend the next Parameter Committee meeting to discuss the rationale for the 5 ADA DRep deposit proposal.
* **Sebastian:** Coordinate a Doodle poll to schedule a dedicated technical session for the TSC to dive deeper into Linear Leios risk management.<br>

| Topic                   | Discussion                                                                                                                                                 | Notes                                                                                                                  |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum        | Kevin opened the meeting, noting the group was not currently quorate (5 members present). Logistics regarding daylight savings transitions were discussed. | Europe transitions earlier than North America, causing a 2-3 week shift in meeting times.                              |
| DRep Compensation Paper | Ryan presented a proposal to optimize for decentralization and participation rather than binary "good/bad" voting outcomes.                                | Proposal involves an "Exclude K, Pay N" model (e.g., exclude top 10, pay next 100).                                    |
| Quality Control & AI    | Mark and Ryan debated quality control. Mark suggested delegators are the best market mechanism; Ryan noted AI summarized reviews are useful but risky.     | Kevin cautioned against AI bias in voting; humans should retain judgment.                                              |
| Trialing Compensation   | The committee discussed trialing the compensation scheme as a budget experiment via Intersect before formalizing it as a SIP.                              | Ryan noted that even 1 ADA per proposal could cover transaction fees and incentivize the "middle out" of DREPs.        |
| Hard Fork Status        | Node version 10.7.0 is in preparation. It will enable testing on Preview/Pre-prod but is not the final forking candidate.                                  | <p><br></p>                                                                                                            |
| SanchoNet Incident      | A misconfiguration in the Plutus cost model update on SanchoNet broke script execution; recovery efforts are ongoing.                                      | This incident highlights the need for rigorous testing before Protocol Version 11.                                     |
| Timeline Projections    | Bosko provided a forecast for a late May 2026 hard fork enactment, assuming a stable node is ready by mid-March.                                           | The timeline includes a 7-10 day buffer for regression and performance testing.                                        |
| Luma Hard Fork Calendar | Bosko shared a Luma calendar for all hard fork-related events, including working groups and X spaces.                                                      | An X space is scheduled for March 5 at 3 PM UTC.                                                                       |
| Future Scoping (Dextra) | Ryan (W) is developing a tool for on-chain surveys via metadata to allow the community to poll for SIP preferences for the next hard fork.                 | The tool supports multiple-choice, numerical, and custom field responses.                                              |
| Parameter Updates       | Alexander reported that the Parameter Committee is reviewing new Plutus cost models and corrected built-in values.                                         | A proposal could be enacted before the hard fork once recommendations are finalized.                                   |
| DRep Deposit Proposal   | Mike Hornan proposed reducing the DRep deposit from 500 ADA to 5 ADA to promote global inclusion and self-representation.                                  | Alexander questioned if technical spam protection (e.g., certificate size) was the original reason for the higher fee. |
| TSC Budget Miro Board   | Bosko has consolidated the TSC budget into work packages on a Miro board for Intersect review.                                                             | Items include core operations and support for the Security Council.                                                    |
| Linear Layers Risk      | Sebastian updated on the Linear Layers (Leios) prototype. Technical focus is on data storage duration and ledger benchmarking.                             | <p><br></p>                                                                                                            |
| Constitution Review     | The committee agreed to pass a formal technical concern statement regarding v2.4 to the Civics Committee.                                                  | Discussion emphasized identifying loopholes for future v2.5 or v3.0 iterations.                                        |
