# May 18th, 2026 Budget Comm Minutes

### Budget Committee Weekly Meeting — May 18th, 2026

**Date:** May 18, 2026 **Time:** 09:00 EDT

**Attendees:**

Christina Gianelloni (visitor), Colleen O'Beirne (Cardano Foundation), Eric Helms (SCATDAO), Fanny Wijaya, Jose Velazquez, Kristijan (Chris) Kowalsky, Lloyd Duhon (Secretary), Megan Hess (Chair), Nicolas Cerny, Otávio Lima, Rodrigo Pacini, Seun Gbiri, Simo Simovic (Project Manager), Stephen Wood (Cardano Foundation)

**Quorum:** Confirmed.

> **Context:** Two main items: (1) whether to move from **two bundled treasury withdrawals** to **single treasury withdrawals per passing proposal**, now that Intersect's operational constraint has lifted; and (2) a walkthrough of the committee's new **open-source proposer funding-history tool**. The committee chose to consult the community via X before voting on the withdrawal-structure change next week.

***

### 1. Treasury Withdrawal Structure — Single vs. Bundled

Simo raised the question of how passing proposals should be submitted as treasury withdrawals — individually or bundled. (Jack was not needed; this is a Budget Committee decision.)

#### 1.1 Simo's Recommendation — Single Withdrawals

Simo's personal recommendation is to proceed with a **single treasury withdrawal per proposal**:

* **DRep sentiment:** Two bundled proposals that were submitted **did not pass**. DReps left rationale on Summit and elsewhere indicating they dislike bundling — including some who supported the budget process and voted yes but asked for single proposals, and some who did not support the process and said single submissions matter to them.
* **Fairness and odds:** Single withdrawals for each proposal that clears Ecclesia are fairer and more likely to pass; bundling risks losing time on proposals unlikely to clear.
* **Room in the info action:** The approved info action already states the treasury-withdrawal criteria "**will be reassessed depending on the current position of the NCL, volume of proposals**," etc. — so reassessing is within scope, though it would still be a change from what the info action specified (two withdrawals).

Lloyd clarified the mechanics: changing this requires a **motion** — to move from two treasury-withdrawal governance actions (per the info action) to **a single treasury-withdrawal governance action per proposal that clears the 67% threshold** at the Hydra voting stage.

#### 1.2 Discussion

* **Nico:** Initially opposed changing it — the two-withdrawal approach was approved in the info action and chosen deliberately (Intersect could not operationally facilitate individual withdrawals at the time, _and_ it was discussed and accepted by DReps). Now that the operational constraint is gone, pivoting isn't inherently bad, but it must be done **carefully** to avoid the perception of arbitrary process changes "decided by an unknown cabal." He urged consulting DReps/community (X, Discord) first, as was done originally.
  * **NCL math:** On-chain treasury-withdrawal requests currently total **\~281 million ADA**; the NCL has **\~282 million ADA**, leaving roughly **1 million ADA** if everything currently live were approved (unlikely). Given this, bundled items are very unlikely to pass anyway.
  * **Counterargument (Nico):** Moving everything to individual withdrawals partly **defeats the purpose of the process** — anyone could have submitted directly from the start. The process's value is its filter, the structured feedback, and that proposers can rely on Intersect rather than sourcing the 100K ADA deposit themselves. **DRep voting fatigue is real**, and more individual proposals adds to it.
* **Rodrigo:** Prioritize **clear communication** and guidelines. Last year there was community confusion/backlash over voting options (e.g., the best-voted option not reaching 50% support). Clarity will make the community more comfortable.
* **Megan:** Individual withdrawals could be seen as a **structured onboarding** path — the Ecclesia poll as the first check, the treasury withdrawal as the second — which is close to the original info-action design and may be where the community ultimately wants to go.
* **Lloyd:** The Ecclesia poll is also an **attentional magnet** that gets proposals (especially from smaller community groups with no other route) in front of DReps and generates structured feedback. Even proposals that don't reach 67% benefit from the feedback loop and can pursue funding later on their own. Lloyd noted he has personally favored bundled budgets (standard corporate practice), but acknowledged many in the community disagree, and if that is the majority and the committee has the capability, it can move that way.

#### 1.3 Outcome — Community Consultation Posted

Rather than vote immediately, the committee agreed to publish an **X post** (drafted live, refined with member input — Eric flagged defining the **TWWGA** acronym on first use; Nico, Rodrigo, Simo, and Jose caught the **67%** figure) explaining that the operational constraint that originally blocked individual withdrawals is gone, that the info action allows reassessment, and asking the community whether to switch to single TWWGAs per proposal or keep bundling. The post was **published** during the meeting for members to amplify from their own accounts.

> **Note:** This cannot be turned into an Ecclesia poll on short notice — feedback will be whatever can be gathered on X over the coming week. A Klesia/Ecclesia poll requires lead time to assemble and deploy.

***

### 2. Proposer Funding-History Tool (Catalyst / Treasury History)

Lloyd demoed the tool the committee asked for last week, built between Thursday and Friday and shared with the committee on Friday.

* **Repo-backed and open source:** A public GitHub repository with fetch scripts pulling data from Lidonation, Catalyst, the Treasury, Intersect's previous rounds, and the current Intersect round — normalized into a machine-readable dataset.
* **Licensing:** Software is **MIT**; data is **CC-BY (attribution)** because it contains Catalyst data (attributed back to Catalyst and to Darlington's dataset).
* **Three views:**
  * **Group explorer** — click a proposer to see prior funding history and what they received; proposers with no prior funding appear as outliers.
  * **Proposal ledger** — proposal-by-proposal: who, how much requested, how much ADA received previously, and ties to Catalyst/prior budget rounds.
  * **Sankey** — funding flow from Project Catalyst or Treasury Fund 1 to recipients.
* **Identity bridge:** A CSV that maps old proposer names to new ones (e.g., MLabs, Rare Network variants) so funding can be consolidated; several manual links are included where history is known, all visible in the repo.
* **In progress (target this week):** A **scope-similarity** report that scores whether each of the 69 current proposals resembles something previously proposed and funded — the second half of the delegated reporting work.

Reception was strong (Eric, Megan, Christina) — praised as unbiased, information-only tooling. Data corrections were already surfaced (e.g., Five Binaries, Insurable Systems as bundled/renamed groups). Lloyd emphasized this is **the committee's tool, not his**, and brought it to the committee first specifically so name-matching could be corrected before any public release.

#### 2.1 Contribution Path

* **Rodrigo** (newly joined the Cardano Ambassadors program, doing content/research) offered to research overlapping proposers and track records across different names. Lloyd showed where contributions go — primarily improving the **identity bridge** CSV under the repo's reports/data; no developer skills required, just better data.
* **Christina** offered to send known bundled-group mappings.
* The committee can vote to make the tool fully public and post it from the committee's X account (≈2-hour posting delay applies). Christina offered to amplify once cleared.

***

### 3. Committee's Own Budget Proposal — Feedback Status

Lloyd reviewed the committee's own proposal: officially **only one comment so far** (from Dimitri).

* Members who have received feedback through other channels should **add it to the proposal**, link it in Discord for visibility, and — importantly — ask those people to **post their feedback in the Hydra voting app** so it is tracked.
* Publicly written feedback should be shared to the **committee Discord** so all members can see it (private DMs need not be disclosed).
* There is still time to make changes to the proposal if feedback warrants. The committee will **prepare a reply to Dimitri's comment for the Wednesday (May 20) working session**, along with any other feedback gathered in the wild. (Consensus: unlikely the committee would ask for _more_ budget — "we can do a lot with a little.")

***

### 4. Action Items

| Action                                                                                              | Owner                           | Notes                                                   |
| --------------------------------------------------------------------------------------------------- | ------------------------------- | ------------------------------------------------------- |
| Amplify the X consultation post on single vs. bundled treasury withdrawals                          | All members                     | From individual accounts; gather feedback for next week |
| Be ready to vote on the withdrawal-structure change (single TWWGA per passing proposal at 67%)      | Committee                       | Next Monday, after a week of community feedback         |
| Collect and share community feedback (X/Discord) ahead of the working session                       | All members                     | Bring to Wednesday May 20                               |
| Improve the proposer funding-history tool's identity bridge (old↔new name mappings)                 | Rodrigo / Christina / community | e.g., Five Binaries, Insurable Systems                  |
| Finish the scope-similarity report scoring the 69 proposals against prior funded proposals          | Lloyd                           | Target this week                                        |
| Decide on/vote to make the funding-history tool fully public and post from committee X              | Committee                       | \~2-hour posting delay                                  |
| Add externally received feedback to the committee proposal; ask sources to post in Hydra voting app | All members                     | Keep feedback trackable                                 |
| Share publicly written proposal feedback to the committee Discord                                   | All members                     | Visibility for all members                              |
| Draft a reply to Dimitri's comment on the committee proposal                                        | Lloyd / committee               | Prepare for Wednesday May 20                            |

***

### 5. Adjournment

With no further business and several members due at the Intersect Steering Committee call immediately after, Lloyd closed the meeting early. He asked members to collect community feedback and any requested tool changes for the **Wednesday, May 20 working session**, reiterating that the funding-history tool belongs to the committee.

**Headline outcomes:**

* **Single vs. bundled treasury withdrawals:** Simo recommended moving to single withdrawals per passing proposal; the operational constraint that forced bundling has lifted. Rather than vote immediately, the committee **published an X consultation post** and will **vote next Monday** after gathering community feedback.
* **NCL is nearly exhausted:** \~281M ADA in on-chain requests against \~282M ADA NCL — roughly **1M ADA** of headroom if all current items passed; bundled items are very unlikely to clear regardless.
* **Process value reaffirmed:** Even with a possible shift to individual withdrawals, the Ecclesia stage provides a filter, DRep attention, structured feedback, and removes the 100K ADA deposit burden from proposers — but voting fatigue is a real counterweight.
* **New open-source funding-history tool demoed** — repo-backed (MIT software / CC-BY data), with group explorer, proposal ledger, and Sankey views, plus an identity bridge for name reconciliation; scope-similarity scoring in progress. Brought to the committee first for data correction before public release.
* **Committee proposal feedback is thin** (one comment, from Dimitri); members to surface external feedback into the proposal/Discord/Hydra and prepare a reply for Wednesday.

Meeting adjourned after **00:54:39**.
