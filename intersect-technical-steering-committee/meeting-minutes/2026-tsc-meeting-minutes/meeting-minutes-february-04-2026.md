# Meeting Minutes February 04, 2026

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
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Christian Taylor
* Mike Hornan
* Robert Hever
* Vinay Devabhakthuni
* Vinit Inamke<br>

Recording: [Technical Steering Committee - 2026/02/04 - Recording](https://drive.google.com/file/d/1kEG-rcN3Ozqi2q_Ds8Jek3lqLfNQxCY2/view?usp=sharing)

Transcript: [Technical Steering Committee - 2026/02/04 - Transcript](https://docs.google.com/document/d/1W_10sbeixee9NbQ1jti3MDs7z7gk6bvqthiJJXpvaoM/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/02/04 - Chat Transcript](https://drive.google.com/file/d/1Me_24eXJCYGfMrYSHuJaXyPDV2zABBI4/view?usp=sharing)

## Intros

Christian: Christian taylor, anything Open source, intersect\
Nicolas: Nicolas Biri, TSC voting member, IOG\
Ryan (Cerkoryn): Ryan Wiley, TSC voting member, Cybersecurity professional\
Kevin: Kevin Hammond, TSC Chair, Ensurable Systems

## Agenda 02.04.26

* Actions from the last meeting
* Charli3 Incubation - Robert
* Plutus mem limits parameter update
* TSC Operational Budget '26
* Review - Cardano Constitution v2.4
* Chain Incident Report Publication
* Draft Fire Drill Report #2
* Cardano Node Update
  * 10.5 Status
  * 10.6 Status
  * 10.7 Status
  * HF: Feature work continues
* 2030 Vision KPI's
* TSC Objectives 2026
* IOR Annual Report Review
* AOB
  * Intersect Committee Term Extension to 2 years
  * Upcoming Committee Elections Prep

## Actions from the last meeting

* Ryan: Write a paragraph summarizing the “Stake Pool Math” (including pool counts and redistribution figures) for the minutes.

Math for how many pools could be affected by changing stakePoolTargetNum from 500 to 1000.  This is OFC modeling as if no new pools would be created, but AFAIK there is no way whatsoever to estimate that.

| Scenario                    | Pools | Oversat ADA | Share/Pool | Crossed 3M |
| --------------------------- | ----- | ----------- | ---------- | ---------- |
| All recipients              | 2945  | 5.45B       | 1.85M      | 201        |
| <3M recipients              | 2229  | 5.45B       | 2.44M      | 345        |
| Active only, all recipients | 1366  | 5.45B       | 3.99M      | 653        |
| Active only, <3M recipients | 653   | 5.45B       | 8.34M      | 653        |

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

## Decisions/Actions

**Decisions**

* Charlie 3 Incubation: The TSC formally moved to proceed with the incubation of Charlie 3 under Intersect, pending review of supplemental materials.
* Budget Draft: The TSC agreed to remove "Town Halls" from the funding request and proceed with socialization of the draft (minus milestone rate disputes).
* Communication: Agreed to utilize the TSC Twitter account to promote the SPO round table recording and the Plutus memory limit vote.

**Actions**

* Alexander: Follow up with Miquel (Exchange integrations) to encourage exchange pools to vote on governance actions.
* Kevin: Discuss the Plutus memory limit vote with Emurgo and promote it during the monthly SPO call.
* Bosko: Schedule a meeting with the Intersect delivery team (Matt) to discuss budget overheads and milestone review rates.
* Leandros: Create a draft of realistic KPI targets (conservative/optimistic/stretch) for 2026–2030.
* Kevin & Neil: Complete a detailed technical audit of Constitution v2.4, specifically regarding guardrail label uniqueness.
* Leandros & Bosko: Reach out to the Product Committee to advise that KPI technical reviews are underway and suggest pausing on-chain actions.

<br>

| Topic                          | Discussion                                                                                                                                              | Notes                                                                                                  |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Welcome & Quorum               | Kevin opened the meeting, confirming that 7 voting members were present, establishing a quorum.                                                         | Robert (Charlie 3) attended as a guest.                                                                |
| SPO Round Table Update         | Alexander reported on the SPO round table held recently. It featured views from DApp developers and infrastructure providers.                           | The recording is available; the TSC will promote it via Twitter.                                       |
| Staking Pool (K) Analysis      | Ryan presented simulations on changing the staking pool target (K) from 500 to 1,000.                                                                   | Results showed 653 non-viable active pools could become viable under various redistribution scenarios. |
| Incentive Simulation Timeline  | Nicolas chatted with Carlos; simulation results for incentive changes are expected by mid-March.                                                        | This timeline precedes the planned parameter change votes.                                             |
| Project Incubation: Charlie 3  | Robert proposed Charlie 3 (a decentralized Oracle network) for Intersect incubation. He aims to open-source core repos and shift to USDM for stability. | The TSC has no technical objections; the Open Source Committee will handle execution.                  |
| Plutus Memory Limits Campaign  | Alexander updated on the social media campaign to encourage voting on memory limit increases.                                                           | Voting expires Feb 13. Current support is \~31% for DREPs and \~20% for SPOs.                          |
| SPO Outreach                   | The committee discussed low SPO turnout for the current governance action.                                                                              | Alexander and Kevin will engage exchange pools and promote the vote at the monthly SPO call.           |
| TSC 2026 Operational Budget    | Kevin presented the draft budget, which currently exceeds 1M ADA. New guidelines require administrative costs and specific travel ROI.                  | A draft must be finalized by the end of February.                                                      |
| Travel & ROI                   | Terence clarified that travel funds aren't "slush funds" but must be tied to specific events like hackathons or summits.                                | Funding is prioritized for members without vendor backing.                                             |
| Milestone Technical Reviews    | Nicolas expressed strong concerns regarding the $200 rate for milestone reviews, arguing it is too low for professional-grade audits.                   | Kevin and Bosko will meet with the delivery team to discuss realistic rates and cohorts.               |
| Constitution v2.4 Review       | Kevin and Neil reviewed terminology changes. Concerns were raised about the removal of semantic bolding and the reuse of guardrail labels.              | There is a risk that label reuse could break tooling or cause internal inconsistencies.                |
| Budget Safeguards              | Kevin noted that "Info Actions" for budget proposals were removed in v2.4, potentially weakening treasury oversight.                                    | Kevin will verify if clauses requiring "Cardano-specific benefit" were also removed.                   |
| 2030 KPIs & Throughput         | Sebastian noted that the 3x throughput target may be insufficient to support the 27M monthly transaction adoption goal.                                 | Leandros will compile realistic conservative and stretch targets for the next meeting.                 |
| Product Committee Coordination | The committee discussed preventing premature "Info Actions" on-chain regarding KPIs before technical vetting is complete.                               | Leandros and Bosko will coordinate with the Product Committee to align on timing.                      |
