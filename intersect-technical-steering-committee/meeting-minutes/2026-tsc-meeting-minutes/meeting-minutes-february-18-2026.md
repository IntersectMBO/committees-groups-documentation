# Meeting Minutes February 18, 2026

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
| Neil Davies       | No         | Member/Seat     | Y                 | April 2026   |
| Alexander Moser   | Yes        | Member/Seat     | Y                 | April 2026   |
| Ryan Wiley        | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki      | No         | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh      | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Benjamin Hart
* Design Thyme
* Wilco van de Burgwal



Recording: [Technical Steering Committee - 2026/02/18 - Recording](https://drive.google.com/file/d/1U548JrpEOGFJP1VvV8BfSolMlMtljQab/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/02/18 - Transcript](https://docs.google.com/document/d/15h35oLAF6olLZxBjJqpBSVDf5bfokiP8z4rfTOrB0Ik/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/02/18 - Chat Transcript](https://drive.google.com/file/d/1pVZaDl1O6gBYzEmgKRu3V2Re1gbC0yJi/view?usp=drive_link)

## Intros

Kevin:  Kevin Hammond, TSC Chair, Ensurable Systems\
Sebastian: Sebastian Nagel, nCoding, IOE, Technical Architect\
Bosko: Senior Project Manager, Intersect Staff, TSC Secretary\
Tex: Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Liaison

## Agenda 02.18.26

* Actions from the last meeting
* Improving Technical Comms for HF etc.
* 2030 Vision KPI's
* Parameter Update Status
  * Plutus Mem Limit has Passed
  * How to proceed with ccMinCommitteeSize
* Constitution v2.4 Review
  * Review issues
  * Decide on actions
* Cardano Node Update
  * 10.6 Status
  * 10.7 Status
  * Daedalus likely to wait for 10.7/11.x
* TSC Operational Budget
  * Passed on to Intersect Delivery Team
  * Shared with ISC
  * ISC to organize a discussion session
* Questions from Product Committee about TVL
* dRep Compensation Paper
* Christian Taylor
* AOB

## Decisions/Actions

**Decisions**

* **Provisional Agreement on KPIs:** The committee accepted the initial KPI framework presented by Leandros, subject to normalizing the "Chain Density" metric to "Chain Quality."
* **Budget Socialization:** Kevin will continue socializing the budget with the Intersect Steering Committee (ISC) but will seek to move "proposal reviews" to a general Intersect line item.
* **Elections Questions:** The TSC confirmed that the existing election questions for technical seats remain valid and do not require immediate amendment for the April cycle.

**Actions**

* **Alexander:** Publish the X (Twitter) post regarding the SPO auto-abstain mechanism to the community.
* **Leandros:** Connect with the consensus/research team (Yorgos) to refine the Chain Quality metric for the 2030 vision.
* **Kevin & Neil:** Continue the technical audit of Constitution v2.4, focusing specifically on the guardrail text and immutability definitions.
* **Bosko:** Share the link to the three TSC-specific election questions on Slack for a final 48-hour review by the committee.
* **Ryan (C):** Present the DRep Compensation Paper for a dedicated discussion in the next TSC meeting.

<br>

| Topic                         | Discussion                                                                                                                                                                     | Notes                                                                                                                                                |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| SPO "Auto-Abstain" Post       | The committee discussed educating Stake Pool Operators (SPOs) on the mechanism to remove themselves from governance voting to reduce friction.                                 | Alexander is drafting a post for the TSC account to clarify this for large staking providers.                                                        |
| KPI Targets Review            | Leandros presented the refined KPI document, focusing on protocol revenue (30% annual growth target), Plutus script usage, chain density, and Total Value Locked (TVL).        | Target TVL set to $3B (mid-range chain) with a stretch goal of $9B (top-tier chain).                                                                 |
| Chain Density Metric          | Sebastian and Leandros debated the 5% chain density target. Sebastian noted 5% is the theoretical maximum given the active slot coefficient (f=0.05).                          | The metric will be normalized to "Chain Quality" (actual vs. expected blocks).                                                                       |
| Technical Comms: Hard Fork    | Leandros raised concerns that "security-only" upgrade bulletins lack detail, making it hard for SPOs to know what they are deploying.                                          | Kevin noted the challenge of balancing public disclosure with the risk of exposing vulnerabilities before a patch is adopted.                        |
| Security Council Outreach     | Sebastian suggested using GitHub's security advisory mechanism for more structured, private-by-default communication with node operators.                                      | Kevin will bring the issue of SPO notification improvements back to the Security Council.                                                            |
| Parameter Update Success      | Alexander confirmed the recent parameter update passed with 86% DRep support.                                                                                                  | This update invalidated a competing proposal to reduce the committee minimum size.                                                                   |
| Committee Minimum Size        | The group discussed the pushback against lowering the minimum CC size to 5. Some DReps prefer increasing the total number of CC members to boost decentralization.             | Sebastian suggested that adding a new member alongside a minimum size reduction might improve "marketing" of the change.                             |
| Constitution v2.4 Audit       | Kevin reported that v2.4 is technically "a mess," with 90 pages of diffs that are nearly impossible to audit.                                                                  | Neil and Kevin are struggling to verify if the changes are internally consistent.                                                                    |
| TSC Remit vs. Constitution    | Nicolas argued that legal/constitutional critiques are beyond the TSC's remit, while Kevin insisted technical inconsistencies in guardrails must be flagged.                   | The committee agreed to list technical issues (like immutability definitions) for future iterations (v3.0) rather than blocking the current version. |
| Node v10.7 Readiness          | Kevin updated that Node v10.7 will be the hard fork-capable version. v10.6.2 is Mainnet ready but will not be used for the fork.                                               | Daedalus is expected to wait for v10.7 or v11 before a major update.                                                                                 |
| Budget & Review Costs         | Nicolas and Sebastian questioned if the TSC should budget for reviewing all Intersect proposals. Both felt this is an Intersect executive obligation, not a TSC steering task. | Kevin increased the per-review estimate to $1,000 but will discuss shifting this responsibility back to the Intersect delivery team.                 |
| Departure of Christian Taylor | The committee acknowledged Christian Taylor's departure from Intersect and the Security Council.                                                                               | Christian was thanked for his foundational work in establishing the Open Source Committee (OSC).                                                     |
