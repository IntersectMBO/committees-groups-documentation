# Meeting Minutes July 30, 2025

## Attendees:&#x20;

| Name                     | Attendance | Role        | Voting Seat (Y/N) |
| ------------------------ | ---------- | ----------- | ----------------- |
| Kevin Hammond            | Yes        | Chair       | Y                 |
| Adam Dean                | Yes        | Vice Chair  | Y                 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 |
| Lorenzo Bruno            | Yes        | Secretary   | N                 |
| Markus Gufler            | Yes        | Member/Seat | Y                 |
| Nicolas Biri             | No         | Member/Seat | Y                 |
| Duncan Coutts            | Yes        | Member/Seat | Y                 |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 |
| Sebastian Nagel          | No         | Member/Seat | Y                 |
| Benjamin Hart            | Yes        | Member/Seat | Y                 |
| Neil Davies              | Yes        | Member/Seat | Y                 |
| Alexander Moser          | Yes        | Member/Seat | Y                 |

Community/Other Attendees

* Christian Taylor

**Recording:** [Technical Steering Committee - 2025/07/30 - Recording](https://drive.google.com/file/d/1ZwZrRNbpg3koB8E-7C8A7q6eq6fXUee6/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/07/30 - Transcript](https://docs.google.com/document/d/1NeLwaJpMuKnXNQiKyMBWFkpMqTz_LmBRELfAsboZ37c/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2027/07/30 - Chat Transcript](https://drive.google.com/file/d/1EYFnoI2OCRpyPc_AeZIi33JEHAxuf0eO/view?usp=sharing)

Intros\
**Adam:** OSC, TSC, CIP Editor, DripDropz LLC\
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
**Tex:** Terence 'Tex' McCutcheon: Open Source Program Manager (Intersect), GMC/MCC/OSC\
Secretary, Committee Liaison

## Agenda 7.30.25

* Updates from the Past week
* VRF Tiebreaker
* Product Committee vision draft - [https://github.com/IntersectMBO/product-website/pull/18/files](https://github.com/IntersectMBO/product-website/pull/18/files)
* UPLC\_CAPE Repo&#x20;

## Decisions/Actions

Decisions:

* VRF Tiebreaker: Added to next week's agenda for further discussion.
* Repository Creation Permissions (Temporary): A motion was passed to temporarily revoke all permissions for non-Intersect staff to create private or public repositories under the Intersect organization. This is a temporary control measure until a new policy is drafted and adopted.

Actions:

* Adam: Review the "Ouroboros Phalanx" proposal as a CIP editor and ask the author(s) if there is interest to present a summary to the Technical Steering Committee (TSC) at a future meeting.
* Terence:
  * Start working on revoking GitHub permissions so that nobody not part of an Intersect staff group can create any repositories under Intersect.
  * Develop a draft policy for repository creation for presentation to the TSC and Open Source Committee (OSC) at their next meeting.
* All Committee Members: Review the updated "Product Committee Vision" and "Strategy" documents and provide comments directly on GitHub.
* Markus: Share his comments on the proposed TSC remit with the elected committee members to formulate a unified response.
* TSC Members (Duncan, Markus, and others attending Rare Evo): Coordinate with Lorenzo and Terence regarding booth presence and potential presentations at Rare Evo.
* Jonathan: Continue working on the application form and assessment criteria for the Maintainer Retainer Program. He will also gather a list of core repositories that will have new maintainers and aim to set up consultancy meetings with existing maintainers.
* Jonathan & Adam: Take feedback on the Maintainer Retainer Program back to the OSC for scaffolding.
* Jonathan: Share the document with initial application questions for the Maintainer Retainer Program with interested parties.

| Topic                                  | Discussion                                                                                                                                                                                                                                                                                                                                                                    | Notes                                                                                                                                                                                                                                                                                                                                     |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Call to Order & Roll Call              | Adam called the meeting to order. Neil confirmed six attendees were present, meeting quorum.                                                                                                                                                                                                                                                                                  | Adam chaired in Kevin's absence.                                                                                                                                                                                                                                                                                                          |
| Review of Agenda & Carryover Items     | Adam inquired about the current agenda and any unaddressed carryover items from the previous week. Terence was unaware of explicit items but mentioned ongoing work on the "remittant."                                                                                                                                                                                       | <p><br></p>                                                                                                                                                                                                                                                                                                                               |
| VRF Tiebreaker / Unfairness Discussion | Jonathan provided context on a past "bug" where smaller delegated SPOs were favored in a height battle. This was corrected for fairness, but the community pushed back, desiring to support smaller pools. Duncan and Neil discussed the concept of "designer fairness" versus "mathematically fair" and the need to quantify the difference.                                 | This topic was added to next week's agenda: "VRF Tiebreakers and/or Unfairness."                                                                                                                                                                                                                                                          |
| Ouroboros Phalanx Proposal             | Adam mentioned the "Oraboros Phalanx" proposal in the CIP directory, aimed at addressing anti-grinding and other grinding attacks. Neil asked how the committee should deal with this, suggesting delegating a couple of members to review the paper and present it. Duncan inquired if it was from researchers and if it involved a verifiable delay function.               | Adam will review the proposal as a CIP editor and ask the author(s) if there is interest to present a summary to the TSC at a future meeting.                                                                                                                                                                                             |
| Plutus Team's New Private Repositories | Adam raised a concern about the Plutus team creating new private repositories under the Intersect MBO GitHub organization without proper process. Terence explained that individual contributors can create private repos, but only admins can make them public. Christian highlighted the administrative cost and lifecycle management for all repositories under Intersect. | Jonathan proposed a motion to temporarily revoke the ability for non-Intersect staff to create new repositories (private or public) until a new policy is adopted. Terence will draft this policy for review by the TSC and OSC. The motion passed.                                                                                       |
| Product Committee Vision 2030 Roadmap  | Lorenzo presented an update on the Product Committee's vision and strategy documents, which have been streamlined and divided into a concise vision section and a longer strategy part. He requested comments directly on GitHub and mentioned an upcoming workshop.                                                                                                          | Adam found the streamlined document more palatable. The committee will review the updated documents and provide feedback.                                                                                                                                                                                                                 |
| TSC Remit Review                       | Lorenzo asked if the committee had reviewed the proposed TSC remit. Markus stated he had reviewed it and suggested that comments should come from the elected committee members as a whole, not individually.                                                                                                                                                                 | Adam and Markus indicated they likely won't run for re-election. The committee will discuss the proposed remit and aim to provide a unified response.                                                                                                                                                                                     |
| Rare Evo Presence                      | Lorenzo inquired about TSC members attending Rare Evo to make presentations or be available at the Intersect booth. Duncan and Markus confirmed their attendance.                                                                                                                                                                                                             | The attendees will coordinate with Lorenzo and Terence regarding booth presence and potential presentations.                                                                                                                                                                                                                              |
| Maintainer Retainer Program            | Jonathan brought up the ongoing maintainer retainer program from the Open Source Committee, seeking sentiment and potential overlap with the TSC. Neil was unfamiliar with the program and asked for details on its intention and interaction with TSC committees.                                                                                                            | Adam explained the program's intent: to stipend technically competent individuals to triage issues, identify good first issues, and approve pull requests, acting as independent community members. The TSC will be consulted on the process of appointing these maintainers. Christian outlined risk mitigation and the program's goals. |
| Meeting Adjournment                    | Adam moved to adjourn the meeting as there was no further business to discuss.                                                                                                                                                                                                                                                                                                | The meeting was adjourned.                                                                                                                                                                                                                                                                                                                |
