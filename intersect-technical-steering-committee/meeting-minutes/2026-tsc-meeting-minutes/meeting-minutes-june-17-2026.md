# Meeting Minutes June 17, 2026

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
| Alexander Moser    | No         | Member/Seat     | Y                 | April 2028   |
| Ryan Wiley         | Yes        | Member/Seat     | Y                 | October 2026 |
| Udai Solanki       | Yes        | Member/Seat     | Y                 | October 2026 |
| Leandros Holleman  | Yes        | Member/Seat     | Y                 | October 2026 |
| Seungheon Oh       | No         | Member/Seat     | Y                 | October 2026 |

Community/Other Attendees

* Ken-Erik Ølmheim<br>

Recording: [Technical Steering Committee - 2026/06/17 - Recording](https://drive.google.com/file/d/1STxyQMEjEmfkNcyariZ45batRnP5uyUX/view?usp=drive_link)

Transcript: [Technical Steering Committee - 2026/06/17 - Transcript](https://docs.google.com/document/d/1Agxlm8OgOTFuQ23Wda5d8As3nWmig26KQSvcy6_RrPs/edit?usp=drive_link)

Chat Transcript: [Technical Steering Committee - 2026/06/17 - Chat Transcript](https://drive.google.com/file/d/1QSxumJPXUe-MIHJiw2-Ubbfczc5j95Qq/view?usp=drive_link)

## Intros

* **Terence McCutcheon:** Terence 'Tex' McCutcheon - Open Source Program Manager, Intersect Staff, OSC Secretary, Committee Member Advocate
* **Bosko Majdanac:** Senior Project Manager, Intersect Staff, TSC Secretary
* **Christian Taylor:** VC TSC, Filecoin Foundation Governance, OS Cowboy Cosnulting etc
* **Marcin Szamotulski:** IOG, TSC member
* **Ryan Wiley:** TSC Member, Cybersecurity Professional
* **Leandros Holleman:** VS TSC,CTO @GenWealth, SPO@BSP, Founder@KeyPact, Memeber@CardanoSPA
* **Udai Solanki:** member TSC and OSC, AIQUANT Technologies
* **Neil Davies:** PNSol, TSC

## Agenda 17th June 2026

* Actions from the last meeting
* Chair Election Voting Outcomes
* Hard Fork Status
* Parameter Committee
* Budget Process
* Technical Gating Requirements for Linear Leios
* Testnet Purposes
* Post-Quantum Crypto
* Intersect: Focus, Planning and Reporting
* AOB

## Decisions/Actions

**Decisions**

* **Election Ratification:** Accepted the official election results confirming Kevin as Chair and Christian as Vice Chair.
* **Balanced Parameter Strategy:** Approved a strategy to present a split "case-for" and "case-against" document to the community regarding the $K=1000$ change to foster an informed vote.
* **Reporting Delegation:** Voted to grant the Chair and Vice Chair full structural autonomy to compile, refine, and submit the quarterly Q2/Q3 Intersect planning report on behalf of the whole TSC.

**Actions**

* **Christian:** Generate a written analytical summary of Hart’s post-quantum presentation utilizing available transcripts while Hart remains traveling.
* **Ryan:** Complete the draft list of technical evaluation questions concerning the $K$ parameter expansion to distribute to the broader community.
* **Neil:** Draft the formal counter-argument text detailing the negative infrastructure implications of a $K=1000$ change to accompany Ryan's questionnaire.
* **Kevin:** Follow up with the core vendor’s product and engineering management teams to track the response regarding the Leios linear gating requirements.
* **Christian:** Set up a recurring weekly 30-minute alignment sync with Kevin to offload the Q3 strategic reporting and deliverables timeline from the main committee.
* **Christian:** Conduct a comparative review of quantum readiness frameworks from other active blockchain networks (such as Algorand, Arbitrum, or Stellar) to isolate high-value approaches.

<br>

| Topic                    | Discussion                                                                                                                                                                                                    | Notes                                                                                                                        |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Meeting Leadership       | Christian chaired the meeting as acting lead. Kevin was absent from the call to observe his birthday.                                                                                                         | The committee noted they had a sufficient voting quorum present to proceed with business.                                    |
| TSC Leadership Elections | The committee noted that the formal leadership elections have officially concluded. Kevin has been re-elected as the TSC Chair.                                                                               | Neil noted a procedural discrepancy regarding a sub-rule requiring seven votes, but the outcome stands.                      |
| Raising K to 1000        | Ryan detailed the ongoing Parameter Committee debate regarding raising the K parameter to 1000. Primary concerns include increased infrastructure costs and questionable efficacy.                            | Ryan is drafting a list of questions for community feedback. Neil will write a counter-argument to balance the presentation. |
| In-Camera Leios Review   | Neil confirmed that the highly technical system integrity feedback compiled during last week's closed, in-camera session is currently in the process of being shared upstream with the core vendor.           | Further progress on these requirements is paused pending a formal response from the vendor's management.                     |
| Mainnet Hard Fork Status | Bosko reported that following async Slack ratification by the TSC on Monday, the protocol version 11 hard fork governance action was officially submitted on mainnet yesterday.                               | Early voting data shows 10% DRep support and minor SPO support, with zero "No" or "Abstain" votes recorded so far.           |
| Hard Fork Contingencies  | The earliest possible mainnet ratification date is June 23rd, with the absolute earliest enactment date landing on June 28th.                                                                                 | Bosko is building out a resource tracker to coordinate on-call technical support across IOG, CF, and Intersect.              |
| Ecosystem Readiness      | Exchange readiness for the hard fork is currently tracking at 25%, while overall DApp and ecosystem tooling readiness sits between 65% and 70%.                                                               | Mainnet block production data indicates that version 11 nodes are currently outputting between 81% and 88% of all blocks.    |
| Parameter updates        | The live Plutus cost model parameter update is tracking on schedule and is officially slated for mainnet enactment tomorrow.                                                                                  | The separate Constitutional Committee size reduction action remains open on-chain.                                           |
| Treasury Withdrawals     | Terence shared an update from the Intersect Steering Committee confirming that the ongoing mainnet hard fork implementation will not delay the processing of upcoming treasury withdrawal governance actions. | Treasury actions are expected to go live by the end of this week or early next week.                                         |
| Quantum Crypto Plan      | The topic was briefly discussed but ultimately tabled due to the absence of the presentation's author, Ryan Williams.                                                                                         | Alonzo highlighted a link in the TSC channel referencing Stellar's recently published quantum preparedness plan.             |
| Q3 Strategic Planning    | Bosko outlined the requirement for the TSC to submit a Q2 achievements slide and a Q3 strategic priority focus board to the Intersect Committee by June 29th.                                                 | Neil proposed that the committee's existing structural cadence already meets these requirements.                             |
