> [!info]- This post was originally published in the Governance Forum
> To view the source, please click [here](https://gov.optimism.io/t/retropgf-3-round-design/6802). Initially published on September 12, 2023 and last modified on September 13, 2023.

<span class="notvisible"></span>
![[Untitled (5).png]]
# RetroPGF 3: Round Design

Retroactive Public Goods Funding is an ongoing experiment. Each round, the Collective tries to learn and iterate on the system design. This post outlines the process & design decisions for RetroPGF 3.

To recap, these were the key points we outlined as the [[RetroPGF2 - Learnings & Reflections|learnings and reflections from RetroPGF round 2]]:

1. _**How can the Collective gather more high quality data for the evaluation of impact & profit?**_  
    Round 2 suffered from low-quality data, consisting of qualitative descriptions from projects on their impact & profit. The lack of comparable and structured indicators (quantitative and qualitative) made it hard for badgeholders to evaluate impact.
2. _**How can we scale badgeholders’ impact evaluation to accurately assess the impact & profit of all nominated projects?**_  
    In Round 2, the number of nominated projects was overwhelming for badgeholders, with some spending significant time on evaluating all nominated projects.
3. _**How do we provide better mental models and definitions for impact evaluation?**_  
    Round 2 surfaced ambiguity in both the badgeholder role description, as well as impact definition, leading to badgeholders using vastly different criteria to evaluate a project.
4. _**How can the Collective provide a better voting experience to Badgeholders? How can the Optimism community create tooling that improves the RetroPGF system for all types of participants?**_  
    In Round 2, badgeholders were faced with a far from optimal voting experience, allocating votes via one long form.

Based on the learnings above, we tried to make improvements to the design of Round 3. These design choices and their assumptions will be tested in the upcoming Round and will help us further improve RetroPGF.

**Timeline Overview**

1. Project Sign-up: Sept 19th - Oct 23rd
2. Voting: November 6th - December 7th
3. Results & Token Disbursement: Starting early January

---

## RetroPGF Sign up - gathering the right data from Projects

![[Sign-up_landing.jpg]]
_**How can the Collective gather more high quality data for the evaluation of impact & profit?**_

Retroactive Public Goods Funding is moving towards a future in which the Collective gives projects the ability to quantify their impact. The Optimist Profile is a first step towards this future, enabling projects to self-report their impact & profit and provide references to relevant data sources. Projects often know best how to measure their impact and we want to empower them to surface their impact to badgeholders as they see fit.

RetroPGF 3 is introducing an improved sign-up process:

- More detailed questions that are aligned with the impact evaluation process
- Input relevant standardized external data sources, such as Github repos or onchain contracts, to power richer analytics tooling
- Self-reported impact metrics with references to external data sources. This should help the Collective identify standardised metrics and evaluation frameworks in the future.

Note: there will be no nominations process for projects this round. Instead, projects sign-up directly. This improves the project experience, reducing the necessary steps from nominating & signing up to completing a single step.

While this improved sign-up process is only a first step towards a data rich future of evaluating impact, _our hypothesis is that this will be a vast improvement to the data gathered in RetroPGF 2 and provide badgeholders with better information to evaluate impact & profit._

## Lists - Scaling the Evaluation of Projects

![[List_showcase.jpg]]

_**How can we scale badgeholders’ impact evaluation to accurately assess the impact & profit of all nominated projects? How can we support badgeholders to more effectively collaborate?**_

No single badgeholder has sufficient knowledge or context on all nominated projects, but each badgeholder brings their unique insight and expertise within specific areas to the table.  
In previous rounds, we saw badgeholders [sharing their evaluation of projects with each other](https://gov.optimism.io/t/retropgf-round-2-voting-rationale/5570/3). In Round 3, we want to improve that collaborative effort and **enable badgeholders to share their evaluation of projects with others via Lists.**

Lists are a new form of flexible delegation.

- A List contains a set of projects, chosen from the total set of RetroPGF applicants, together with a suggested OP allocation for each project.
- Lists facilitate knowledge sharing among badgeholders, and enable badgeholders to easily replicate or modify each other’s votes.
- Each List should reference some methodology for allocating OP to each project based on the List creator’s expertise and evaluation of relevant data.

Lists allow badgeholders to leverage the expertise of other badgeholders when they cast their own votes, while maintaining the agency to combine or modify their votes based on individual preferences. This is a first step in moving the voting behaviour from a subjective review process to deciding on standardised impact evaluation frameworks.

_We expect Lists to become a valuable tool for badgeholders to collaborate and leverage each others’ expertise. Out hypothesis is that this will result in badgeholders allocating their votes among more projects than previous rounds._

## Impact Evaluation - Frameworks & Definitions

![[Untitled 1.jpg]]

_**How do we provide better mental models and definitions for impact evaluation?**_

Retroactive Funding is quite a novel and new concept among grant funding mechanisms. It requires participants to rethink how they reward projects by rewarding past impact to the Collective rather than expectation of future contributions.

Round 3 aims to provide more clarity to badgeholders on how to evaluate impact:

- Badgeholders are provided with a clearer role definition. They’re expected to be judges of impact = profit, instead of expressing their personal preferences or experiences with projects.
- Frameworks for impact evaluation are established. Defining impact more precisely is key to the success of RetroPGF. Achieving this is a collaborative effort among badgeholders.  
    This not only supports badgeholders in their voting process, but also allows projects to better understand what they will be rewarded for.

Defining impact and establishing relevant frameworks will be an ongoing effort. Round 3 will lay the groundwork in driving towards a common understanding of evaluating impact.

_Our hypothesis is that impact evaluation frameworks will result in more consensus among badgeholders and coherent voting behavior._

## Voting application - how badgeholders express themselves

![[Untitled 2.png]]

_**How can the Collective provide a better voting experience to Badgeholders?**_

In previous rounds, we’ve seen that badgeholders review and vote on tens to hundreds of projects. Voting applications that facilitates this process well will support badgeholders in their efforts and allow them to focus on the task at hand. The voting design experience and design shapes how badgeholders understand their role and drives behaviour.

Round 3 voting applications and design will allow for a more coherent experience:

- Badgeholders are able to review projects and Lists, allocate votes and submit their ballot, all within a single application.
- Project profiles and applications can be easily integrated with additional tooling
- Voting design is more aligned with the role of badgeholders roles
    - Each badgeholders allocates up to 30m OP across projects.
    - Badgeholders can choose to only use a portion of their voting power
    - Each badgeholder can allocate up to 10m OP per project
    - Results are calculated using the Median, with additional considerations.
    - Votes are private, only accessible to the Optimism Foundation for purposes of enforcing the [[Code of Conduct]]

_Our hypothesis is that these voting applications will make the job of badgeholders easier and drive voting behavior to be more aligned with RetroPGF vision and goals._

## Multiple teams, lots to build, one common vision ✨

_How can the Optimism community create tooling that improves the RetroPGF system for all types of participants?_

The more builders, researches and regens that are contributing to RetroPGF, the faster we will continue our journey to summon Ether’s Phoenix. Contributing to the development of Optimism’s RetroPGF is itself in the scope of receiving RetroPGF rewards and a nice opportunity to dogfood the system.  
RetroPGF naturally embraces plurality, allowing contributors to experiment with different ideas and embracing multiple approaches to solving a single problem.

**Core applications in development for RetroPGF 3**:

- RetroPGF Sign-up is being built by OP Labs EcoPod. This product enables projects to sign-up for RetroPGF 3.
- [Discovery & Voting RFP](https://github.com/ethereum-optimism/ecosystem-contributions/issues/104) is being built by Supermodular and Agora. These products will enable badgeholders to review and vote on projects. These will be two applications with different implementations of the voting experience, allowing badgeholders to pick and choose which application suits them better.
- [List Creation UI RFP](https://github.com/ethereum-optimism/ecosystem-contributions/issues/106) is being built by Supermodular. This product will enable badgeholders to create Lists.

Additional tooling and experimentation built by the community

- [OpenSource Observer](https://www.opensource.observer/aboutus): Analytics tooling to evaluate the impact of open source projects.
- [Pairwise](https://gov.optimism.io/t/draft-pairwise-tinder-ux-for-web3-community-signaling/6142): Pairwise comparison voting allows badgeholders to iterate on their ballots in a low cognitive effort “tinder-like” experience.
- [Community project suggestion form](https://github.com/orgs/ethereum-optimism/projects/31/views/4?filterQuery=retropgf&pane=issue&itemId=31790441): Enable community members to suggest projects that should sign-up for RetroPGF
- [BuidlGuidl experimenting with RetroPGF voting application](https://github.com/scaffold-eth/OP-RetroPGF3-Discovery-Voting)

If you’re looking for ideas on what you can build for RetroPGF head to the [ecosystem contributions page](https://github.com/orgs/ethereum-optimism/projects/31/views/4?filterQuery=retropgf) 👈

If you have an interesting experiment or project you want to propose, head to the [Governance forum](https://gov.optimism.io/c/retropgf/46) 👈