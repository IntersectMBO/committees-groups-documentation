# Plutonomicon/CTL

**Plutonomicon/CTL:** MLabs will update and validate the Cardano Transaction Library (CTL)\
for compatibility with the van Rossem hardfork, including dependency upgrades, local test\
infrastructure, transaction-building and balancing compatibility work, governance-related\
updates, developer documentation, and compatibility reporting.

{% file src="../../../../.gitbook/assets/OSC-26-0039_CTL_MLabs_LTD_Community_grant_contract.pdf" %}

**Milestone 1:**&#x20;

1. Bump runtime dependencies. Update the Nix flake and Spago dependencies to versions compatible with Protocol Version 11: Cardano Node (11.0.1 mainnet-ready release), Ogmios, Kupo.
2. Verify the test infrastructure. Confirm that CTL's cardano-testnet-ba sed local cluster still launches correctly against the updated node revision, and that all testing utilities work as expected.
3. Verify existing tests pass. Run the full unit, integration, and end-to-end test suites. Investigate and fix any failures. Also confirm the Blockfrost backend does not regress, since CTL supports it as an alternative query layer.

{% file src="../../../../.gitbook/assets/OSC-26-0039 - Milestone 1.pdf" %}

**Milestone 2:** Under Review

**Milestone 3:** Coming soon
