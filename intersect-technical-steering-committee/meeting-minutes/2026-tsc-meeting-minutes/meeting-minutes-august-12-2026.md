# Meeting Minutes August 12, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | No         | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | No         | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | No         | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ken-Erik Ølmheim
* Sebastian Nagel



Recording: [Technical Steering Committee - 2026/08/12 15:57 CEST - Recording](https://drive.google.com/file/d/1-XqYb13Y-2J9cEKlbJSoiXdwEaaCw-DG/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/08/12 15:57 CEST - Transcript](https://docs.google.com/document/d/1Oe86DnCCluEI9ondD8F5O9k1C51lCp13KDwBYKydIdU/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/08/12 - Chat Transcript](https://drive.google.com/file/d/1cpvAtZXlVQ2RepzUXKkAzeLjM0qUb6kJ/view?usp=drive_link)

## Agenda 12th August 2026

* Actions from the last meeting
* Technical Steering Committee Budget
  * CIP editors work breakdown and contracts
* Dijkstra era hard fork
* Linear Leios: Questions
* minPoolCost Reduction/Plutus mem limits increase
* Cardano Vision 2030 KPI Framework: Committee Feedback - CPC Survey
* Post Quantum Cryptography
* AOB

## Decisions/Actions

**Decisions**

* **Public Budget Transparency:** The TSC decided to issue periodic public updates (including posts on X) detailing the conversion and utilization of the secured $24k USD budget for technical experts and reports
* **CIP Impact Analysis Responsibility:** Impact analyses for protocol changes will originate from CIP authors/implementers and undergo validation by CIP editors (e.g., Robert) before being centralized on the Cardano Upgrades site.
* **Leios Review Framework:** The TSC will utilize a shared Google Doc as the central working document to provide technical feedback and evaluate showstoppers for the Leios implementation.

**Actions**

* **Alex:** Coordinate with Marcus to ensure CIP-155 is included in the upcoming SPO campaign.
* **Alex, Bosko, Tex:** Draft and publish a call-to-action post on X encouraging SPOs to participate in active governance votes.
* **Bosko, Christian, & Tex:** Meet offline to finalize contract templates and milestone structures for contributors based on past experience.
* **TSC members:** Review the Leios technical working document and add comments/feedback.
* **Christian:** Meet with Neil or Kevin to draft an action plan on post quantum cryptography and present it to the TSC.
* **Christian:** Upload the corrected repository security scan reports and coordinate with Tex regarding escalation to Nick.

| Topic                                     | Discussion                                                                                                                                                                                                                  | Notes                                                                                           |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Meeting Opening & Attendance              | Bosko opened the meeting. Attendance was confirmed, noting apologies from Neil and absence of Marcin, Neil, and Kevin. The transition of Nick Clark replacing Matt Vis as Director of Cardano Tech at Intersect was noted.  | Attendance logged; quorum acknowledged.                                                         |
| Action Items Review                       | Alex confirmed documentation/user guides for DNS SRV records were shared on Slack. Marcus is planning an SPO campaign for SIP-155.                                                                                          | DNS SRV docs completed.                                                                         |
| TSC Budget & Transparency                 | Bosko provided an update on securing $24k USD for technical expert attendance and technical reports. The TSC will publicly report usage to maintain transparency once funds are secured and conversion rates are finalized. | Need to post transparent updates on X regarding budget usage.                                   |
| Contracting & Templates                   | Discussion regarding contract templates and milestone breakdowns for contributors. Bosko requested assistance to draw on past experience.                                                                                   | Bosko, Christian, and Tex to collaborate offline.                                               |
| Cardano Upgrade / Hard Fork Working Group | Ryan summarized the recent hard fork working group meeting. Dates/scope remain unchanged, communications are aligned, and Miro timelines are being updated. Bootstrap key requirements (BLS keys) were emphasized.          | Critical to document impact analysis for CIPs to communicate breaking changes to the community. |
| CIP Impact Analysis Ownership             | Discussion on who is responsible for drafting and validating CIP impact analyses. Sebastian suggested CIP authors and implementers should provide initial details.                                                          | LLMs can draft summaries, with validation needed from CIP editors (e.g., Robert).               |
| Leios Development & Risk Assessment       | Sebastian presented updates on Leios development, the initial risk assessment, and open technical questions regarding protocol stability. Google Doc provided for TSC member feedback.                                      | TSC members asked to review and comment on the Leios Google Doc.                                |
| Governance & Constitutional Changes       | Brief mention of governance progress, including the Constitutional Amendment portal and CIP-179 being live on the preview testnet.                                                                                          | CIP-179 to be enabled on Devnet/Gougen tools soon.                                              |
| SPO & DRep Voting Participation           | Alex raised a concern regarding low SPO participation on current governance votes despite a 10% increase in DRep support.                                                                                                   | Intersect and TSC to draft/post calls-to-action on X.                                           |
| Product Committee Framework               | Leandros confirmed completion of the Product Committee KPI framework survey via Google Form on behalf of the committee.                                                                                                     | Task completed.                                                                                 |
| Repository Security Scanning              | Christian reported running an open-source security scan across repositories, fixing the assessment, and preparing corrected reports for review.                                                                             | Report to be shared with Tex and escalated to Nick Clarke if relevant.                          |
| Leios Testnet Demo (Musashi)              | Sebastian demoed the Musashi testnet running Leios prototype releases, demonstrating block certification, transaction throughput, telemetry, and committee distribution.                                                    | Musashi testnet actively running 10th prototype iteration.                                      |
| Red Team & Threat Modeling                | Discussion on Leios security testing, including DoS vectors, EB diffusion, VRF/BLS key rotations, and protocol burst mitigations.                                                                                           | Red team actively simulating attack vectors on the testnet.                                     |
