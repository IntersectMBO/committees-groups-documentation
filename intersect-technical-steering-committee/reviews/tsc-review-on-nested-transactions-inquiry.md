# TSC review on nested transactions inquiry

Thank you for raising this issue with the Technical Steering Committee (TSC), and for stimulating technical discussion.  The TSC has reviewed your concerns regarding the introduction of nested transactions, specifically focusing on your points related to MEV exposure (Point 1) and whether the feature is needed (Point 4).

The TSC's discussion concluded that the matter of nested transactions is primarily a product design choice involving a trade-off of development complexity and user experience against potential system-level risks. As such, we advise that this issue be formally directed to the Product Committee for a final decision on whether nested transactions should be supported in Cardano.

The following is a summary of the technical trade-offs discussed by the TSC:Trade-offs of Multi-Party Atomic Transactions (Relating to Point 4 - "Not Needed")

While the current protocol does allow for the creation of atomic transactions, the core value proposition of nested transactions is to significantly simplify the creation of atomic transactions involving multiple, uncoordinated parties.

* Current Process (Without Nested Transactions): Achieving multi-party atomic transactions requires a more "involved and difficult pattern of interaction" or off-chain coordination between all parties to build and sign the entire transaction body together.
* Nested Transactions Benefit: This feature enables a more streamlined communication pattern, exemplified by the babel fees use case. A party can sign a partial transaction (e.g., spending an asset without paying the ADA fee) and fire it into the system, trusting a third party will fill the remaining component (e.g., provide the fee) without prior, explicit coordination. The necessity of this improved multi-party coordination model is a key product consideration.

**MEV Exposure (Relating to Point 1)**

The concern over Maximal Extractable Value (MEV) exposure stems from the modular nature that nested transactions introduce:

* Nested transactions essentially "modularize" the pieces of a transaction. This modularity means an external party (such as a searcher or miner) can potentially "reach inside those nested transactions and pull out the pieces and reassemble them" in a different way to extract value.
* The general sentiment of the committee was that the ability to perform such rebundling is a consequence of making the transaction parts modular, and that MEV is often considered "inevitable" in such systems. The degree of this exposure and whether it is an acceptable risk is part of the product decision.

In summary, the TSC believes the debate centers on a product trade-off between greater ease of multi-party decentralized coordination and the introduction of a more complex MEV environment, rather than a predominantly technical concern. We therefore recommend presenting these trade-offs to the Product Committee for their review and decision.
