# Meeting Minutes October 22, 2025

## Attendees:&#x20;

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | Yes        | Chair       | Y                 | October 2025 |
| Adam Dean                | Yes        | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Markus Gufler            | Yes        | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | No         | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | Yes        | Member/Seat | Y                 | October 2025 |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | Yes        | Member/Seat | Y                 | April 2026   |

**Community/Other Attendees**

* Arnaud Bailly
* Christian Taylor
* Jessica Gilbert



**Recording:** [Technical Steering Committee - 2025/10/22 - Recording](https://drive.google.com/file/d/1mXmXIdevKJpB7vMQX6FE_afpjFwVXTUU/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/10/22 08:22 CDT - Transcript](https://docs.google.com/document/d/1pL3KDVhoPWekp-YPopzcOLrhdDjPNmvZnYSvMl524ok/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/10/22 - Chat Transcript](https://drive.google.com/file/d/1prHKG4GhzsMKnKNAop6DknLmcTkas8Pf/view?usp=sharing)

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

## Agenda 10.22.25

* New Topic - Arnaud
* Cardano Reward Sharing Scheme v2 Ballot - Johnny
* Hard Fork Working Group - Tex
* Cardano Vision: Enabling Technology Pillar request - Kevin
* Fire Drill Report - Johnny
* Linear Leios Status - Sebastian/Nicolas/Neil&#x20;

## Decisions/Actions

**Decisions**

* Agenda Prioritization: Agreed to start the meeting with Arnaud's presentation on Antithesis to accommodate Nicolas and Neil's need to leave early.
* Antithesis Discussion: Decided to seek feedback on the Antithesis funding proposal (community asset funded by the Treasury) asynchronously or offline.
* Hard Fork Working Group (HFWG) Reforming: Decided to reconvene the HFWG as quickly as possible and delegate to the group the tasks of:
* Defining the scope of the upcoming intra-era hard fork.
* Engaging with the community on the scope and timeline.
* Considering the proposal to name the hard fork in memory of Maxon Rothsam, and subsequently putting the final naming decision to the community as an info action.
* HFWG Scope: Agreed that the HFWG should be a standing group focused on the overall cadence of releases and hard forks (including the Dijkstra hard fork), essentially serving as a release management group.

**Actions**

* **Kevin:**
  * Take the list of HFWG volunteers/essential members (Kevin, Adam, Johnny, Sebastian, Alex (optional)) offline to coordinate the initial meeting invitations.
  * Start a document and make initial comments on the Cardano Strategy Document/Enabling Technology Pillar to allow others to contribute, then pass it on to Sam.
* **Arnaud (or Antithesis Team):**
  * Provide detailed answers to Neil's questions regarding the cost-benefit analysis, false positive rate, robustness in regression, and scaling for conformance testing.
  * Coordinate with the Cardano Foundation regarding the future of Antithesis funding post-2025.
* **Johnny:**
  * Write a report to highlight lessons learned from the Disaster Recovery Fire Drill.
  * Carry out additional test scenarios, specifically Scenario 1 (bifurcated network recovery).
  * Determine whether additional tooling (fast-forwarding clock) or updating the SIP to reflect distributed use of DB Synthesizer is necessary.
  * Put the action points for the fire drill follow-up in the technical steering chat.
* **Tex and Kevin:**
  * Coordinate with Jess to get a list of initial invitees for the reformed HFWG.
* **All Attendees:**
  * Look at the link provided for the Cardano Strategy Document/Enabling Technology pillar and provide individual contributions (e.g., submitting PRs) if a coordinated PR is not possible due to the short timeline before the Cardano Summit.

| Topic                                     | Discussion                                                                                                                                                                                                                                                                                                                                                              | Notes                                                                                                                                                                                                                                     |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Meeting Convening & Attendance            | Kevin formally convened the meeting, noting that there were nine voting members present. Attendees included Kevin, Nicolas, Johnny, T., Neil, Alex, Arnaud, Jess, and Markus.                                                                                                                                                                                           | Almost complete quorum achieved.                                                                                                                                                                                                          |
| Agenda Prioritization                     | Kevin presented the hastily compiled agenda. Nicolas and Neil noted they had to leave at 15:00 and prioritized a discussion about Antithesis.                                                                                                                                                                                                                           | Agreed to start with Arnaud's presentation on Antithesis to allow him to leave afterward.                                                                                                                                                 |
| Review of Previous Actions                | T. noted previous actions included publicizing STO participation in governance and raising awareness about parameter changes (ongoing). Actions from the previous meeting related to the linear layout conversation, which is on the current agenda.                                                                                                                    | Actions from October 8th and October 15th were briefly addressed.                                                                                                                                                                         |
| Antithesis Status & Proposal              | Arnaud presented the status of the Antithesis project, a distributed systems simulation testing tool. He sought guidance on whether to continue and how to fund it as a Cardano community asset.                                                                                                                                                                        | Antithesis provides deterministic, reproducible testing with fault injection and fuzzing capabilities.                                                                                                                                    |
| Antithesis Usefulness & Findings          | Arnaud shared that initial testing in April/May found a couple of issues, including one security bug requiring a patch. Recent work focused on making the tool more usable for the community through tooling (NTCLI).                                                                                                                                                   | NTCLI uses on-chain contracts and an off-chain oracle to track usage and encrypt results.                                                                                                                                                 |
| Antithesis Funding & Cost                 | Johnny, Neil, and Kevin discussed potential funding paths. Arnaud stated the license cost is $400,000 per year, with total costs estimated around $500k–$600k (including one FTE for maintenance).                                                                                                                                                                      | The cost is too high for Open Source Tooling Sustainability. Options are Intersect budget (2026) or a direct on-chain proposal.                                                                                                           |
| Cost-Benefit and False Positives          | Neil questioned the cost-effectiveness, emphasizing human cost over dollar cost. Arnaud acknowledged initial false positives but said they are now at near zero due to tuning. He argued it offers a multiplying effect on testing coverage.                                                                                                                            | Neil suggested the core issue is the return on investment compared to putting human effort elsewhere.                                                                                                                                     |
| Antithesis as Agnostic Testing            | Markus and Sebastian discussed the value of Antithesis as a neutral, agnostic platform for comparable testing between different node implementations (Haskell, Rust, etc.), as seen in the Node Diversity Workshop.                                                                                                                                                     | Sebastian noted that it supports testing of consensus and data nodes in adversarial Docker environments.                                                                                                                                  |
| Reforming the Hard Fork Working Group     | Jess (from IO) introduced herself and the proposed intra-era hard fork. Kevin proposed delegating the scope definition and community engagement to a reformed Hard Fork Working Group.                                                                                                                                                                                  | Group to be reconvened as quickly as possible to manage the full release cadence, not just the upcoming hard fork.                                                                                                                        |
| Hard Fork Timeline and Naming             | Jess gave an aspiration of an on-chain vote in mid-January. Kevin, Adam, and Sebastian stressed that given the process (delivery status, tooling updates, holiday period, SPO voting), January is unlikely. Sebastian suggested naming the hard fork in memory of Maxon Rothsam and the group agreed to delegate this to the working group to propose to the community. | A 3-month lead time is generally considered reasonable between the release candidate and the hard fork.                                                                                                                                   |
| Parameter Change Proposal (PCP00004)      | Alex briefly mentioned PCP00004, which proposes adjusting Plutus V2 cost model values to align closer with V3, which is being introduced in the hard fork.                                                                                                                                                                                                              | This needs to go through the Parameter Committee.                                                                                                                                                                                         |
| Current Parameter Update (PCP00003)       | Alex updated that the current governance action (PCP00003) to increase the max transaction execution units for Plutus memory is ready for go-live after testnet ratification, aiming for submission on Mainnet in the second week of November.                                                                                                                          | Increased execution units for Plutus scripts. Voting time may run into the Christmas break.                                                                                                                                               |
| Disaster Recovery Fire Drill (Scenario 2) | Johnny reported on the drill where block production was stopped for over 24 hours on Sanchet. Recovery was successful using DB Synthesizer, building a less dense chain of empty blocks.                                                                                                                                                                                | Action: Write a report on lessons learned; carry out additional tests (Scenario 1 - bifurcated network); determine if additional tooling (fast-forwarding clock) or updating the SIP to reflect distributed DB Synthesizer use is needed. |
| Future Tooling: Fast-Forwarding Clock     | Johnny noted that no readily available tool was found to 10x the speed of Cardano node production for recovery. Arnaud confirmed that DB Synthesizer in a distributed way is not a far stretch.                                                                                                                                                                         | Concerns raised about SPOs handing over VRF/KZ keys for centralized recovery.                                                                                                                                                             |
| Cardano Strategy Document Input           | Kevin mentioned Sam L. is asking for input on the Enabling Technology pillar for the Cardano Vision/Strategy document before the Cardano Summit.                                                                                                                                                                                                                        | Kevin will start a document for coordinated community input; individuals can also submit PRs directly.                                                                                                                                    |
