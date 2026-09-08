# Meeting Minutes September 02, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | No         | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | No         | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Nick Clarke

\
Recording: [Technical Steering Committee - 2026/09/02 - Recording](https://drive.google.com/file/d/1V4dAEFhfcxOZym8GRIB3xdpuyLocuZkV/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/08/26 - Transcript](https://docs.google.com/document/d/1buNCkBq1RB_dgh-sFR_3mWTrsEs2C3bXKEQrvweL-8o/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/09/02 - Chat Transcript](https://drive.google.com/file/d/1XsaDr2kjsLPIs9116UT3n8W2oli4AlRH/view?usp=drive_link)

## Agenda 2nd September 2026

* Actions from the last meeting
* Dijkstra era hard fork
* Serialisation Library
* Technical Steering Committee Budget
* Parameter Committee
* Post Quantum Cryptography
* CC Update has passed
* Committee Member Experience and Performance Review Survey
* Intersect Board elections 2026
* Q3 Reporting & Q4 Planning
* AOB

## Decisions/Actions

**Decisions**

* **Travel Support Cap:** The committee formally confirmed that travel support bursaries will be capped at a maximum of $2,000 per request, up to a total budget of $24,000 (up to 12 bursaries) for the current budget cycle.
* **Dijkstra Scope Clarification:** Confirmed the primary scope of the Dijkstra hard fork to consist of linear Leios, nested transactions, CIP-50, and CIP-23 (Part 1).
* **Serialization Library Custody:** Agreed that Intersect will step in to take ownership or fork the Emergo serialization library if Emergo ceases maintenance.

**Actions**

* **Kevin:** Reach out to Jeff (out of band) to resolve information flow issues and establish access to a centralized technical risk register.
* **Kevin & Terence:** Draft Statements of Work (SOWs) for travel funding and work packages to enable callouts for travel claims.
* **Kevin:** Check with Fergie / IO Research to ensure the proposed Post-Quantum Cryptography report does not duplicate existing internal research.
* **Neil:** Finalize the "case against" document regarding the K=1000 parameter proposal prior to the Parameter Committee meeting.
* **Nick:** Take ownership of tracking the status, usage, and maintainers of the Emurgo serialization library.
* **Ryan:** Gather feedback from SPOs during the upcoming SPO call regarding the Minpool cost reduction proposal and participation obstacles.
* **TSC Members:** Vote out-of-band on the prioritization of commissioned technical report topics and volunteer for Work Package leadership roles.

| Topic                                        | Discussion                                                                                                                                                                                                                                                                                                                            | Notes                                                                                                                                              |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Attendance & Availability                    | Ryan noted he will be unavailable for workday meetings starting in three weeks for two months due to personal reasons. He will monitor Slack in the evenings when possible.                                                                                                                                                           | Ryan may set up a proxy vote through Terence or Bosco during his absence.                                                                          |
| Security Scanning & AI Models                | Ryan mentioned obtaining access to OpenAI's trusted cyber program and state-of-the-art Daybreak models (with Astra model releasing soon) to potentially scan libraries. Kevin and Marcin advised caution regarding scanning public code on external cloud/AI platforms due to the risk of leaking unknown vulnerabilities or prompts. | Kevin referenced a presentation from Consensus Diligence regarding AI model security usage trends.                                                 |
| Agenda & Quorum                              | The meeting formally commenced with 7 Technical Steering Committee (TSC) members present, satisfying the quorum requirement.                                                                                                                                                                                                          | Official meeting date logged: September 2, 2026.                                                                                                   |
| Action Items Review                          | Neil completed the action regarding larger max transaction execution units (red herring, no active execution). Neil is still drafting the "case against" document for the K=1000 action for the upcoming parameter meeting. Terence/Bosco confirmed the initial budget conversion/dispersal transactions have not yet occurred.       | Canonical Dijkstra scope was published in the hard fork working group channel. Vendor sequence details remain pending Node 11.2 release.           |
| Travel Funding Allocation                    | The committee discussed allocating travel bursaries for upcoming events like Token 2049 and the Node Diversity workshops. Kevin proposed offering up to 12 bursaries at $2,000 each (capped at a total $24,000 budget).                                                                                                               | The $2,000 max per request was confirmed by the committee as the official limit for the current budget cycle.                                      |
| Dijkstra Hard Fork Status                    | Ryan summarized node releases: Node 11.1 is mainnet ready; 11.2 includes early Dijkstra changes (excluding Leios); 11.3 will be the full Dijkstra hard-fork-ready scope; Node 12.0 will be the primary version. Node diversity workshops are scheduled for Singapore (Oct 7–8) and London (Nov 12–13).                                | Clarified Dijkstra scope includes linear Leios, nested transactions, CIP-50, and CIP-23 (Part 1).                                                  |
| Technical Risk & Information Flow            | Neil and Kevin expressed frustration regarding dispersed information, missing definitive technical risk logs, and unclear communication flows from vendors. Kevin agreed to engage directly with Jeff out of band to establish a clear, centralized technical risk log.                                                               | The committee emphasized that the vendor is responsible for maintaining and exposing a definitive risk register.                                   |
| Serialization Library                        | Christian raised a concern about the Emergo serialization library, a critical ecosystem dependency whose long-term maintenance status is unclear. The committee agreed Intersect should adopt or fork it if Emergo does not continue maintenance.                                                                                     | Nick agreed to track this item and investigate its current maintenance status and dependent tooling.                                               |
| TSC Budget & Work Packages                   | Kevin outlined policies for administering community funds and introduced plans to break the TSC budget into three Work Packages: (1) Technical Engagement & Travel, (2) Technical Involvement/Sub-editors/Parameter Committee, and (3) Technical Reviews.                                                                             | Statements of Work (SOWs) will be drafted for individual work streams. Volunteers were requested for Work Package leads.                           |
| Proposed Commissioned Reports                | The group reviewed potential technical reports to commission: Governance thresholds/risk, Governance incentives, Post-Quantum Cryptography (PQC), and Security/All-Node implementations. Christian and Kevin highlighted PQC as a key report candidate to map out requirements ahead of 2030 targets.                                 | Prioritization of 2 to 3 report topics will be voted on out of band. Kevin will verify IO Research's current scope on PQC to avoid duplicate work. |
| Parameter Committee Update                   | Discussed the failure of the Minpool cost reduction and Plutus memory unit governance action. Low SPO turnout (37.5% vote) prevented it from reaching the necessary participation threshold. Ryan will seek feedback on an upcoming SPO call.                                                                                         | The committee discussed whether to split or resubmit the proposal, or prioritize the upcoming K=1000 community info action instead.                |
| Governance & Constitutional Committee Update | The Constitutional Committee update action passed successfully, ensuring governance actions and parameter changes can continue without hitting a governance freeze or impacting hard fork timelines.                                                                                                                                  | Meeting adjourned after 56 minutes.                                                                                                                |
