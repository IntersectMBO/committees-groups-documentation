# Meeting Minutes August 05, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | No         | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | No         | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Michiel Bellen
* Musa Ridwan Itopa



Recording: [Technical Steering Committee - 2026/08/05 - Recording](https://drive.google.com/file/d/1rKrB44IedDORtUz3s9BqffeW_ocRPn-i/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/08/05 - Transcript](https://docs.google.com/document/d/12eXKh_jFaWg2PI7H3hAYBmG_7N_Zo_rfF5P8pP4F6aw/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/08/05 - Chat Transcript](https://drive.google.com/file/d/1Zlwvywu1857GyCVODjxPqreOz5qTwenm/view?usp=drive_link)

## Agenda 5th August 2026

* Actions from the last meeting
* Technical Steering Committee Budget Action
* Linear Leios: Scope, Questions, Hard Fork Timing
* minPoolCost Reduction/Plutus mem limits increase
* Usage of SRV records in cardano ecosystem
* Cardano Vision 2030 KPI Framework: Committee Feedback - CPC Survey
* Health scan across the Intersect MBO GitHub organization
* Post Quantum Cryptography
* Ryan Williams left Intersect
* AOB

## Decisions/Actions

**Decisions**

* **TSC Budget Hedging Approval:** Formally authorized Intersect to convert designated budget lines, Technical Expert Attendance at Community Events and Commissioning of Technical Reports, (\~20% of the total budget allocated) into USD, leaving the remaining operational budget denominated in ADA.
  * 40K USD for Technical Expert Attendance at Community Events
  * 24K USD for Commissioning of Technical Reports
* **SPO SRV Record Promotion:** Approved community outreach to encourage SPO adoption of DNS SRV records (CIP-155) to enhance network resilience for Mithril and future node extensions.

**Actions**

* **Alexander:** Coordinate with the Developer Portal team to create SPO documentation and user guides for setting up DNS SRV records.
* **Bosko:** Share the Dijkstra phased rollout document with the TSC members and follow up with Jeff (IO) to resolve dashboard access permissions.
* **Bosko:** Notify Intersect finance (Matt / Jack) that the TSC budget hedging conversion document has achieved the required sign-offs and is approved for execution.
* **Leandros:** Review the Product Committee KPI framework survey for Vision 2030 and share initial draft thoughts in the TSC Slack channel.
* **Neil:** Forward broken website links regarding public TSC minutes on the Intersect site to Bosko for correction.

| Topic                                                  | Discussion                                                                                                                                                                                                                                                                                                                 | Notes                                                                                                                                                                                           |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Agenda Review & Quorum                                 | Neil and Bosko opened the meeting. Five TSC members were present, officially confirming a quorum for binding decisions.                                                                                                                                                                                                    | Christian noted he had to leave early due to a conflicting meeting. The TSC budget conversion item was prioritized to accommodate his schedule.                                                 |
| Review of Previous Action Items                        | Bosko reviewed pending actions: the Cardano Over Coffee session and approved budget messaging were complete. Jeff (IO) shared the Dykstra phase rollout plan via email, though the internal dashboard link required access troubleshooting.                                                                                | Bosko will post the Dijkstra project plan with the TSC members                                                                                                                                  |
| TSC Budget Conversion & Hedging Approval               | The committee reviewed the formal budget conversion document. To mitigate price volatility, funds for USD-denominated lines (technical experts and independent reports) will be converted to stablecoins (e.g., USDM/USDCx), while ADA-denominated lines (Parameter Committee, CIP Editors, Working Groups) remain in ADA. | With signatures from Alexander, Leandros, and Christian's verbal sign-off, the conversion plan reached the required 70%+ approval threshold to allow Intersect to execute the hedging strategy. |
| CIP Editors Payment Structure                          | Bosko clarified that among the active CIP Editors, only Robert requested payment (denominated in ADA at up to $4,000/month equivalent). Ryan (Williams) declined compensation, and Thomas is covered via IOG.                                                                                                              | Robert is currently looking to recruit an additional CIP Editor to expand the team beyond its current three members.                                                                            |
| Parameter Change Governance Action (Minimum Pool Cost) | Alex confirmed that the parameter change proposal (reducing minimum pool cost to 75 and increasing Plutus memory limits) is live on-chain. It currently sits at 12% DREP and 1% SPO support, with an expiration date of September 1st.                                                                                     | The committee discussed the need to actively engage SPOs early to avoid voting bottlenecks prior to the deadline.                                                                               |
| Ecosystem Adoption of SRV Records (SIP-155)            | Marcin presented on Cardano node support for DNS SRV records (CIP-155), which allows dynamic, decentralized node discovery (currently implemented in the DMQ node for Mithril).                                                                                                                                            | SPOs are strongly encouraged to update and resubmit their certificates to comply with CIP-155. This allows IP/port changes without requiring continuous on-chain re-registration.               |
| Best Practices for SRV Records Documentation           | Neil explained that SRV records provide late-binding resilience, precedence ordering, and custom port configuration. Alex proposed incorporating SRV setup guides into the Cardano Developer Portal.                                                                                                                       | Alex will coordinate with the Developer Portal maintainers (Bora) to publish user guides for SPOs.                                                                                              |
| Intersect Product Committee KPI Survey                 | The Product Committee issued a 15-minute survey asking each committee to submit feedback on the Cardano Vision 2030 KPI framework within three weeks.                                                                                                                                                                      | Leandros will take the lead on reviewing the survey requirements and drafting proposed TSC inputs for group review in the Slack channel.                                                        |
| Departure of Ryan Williams                             | Bosko formally announced that Ryan Williams is stepping down from his role with Intersect and leaving for another project, though he will remain active in the broader community.                                                                                                                                          | The TSC expressed its gratitude to Ryan for his extensive contributions to the Cardano testnets and CIP processes.                                                                              |
