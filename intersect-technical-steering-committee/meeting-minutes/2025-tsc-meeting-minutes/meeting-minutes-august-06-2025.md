# Meeting Minutes August 06, 2025

## Attendees:&#x20;

| Name                     | Attendance | Role        | Voting Seat (Y/N) |
| ------------------------ | ---------- | ----------- | ----------------- |
| Kevin Hammond            | Yes        | Chair       | Y                 |
| Adam Dean                | No         | Vice Chair  | Y                 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 |
| Markus Gufler            | No         | Member/Seat | N                 |
| Nicolas Biri             | No         | Member/Seat | Y                 |
| Duncan Coutts            | No         | Member/Seat | Y                 |
| Jonathan Kelly           | No         | Member/Seat | Y                 |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 |
| Benjamin Hart            | Yes        | Member/Seat | Y                 |
| Neil Davies              | Yes        | Member/Seat | Y                 |
| Alexander Moser          | No         | Member/Seat | Y                 |

Community/Other Attendees

* Christian Taylor
* Jethro Adebisi



**Recording:** [Technical Steering Committee - 2025/08/06 08:29 CDT - Recording](https://drive.google.com/file/d/1tpYW5CtJVkAe8v8GRmo0VG_hG-M__25f/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/08/06 08:29 CDT - Transcript](https://docs.google.com/document/d/1SSdnnkhNrMFmry5IC0JK5zNbh98QkBRahMkK8ME21Xc/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2027/08/06 - Chat Transcript](https://drive.google.com/file/d/1Wa2jDFsNU9vPm0S5FosGA2YHxztC3lzN/view?usp=sharing)

## Intros

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

## Agenda 8.06.25

* VRF tiebreaker carried forward
* Intersect repo creation policy and process
* Product Committee vision document
* Parameter Committee Update
* Security Council Update

## Decisions/Actions

Decisions:

* The group decided to postpone the VRF tiebreaker discussion until the next meeting due to a lack of quorum.
* The review of the Product Committee vision document was also postponed.
* The group agreed to use a lazy consensus approach, utilizing reactions on the channel, to approve the tweet about the Plutus memory limits change.
* It was decided that a fire drill of the disaster recovery process would be executed on SanchoNet to test CIP 135.

Actions:

* **Terence** will continue to work on the GitHub backend for the new repo creation policy and is open to moving to an issue-based workflow in the future. He will also post the tweet about the Plutus memory limit increase.
* **Kevin** will engage with GovPool to raise awareness of the Plutus memory limit change proposal.
* The **Communications team** will be involved in the disaster recovery fire drill to manage public perception.
* **Sebastian** will continue to run the Layer 2 Working Group, and his team will handle the next meeting.
* **Terence** will check for new video uploads from the working groups and post them.

| Topic                             | Discussion                                                                                                                                                                                                                                                                                                         | Notes                                                                                                                                                    |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Meeting Start and Attendance      | The meeting was called to order with Kevin, Ben, and Neil present as voting members. Jethro and Terence from Intersect were also in attendance. Jethro joined as a community member, while Terence served as the secretary. It was noted that the meeting was not quorate due to the low number of voting members. | Attendance: Kevin, Ben, Neil, Jethro, Terence, Sebastian, Christian                                                                                      |
| Agenda Review                     | Kevin reviewed the agenda items: VRF tiebreaker, Intersect repo creation policy, product committee vision document, parameter committee update, and security council update. He stated that due to the lack of a quorum, the meeting would be brief and focus on any urgent issues.                                | The agenda was discussed, but no decisions could be made due to low attendance.                                                                          |
| VRF Tiebreaker                    | The VRF tiebreaker was carried over from the last meeting. The group agreed a detailed technical discussion was needed and it would be best to postpone until Adam, who proposed the item, was present.                                                                                                            | This topic was postponed to a future meeting with a larger group.                                                                                        |
| Intersect Repo Creation Policy    | Terence provided an update on the new policy, stating that Intersect had restricted repo creation to staff members to control growth. They are using a form for project support, and he is working on the GitHub backend.                                                                                          | Ben and Neil suggested that using GitHub issues would be a more streamlined approach than a web form.                                                    |
| Community Involvement             | The group discussed the extent of community involvement in the new policy. Neil suggested the community should be informed, but not necessarily consulted, to avoid unnecessary delays.                                                                                                                            | The TSC will be informed of new repo requests, and staff can bring an issue to the committee if needed.                                                  |
| Product Committee Vision Document | The group was reminded to review the latest version of the 2030 vision document from Sam.                                                                                                                                                                                                                          | The item was briefly mentioned and postponed until the next meeting.                                                                                     |
| Parameter Committee Update        | Kevin updated the group on proposed changes to Plutus memory limits. The Plutus team is planning a 25% increase, to be rolled out in two stages to avoid tripping a guardrail. A three-month notice period is required for any governance-critical parameter changes.                                              | The group discussed the motivations and implications of this change, including performance impacts and the use of the "golden machine" for benchmarking. |
| Security Council Update           | Kevin announced that the Security Council would meet next week. He discussed plans to conduct a fire drill of the disaster recovery process on SanchoNet to test SIP 135 and train SBOs.                                                                                                                           | Two scenarios for the fire drill were proposed: a network stall due to a lack of blocks and a bad block being injected.                                  |
| Layer 2 Working Group             | Sebastian updated the group on the Layer 2 working group, noting recent discussions about interoperability, particularly for payments. The next meeting will be hosted by others while Sebastian is away.                                                                                                          | The working group's progress was noted. The idea of tweeting about its activities to inform the community was also raised.                               |
| Meeting Close                     | With no other topics to cover and the main items postponed, Kevin ended the meeting.                                                                                                                                                                                                                               | The meeting adjourned with the plan to reconvene when everyone returned from their travels.                                                              |
