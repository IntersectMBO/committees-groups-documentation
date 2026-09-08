# Meeting Minutes October 15, 2025

## Attendees:&#x20;

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | No         | Chair       | Y                 | October 2025 |
| Adam Dean                | No         | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Markus Gufler            | Yes        | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | No         | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | No         | Member/Seat | Y                 | October 2025 |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | Yes        | Member/Seat | Y                 | April 2026   |

Community/Other Attendees

* Christian Taylor



**Recording:** [Technical Steering Committee - 2025/10/15 - Recording](https://drive.google.com/file/d/1vGDzCdk49mCl3r0Uq71ALaD2QCdA-jPR/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/10/15 - Transcript](https://docs.google.com/document/d/1vKB2ATc4bXH9W6UQ4vP-dYPsUvsOObrBZaxo4WFZqVY/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/10/15 - Chat Transcript](https://drive.google.com/file/d/1mUHnnmLQ2BBUQrB4JLfW7acW6IihM69E/view?usp=sharing)

## Intros

**Adam:** OSC, TSC, CIP Editor, DripDropz LLC\
**Alex:** TBD\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:**  TBD\
**Markus:** TSC member, CF employee, SPO\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TBD\
**Sebastian:** TBD\
**Tex:**  Open Source Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison

## Agenda 10.15.25

* Updates from weekly Intersect Steering Committee (ISC) meeting
* Hard Fork Working Group status update
* CIP-164 (Leios) update \[Sebastian]
* CIP-135 (Sancho Net) Fire Drill \[Adam/Mike Hornan]
* Any Other Business

## Decisions/Actions

Decisions

* **Sebastian** was nominated and accepted the role of **temporary Chair** for this specific meeting.
* The agenda was confirmed, including the decision to discuss the parameter change tooling issue first due to its urgency.

Actions

* **Communication:** Publicize the requirement for SPO participation in the current governance action and raise awareness about the Security Group parameters in the Constitution. (Owner: Alexander/Terence/Jonathan)
* **TSC Chair:** Individuals to "stew on" the Chair/Co-Chair role and reach out to Terence if interested in an individual or small-group discussion. (Owner: All)
* **Elections:** Reach out to and encourage qualified individuals to apply/reapply for the committee elections before the October 24th deadline. (Owner: All)
* **Disaster Recovery:** Jonathan to report back to the TSC next week on the outcome of the CIP 135 disaster recovery fire drill on SanchoNet. (Owner: Jonathan)

| Topic                                  | Discussion                                                                                                                                                                                                                                 | Notes                                                                                                                                                                               |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Search for Technical Female Candidates | Terence asked if anyone knew of smart technical ladies who could be considered for positions like the TSC.                                                                                                                                 | Neil and Alexander questioned the purpose. Neil has technical ladies in his company and suggested they should apply, though he was unsure if they would.                            |
| TSC Gender Balance                     | Terence suggested the need for a female on the TSC for balance. Neil agreed that proper gender balance can "massively help the dialogue and the nature of communications" and change the dynamic dramatically in groups of engineers.      | This was raised as a potential need to "break it up" and "bounce it out" of the current dynamic.                                                                                    |
| TSC Chair Role Discussion              | Terence brought up the Chair role, noting that most current members are continuing. The group discussed the fact that Kevin was willing to continue, but no one else had volunteered.                                                      | This conversation was separate from the formal agenda.                                                                                                                              |
| Continuity of Chair Role               | Terence noted the difference in the TSC from other committees that have adopted a cycling chair/co-chair model for continuity, asking for an election to replace Adam six months ago.                                                      | Sebastian asked for clarification on the exact "ask" regarding having a chair before the general election.                                                                          |
| TSC Stripped of Power/Motivation       | Neil stated that the TSC's power has been stripped, making it difficult to find motivation to take on the Chair role due to lack of resources and outside interference. Terence disagreed with attributing all concerns to this point.     | Neil noted that this is why people aren't standing for election and why no one is willing to step up for the Chair role.                                                            |
| Chair Role Time Commitment             | Duncan and Neil pointed out the significant, uncompensated time commitment required for the Chair role, including attending several other technical and operational meetings weekly. Sebastian mentioned a planned change to compensation. | Duncan stated he would prefer to spend extra time on reviewing specs. Sebastian noted a repeated time conflict every four weeks.                                                    |
| Interim Chair Nomination               | After confirming Adam was not present for the updates, Sebastian offered to run the meeting. Duncan nominated Sebastian as a temporary chair for the current meeting, which was seconded by Jonathan.                                      | Sebastian accepted and started the meeting officially.                                                                                                                              |
| Parameter Change Tooling Shortcomings  | Alexander raised a point about common tools, including the governance overview, failing to correctly implement a small sub-clause requiring SPO (Stake Pool Operators) votes for parameters within the security group.                     | Alexander and Neil noted this issue has highlighted shortcomings in the available tools. Markus confirmed Cardano Scan fixed it, and other tools are being updated.                 |
| SPO Vote Communication and Awareness   | Markus and Alexander stressed the need to communicate this to SPOs to raise awareness of their voting requirement for the security group parameters.                                                                                       | Jonathan confirmed his "Martin Lang" tools work correctly. Jonathan also noted that many SPOs have opted to auto-abstain, mitigating the worry.                                     |
| CIP 1694 Clarification                 | Duncan and Alexander noted that the exception for security-relevant parameters in CIP-1694's voting table is easy to miss and suggested clarifying the CIP. Jonathan offered his color-coded guardrails table as a resource.               | Action items include highlighting the SPO participation requirement and the existence of the security group via communication channels. Alexander confirmed a blog post is planned. |
| Intersect Steering Committee Updates   | Terence provided updates on the committee elections, emphasizing the need to reach out and encourage qualified people to apply before the nomination deadline.                                                                             | Nominations close on October 24th; voting is from October 27th to November 7th. Announcements planned for the Cardano Summit (mid-November).                                        |
| Hard Fork Working Group Status         | Markus reported that Kevin was following up on the status and composition of the former working group. No immediate action was taken.                                                                                                      | It was noted that this could potentially be bootstrapped from the Tuesday release meeting.                                                                                          |
| CIP 164 Update                         | Sebastian provided a follow-up on CIP 164, noting that the design team has been working on feedback and that a bug was found in the simulator, which produced better (more promising) results for transaction throughput.                  | Sebastian requested that feedback continue to be provided, preferably using the threading feature in the CIP PR comments.                                                           |
| Disaster Recovery Fire Drill           | Jonathan gave an update on the planned fire drill on SanchoNet to test recovering from a lack of block production across the network. Six SPOs will participate to coordinate the recovery.                                                | The drill is scheduled for the evening at 8:00 UTC. Jonathan will report back next week.                                                                                            |
| Upcoming Cardano Summit                | Duncan asked who would be attending the Cardano Summit in Berlin, with Terence, Sebastian, and Alexander confirming they would be there.                                                                                                   | An opportunity to meet in person soon.                                                                                                                                              |
