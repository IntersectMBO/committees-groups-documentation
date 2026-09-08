# Meeting Minutes October 08, 2025

## Attendees:

| Name                     | Attendance | Role        | Voting Seat (Y/N) | Term         |
| ------------------------ | ---------- | ----------- | ----------------- | ------------ |
| Kevin Hammond            | No         | Chair       | Y                 | October 2025 |
| Adam Dean                | No         | Vice Chair  | Y                 | October 2025 |
| Terence ‘Tex’ McCutcheon | Yes        | Secretary   | N                 | N/A          |
| Markus Gufler            | No         | Member/Seat | Y                 | October 2025 |
| Nicolas Biri             | No         | Member/Seat | Y                 | April 2026   |
| Duncan Coutts            | Yes        | Member/Seat | Y                 | April 2026   |
| Jonathan Kelly           | Yes        | Member/Seat | Y                 | October 2025 |
| Sebastian Nagel          | Yes        | Member/Seat | Y                 | April 2026   |
| Benjamin Hart            | No         | Member/Seat | Y                 | October 2025 |
| Neil Davies              | Yes        | Member/Seat | Y                 | April 2026   |
| Alexander Moser          | Yes        | Member/Seat | Y                 | April 2026   |

Community/Other Attendees

* Christian Taylor
* Pi Lanningham
* Thomas Vellekoop



**Recording:** [Technical Steering Committee - 2025/10/08 - Recording](https://drive.google.com/file/d/1zWRuy6BNG8KcvdZck8PUlPIcUnWLfrCL/view?usp=sharing)

**Transcript:** [Technical Steering Committee - 2025/10/08 - Transcript](https://docs.google.com/document/d/1bW257zPi6i5jkQyCkvuvBFSPG3wQA7za21BI119Plwg/edit?usp=sharing)

**Chat Transcript:** [Technical Steering Committee - 2025/10/08 - Chat Transcript](https://drive.google.com/file/d/1vegJ648pQ7YJ0AZqpxh5WW0m-CwYVqd8/view?usp=sharing)

## Intros

**Adam:** OSC, TSC, CIP Editor, DripDropz LLC\
**Alex:** TBD\
**Ben:** TBD\
**Duncan:** TBD\
**Johnny:** Non-Custodial Co-Management SysOps Engineer (Tech Janitor) for 3 Mainnet\
Cardano SPO Clients. Keystone Ambassador. Voting Seat Member on Technical Steering\
Committee and Open Source Committee.\
**Kevin:**  TBD\
**Markus:** TBD\
**Neil:** TSC, Network Params, PNSol Ltd\
**Nicolas:** TBD\
**Sebastian:** TBD\
**Tex:** Open Source Program Manager (Intersect), GMC/MCC/OSC\
Secretary, Committee Liaison

## Agenda 10.08.25

* No chair was present at this meeting.
* Conversation focused around Ouroboros-Leios

## Decisions/Actions

**Decisions:**

* No decisions made as no chair was present. &#x20;

**Actions:**

* **CIP Write-up Clarity:** Sebastian to clarify the CIP's current write-up regarding whether new transactions are allowed in a Ranking Block (RB) when it contains an Endorsement Block (EB) certificate.
* **CIP Analysis & Quantification:** Neil and the R\&D Team (including Sebastian and Vashy) are to perform further analysis to quantify the frequency and magnitude of the Linear Leios overhead cost vs. benefit. This includes looking at historical data to estimate how often Leios would have provided improvement.
* **Simulation Data Improvement:** The R\&D Team (Sebastian) needs to generate improved simulation data, specifically a better model or visualization for the latency histogram (similar to Figure 9 in the DIP/CIP), to address concerns about the lack of predictability in transaction delays across different load scenarios.
* **Strategic Rationale Update:** Duncan will put a comment on the pull request, and Sebastian should ensure the SIP's rationale is updated. The goal is to clearly articulate why Linear Leios is the right intermediate step and how it contributes to the long-term strategy for scalability and economic sustainability.
* **Future Discussion:** The team agreed to schedule a future discussion to cover the concerns about asymmetric resource attacks and related attack vectors that Neil raised.

| Topic                                 | Discussion                                                                                                                                                                                                                                                                                                                                                                           | Notes                                                                                                                                                                    |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Meeting Logistics                     | Duncan confirmed the recording was started. Neil asked for a clear question or agenda, noting the small group size (six people).                                                                                                                                                                                                                                                     | Recording is active. Small, technical discussion on Leios.                                                                                                               |
| CIP Discussion Context                | Sebastian set the stage: the time was used for a technical discussion on Leios since there was no set agenda. Neil and Duncan had time to look at the CIP (Cardano Improvement Proposal). Sebastian acted as a proxy for the R\&D team.                                                                                                                                              | Focus on the Leios SIP. Sebastian acts as R\&D proxy.                                                                                                                    |
| Concerns on Linear Leios Behavior     | Neil discussed concerns about the likely detailed behavior of the proposed linear Leios. He noted that the current formulation involves work that is likely to be thrown away, which is not good systems engineering and could cause issues, specifically, longer delays compared to Preos by itself.                                                                                | Neil: Linear Leios may result in wasted work (EBs thrown away) and longer delays than Preos.                                                                             |
| Wasted Work and Delays                | Sebastian asked for precision on "wasted work" and "longer delays." Duncan clarified that wasted work is the Endorsement Blocks (EBs) being thrown away after production and voting. Sebastian confirmed this means re-announcement and re-voting are necessary.                                                                                                                     | Wasted work = EBs, voting, and dissemination that are invalidated. Longer delays occur for transactions in the wasted EBs.                                               |
| Leios-Preos Boundary Behavior         | Neil stated that if everything fits inside a Ranking Block (RB) (a Preos block), the system behaves just like Preos and never issues an EB—a desirable property according to Sebastian.                                                                                                                                                                                              | When load is low (fits in an RB), Leios should behave like Preos.                                                                                                        |
| Behavior at Slight Overload (Example) | Neil presented a case: mempool has an RB's worth plus 50% extra. An EB is generated. Neil argued that because of the Poisson distribution of block arrivals, an RB will appear before the EB is incorporated at least 50% of the time, making the EB work waste.                                                                                                                     | At 150% Preos load, 50% of the time, the EB work is wasted due to a new RB arriving first.                                                                               |
| RB Containing EB Certificate          | Neil discussed the case where the EB work is done. The protocol says a new RB should contain the certificate for the previous EB but no new transactions. Sebastian noted that the SIP's current write-up is unclear if other transactions are allowed alongside the certificate, but his understanding is that it's mutually exclusive for better protocol security.                | When an EB is certified, the next RB contains the certificate, potentially excluding transactions.                                                                       |
| Transaction Inclusion Delay/Latency   | Neil argued that at 150% Preos load, when an EB is successfully incorporated, the transactions that arrived during that time (the extra 50% and any new arrivals) experience a longer delay/higher latency compared to if it were a Preos implementation.                                                                                                                            | Leios can introduce higher latency for transactions compared to Preos under certain load conditions.                                                                     |
| Low Load EB Generation                | Neil asked if EBs would ever be generated at 10% Preos load. Duncan and Neil agreed it would occur rarely due to the Poisson distribution—a long gap between RBs can still fill the mempool enough for an EB. Neil noted this means Leios would be paying costs even at low load.                                                                                                    | Due to Poisson block arrivals, EBs can be generated even at very low (10%) load.                                                                                         |
| EB Diffusion Complexity               | Jonathan asked for a "sense check" on EB diffusion: it’s an optimistic protocol where only "gaps" (missing transactions) are fetched and validated, but these gaps become more significant at higher loads. Neil agreed, highlighting that fetching missed transactions introduces an expensive network delay.                                                                       | EB diffusion relies on optimistic fetching, but missed transactions incur significant network delay/cost, eating into the validation time budget.                        |
| System Unpredictability               | Neil raised a major system engineering concern: the protocol's probabilistic choice to operate in different modes (Preos-like or Leios-like) makes the system's behavior, specifically latency, less predictable than the current Preos system.                                                                                                                                      | Leios's non-deterministic operation modes will lead to worse predictability and wider distributions of transaction times.                                                |
| Leios Payoff/Turning Point            | Sebastian acknowledged the boundary load case (100-200% Preos load) where Preos would outperform Leios. He asked if Leios would always be better than Preos at very high loads (e.g., 20x Preos capacity) where Preos cannot serve the demand. Neil disagreed, stating that the issue is not simply throughput, but the continuous change in probabilities and unpredictable delays. | Leios is expected to be better at very high loads, but Neil is concerned about the unpredictable nature of delays at all load levels, which drives away rational actors. |
| Leios Strategy and Scalability        | Duncan raised a big-picture strategic question, worrying that linear Leios, while providing an intermediate capacity increase (e.g., 5x Preos), doesn't move the ecosystem closer to genuinely scalable designs, as users are not forced to adapt. Sebastian noted the motivation is economic sustainability.                                                                        | Duncan is concerned that Leios is a good intermediate step for capacity but may not push the ecosystem toward true, long-term scalability.                               |
