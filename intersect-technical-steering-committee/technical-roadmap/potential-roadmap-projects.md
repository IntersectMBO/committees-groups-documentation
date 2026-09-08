# Potential Roadmap Projects

The following project cards have been submitted by the community and technical working groups and have been triaged through the [Core Infrastructure Roadmap working group](https://committees.docs.intersectmbo.org/intersect-product-committee/working-group/core-infrastructure-roadmap-working-group).

This process reviews and validates the information provided before being inclusion on the following list for community prioritization.

{% hint style="info" %}
Note, these project cards are subject to revision and update by the project champion at any time until the project becomes committed.&#x20;
{% endhint %}

***

### Automatic Formal Verification

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: This proposal is an automated formal verification tool to prove that DApps do not exhibit any security vulnerabilities and behave as expected across all scenarios. It will offer the possibility to automatically generate properties showing absence of common security vulnerabilities and deadlocks. For specific business logic, users are only required to annotate their smart contracts with the expected requirements. It will automatically and mathematically prove the correctness of the DApp against all possible blockchain events or return a set of blockchain events leading to a requirement violation or an exploited vulnerability. Although aimed at Plinth in 2025, the tool’s core is adaptable to any other smart contract languages by the simple addition of a translator module.

**Problem Statement**: DApps in Cardano, expressed as several smart contracts interactions, lack accessible formal verification tools, posing security risks that can lead to severe economic loss. Current testing tools fall short in capturing all possible execution scenarios, leaving vulnerabilities open to exploitation. As for existing formal verification tools, they rely on the manual use of proof assistants that require high level of expertise.

**Benefit**:&#x20;

* Verification automation: Automatic generation of security requirements and automatic verification
* Higher Code Quality: Guarantees contracts perform as intended.
* Comprehensive Scenario Coverage: Reduces missed vulnerabilities, costly bugs and exploits
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Stefano Leone

**Product Goal**: Meet the needs of apps

**Dependencies**: [Lean4](https://github.com/leanprover/lean4/), [Z3](https://github.com/Z3Prover/z3) (or other SMT solvers, e.g., [CVC5](https://github.com/cvc5/cvc5), [Alt-Ergo](https://github.com/OCamlPro/alt-ergo/))

**2025 Deliverable**:

* Core Reasoning framework: Plinth-Lean4 formalization, complex optimizations, Lean to SMT translators; Counterexample generator&#x20;
* Blockchain formalization: State transition system, blockchain events, plutus-ledger API, ledger state and rules
* Universal Annotation language: Formal specification describing syntax and semantics with temporal operators
* Plinth Bridge: Transpiler of Plinth and annotations to Lean4; Generation of common vulnerability properties; Lean4 to Plinth for counterexample representation at source code level

**Readiness (Current -> Target)**: SRL 3 -> SRL 7

**Estimated Effort**: 5.5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/14ancSUqAxVbevIH9CbRCLcp28V364VAO/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Babel Fees

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: We propose implementing Nested Transactions, a change to the current ledger design to support a specific kind of transaction batching. This design supports swap intents, by allowing individual transactions in a batch to be unbalanced, but the full batch itself must be balanced. We interpret Babel fees as swap intent. We include several related ledger changes for the purpose of demonstrating the extensibility of this framework to support additional kinds of intents, inclusion of which in the production implementation is optional.

**Problem Statement**: Users who do not hold Ada are not able to easily interact with the Cardano blockchain at this time because they cannot pay transaction fees, supply min-UTxO Ada for each UTxO, or provide collateral for engagement with scripts. Support is needed to allow such users to seamlessly use non-Ada tokens for those purposes.

**Benefit**: If implemented, this feature will (1) bring in Ada-less users, (2) make multi-user, multi-UTxO asset swaps cheaper, faster, and with less contention (3) be a step towards supporting arbitrary intents
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Polina Vinogradova

**Product Goal**: Get more usage | Attract dApps and users

**Dependencies**: (1) finish work on currently planned preceding hardforks (2) finalize any other features planned for the HF which will include Nested Transactions

**2025 Deliverable**: Integration of this feature into mainnet

**Readiness (Current -> Target)**: SRL 4 -> SRL 6

**Estimated Effort**: _Not Provided_
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/15b9TRU9F2QsyeP4YyuJlaOX5W7ZdSPe_/view?usp=drive_link" %}
{% endtab %}
{% endtabs %}

***

### Cardano Node Architecture Refresh

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Discovery and proof-of-concept phase to re-architect the Cardano node in a modular, event-based model to achieve greater scalability in accessibility, extensibility and throughput.

**Problem Statement**: The current Cardano node, while successful, has a centralised codebase with limited understanding and input from the community, and is perceived to be difficult to extend and integrate with.  Looking forward to Leios we will also require greater horizontal scalability.

**Benefit**: A modular architecture will allow the node to be split into smaller, more understandable components, which can be developed by independent teams in any suitable language, and released with their own cadence. The message interfaces between components will be clear, simple and language-independent, making it easier to add new functionality and to integrate applications. Components will be packaged in standard ways making it easier and more flexible to deploy and scale.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Ricky Rand

**Product Goal**: Meet the needs of apps

**Dependencies**: None

**2025 Deliverable**: Proof of concept of a modular node with limited functionality;  architecture and roadmap reports;  a well-functioning coalition of development partners.

**Readiness (Current -> Target)**: SRL 0 -> SRL 4&#x20;

**Estimated Effort**: 5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1y53mEwcxAqdHfxB-2OqnHTHe9GRWTWTd/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Cardano Wallet/GraphQL

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Funding for maintenance and development on a full node wallet for Cardano. Full node wallets are some of the more secure types of wallet, limiting the amount of trust a user has to place on other parties.

**Problem Statement**: The ecosystem needs a choice for a fully featured full node wallet. The legacy offering of Daedalus does not seem to be maintained anymore. And it now lacks governance functionalities, leaving Cardano users behind.

**Benefit**: _Not Provided_
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: _David Clarke_

**Product Goal**: Governance

**Dependencies**: _Not Provided_

**2025 Deliverable**: _Not Provided_

**Readiness (Current -> Target)**: _Not Provided_

**Estimated Effort**: _Not Provided_
{% endtab %}
{% endtabs %}

***

### Decentralised Oracle

{% tabs %}
{% tab title="Project Abstract" %}
**Please note this project is pending review from the CIR working group.**

**Description**: The decentralised oracle is a mechanism for publishing off–chain data such as price feeds so that it can be used by smart contracts. Operated by a network of data providers, the oracle can be used by any dapp, requiring only a small amount of work to integrate new data sources and use them in smart contracts.

**Problem Statement**: Most dapps need data from the outside world in order to function. Existing oracle solutions require trust in some centralised entity. The decentralised oracle provides vital data in an open, transparent, trustless, reliable and price-efficient manner.

**Benefit**: All who build on Cardano will have access to a high-quality design and implementation of the trustless oracle without charge. SPOs will have the chance to become oracle operators, giving them financial rewards and visibility. Users of dapps that consume oracle data will benefit from low fees and high trust.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Jann Muller

**Product Goal**: Get more usage | Easier to build on and to use Cardano

**Dependencies**: Two preliminary designs will be produced by Jan 2025. A highly qualified team is in place to start working on this in 2025.

**2025 Deliverable**: The entire project will be finished in 2025. The product will be deployed to mainnet and used by (at least) the Djed stablecoin.

**Readiness (Current -> Target)**: SRL 2 -> SRL 9

**Estimated Effort**: 4.5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1f1ZmG2D4BGieQ5dMXhb3T5RePm_T6gqY/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Decentralised Stablecoin

{% tabs %}
{% tab title="Project Abstract" %}
**Please note this project is pending review from the CIR working group.**

**Description**: The Djed stablecoin has operated reliably on mainnet since its release in January ‘23, with its codebase establishing a good reputation (having multiple audits and zero incidents). This project will (1) publish the source-code of the Djed stablecoin and (2) add a feature to Djed to allow multiple operators to process stablecoin orders in a decentralized way

**Problem Statement**: Stable coins are crucial for the evolution of blockchain development, as they facilitate client interactions using familiar currencies, but crucially without the risk of exchange drift. Cardano currently lacks an open source, decentralized algorithmic stablecoin, preventing it from realizing its full potential as a first class blockchain .

**Benefit**: App developers can inspect the source code as a best-practice example, and build integrations with other apps. Operators (eg. SPOs) will benefit from transaction fees and the Cardano community at large will be able to use a reliable, fully decentralized, algorithmic stablecoin.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Jann Muller

**Product Goal**: Get more usage | Easier to build on and to use Cardano

**Dependencies**: DJD-2 will benefit greatly for a decentralized oracle (DJD-1), but is not strictly dependent on it. The catalyst project “secure upgrade mechanism” will also be beneficial but is not strictly required.

**2025 Deliverable**: The Djed source code, including a mechanism for independent operators to participate in the protocol.

**Readiness (Current -> Target)**: SRL 7 -> SRL 9

**Estimated Effort**: 5.5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1cDYMUMh2t1WYXWU0eutT9QdYYnbZ4vY6/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Governance Improvements

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: The Civics Committee and other parties have identified a number of improvements that could be made to on-chain governance and related social governance procedures. These include a reward scheme for DReps, ways to record budget information on-chain, improvements to submissions, extensions to automate additional guardrails, and tracking governance action dependencies. This project will identify key concerns and focus effort on addressing these in a timely manner.

**Problem Statement**: As experience grows with Cardano on-chain Governance following Chang#2, improvements will need to be made to increase the effectiveness of the governance system, address social governance priorities, and to address any shortcomings that are identified in practice. This will maintain a healthy open governance system.

**Benefit**: The community will benefit from a governance system that evolves to meet its needs.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Adam Rusch

**Product Goal**: Governance

**Dependencies**: Following Chang#2, a CPS needs to be written to identify key community concerns, supported by one or more CIPs to address specific technical issues that arise from the CPS.

**2025 Deliverable**: Deployment of the new governance features to a public test environment, such as SanchoNet. Identification of future governance enhancements.

**Readiness (Current -> Target)**: SRL 5 -> SRL 7 &#x20;

**Estimated Effort**: 8 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/15tOBffNCCdAwsRp7Z8TC5WN8IlhQ7Wst/view" %}


{% endtab %}
{% endtabs %}

***

### Hydra Development

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Hydra is a L2 scaling solution, an isomorphic multi-party state channel. This enables a fixed set of people to create an off-chain ledger with custom parameters, execute transactions and smart contracts, and only settle agreed upon states, to L1, incrementally and upon closure.

**Problem Statement**: The decentralization and security of Cardano relies on trade-offs that introduce friction points for developers and users, like throughput restrictions, finality time, transaction costs and growing storage requirements for SPOs.

**Benefit**: Hydra heads allow effectively unlimited scaling, and the reduction/removal of friction points that currently restrict adoption, like transaction fees, settlement times etc. Hydra heads benefit from the properties of the Cardano ledger, while allowing customization to application specific requirements.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Trym Bruset

**Product Goal**: Business as usual

**Dependencies**: None

**2025 Deliverable**: Hydra head version 1 + audit, ecosystem development support for Gummiworm, Hydrozoa, and other applications to drive adoption, including business development.

**Readiness (Current -> Target)**: SRL 6 -> SRL 9

**Estimated Effort**: 8 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1yeE07gx7KAtvnj5veF12Klp9ph7zTQLn/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Ledger App Rewrite

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Work with Ledger team to design new UI according to the [expectations](https://docs.google.com/document/d/1AKwX7xoKL0w4ZX9rK5On1px1kGqC6FOabrlSV2SfrrA/edit?usp=sharing). Implement new UI into the Cardano Ledger App. Pass the external audit process (costs for this shall be included in proposal). Support the Ledger team by the release process.

**Problem Statement**: In 2018 when Ledger Cardano App was developed, there was no standard for embedded app UI. Over the years this changed and now Cardano is the only Ledger application with non-standard UI such as requiring double-click several times during the confirmation process. This is causing confusion among users and problems with testing because the design is not compatible with the testing suite.

**Benefit**: Ledger wallet users will have better Cardano experience. Further app updates and releases will be faster due to testing suite compatibility.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Michal Petro

**Product Goal**: Business as usual

**Dependencies**: None

**2025 Deliverable**: Full release to production

**Readiness (Current -> Target)**: SRL 3 -> SRL 9&#x20;

**Estimated Effort**: 0.5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1K3EqEbhk-hWPGf7FzJ6xXU1TR0ZTxsSX/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Log-Structured Merge (LSM) Trees - Reduce Node Memory

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: This is a proposal to move the UTxO set and other data structures on disk to reduce the memory required to run a node. It’s broken into 3 phases, to move UTxO on-disk using LMDB which is currently in progress. This phase cannot be used on relays or block producing nodes. Phase 2 is to migrate LMDB to the custom LSM library developed by supplier Well-Typed. Phase 3 is to identify other parts of ledger state that can be migrated to reduce memory further.

**Problem Statement**: SPO node memory use exceeds available resources or increases SPO and other operator costs to unacceptable levels.

**Benefit**: If implemented, this will enable Cardano to reach Bitcoin scale in terms of the number of users & wallets and the size of the UTxO set. At the same time SPOs nodes and full node wallets will be able to function on commodity hardware, including cheap cloud instances.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor:** Duncan Coutts

**Product Goal:** Business as usual

**Dependencies:** Completion of LSM libraries by supplier Well-Typed

**2025 Deliverable:** The integration of the new backend with the existing consensus layer of the node

**Readiness (Current -> Target):** SRL 6 -> SRL 9&#x20;

**Estimated Effort:** 6 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1I2aaw32bPJ4ldTfjccC8twqU6cHz3bJQ/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Mithril Development

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Mithril enables secure, decentralized access to blockchain data without requiring a full node. It is a protocol that works alongside the Cardano blockchain, executed by stake pool operators.

**Problem Statement**: Accessing the Cardano blockchain securely requires running a resource-intensive full node, which not all users can afford or prefer to do. This limits accessibility and decentralization, pushing many users to rely on centralized intermediaries to interact with the blockchain.

Addresses [CIP-0137](https://cips.cardano.org/cip/CIP-0137) | Decentralized Message Queue

**Benefit**:&#x20;

* Faster bootstrapping and sync times for full node applications,
* Secure and efficient access for light clients such as light wallets and mobile apps,
* Enhanced L2 protocols (like Hydra, partner chains, and bridges),
* and enabling Cardano through scaling protocols such as Peras and Leios.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Reza Baram

**Product Goal**: Get more usage | Easier to build on and to use Cardano

**Dependencies**:&#x20;

* Cardano’s network layer (Networking team)
* Mini-protocols for Mithril communication (TxPipe and Cardano Node teams)

**2025 Deliverable**:&#x20;

* Decentralized signature diffusion
* Decentralized Signer registration
* Incentive Model

**Readiness (Current -> Target)**: SRL 6 -> SRL 9

**Estimated Effort**: 6.5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1XNrM5bMAzgGyhR4Y-NV5SjZuI2vtMj4C/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### New Anti-Grinding Measure

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: This initiative focuses on enhancing the Ouroboros Consensus Layer by increasing the difficulty for adversaries to execute grinding attacks, while imposing minimal overhead on honest participants in the Praos leader election process. Specifically, we will explore cryptographic alternatives for the η-nonce computation and provide updated recommendations for the security parameter K, currently set to 2160 blocks (approximately 12 hours)

**Problem Statement**: A grinding attack occurs when network leaders manipulate block additions to improve their chances of re-election as future leaders. The Ouroboros protocol includes anti-grinding measures, but these protections often impact settlement times and finality. Furthermore, grinding attacks are CPU-based, meaning their effectiveness escalates as CPU power becomes more accessible and affordable. This prompts the question: can we enhance settlement times and finality while maintaining robust defenses against the evolving threat of grinding attacks?&#x20;

Addresses 2 CPS - [CPS-0017](https://github.com/cardano-scaling/CIPs/blob/settlement-cps/CPS-0STL/README.md) | _Settlement Speed_ + New CPS | _Countermeasures for CPU-Based Attacks_

**Benefit**: Significant reduction in time needed to finalise blocks on chain and/or requiring more resources to perform a grinding attack
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Kevin Hammond

**Product Goal**: Gets more usage | Attract dApps and users

**Dependencies**: None

**2025 Deliverable**: A “Proposed” CIP detailing the pros and cons of various cryptographic primitive alternatives. This includes the implementation and benchmarking of the selected cryptographic primitive, a structured "Recipe for Setting the Security Parameter 𝐾" an impact analysis on the Consensus & Ledger repository, and an updated formal specification in Agda of the consensus layer.

**Readiness (Current -> Target)**: SRL 1 -> SRL 4&#x20;

**Estimated Effort**: 4 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1UOS0xafdRUyI_5FuxypoW3T--swQFvsz/view?usp=drive_link" %}
{% endtab %}
{% endtabs %}

***

### Ouroboros Leios

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Whereas in a classical blockchain the block bodies directly contain transactions, in Leios the block bodies can also contain references to Endorser Blocks which themselves contain references to so-called Input Blocks containing the actual transactions. Those references are certified through a voting mechanism that guarantees a majority of validators agree on the content of Endorser Blocks.

**Problem Statement**: The Cardano mainnet occasionally experiences congestion where there are too many transactions in the memory pool to be included in the next block or in the next few blocks. Sometimes the block utilization peaks above 90% for an extended period of time. Emerging use cases and application deployments promise to accelerate the need for high throughput on Cardano.

Addresses [CPS-????](https://github.com/cardano-foundation/CIPs/pull/925) Greater Transaction Throughput #925

**Benefit**: Increase transaction throughput on Cardano mainnet by orders of magnitude.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Brian Bush

**Product Goal**: Gets more usage | Attract dApps and users

**Dependencies**: None

**2025 Deliverable**: Implement multi-node simulations that are formally verified to be faithful to the Leios protocol; develop and release to the community the analysis and visualization tools to quantify Leios behavior and performance; estimate Leios techno-economics and quantify Leios throughput.

**Readiness (Current -> Target)**: SRL 2 -> SRL 6&#x20;

**Estimated Effort**: 7 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1hmS0Q9gvJQtOba1mE_ZaNE496-k7SZUt/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Ouroboros Peras

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Peras modifies the chain-selection rule to include the “boosting” of the dominant chain's blocks by a quorum of votes from periodic randomly-selected voting committees. It modifies the chain-selection rule, the CDDL of the block body, and the creation, transport, and verification of votes and the certificates that witness a quorum of votes. It adds several new protocol parameters.

**Problem Statement**: Existing and emerging Cardano use cases would greatly benefit from faster "settlement" or "finality" of transactions. Moreover, some current and pending use cases are hampered or blocked by not having transaction settlement within minutes of including of a transaction in a block.

Addresses [CPS-0017](https://github.com/cardano-scaling/CIPs/blob/settlement-cps/CPS-0STL/README.md) | _Settlement Speed_ + [CIP-????](https://github.com/cardano-foundation/CIPs/pull/872) | Ouroboros Peras - Faster Settlement #872

**Benefit**: Peras reduces settlement time by orders of magnitude without weakening the existing security guarantees. It is compatible with Leios and Genesis, and does not significantly impact node resources.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Brian Bush

**Product Goal**: Gets more usage | Attract dApps and users

**Dependencies**: None

**2025 Deliverable**: Initially, a concrete plan to add Leios support to the Cardano node. Depending on the result of that plan, some part of implementation may also be done.

**Readiness (Current -> Target)**: SRL 5 -> SRL 9&#x20;

**Estimated Effort**: 5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1Jfk5E3oz5ij_3SOVWrG3RT8qVHntZ6_1/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Partner Chains

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Partner Chains toolkit empowers Cardano SPOs to validate and produce blocks for specialized blockchains directly connected to Cardano. This enables SPOs to increase their earning potential while actively contributing to the expansion and diversification of the Cardano ecosystem. By introducing native cross-chain transaction capabilities, Partner Chains enhance scalability and foster seamless interoperability with EVM-based applications, significantly boosting the connectivity and utility of the Cardano network.

**Problem Statement**: Improving the scalability and interoperability of the network

**Benefit**: Unlock new revenue streams for Cardano SPOs and supercharge the ecosystem's growth by enabling scalable, cross-chain Partner Chains that enhance connectivity and interoperability across blockchain networks.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Anita Jovic

**Product Goal**: Gets more usage | Attract dApps and users

**Dependencies:**&#x20;

* Integration with Cardano network protocols - LibP2P.
* Compatibility with EVM-based applications and tools.

**2025 Deliverable**: Midnight Mainnet Launch, Minotaur multi chain staking implemented across Cardano and Ethereum, FastBFT implementation in PC substrate node, cross chain communication design

**Readiness (Current -> Target)**: SRL 6 -> SRL 9&#x20;

**Estimated Effort**: 15 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1AnKwK-E6mI-l7F1_ZpjNn3gsnUEAG0DT/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Proof of Useful Work

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Use the training process of deep learning as “useful work” for validators to elect a block producer ensuring traceability of dataset and models trained, and obtained accuracy.

**Problem Statement**: AI model training and fine-tuning processes are largely opaque, with limited visibility into training datasets, feature engineering, and optimization techniques. While some organizations build in the open, most models lack comprehensive documentation about their training methodology and data sources, making it difficult to assess their reliability and biases.&#x20;

**Benefit**: Cardano blockchain becomes a solution for open and transparent training for AI. SPOs and their delegators get rewards through a Partner Chain running Minotaur consensus.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Romain Pellerin

**Product Goal**: Gets more usage | Attract dApps and users

**Dependencies**: Depends on Minotaur consensus (PoW in PoS) and Partner Chains for prototyping.

**2025 Deliverable**: We expect to progress this to SRL4. Deliverables: research paper, simulations, formal specs, early prototype in Partner Chain framework.&#x20;

**Readiness (Current -> Target)**: SRL 1 -> SRL 4&#x20;

**Estimated Effort**: 5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1sHLkw8OUqUKpU4Ji2WHZn7Vrs0r-QV_5/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Property Based Testing Tool&#x20;

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: The Plinth Property-Based Testing Tool is designed to perform property-based testing on Plinth smart contracts. By automatically generating a wide range of inputs and actions to test against the specified properties of a contract, it ensures that the contract behaves as expected. This tool helps developers identify edge cases, validate assumptions, improve contract robustness, and check against known vulnerabilities. It integrates seamlessly into the Plinth development workflow, enabling more rigorous and automated testing, ultimately enhancing the reliability and security of Plinth scripts.

**Problem Statement**: Cardano lacks any property-based testing (PBT) tools, leaving smart contracts vulnerable to undetected edge cases and potential security flaws. Our proposal will bring a PBT tool for Plinth, setting a new standard for automated testing, enhancing contract reliability, and bridging a critical gap in Cardano’s security infrastructure.

**Benefit**:

* Reduced Financial Losses: Prevents costly bugs and exploits.
* Increased Confidence: Builds trust in Cardano’s smart contracts.
* Enhanced Code Quality: Boosts contract robustness.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Stefano Leone

**Product Goal**: Meet the needs of apps

**Dependencies**: Quickcheck library/Emulation libraries

**2025 Deliverable**: CLI tool, VSCode, Documentation.

**Readiness (Current -> Target)**: SRL 3 -> SRL 7

**Estimated Effort**: 4 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1QgkGE7oC0osYRR8nxYWv2DtvbxExKnWI/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Revised Stake Pool Incentive Scheme

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Several proposals have been made to adjust the current stake pool incentives scheme. A particular concern is that of providing smoother incentives for smaller pools. This project will investigate this important issue, considering the merits of existing proposals, identifying possible improvements to the current scheme with costs/benefits, and outlining a development plan if successful.

**Problem Statement**: Smaller stake pool operators, especially those with single pools, are unable to compete with larger, especially multi-pool operations. This reduces diversity and choice, making it harder for new pools to enter the Cardano ecosystem.

**Benefit**: The community will benefit from greater diversity in the stake pool offering, with healthier small pools. Stake pools will benefit from fairer treatment.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Kevin Hammond

**Product Goal**: Governance

**Dependencies**: None

**2025 Deliverable**: Design evaluation/discovery that can lead into further implementation if successful. Small changes to the existing incentives scheme, if appropriate

**Readiness (Current -> Target)**: SRL 2 -> SRL 5&#x20;

**Estimated Effort**: 1 FTE
{% endtab %}
{% endtabs %}

***

### Rust Node (Amaru)

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: Amaru is an open-source project that aims to build a new fully interoperable block-producing node for improving the overall performance the Cardano blockchain. The Amaru node provides a simplified entry point for building things on Cardano by using a modular design and Rust as its main coding language. Amaru wants to bring diversity and operational resilience to the Cardano network, improve the overall performance with no compromise regarding security and focus on operator experience by having a modular design.

**Problem Statement**: Running a Cardano node today means you have one single point of failure: the Haskell node, Amaru wants to solve the client diversity problem. On top of that, running a node takes a lot of resources and you can’t run it easily on ARM setups. Experimenting with the node, interoperability and customisation is hard with the opacity of the current design.

**Benefit**:&#x20;

* Lower the total cost of ownership of running a Cardano node
* Modular architecture to customize the execution of the node and tailor it to the operator needs
* Documented features and architecture allowing builders to build efficiently around each component
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Damien Czapla

**Product Goal**: Get more usage | Easier to build on and to use Cardano

**Dependencies**: None, but interfacing with projects will be key to insure interoperability

**2025 Deliverable**:

* Full phase 1 and phase 2 validation
* Hard fork combinator integration
* Block forging, full block validation and propagation

**Readiness (Current -> Target)**: SRL 6 -> SRL 9&#x20;

**Estimated Effort**: 8 FTE (Funded by Catalyst, contributions and treasury withdrawal: _not asking for budget from Intersect)_\
\
_Why is this item excluded from the budget ask?_\
The process for budget and treasury withdrawals is not yet fully defined. The team is aiming to take an independent approach to treasury withdrawals. However, they believe it’s essential to keep the Intersect roadmap informed about this critical item. Additionally, if there’s a limit of one withdrawal for constitutional purposes, they want to ensure that the Rust Node remains part of the discussion.
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1YzgIof-n2x_hMMNQDJhMsbfPvTq16I4R/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Static Analyzer

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: The Plinth static analyzer is a tool designed to evaluate Plinth smart contracts for common errors, performance inefficiencies, and potential anti-patterns. It inspects code statically, offering suggestions for improvements and generating detailed reports, both in HTML and terminal formats. Configurable through CLI and TOML, it helps developers optimize Plinth contracts by identifying bugs and performance bottlenecks early, ensuring high code quality and adherence to best practices within the Plutus ecosystem.

**Problem Statement**: Blockchain smart contract bugs can lead to major financial losses. Traditional reviews are slow and require expertise, often missing critical issues. A one-click static analyzer for Plinth can potentially detect 80% of common security flaws and performance issues instantly, no expertise needed, strengthening security and trust across the ecosystem.

**Benefit**:&#x20;

* Cost Savings: Reduces financial loss by catching critical bugs early.
* Productivity Increase: One-click automation streamlines contract audits.
* Quality Improvement: Detects 80% of common bugs and vulnerabilities automatically.
* Full Automation: 100% automated analysis, requiring zero expertise.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Stefano Leone

**Product Goal**: Meet the needs of apps

**Dependencies**: [https://github.com/kowainik/stan](https://github.com/kowainik/stan)

**2025 Deliverable**: Proof of concept; List of coding rules and antipatterns (documentation); Stable release

**Readiness (Current -> Target)**: SRL 2  -> SRL 7&#x20;

**Estimated Effort**: 2.5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1cQR2aLDnGmGdHiRiUw40RG2Dm2fQd2WO/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Tiered Pricing Model

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: This Tiered Pricing Model introduces a prioritization mechanism for Cardano transactions. Users can select from three transaction channels—Standard, Priority, and Assured—each offering different fee levels and block inclusion expectations. This flexible system, powered by AI-based congestion predictions, allows users to choose the urgency and cost of their transactions to meet their specific needs.

**Problem Statement**: The Cardano network faces congestion issues during peak times, leading to unpredictable transaction delays. Approximately 20% of the time, users experience delays that disrupt critical, time-sensitive transactions, often causing frustration and financial risk.

**Benefit**:&#x20;

* Predictable Timing and Costs: Users can better anticipate both transaction times and fees, enhancing reliability
* Flexible Prioritization: Higher fees for urgent transactions ensure timely inclusion
* Improved Experience: Users avoid delays and unexpected costs during congestion
* Ecosystem Growth: Increased network fees support ongoing Cardano development
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Kevin Hammond

**Product Goal**: Business as usual

**Dependencies**: None

**2025 Deliverable**:

* Testing framework for transaction prioritization; prototype fee-based selection algorithms.
* AI congestion prediction service; data collection for fees, load, and timing.
* Wallet integration for fee/timing predictions; testnet launch of Standard and Priority channels.
* Finalized Assured channel design.
* CPS & Revised CIPs: Cardano Problem Statement and updated/new CIPs.

**Readiness (Current -> Target)**: SRL 2 -> SRL 6&#x20;

**Estimated Effort**: 8 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1EoXmW2wCAXJ5xK11eHTNvdrgCIxujwWm/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Timeliness Market

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: The proposed work would create a PoC of a small change to the cardano\_node (and its client-to-node interface) that would permit a block producing node to ensure, even under extreme cardano load, the insertion of a transaction into the block about to be produced.

**Problem Statement**: The risk profiles of operating DeX, chain bridges and certain dApps is strongly influenced by time-to-chain for critical transactions (such as Oracles), this currently lacks appropriate predictability

**Benefit**: The proposed work would enhance the cardano\_node to have the appropriate API call to support such transaction insertion; This would permit the creation of (one more) “assured transaction timeliness markets” by others.
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Neil Davis

**Product Goal**: Get more usage | Easier to build on and to use Cardano&#x20;

**Dependencies**: There is no particular dependencies for this; the development would have to choose a suitable stage of cardano\_node to base the work against.

**2025 Deliverable**: This is estimated to be a 3 to 4 month activity that would deliver a validated design, a proof of concept node operating, and a CIP for its inclusion in the cardano node (captured as a PR)

**Readiness (Current -> Target)**: SRL 3 -> SRL 8&#x20;

**Estimated Effort**: 3 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1XUL__2Pyph9eB4WN8B9dLQEVybP70fQS/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

### Transaction Monitoring System

{% tabs %}
{% tab title="Project Abstract" %}
**Description**: The Transaction Monitoring System is a real-time fraud detection tool powered by machine learning algorithms. It continuously monitors blockchain transactions, identifying unusual patterns and flagging potentially fraudulent activities instantly. By analyzing transaction data in real time, it provides immediate alerts, enabling swift responses to security threats. This system helps enhance financial safety within the blockchain ecosystem, ensuring secure and reliable operations by proactively mitigating risks associated with fraud.

**Problem Statement**: Cardano lacks a real-time transaction monitoring system to detect fraud and analyze on-chain activity. Without proactive oversight, node operators and businesses have limited ability to respond to security threats or monitor network health. This system will fill that gap, providing real-time alerts, transaction classification, and actionable insights.

**Benefit**:&#x20;

* Security: Real-time fraud detection
* Visibility: Continuous monitoring of on-chain health
* Insights: Transaction stats and classifications for strategy
{% endtab %}

{% tab title="Project Details" %}
**Project Sponsor**: Stefano Leone

**Product Goal**: Business as usual

**Dependencies**: None

**2025 Deliverable**:

* State-of-the art on fraud/anomaly detection and executable specification
* Alpha version of the backend with a frontend for data visualization and alert mechanism

**Readiness (Current -> Target)**: SRL 1 -> SRL 5&#x20;

**Estimated Effort**: 5 FTE
{% endtab %}

{% tab title="Video" %}
{% embed url="https://drive.google.com/file/d/1WJGOc_iQ2OsTl559MtbfGqTdsZ9VbKiE/view?usp=drive_link" %}


{% endtab %}
{% endtabs %}

***

Should you find or believe information about these projects incorrect or misleading please contact the technical-steering-committee@intersectmbo.org or the individual project sponsor listed for corrections.
