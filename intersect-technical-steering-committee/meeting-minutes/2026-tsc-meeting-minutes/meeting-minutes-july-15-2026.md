# Meeting Minutes July 15, 2026

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
| Udai Solanki       | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* None

Recording: [Technical Steering Committee - 2026/07/15 - Recording](https://drive.google.com/file/d/16JDltmRkHSjp6_RGOyMGUaofrkbbz8U8/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/07/15 - Transcript](https://docs.google.com/document/d/1pMqxVPZhoD6m9m6lB4xdKcfVxZGgIbdMa_Qah1Pw9is/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/07/15 - Chat Transcript](https://drive.google.com/file/d/186mlpmEzj5wLqCyu_Wq7fQ_LObX4XqT-/view?usp=drive_link)

## Intros

**Christian Taylor:** Christian Taylor, VC of TSC, Filecoin Gov, Andamio, Kai Systems, no longer charli3 Advsiory\
**Kevin Hammond:** Kevin Hammond, TSC Chair, CEO Ensurable Systems Ltd\
**Ryan (Cerkoryn):** Ryan Wiley, TSC Member, Cybersecurity Professional, Incentives Researcher\
**Udai Solanki:** Udai Solanki, TSC Member, AIQUANT\
**Neil Davies:** Neil Davies, TSC member, Parameter Commte, PNSol

## Agenda 15th July 2026

* Actions from the last meeting
* van Rossem Hard Fork Status
* Dijkstra Hard Fork Planning
* Parameter Committee
* 2026 Budget
* Product Committee Roadmap/KPIs
* Technical Gating Requirements for Linear Leios
* Quantum Cryptography
* AOB

## Decisions/Actions

**Decisions**

* **Assertive Parameter Deployment:** Approved submitting the minimum pool cost reduction (75) and Plutus memory limit increases to Pre-Prod and Mainnet concurrently (Passed 5-1).
* **Dijkstra Scope Freeze Target:** Endorsed aiming for a preliminary technical scope freeze for the Dijkstra hard fork by the end of July 2026.
* **Cardano Over Coffee Attendance:** Agreed that Kevin and Neil will attend the Cardano Over Coffee X Space to advocate for the TSC budget on July 16th, while Ryan and Bosko cover the conflicting Hard Fork Working Group meeting.
* **PQC Agenda Delay:** Approved delaying the post-quantum cryptography summary discussion to the next session to allow Christian to finalize the report.

**Actions**

* **Bosko:** Organize and publicize the details (Google Meet link/timing) for the public van Rossem hard fork bridge call.
* **Bosko:** Forward the Product Committee's KPI and PR request details directly to Leandros for review.
* **Bosko:** Share the Intersect communications support document containing links and graphics with the TSC as soon as it is received from the marketing team.
* **Christian:** Finalize the post-quantum cryptography summary report by Friday, July 17th, for inclusion in next week's agenda.
* **Kevin:** Draft a reminder tweet urging the community to vote on the on-chain TSC budget proposal before the July 23rd deadline.
* **Kevin:** Contact Jeff to resolve the communication confusion and request a formal response to the June technical gating questions regarding linear Leios.
* **Kevin:** Follow up on the outstanding action to acquire a summary or transcript of Hamza's post-quantum cryptography seminar.
* **Neil & Ryan:** Collaborate on drafting a visual dependency graph and timeline to demonstrate the realistic constraints of the Dijkstra hard fork.

| Topic                                  | Discussion                                                                                                                                                                          | Notes                                                                                                                                                     |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Agenda Review & Attendance             | Kevin opened the meeting, noting that some members were traveling. Alex was unable to attend due to scheduling conflicts and will be prioritized for the week of July 27th.         | Six TSC members were present, establishing a quorum. Marcin joined representing the developer perspective.                                                |
| Review of Previous Action Items        | Bosko ran through the pending actions. Kevin's task to request a summary of the post-quantum cryptography seminar remains outstanding.                                              | The approved TSC budget messaging, Cardano Over Coffee setup, and the Daedalus Twitter thread tasks were completed.                                       |
| Van Rossem Hard Fork Status            | Ryan reported that the van Rossem hard fork was successfully ratified on July 13th and is scheduled to be enacted on July 18th.                                                     | Approximately 93% of block production is currently running node version 11, well exceeding the 85% target.                                                |
| Van Rossem Impact & Side Effects       | Neil inquired about on-chain side effects. Kevin and Ryan confirmed that the Ikigai deposit withdrawal proposal expired and was dropped before reaching its threshold.              | There is the option to resubmit the Ikigai proposal if they wish to reconsider it post-hard fork.                                                         |
| van Rossem Public bridge call          | Bosko is coordinating a public technical bridge call to monitor the hard fork enactment.                                                                                            | The event will be completely public and likely hosted via Google Meet or as an X Space.                                                                   |
| Dijkstra Hard Fork Planning            | The Hard Fork Working Group proposed a target of November 2026 for a light Dykstra hard fork, focusing primarily on nested transactions.                                            | Neil and Kevin noted a November deadline is highly ambitious and potentially infeasible given testing and governance lead times.                          |
| Dijkstra Feature Scope                 | There is clear tension over what features should be included. Ryan shared a draft of potential features (Plutus V4, Paris, Laos block body extensions).                             | Marcin and Neil highlighted the risk of unintended feature interactions (e.g., resource consumption spikes if Paris and Laos are enabled simultaneously). |
| Mapping Ecosystem Dependencies         | Ryan highlighted that a dependency mapping document has been created for projects to declare their implementation requirements.                                                     | Bosko is setting up a dedicated GitBook space for the TSC to organize Dijkstra documentation.                                                             |
| Parameter Changes & Bundling           | The Parameter Committee submitted a governance action reducing minimum pool cost to 75 and increasing Plutus limits. This is currently on the Preview network.                      | The action is scheduled for enactment on Preview this week. Kevin proposed an assertive plan to submit to Mainnet concurrently with Pre-Prod.             |
| Voting on Parameter Deployment         | The committee voted on whether to proceed with the assertive parameter deployment timeline (submitting to Mainnet and Pre-Prod together).                                           | The motion passed with 5 votes in favor and 1 against (Neil, acting as devil's advocate for risk mitigation).                                             |
| 2026 TSC Budget Proposal               | The TSC budget proposal is live on-chain with roughly 43% support, but requires 67% to pass by its July 23rd expiration date.                                                       | The main Intersect budget proposal, on which the TSC budget depends, is lagging at 36.8% support.                                                         |
| Budget Public Outreach & Communication | Kevin and Neil will represent the TSC at the Cardano Over Coffee X Space on July 16th at 14:00 UTC to drum up voting support.                                                       | Bosko will share a comprehensive communications package from the Intersect marketing team to synchronize social outreach.                                 |
| Product Committee KPI PR               | Bosko passed information to Kevin regarding a request from the Product Committee for the TSC to submit a PR based on KPIs.                                                          | Leandros was not yet aware of this request. Bosko will share the details directly with Leandros.                                                          |
| Linear Leios Technical Gating          | Kevin and Neil discussed a mismatch regarding the linear Leios technical document. Marcin clarified that the received response was for the April inquiries, not the June inquiries. | The June technical questions remain outstanding due to previous communication gaps. Kevin will seek clarification from Jeff.                              |
| Post-Quantum Cryptography              | Christian requested a one-week extension to finalize the summary report on post-quantum cryptography.                                                                               | The report will be completed by Friday and placed at the top of the next TSC meeting agenda.                                                              |
