# Meeting Minutes August 26, 2026

## Attendees:&#x20;

| Name               | Attendance | Role            | Voting Seat (Y/N) | Term         |
| ------------------ | ---------- | --------------- | ----------------- | ------------ |
| Kevin Hammond      | Yes        | Chair           | Y                 | October 2026 |
| Christian Taylor   | No         | Vice Chair      | Y                 | October 2026 |
| Bosko Majdanac     | Yes        | Secretary       | N                 | N/A          |
| Tex McCutcheon     | Yes        | Alt - Secretary | N                 | N/A          |
| Marcin Szamotulski | Yes        | Member/Seat     | Y                 | April 2028   |
| Alonzo Benavides   | Yes        | Member/Seat     | Y                 | April 2028   |
| Neil Davies        | Yes        | Member/Seat     | Y                 | April 2028   |
| Alexander Moser    | Yes        | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ken-Erik Ølmheim

\
Recording: [Technical Steering Committee - 2026/08/26 - Recording](https://drive.google.com/file/d/1yxiwephuT-4uG-7uAssQ46kOf74CzYBo/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/08/26 - Transcript](https://docs.google.com/document/d/1buNCkBq1RB_dgh-sFR_3mWTrsEs2C3bXKEQrvweL-8o/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/08/26 - Chat Transcript](https://docs.google.com/document/d/1buNCkBq1RB_dgh-sFR_3mWTrsEs2C3bXKEQrvweL-8o/edit?usp=sharing)

## Agenda 26th August 2026

* Actions from the last meeting
* Dijkstra era hard fork
* Serialisation Library
* Technical Steering Committee Budget
* Post Quantum Cryptography
* Parameter Committee
* AOB

## Decisions/Actions

**Decisions**

* **CIP 50 Parameter Discussion:** Agreed to include the CIP 50 max pledge leverage parameter proposal in the upcoming Parameter Committee agenda alongside K parameter discussions.
* **Budget Items Deferred:** Formal approval of serialization library funding, post-quantum crypto items, and specific budget contract templates was deferred to the following week's meeting.

**Actions**

* **Neil:** Locate and comment on the PR regarding larger max transaction execution units in linear layers vs. ranking blocks (requesting assistance via message if needed).
* **Neil:** Provide the written "case against" argument for the K=1000 action document to complete the draft before Ryan's upcoming absence.
* **Bosko:** Confirm with James whether the budget finalizing step was explicitly completed.
* **Bosko:** Share the Node Diversity Workshop (London, Nov 12–13) PDF deck/link with the committee.
* **Bosko/IO:** Circulate the single canonical Dijkstra scope document to the community, tool providers, SPOs, and exchanges.
* **Kevin:** Follow up with vendors to clarify the explicit sequence of network wire protocol versions, CDDL completion dates, and release numbers (11.2 vs. 11.3).
* **Leios team/Bosko:** Leios team to respond to technical concerns raised by TSC
* **Kevin:** Circulate the list of proposed Technical Report topics (governance thresholds, quantum crypto, security reviews, etc.) on Slack.
* **Kevin:** Share details on travel support calls for Token 2049 (Singapore) and the Node Diversity Workshop (London) via Slack.

| Topic                                      | Discussion                                                                                                                                                                                                                                                                                                                                            | Notes                                                                                                                            |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Meeting Opening & Agenda Review            | Kevin opened the Technical Steering Committee meeting on August 26, 2026. The committee confirmed six voting members were present, establishing a quorum. Alex and Marcin had no additions to the agenda.                                                                                                                                             | Agenda pinned in channel; meeting proceeded with confirmed quorum.                                                               |
| Action Items & SPO / DREP Voting           | Bosko and Alex reviewed past actions regarding SPO and exchange outreach for governance voting. Alex confirmed outreach is active and newsletter drafts were sent. Kevin noted an upcoming DREP call right after the meeting to encourage engagement.                                                                                                 | SPO voting engagement remains a critical focus area.                                                                             |
| Linear Leios PR Review                     | Neil tried to locate a PR concerning larger max transaction execution units in linear Leios vs. ranking blocks. He expressed concern that larger transactions allowed in linear blocks could get stranded during fallback conditions if they cannot fit in ranking blocks.                                                                            | Neil will attempt to find the PR again with assistance; Kevin noted Alex may have already raised this point.                     |
| Node Release Sequence & Protocol Versions  | The team debated node versions (11.1.1, 11.2, 11.3), protocol versions (Version 12), and network wire protocol versions. Neil highlighted risks in changing wire/CDDL formats without proper sequencing, warning that mismatched versions could delay node rollout. Marcin noted no PRs currently bump the network version from 15 (16 experimental). | Clarification needed from vendor on exact sequence of network protocol, CDDL, and node release versions.                         |
| Budget & ADA Value Updates                 | Bosko brought up outstanding budget questions linked to James's domain. Kevin noted a short delay wasn't harmful as the ADA value had actually increased.                                                                                                                                                                                             | Bosko to confirm explicit status once James provides updates.                                                                    |
| Dijkstra Hard Fork Scope & Delivery Plan   | Ryan outlined the current state of Dijkstra scope work, Plutus V4 ledger interfaces, CDDL timelines (\~3 weeks estimate), and DBsync integration. Kevin emphasized the need for a single canonical source for the Dijkstra scope (frozen by end of August) rather than multiple circulating drafts.                                                   | Vendors provided version 2.1 of the plan, though concerns remain over timeline feasibility and feature completeness definitions. |
| Governance Risks & CC Election             | Ryan shared that with 6 days remaining, SPO voting for the Constitutional Committee update stands at only \~51% (needing 67%). Kevin, Bosko, and Ryan discussed the massive risk of governance freezing if the action fails, which would delay parameter updates, hard forks, and constitutional amendments by at least 35–45 days.                   | Contingency plans (e.g., resubmitting with rationale adjustments) are being evaluated internally by Intersect.                   |
| Linear Leios Technical Concerns            | Neil raised unresolved technical risks regarding linear leios, including block settlement timing spikes seen on testnets (previously >10s, now reduced) and the lack of a defined mechanism to disable linear leios if issues arise.                                                                                                                  | Neil advocated for a strict, formal risk log to keep vendors accountable for technical dependencies.                             |
| TSC Technical Reports & Studies            | Kevin proposed several topics for potential technical reports/reviews: governance thresholds, post-quantum cryptography, linear leios impacts, alternative node security impacts, performance concerns, and ecosystem security reviews.                                                                                                               | Kevin to circulate the proposed report list on Slack for committee input.                                                        |
| Parameter Committee: Minpool Cost & K=1000 | Alex reported that the minpool cost proposal faces low participation similar to the CC update. Ryan drafted the neutral body and "case for" K=1000 info action; Neil is providing the "case against."                                                                                                                                                 | Ryan will be away in a month, so completing the info action draft promptly is high priority.                                     |
| CIP 50 Integration (Max Pledge Leverage)   | Ryan mentioned CIP 50 was approved forDijkstraDystra and proposed introducing a parameter for max pledge leverage (L) alongside K parameter discussions to handle stake shifts simultaneously.                                                                                                                                                        | Topic to be forwarded to the Parameter Committee agenda for next week.                                                           |
| Travel Support & Upcoming Events           | Kevin proposed opening technical travel support calls for two events: Token 2049 in Singapore (October 2026) and the Node Diversity Workshop in London (November 12–13, 2026).                                                                                                                                                                        | Committee expressed general agreement; details to be shared via Slack.                                                           |
