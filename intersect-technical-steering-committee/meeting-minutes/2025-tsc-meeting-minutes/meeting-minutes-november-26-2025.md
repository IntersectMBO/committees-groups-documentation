# Meeting Minutes November 26, 2025

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | Yes        | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | No         | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Benjamin Hart
* Christian Taylor



**Recording:** [Technical Steering Committee - 2025/11/26 - Recording](https://drive.google.com/file/d/1b0ME5jvhhQoaa_Bx7lXu8isGpDxzcIMA/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/11/26 - Transcript](https://docs.google.com/document/d/1TlX8YzUSP9fEjK8mnuGdydwrsQrL26Dx-aNo-wgNCfs/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/11/26 - Chat Transcript](https://drive.google.com/file/d/1PguS0doS4f5BSob_6TCloVGnG8It1n60/view?usp=sharing)

## Intros

**Alex:** Head of Infrastructure, Cardano Foundation, TSC member, Parameter Committee\
co-chair, CF, Drep\
**Duncan:** TBD\
**Kevin:**  TSC Chair, Founder at Ensurable Systems\
**Leo:** Developer@KeyPackt/AnetaV2/GenWealth single pool SPO, CEO LnLlabs, TSC member\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TSC member, Director of Software Architecture at IOG\
**Ryan:** TBD\
**Sebastian:** TSC member,  Software Architect, nCoding and IOE\
**Tex:** OS Program Manager (Intersect), TSC/OSC Secretary, Committee Liaison\
**Udai:** Member OSC and TSC, AIQUANT Technologies

## Agenda 11.26.25

* TSC Chair - Neil
* Annual Members Meeting - Bosko
* Mainnet Incident Summary - Kevin
  * Including request for input from Geoff Watson (IOE)
* Hard Fork Working Group - Bosko
  * First meeting is 2nd December
  * Plutus cost model will need to be updated
  * Benchmarking will need to be done
* Nested Transactions Follow-on - Kevin
* 2030 Vision and 2026 Budget - Kevin
  * TSC Role
* TSC operational budget - Kevin
* Seungheon Oh - Kevin
* AOB

## Decisions/Actions

**Decisions**

* **TSC Chair & Vice-Chair Nominations:** Agreed to start the process for nominations for the new Chair and Vice-Chair in the next week, followed by a discussion on the role and then a vote.
* **Out-of-Band Discussion on Chair Role:** Neil offered to facilitate an out-of-band discussion with interested members about the specifics and experience of the Chair role.
* **Nested Transactions Response Strategy:** Agreed to draft a summary response to Michaela's concerns regarding nested transactions, focusing on the trade-offs of multi-party atomic transactions and MEV exposure (his points 4 and 1). The TSC will advise that the issue appears to be primarily a product choice and should be directed to the Product Committee for a decision.
* **Drafting the Nested Transactions Response:** Bosko was assigned to use AI tools to generate the initial draft text for the TSC's response on nested transactions.
* **TSC Operational Budget Proposal:** Agreed to kick off the process for creating a proposal for a TSC operational budget to support essential activities like event attendance.

**Actions**

* **Clarify Jeff's Request:** Kevin will follow up with Jeff to clarify precisely what he means by the TSC "tracking" his request for guidance on incident improvements.
* **Draft Nested Transactions Response:** Bosko will use AI tools to generate the initial text for the TSC's response regarding nested transactions and circulate it for review.
* **Start Operational Budget Proposal:** Kevin will begin drafting the proposal for a TSC operational budget to be progressed over the next few weeks.
* **Begin Chair/Vice-Chair Nomination Process:** The committee will begin asking for nominations for the new Chair and Vice-Chair within the next week.
* **Review Plutus Cost Model:** The committee will pass on the concern regarding the need for more evidence and a robust regression process for the new Plutus cost model to the appropriate team/committee.
* **Discuss Root Cause Analysis:** Ryan, Neil, and Kevin will attend the 4:30 PM Forensic Working Group meeting and pass on Duncan's suggestion that the working group's remit should include looking at the root cause in terms of systematic testing and code coverage gaps.
* **Hard Fork Working Group Meeting:** Attendees will join the first Intra-Era Hard Fork Working Group meeting on December 2nd.

| Topic                       | Discussion                                                                                                                                                                                                                                                                                                                 | Notes                                                                                                                                                                                                                                                  |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| TSC Chair and Vice-Chair    | Neil introduced the topic of the customary voting process for a new Chair and Vice-Chair following the new committee. Neil will not be standing for the positions.                                                                                                                                                         | Need to hold nominations and a vote soon for Chair and Vice-Chair.                                                                                                                                                                                     |
| Nomination Process Timeline | Neil suggested asking for nominations for Chair/Vice-Chair within the next week, followed by a general discussion (possibly in two weeks) about the roles and expectations before the vote.                                                                                                                                | Nominations requested next week. Discussion on role expectations to follow.                                                                                                                                                                            |
| Chair Role Details          | Kevin explained the Chair's role involves chairing the TSC meeting, setting the agenda, and interacting with other bodies, including attending the weekly Intersect Steering Committee meetings.                                                                                                                           | Role includes chairing and external committee interaction (e.g., Intersect).                                                                                                                                                                           |
| Out-of-Band Discussion      | Neil offered to lead an out-of-band discussion about the role of the Chair, drawing on his 18 months of committee experience, for those interested.                                                                                                                                                                        | Neil will facilitate an out-of-band discussion on the Chair role.                                                                                                                                                                                      |
| Mainnet Incident Summary    | Kevin provided a summary: a malformed transaction on the Preview Testnet, then Mainnet, exploited a code bug (malformed pool hash), causing a chain partition. A quick fix was released within 12 hours.                                                                                                                   | Malformed transaction led to a chain partition; hotfix was fast-tracked.                                                                                                                                                                               |
| Chain Recovery              | The decision was made to follow the minority (healthy) chain. Over 50% of the stake joined the healthy chain within 8-9 hours, and the healthy chain overtook the poisoned chain in block production within 14 hours. Nodes recovered under the protocol.                                                                  | Chain successfully rejoined after about 14 hours; technical response was excellent.                                                                                                                                                                    |
| Forensic Working Group      | A Forensic Working Group is being initiated by the security council to analyze the incident. Neil noted their first meeting will be today at 4:30 PM UTC. Duncan raised the need to look at root cause beyond the immediate code bug, suggesting systematic code coverage and fuzzing testing from the CDDL specification. | Working group will perform a forensic analysis; concerns raised about its scope and potential legal scrutiny. Duncan suggested including root cause and testing coverage in the remit.                                                                 |
| Jeff's Request for Guidance | Kevin shared Jeff's request for the TSC to track and provide guidance on improvements following the incident. Neil requested clarification on what "track" means.                                                                                                                                                          | Kevin will follow up with Jeff to clarify the term "track" and the intended level of TSC involvement (advice/consultation vs. sign-off).                                                                                                               |
| Hard Fork Working Group     | Bosko announced the first meeting on December 2nd. The proposal is for an Intra-Era Hard Fork (protocol version 11) with new Plutus primitives (like multiscalar multiplication) and ledger bug fixes, but no full hard fork mandate. This will be the first hard fork in full governance reality.                         | First meeting is December 2nd. Hard fork is for Plutus primitives and bug fixes (Intra-Era).                                                                                                                                                           |
| Plutus Cost Model Concerns  | Neil raised a strong concern about the process for the new Plutus cost model, requesting a lot more evidence and a proper regression path, not last-minute checks. Kevin noted the benchmarks aren't completed yet.                                                                                                        | Need to ensure sufficient evidence and proper regression testing for the Plutus cost model before parameter committee review.                                                                                                                          |
| Nested Transactions Review  | Following the presentation from last week, the discussion focused on how to respond to Michele's concerns. Neil and Duncan agreed the core issues are about ease of multi-party atomic transactions and potential MEV exposure, which are heavily tied to product choice.                                                  | TSC will write a summary response focusing on the trade-offs (specifically points 4 and 1) and will advise Michaela to refer the matter to the Product Committee, as it's primarily a product choice issue. Bosko to generate initial AI-drafted text. |
| 2026 Budget & Roadmap       | The 2026 budget process is starting. Technical input is needed for the 2026 roadmap, aligning with the 2030 vision. A gap exists in the technical evaluation of proposals for the DRAPS process. Neil noted the need for resourcing for this evaluation.                                                                   | Need to provide technical input for the 2026 roadmap and establish a process/resourcing for technical evaluation of DRAPS proposals.                                                                                                                   |
| TSC Operational Budget      | Kevin proposed kicking off a process for a TSC operational budget (e.g., for activities, event attendance), seeking board ratification.                                                                                                                                                                                    | Kevin will start the process for proposing a TSC operational budget.                                                                                                                                                                                   |
