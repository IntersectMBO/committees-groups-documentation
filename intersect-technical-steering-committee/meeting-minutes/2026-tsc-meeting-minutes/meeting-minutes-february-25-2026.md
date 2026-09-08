# Meeting Minutes February 25, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | Yes        | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

**Community/Other Attendees**

* Benjamin Hart
* Gauthier Paluku
* Ian Njuguna
* Ken-Erik Ølmheim
* Mike Hornan
* Pedro Lucas
* Ryan Williams<br>

Recording: [Technical Steering Committee - 2026/02/25 - Recording](https://drive.google.com/file/d/1ZIKxmHxcCs_-_ej3L-DYO0hYGED-q_Lr/view?usp=sharing)

Transcript: [Technical Steering Committee - 2026/02/25 - Transcript](https://docs.google.com/document/d/1cWv6YjA3XsWuY6-k4K-DH_EYnmfOgC5RI8hVbzIqGjk/edit?usp=sharing)

Chat Transcript: [Technical Steering Committee - 2026/02/25 - Chat Transcript](https://drive.google.com/file/d/13GKWE3i7o-SdCB2mnRQQthtEq8j0Yhin/view?usp=sharing)

## Intros

**Kevin:** Kevin Hammond, Ensurable Systems, TSC Chair\
**Ryan (Cerkoryn):** Ryan Wiley, Cybersecurity Professional, TSC Voting Member\
**Udai:** Udai Solanki, member TSC , AIQUANT Tech\
**Sebastian:** Sebastian Nagel, Technical Architect, nCoding, IO\
**Nicolas:** Nicolas Biri, Director of Software Architecture, IO Group\
**Bosko:** Bosko Majdanac - Senior Project Manager, Intersect Staff, TSC Secretary

## Agenda 02.25.26

* Linear Leios Update
* Actions from the Last Meeting
* Update on 2030 Vision KPI's
* Parameter Committee Updates
  * ccMinCommitteeSize passed to Civics Committee
  * Plutus V1/V2/V3 cost models to be considered
* Hard Fork Updates
  * van Rossem status
  * future HF planning
* Question from CPC about TVL
* Constitution v2.4 Review
* 2026 TSC Operational Budget
* April Elections
  * Number of Seats for Election 5 vs 6
  * Clarification on 2yr terms (if needed)
* dRep compensation paper
* AOB

## Decisions/Actions

**Decisions**

* **KPI Publication:** The committee agreed to make the [TSC review of 2030 Vision KPI document](https://docs.google.com/document/d/1PI6ZnawO7S_bidCC4gpm0CauCqI7Ct6nuijHlWPznGE/edit?usp=sharing) public to stimulate community debate.
* **Elections Logic:** Confirmed five seats are officially open for election in April; replacing the sixth vacant seat will be handled via a separate co-option or election process.
* **Constitutional Review:** The committee moved to formalize a document listing the technical inconsistencies found in v2.4 to guide the "Version 3.0" revision.

**Actions**

* **Alexander:** Publish the community post regarding the Stake Pool Operator (SPO) auto-abstain mechanism within 24 hours
* **Leandros:** Incorporate feedback from the Product Committee into the KPI document by next week’s meeting
* **Kevin & Neil:** Convene a dedicated session to draft the formal "Technical Concerns" statement regarding Constitution v2.4 for the Civics Committee
* **Bosko & Ryan Williams:** Update the hard fork timeline diagram based on the two-week shift in node readiness and share the link on GitBook
* **Ryan WIley:** Prepare the DRep compensation paper and the "off-chain process change request" proposal for detailed discussion next week
* **Sebastian:** Organize a dedicated technical session for the TSC to dive deeper into Linear Leios risk management<br>

| Topic                    | Discussion                                                                                                                                      | Notes                                                                                                                |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Linear Leios Update      | Sebastian provided an update from the monthly review. Progress includes an EBS (Endorsement Block Services) relay prototype on a small network. | A key concern is the "tail end" of the protocol: data storage duration and endorsement dissemination.                |
| Chain Growth Concerns    | Sebastian noted that Linear Leios could lead to gigabytes of chain growth per week.                                                             | Current estimates suggest 150 GB of storage growth over six days, necessitating SSDs for latency.                    |
| Benchmarking Risks       | Sebastian is worried that benchmarking for the Haskell ledger hasn't progressed enough to validate high transaction loads.                      | Risk mitigation is ongoing through simulations of network diffusion and ledger state creation.                       |
| Hard Fork Timeline       | Node v10.7 is the candidate for Protocol Version 11. Mid-to-late May 2026 is the tentative hard fork enactment date.                            | 10.6.2 was for testing Plutus primitives on SanchoNet but is not the final forking node.                             |
| Dijkstra (Next HF) Scope | The committee discussed starting a process to collect requirements for the "Dijkstra" hard fork.                                                | Ryan presented a proof-of-concept for an on-chain survey via info actions to rank community CIP priorities.          |
| 2030 KPIs Review         | Leandros presented the updated 2030 vision document, including protocol revenue, TVL, and chain density.                                        | Discussion focused on positioning Cardano competitively against top-tier chains like Solana and Ethereum.            |
| Chain Quality Metrics    | Leandros and Sebastian debated "Chain Density" vs. "Chain Quality."                                                                             | Neil suggested measuring "slack" on the happy path to see how much computation is wasted during failures.            |
| Parameter Updates        | Alexander reported that new Plutus cost models are being reviewed by the Parameter Committee, with a major meeting set for next Thursday.       | The previously failed CC min-size parameter change is currently being coordinated with Intersect.                    |
| CC Size Strategy         | Kevin noted feedback suggesting the community prefers increasing the number of committee members rather than lowering the minimum size.         | The Civics Committee will decide whether to elect new members to reach a count of eight or nine.                     |
| Constitution v2.4 Audit  | Kevin and Neil expressed frustration over the "messy" state of v2.4, citing a lack of clear diffs from v1.0.                                    | Concerns include "accidental changes" where preamble text was moved into guardrails, changing legal interpretations. |
| TVL Definition           | The Product Committee asked about including deposits and min-UTXO in the TVL definition.                                                        | The TSC viewed this as a marketing/positioning question rather than a purely technical one.                          |
| April 2026 Elections     | Five seats are open for two-year terms. The committee discussed how to handle the sixth seat left vacant by a recent resignation.               | Neil proposed co-opting the sixth-ranked candidate for the remainder of the vacant term.                             |
| TSC Budget Proposal      | Bosko and Kevin will work on a Miro board this week to package operational work packages for the budget committee.                              | The final proposal template is due in two weeks.                                                                     |
