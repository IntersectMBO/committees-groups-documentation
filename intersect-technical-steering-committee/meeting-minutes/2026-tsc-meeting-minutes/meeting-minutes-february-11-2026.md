# Meeting Minutes February 11, 2026

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
| Udai Solanki      | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ryan Williams



Recording: [Technical Steering Committee - 2026/02/11 - Recording](https://drive.google.com/file/d/1RloLc_6bDRHgaPTVPpcqJE-1B-Qy-RES/view?usp=sharing)

Transcript: [Technical Steering Committee - 2026/02/11 - Transcript](https://docs.google.com/document/d/1QonLeEUznCh14x32GQ5-QTcoPcaxaNeiBpKM42i1hzQ/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/02/11 - Chat Transcript](https://drive.google.com/file/d/17eA6W223woL_rgVzEU8FOocOYMkhknoD/view?usp=sharing)

## Intros

Kevin:  Kevin Hammond, TSC Chair, Ensurable Systems\
Bosko: Senior Project Manager, Intersect Staff, TSC Secretary\
Tex: Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Liaison

## Agenda 11.05.25

* Actions from the last meeting
* Update on Plutus Mem Unit Limits
* Update on TSC Operational Budget
* Review of Constitution v2.4
* Hard Fork WG
* NCL as a Governance Action
* 2030 Vision KPI's
* Committee Elections
* Charli3 Incubation
* TSC 2026 Objectives
* IOR Annual Report Review
* AOB

## Decisions/Actions

**Decisions**

* Budget Sharing: Unanimously agreed to share the TSC operational budget draft with the Intersect delivery team and Steering Committee for socialization.
* Governance Priority: Agreed that passing the current memory unit limit update is the immediate priority to preserve the technical timeline.

**Actions**

* Alexander & TSC X Account: Promote the "auto-abstain" mechanism for SPOs to reduce governance friction for non-participating pools.
* Leandros: Share the comprehensive KPI targets document and quarterly breakdown with the committee for async review.
* Neil: Perform a peer review of Kevin’s technical audit of Constitution v2.4 within the next 48 hours.
* Ryan (W): Refine the "CIP Short-listing" name and process to present as a standing function of the Hard Fork Working Group.
* Bosko: Finalize the three TSC-specific election questions on Slack to meet the upcoming Friday deadline.
* Kevin & Neil: Attend the Product Committee meeting next week to present technical concerns regarding proposed 2030 KPIs.

<br>

| Topic                        | Discussion                                                                                                                               | Notes                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Constitutional Blindsight    | Kevin and Neil discussed how the TSC and Civics Committee were "blindsided" by constitutional changes proposed on-chain in December.     | The Civics Committee was apparently unaware of these specific community-driven changes.                                      |
| Parameter Update Status      | Alexander updated the group on the Plutus memory unit limit vote. Support is currently near the threshold for DREPs and SPOs.            | The action expires on February 13th; several large pools (e.g., Figment, Nordic) have not yet voted.                         |
| SPO Governance Options       | Ryan (W) noted a poorly documented "auto-abstain" option for SPOs who do not wish to participate in active governance.                   | An action was created to better communicate this specific mechanism to the SPO community.                                    |
| KPI Draft Presentation       | Leandros presented initial KPI targets including protocol revenue (15% improvement target), Plutus script usage, chain density, and TVL. | The "stretch" target for TVL is $9 billion; the "conservative" target is $390 million.                                       |
| Competing Governance Actions | The committee discussed a proposal by Yuta to reduce the committee minimum size, which competes with the memory unit limit update.       | Only one of these mutually exclusive parameter changes can pass in the current governance cycle.                             |
| Operational Budget Update    | Kevin and Bosko met with the Intersect delivery team to discuss technical review rates and administrative support costs.                 | The group reached a unanimous decision to share the budget proposal with the Intersect Steering Committee.                   |
| Community Reward Logistics   | Discussion around rewarding community members (e.g., Hard Fork Working Group) for technical contributions.                               | Intersect noted potential KYC hurdles for individual payments; outsourcing this function is being considered.                |
| Constitution v2.4 Audit      | Kevin highlighted technical inconsistencies in v2.4, specifically the reuse of guardrail labels which breaks tool automation.            | Neil volunteered to double-check Kevin's technical review before it is shared with the Civics Committee.                     |
| Metadata Immutability        | Concern was raised over the new requirement for immutable metadata and how it treats mutable URLs used for evidence.                     | The "transitive closure" of immutability remains undefined and technically ambiguous.                                        |
| Hard Fork Readiness          | Ryan (C) reported that Node v10.7 is the hard fork candidate. Plutus cost models exist but are not yet finalized for Mainnet.            | Testing is currently being performed on the SanchoNet test environment.                                                      |
| CIP Short-listing Process    | Ryan (W) is developing a transparent process for ranking and scheduling CIPs for the upcoming Dextra hard fork.                          | This aims to move away from purely vendor-driven feature selection to a community-prioritized model.                         |
| Automated Net Change Limit   | Ryan (C) is rewriting the Net Change Limit CIP to move enforcement directly into the ledger as an adjustable parameter.                  | This automation would prevent treasury withdrawals that exceed a percentage of previous revenue without manual intervention. |
| April 2026 Elections         | Bosko confirmed that the TSC must finalize election questions and the number of open seats by next Friday.                               | The group estimates six seats will be open (five standard plus one currently empty seat).                                    |
