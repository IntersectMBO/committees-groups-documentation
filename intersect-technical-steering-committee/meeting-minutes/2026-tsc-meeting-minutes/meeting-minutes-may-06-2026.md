# Meeting Minutes May 06, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | No         | Alt - Secretary | N                 | N/A          |
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

* Filip Blagojevic
* Lorenzo Bruno
* Seun Gbiri
* Simo Simovic

Recording: [Technical Steering Committee - 2026/05/06 - Recording](https://drive.google.com/file/d/1obfqu8EEKhbzuLtmrULzmjm6SnsvsF-M/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/05/06 - Transcript](https://docs.google.com/document/d/1106duVVe2_ZZrklJZ9KmQ3js1O-VjGzxmgTdzRCNObs/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/05/06 - Chat Transcript](https://drive.google.com/file/d/1qxJYLEVLzgj4DyDGpPPnhwumLRIn-6Fo/view?usp=sharing)

## Agenda 6th May 2026

* Actions from the last meeting
* Intersect Election Results
* Leios Risks
* Post Quantum
* van Rossem Hard Fork
* TSC Budget Proposal
* AOB

## Decisions/Actions

**Decisions**

* **TSC Voting Rights:** Current members retain voting rights until the end of this week; new members take over next week post-onboarding.
* **Parameter Changes:** Approved the move to lower minPoolCost to 75 while keeping $K=500$ for now.
* **Pre-Prod Hard Fork:** Confirmed proceeding with the Protocol v11 hard fork (should hard fork working group gives the recommendation tomorrow, 7th May) and Plutus parameter updates on Pre-Prod this week.
* **Mainnet Strategy:** Agreed to a "one epoch delay" between Pre-Prod enactment and Mainnet submission for the Plutus upgrade.

**Actions**

* **Bosko:** Send onboarding invites and details to newly elected/reelected members this week.
* **Kevin & Bosko:** Coordinate offline to draft the DApp developer communication regarding cost risks.
* **Kevin:** Invite IOG cryptographers to present specific post-quantum risks to Cardano.
* **Neil & Sebastian:** Continue the Leios technical risk discourse in a written, public format (Google Doc).
* **Bosko & Ryan Williams:** Coordinate the submission of governance actions for parameter updates on Pre-Prod and Mainnet based on the agreed timeline.

<br>

| Topic               | Discussion                                                                                                                                                      | Notes                                                                                     |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| TSC Transition      | Bosko questioned the legitimacy of votes until new members are onboarded. Kevin and Lorenzo clarified that the current committee remains in force this week.    | New members start their term the month after elections (May).                             |
| Election Results    | Lorenzo announced the election results. Newly elected members will receive onboarding details and attend sessions next week.                                    | Onboarding focuses on policy reminders for new and existing members.                      |
| Member Recognition  | Kevin congratulated new members whole are elected/re-elected. Outgoing members Sebastian, Nicolas, and Duncan were thanked.                                     | Outgoing members are encouraged to remain as observers/contributors in open meetings.     |
| Committee Terms     | Kevin confirmed that incoming members serve a two-year term, expiring in April 2028.                                                                            | A process for those elected in October to confirm their status until 2027 is forthcoming. |
| Previous Actions    | Bosko reviewed pending actions, including the SEB proposal and expert feedback links for K=1000 and minPoolCost=75.                                             | Alex was absent for the initial part of this review.                                      |
| Parameter Changes   | Neil reported that the Parameters Committee voted to move forward with minPoolCost=75, but delayed K=1000 for further discussion.                               | A formal Change Proposal (PCP) will be created for the community review.                  |
| Communication Plan  | Kevin and Bosko discussed a formal plan to inform DApp developers of risks associated with total costs via the Hard Fork Working Group.                         | Kevin will assist Bosko in articulating the risks offline.                                |
| Post-Quantum Risks  | Neil requested that IOG cryptographers present specific risks to the Cardano ecosystem rather than general research.                                            | The goal is a self-contained public slide deck on ecosystem-specific risks.               |
| Leios Risk Analysis | Neil presented a risk framing for "Linear Leios," focusing on performance risks and its nature as a preemptive system that discards work.                       | Neil expressed concern that the system might not have monotonic performance under load.   |
| Leios Response      | Sebastian responded to Neil's analysis, arguing that the system is optimistic and that "discarded work" is a small fraction compared to total throughput gains. | Sebastian emphasized that Leios avoids resubmitting transactions already in mempools.     |
| Network Performance | Neil argued that Leios's 12MB data movement requirement might not be achievable transatlantically under certain loss conditions.                                | Neil views this as a reputational risk if throughput "falls off a cliff" under load.      |
| Protocol Impact     | Kevin noted that it must be verified that Leios does not negatively impact the underlying Ouroboros Praos safety arguments.                                     | Sebastian agreed that data availability is the key factor for Praos safety.               |
| Hard Fork Status    | Protocol version 11 hard fork on Preview is scheduled for this week, following a successful out-of-band vote.                                                   | Enactment is expected shortly after Blockfrost completes its upgrade.                     |
| Pre-Prod Upgrades   | The committee voted (5 in favor) to proceed with the Plutus parameter upgrade on Pre-Prod as soon as practical.                                                 | Submission is pending a heads-up to the Hard Fork Working Group.                          |
| Mainnet Schedule    | The committee approved a conditional vote to submit the Plutus upgrade on Mainnet one epoch after it is enacted on Pre-Prod.                                    | This ensures at least one epoch of testing on Pre-Prod before Mainnet submission.         |
