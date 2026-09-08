# Focus Group - SPOs - 3rd April 2025

## Data Points

* [Session recording](https://drive.google.com/file/d/1qvHpdhHPHBfDrPTAnS84t6Uq-ryYlV8y/view?usp=sharing)
* [Transcript](https://docs.google.com/document/d/1Arwxv6ScErQrZ-s36D1kOcuj54FB8kY10fYeZnsJsR4/edit?tab=t.0#heading=h.3tppjgxuspn)
* [Notes](https://docs.google.com/document/d/1WEtd5BgWvpkgiKWGP43ww6UpW8EoTquIBMYQwq3um3M/edit?tab=t.0#bookmark=id.ijivza89lqtt)

## Key Learnings

### 🏗️ User Issues & Running a Node

* Installation is easy for experienced SPOs, but less so for newcomers.
* Voting as an SPO is risky & labour-intensive (moving hot/cold keys); inconsistent methods add complexity.
* Dead pools with inactive stake are a persistent problem — they reduce network efficiency and distort staking incentives.
* SPO profitability is under threat:
  * Decline in staking rewards faster than new fee mechanisms can compensate.
  * Negative feedback loop: less staking participation → fewer rewards → less staking.
  * Lack of users; difficulty attracting new delegators.
* Competition from exchanges & other networks makes it hard to attract/retain delegators.
* Staking is currently competing with dApps for user capital — staking being "risk-free" discourages capital use in dApps.

***

### ⚖️ Incentives & Sustainability

* Profitability must stay above operating costs for SPOs; current reward trajectory is unsustainable.
* Rewards should be more balanced across market cycles — current system makes it hard to sustain pools long-term.
* Proposal to adjust reward calculation to eliminate negative feedback loop:
  * Emit full rewards each epoch without returning any portion to reserves.
  * Would stabilize rewards & improve short-term viability.
* Compound rewards on lost ADA is a long-term risk — may require expiring delegation certificates to avoid distortion.
* Pledge is seen as capital inefficient — ideas to de-emphasize its role.
* Min margin vs min pool cost:
  * Broad support for moving toward a min margin model instead of min pool cost.
  * Both parameters could be maintained short-term and governed via DReps.
* Reducing taxes from 20% to 10% suggested to help improve delegator rewards and attractiveness.

***

### 🚀 Business Opportunities & Network Expansion

* Partnerchains/sidechains could offer additional revenue, but concerns:
  * Complex, requires matching ADA market cap for impact.
  * Seen as potentially harmful (as with Ethereum’s fragmentation).
  * Rollups (with settlement on L1) preferred over standalone partnerchains.
* Direct fiat on/off ramps not seen as a blocker today — most SPOs already manage this via exchanges.
* Direct stablecoin swaps (USDC/USDT) would be helpful for operational flexibility, but not critical.
* Stake pool business model will need new revenue streams:
  * Examples include staking derivatives, stable pools, rollup infrastructure, partnerchain security.
  * Without new products, SPO business model may become unsustainable.

***

### 📢 Marketing & Growth

* Paid marketing is not effective for SPOs:
  * Low ROI; acquiring single users not worth the cost.
  * Personal branding & visibility are the best tactics.
* A better on-chain experience is needed:
  * New wallets should better guide users toward staking.
  * Better pool discovery UX needed (current approach too hidden/technical).
* General Cardano marketing to new users (staking as utility) more useful than marketing individual pools.

***

### 🌐 Infrastructure & Decentralization

* Bare metal setups are preferred when feasible:
  * More cost-effective in the long run.
  * Avoids risks of cloud centralization.
  * Hybrid models (bare metal + cloud failover) commonly used.
* Cloud-only setups offer good block propagation but harm decentralization if used too broadly.
* Future bandwidth demands (e.g. from Mithril, LAOs, etc.) may make bare metal more attractive.
* Suggestion to allow optional node compilation (modular builds) to avoid bloated binaries & improve security.

***

### 🛠️ Future Parameter Changes & Governance

* Reduce saturation (K) or rethink how K is used.
* Priority to improve delegator rewards.
* Desire for more rapid iteration of key parameters (K, taxes, reward models).
* Governance process (DRep voting) currently seen as suboptimal for managing operator-specific parameters like fees.
