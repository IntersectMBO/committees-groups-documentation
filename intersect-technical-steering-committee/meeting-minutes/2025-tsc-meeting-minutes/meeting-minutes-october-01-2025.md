# Meeting Minutes October 01, 2025

## Attendees:

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | Yes        | Chair       | Y                 | October 2025 |
| Adam Dean                | No         | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Lorenzo Bruno            | Yes        | Secretary   | N                 | N/A          |
| Markus Gufler            | Yes        | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | Yes        | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | No         | Member/Seat | Y                 | October 2025 |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | Yes        | Member/Seat | Y                 | April 2026   |

Community/Other Attendees

* Christian Taylor



**Recording:** [Technical Steering Committee - 2025/10/01 - Recording](https://drive.google.com/file/d/1xlyCoGiPJx-xmBKMzaDuMxMQ286h7kLr/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/10/01 - Transcript](https://docs.google.com/document/d/1jDnTU-A_p0d1qV9I42O0EFbLe547ZHfNLWOt6wrVNkY/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/10/01 - Chat Transcript](https://drive.google.com/file/d/1Up2x2JjkvaPIDHE2gCSs7c1GWDtlGtse/view?usp=sharing)

## Intros

**Adam:** OSC, TSC, CIP Editor, DripDropz LLC\
**Alex:** TBD\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:**  TBD\
**Lorenzo:** TBD\
**Markus:** TBD\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TBD\
**Sebastian:** TBD\
**Tex:**  Open Source Program Manager (Intersect), GMC/MCC/OSC Secretary, Committee Liaison

## Agenda 10.01.25

* Actions from the last meeting
  * Feedback on IOR progress report
* Hard Fork Working Group Update - Kevin
* TSC Committee Budget - Open Discussion
* Slot battle discussion with SPOs - Duncan C
* Security Council Bug Bounty Nomination for Mike Hornan - Christian
* maxTxExecutionCost\[memory] Parameter Change - Alex/Kevin
* 2030 Vision - Adam
* Committee Election Process - Tex/Lorenzo

## Decisions/Actions

**Decisions:**

1. **Reformation of Hard Fork Working Group (HFWG):** Agreed to reform the HFWG.
2. **Max TX Unit Parameter Change (Plutus Parameter):** The proposal to confirm the recommendation to update the Plutus protocol parameter for max TX units and issue it as an on-chain governance action was carried unanimously by the TSC.

**Actions:**

1. **Provide Input to IOR Progress Review:** All attendees are to provide input on the IUR progress review.
2. **Hard Fork Working Group (HFWG) Reconvening:** The HFWG will reconvene with a meeting at the end of October.
3. **Progress Governance Action:** Kevin is to approach Intersect, specifically Ryan Williams, to progress the on-chain governance action for the Plutus parameter change. (Neil offered to take over if Kevin is unavailable.)
4. **SPO Advocacy (Slot Battles):** Small SPOs were advised to proceed with writing a Cardano Problem Statement (CPS) to clearly state the problem and engage with IOG's incentives team (e.g., Carlos) for potential solutions.

| Topic                                           | Discussion                                                                                                                                                                                                                                      | Notes                                                                                                                                                                                                                                                                           |
| ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Follow-Up Session for Discussion                | Sebastian requested time for open Q\&A/discussion. Kevin agreed, suggesting a follow-on session for deeper details, which was Chris's initial idea for the SIP editors' meeting.                                                                | A follow-on session may be needed to cover details, as the current meeting is to be kept short.                                                                                                                                                                                 |
| Meeting Structure & Agenda                      | Kevin proposed starting the meeting right away to stick to the short timeframe, filling in late joiners later, which was agreed upon. Kevin shared the agenda.                                                                                  | Agenda was shared and pinned in the channel. Proposal to keep the meeting short to attend the layoffs monthly meeting.                                                                                                                                                          |
| Review of Previous Minutes & Actions            | Kevin brought up the minutes from the last meeting and necessary actions. Terence provided an update on pending actions.                                                                                                                        | Action to provide feedback on the IUR progress report was noted. Terence confirmed links were emailed. Other actions included: Carlos invited to the parameter committee, recruitment input for security incident manager role, and postponement of the slot battle discussion. |
| IUR Progress Review Input                       | Kevin set an action for all attendees to provide input on the IUR progress review.                                                                                                                                                              | Action: All attendees to provide input to the IUR progress review.                                                                                                                                                                                                              |
| Hard Fork Working Group (HFWG) Update           | Kevin met with Terence, Christian, Jessica (IO), and Matt (Intersect) and agreed to reform the HFWG. Discussion included the time-based release proposal (met favorably) and procedures.                                                        | Proposal is to reconvene the HFWG starting at the end of October with a small core group, a slow cadence (approx. 4 weeks), increasing frequency closer to the hard fork deadline.                                                                                              |
| HFWG Scope and Procedure                        | Initial HFWG topics will cover the scope of next and subsequent hard forks (seeking community buy-in), assessment timelines, and the increasingly complex enactment steps. Zamal prepared an outline timeline.                                  | The HFWG needs to include tool developers, exchanges, and other node versions developers early in the process for coordination.                                                                                                                                                 |
| Node Versions Discussion                        | Ben mistakenly asserted Amaru was used in production. Alex clarified it's not production-ready, but Sebastian noted Pallas (used by Scrolls and as a foundation for Amaru) is used in production for infrastructure (like Okamio and Koopo).    | Confirmed Pallas and similar infrastructure pieces are in production and should be included in discussions, categorized as "tool chain followers."                                                                                                                              |
| HFWG Scheduling                                 | Sebastian inquired about the HFWG schedule. Kevin stated the HFWG would have autonomy, but the initial meeting time would be fixed. Terence mentioned previous HFWG meetings were scheduled an hour before the release meeting.                 | Timing needs to balance US and European time zones. Terence offered to coordinate with Christian and work around Intersect staff availability.                                                                                                                                  |
| Working Group Calendar Visibility               | Sebastian asked about a central calendar for working groups. Terence stated the Intersect Events Calendar populates Discord (showing 14 days upcoming) and the Events Dashboard for a longer view. Terence controls updates to these calendars. | Discord's events summary is the public reference, though its two-week limit is a problem for irregular meetings. Terence is working to improve the calendar visibility issue.                                                                                                   |
| Max TX Unit Parameter Change (Plutus Parameter) | Alex formally proposed that the TSC confirm the Parameter Subcommittee's recommendation to update the Plutus protocol parameter for max TX units, which was seconded by Neil.                                                                   | The proposal was carried unanimously by all eight voting members. Action: Kevin will approach Intersect (specifically Ryan Williams) to progress the on-chain governance action. Neil offered to take over if Kevin is away.                                                    |
| Slot Battle Discussion Update                   | Duncan reported back on his conversation with small SPOs who were unhappy about slot battles and proposed reversing a change to reintroduce a bias favoring smaller SPOs in VRF chain ordering.                                                 | Duncan advised them to write a Cardano Problem Statement (CPS), stating the problem clearly, to seek community consensus and engage with IOG's incentives team (like Carlos) for potential solutions, possibly on the reward side rather than block production.                 |
| Security Council Bug Bounty Nomination          | Christian raised the Open Source Committee's (OSC) desire to compensate Mike Horn for his vulnerability disclosure before the program's full launch, making it the first payment of the bug bounty program.                                     | Budget allocation is anticipated to be between $5k to $10k, with the Security Council making a recommendation to the TSC and OSC.                                                                                                                                               |
| TSC Operational Budget Proposal                 | Kevin informed the group that the TSC could potentially put forward its own budget proposal for operational costs (e.g., HFWG support, technical town halls) with the board's agreement.                                                        | This was raised as a possibility for future discussion in Slack or later meetings.                                                                                                                                                                                              |
