# Meeting Minutes May 27, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | No         | Chair           | Y                 | October 2026 |
| TBC                | No         | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | No         | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | No         | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Christian Taylor   | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Hart Montgomery
* Mike Hornan



Recording: [Technical Steering Committee - 2026/05/27 - Recording](https://drive.google.com/file/d/1loyC0YS7PBVevClCNi0_r44PblaF-jgd/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/05/27 - Transcript](https://docs.google.com/document/d/1BHgUZm1rWcms7UehCFDVxVZdY2pXAgAle4hufiyFmKM/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/05/27 - Chat Transcript](https://drive.google.com/file/d/1bz_M58QNGq1rRuxo0y-npcVA_h9qrOZV/view?usp=drive_link)

## Agenda 27th May 2026

* Actions from the last meeting
* Post-Quantum Crypto
* TSC Proposal Feedback
* Providing TSC Feedback on Ekklesia Proposals
* Hard Fork Status
* committeeMinSize
* Upcoming Chair Elections
* AOB

## Decisions/Actions

**Decisions**

* **Parameter Bundling:** Rejected the idea of bundling the CC minimum size change with other parameter alterations (like minPoolCost), choosing to keep them as standalone votes for DReps.
* **Ogmios Path Forward:** Defined the official criteria for the Pre-Prod fork recommendation as having a finalized, non-draft Ogmios upgrade PR ready by the upcoming epoch boundary.
* **Proposal Framework Integration:** Agreed to use Kevin's DRep guidance text as a foundational blueprint to be integrated directly into a technical governance agent tool.

**Actions**

* **Hart:** Share the post-quantum readiness slide deck with Christian for distribution to the full committee.
* **Christian & Hart:** Coordinate a separate side-recording of the quantum readiness presentation to share async with the broader community.
* **Alexander:** Provide the DRep proposal guidance framework document to partners at Griffin to integrate technical evaluation logic into their governance knowledge graph.
* Bosko: Track tomorrow's Hard Fork Working Group meeting outcomes and provide a comprehensive update to the TSC regarding Ogmios and the Pre-Prod schedule.
* Bosko: Open an asynchronous communication thread on Slack to gauge committee sentiment regarding a potential extension of the Chair election application phase.
* All Members: Review the unified CC minimum size metadata documentation and submit candidacy applications in the Members Area if seeking the Chair/Vice Chair roles.

| Topic                        | Discussion                                                                                                                                                                              | Notes                                                                                                            |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Meeting Leadership           | Kevin was absent. The committee agreed to follow the pre-defined agenda with Bosko facilitating the review and keeping track of items.                                                  | The meeting proceeded as a decentralized, self-chaired session.                                                  |
| Action Items Review          | Kevin completed the TSC budget proposal adjustments by the previous Friday deadline. Terence confirmed that all new members have accepted ClickUp, Google Drive, and Slack invitations. | All member onboarding and access setups are fully complete.                                                      |
| CC Minimum Size              | Alexander reported that the Civics Committee expressed concern over drastic rationale changes regarding the Constitutional Committee (CC) minimum size.                                 | Alexander and Ryan collaborated with them to establish a unified proposal.                                       |
| Parameter Change Submission  | Alexander suggested submitting the CC minimum size reduction this week without waiting for the Plutus parameter updates to fully finish on-chain.                                       | Ryan supported keeping parameter changes unbundled so DReps can weigh them separately.                           |
| Quantum Computing Context    | Guest speaker Hart provided an overview of quantum compute capabilities, noting its severe threat to public-key cryptography via Shor's algorithm.                                      | Symmetric cryptography (e.g., AES) is a lower priority due to the high resource cost of Grover's algorithm.      |
| Harvest Now, Decrypt Later   | Hart highlighted the active risk of adversaries recording current encrypted data traffic to decrypt it once fault-tolerant quantum computers emerge.                                    | This makes off-chain data flows and non-PQ secure ZKPs vulnerable today.                                         |
| Cryptographic Agility        | Hart defined cryptographic agility as the engineering ability to swap algorithms and keys cleanly without core system downtime.                                                         | Protocols must be robust enough to handle the larger key and signature sizes inherent to PQ crypto.              |
| Cardano Quantum Risk Profile | Hart assessed Cardano's core ledger risk as relatively low compared to EVM chains since it avoids encrypted commitments.                                                                | Alexander argued that Cardano remains uniquely vulnerable because its consensus relies heavily on VRF keys.      |
| Ekklesia Evaluation Tool     | Christian proposed converting Kevin's DRep evaluation framework blueprint into an automated, AI-driven analysis tool to flag project red flags.                                         | Alexander noted this fits his ongoing work with custom sentiment-aligned governance agents.                      |
| Hard Fork Status & Ogmios    | Bosko reported that Ogmios readiness remains the critical path blocker for the Pre-Prod hard fork, as a fast review of the massive PR by Matthias is unlikely.                          | To maintain the May 29th Mainnet timeline, an option to utilize a temporary code fork of Ogmios is under review. |
| DB-Sync Fix                  | Bosko confirmed that the epoch tracking discrepancy affecting versions up to 13.7.0.x has been completely resolved in the new 13.7.1.0 release.                                         | Operators remaining on 13.7.0.5 are instructed to run the patch script provided in the release notes.            |
| TSC Chair Elections          | Terence outlined the standard annual election process for the TSC Chair and Vice Chair roles via the Intersect Members Area interface.                                                  | The application window officially opened this week. The runner-up in the vote becomes Vice Chair.                |
