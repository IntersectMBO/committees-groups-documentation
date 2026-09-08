# Meeting Minutes June 3, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | No         | Chair           | Y                 | October 2026 |
| TBC                | No         | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | No         | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Christian Taylor   | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Mike Hornan



Recording: [Technical Steering Committee - 2026/06/03 - Recording](https://drive.google.com/file/d/1L7piNvvc0WyaDcUwNsIJySMuLr3_FZvL/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/06/03 - Transcript](https://docs.google.com/document/d/1CgacVuwGdOVE7Vgs3VuvssxKPdzUV3eF3PRXAm86xhU/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/06/03 - Chat Transcript](https://drive.google.com/file/d/1qkq4CO-KyBoH8GD5HyMUf_kKBi3dH-Ik/view?usp=drive_link)

## Intros

Ryan 'Cerkoryn' Wiley: TSC Voting Member, Cybersecurity Engineer\
Tex: OS Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison

## Agenda 3rd June 2026

* Actions from the last meeting
* Hard Fork Status
* committeeMinSize
* Post-Quantum Crypto
* Upcoming Chair Elections
* Committee Member Dismissal & Replacement Policy
* Define a checklist for Leios confidence?
* AOB

## Decisions/Actions

**Decisions**

* **CC Minimum Size Endorsement:** Approved the technical validation of the CC minimum size reduction metadata, confirming it complies with the 90-day disclosure rule.
* **Voting Procedure:** Decided to transition the formal confirmation vote for the CC minimum size document to a structured, 24-hour verification poll inside the private TSC Slack channel.
* **Mainnet Fork Rescheduling:** Agreed to push the tentative Mainnet governance action submission "Go" decision back to June 15th to accommodate the Pre-Prod boundary delay.

**Actions**

* **Christian:** Retrieve the public quantum readiness presentation link from Hart and share it with the committee.
* **Alexander:** Follow up with Griffin regarding the placement and timeline of the user feedback/dispute button on the Proposal Examiner interface.
* **Terence:** Set up the formal 24-hour verification poll for the CC minimum size metadata document inside the private TSC members-only channel.
* **Bosko:** Track the upcoming Hard Fork Working Group data points to ensure the Ogmios/Kupo structural dependencies are monitored for upstream merging within the next 3 months.
* **Neil:** Draft an agenda framework outlining the committee's specific system integrity concerns regarding Leios to prepare for a deep-dive session.
* **All Members:** Submit any remaining leadership candidacy applications before the June 8th cutoff and prepare for an internal, unrecorded "in-camera" Leios readiness session on June 10th.
* **Bosko:** Set up the poll in the TSC members only channel on committee policies acceptance based on Neil and Alonzo expressing strong dissatisfaction with the newly formalized annual election and committee dismissal policies introduced by the Governance Working Group.

<br>

| Topic                      | Discussion                                                                                                                                                                              | Notes                                                                                                            |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Meeting Leadership         | Kevin was absent due to a concurrent session in an adjacent room. Neil volunteered to take over as temporary chair once the agenda was agreed upon.                                     | Bosko continued his structural role to facilitate the agenda.                                                    |
| Action Items Review        | Christian confirmed he is sourcing the post-quantum readiness slide deck from Hart. Hart's availability for a separate side-recording is limited due to the upcoming Ethcon conference. | Christian will be absent next week for Ethereum/Filecoin conferences.                                            |
| Griffin Proposal Examiner  | Alexander met with partner company Griffin to deliver the TSC's guidance framework for DReps. The logic is being integrated into their automated Proposal Examiner tool.                | The tool analyzes on-chain constitutionality, rationale, and metadata integrity.                                 |
| Tooling & Appeal Concerns  | Neil and Alonzo emphasized the importance of a clear user feedback/appeal mechanism for disgruntled proposers if the AI misinterprets a proposal.                                       | Alexander noted that the tool is a source of opinion, not a replacement for human judgment.                      |
| Hard Fork Voting Failure   | Bosko and Mike detailed why the Pre-Prod hard fork failed to execute at the last epoch boundary. The SPO voting stake fell just short (under 51%) due to real-time supply shifts.       | Auto-abstain rules and a last-minute 25M ADA delegation shift altered the expected majority.                     |
| Hard Fork Resubmission     | The original governance action remains live and active for the next epoch boundary. Current tracking tools estimate safe voting headroom at around 55%.                                 | Hard fork submission and enactment schedules have been shifted out globally as a result.                         |
| Ogmios & Koopo Forks       | Alonzo inquired about the status of the Ogmios and Kupo software forks. Terence confirmed the fixes are currently running successfully on the Intersect-cloned repositories.            | These fixes must eventually be merged back into the original codebases during the voting period.                 |
| CC Minimum Size            | The committee conducted a real-time review of the metadata documentation proposing a reduction in Constitutional Committee (CC) size from 7 to 5.                                       | The proposal satisfies the necessary 90-day security parameter guardrail since its initial Nov 2025 publication. |
| TSC Chair Elections        | Applications for the TSC Chair and Vice Chair roles remain open in the Intersect Members Area interface until the cutoff date of Monday, June 8th.                                      | Christian has officially applied for the Vice Chair role; Kevin indicated a willingness to continue as Chair.    |
| Governance Policies        | Neil and Alonzo expressed strong dissatisfaction with the newly formalized annual election and committee dismissal policies introduced by the Governance Working Group.                 | Neil characterized the centralized enforcement of these rules as an outreach against self-governing committees.  |
| Leios Competence Checklist | Terence introduced a request from Kevin regarding whether the TSC should define a definitive technical competence readiness checklist for the upcoming Leios protocol changes.          | The TSC holds structural oversight for approving the parameter frameworks used by the Parameters Committee.      |

<br>
