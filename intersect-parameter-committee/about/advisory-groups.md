# Advisory Groups

{% hint style="info" %}
This page is written on behalf of the Parameter Committee, the information contained is subject to change and amendment by the committee chairs at any time and should be used at your own risk
{% endhint %}

## Advisory group members

Each Committee may freely establish advisory groups to study and address temporary work items.

* The Parameter Committee members will propose and vote on the appointment of a Head for the working groups.
* The head of the working group may invite any person or representative of an organization to participate in working groups. Working group heads are responsible to report back to their respective committee or subcommittee.
* Representatives of the SPO and dRep community can also apply to become members of the working groups.

### Protocol parameter governance

The Parameter Committee has grouped the protocol parameter changes by type, allowing different thresholds to be set for each group.

We are not, however, restricting each protocol parameter governance action to be contained within one group. In case where a governance action carries updates for multiple parameters from different groups, the maximum threshold of all the groups involved will apply to any given such governance action.

The network, economic and technical parameter groups collect existing protocol parameters that were introduced during the Shelley, Alonzo and Babbage eras. In addition, we introduce a new governance group that is specific to the new governance parameters that will be introduced by CIP-1694.

**The network group:**

* maximum block body size (maxBBSize)
* maximum transaction size (maxTxSize)
* maximum block header size (maxBHSize)
* maximum size of a serialized asset value (maxValSize)
* maximum script execution units in a single transaction (maxTxExUnits)
* maximum script execution units in a single block (maxBlockExUnits)
* maximum number of collateral inputs (maxCollateralInputs)

**Economic group:**

* minimum fee coefficient (minFeeA)
* minimum fee constant (minFeeB)
* delegation key Lovelace deposit (keyDeposit)
* pool registration Lovelace deposit (poolDeposit)
* monetary expansion (rho)
* treasury expansion (tau)
* minimum fixed rewards cut for pools (minPoolCost)
* minimum Lovelace deposit per byte of serialized UTxO (coinsPerUTxOByte)
* prices of Plutus execution units (prices)

**The technical group:**

* pool pledge influence (a0)
* pool retirement maximum epoch (eMax)
* desired number of pools (nOpt)
* Plutus execution cost models (costModels)
* proportion of collateral needed for scripts (collateralPercentage)

**The governance group:**

* governance voting thresholds ($P1$, $P{2a}$, $P{2b}$, $P3$, $P4$, $P{5a}$, $P{5b}$, $P{5c}$, $P{5d}$, $P6$, $Q1$, $Q{2a}$, $Q{2b}$, $Q4$)
* governance action maximum lifetime in epochs (govActionLifetime)
* governance action deposit (govActionDeposit)
* DRep deposit amount (drepDeposit)
* DRep activity period in epochs (drepActivity)
* minimal constitutional committee size (ccMinSize)
* maximum term length (in epochs) for the constitutional committee members (ccMaxTermLength)
