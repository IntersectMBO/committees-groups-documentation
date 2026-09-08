# Meeting Minutes July 8, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | No         | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | No         | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ryan Williams

Recording: [Technical Steering Committee - 2026/07/08 - Recording](https://drive.google.com/file/d/1DPSMTE4m7tIhOvYvrmUV0CTDIJRzmo4Y/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/07/08 - Transcript](https://docs.google.com/document/d/1GOeHVmyD1zh2_nGOIWBfFgHj1w9tRnFy1TpFibiWIss/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/07/08 - Chat Transcript](https://drive.google.com/file/d/19qQ20OoGTFh4EnLv6tkLBnrE6YPUx22O/view?usp=drive_link)

## Intros

**Christian Taylor:** Christian Taylor, Vice Chair (TSC), Cofounder of Open Source Cowboy, Governance at Filecoin foundation, Advisor to Andamio, Charli3, and KAI Systems / Aquana\
**Kevin Hammond:** Kevin Hammond, TSC Chair, Ensurable Systems Ltd (Co-Founder)\
**Ryan Wiley**, TSC Member, Cybersecurity Professional, Incentives Researcher\
**Udai Solanki:** Udai Solanki, TSC Member, AIQUANT Technologies

## Agenda 8th July 2026

* Actions from the last meeting
* Testnet Purposes
* Parameter Committee
* SecondFi Status Update
* van Rossem Hard Fork Status
* Dijkstra Hard Fork Planning
* 2026 Budget
* Technical Gating Requirements for Linear Leios
* Post-Quantum Cryptography
* AOB

## Decisions/Actions

**Decisions**

* **Cardano Over Coffee Slot:** Accepted the offer to take up a presentation slot on July 16th at 15:00 UTC to address the TSC budget.
* **TSC Budget Tweet Approval:** Agreed to a soft deadline of 16:00 UTC (July 8th) for TSC feedback on the budget Twitter thread. If no vetoes are submitted, the thread will be approved for publication.
* **Testnet Document Next Steps:** Agreed to move the Testnet Purpose document review offline for further community iteration, specifically targeting alternative node developers.

**Actions**

* **Bosko:** Pass on the approved TSC budget messaging to the Intersect communications team for an upcoming blog post.
* **Kevin:** Reach out to the Cardano Over Coffee team to finalize the coordination for the July 16th presentation slot.
* **Kevin:** Request a formal summary or transcript of the recent IO seminar presented by Hamza regarding post-quantum cryptography.
* **Neil:** Coordinate an offline engagement strategy to address the deficient vendor response regarding linear layoffs.
* **Ryan:** Update the Cardano Blueprint testnet draft to incorporate the strict "Not for Production Use" disclaimer and define explicit negative use cases.
* **Ryan / Alex:** Sync up regarding the coordination and rationale formulation for the upcoming pool cost reduction and Plutus memory unit governance bundle.
* **Terence / Bosko:** Publish the TSC Budget proposal thread on X (formerly Twitter) following the 16:00 UTC sign-off window.



| Topic                                   | Discussion                                                                                                                                                                         | Notes                                                                                                                                         |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Agenda Review & Prioritization          | Kevin opened the meeting, noting that Christian would attend only the first 30 minutes, Leo and Alonso were unable to join, and Ryan would be invited up to discuss testnets.      | Six TSC members were present, meeting the requirement for a quorum.                                                                           |
| Review of Action Items                  | Bosko shared the ClickUp list focusing on upcoming tasks, including post-quantum cryptography and practical parameters.                                                            | Kevin noted he reached out to the Cardano Over Coffee team regarding a budget breakdown session.                                              |
| Cardano Testnet Purpose Document        | Ryan presented a draft document defining the formal purposes, upgrade paths, and lifecycles (short-lived vs. long-lived) for testnets like Preview, Pre-Prod, Sancho, and Dripnet. | Neil and Kevin emphasized adding a clear upfront disclaimer that testnets are not for production and offer no uptime or stability guarantees. |
| Parameter Committee Update              | Alex gave an update on the successful Parliamentary Committee meeting and noted that the constitutional minimum size reduction proposal thresholds had been met.                   | A proposal to bundle a pool cost reduction (to 75) with a 25% Plutus memory unit limit increase is being drafted for Q3.                      |
| K=1000 Parameter & Info Action          | The Parameter Committee decided to present a side-by-side pro/con view for K=1000 to educate DREPs rather than endorsing a stance.                                                 | An "Info Action" (via SIP-179 tooling) will be launched to gather specific, unambiguous feedback from SPOs.                                   |
| Second\_fi Incident Status Report       | Kevin provided a public update regarding Second\_fi and the CTRL wallet ceasing operations. Security Council has submitted forensic questions to the auditor via Emurgo.           | Users are strongly encouraged to strictly follow the official Emurgo automated recovery processes to avoid losing funds.                      |
| Daedalus Wallet Support                 | Kevin highlighted the importance of supporting open-source, full-node wallets like Daedalus.                                                                                       | A Twitter thread in support of the Daedalus wallet has been drafted and will be published in a few days.                                      |
| Babbage/Chang Hard Fork Ledger Behavior | Ryan (Cerkoryn) explained a critical ledger design rule: if a governance action expires in the same epoch a hard fork is ratified, it is dropped even if passing.                  | Kevin clarified that this is intentional ledger design behavior to prevent rule misalignment, not a bug.                                      |
| On-Chain Proposals At Risk              | If the hard fork ratifies immediately, the Hydra proposal and Committee Minimum Size parameter risk being dropped.                                                                 | An urgent call to action was issued for DREPs and ADA holders to vote immediately, particularly on the Ikigai proposal.                       |
| Dijkstra Hard Fork Planning             | The upcoming Working Group meeting on July 9th at 14:00 UTC will be dedicated to scoping out the complex Dykstra hard fork.                                                        | The Product Committee has been manually invited. This hard fork will involve constitutional amendments and guardrail script changes.          |
| 2026 TSC Budget Proposal                | The on-chain budget proposal sits at \~35% support, short of the 67% needed before the July 23rd expiry date.                                                                      | A communications push is planned, including an Intersect blog post and a Cardano Over Coffee slot on July 16th at 15:00 UTC.                  |
| Linear Leios Response                   | Neil reported that the vendor response regarding linear leios failed to answer any of their direct technical tracking questions.                                                   | Neil and Kevin will take this conversation offline to figure out how to engage the right engineering contacts.                                |
| Post-Quantum Cryptography               | The committee briefly discussed a Linux Foundation report shared in the chat. The material focuses on the vulnerability of cryptographic primitives.                               | Neil noted the need to refocus the material specifically on blockchain blast radiuses, PR/FUD management, and educational hurdles.            |
