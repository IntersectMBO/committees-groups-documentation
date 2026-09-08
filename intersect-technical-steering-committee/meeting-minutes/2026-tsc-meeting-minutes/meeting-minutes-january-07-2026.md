# Meeting Minutes January 07, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | No         | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | No         | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Empty Seat        | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ryan Williams



**Recording:** [Technical Steering Committee - 2026/01/07 - Recording](https://drive.google.com/file/d/1I1U2Cec3CTwl1SHGbhkyGDxIzfK6Ez8v/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2026/01/07 - Transcript](https://docs.google.com/document/d/1yh5ASMtPxb8R4rko9OGz8iVLGq70wBL2EUKAZXEwUYA/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2026/01/07 - Chat Transcript](https://drive.google.com/file/d/1JXy8LtsaQazZXHVtqwIUOp2mbCPqwL1C/view?usp=sharing)

## Intros

Duncan: TBD\
Kevin:  Kevin Hammond, TSC chair, Founder at Ensurable Systems\
Leo: Developer@KeyPackt/AnetaV2/GenWealth single pool SPO, CEO LnLlabs, TSC member\
Neil: TSC, Network Params, PNSol Ltd\
Nicolas: Nicolas Biri, TSC voting member, Director of Software Architecture, IOG\
Ryan: Ryan Wiley, TSC voting member, Cybersecurity Penetration Tester.\
Sebastian: Sebastian Nagel, TSC voting member, Technical Architect, nCoding, IOE\
Tex: Terence 'Tex' McCutcheon - Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Liaison

## Agenda 01.07.26

* Actions from the last meeting - Tex
* Chain Incident Partition Working Group Update - Neil/Ryan/Kevin
* Hard Fork Update (van Rossem) - Kevin
* TSC operational budget  - Kevin
* Scheduling Parameter Updates - Alex/Ryan Williams
* 2030 Vision - Kevin
* Joint session with Product Committee
* AOB

## Decisions/Actions

**Decisions**

* Hard Fork Priority: The committee decided not to delay the hard fork for non-essential features; specifically, Node 10.6.2 will likely be the release candidate, while the LSM features in 10.7 will be deferred to a later version (11.1).
* Naming Convention: The committee agreed to move forward with the governance action to officially name the upcoming hard fork the "Max Van Rossem" hard fork.
* Budget Methodology: The group decided to focus first on defining the "what" (headings and priorities) of the operational budget before assigning specific ADA or Dollar values.
* KPI Review Strategy: The committee reached a consensus to scrutinize all KPIs in the 2030 Vision document for technical feasibility and internal consistency, rather than just accepting them as product-level aspirations.

**Actions**

* Kevin: Follow up with Alex to confirm if the blog post/thread regarding the Constitution Committee size was published.
* Bosco (via Kevin): Extend formal invitations to the Product Committee for a joint session to align the 2030 Vision with 2026 goals.
* Ryan Williams: Merge suggested edits from executives into the Chain Partition Incident Report and finalize the document for the board.
* TSC Members: Review the proposed metadata for the "Van Rossem" hard fork naming action and provide feedback by Friday.
* TSC Members: Review the draft TSC Operational Budget and provide asynchronous comments/feedback before the next meeting.
* Ryan (Cerkoryn): Prepare a formal presentation for next week regarding the proposal to increase K to 1,000 and lower the minimum pool cost to 75.
* Kevin & Ryan Williams: Meet to finalize the schedule for parameter updates and coordinate the timing of the various upcoming governance actions.
* All Members: Consider and submit nominations for the Vice Chair position as soon as possible.<br>

| **Topic**                       | **Discussion**                                                                                                                                                        | **Notes**                                                                                                                            |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Previous Action Items           | Terence and Kevin reviewed outstanding items: budget drafting, blog posts regarding committee size, and the vice chair nominations.                                   | Bosco is currently away; he will extend formal invitations to the Product Committee upon his return.                                 |
| Vice Chair Nominations          | Terence emphasized the urgency of appointing a Vice Chair before the March/April election cycle to ensure leadership redundancy.                                      | Kevin encouraged members to consider nominating themselves to provide backup for the Chair position.                                 |
| Chain Partition Report          | The report on the recent incident is finalized but awaiting board feedback before public release. Ryan W noted that suggested edits from executives are being merged. | Key Finding: 500 transactions appeared on the non-preferred chain; 20 remain unaccounted for, but ledger consistency was maintained. |
| Chain Incident Impact           | Neil noted that despite the technical partition, there were no reports of significant user loss or "starving children" scenarios.                                     | The system successfully "snapped back" to the preferred chain. Neil suggested highlighting this resilience in communications.        |
| Hard Fork Update (Node 10.6.2)  | A preview version of Node 10.6.2 is expected within two weeks. This version will likely be the release candidate for Protocol Version 11 (Van Rosenom).               | Feature-complete for the hard fork. Integration of final changes is the current focus.                                               |
| Node Version 10.7 & LSM         | Development on 10.7 (including Log-Structured Merge-Tree support for out-of-memory storage) is ongoing but not essential for the hard fork.                           | 10.7 may become a Version 11.1 release to avoid delaying the hard fork for non-essential features.                                   |
| Incentives & Parameter Changes  | Ryan C proposed increasing K to 1,000 and lowering the minimum cost to 75 to account for decreased block rewards.                                                     | Discussion deferred to next week’s agenda and the Parameter Committee meeting on January 15.                                         |
| Governance Action Coordination  | Ryan C highlighted the technical requirement to reference the hash of the previous successful parameter change to avoid governance action failure.                    | Coordination is required between the Incentives Working Group and the Parameters Committee.                                          |
| TSC Operational Budget          | Kevin circulated a draft budget based on April 2025 headings. The focus is on technical outreach and supporting community members.                                    | Members requested one week for asynchronous review. No specific numbers (ADA/USD) have been attached yet.                            |
| Hard Fork Naming Action         | Ryan W is submitting a governance action this week to name the next hard fork after Max Van Rosenom.                                                                  | Metadata for the action is being shared with the group for immediate feedback by Friday.                                             |
| 2030 Vision & KPIs              | Neil and Ryan C criticized the current KPIs as being "top-down" and disconnected from specific problem statements or technical realities.                             | Neil argued that KPIs must have consequences for failure to be meaningful; Ryan C warned against "throwing everything at the wall."  |
| Committee Remit & KPIs          | Nicolas and Sebastian discussed whether the TSC should judge product goals (like TVL) or strictly focus on technical feasibility (like 1-second finality).            | Action: The TSC will scrutinize all KPIs for technical consistency and potential conflicting side effects.                           |
| Product Committee Collaboration | Kevin and Bosco are coordinating a joint meeting with the Product Committee to align the 2030 vision with 2026 goals.                                                 | Timing is dependent on Sam’s return from the Orthodox Christmas holiday.                                                             |
