### Background

Access to structured chain data unlocks the proliferation of sophisticated information technology. The rise of APIs changed the Web2 landscape by permitting the automation of many functions and facilitating rapid information transfer. Web3 needs more infrastructure to achieve similar levels of performance.

The intrinsic value of blockchain data needs little elaboration. Everyone from product developers to users to researchers to traders benefits from easy access to data. Indeed, the market has largely satisfied the demand for real-time on-chain data, providing a range of products including subgraphs and block explorer APIs.

Although sourcing historical on-chain state is just as important as real-time data, it can require more complex infrastructure or costly indexing. Current solutions for historical data are limited, underpowered, and fraught with usability issues. Analysts may have to rely on user-made Dune dashboards or incomplete subgraphs, or they may have to pay organizations to procure bespoke datasets and offer some sort of visualization. The APIs that do exist, such as Hardhat and Brownie, are often prohibitively unwieldy, or over-specialized, leading users to revert to SQL-based solutions or hope that others have run the analysis they need.

Given the evident value of historical data, the lack of a user-friendly solution is likely due to the absence of a clear monetization path. This presents a clear opportunity for the Grant Council to step in and subsidize this development.

### Request

What the Optimism community needs are solutions that resonate with developers, allowing them to swiftly retrieve information (e.g., from blockchain state at a specific moment in the past, or a set of actions within some time range). Such solutions will make Optimism a uniquely rich and accessible environment for users, developers, analysts, and academics; the benefit will be immense.

Such a product could empower developers to access historical state from Optimism mainnet more easily and in a lightweight/portable manner. Unlike existing APIs, developers would not need to use customized RPCs or input specific contracts; this solution would offer an environment that takes in some point in time, pulls contract ABIs from existing repositories, and returns the desired historical data in some approachable way.

The proposed service would not only streamline the development process by making it easier to query historical data as needed, but also enable UIs and analysts to display any sort of historical data swiftly and easily.

Examples of possible improvements in tooling abound. Protocol teams can now access a previously nearly inaccessible bounty of information that can aid in their strategic planning or program evaluation. Individual users can now be served more detailed portfolio analytics by service providers. Oracle teams can stress-test price assumptions to ensure their stability. The list goes on.

Even the Grant Council would benefit from this; easy access to historical data would enable more specialized tracking of individual grants, performance, and milestones. We would be able to, for instance, determine whether some protocol met a certain threshold of liquidity providers by some point in time. Currently, someone seeking that information would most likely have to get that number through a roundabout Dune query.

## **What is required to execute this RFG?**

To implement this RFG, the solution should be capable of executing smart contract view function calls at arbitrary (or hourly/daily) times in the past for Optimism Mainnet contracts.

The solution can be generalized for all smart contracts and functions or tailored for specific popular contracts and important function calls.

The solution should be programmatically accessible via an API or similar service, and it should be adequately performant to be usable on a production dapp – that is, it should be able to handle several calls at a time and serve these calls in a timely manner so as not to harm user experience.

We acknowledge that there may be several potential paths to meet the brief, so a second grant category is earmarked for those builders that may have their own ideas as to how to make historical data more easily accessed and presented.

## **Baseline grant amount**

We see three categories of grants within this broader objective:

**1(a).** Building open source, public API for calling view functions of smart contracts on Optimism mainnet.

- 30k OP (up to 2 in Cycle 13)

**1(b).** Any other tool that solves the core need outlined in this proposal of Optimism app developers wanting more lightweight solutions for programmatically retrieving historical data from Optimism.

- 25k OP (up to 2 in Cycle 13)

**1(c).** Any UI or tool that supports accessibility of the above tools for developers and non-developers alike.

- 5k OP (up to 3 in Cycle 13)

_Note that all grants will be subject to the lockup terms explained [here](https://gov.optimism.io/t/grant-token-lock-explainer/5060)_.

## **What milestones will help the Collective track progress towards completion of this RFG?**

As with conventional Governance grant proposals, participating projects are expected to be able to have their work tracked over the course of Season 4.

For grant 1(a)

- Proof of concept that can call even just a single function on a single smart contract at specific hours or days or blocks in the past.
    
- Confirmed deployment
    

For grants 1(b)-(c)

- Confirmed contract deployment
    

Proposers can use these milestones as a baseline and can improve their proposals by adding milestones in accordance with the [Milestones Assessment](https://gov.optimism.io/t/milestone-assessment/5314) guidance.

## **How should the Grant Council measure impact?**

_In addition to the factors in the [Builders Grant rubric](https://app.charmverse.io/op-grants/page-13972604474186334),_ _proposers will be graded on their ability to provide directly measurable, transparent KPIs. Where possible, we will instruct proposers to construct a Dune query measuring impact. Some of the factors include:_

- Integration of tool in Optimism dapps to display historical data*
    
- Performance: Benchmarking latency, throughput/throttling of the service relative to comparable services**
    
- Scalability, e.g., computational cost per 1k calls***
    
- Accessibility to developers or end users relative to current solutions****
    

|   |   |   |   |   |   |
|---|---|---|---|---|---|
|**RFG Factors**|0|1|2|3|4|
|**Integration***|Very hard to integrate|Somewhat difficult to integrate|Feasible to integrate|Easy to integrate|Very easy to integrate|
|**Benchmarking latency****|Nonperformant, low capacity|Low performance in some dimensions that could inhibit usability|Performance likely consistent with replacement solutions|Performance likely to exceed replacement solutions in some respects|Likely to far exceed performance of replacement solutions|
|**Scalability*****|Prohibitively complex / costly to scale|Scalable with significant difficulty|Reasonably scalable|Built to scale in a cost-effective manner|Enterprise-grade out of the box|
|**Accessibility******|Too unapproachable of a tool for most people|Challenging for most engineers|More for developers than end users|Many end users may find this accessible|Likely for anyone to have an easy time using it|
|**Merits**|**0**|**1**|**2**|**_3_**|**_4_**|
|**Likelihood of success**|There's a clear flaw in the design that cannot be easily remedied|Difficult to see the project continuing for more than a year|There's a reasonable chance that the project has intermediate-to-long-term success (+1 Year)|The project is likely to generate long-term, sustainable value for the Optimism ecosystem|The project has a substantial likelihood of generating long-term, sustainable value for the Optimism ecosystem|
|**Novelty**|There is little to distinguish this project from other projects that exist on Optimism already|This is one of a small number of examples of a project being built on Optimism that is otherwise common throughout Web3|This project is distinguishable from other projects in Web3 on the margins (e.g., a different way of doing something that may be done in other contexts already)|This project is distinguishable from other projects in Web3: very few other projects are doing something similar and this is not merely a different way of performing an existing operation|This project is on the horizon and is meaningfully different from other projects in Web3.|
|**Team assessment**|The team does not substantiate the ability to deliver on the plan|The team does not show significant ability to deliver on the plan|The team shows a reasonable ability to deliver on the plan|The team shows a significant ability to deliver on the plan|The team exceeds what is required to deliver on the plan|
|**Builder commitment**|No commitment attraction|Mercenary commitment attraction (stays until benefits end)|Commitment attraction (1 – 3 months after rewards end)|Commitment attraction (1 year after rewards end)|Commitment attraction (2+ years after rewards end)|
|**Specs**|0|1|2|3|4|
|**Suitability**|Does not meaningfully address any of the grant requirements|Partially addresses some of the grant requirements|Mostly addresses|Fully meets all grant requirements|Exceeds requirements, anticipates extensions|
|**Milestone** **suitability**|Does not incorporate milestones suggested by RFG|Incorporates milestones suggested by RFG|Incorporates milestones suggested by RFG in addition to other thoughtful milestones|||
|**Milestone trackability**|Not trackable|Somewhat trackable|Easily trackable|||
|**Other**|0|1|2|3|4|
|**Optimism relationship**|Not deployed in any ecosystem|Deployed in other ecosystems, not Optimism|Deployed on Optimism and other ecosystems|Deployed exclusively on Optimism||
|**Open-sourcing**|Not open-source||Currently or initially open-source, but not committed to open-source model||Committed to a long-term open-source model|
|**Discretionary score***|-2|-1|0|1|2|
|**Factors**||||||
|_*Reviewers will have a discretionary score to apply to the overall rubric of (-2 to 2). An explanation must be included with the assignment of any discretionary score._||||||

# RFG Form

  

> 📄
> 
> _Please do not post this form to the Governance Forum. Proposals should be submitted on the Grants Council landing page, [here](https://app.charmverse.io/op-grants/proposals)._
> 
>   
> 
> _Before filling out this form, note that you are responsible for checking updates to the Landing Page, which will reproduce updates to the Forum and to the Optimism Discord._
> 
>   
> 
> _Updates will be posted to the landing page, forum and #grants. The Grants Council will post the results of the Preliminary and Final reviews on the Forum. Proposer conduct and etiquette will be taken into account in assigning final scores._
> 
> ### Basic Details  
>   
> 
> **Which RFG are you applying for? Specify which request and sub request.**
> 
> - 1a (API solution)
>     
> - 1b (Alternate general solution)
>     
> - 1c (Add-on solutions / accessibility tools)
>     
> 
>   
> 
> **Project name:**
> 
>   
> 
> **Author name and forum name (please provide a reliable point of contact for the project):**
> 
>   
> 
> **L2 recipient address:**
> 
>   
> 
> **Which Voting Cycle are you applying for?:**
> 
>   
> 
> **I understand that I will be required to provide additional KYC information to the Optimism Foundation to receive this grant: [Yes/No]:**
> 
> - Yes
>     
> - No
>     
> 
> **I understand that I will be expected to follow the public grant reporting requirements outlined [here](https://gov.optimism.io/t/suggested-public-reporting-requirements-for-grantees/4176):**
> 
> - Yes
>     
> - No
>     
> 
> **I understand that grants under RFG are subject to a 1-year lock-up, as explained further in [this post](https://gov.optimism.io/t/grant-token-lock-explainer/5060): [Yes/No]:**
> 
> - Yes
>     
> - No
>     
> 
> **This project needs upfront capital and should be considered for a [co-grant](https://gov.optimism.io/t/introducing-optimism-co-granting/5870):**
> 
> - Yes
>     
> - No
>     
> 
> ### Project Details
> 
>   
> 
> **What are you going to build?:**
> 
>   
> 
> **Provide us with links to any of the following for the project:**
> 
> - Demo:
>     
> - Website:
>     
> - Twitter:
>     
> - Discord/Discourse/Community:
>     
> - Github:
>     
> - Other:
>     
> 
>   
> **Why is what you are going to build going to succeed in meeting the RFG's requirements? Please describe how your proposed specs will address each requirement.**  
>   
> **Please discuss how you are going to meet each of the milestone objectives outlined in the grant:**
> 
> - Integration
>     
> - Performance
>     
> - Scalability
>     
> - Accessibility  
>       
>     
> 
> **Is what you are going to build novel? (You can think of novelty in one of two ways: either your project is meaningfully different from what others are building in the blockchain industry or you can describe how you are approaching a problem in a way unique from how others are approaching the same problem, provided that the unique aspect of the proposed solution is a key driver of the value created).**
> 
>   
> 
> **If you are presenting a novel solution...**
> 
>   
> 
> 1. **is your build likely to bring new builders to the Optimism ecosystem? If so, please describe how:  
>     **  
>     
> 2. **Is your project likely to improve the quality of developers in the Optimism ecosystem? If so, please describe how:  
>     **  
>     
> 3. **Is your project likely to improve the commitment of developers in the Optimism ecosystem? If so, please describe how:**
>     
> 
>   
> 
> **What are some competing alternatives to what you are going to build?:**
> 
>   
> 
> **Will your project be composable with other projects on Optimism? If so, please explain:**
> 
>   
> 
> **Do you have any metrics on the project currently? (TVL, transactions, volume, unique addresses, etc. Optimism metrics preferred; please link to public sources such as Dune Analytics, etc.):**
> 
>   
> 
> **Will your project be fee-based or free to the end user?**
> 
>   
> 
> **Will your project be open-source?**
> 
> ### Team
> 
>   
> 
> **Who are your founders?:**
> 
>   
> 
> **What makes your founders well-positioned to accomplish your goals with this project (1-2 sentences on each)?:**
> 
>   
> 
> **Tell us about the rest of your team (if there are more teammates):**
> 
>   
> 
> **Is this your first Web3 project?:**
> 
>   
> 
> **If not, what else have you built, or what are you currently working on? (Share links, Github repository, or any other helpful information.):**
> 
>   
> 
> **Are your current Web3 projects currently funded or revenue-generating?**
> 
>   
> 
> ### Roadmap
> 
>   
> 
> **Describe in discrete steps your plan for accomplishing your project:**
> 
>   
> 
> **Please provide any additional information that will facilitate accountability: (smart contract addresses relevant to the proposal, relevant organizational wallet addresses, etc.)**
> 
>   
> 
> **Does your plan depend on the receipt of OP tokens?:**
> 
>   
> 
> **What is your plan for using the OP token after the 1-year lock-up?:**
> 
>   
> 
> ### Milestones
> 
> _Please refer to the [Milestone Assessment](https://gov.optimism.io/t/milestone-assessment/5314) guide before filling out this section._
> 
>   
> 
> **Please provide benchmark milestones for this project by extending the table below. These milestones should guide the Optimism community on the progress of your project throughout your work on the project. Do not use the distribution of the grant itself as a milestone**
> 
> |   |   |   |   |   |
> |---|---|---|---|---|
> |Project|Milestone Type|Milestone|Source of Truth|Deadline|
> |||Benchmark|||
> |||Benchmark|||
> 
> **Please define critical milestones for this project by extending the table below. Critical milestones are meant to show good-faith efforts to accomplish the project. Non-completion of these milestones could lead to the revocation of remaining grant rewards. Do not use the distribution of the grant itself as a milestone:**
> 
> |   |   |   |   |   |
> |---|---|---|---|---|
> |Project|Milestone Type|Milestone|Source of Truth|Deadline|
> |||Critical|||
> |||Critical|||
> 
> ### Optimism Relationship
> 
>   
> 
> **How does your proposal offer a value proposition for solving the above problem?:**
> 
>   
> 
> **How committed are you (and your team) to building on Optimism?:**
> 
>   
> 
> **Will your project be (a) deployed on Optimism exclusively; (b) deployed on Optimism and other networks; (c) not yet deployed on Optimism but deployed on other networks; or (d) not yet deployed on Optimism or elsewhere?**
