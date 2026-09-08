# Meeting Minutes June 24, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | Yes        | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | No         | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Mike Hornan

\
Recording: [Technical Steering Committee - 2026/06/24 15:58 CEST - Recording](https://drive.google.com/file/d/12F4hddkXanUIhSDg-aVSH61-p97dcpta/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/06/24 15:58 CEST - Transcript](https://docs.google.com/document/d/1BzoOc1LtWo4wt0DdMbcLi33xScLj6oIM6jCcVZp1RHk/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/06/24 - Chat Transcript](https://drive.google.com/file/d/1n8i8jmmklrigo37BjoATKBUelHBA_x-5/view?usp=drive_link)

## Intros

**Christian Taylor:** Christian Taylor, TSC VC, Filecoin Foundation Governance, Founder / Open Source Cowboy, Advsior to Charli3, Andamio, Kai systems\
**Terence McCutcheon:** Terence 'Tex' McCutcheon - Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Member Advocate\
**Ryan (Cerkoryn):** Ryan Wiley, TSC Voting Member, Cybersecurity profressional\
**Udai Solanki:** Udai Solanki , member TSC , AIQUANT Technologies\
**Marcin Szamotulski:** Marcin Szamotulski, member TSC, IOG

## Agenda 24th June 2026

* Action Items from Last Meeting
* Discussion of SecondFi Issue
* Hard Fork Status
* Parameter Committee
* Budget Process
* Intersect: Planning and Reporting
* Technical Gating Requirements for Linear Leios
* Testnet Purposes
* Meetings Next Week
* AOB

## Decisions/Actions

**Decisions**

* **Meeting Cadence:** Rejected an Intersect suggestion to cancel next week's regular meeting for a "focus week," choosing to maintain the standard weekly technical cadence.
* **Wallet Mitigation Strategy:** Endorsed the safety recommendation that affected users perform a single-transaction fund migration to a clean wallet architecture rather than merely restoring seed phrases.
* **Budget Strategy Transparency:** Approved the principle of dynamically adjusting and scaling back sub-category funding allocations to maintain structural alignment with lower ADA exchange rates.

**Actions**

* **Christian:** Coordinate with Kevin via Slack to lock in a recurring weekly 30-minute alignment sync.
* **Christian:** Complete the comparative study isolating high-value quantum readiness frameworks across Algorand, Arbitrum, and Stellar by the end of the week.
* **Ryan:** Deliver the draft community questionnaire regarding the $K=1000$ parameter modification to the Parameter Committee a week from tomorrow.
* **Kevin:** Compile an outline promotion plan for the on-chain TSC budget proposal, integrating it directly with Intersect's marketing channels.
* **Kevin & Christian:** Formulate a presentation and participate in an upcoming Cardano Over Coffee Twitter Space next week to promote the on-chain TSC budget proposal.
* **All Members:** Review the Q2/Q3 quarterly slide decks and submit final tactical modifications before the time-lock deadline tomorrow.

<br>

| Topic                      | Discussion                                                                                                                                                                                                                            | Notes                                                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum           | Kevin opened the meeting and confirmed that seven elected members were present, satisfying the voting quorum requirement.                                                                                                             | Terence acted as secretary in place of Bosko, who is on leave.                                                        |
| Action Items Review        | Terence reviewed actions from the last meeting. Christian's written summary of Hart’s post-quantum talk is complete. Ryan's K parameter draft questions are in progress.                                                              | Neil will draft his counter-arguments after reviewing Ryan's draft.                                                   |
| SecondFY Wallet Security   | The committee discussed a recent wallet exploit involving misdirected funds. An ongoing white-hat operation is recovering funds. Users were advised to restore seed phrases in external apps and migrate immediately to a new wallet. | Further technical details and attack vectors were moved to an in-camera session to protect user security.             |
| Security Council Action    | Kevin proposed bringing the SecondFY wallet issue to the Security Council. While the wallet is external to Intersect, it presents a reputational and practical risk to the broader Cardano ecosystem.                                 | Mike confirmed that the security backlog currently stands at roughly 38 reports from the past two weeks.              |
| Hard Fork Readiness        | Ryan gave an update on the protocol version 11 hard fork. Node adoption is trending positively. Liquid exchange readiness is at 50.2% (climbing to 65% once Binance finishes upgrading).                                              | The Ogmios team deployed updated official versions of Ogmios and Koopo over the weekend, resolving fork dependencies. |
| Hard Fork Voting Status    | Hard fork execution requires 60% DRep approval and 51% active SPO votes (excluding auto-abstain). Current metrics show 40% DRep support and roughly 15% true SPO support.                                                             | Tooling discrepancies were noted: AdaStat and Cardano Scan track the metrics correctly, while CGV does not.           |
| Parameter Committee        | No formal Parameter Committee has met since last week. The upcoming meeting will prioritize the K=1000 expansion debate using the split pros/cons document being drafted by Ryan and Neil.                                            | The live Plutus cost model parameter update is scheduled for mainnet enactment tomorrow.                              |
| CC Size Reduction Vote     | The governance action to reduce the Constitutional Committee (CC) minimum size from 7 to 5 is live with 41% DRep support. It needs a 75% threshold to pass before its July 8th deadline.                                              | Tooling errors were flagged again, as AdaStat is incorrectly displaying the support level as 67%.                     |
| TSC Budget On-Chain        | The TSC budget proposal successfully passed the Ecclesia phase and was officially submitted on-chain yesterday evening.                                                                                                               | The committee must now pivot toward on-chain voting promotion.                                                        |
| Q2/Q3 Intersect Reporting  | Christian and Kevin presented the draft quarterly reports. Key Q2 milestones include the hard fork execution, Security Council reviews, and budget completions. Q3 focuses on post-quantum and Leios planning.                        | The deadline for feedback on the presentation slides is tomorrow, with finalization on Friday.                        |
| Bug Bounty AI Volume       | Mike and Terence reported a massive surge in bug bounty submissions (10–15 reports in the last two days alone), primarily driven by AI-generated reports.                                                                             | Most submissions focus on minor repository maintenance and documentation issues rather than severe structural bugs.   |
| Linear Leios Gating        | Kevin confirmed that Neil's technical mind map detailing linear Leios requirements was sent to the vendor's product manager and officially acknowledged.                                                                              | Kevin is drafting secondary gating criteria involving constitutional updates and guardrail analyses.                  |
| Testnet Node Policies      | The committee previewed a draft policy by Ryan Williams concerning whether testnets (Pre-Prod/Preview) should remain locked to production-ready nodes or opened to experimental builds.                                               | Alexander argued that testnets should be open to experimental testing to catch edge-case indexing bugs early.         |
| Budget Adjustment Strategy | Due to the drop in ADA price compared to original proposal projections, Kevin suggested scaling back activities dynamically or transferring unspent funds between categories.                                                         | The committee agreed that any shifting of funds must be communicated transparently to the community.                  |
