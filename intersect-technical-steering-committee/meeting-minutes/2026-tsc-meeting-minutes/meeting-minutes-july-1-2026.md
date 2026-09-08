# Meeting Minutes July 1, 2026

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

* Mike Hornan

\
Recording: [Technical Steering Committee - 2026/07/01 - Recording.mp4](https://drive.google.com/file/d/14GhkA9pwFT6WOVpErVrygmeewLIycAb6/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/07/01- Transcript](https://docs.google.com/document/d/1L8ka9bVRCp8yljsrErSCIP4F5J1LdqBcS98xlzMd9ck/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/07/01 - Chat Transcript](https://docs.google.com/document/d/1HiQlNwnZXay-WQLelmCSqd6vhFceT6Kq2UlVORElZYw/edit?usp=drive_link)

## Intros

**Terence McCutcheon:** Terence 'Tex' McCutcheon - Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Member Advocate

**Neil Davies:** Neil Davies - TSC member, PNSol

**leandros bsp:** Leandros Holleman, CTO@Genwealth, Maintainer@keypacts, Voting member@TSC

**Kevin Hammond:** Kevin Hammond, Ensurable Systems, TSC Chair

**Ryan (Cerkoryn):** Ryan Wiley, Cybersecurity Professional, Incentives Researcher, TSC Voting Member

**Christian Taylor:** Christian Taylor, TSC Vice Chair, Filecoin Foundation, Andamio, Charli3, Kai Systems (Aquana), Open Source Cowboy

**Udai Solanki:** Udai Solanki, member TSC, AIQUANT Technologies

## Agenda 1st July 2026

* Actions from the last meeting
* SecondFi Status Update
* van Rossem Hard Fork Status
* Dijkstra Hard Fork Planning
* Parameter Committee
* Budget Status
* Intersect Repository Maturity
* Technical Gating Requirements for Linear Leios
* Testnet Purposes
* Intersect: Planning and Reporting
* AOB

## Decisions/Actions

**Decisions**

* **Hard Fork Ratification Endorsement:** Voted unanimously to formally record the TSC's official endorsement and technical approval of the live mainnet hard fork governance action.
* **Dijkstra Timeline Safeguards:** Confirmed a mandatory structural policy enforcing a minimum 6-month timeline for non-emergency hard forks to allow thorough testnet benchmarking.
* **Parameter Process Enforcement:** Directed the SIP editor group to reject parameter-only SIP alterations, pointing community authors instead to the standard Parameter Change Proposal (PCP) pipeline.
* **Communication Interface Points:** Established that all formal, technical communications between the vendor's engineers and the TSC will flow explicitly through the Secretary, Chair, or Vice Chair.

**Actions**

* **Christian:** Finalize the post-quantum cryptography comparative analysis document across competing chains by next week.
* **Ryan & Neil:** Synchronize and present the finalized K=1000 pro/con evaluation framework to the Parameter Committee tomorrow.
* **Kevin & Christian:** Finalize scheduling for the upcoming technical TSC budget breakdown broadcast on Cardano Over Coffee next week.
* **Kevin:** Collaborate with the Civics Committee to draft and release focused communications regarding the CC minimum size reduction ahead of its July 8th expiration.
* **Bosko:** Invite Ryan Williams to the next weekly session to present the Testnet Purpose and Upgrade Policy documentation firsthand.
* **Terence:** Distribute the official YouTube broadcast and Intersect Connect portal links to all TSC members ahead of tomorrow's virtual hub community presentation.<br>

| Topic                            | Discussion                                                                                                                                                               | Notes                                                                                                            |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum                 | Kevin officially opened the session. A headcount confirmed that eight voting TSC members were present, satisfying the committee's strict structural quorum.              | Bosko handled the agenda documentation.                                                                          |
| Action Items Review              | The committee reviewed pending items. Christian noted his comparative study on post-quantum readiness across alternative chains is currently in progress.                | Christian will lock in a recurring weekly sync with Kevin next week.                                             |
| Hard Fork Status Update          | Ryan reported that all ratification metrics have been met. Ecosystem exchange liquidity crossed the required 80% threshold, leading to a successful vote.                | Out of 17 participants in the working group, a clear majority voted to proceed.                                  |
| Mainnet Ratification Support     | Live governance metrics show DRep support at 5%, SPO support at 36%, and Constitutional Committee (CC) support at 1 out of 5 members.                                    | The auto-abstain mechanism for SPOs does not apply to hard forks; active votes are mandatory.                    |
| Ecosystem Explorer Discrepancies | The committee observed conflicting support data across public explorers. Cardano Scan tracks historical days differently than AdaStat, which shows SPO support at 39.9%. | The Hard Fork Working Group is actively auditing a definitive source of truth.                                   |
| Dystra Hard Fork Planning        | Kevin proposed launching joint planning with the Product Committee for the next major protocol upgrade (Dystra / protocol version 12) via a public but focused forum.    | The timeline is estimated to be at least 6 months due to required constitutional and guardrail updates.          |
| Parameter Committee & K Change   | Alexander previewed the agenda for tomorrow's Parameter Committee. The group will continue building out the pros/cons documentation regarding the K=1000 expansion.      | Ryan and Neil are shaping a balanced questionnaire to accurately gauge ecosystem sentiment.                      |
| On-Chain Parameter Processes     | Alexander noted an influx of direct community requests regarding mining UTXO alterations and transaction fees.                                                           | The committee emphasized that all adjustments must follow the formal PCP forum process.                          |
| CC Minimum Size Threshold        | The live governance action to reduce the CC minimum size from 7 to 5 expires on July 8, 2026. It has achieved 43.6% support but faces a high 75% hurdle.                 | Large DRep groups (such as Emurgo/Yoroi) have yet to vote. AdaStat is displaying an incorrect 67% support level. |
| TSC Budget Promotion             | The TSC on-chain budget proposal expires July 23, 2026, and currently sits at roughly 11% support.                                                                       | Promotion will target undecided DReps via custom X Spaces and a dedicated Cardano Over Coffee session.           |
| Daedalus Private Budget Action   | The Daedalus team bypassed the Intersect pipeline to submit a private on-chain budget proposal.                                                                          | Neil and Kevin expressed support, noting that a community-backed node wallet adds crucial security options.      |
| 2027 Budget Front-Running Risks  | Alonzo and Neil raised concerns that the current 18-month Interim Constitution (NCL) process is being circumvented by teams going straight to the treasury.              | Neil noted that DReps must remain disciplined and vote "No" on unvetted, front-running proposals.                |
| Repository Maturity Scanner      | Christian demonstrated an AI-native repository health tool utilizing CHAOSS community best practices to scan codebases for maturity, security, and health.               | The tool will be evaluated for potential integration into upcoming TSC open-source initiatives.                  |
| Linear Leios Gating & Audit      | Kevin confirmed that Neil's Leios Mind Map was officially delivered to the vendor's engineering team. Neil stressed the need for a formal, written audit trail response. | Marcin reassured the committee that IOG technical teams are treating the document seriously.                     |
