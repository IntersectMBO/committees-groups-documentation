# Meeting Minutes August 19, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* James Meidinger
* Michiel Bellen
* Seun Gbiri

Recording: [Technical Steering Committee - 2026/08/19 - Recording - Part 1](https://drive.google.com/file/d/1savzo-_uD3y95WJMS-DUsEkyEauRtkrx/view?usp=drive_link) [Technical Steering Committee - 2026/08/19 - Recording - Part 2](https://drive.google.com/file/d/1-XnoLPFOL8VTWiT-FHEB82l9fm7Bnqib/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/08/19 - Transcript - Part 1](https://docs.google.com/document/d/1PEnhRur-Eg7P_gxbZ0Ej9kVjwtafFNLzm5Rayifl_ZY/edit?usp=drive_link) [Technical Steering Committee - 2026/08/19 - Transcript - Part 2](https://docs.google.com/document/d/1zVGuLUB8OI0BvfrojK4fKCmE4WVvHO2m2dFcU4_HJi0/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/08/19 - Chat Transcript - Part 1](https://drive.google.com/file/d/1ZfgyN6R1QAoPq-Yo7fX0mNHp2aSb_fcm/view?usp=drive_link) [Technical Steering Committee - 2026/08/19 - Chat Transcript - Part 2](https://drive.google.com/file/d/1b_J4qnHNXSvuuDOs_fzFxTAsvz95EXUi/view?usp=drive_link)

## Agenda 19th August 2026

* Actions from the last meeting
* Dijkstra era hard fork
* Technical Steering Committee Budget
* Linear Leios
* minPoolCost Reduction/Plutus mem limits increase
* Post Quantum Cryptography
* Committee Member Experience and Performance Review Survey
* AOB

## Decisions/Actions

**Decisions**

* Bug bounty submissions will continue to be accepted, but classified strictly as "advisory only" pending future funding allocations.
* Main agenda items regarding the detailed TSC budget allocation are postponed to an out-of-band discussion and next week’s meeting.
* The Parameter Committee will request concrete parameter details by the end of next week to maintain a manageable analysis schedule.

**Actions**

* **Alex:** Follow up with exchanges and SPO channels to encourage active voting/abstaining on governance actions, and check protocol rules regarding action expirations concurrent with CC updates.
* **Neil:** Locate and comment on the PR proposing larger linear layer transactions to raise awareness of MEV and DoS security risks.
* **Kevin:** Clarify with node teams whether node 11.2 or 11.3 introduces the new block structure and confirm the network protocol rollout timeline.
* **Bosko, Terence, & Christian:** Prepare CIP editor and travel request templates based on existing OSC structures.
* **James:** Coordinate with Intersect legal and admin teams to finalize the USDM terms of service addendum by Friday.

<br>

| Topic                                     | Discussion                                                                                                                                                          | Notes                                                                                                                      |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Meeting Formalities & Agenda              | Kevin opened the TSC meeting (19th August 2026). Attendance was checked (8 members present, Alex absent initially), and the agenda was confirmed without additions. | Kevin welcomed members back after his absence and thanked Christian for covering.                                          |
| Action Items & Security Council Budget    | Bosko reviewed prior meeting actions. Kevin noted that the Security Council exhausted its budget for the bug bounty program.                                        | Terence confirmed reports are now "advisory only" until formal ownership transfer and reporting are closed out by the OSC. |
| DIjkstra Hard Fork Timelines & Parameters | Ryan, Neil, and Kevin evaluated the hard fork readiness and timeline. Neil expressed concerns over overly optimistic schedules and compressed timeframes.           | Parameter Committee needs concrete details by the end of next week. Critical path relies heavily on node version 11.3.     |
| Node Versions & Network Upgrades          | Discussion focused on node releases (11.2, 11.3, 11.4) and when new block structures/syntactic elements would be tested on the network.                             | Kevin to clarify the exact release schedule and network-level protocol upgrade plan for the new block format.              |
| Hard Fork Delivery Plans & Confidence     | Bosko highlighted the IOG plan options (Moderate vs. High Confidence). Neil pointed out a 2-month feature completeness gap between the two plans.                   | High-confidence plan targets submission in February and enactment in March; moderate targets December enactment.           |
| Dijkstra Hard Fork Scope                  | Scope definition was discussed; Amaru team considers scope frozen for mainnet readiness, with Jeff confirming P0/P1 fixes as sole exceptions.                       | Scope is documented across the Hard Fork Delivery Plan and Cardano Upgrade pages.                                          |
| Transaction Size Proposal Risk            | Proposal to allow larger transactions within linear Leios was debated. Alex, Neil, and Kevin noted severe security and MEV front-running risks.                     | Neil to comment on the PR to flag MEV/DoS attack vectors regarding non-EB block transactions.                              |
| TSC Budget & USDM Conversion              | Bosko and James provided an update on Intersect treasury funds and conversion into USDM.                                                                            | Legal terms of service (ToS) addendum between Intersect and USDM is nearing final approval (expected Friday).              |
| Governance Actions & Parameter Changes    | Alex provided updates on the Min Pool Cost parameter change (5% dRep participation) and CC Update action (3% participation).                                        | Alex to verify edge-case rules regarding expiring actions if the CC Update action passes concurrently on September 1st.    |
| SPO Engagement Strategies                 | The steering committee observed SPOs withholding votes over preferences for min margin rather than min pool cost.                                                   | CF to engage exchanges/SPOs to encourage explicit voting or setting pool addresses to auto-abstain.                        |
| CIP Editors & Travel Approvals            | Bosko, Terence, and Christian discussed template preparation for CIP editors and travel requests.                                                                   | TSC will use modified OSC templates for travel approval workflows once budget allocations settle.                          |
| Committee Member Survey & Workshops       | Bosko shared the Intersect committee survey and floated an idea regarding potential technical workshops in Singapore.                                               | Members to discuss budget usage and potential workshop hosting asynchronously on Slack and in next week's meeting.         |
