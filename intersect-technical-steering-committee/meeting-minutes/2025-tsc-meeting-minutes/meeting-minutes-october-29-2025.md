# Meeting Minutes October 29, 2025

## Attendees:

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | No         | Chair       | Y                 | October 2025 |
| Adam Dean                | Yes        | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Markus Gufler            | No         | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | No         | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | Yes        | Member/Seat | Y                 | October 2025 |
| Neil Davies              | No         | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | No         | Member/Seat | Y                 | April 2026   |

**Community/Other Attendees**

* Christian Taylor



**Recording:** [Technical Steering Committee - 2025/10/29 - Recording](https://drive.google.com/file/d/1rV8w6wrzZMC-wxuaYE2mxc1GHIL7aVRO/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/10/29 - Transcript](https://docs.google.com/document/d/1_qhHU-fJoiPWS_ycGc0yCJXe4Fz5sny3IrCc2uVc6Qs/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/10/29 - Chat Transcript](https://drive.google.com/file/d/1eK5Yfj5biBAB8sFUjixg-62zqmfmDgH5/view?usp=sharing)

## Intros

**Adam:** OSC, TSC, CIP Editor, DripDropz LLC\
**Alex:** Head of Infrastructure, Cardano Foundation, TSC member, Parameter Committee\
co-chair, CF Drep committee voting member,\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:**  TSC chair, Hylomorph Solutions Ltd\
**Markus:** TSC voting member, CF employee, SPO\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TSC member, IOG\
**Sebastian:** Software Engineer/Architect, nCoding GmbH, IOE, TSC member\
**Tex:** OS Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison

## Agenda 10.29.25

* Cardano Reward Sharing Scheme v2 Ballot - Johnny
* Hard Fork Scope Discussion - Tex
* Protocol Parameter Update - Alex
* Cardano Vision: Enabling Technology Pillar input - Kevin
* Committee Election Update - Tex/Simo

## Decisions/Actions

**Decisions**

* **Intra-Era Hard Fork Working Group Reformation:** The motion to reinstitute the Hard Fork Working Group with the intent to work towards the Version 11 intra-era hard fork, based on the circulated scope document (with the caveat about the first sentence's wording) was passed unanimously by the present members and one asynchronous vote.
* **TSC Position on Reward Sharing Proposals:** The committee agreed that its formal assessment of the Community Reward Sharing Schema Update (including SIP 50, SIP 163, and SIP 23) should focus solely on the technical viability and feasibility of the proposals, not on recommending for or against their adoption.
* **Election Term for TSC Chair:** There was consensus, aligning with the current design, that the Chair role should ideally cycle with each election term ($\approx 6$ months), with the recommendation (but not requirement) that the Chair come from the newly elected cohort.

**Actions**

* **TSC Review of Reward Sharing Schema:** All TSC members (present and non-present) are to review the associated document detailing the Community Reward Sharing Schema update (SIPs 50, 163, 23).
* **Provide Technical Feedback:** Members should provide their high-level technical analysis and raise any technical concerns in the internal Slack or Discord channels.
* **Coordinate Response:** The TSC will coordinate a formal, technical-only response to the authors of the Reward Sharing proposals in approximately one to two weeks.
* **Hard Fork Working Group Formation:** Terence will work with Jess, Bosco, and Ryan (from Intersect) to get the Hard Fork Working Group up and running.
* **Onboarding Slide Deck for New TSC Members:** A request was made for a volunteer to take leadership in creating or adjusting an onboarding slide deck for new Technical Steering Committee members.
* **Review New Project Requests:** Christian will submit three new project requests (Typed Protocols, IOSIM, and SERDOC) from the Ouroboros network team for the TSC's review and Intersect's ownership. Christian will confirm with IE that they will be the maintainers of these projects.

| Topic                                         | Discussion                                                                                                                                                                                                                                               | Notes                                                                                                                                                                                                                      |
| --------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Attendance & Absences                         | Adam noted several members were missing, including Kevin who was at a conference, and Sebastian, who was on a separate call. Nicolas confirmed only Given from the TSC was attending the UPLC workshop in Edinburgh.                                     | Need to track reasons for multiple absences. Sebastian expected to join in ≈30 minutes (though may have been missed).                                                                                                      |
| Community Reward Sharing Schema Update        | Johnny introduced the proposal from a working group to update parameters for better reward distribution, focusing on five points that require an Ecclesia vote. The goal is for the TSC to assess the technical viability and safety of the proposal.    | Action Item: TSC members to review the associated document and provide high-level technical analysis and feedback.                                                                                                         |
| CIP 50 Adoption (Parameter L)                 | Discussed adopting SIP 50, which introduces a parameter 'L' to make pledge more significant for saturation. Duncan asked if a proper game theory analysis had been performed.                                                                            | Adam and Johnny raised concerns that this could put an upper bound on staked ADA and that analysis on the changes to the system equilibrium is needed.                                                                     |
| CIP 163 Adoption (Timebinding Delegation)     | This new SIP involves time-binding delegation and a delegator inactivity setting to drop delegation from a Stake Pool Operator (SPO) after a certain number of epochs if the wallet is inactive.                                                         | To be included in the TSC's technical viability assessment.                                                                                                                                                                |
| CIP 23 Adoption (Min Margin)                  | The last point to be voted on is adopting SIP 23 to introduce a minimum margin alongside or instead of the minimum pool cost.                                                                                                                            | To be included in the TSC's technical viability assessment.                                                                                                                                                                |
| TSC Feedback on Reward Sharing Schema         | Adam suggested the TSC's response should only address technical feasibility (Is it possible?) rather than recommending for or against the proposals. Johnny felt the parameters were technically introducible, but had doubts about their effectiveness. | TSC to coordinate a response in Slack/Discord within one to two weeks after review.                                                                                                                                        |
| Hard Fork Working Group Scope                 | Terence introduced the draft scope for an intra-era hard fork targeting Q2 2026 to update Plutus and Ledger, noting the need to reform the working group 6 months prior.                                                                                 | The initial wording of the proposal mentioning "contractual commitments to Intersect milestones" was deemed inappropriate and confusing for a community-facing justification.                                              |
| Intra-Era Hard Fork Scope Vote                | The request was to approve the reformation of the working group with the proposed scope (after adjusting the weird initial sentence). Adam, Johnny, Terence, Duncan, Nicolas, and Ben present members, plus Kevin's async vote, all gave a thumbs up.    | Motion Passed to reinstitute the Hard Fork Working Group to work towards a Version 11 intra-era hard fork based on the circulated scope.                                                                                   |
| Hard Fork Working Group Next Steps            | Terence will work with Jess, Bosco, and Ryan (from Intersect) to begin forming the group.                                                                                                                                                                | <p><br></p>                                                                                                                                                                                                                |
| TSC Committee Elections Update                | Terence reported that voting is open for the seven candidates until next Friday, November 7th, at noon UTC.                                                                                                                                              | An onboarding slide deck for new members is needed; Terence requested help to create or lead this effort.                                                                                                                  |
| Chair/Vice-Chair Discussion                   | Terence provided an update on the ongoing discussion, suggesting a new chair be elected every six-month election term to split responsibilities and maintain consistency. The design aims to elect the chair from the new cohort.                        | Ben suggested the chair should ideally come from the newly elected batch for institutional memory, but not as a strict requirement over democratic choice. Adam and Ben agreed it should be encouraged, not mandatory.     |
| New Project Requests (Ouroboros Network Team) | Christian gave an FYI that three new project requests are coming in from the Ouroboros network team (Type Protocols, IOSIM, and SERO) that complement their work. Duncan noted he will recuse himself as colleagues may apply for retainer roles.        | The request is to have Intersect own and maintain these packages as part of the core Haskell node. Christian will confirm Intersect will be the maintainer to avoid becoming a "dumping ground" for unmaintained projects. |
| Meeting Adjourned                             | Adam adjourned the meeting, giving everyone back ≈30 minutes.                                                                                                                                                                                            | Next meeting to be held next week.                                                                                                                                                                                         |
