# Meeting Minutes January 14, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | No         | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | No         | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Christian Taylor
* Niamh Ahern
* Fergie Miller



**Recording:** [Technical Steering Committee - 2026/01/14 - Recording](https://drive.google.com/file/d/1Y9fQTiLoKwZQXMyc0lLukB-AAWJwp0cm/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2026/01/14 08:29 CST - Transcript](https://docs.google.com/document/d/1Slyp9TeWEcDAMeSOOmaZjxKFXII8VzXFGENpVGtVxXU/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2026/01/14 - Chat Transcript](https://drive.google.com/file/d/1IO07k6wE65kTpibvwwDclg4MOoTcX7TG/view?usp=sharing)

## Intros

Kevin:  Kevin Hammond, TSC chair, Ensurable Systems\
Leo: Developer@KeyPackt/AnetaV2/GenWealth single pool SPO, CEO LnLlabs, TSC member\
Neil: TSC, Network Params, PNSol Ltd\
Nicolas: Nicolas Biri, TSC voting member, Director of Software Architecture, IOG.\
Ryan: Ryan Wiley, TSC Voting Member, Cybersecurity Professional\
Sebastian: Sebastian Nagel, TSC voting member, Software Architect, nCoding, IOE\
Bosko: Bosko Majdanac - Senior Project Manager, Intersect Staff, TSC Secretary\
Tex: Terence "Tex" McCutcheon - Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Liaison\
Christian: Christian Taylor, Head of OSO/ Incubation, Intersect and a guy who pretends to know what he's doing regularly

## Agenda 01.14.26

* Actions from the last meeting
* Chain Incident Partition Report
* Hard Fork Update (van Rossem)
* Presentation on increasing k to 1,000
* TSC Operational Budget
* Security Incident Office Appointed
* 2030 Vision
* IOR 2025 EOY Report
* AOB

## Decisions/Actions

**Decisions**

* Closure of Working Group: The Technical Steering Committee formally voted to close the Chain Incident Working Group as the report is now finalized.
* Product Committee Representation: The group decided not to send the full TSC to the 90-minute Product Committee meeting; instead, a smaller representative group (Neil, Leandro, Kevin, Nicolas, and Ryan) will attend.
* Hard Fork Naming: The name "van Rossem" was confirmed and the info action has been submitted on-chain.
* Report Finalization: Version 0.5 of the Chain Incident Report (dated the previous Friday) was approved as the final factual version, with no further changes to be made by the TSC.
* Security Appointment: Mike was officially appointed and onboarded as the Security Incident Response Officer.

**Actions**

* Kevin: Follow up with Alex via Slack to confirm if the blog post regarding the Constitution Committee size has been published.
* Kevin: Apply additional pressure to the Intersect Executive and Board to ensure the timely release of the Chain Incident Report.
* Ryan: Perform detailed mathematical analysis on how much stake needs to move to smaller pools to make them viable under the proposed K=1,000 change.
* Kevin: Schedule a "pre-meeting" for the TSC small group to align on KPI criticisms before the joint session with the Product Committee next Tuesday.
* TSC Members: Download and save a PDF copy of the finalized Chain Incident Report (v0.5) for personal records to ensure no unauthorized changes are made during the legal review.
* TSC Members: Review the 2025 Foundational Research and Technology Validation reports provided by Fergie and provide feedback by January 23rd.
* Nicolas: Act as the primary proxy/point of contact for any technical questions regarding the IOG research papers.
* Kevin: Organize a separate session to progress the TSC Operational Budget proposal
* Bosko: Reconcile calendars to potentially move the Hard Fork Working Group meeting time to better align with IO's internal node meetings.



| Topic                       | Discussion                                                                                                                                                                              | Notes                                                                                                                                            |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Action Items Review         | Bosko reviewed status of previous actions. Blog post regarding constitution committee size is still open (waiting on Alex).                                                             | Kevin to follow up with Alex on Slack.                                                                                                           |
| Product Committee Alignment | Discussion on aligning the 2030 vision with 2026 goals. A 90-minute joint session is scheduled for next Tuesday.                                                                        | Group decided to delegate a small subset (Neil, Leandro, Kevin, Nicolas, Ryan) to attend rather than the full TSC.                               |
| Chain Incident Report       | The factual report on the recent network incident was finalized Friday (v0.5). Neil expressed "paranoia" and frustration that the Board is requiring legal approval before publication. | Action: Members to keep private PDF copies. Kevin to apply pressure on the Executive/Board for timely release. Working Group is formally closed. |
| Hard Fork Update            | Update on node v10.7 release candidate, which includes Prometheus features for SPOs. Targeting a possible Q1 hard fork.                                                                 | Info action for "Van Rossem" name submitted on-chain. Node RC expected in 2–3 weeks.                                                             |
| Plutus Cost Models          | Kevin confirmed with Ryan (Williams) that cost model settings can be updated ahead of the hard fork event.                                                                              | Parameters to be presented to the Parameter Committee on Jan 15.                                                                                 |
| Parameter K to 1,000        | Ryan presented benefits of increasing K (Nakamoto coefficient, pledge viability). Neil challenged the assumption that it automatically helps struggling small pools.                    | Ryan to provide more detailed arithmetic/math on stake movement for the next meeting.                                                            |
| Min Pool Cost Reduction     | Ryan proposed lowering minPoolCost from 170 to 75 ADA to prevent delegator rewards from being eaten by the "first block tax" as rewards decrease.                                       | Long-term solution: Moving toward SIP-23 (min pool margin) in the Dykstra hard fork (v12).                                                       |
| 2030 Vision & KPIs          | Leandro shared a document criticizing existing KPIs, noting they don't necessarily correspond to sustainability or technical reality.                                                   | Action: Kevin to schedule a small group meeting before next Tuesday to refine the TSC's stance on these metrics.                                 |
| 2025 Research Reports       | Fergie presented end-of-year reports for Foundational Research and Tech Validation. 24 papers were published in 2025 (20% over target).                                                 | Community feedback on reports is open until Jan 23. Nicolas to act as proxy for technical research questions.                                    |
| Security Appointment        | Christian announced that Mike has been onboarded as the Security Incident Response Officer this week.                                                                                   | Mike will take the lead on SecOps and support the Security Council.                                                                              |
| TSC Operational Budget      | Kevin discussed the need for a formal budget to support TSC operations. General support from the Intersect Steering Committee.                                                          | Kevin to organize an outbound meeting to define budget specifics before his upcoming absence.                                                    |
