# Meeting Minutes June 10, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| TBC                | No         | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | No         | Member/Seat     | Y                 | April 2028   |
| Christian Taylor   | No         | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* None



Recording: [Technical Steering Committee - 2026/06/10 - Recording](https://drive.google.com/file/d/1lFVm_sofJRNaPIM1f3JrgYwSi5BQhixm/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/06/10 - Transcript](https://docs.google.com/document/d/1dUrYFKxIDKcru8kekO6MStO4uGrATKYXqfM7QkBq_hc/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/06/10 - Chat Transcript](https://drive.google.com/file/d/1Ck5LRzALVgbiv9woz3lEa8Vs5gGy6lg5/view?usp=drive_link)

## Agenda 10th June 2026

* Actions from the last meeting
* Hard Fork Status
* Parameter Committee
* Budget Process
* Technical Gating Requirements for Linear Leios
* Testnet Purposes
* Post-Quantum Crypto
* Report from the Node Diversity workshop Porto
* Chair Elections
* Intersect: Focus, Planning and Reporting
* AOB

## Decisions/Actions

**Decisions**

* **Hard Fork Metadata Alignment:** Approved the technical contents of the Mainnet hard fork metadata, subject to an final verification check with the IOG developers regarding completed security evaluations.
* **TSC Inclusion in Go-Decision:** Agreed that the entire TSC body must be formally invited to participate in the critical June 15th Mainnet "Go/No-Go" submission meeting.
* **In-Camera Session Transition:** Voted to transition out of the open public broadcast into a closed, in-camera session to analyze technical risks on Leios without public presence.

**Actions**

* **Bosko:** Raise the slowness of the Intersect Members Area login credential system with the respective Intersect team to resolve onboarding friction.
* **Kevin:** Coordinate with the Hard Fork Working Group tomorrow to double-check the accuracy of the security verification text in the metadata.
* **Bosko:** Ensure all TSC members are added to the official calendar invitation for the Monday Mainnet Go-Decision meeting.
* **Ryan:** Represent the TSC's position at tomorrow's Parameter Committee meeting and report back on the $K=1000$ networking and peer list debate.
* **Kevin:** Conduct targeted async outreach to undecided DReps to secure further voting support for the TSC and Intersect budget proposals before the June 12th deadline.
* **Neil:** Postpone the formal vote on producing the Leios technical requirements document until the conclusion of the private in-camera session.
* **Bosko:** Set up the poll in the TSC members only channel on committee policies acceptance based on Neil and Alonzo expressing strong dissatisfaction with the newly formalized annual election and committee dismissal policies introduced by the Governance Working Group.
* **Christian:** Retrieve the public quantum readiness presentation link from Hart and share it with the committee.
* **Alexander:** Follow up with Griffin regarding the placement and timeline of the user feedback/dispute button on the Proposal Examiner interface.

| Topic                        | Discussion                                                                                                                                                                      | Notes                                                                                                   |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Meeting Leadership & Quorum  | Kevin chaired the first part of the meeting. The committee confirmed it reached a voting quorum, allowing any official structural decisions to proceed.                         | Bosko joined a few minutes late. Christian was absent.                                                  |
| Chair Election Procedures    | Neil and Kevin criticized the Intersect Members Area leadership election bureaucracy. Only two people applied for two open posts, yet a full centralized vote is required.      | Voting for the open leadership positions closes on June 12, 2026.                                       |
| Action Items Review          | The committee reviewed outstanding items. Christian is still tracking the public slide deck from Hart. Alexander was absent, delaying the Griffin follow-up.                    | Neil successfully finalized and shared the system integrity framework on Leios.                         |
| Pre-Prod Hard Fork Enactment | Bosko reported that the Pre-Prod protocol version 11 hard fork successfully enacted late last night at midnight UTC.                                                            | This marks a critical technical milestone for testing the upgrade.                                      |
| Mainnet Metadata Review      | The committee reviewed the upcoming Mainnet hard fork metadata. Kevin noted it is almost identical to Pre-Prod but links to the companion Plutus cost model governance action.  | A final review is scheduled with the developer team tomorrow to avoid misleading text.                  |
| Guardrail Assurances         | Bosko noted that community members requested a formal TSC position confirming that the underlying guardrail scripts are completely unchanged for this hard fork.                | Kevin confirmed no guardrail changes are being introduced in this upgrade cycle.                        |
| Mainnet Go-Decision Timeline | The collective "Go/No-Go" decision to submit the Mainnet hard fork initiation governance action is scheduled for Monday, June 15, 2026.                                         | The timeline gives DApps only 3 to 4 working days to test changes on Pre-Prod.                          |
| Ogmios & Kupo Maintenance    | Bosko provided an update on Ogmios/Koopo tooling. A dual path forward exists; changes are currently running on an Intersect fork, with an upstream merge expected in late June. | The upstream merge will occur after the Mainnet governance action is live.                              |
| SPO Node 11 Adoption         | PoolTool shows Mainnet block production from upgraded SPO nodes is at 76–77%, while Cexplorer calculates a trailing-day average of 84%.                                         | The hard fork requires a minimum threshold of 85% SPO readiness to safely execute.                      |
| Hard Fork Risk Assessment    | Neil highlighted that the testing window on Pre-Prod is exceptionally short. He advocated accepting the risk but preserving the right to pull the plug if flaws emerge.         | A governance action can be paused or aborted via the Constitutional Committee within its 35-day window. |
| Parameter Committee Updates  | Kevin reviewed live actions. The Plutus parameter update has 54% voting support with 3 weeks left. The CC size reduction action is at 19% and expires July 8th.                 | The Parameter Committee's main focus tomorrow is debating an increase to K=1000.                        |
| TSC Budget Voting Status     | The TSC budget proposal on Ekklesia is gaining momentum, rising from 65.5% to 67.9% support following a major "Yes" vote.                                                       | Major DRep abstentions are helping the margin, but direct outreach is still required.                   |
