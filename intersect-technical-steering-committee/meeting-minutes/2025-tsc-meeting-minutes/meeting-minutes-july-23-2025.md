# Meeting Minutes July 23, 2025

## Attendees:&#x20;

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Election Cycle |
| ------------------------ | ---------- | ----------- | ----------------- | -------------- |
| Kevin Hammond            | Yes        | Chair       | Y                 | October 2025   |
| Adam Dean                | Yes        | Vice Chair  | Y                 | October 2025   |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A            |
| Lorenzo Bruno            | Yes        | Secretary   | N                 | N/A            |
| Markus Gufler            | Yes        | Member/Seat | N                 | October 2025   |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026     |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026     |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025   |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026     |
| Benjamin Hart            | Yes        | Member/Seat | Y                 | October 2025   |
| Neil Davies              | No         | Member/Seat | Y                 | April 2026     |
| Alexander Moser          | No         | Member/Seat | Y                 | April 2026     |

Community/Other Attendees

* Alex Seregin
* Christian Taylor
* Duncan Soutar
* Kris Bennett

**Recording:** [Technical Steering Committee - 2025/07/23 - Recording](https://drive.google.com/file/d/12emDAcfIC0zxGUSj_lqhuAHMQuB7Vzyw/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/07/23 08:27 CDT - Transcript](https://docs.google.com/document/d/1JuLU4A9h_X86fZT3-u6LmO-KDPV50LB2b-PPfkwclF0/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2027/07/23 - Chat Transcript](https://drive.google.com/file/d/1qN1l2G-xm2rnmqJe61HDv4eKSy_uCg9r/view?usp=sharing)

## Intros

TBD

## Agenda 7.23.25

* Node 10.5.1 released
* TSC remit
* 2030 vision - initial discussion/feedback&#x20;
* TSC evaluation criteria published for DReps to use (tweet etc)
* Any further discussion of contrcontracts/milestones/deliverables - Markus’s points
* Plutus maxExecutionUnits Parameter Update tweet
* Intersect Updates
* Update from Security Council - Charles Morgan has left IOG; plan for Disaster Recovery Fire Drill&#x20;

## Decisions/Actions

#### Decisions

* **Motion Passed:** Deliverables for Fund Withdrawal The TSC voted to recommend that DREPs should not vote to withdraw funds for technical development budgets without deliverables being available for their review and approval. This motion passed with 6 votes for, 0 against, and 2 abstentions.

#### Actions

* **Follow Up on Milestone/Deliverable Transparency:** Kevin will set up a meeting with Jack Briggs from the ISC to discuss the issues of incomplete treasury withdrawals and learn lessons for future budget rounds.
* **Formulate DREP Guidance:** The TSC will work on formulating general guidance for DREPs regarding the importance of deliverables when voting on proposals, rather than targeting individual proposals.
* **Postpone TSC Remit Discussion:** The in-depth discussion about the TSC's remit has been postponed.
* **Schedule 2030 Vision Discussion:** Kevin will organize an out-of-band meeting with the product committee (Sam and others) and interested TSC members to have a detailed discussion about the 2030 vision.
* **Publish Parameter Update Tweet:** An async request will be made to Tex to publish a Twitter post about the protocol parameter update, including a link to the Cardano forum post for further context.
* **Reconsider 90-Day Notification Guardrail:** The issue of the 90-day notification period for protocol parameter changes will be passed back to the parameter committee for reconsideration, potentially with input from security researchers.
* **Identify IOG Security Council Representative:** Nicolas will follow up with Christian regarding the recommendation for a new IOG representative on the Security Council.
* **Plan Disaster Recovery Plan (SIP 135) Fire Drill:** Kevin will link up with Christian and Nick to prepare for a fire drill of SIP 135 (Disaster Recovery Plan), aiming to coordinate with SPOs next week and run the first drill around September on SanchoNet. Johnny offered to assist with writing guidance documents.
* **Synthesize Minutes for Intersect Update:** Kevin will discuss with Tex and Christian how to synthesize a short form of the meeting minutes and extract important actions to be passed on via Intersect's new online update mechanism.

| Topic                                       | Discussion                                                                                                                                                                                                                                                                                                                                                                             | Notes                                                                                                                                                                                 |
| ------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Call to Order & Quorum                      | Kevin called the meeting to order. Kevin clarified that the quorum is six, not five plus the chair, as the chair can be elected.                                                                                                                                                                                                                                                       | Quorum was met.                                                                                                                                                                       |
| Agenda Review                               | Kevin pasted the proposed agenda into the chat. Alex, as a guest, had no specific items to add. Kevin asked TSC members for any additions or prioritization.                                                                                                                                                                                                                           | Proposed agenda pinned in chat.                                                                                                                                                       |
| Milestones & Treasury Withdrawals           | Johnny raised an action item from the previous week regarding linking milestones/information to Treasury withdrawals. He proposed a motion to communicate to the board to link documents for treasury withdrawals so DREPs know what milestones have been drafted. Kevin confirmed the incompleteness of treasury withdrawals without milestones.                                      | Motion proposed by Johnny: Communicate to the board to create linked documents for treasury withdrawals to expose milestones to DREPs.                                                |
| Tooling for Milestones                      | Kevin asked Adam about tooling for exposing milestones. Adam clarified that Zerates is working on a dashboard, not him. Lorenzo shared a link to a blog post about the platform and confirmed Zerates is building a dashboard similar to the CAT's milestone module, displaying payments and details.                                                                                  | Zerates is developing a dashboard for milestones. Link to blog post shared in chat.                                                                                                   |
| Availability of Draft Contracts             | Johnny inquired if draft milestones/contracts are available through the tooling for voting. Lorenzo explained the tooling reads from smart contracts, and as wet (legal) contracts are off-chain, the tooling cannot present drafts pending approval.                                                                                                                                  | Tooling reads from smart contracts; cannot display draft off-chain contracts.                                                                                                         |
| Concerns on Rushing Withdrawals             | Kevin expressed concern about treasury withdrawals being pushed without agreed-upon milestones and deliverables, leading to vague proposals and significant funding without detail. Adam confirmed that funds would go to a holding address, with metadata accompanying movement to project-specific smart contracts once milestones are ready, but this is after treasury withdrawal. | Process relies on trust that Intersect will properly administer contracts.                                                                                                            |
| TSC Remit Discussion                        | Nicolas questioned if the discussion on milestones falls within the TSC's remit. Johnny argued that DREPs voting on funds needs this information. Kevin stated that technical direction and delivery fall under the TSC.                                                                                                                                                               | Discussion on whether milestone concerns are within TSC scope.                                                                                                                        |
| Motion on Deliverables                      | Adam proposed a motion: "The TSC recommends that DREPs should not vote to withdraw funds for technical development budgets without milestones being available for their review and approval." Duncan suggested changing "milestones" to "deliverables" or "deliverables and preferably milestones." Adam agreed to "deliverables." Johnny seconded the amended motion.                 | Amended Motion: The TSC recommends that DREPs should not vote to withdraw funds for technical development budgets without deliverables being available for their review and approval. |
| Vote on Motion                              | The motion was put to a vote.                                                                                                                                                                                                                                                                                                                                                          | Motion Passed: 6 for, 0 against, 2 abstentions.                                                                                                                                       |
| Next Steps for Deliverables                 | Kevin raised the issues with the ISC, and Jack Briggs offered to speak with TSC members. Kevin suggested setting up a session to learn lessons for future budget rounds. Lorenzo suggested the TSC could ask specific questions about proposals to help DREPs. Johnny preferred broad guidance rather than targeting individual proposals.                                             | Kevin to set up meeting with Jack Briggs. TSC can formulate general guidance for DREPs.                                                                                               |
| TSC Remit Re-evaluation                     | Adam suggested postponing the TSC remit discussion to focus on more productive items like protocol parameter changes. Kevin noted the remit needs to be agreed upon before elections.                                                                                                                                                                                                  | Postponed discussion on TSC remit.                                                                                                                                                    |
| 2030 Vision                                 | Kevin suggested taking the detailed discussion on the 2030 vision out of band, proposing a meeting with the product committee (Sam and others) and interested TSC members.                                                                                                                                                                                                             | Out-of-band meeting to discuss 2030 vision.                                                                                                                                           |
| TSC Evaluation Criteria & Tweet             | The TSC reviewed and updated evaluation criteria from April, publishing a tweet about them for DREPs. Johnny clarified the tweet emphasizes these are optional guidelines, not evaluations.                                                                                                                                                                                            | Tweet published regarding updated TSC evaluation criteria for DREPs. No immediate reaction observed.                                                                                  |
| Protocol Parameter Update                   | Sebastian reminded Kevin about a pending tweet regarding the protocol parameter update. Kevin confirmed the Cardano forum post has already gone live, starting the 90-day notification period before an on-chain submission. Johnny suggested linking the forum post in the tweet.                                                                                                     | Tweet about parameter update pending. 90-day notification period started with forum post.                                                                                             |
| Discussion on 90-day Notification           | Adam questioned the 90-day wait, suggesting it's overly conservative, and asked if the TSC could propose lowering it. Kevin explained the 90-day period was a compromise with security researchers for proper community debate. This falls under the parameter committee's remit, not the TSC's. Sebastian questioned why it's an off-chain agreement not on-chain.                    | Discussion on the rationale and potential review of the 90-day notification period for protocol parameter changes.                                                                    |
| Security Council Update                     | Kevin provided an update from the Security Council. Charles Morgan (IOG Head of Security) is no longer a representative, and the Security Council has approached Nicolas for a recommendation for a replacement. Kevin highlighted Charles's instrumental role in Cardano's security.                                                                                                  | IOG representative needed for Security Council. Nicolas to follow up on recommendation.                                                                                               |
| Disaster Recovery Plan (SIP 135) Fire Drill | Kevin discussed planning a fire drill for SIP 135 (Disaster Recovery Plan) around September, using SanchoNet as the testbed to avoid impacting live testnets. Johnny offered to participate and help with guidance documents. The goal is to test communication channels and build trust in the recovered system.                                                                      | Fire drill for SIP 135 planned for September on SanchoNet.                                                                                                                            |
