# Meeting Minutes July 22, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | No         | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | No         | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | No         | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ken-Erik Ølmheim

\
Recording: [Technical Steering Committee - 2026/07/22 - Recording](https://drive.google.com/file/d/1OGq9C3_t6dDhMi5kfVn54lDHemSFYKGt/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/07/22 - Transcript](https://docs.google.com/document/d/1E4PNHUs8YQmHy5yhTPJPaiCUhvEvtc1-jqq13ASkv6s/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/07/22 - Chat Transcript](https://drive.google.com/file/d/1ktYBLzSHWkONnElGpIKvdExiWWA1lQWS/view?usp=drive_link)

## Intros

**Neil Davies:** Neil Davies, PNSol, TSC member and parameter commitee meeting\
**Ryan (Cerkoryn):** Ryan Wiley, Cybersecurity Professional, TSC Member, Incentives Researcher

## Agenda 22nd July 2026

* Actions from the last meeting
* van Rossem Hard Fork
* TSC and Intersect budget proposals
* Dijkstra-era hard fork scoping
* Parameter Updates
* WanChain Attack
* Linear Leios
* Post Quantum Cryptography
* Voting on Intersect Bylaws
* Monthly ISC Meeting with the Board
* AOB

## Decisions/Actions

**Decisions**

* **TSC & Intersect Budget Support Strategy:** Agreed to send out a final thank-you and call-to-action message across public channels ahead of the July 23rd budget proposal voting deadline.
* **Parameter Action Execution:** Re-confirmed the decision to move forward with the minimum pool cost reduction (75) and Plutus memory limit updates across Preview, Pre-Prod, and Mainnet.
* **ISC Representation:** Appointed Christian to represent the TSC during the upcoming monthly Intersect Steering Committee (ISC) meeting.

**Actions**

* **Bosko:** Pass high CPU usage reports from SPO Telegram channels during the van Rossem hard fork to the node engineering teams for analysis.
* **Christian:** Represent the TSC and raise any relevant community/steering points at the upcoming monthly Intersect Steering Committee meeting.
* **Kevin:** Prepare the meeting agenda for next week to allocate 30 minutes for Jeff (IO) to cover Dijkstra scope and linear layoffs.
* **Kevin / Neil:** Review IO's technical response to the April linear leios questions to prepare feedback ahead of next week's session.
* **Neil / Ryan:** Continue drafting the visual dependency graph and timeline constraints for the Dijkstra hard fork.
* **Ryan:** Follow up with node release managers regarding the review and integration testing of the completed CIP-50 pull request.

<br>

| Topic                                     | Discussion                                                                                                                                                                                                                 | Notes                                                                                                                                                                                 |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Agenda Review & Attendance                | Kevin opened the meeting, noting that Christian could join for part of the session, Neil had a hard stop at 15:55 UTC, and Jeff from IO would attend the following week's meeting instead.                                 | Four voting members were present initially with 5th member joining later                                                                                                              |
| Review of Action Items                    | Bosko ran through the status of previous actions. Approved TSC budget messaging was published, and Kevin reached out to Jeff regarding linear leios and hard fork scoping.                                                 | Neil and Ryan noted that work on the visual dependency graph for hard fork planning is on their to-do lists.                                                                          |
| van Rossem Hard Fork Review               | Ryan reported that the van Rossem hard fork enacted successfully over the weekend                                                                                                                                          | A brief (\~10 minute) block delay occurred immediately post-fork, likely due to expected ledger rewrite processing or peer churning, which node teams are monitoring.                 |
| On-Chain Budget Proposals                 | Kevin reported that both the TSC and Intersect on-chain budget proposals reached roughly 70% support from DREPs ahead of the July 23rd expiration deadline.                                                                | The committee noted that both proposals are tracking above the passing threshold, marking a positive outcome for community governance.                                                |
| Linear Leios Status                       | The committee discussed the status of technical inquiries sent to the Linear Leios team. Neil and Marcin clarified that previous confusion stemmed from delays in routing April responses versus the newer June questions. | Kevin confirmed that Jeff will attend next week's meeting to address hard fork planning and linear layoffs directly.                                                                  |
| Minimum Pool Cost Action                  | Kevin revisited last week's vote regarding the parameter change (reducing minimum pool cost to 75 and increasing Plutus memory limits) to confirm execution readiness.                                                     | The action is ready for enactment on Preview and will proceed straight to Pre-Prod and Mainnet per the previous committee decision.                                                   |
| DIjkstra Hard Fork Scope & Timelines      | The committee held an extensive debate on the proposed DIjkstra hard fork scope and the proposed October/November 2026 target timeline from the Product Committee.                                                         | Neil, Ryan, and Kevin noted that an October/November hard fork is overly optimistic given the required testing, node release cycles, and governance timelines.                        |
| SPO Voting Experience (CIP-151 / CIP-175) | Guest Ken-Erik (Civics Committee) presented on improving SPO governance participation by allowing voting without using cold keys.                                                                                          | While CIP-175 (certificate-based hot keys) is the proper secure path, it requires roughly six months of development and cannot make the Dijkstra hard fork without dedicated funding. |
| CIP-50 Status (Pledge Influence)          | Ryan reported that Jared Corduan has completed the code implementation for CIP-50 (adding an L parameter to scale rewards with pledge) and submitted a pull request to the ledger repo.                                    | CIP-50 aims to enhance Sybil resistance and increase the value of pool pledge without conflicting with other major ledger changes.                                                    |
| Post-Quantum Cryptography                 | A technical report from the IO cryptography team regarding post-quantum readiness was distributed to the committee.                                                                                                        | Detailed discussion on PQC was deferred to next week's agenda to allow Alex, Alonzo, and Christian to participate fully.                                                              |
| Intersect Governance Housekeeping         | Members were reminded to cast their votes on the Intersect bylaws. Christian offered to represent the TSC at the upcoming monthly ISC meeting.                                                                             | Members should pass any specific inquiries for the Intersect Board directly to Christian ahead of Monday's call.                                                                      |
| WanChain Security Incident                | Kevin provided a brief informational update regarding a recent exploit on WanChain involving a contract deployed two years ago, leading to token drains.                                                                   | The Security Council is actively monitoring the situation alongside impacted ecosystem projects like MinSwap.                                                                         |
