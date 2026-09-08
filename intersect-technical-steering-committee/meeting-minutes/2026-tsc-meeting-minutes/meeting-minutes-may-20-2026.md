# Meeting Minutes May 20, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| TBC                | No         | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | No         | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | No         | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Christian Taylor   | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Lorenzo Bruno
* Thiago Nunes
* Thomas Lindseth
* Wilco van de Burgwal

Recording: [Technical Steering Committee - 2026/05/20 - Recording](https://drive.google.com/file/d/1rELn1UrT67qAC7R_jyDRPYbCmb05yreU/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/05/20 - Transcript](https://docs.google.com/document/d/1t-QWsayQN0h21RoeG-bOKIk8-Ka39tPGr2hHEyxvzFo/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/05/20 - Chat Transcript](https://drive.google.com/file/d/1QcG9nDEVa_fO7FyowwJPfXKfLz4k3kNV/view?usp=drive_link)



## Agenda 20th May 2026

* Actions from the last meeting
* TSC Proposal Feedback
* Providing TSC Feedback on Ekklesia Proposals
* van Rossem Hard Fork
* Two repositories transferred to Intersect
* Post Quantum Crypto (Standing Item)
* Parameter Committee
* CC Member Nomination
* Upcoming Event: Node Diversity workshop in Porto: June 2-3
* AOB

## Decisions/Actions

**Decisions**

* **Guidance for DReps:** Approved the principle of publishing the 6-point evaluation framework checklist to assist DReps, rather than reviewing individual technical proposals.
* **Format for Quantum Session:** Decided to host the upcoming post-quantum crypto session as an open, 1-hour community workshop rather than a standard, restricted TSC meeting item.
* **Pre-Prod Recommendation Criteria:** Established that the Hard Fork Working Group will only recommend the Pre-Prod fork if the Ogmios upgrade PR is fully out of draft status by the epoch boundary.

**Actions**

* **Kevin:** Revise the TSC Ekklesia budget proposal by Friday noon to explicitly include the community-requested transparency and conflict of interest guidelines.
* **Alonzo & New Members:** Review the CC minimum size rationale metadata document prepared by Ryan and comment on Slack.
* **Marcin, Alonzo, & Alexander:** Check email inboxes to accept the pending ClickUp workspace invitations sent via Intersect.
* **Alonzo:** Coordinate with Terence and Bosko to update and sync his official member profile email address for private Slack channel access.
* **Ryan:** Invite Rich Mandarino to join tomorrow's Parameter Committee meeting as an observer for the K parameter adjustment debate.

<br>

| Topic                       | Discussion                                                                                                                                                                                        | Notes                                                                                                                     |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Meeting Leadership          | Kevin announced he must leave after 30 minutes to present the maintenance proposal to Cardano Over Coffee. The committee agreed to a decentralized, "self-chairing" approach for the second half. | Bosko acted as a facilitator to keep the meeting aligned with the pre-defined agenda.                                     |
| CC Nominations & CIP-182    | Leandros discussed his candidacy for the Constitutional Committee (CC). Alexander introduced SIP-182 (Optimistic Constitutionality), which explores treating non-votes as passive "Yes" votes.    | Ryan and Leandros noted that utilizing a script to auto-delegate CC hotkeys is more secure than changing ledger defaults. |
| Post-Quantum Presentation   | Kevin received a positive response from Hamza regarding a post-quantum risk presentation. Christian and Kevin are following up on potential speakers.                                             | The presentation will be structured as a dedicated public workshop in 3–4 weeks.                                          |
| Ecosystem CPS Review        | Kevin emphasized that all members, particularly new ones, must review CPS-27 and CPS-30 to familiarize themselves with post-quantum cryptography problem definitions.                             | Alexander noted that CPS-30 provides a clearer problem breakdown than CPS-27.                                             |
| TSC Budget Proposal         | The committee reviewed community feedback on the TSC Ecclesia proposal. The feedback requested explicit conflict of interest rules, reviewer criteria, and public reports.                        | The deadline to finalize and submit revisions on Ecclesia is Friday, May 22nd, at 12:00 PM Noon.                          |
| Ekklesia Proposal Advice    | The Intersect Steering Committee asked if the TSC could provide technical evaluations for the 92 submitted proposals to guide DReps.                                                              | The committee expressed concern over the high workload and low ROI for a shallow review process.                          |
| DRep Guidance Criteria      | Kevin drafted a 6-point checklist to help DReps evaluate proposals objectively without the TSC endorsing specific projects.                                                                       | The criteria cover public good status, team track record, milestones, cost, roadmap fit, and security.                    |
| Hard Fork & Ogmios Status   | Bosko provided an update from the Hard Fork Working Group. Ogmios readiness remains the critical path bottleneck for the Pre-Prod hard fork.                                                      | John Latuski and Eric de Castro (IOG) are drafting PRs, which are currently being reviewed by Matthias.                   |
| Pre-Prod Cutoff Timeline    | If the Ogmios PR is not finalized by tomorrow's Pre-Prod boundary, the Pre-Prod fork will be delayed, subsequently impacting the planned May 29th Mainnet governance submission.                  | Node 11.2.5 adoption among SPOs has progressed to 33% according to PoolTool data.                                         |
| DB-Sync Discrepancy         | Alexander and Bosko noted a bug where DB-Sync version 13.7.0.5 fails to track the entirety of Epoch 631.                                                                                          | IOG and integration teams are working on a resolution script.                                                             |
| Repository Transfers        | Marcin announced the transfer of two basic, non-Cardano-specific IOG network libraries (io-sim and typed-protocols) to Intersect.                                                                 | These libraries focus on testing and type-safe network protocols.                                                         |
| Parameter Committee Preview | Alexander previewed the upcoming Parameter Committee meeting, highlighting a highly anticipated debate on increasing the K parameter.                                                             | Ryan shared a custom Dune Analytics dashboard collating incentive data to support the debate.                             |
| Porto Tech Workshop         | Bosko shared details for an upcoming technical workshop in Porto, Portugal, from June 2–3. Free accommodation is available via the Amaru team.                                                    | Committee members traveling to the event must coordinate with Damian on Discord.                                          |
