# Meeting Minutes March 25, 2026

## Attendees:&#x20;

| Name              | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ----------------- | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond     | Yes        | Chair           | Y                 | October 2026 |
| TBC               | No         | Vice Chair      | Y                 | October 2025 |
| Bosko Majdanac    | No         | Secretary       | N                 | N/A          |
| Tex McCutcheon    | Yes        | Alt - Secretary | N                 | N/A          |
| Nicolas Biri      | Yes        | Member/Seat     | Y                 | April 2026   |
| Duncan Coutts     | Yes        | Member/Seat     | Y                 | April 2026   |
| Sebastian Nagel   | No         | Member/Seat     | Y                 | April 2026   |
| Neil Davies       | Yes        | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | No         | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | No         | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Wilco van de Burgwal

Recording: [Technical Steering Committee - 2026/03/25 - Recording](https://drive.google.com/file/d/1wgNj2Ub_BSAxJe9HM3VzGy5Qv_Rtr1en/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/03/25 - Transcript](https://docs.google.com/document/d/1KokBQTkPpMH7D77Ku85s2Ca_PZudZwZfxzClfx5ivn0/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/03/25 - Chat Transcript](https://drive.google.com/file/d/1eF2hYfWrWsnHO76JcgOBvFrrvzJh6JUd/view?usp=drive_link)

## Agenda 25th March 2026

* Actions from the Last Meeting
* TSC Budget Proposal
  * Updates with Comments applied
  * Discussed with Intersect Staff, Changes applied
    * Now 4 WP's Intersect to take on software and TSC Workings
  * Presented to ISC, Execs, and Board Monday Mar 23
* Intersect Draft Budget
  * In preparation, still very early
* Parameter Committee Update
  * Plutus Cost Model
  * ccMinSize
  * Review of Plutus mem limit effect
* From CIP Farm to Hard Fork
  * CIP 179 - active/available on Mainnet
* Net Change Limit Governance Actions
  * CIP 173
* 2030 Vision KPI's
* van Rossem Hard Fork
  * Node 10.7.0 expected this week
  * Risk Register in preparation
* AOB

## Decisions/Actions

**Decisions**

* **Budget Restructuring:** Agreed to move "R\&D/Commissioned Reports" into Work Package 4 (Technical Review) and rename it to reflect a more serious R\&D focus.
* **Workshop Strategy:** Adopted a hybrid model with a preference for virtual sessions, limiting in-person workshops to 4 per year collocated with existing events.
* **Governance Priority:** Confirmed that Plutus cost model upgrades will be prioritized ahead of the CC minimum size reduction in the parameter change sequence.

**Actions**

* **Kevin & Udai:** Meet with Intersect representatives to clarify the division of security budgets between the Security Council, OSC, and TSC.
* **Kevin & Neil:** Collaborate on a revised proposal for "Professional Technical Reviews" that includes risk registers and higher due diligence standards.
* **Leandros:** Update the 2030 KPI document with the latest feedback from the Product Committee and share the community-driven initiatives memo.
* **Terence:** Share the confirmed time slots for the upcoming Election X-Spaces and Virtual Hub events in the chat/Slack.
* **Kevin:** Review the Node v10.7 pre-release notes and provide final TSC approval for the release.
* **Bosko:** Investigate the feasibility of an RSS feed for technical parameter updates to improve developer communication.
* **Bosko:** Coordinate a Doodle poll to schedule the private “Linear Leios Risk Management” deep dive with Sebastian.

<br>

| Topic                   | Discussion                                                                                                                                                   | Notes                                                                                                                     |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| Welcome & Quorum        | Kevin opened the meeting, noting that only five members were present due to several apologies. The meeting was not quorate.                                  | Ryan and others sent apologies; the meeting proceeded for information sharing.                                            |
| TSC Budget Proposal     | The budget was revised from five to four work packages, totaling $371,000. This aligns with other committee funding levels.                                  | The total Intersect budget is estimated between $7M and $10M.                                                             |
| Budget Pillars          | Kevin confirmed the TSC budget aligns with all five Intersect pillars, including infrastructure research, adoption, and sustainability.                      | Pillar 5 focuses specifically on ecosystem resilience.                                                                    |
| Security Response       | Udai suggested increasing the Security and Incident Response budget to at least $100k, noting that a single major incident could cost over $500k to contain. | Part of this budget is currently shared with the OSC (Bug Bounty) and Intersect central funds.                            |
| Technical Review Costs  | Neil criticized the $150 per proposal review rate as "laughable" for $5M delivery projects requiring deep due diligence.                                     | Kevin noted this benchmark was based on government research rates but agreed to refine the figures for delivery projects. |
| Post-Quantum Research   | Kevin highlighted Ethereum’s million-dollar investments in post-quantum research and moved this into a specialized "R\&D" work package.                      | This is critical for Cardano’s status as a security-oriented chain.                                                       |
| Workshops & Travel      | The plan includes 10 technical workshops (4 in-person, 6 virtual). In-person events will be collocated with major summits to save costs.                     | Nicolas emphasized remote-first to increase international attendance and reduce travel fatigue.                           |
| CC Minimum Size         | Kevin reported on the recommendation to reduce the Constitutional Committee (CC) minimum size from 7 to 5 members.                                           | The Civics Committee has agreed to move forward with this proposal to improve governance agility.                         |
| Plutus Cost Models      | Neil reported a potential issue: some existing script costs have increased. Transactions created with "lazy" fee calculations might fail.                    | These changes must be communicated clearly to DApp developers to avoid "red letter day" failures.                         |
| DRep Deposit (5 ADA)    | Benchmarking confirms the system can handle 5,000+ DReps. The 5 ADA deposit aims for global inclusivity.                                                     | There is currently no automated mechanism to refund the 495 ADA difference to existing DReps.                             |
| Node v10.7 Status       | Node v10.7 is in pre-release testing. A minor "breakage" occurred at the end of the previous day, but a fix is imminent.                                     | v10.7 is a precursor; Node v11 will be the official hard fork-capable version for Mainnet.                                |
| 2030 Vision KPIs        | The Product Committee is reviewing the TSC's proposed values. One member is pushing for more "community-driven" qualitative KPIs.                            | Leandros will share the specific memo regarding community-driven initiatives on Slack.                                    |
| Hard Fork Risk Register | The Hard Fork Working Group is populating a risk register based on lessons learned from previous upgrades.                                                   | This will be shared with the TSC for final technical vetting.                                                             |
