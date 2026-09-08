# Meeting Minutes August 27, 2025

## Attendees:

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | Yes        | Chair       | Y                 | October 2025 |
| Adam Dean                | No         | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Lorenzo Bruno            | No         | Secretary   | N                 | N/A          |
| Markus Gufler            | No         | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | Yes        | Member/Seat | Y                 | October 2025 |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | Yes        | Member/Seat | Y                 | April 2026   |

Community/Other Attendees

* Christian Taylor
* Ken-Erik Olmheim



**Recording:** [Technical Steering Committee - 2025/08/27 - Recording](https://drive.google.com/file/d/1QnyhXTvMS-tPdGSs2QkBMu9Jp0U4G3eB/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/08/27 - Transcript](https://docs.google.com/document/d/1Cy0Z4EidI41CdgrHza0sKfRY97BZ31Wfs9sR6-xnkrc/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/08/27 - Chat Transcript](https://drive.google.com/file/d/1WfXU9FrRY88H3DLb4mtVuPuO4m_iuZpY/view?usp=sharing)

## Intros

**Adam:** OSC, TSC, CIP Editor, DripDropz LLC\
**Alex:** TBD\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:** TBD\
**Lorenzo:** TBD\
**Markus:** TBD\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TBD\
**Sebastian:** TBD\
**Tex:** Open Source Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison

## Agenda 8.27.25

* VRF Tiebreaker (Neil)
* Hard Fork WG Reactivation (Kevin)
* Deposits for Parameter Updates (Alex)
* Update on “Fire Drill” (Kevin)&#x20;

## Decisions/Actions

#### Decisions

* **VRF Tiebreaker:** The committee decided to reject the current pull request, concluding that the change should not be treated as a bug fix. Instead, any proposed changes to the VRF tiebreaker must go through a more formal process, starting with a Cardano Problem Statement (CPS).
* **Hard Fork Working Group:** The group approved the reactivation of the hard fork working group to formally begin planning for the next hard fork.
* **Community Proposal Funding:** A decision was made to recommend that Intersect use its budget to cover the 100,000 ADA deposit for "sensible" community-submitted governance actions.
* **Disaster Preparedness:** A disaster recovery fire drill was formally approved to test the network's emergency procedures on the Sancho Testnet.

#### Actions

* **Jonathan** will inform the working group that submitted the VRF tiebreaker pull request of the TSC's decision. Duncan will attend their next meeting to offer further guidance.
* **Kevin** and **Terence** will take the lead in reinstating the hard fork working group.
* **Kevin** will present the recommendation for funding community proposals to the Intersect Steering Committee and the Budget Committee. He will also seek a TSC volunteer to attend the meeting in his absence.
* **Kevin**, **Jonathan**, and **Alex** will organize and participate in the fire drill. Kevin will also share the planning document for review and work with the communications team to manage public messaging.

| Topic                                | Discussion                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Notes                                                                                                                                                                                                                                                                                                        |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| VRF Tiebreaker & Protocol Changes    | Neil raises a concern about a recent pull request (PR) regarding the VRF tiebreaker, suggesting it could have economic and security implications. He wants to discuss a formal process for vetting such changes. Jonathan shares links to the PR and related articles, noting that the community is upset about a change being made without a formal SIP (Cardano Improvement Proposal). He adds that the core team saw the change as a bug fix for a bias toward smaller pools. | Neil suggests a need for a more formal process to manage contentious changes. He notes that the developer team was uncomfortable with the decision and referred it to the TSC, which is a good sign. The group agrees that the developers should be thanked and the PR marked to prevent an immediate merge. |
| Proposed Solution & Next Steps       | Jonathan reiterates the need for a CIP. Duncan suggests a Cardano Problem Statement (CPS) instead, arguing that it's an "ad hoc" change and that any deliberate bias should be a tunable, deliberate feature. Nicolas agrees, stating a CPS would allow for a proper discussion on revenue distribution.                                                                                                                                                                         | The group agrees to recommend that the developers create a CPS to first get consensus on whether a problem actually exists, and then work toward a deliberate, tunable solution if needed. Jonathan will communicate this feedback to the working group that submitted the PR.                               |
| Hard Fork Working Group Reactivation | Kevin proposes reactivating the hard fork working group to determine the scope for the next hard fork, expected in November. The goal is to start small and agree on the scope with the developer teams.                                                                                                                                                                                                                                                                         | The group agrees to reactivate the working group. Kevin will work with Terence and others to get it organized and will call on people to be involved as needed.                                                                                                                                              |
| Deposits for Parameter Updates       | Alex raises a question from the parameter committee about Intersect sponsoring the 100,000 ADA deposit for governance actions for community members who cannot afford it. This would serve as a potential solution until a crowdfunding mechanism is available. Neil, Kevin, and Ben discuss the details, noting the deposit is always returned, and the cost is the opportunity to use one of the five "slots" earmarked in the budget for such concurrent actions.             | The group agrees to recommend that Intersect use its existing budget to cover the deposits for "sensible" community proposals. The parameter working group and TSC will act as quality control to filter these proposals. The scope will be limited to simple protocol updates.                              |
| Budget Committee Recommendation      | The discussion shifts to the process of formalizing the recommendation for the budget committee. Terence expresses concern that the TSC might be overstepping its authority by trying to mandate how Intersect uses its funds. Kevin clarifies that it's a recommendation, not a mandate.                                                                                                                                                                                        | The TSC agrees to formally recommend the proposal to the budget committee. Kevin will raise the issue with the Intersect Steering Committee (ISC) and the budget committee. He will also seek a volunteer to attend the next meeting in his absence.                                                         |
| VRF Tiebreaker Update                | Jonathan reports back on his conversation with the working group that proposed the VRF tiebreaker change. He says they are frustrated but willing to write a problem statement. They will not make a formal statement until their working group meeting tomorrow. Kevin asks Jonathan to relay the message that the concern is with potential security implications, not a rejection of the idea itself.                                                                         | Jonathan will pass along the feedback and let the working group know that the meeting recording will be available. Duncan volunteers to join their incentives working group meeting.                                                                                                                         |
| Disaster Recovery Fire Drill         | Kevin provides an update on the proposed disaster recovery fire drill. The goal is to test the procedures outlined in SIP 135 on Sanchonet to ensure they work as intended in case of a real disaster. The plan involves engineering a disaster on the testnet and recovering from it.                                                                                                                                                                                           | Jonathan confirms he will be part of the fire drill. Alex and another TSC member will also be involved. They will work with the communications team to manage messaging to avoid negative publicity. Kevin will share the document with the group for comments and feedback.                                 |
| Conclusion & Adjournment             | The meeting concludes with a final thank you to everyone. Kevin announces that Adam will chair the next meeting in his absence and that he will see everyone in two weeks.                                                                                                                                                                                                                                                                                                       | The meeting is adjourned.                                                                                                                                                                                                                                                                                    |
