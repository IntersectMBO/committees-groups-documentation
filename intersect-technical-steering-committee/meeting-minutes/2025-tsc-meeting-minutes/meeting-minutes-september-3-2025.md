# Meeting Minutes September 3, 2025

## Attendees:

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | No         | Chair       | Y                 | October 2025 |
| Adam Dean                | Yes        | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Lorenzo Bruno            | No         | Secretary   | N                 | N/A          |
| Markus Gufler            | No         | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | No         | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | No         | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | Yes        | Member/Seat | Y                 | October 2025 |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | Yes        | Member/Seat | Y                 | April 2026   |

Community/Other Attendees

* N/A



**Recording:** [Technical Steering Committee - 2025/09/03 - Recording](https://drive.google.com/file/d/1QWySD8IsNRSH2sIx_HYIDhtCsg9KNBvf/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/09/03 - Transcript](https://docs.google.com/document/d/1DoBm7GS6nESIOsxij_CgF55QSGAdDmXpzJZCxU-9n5k/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/09/03 - Chat Transcript](https://drive.google.com/file/d/1o9_ss-hn9KWeAXm1tMmxH7cFjEdcOOn9/view?usp=sharing)

## Intros

**Adam**: OSC, TSC, CIP Editor, DripDropz LLC\
**Alex:** TBD\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:**  TBD\
**Lorenzo:** TBD\
**Markus:** TBD\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TBD\
**Sebastian:** TBD\
**Tex:** Open Source Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison

## Agenda 9.03.25

* Informal, No pre-planned Agenda

## Decisions/Actions

#### Decisions

1. **Objective review:** The TSC decided to provide an objective review of the CIP and avoid making subjective judgments. Their role is to provide informed analysis of technical trade-offs, not to make final product decisions.\
   <br>
2. **Delay of other topics:** The group decided to table other topics, such as the disaster recovery fire drill, to focus on the CIP analysis.

#### Actions

1. **Draft a technical analysis of CIP-0164:** The Technical Steering Committee (TSC) will create an "ELI5" (Explain Like I'm 5) document to be published as commentary on the CIP's repository. Adam requested that all members read and prepare initial thoughts on the CIP for the next meeting.

| Topic                        | Discussion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Notes                                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Call to Order/Quorum         | Benjamin called the meeting to order. Acknowledged they didn't have a quorum of six, as only five members were present.                                                                                                                                                                                                                                                                                                                                                                             | The meeting proceeded as an informal discussion rather than a formal board meeting.                                                                                               |
| Upcoming Elections           | The group discussed the upcoming board and technical steering committee (TSC) elections. Adam noted that the committee elections were less than a month away and raised concern about the lack of candidates and a timeline. Jonathan clarified that the announcement for final candidates is on October 26th and that existing members remain until the results are announced.                                                                                                                     | The timeline for the TSC elections is near the end of October.                                                                                                                    |
| TSC Candidate Qualifications | Adam stated that any references to tendering should be removed from the TSC's qualifications. Benjamin humorously noted they were all asked to campaign on those qualifications, which were later said not to exist.                                                                                                                                                                                                                                                                                | Neil and Adam agreed that references to tendering are no longer relevant to the TSC's qualifications.                                                                             |
| CIP-0164: Ouroboros Leios    | The main topic of the meeting was the recently published CIP-0164 (Ouroboros Leios), which aims to increase transaction throughput. Neil expressed significant technical concerns about the proposal, arguing that it prioritizes throughput over latency and concurrency. He believes the proposal's approach pushes off the "difficult problem" of concurrency and could lead to network centralization by requiring more expensive hardware to run nodes.                                        | Concerns were raised about the technical direction of CIP-0164 and its potential negative impact on decentralization and business-to-business activity due to increased latency.  |
| Latency vs. Throughput       | Neil and Adam discussed the trade-offs of the new proposal. Neil pointed out that while throughput increases, transaction inclusion latency goes up by a factor of two to three, which he believes would have a negative impact on business-to-business activities that require low latency. Jonathan and Nicolas noted that some latency is inherent in throughput-focused layer-1 solutions.                                                                                                      | The group debated whether increased throughput or lower latency is more critical for the Cardano network's long-term health and business adoption.                                |
| Communication of Trade-offs  | Adam, Jonathan, and Neil discussed the importance of clearly communicating the technical trade-offs of the CIP to the broader community. Neil criticized past communications for only highlighting the positive aspects of such proposals and not the downsides, which he believes creates false expectations. Adam suggested the TSC's role could be to translate highly technical documents into a more understandable format for the public and other committees, such as the product committee. | The TSC recognized its potential role in bridging the gap between highly technical proposals and the community by providing clear, unbiased explanations of technical trade-offs. |
| Role of the TSC              | Nicolas argued that the decision of whether to prioritize latency or throughput is a "product question," not a technical one. Neil disagreed, stating that the TSC's role is to provide the "informed trade" and perform a risk analysis for decision-makers. The group concluded that the TSC should provide objective facts and questions about the proposal without making a final decision.                                                                                                     | The TSC's role was defined as providing objective technical analysis and highlighting key trade-offs to the community and other committees.                                       |
| Action Items                 | Adam motioned that the TSC would conduct an objective review of the Leios and Faelen CIPs. The committee will work on an "ELI5" (Explain Like I'm 5) document to be published as commentary on the CIP's repository. Adam asked that all members at least read and form an initial opinion on the Leios CIP by the next meeting.                                                                                                                                                                    | The TSC agreed to create an ELI5 document summarizing the key technical aspects and trade-offs of the proposed CIPs.                                                              |
| Disaster Recovery Fire Drill | Jonathan mentioned the need to schedule a disaster recovery fire drill, noting that Kevin would need to be present for it.                                                                                                                                                                                                                                                                                                                                                                          | This topic was tabled for a future meeting when Kevin is available.                                                                                                               |
| 2030 Vision Roadmap          | Adam mentioned that the product committee is working on a 2030 vision roadmap and has requested the TSC's input on what is "technically needed to reach the 2030 desired state." Adam noted that today's discussion is a good starting point for that work.                                                                                                                                                                                                                                         | The TSC will contribute its technical expertise to the product committee's 2030 vision roadmap.                                                                                   |
