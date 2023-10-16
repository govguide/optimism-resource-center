---
aliases:
  - this template
---

> [!info]- This post was originally published in the Governance Forum
> To view the source, please click [here](https://gov.optimism.io/t/inflation-adjustment-proposal-template/5923). Initially published on April 25, 2023 and last modified on June 16, 2023.

<span class="notvisible"></span>
## Background

Inflation of the OP token is set to 2% per year by default. This inflation takes place via the `MintManager` contract calling the `mint()` function on the OP token contract at `0x4200000000000000000000000000000000000042`.

This inflation parameter can be adjusted by Optimism Collective Governance. In Year 1, while the Citizens’ House is still in early stages, inflation adjustment will be determined via vote from the Token House, as specified in the [[OPerating Manual]].

Note that this may not be the final governance process for inflation; the system may evolve as additional governance rights and capabilities come online.

Inflation accrues to the “Unallocated” portion of the OP token allocations. The Unallocated portion of the treasury is held in reserve for future programs. For now, the Collective is focused on building healthy processes around the existing active portions of the treasury.

## How the Inflation Adjustment Vote works

> [!warning] Outdated information
> Information in the following paragraph talks about Voting Cycle 12b, which happened in the past. 

In the Voting Cycle that ends closest to and before May 31, the Token House may vote to set inflation to any value between 0% and 2%, inclusive.

This inflation adjustment vote must pass with 76% approval and 30% quorum of votable supply. **If no vote passes, inflation will default to 2%.**

In 2023, an Inflation Adjustment Vote may take place in **Special Voting Cycle ``#12b``**, which runs from May 18 - May 31, 2023. If more than one Inflation Adjustment Proposal is passed by governance, the proposal with the highest ratio of `yes` votes to total votes cast will pass.

Inflation Adjustment approval should follow the template provided below and will need 4 delegate approvals by May 17th at 19:00 GMT to proceed to a vote, as outlined in the [[OPerating Manual]].

## Inflation Adjustment Proposal Template

_Inflation Adjustment Proposals should follow the template below:_

> ### **Summary**
> 
> _What is this inflation adjustment proposal?_
> 
> ### **Motivation**
> 
> _Why should the Collective adjust inflation?_
> 
> ### **Specification**
> 
> _This proposal would set an inflation rate for [**YEAR**] of [**X%**]._
> 
> _If approved, and if not superceeded by another Inflation Adjustment Proposal with higher approval, this proposal will result in a one-time mint of OP of [**X**]% of the current total supply (4,294,967,296 OP) equal to **[Y]** tokens. This inflation will occur on or shortly after May 31 and accrues to the “unallocated” portion of the token treasury._
> 
> _If not approved, and unless another Inflation Adjustment Proposal is approved, inflation will remain at **2%**, which will result in a one-time minting of 2% of the current total supply, or 85,899,345 OP. Inflation will occur on or shortly after May 31 and accrues to the “unallocated” portion of the token treasury._
> 
> ### **Impact Summary**
> 
> _Expected effects resulting from inflation adjustment_  
> _Expected impact to key stakeholders in the Collective_