> [!info]- This post was originally published in the Governance Forum
> To view the source, please click [here](https://gov.optimism.io/t/security-council-vote-1-change-to-security-model/6886). Initially published on September 28, 2023 and last modified on September 28, 2023

<span class="notvisible"></span>
For full context on the implementation of the Security Council, please read [[Intro to Optimism's Security Council]]

# Security Council: Vote #1 - Change to Security Model

The proposal that follows requests Token House approval for a change to the security model of OP Mainnet. This change does not constitute a Protocol Upgrade.

## Summary

This is a proposal to turn proxy admin keys for OP Mainnet over to a public, decentralized set of individual actors (“participants”) accountable to Optimism Governance: i.e., the [[Security Council Charter v0.1|Security Council]]

Specifically, for this initial Security Council proposal (Vote # 1), Governance will vote to approve the addition of the Security Council as one signer (of two) on a 2/2 multisig that controls protocol upgrades for OP Mainnet. The other signer on the multisig will be the current Foundation multisig.

If this proposal passes, it will approve a change similar to [this illustrative example](https://github.com/ethereum-optimism/superchain-ops/blob/zchn/multisig-2-of-2-example/eth/1-proxyadmin-2-of-2-example/proxyadmin.json).

There will be an on-chain change of the ProxyAdmin’s owner from `0x9ba6e03d8b90de867373db8cf1a58d2f7f006b3a` to a new 2 of 2 multisig (`0xdc53b1d440b8a56dd50a6d69312dac903d3aa48b`, in the example provided above).

The state diff for the above example can be found [here.](https://dashboard.tenderly.co/public/safe/safe-apps/simulator/346038ec-661c-405e-af7f-a524487bb789/state-diff)

## Security Considerations

- The Security Council will operate a Gnosis Safe multisig wallet.
- Participants will carry out their roles in accordance with the [[Security Council Charter v0.1|Security Council Charter]] including the following key points:
    - During [[Security Council Charter v0.1#**Normal Operation**|normal operations]], the Security Council will implement the protocol upgrade and role designation decisions (such as designations for the sequencer, proposer, and challenger roles, as well as designating the composition of the participants on the Security Council multisig) made by Optimism Governance. The Security Council simply does as Governance directs. It does not directly evaluate the “merit” of the accompanying proposed code (e.g., for security purposes); that evaluation is the responsibility of Governance.
    - During defined [[Security Council Charter v0.1#**Emergency Response**|emergency situations]], the Security Council is empowered to act preemptively, without direct Governance approval, in order to keep the network safe and secure. Each participant may also take actions they or the Optimism Foundation believes to be necessary to comply with applicable law.
    - Dysfunctional participants, either individually or acting as a quorum, can be effectively checked, without undermining the security advantages motivating the formation of the Council in the first place.

## Conclusion

You can read the complete Security Council Charter [[Security Council Charter v0.1|here]]. Technically, neither the existence of a Security Council nor its Charter needs to be approved via governance. However, since the implementation of this proposed [[Security Council Charter v0.1|Security Council]] represents a fundamental change to OP Mainnet’s security model, the Optimism Foundation is requesting approval to implement the change.

If this proposal passes with a 76% approval threshold (30% quorum), the Optimism Foundation will move forward with the implementation of the [[Security Council Charter v0.1|Security Council.]]

---

**Note:** _Through subsequent Governance proposals and votes, it is intended that this Security Council will eventually extend beyond OP Mainnet, to secure all other OP Chains within the Superchain (read more). The ultimate goal is preventing any single party from being able to upgrade the system, modify rollup state, or censor transactions._

---

# What Does this Mean for Delegates?

This proposal will go to a vote in Special Voting Cycle ``#16a``.