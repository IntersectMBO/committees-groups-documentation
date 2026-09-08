# Meeting Minutes November 19, 2025

## Attendees:&#x20;

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | Yes        | Chair       | Y                 | October 2026 |
| Adam Dean                | Yes        | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026   |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026   |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | No         | Member/Seat | Y                 | April 2026   |
| Markus Gufler            | Yes        | Member/Seat | Y                 | October 2025 |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Benjamin Hart            | Yes        | Member/Seat | Y                 | October 2025 |
| Ryan Wiley               | Yes        | Member/Seat | Y                 | October 2026 |
| Udai Solanki             | Yes        | Member/Seat | Y                 | October 2026 |
| Leandros Holleman        | Yes        | Member/Seat | Y                 | October 2026 |
| Seungheon Oh             | No         | Member/Seat | Y                 | October 2026 |

Community/Other Attendees

* Bosko Majdanac
* Christian Taylor
* Lorenzo Bruno
* Marcin Szamotulski
* Michele Nuzzi



**Recording:** [Technical Steering Committee - 2025/11/19 - Recording](https://drive.google.com/file/d/1O1G2GPwMPpr0c2Mr9rm8Hr0ypBbLlujn/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/11/19 - Transcript](https://docs.google.com/document/d/1YyNMw9az3oUh5sYupRrnVUNAPRLlYB-vc65GTi99Ojg/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/11/19 - Chat Transcript](https://drive.google.com/file/d/1dmTA5WyaGDC2qIIc0l9-KT-h7VvoxMDe/view?usp=sharing)

## Intros

**Adam:** OSC, TSC, CIP Editors, DripDropz LLC Guy Who Does Stuff & Things\
**Alex:** Head of Infrastructure, Cardano Foundation, TSC member, Parameter Committee\
co-chair, CF Drep committee voting member,\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:**  TSC Chair, Founder at Ensurable Systems\
**Leo:** Developer@KeyPackt/AnetaV2/GenWealth single pool SPO,  CEO LnLlabs, TSC member\
**Markus:** TSC voting member, CF, SPO, Parameter Commitee\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TSC member, Director of Software Architecture at IOG\
**Sebastian:** TSC member,  Software Architect, nCoding and IOE\
**Tex:** OS Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison\
**Udai:** Member OSC and TSC, AIQUANT Technologies

## Agenda 11.19.25

* Committee Election Outcome - Bosko
* Annual Report - Kevin
* Nested transactions (Michele Nuzzi, Harmonics)
* Adopting IO Sim and Typed Protocols repos (Marcin Szamotulski, IOE) - Neil
* Cardano Summit - Markus
* Impending Governance Shutdown
* 2030 Vision and 2026 Budget - Kevin
  * TSC Role
* Intersect Coordination- Christian/Bosko
  * HFWG Status
  * Any questions about node releases
  * Alternate node coordination
  * (Technical WG reporting)
* TSC operational budget - Kevin
* AOB

## Decisions/Actions

**Decisions**

* The TSC formally voted to support the adoption of the IOSIM and Type Protocols repositories within the Intersect organization.
* Result: 8 votes in favor, 0 votes against. (Vote Carried)

**Actions**

* **Tex** to ensure all incoming members (Leo, Udai, and Seung) are added to the TSC Slack channels.
* **Kevin** to create an initial draft of the Intersect Annual Report in the shared drive by tomorrow.
* **Tex** to share the example report produced by the product committee (for the Annual Report) in the TSC channel.
* **Sebastian** volunteered to compile and edit the final summary of the Intersect Annual Report (target: end of day tomorrow).
* **Tex** to provide Sebastian with access to relevant reference materials (e.g., weekly minutes) for the Annual Report.
* **Michele** to send a summary of his concerns regarding nested transactions to Kevin or Tex.
* **Kevin** and other TSC members to organize a focused discussion/adjudication with Michael and the Ledger Working Group on the nested transactions issues.
* **Tex** to record the vote outcome on the repository adoption and convey the result to the OSC (Open Source Committee) for their discussion tomorrow.
* **Tex** to convey the committee's representation to Intersect that they should look to appoint more than one new Constitutional Committee (CC) member to establish a buffer and avoid future governance freezes.
* **Bosko** to keep the TSC informed about the timelines for the Hard Fork Working Group meetings (starting next week).
* **Bosko** to invite interested TSC members to the Hard Fork Working Group meetings.
* **Kevin** to discuss the possibility of becoming an individual or collective CC member with any interested parties out of band (outside of the meeting).
* **Kevin** to raise unaddressed agenda items out of band and bring them onto next week's agenda.

| Topic                              | Discussion                                                                                                                                                                                                                                                       | Notes                                                                                                                                                                            |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Agenda Review                      | Kevin pasted the agenda into the chat and pinned it, inviting additions and prioritization.                                                                                                                                                                      | Agenda pinned to chat. Items may be postponed until next week.                                                                                                                   |
| Committee Election Outcome         | Tex, the TSC secretary, confirmed the re-election of Kevin and the election of Ryan, Udai, Leandro (Leo), and Seung to the committee for the next year.                                                                                                          | Congratulations to the newly elected members. Tex sent welcome emails and will help coordinate the transition.                                                                   |
| Transition Plan                    | Kevin emphasized the need to manage the transition between outgoing and incoming members to ensure continuity. The initial step is adding all new members to the relevant Slack channels.                                                                        | Ensure all incoming members (Leo and Udai confirmed requests) have access to TSC Slack channels.                                                                                 |
| Thanks to Outgoing Members         | Kevin expressed gratitude to the outgoing members for their fantastic contributions over the past year.                                                                                                                                                          | Kevin acknowledged and thanked outgoing members for their diligent service.                                                                                                      |
| Intersect Annual Report Request    | The TSC was asked to prepare an annual report for presentation by Intersect next week. Kevin asked all members who served last year to provide input.                                                                                                            | Annual Report is due very quickly (possibly by Friday/Monday). Requires input from all members who served.                                                                       |
| Report Drafting Strategy           | Kevin offered to create the first draft in a shared drive by the next day, but requested that members review his initial list of major points to identify any omissions.                                                                                         | Kevin will create a draft document in the shared drive by tomorrow. Tex will share an example report from the product committee.                                                 |
| Volunteer for Report Summary       | Sebastian volunteered to take ownership of compiling the final summary of the report, suggesting the use of language models for summarization and focusing on notable points.                                                                                    | Sebastian will compile the report. Tex will help provide access to relevant meeting minutes/notes. Target first report is by end of tomorrow.                                    |
| Nested Transactions Concerns       | Micheel presented his technical concerns regarding nested transactions, arguing they add complexity to the ledger without solving any problems that can't be handled by normal transactions.                                                                     | Michele cited concerns about added complexity, difficulty in developer tooling/interface, and potential for Value Extraction (MEV) due to signature changes.                     |
| Nested Transactions: Atomicity     | Neil, Duncan, and Michele debated the core value of nested transactions. Neil and Duncan argued the key is providing atomicity with separate signing, which Michael asserted could be achieved differently.                                                      | The core technical dispute is whether nested transactions add unique atomic functionality beyond what is currently possible with normal transactions and off-chain coordination. |
| Next Steps for Nested Transactions | Kevin proposed that Michele summarize his concerns in a few sentences to organize a focused discussion involving TSC members and the Ledger Working Group for an adjudication of the issues.                                                                     | Michael to send a summary of concerns to Kevin or Tex. A follow-up discussion with the Ledger Working Group will be organized.                                                   |
| Appeal: Repository Ownership       | Neil clarified Marcin's request: the appeal is for IOSIM and Type Protocols repositories to be owned by Intersect instead of IOG. This is primarily to allow non-IOG natural maintainers to be added, ensuring wider participation and continuity.               | Marcin confirmed that the repositories are core components of the Ouroboros network/Cardano node and should be under Intersect for better ecosystem support.                     |
| OSC Discussion & Scope             | Tex noted that the OSC would also be discussing this appeal the next day. Tex also raised a broader issue of setting rules for what is considered relevant for Intersect ownership.                                                                              | The issue will be discussed by the OSC tomorrow. Sebastian made a case for adopting repos that offer maintainer access for the Cardano node supply chain.                        |
| Repository Ownership Vote          | The TSC voted on a motion to support the adoption of IOSIM and Type Protocols within the Intersect organization due to their role as dependencies of the Haskell node.                                                                                           | Vote Carried (8 Yes, 0 No). Tex will record the outcome and convey it to the OSC. Duncan (abstaining) noted a colleague applying for maintainership.                             |
| Impending Governance Shutdown      | Kevin raised the critical issue of the Cardano Atlantic Council resigning from the Constitutional Committee (CC), which will drop the CC size below the minimum of seven, freezing all governance actions (treasury withdrawals, hard forks, parameter updates). | Intersect is holding a snap election to replace the member. Members were encouraged to consider standing individually or collectively as CC members.                             |
