---
description: 'Updated: 28 Aug 2024'
---

# Refinement

Items in this category need to undergo additional requirements that must be met in order to show sufficient maturity for funding:

1. A set of well-scoped deliverables (whether for research or for production software) ready to be made into a work-package (which may define future phases/partitions as well as feasibility)
2. Acceptance of those deliverables by the relevant TWG and/or SIGs

For any further information, refer to the process flow [here](../process-flow.md).

## LSM-2. Increase Capability to store UTxOs on disk using LSM (Integration to Node)

{% hint style="info" %}
This is a follow-up work from current inflight item [LSM-1](../current-state/list-of-inflight-items.md#id-2.-increase-capability-to-store-utxos-on-disk-using-lsm-pre-contracted)
{% endhint %}

With continued growth of the Cardano Blockchain Ledger, the need to move from an in-memory to a disk persisted solution is even more important. This achieves more scalability and assures SPOs and full node wallets of being able to operate on commodity hardware or retain a lower footprint on cloud . Implementation of LSM will use an innovative approach to persisting to disk (SSD) using a Log Structured Merge(LSM) tree, which will be built standalone and integrated in node.

The component will take the form of a Haskell library for managing tables of key-value data stored persistently on disk. This is to reduce the memory size of the UTXO set (ledger) that will allow us to potentially quadruple the transactions on the network without increasing memory cost, which is hugely beneficial to Stake Pool Operators. This is intended to be used later within the Cardano node for storing large parts of the ledger state on disk. The component is specified as a “stand alone” component, in isolation from Cardano, with detailed functional and non-functional requirements. The work is structured in such a way that after an initial design phase further ratification and community feedback will be sought prior to any implementation or production deployment.

<table data-header-hidden><thead><tr><th width="249"></th><th></th></tr></thead><tbody><tr><td>Status</td><td>In draft<br>This item is pending validation of business benefits. A SIG is being set up to gather community input to articulate its value. </td></tr><tr><td>Drivers</td><td><ol><li>Performance - reducing the memory size of the ledger allows us to improve transactions on the network. Ensure long term scalability for Cardano, by fixing a limit on the total memory requirement for the node.</li><li>Ensure all ledger state is held in non-volatile storage</li></ol></td></tr><tr><td>Documentation</td><td>Whitepaper Link:<a href="https://drive.google.com/file/d/1XkY7CKNM9DoL4c8rbnAKUH6s9PUrJ5oH/view?usp=drive_link"> https://drive.google.com/file/d/1XkY7CKNM9DoL4c8rbnAKUH6s9PUrJ5oH/view?usp=drive_link</a></td></tr><tr><td>Target State</td><td>Developed new Log Structured Merge Tree implementations on Cardano mainnet</td></tr><tr><td>Definition of Done</td><td>LSM work integrated into mainnet</td></tr><tr><td>Product Stage</td><td>Integration</td></tr><tr><td>Functional Requirements</td><td>LSM work integrated into the node providing an in-memory backend and an on-disk backend that can be toggled via config and/or runtime flags</td></tr><tr><td>Non-functional Requirements</td><td>TBC</td></tr><tr><td>External Dependencies</td><td>Completion of LSM libraries by Well-Typed</td></tr><tr><td>Communication Channel</td><td><p>Intersect Development Updates</p><p>Intersect Knowledge Base</p></td></tr><tr><td>Indicative Sizing</td><td>L (Will be several months of work)</td></tr><tr><td>Context of Indicative Sizing</td><td>Much of consensus needs to be adapted to use the LSM libraries for reading/writing states from/to disk</td></tr><tr><td>Dependencies &#x26; Dependants</td><td>TBC</td></tr><tr><td>Hardfork (Yes,No, TBC)</td><td>Not required</td></tr><tr><td>Security Review</td><td>Yes</td></tr><tr><td>Code Audit</td><td>Part of Node audit</td></tr><tr><td>Community Endorsement</td><td>TBC</td></tr><tr><td>Feasibility Study Required?</td><td>No</td></tr><tr><td>Reviewing Working Group</td><td>Ledger working group (Also involved Consensus &#x26; CLI)</td></tr><tr><td>Core Infrastructure (Yes, No, TBC)</td><td>Yes</td></tr><tr><td>Item Champion</td><td>IOE</td></tr></tbody></table>

