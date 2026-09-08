# Meeting Minutes April 29, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | No         | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | No         | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | No         | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | No         | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | No         | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | No         | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Seun Gbiri

\
Recording: [Technical Steering Committee - 2026/04/29 - Recording](https://drive.google.com/file/d/17Ko1osb_tJ1kJGnHQ8t2slNgWiLScJ4f/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/04/29 - Transcript](https://docs.google.com/document/d/1PAZKb0TWtUYD7KdKHI0xVTtCqr3ENpKWeoqCGm7tywk/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/04/29 - Chat Transcript](https://drive.google.com/file/d/1ojRq3FStFfeSOGbZDIxmgGwtU4DFNZ2X/view?usp=drive_link)

## Agenda 29th April 2026

* Actions from the last meeting
* Update on committee election process
* TSC Budget Proposal
* van Rossem Hard Fork
* Parameter Committee Update
* Post Quantum Risks
* Leios Risks
* AOB

## Decisions/Actions

**Decisions**

* **Budget Consolidation:** TSC agreed to adjust proposal from their specific budget, as Intersect central has officially picked them up.
* **Hard Fork Schedule:** Formally adopted the "Plan A" timeline for the Van Rossom hard fork, targeting a May 5th Preview fork.
* **Leios Deep-Dive:** Agreed to reserve 30 minutes at the start of the next meeting for a detailed technical discussion on the risks Neil raised regarding Linear Leios.

**Actions**

* **Bosko & Terence:** Meet immediately after this call to finalize and submit the TSC budget proposal to Ekklesia.
* **Alexander:** Share the links for expert feedback on K=1000 and minPoolCost=75 for committee and community review.
* **Kevin & Bosko:** Devise a formal communication plan for DApp developers regarding Plutus cost model risks.
* **Ryan:** Continue coordinating with CIP editors to refine the "maximal list" of forkable CIPs for Dijkstra era prioritization.
* **Kevin:** Invite IOG cryptographers to present their research on post-quantum cryptography to the TSC.

| Topic                    | Discussion                                                                                                                                      | Notes                                                                                                                     |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum         | Kevin opened the meeting. With only three voting members present, the committee was not quorate. Decisions require out-of-meeting ratification. | Discussion began regarding incorrect meeting links in Discord and fixing them for consistency.                            |
| CIP-179 & Prioritization | Ryan discussed combining efforts on standardizing feedback and conditional voting metadata with Matt and Pi.                                    | The goal is to determine community priorities for work items without duplicating efforts across multiple SIPs.            |
| Committee Elections      | Voting closes this Friday. There are 10 candidates for 5 open positions.                                                                        | Alex declined to campaign, but Kevin highlighted the valuable work both Alex and Neil have delivered during their tenure. |
| Election Events          | Upcoming events include a Virtual Hub (April 30 at 15:00 UK) and an X Space (April 28 - previously occurred).                                   | Candidates are encouraged to attend to answer voter questions directly.                                                   |
| Overall Intersect Budget | The main Intersect budget proposal was submitted last Friday. It is for a lower total amount than last year.                                    | Work Package 2 focuses on technical coordination, which directly involves the TSC.                                        |
| TSC Budget Alignment     | Three TSC items were absorbed into the main Intersect budget: Technical meetings/workshops, meeting organization, and Security Council support. | This prevents budget duplication and ensures Intersect staff handles the logistical burden.                               |
| TSC Proposal Submission  | Bosko and Terence will coordinate the final submission of the TSC-specific budget to Ekklesia.                                                  | The deadline for submission is May 8th, with an edit window open until May 22nd.                                          |
| KPIs & DeFi Targets      | Alexander voiced strong concerns about focusing TSC KPIs on DeFi targets like TVL (Total Value Locked).                                         | Alexander argued TVL is out of scope and should be removed from technical performance goals.                              |
| Van Rossem Hard Fork     | Node 10.7.1 is a Mainnet release. Performance issues from 10.7.0 (50% CPU spikes) and rare consensus conditions have been addressed.            | Node v11 is expected early next week for testnet forking.                                                                 |
