> [!info]- This post was originally published in the Governance Forum
> To view the source, please click [here](https://gov.optimism.io/t/intro-to-optimisms-security-council/6885). Initially published on September 28, 2023 and last modified on September 29, 2023

<span class="notvisible"></span>
Optimism is seeking to establish a [[Security Council Charter v0.1|Security Council]] to advance towards a more decentralized Optimism [Superchain](https://www.optimism.io/superchain) Network.

The Security Council would assume control of the keys required to:

- Upgrade the L1 protocol contracts for all OP Chains participating in the Superchain (beginning with OP Mainnet); and
- Modify designations for certain important roles in the system, such as sequencers (i.e., batchers), proposers, challengers, and membership on the Security Council multisig.

By creating and empowering this Security Council, the Collective can make significant steps towards key decentralization targets: ensuring no single party is able to upgrade the system, modify rollup state, or censor transactions.

### Decentralization Impact

Councils are unique and important structures within Collective Governance. They are comprised of elected representatives that manage Collective resources or make decisions on behalf of tokenholders or Citizens. They fulfill roles otherwise filled by the Foundation or other centralized actors and therefore play a critical role in the decentralization of the Collective.

As outlined in the [[Collective Council Framework]], the Foundation may authorize Councils that support a specific Collective Intent. The Security Council falls under Intent #1: Progress Towards Technical Decentralization. You can reference the [[Security Council Charter v0.1|Security Council Charter]].

After the initiation of the Security Council, no single party should be able to:

1. Upgrade L1 protocol contracts
2. Modify L2 state
3. Censor L2 users from transacting onchain

### Governance Impact

As outlined in the Council framework, the existence of a Security Council itself does not need to be approved by governance. However, the proposed initiation of the Security Council requires certain procedural steps that do require a vote.

As proposed, the initiation of the Security Council would be implemented in two phases:

**Phase 0:**

- First, the Security Council will be added as one signer on a 2/2 multisig that controls protocol upgrades for OP Mainnet (with the other signer being the current Foundation multisig).
- Phase 0 only impacts the upgradability of the OP Mainnet, as other chains still need to proceed through the Sequencer/Superchain governance process that will come online in Season 5. This initial, interim step paves the way for the full Superchain Security Council initiation in Phase 1 (below).
- There will not be a Phase 0 for other OP Chains. Phase 0 is a “training wheels” program for the Security Council’s full initiation in Phase 1, and is limited to OP Mainnet.

**Phase 1:**

- At a later date, the 2/2 structure will be transitioned to a single multisig controlled exclusively by the Security Council, enabling the Security Council to upgrade the protocol (and change role designations) for OP Mainnet and eventually, the Superchain. Concurrently:
- Smart contract changes will introduce a 14-day delay on all L1 protocol upgrades and changes to sequencer role designations, which can be vetoed at any time during that period by the Optimism Foundation.
- In order to protect against a loss of assets in the event of a critical vulnerability being identified, the existing pause functionality in OptimismPortal will be extended to all withdrawal methods in the L1StandardBridge, L1ERC721Bridge and L1CrossDomainMessenger contracts.

Phase 1 fully implements the initiation of the Security Council. It will initially include OP Mainnet, then expand to all other OP Chains that proceed through the Sequencer Allowlist/Superchain governance process that will come online in Season 5.

---

# What Does this Mean for Delegates?

In connection with this staged rollout, there are three related proposals for the Token House to review and vote on over the next few months:

1. **[[Security Council Vote 1 - Change to Security Model|Security Council: Vote #1 – Change to Security Model:]]** This vote will approve Phase 0’s addition of the Security Council as a signer on a 2/2 multisig that controls protocol upgrades for OP Mainnet. This does not require any protocol changes, but as this represents a fundamental change to OP Mainnet’s security model, it should be approved by the Token House. The full details of this proposal will be voted on by the Token House during the upcoming Reflection Period.
    
2. **Security Council: Vote #2 – Membership Ratification:** The initial set of members of the Security Council (applicable to both Phase 0 and Phase 1) must be ratified by the Token House. Following the first term of the initial set of members, elections for cohorts of the Security Council will take place each Season. The Token House vote to ratify the initial member set will follow Vote #1 during the upcoming Reflection Period.
    
3. **Security Council: Vote #3 – Full Security Model + Delayed Upgrade:** Phase 1 requires a protocol upgrade to implement the full scope of the Security Council initiation. This will be voted on by the Token House in Season 5.