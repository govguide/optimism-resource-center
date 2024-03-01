> [!info]- This post was originally published on the Mirror blog
> To view the source, please click [here](https://optimism.mirror.xyz/Bbu5M1mTNV2Z637QxOiF7Qt7R9hy6nxghbZiFbtZOBA). Initially published on February 29, 2024.

<span class="notvisible"></span>
Retroactive Public Goods Funding (Retro Funding) is an economic flywheel that rewards positive impact to the Optimism Collective. Without public goods funding, core tools and infrastructure required to keep blockchains running and ecosystems thriving might not have the resources for ongoing operations, or building their vision in the first place. Optimism’s vision is to create a strong incentive for the creation of public goods, resulting in an ecosystem where collaboration becomes the winning strategy.

The Collective is running Retro Funding as an ongoing experiment where insights and learnings from each round inform the design of future experiments.

Below is a summary of the [[RetroPGF 3 - Round Design|key design changes of RetroPGF 3]], which were identified based on the [[RetroPGF2 - Learnings & Reflections|feedback from RetroPGF 2]].

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FIvnHpr6ZzA-dv4aJ2D4R4.png&w=3840&q=75)

## **Key learnings from Retro Funding 3**

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FaqehAYjllqtHyK1cCU9vO.png&w=3840&q=75)

Here are the key learnings from RetroPGF 3:

1. The broad round scope overwhelmed badgeholders and applicants.
    
2. The absence of standardized, verifiable, and comparable impact metrics, and the reliance on individual subjective review criteria, made it difficult to objectively measure the impact of applications.
    
3. The self-selection of applications to review by badgeholders did not ensure a fair review by a minimum number of badgeholders of each application.
    
4. The sheer volume of applications, combined with weak eligibility criteria, complicated the voting process for badgeholders. Lists were not effective in scaling the ability of badgeholders to accurately vote on more applications.
    

These learnings were derived from 300+ crowdsourced pieces of feedback, collected via [a survey among badgeholders](https://optimism.deform.cc/retropgf3-feedback), the RetroPGF 3 feedback [Gov Forum post](https://gov.optimism.io/t/retropgf-round-3-feedback-thread/6177/1), as well as the badgeholder Discord/Telegram channel and will inform the next iteration of Retro Funding.

Below we document these learnings in detail as part of a gradual process to open source Optimism governance design. This post is non-exhaustive and aims to focus on the core learnings and most popular requests.

# Analyzing the results

1. **Scale**: RetroPGF 3 sets a unique precedent in terms of scale. The number of eligible applicants rose by 330% round over round, with the number of recipients increasing from 195 recipients in RetroPGF 2 to 501 recipients in RetroPGF 3. The amount of OP tokens given to builders within the Optimism Collective far exceeds any comparable grant program in crypto.

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2Fobpprl-CwAeIyBcnfC5wM.png&w=3840&q=75)

2. **Low variance**: The results of RetroPGF 3 do not reflect outsized impact well. The difference in rewards between a top 1% recipient vs a median recipient was about 6X (300K vs 45K).

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FQArX3C3cVUmVBMkws3ZLg.png&w=3840&q=75)

3. **Smaller teams, and individual applications, received an outsized reward compared to bigger teams.** The top project - Protocol Guild - received 660K OP split across over 100 full-time contributors, which is about 6K per contributor. By comparison, there were 112 individual applicants for RetroPGF that received a combined 1.7M, or about 15K per application.

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2F2M74Yav01Jx6zOqV7lZQM.png&w=3840&q=75)

4. **Rewarding Optimism specific contributions**: The results lacked prioritization of builders that drive the adoption of Optimism. The focus has been to reward Ethereum public goods at large, with the top 30 recipients almost exclusively made up of public goods which are not specific to Optimism but power the Ethereum ecosystem at large.  By comparison, the top 20% of projects in terms of sequencer fee revenue contributions received only 5% of rewards. (See above the Retro Funding 3 OP Token Allocation among OP Mainnet applications)

For further detailed evaluation of the results, check out [analyses of the results by Optimism Contributors](https://gov.optimism.io/t/retropgf-3-results-analyses-proofs/7657#results-calculation-1) and specifically [Open Source Observers work](https://mirror.xyz/cerv1.eth/CGS5QsqoX9k5_puYopug4SWODm06OAGwOPWiEil2v0U), who provided insights and the above graphics for this section.

# Application Process

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FJYvUwPikvKKV87dc0226u.png&w=3840&q=75)

To participate in RetroPGF 3, projects and individuals were required to submit an [application](https://www.optimism.io/retropgf-app). This process has been simplified based on feedback from RetroPGF 2, where builders had to be nominated (including self-nomination) and submit an application to qualify.

The application process took place from Sept 19th - Oct 23rd 2023 and saw a total of 1594 applicants. Following the application process, a self-selected set of [[RetroPGF 3 - Application Review Process|badgeholders reviewed applications]] that were reported for violating the RetroPGF application rules. The review process followed a jury-like design where badgeholders were randomly sorted into groups to vote on excluding applications from the round based on the application rules.  The application review process took place from Oct 24th - Nov 1st with [1,035 reported applications reviewed and 967 applicants excluded from the round](https://gov.optimism.io/t/retropgf-3-application-review-process-results-feedback/7075).

The newly introduced application form resulted in a vast improvement in the quality of applications compared to previous rounds. Application content was more aligned with the voting process and featured external data sources, such as references to Github repos and onchain deployments, which has been used to power analytics tooling such as OpenSource Observer. The quality of the application flow received positive feedback:

- “It's a very smooth process!”
    
- “I mean this form is pretty neat, the best submission form I have seen in any grant program” - Eduardo
    
- “I just created a profile for the DoD on the RetroPGF-3 website and experienced no technical issues. It's a very smooth process!” - Afri
    

## Bugs, errors & timeline

Still, the application form had room for improvement. Users experienced a number of issues, including the input of inaccurate impact metrics and  grant amounts on a handful of applications due to a bug in dealing with European decimal points. A number of these [errors persisted in the final applications](https://gov.optimism.io/t/retropgf-3-reported-application-errors/7136), as applications were editable during the application period, but could not be changed after. Extending the application period, from 2 weeks (in RetroPGF 2) to 4 weeks in RetroPGF 3, had minimal impact, as the vast majority of users [submitted their application close to the deadline](https://dune.com/queries/3045651/5065422).

## **Application rule violations**

In comparison to RetroPGF 2, which excluded a total of 2 applications from the round based on technicalities, RetroPGF 3 dealt with an overwhelming amount of spam and application rule violations, with 967 applications excluded. This was likely related to the application process starting shortly after [[Airdrop 3|Optimism Airdrop #3]], resulting in a large influx of airdrop farmers. In addition to excluding spam, many badgeholders have voiced [feedback that the application process should be improved to protect against low quality submissions](https://gov.optimism.io/t/retropgf-3-application-feedback/6866) and that there should be stronger eligibility criteria. Badgeholders rated the overall quality of eligible projects and their applications as 6.9 out of 10 points on average.

- “There is no “skin in the game” for spammers. The cost of submitting a spam application is very low, and as we all saw, this can cause a LOT of work for reviewers.” - Michael Vandermeiden
    
- “still feel like there a decent amount of candidates that aren't spam, but shouldn't be listed. I'm if the opinion that if a badgeholder is presented with a candidate, they should already have a clear argument for prior impact” - Brian Lehrer
    
- “Many projects applied for Retro Funding but didn’t make a tangible impact on Optimism collective since RPGF2. It’s okay not to apply if you haven’t made an impact. Applying and pretending to have an impact is NOT okay.” - Rev
    

## Collecting the right information

The information requested from applicants did not include the reporting of venture funding, which has received [significant pushback from badgeholders and the broader community](https://gov.optimism.io/t/retropgf-3-application-feedback/6866).

- “I find the fact that VC funding info is not requested but then donations and grants info are requested really bad.” - Lefteris
    
- “In the future I think projects need to be required to disclose their funding sources.” - ZachXBT
    
- “It’s crucial to disclose private/VC funding in RPGF applications for fairness.” - Rev
    

Further, the application process missed an effective categorization scheme. Applicants could select one or multiple categories of impact, based on the round scope. The multi-selection of categories made filtering functionality in the voting applications unviable.

- “This is probably one of the largest and most important problems to solve. How can a very large list of projects be categorized such that a voter can select just categories in which they have expertise and not be overwhelmed.” - Tam

Due to self-reported impact metrics, applications saw a lack of verifiable impact claims and the use of vanity metrics. Metrics were not standardized, which made comparisons among projects hard. The [majority of referenced data sources](https://github.com/opensource-observer/insights/blob/main/analysis/optimism/retropgf3/notebooks/2023-10-07_RPGF3_Impact_Metrics.ipynb) were links to Etherscan, Github, Dune Analytics, Twitter and Google docs.

- “I’d like to see better impact reporting by applicants. Not sure if that’s an addition to the form or just guidance/template but I was influenced a lot by looking at Carl’s spreadsheet of onchain transactions and Github metrics.” - Chris Carella
    
- “Projects can choose to miss lead badge holders. This was shown, at least by one particular project in which the only presented revenue that had been already handed to them, but decided to hide the data of committed OP they would be receiving after a one-year lock.” - LauNaMu
    

### Takeaways:

1. While the application form has been a vast improvement to round 2 and fulfilled its core goals for Round 3, further improvements should be made to leverage reliable data on impact and power standardized impact metrics.
    
2. There should be stronger eligibility criteria to participate in RetroPGF and the application review process needs to be improved to reliably enforce these criteria.
    
3. Optimism badgeholders should have an opportunity to provide feedback on the application form before it’s finalized. This allows the team to react to emerging feedback, such as the request for VC funding to be disclosed, while possibly slowing down the iteration cycle.
    
4. The multi-selection of impact categories had a negative impact on applicant discovery and added difficulty to the voting process, categorization should be improved to aid the discovery and voting process.
    
5. The application window can be shortened, as deadlines are the real driver of submissions.
    

# Evaluating Impact

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FbgjmnnmpDqH4-sW8erDN2.png&w=3840&q=75)

Voting took place from November 6th - December 7th 2023 and featured a total of 145 [[Citizenship|badgeholders]] and 643 applicants. As was done in previous RetroPGF rounds, badgeholders were provided with a [Badgeholder manual](https://www.optimism.io/badgeholder-manual) which outlined rules and guidelines for the voting process. Included in the manual were guidelines on how to apply the principle of “impact = profit”, an overview of the voting design and its implications, as well as relevant references to the Code of Conduct.

Following through on feedback and learnings from RetroPGF 2, badgeholders were provided with a clearer role definition, in which they were asked to make holistic judgements in applying “impact = profit”, rather than expressing their personal preferences for a particular applicant. This additional context was positively received by badgeholders, especially first-time voters.

- “The Badgeholder manual was a great reference, but too static for the dynamic nature of the voting process.” - Amer
    
- “Overall well laid out and all very useful information.” - Amy
    
- “I believe clearer guidelines for badgeholders could streamline the process. PS: The badgeholder manual was immensely helpful to me in this round!” - Joao Kurry
    
- “...as a new badgeholder I felt very welcomed, the onboarding process was smooth, roles and obligations are clear, the gov team is always ready to address any question.” - Willian
    

The badgeholder manual included an [Impact Evaluation Framework](https://gov.optimism.io/t/retropgf-3-impact-evaluation-framework/7037), created by [LauNaMu](https://twitter.com/0xyNaMu) in collaboration with the Optimism Foundation, which aimed at providing mental models and definitions for impact evaluation (a goal of round 3). It outlines audiences, definitions, and metrics on impact for each of the four categories of scope. The framework has shown useful to support badgeholders in building a deeper intuition on scope, impact and useful metrics, while it functioned more as a tool for highly committed badgeholders to design their own framework, rather than being directly applicable to reviewing projects. You can find a retrospective on the Impact Evaluation Framework [here](https://mirror.xyz/launamu.eth/fFkhrGqjAYg5LT-PCdGFCdc7O-BOLLU45GEm72HdAYI).

- “The Category Frameworks were somewhat helpful. I think the content could be more succinct. The keywords and metric garden were good examples. I used them to create a list of potential impact metrics I should be looking for. “ Amy
    
- “I know the intention was to give everyone wide berth to design a methodology. That was actually a great way to get a lot of smart people to experiment with different solutions. Though it took some time for me personally, doing this for the first time, to build my methodology and then tweak it as I had new insights.” Tam
    

The badgeholder manual and Impact Evaluation Framework provided guidance for evaluating impact, but did not provide frameworks directly applicable in voting. Badgeholders voiced feedback that impact should be more closely defined to be applicable in voting:

- “I do wish that the Profit = Impact framework is better explained and explicitly enforced” - Alex
    
- “There's a big amount of confusion on what "impact" means, and it's really varying across the board on how people are interpreting it. I understand why Optimism may want to leave this open, but I feel like without taking a more opinionated stance on this, there will be constantly infighting on what it really means to drive impact.” - Brian
    
- “Positive impact is yet another vague term” - Lefteris
    

## Round Scope

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2F8OMgC-ZVlA7zFNWETpWbS.png&w=3840&q=75)

RetroPGF 3 featured a [[Announcing RetroPGF Round 3|broad scope]] made up of four categories: OP Stack, Collective Governance, Developer Ecosystem and End User Experience & Adoption. The scope did not specify a time period for which impact should be rewarded, and left it to badgeholders to reward impact within a selected timeframe. This broad scope resulted in a lack of clarity regarding eligibility for some of the applicants and made it difficult to promote the program to relevant builders and to drive the creation of relevant contributions to Optimism.

Common feedback has been to tighten the scope, either around common attributes of applicants (such as separating rounds for individuals and projects) or common contribution types (such as separate rounds for developer tooling and education). A universal demand has been to reduce the number of applicants and introduce rounds with a more focused scope.

- “It feels chaotic with all these different types of projects in a single round.”
    
- “In the future having more small rounds might make sense. I am kinda dreading going over such a huge corpus of projects and know there is no feasible way to really give them all a fair shake.” - Ricmo
    
- “The biggest piece of feedback from the last round was that the volume of projects applying was overwhelming, but somehow this round we ended up with 6 times the amount of projects, so it feels like that piece of feedback wasn’t heard. Imo there needs to be some kind of barrier to entry for applicants, and not put the responsibility entirely on badge holders to review such an insane amount of projects, most of which are out of scope.” - Katie
    
- “The sheer volume of applications that needed to be processed by each badgeholder was overwhelming.“ - Mitch
    
- “I find it pretty reassuring that others are struggling a bit with the number of projects, was worried that I was missing a trick somewhere!” - MinimalGravitas
    
- “I started going through the projects (there are so many...) but I'm far behind.” - Joav
    
- “in general I felt like my attention was stretched very thin.” - Brian
    
- “Smaller periodic capped rounds makes a lot of sense, it would make it a lot easier to measure relative impact” - Nick
    
- “Agreed here, I think more focused & defined rounds with smaller amounts of OP (and a better built in screening process) would be a great experiment for RPGF.” - Matt
    

## **What is a public good and can it be VC funded?**

There has been a broad discussion about the role of venture funding in RetroPGF. Viewpoints ranged from the belief that VC funded projects should be excluded from RetroPGF to VC funding having no relevance to the evaluation process. This debate was far reaching across the Ethereum Community, with many different perspectives and topics of discussion. Please refer to [this summary of the different viewpoints on VC funding and the Optimism Foundation’s perspective](https://gov.optimism.io/t/the-role-of-vc-funding-in-retropgf/7342).

This discussion highlighted that there has been a lack of communication of the intentions of Optimism’s RetroPGF to the broader Ethereum community. Often, RetroPGF is understood as a charity, which takes care of projects in need. In stark contrast, the intention behind RetroPGF has always been to create a new economic system, in which there is an incentive for providing impact to the Optimism Collective.

Beyond VC funding, a very popular debate has been the definition of “public goods” and what it should or shouldn’t include.

- “There was some stark discussion on what constitutes public good, and I truly believe that trying to form a definition suitable for all citizens would lead to our downfall. Our biggest power is diversity in our background, person, and professional, and I would like to keep the stage open for everyone to share their definition.” - OP User
    
- “While the idea of impact = profit is great, I think making an impact, or being a positive for the ecosystem, does not necessarily mean it’s a public good.” - Wesley
    
- “Retroactive Public Goods Funding is a well-meaning label, but in practice it has been woefully misunderstood. “Public goods” is especially misleading, since it causes people to think only of pure public goods and miss the majority of what the program is trying to [reward].” - Spencer
    
- “Concerns around widely used Optimism applications being mostly left out of the round feel legitimate when reading the actual descriptions (e.g. "onboarding new users"), but clash with people's intuitive understanding of "public goods".” - Tim Beiko
    

This has been a hotly debated topic in all three rounds of RetroPGF. It is questionable if the debate of what constitutes a public good actually advances the goals of RetroPGF, or if it is more religious in nature. An outcome from this debate in RetroPGF 1 was the establishment of [[RetroPGF  Impact = Profit Framework|impact = profit]], the principle that the value a contributor has created for the Optimism Collective should equal the value a contributor has extracted from the Optimism Collective. In round 3, guidelines have further emphasized that the goal of RetroPGF is to reward impact and fill the gap between a contributor's impact and profit. The [economics definition](https://en.wikipedia.org/wiki/Public_good_(economics)) of pure public goods (e.g. non-rivalrous, non-exclusionary) does not apply to a large set of highly impactful contributions to Optimism and the Ethereum ecosystem. For example: hackathons, applications that drive Optimism sequencer revenue, free services that are only available to a subset of users & builders, any hosted service, etc. may all provide positive impact to the Collective, even if they do not fit within the traditional economics definition of a pure public good.

Instead of exploring the characterization of the individual goods and services and the definition of “public goods”, our focus should be to closely define the outcomes (i.e. impact) we want to incentivize. Over-applying the classical economic definition of public goods may prevent us from rewarding important contributions to Optimism. One of the more applicable outcomes discussed by badgeholders is the incentivization of open source software, either by providing their creators with outsized rewards or by exclusively rewarding software with an open source license.

- “If it's a closed source freemium product that will cease to exist once it's company dies it's not a public good” - Lefteris
    
- “...if the product is closed source, and I would urge badgeholders to vote 0 on applications that made it to the voting phase” - Willian
    
- “I’ve been pretty clear that I prioritised bootstrapped teams, providing genuine open source public goods, over accelerated, funded teams that can entrench a product or service before introducing fees or withdrawing.” - Nickbtts
    

### **Takeaways:**

- The broad scope and high number of applicants had a significant negative impact on the round.
    
- Impact was not defined in such a way that it can be directly applied in voting, adding difficulty to the work of badgeholders.
    
- Discussions on the definition of public goods do not directly support the Collective in defining the types of impact it wants to reward.
    
- The Collective did not provide sufficient clarity on the goals of RetroPGF, which made constructive discussions within the wider Ethereum community difficult.
    

# Voting design & behavior

### **Voting Design**

RetroPGF 3 voting design calculated individual projects' rewards using [[RetroPGF 3 - Round Design|the median with a minimum quorum requirement of 17 badgeholder votes]], an iteration based on the [[RetroPGF2 - Learnings & Reflections|learnings of RetroPGF 2]], which leveraged the mean of badgeholder votes. While an improvement to round 2, the implications of this design were quite counterintuitive, compared to voting designs which are more common. Badgeholders also flagged that [there’s more room for research and iteration of this voting design](https://gov.optimism.io/t/retropgf-3-results-analyses-proofs/7657#analyse-results-2).

- “I think median actually fixes a lot of flaws from the first round. Median seems like a much better solution for: a. preventing collusion (need much more voters to impact results) b. allowing badgeholders to vote based on area of expertise (projects not penalized for being on fewer ballots) both a. and b. are extremely important as we try to scale up this process” - Michael Vandermeiden
    
- “I am super curious about a variety of maths being run over the dataset. It feels like median isn’t necessarily the exact correct approach. Even if not changed for this round, seeing a variety of outcomes could help influence future rounds. :)” - Richard
    
- “…I agree that median is probably not the best choice and is quite counterintuitive” - Krzysztof Urbański
    

### Quorum

The quorum heavily impacted both the badgeholder and applicant experience. Applicants were in fear of not meeting the quorum and reached out to badgeholders en masse to maximize their chances of success. A small unrepresentative poll showed that each badgeholder received more than 15 DMs from applicants. This created a dynamic which was perceived more like a popularity contest, than an exercise in objectively evaluating the past contributions of each applicant:

- “Projects not making (or not likely to make) quorum are incentivized to promote to every badgeholder so they can get any RPGF. Projects likely to make quorum are incentivized to not promote or only promote to badgeholders who "love" their project, e.g. people already impacted directly (or observe impact) from their project, so they maximize RPGF.” - abcoathup
    
- “Some applicants may even have gotten the impression that desperation and shilling was necessary to make quorum; my own impression is that the rapid increase in ‘ballots’ on the last days of voting had more to do with the fact that many badgeholders had until then been busy working in offline spreadsheets and simply didn’t use the voting software until very late in the process.” - joanbp
    
- “Now, RPGF feels skewed and personally, a bit like a popularity contest.” - 0xzenodotus
    
- “I don't think groups should be advertising their "impact" because then it is a game where the best advertisers win.” - lightclient
    

### **Voting behavior**

Making data-informed voting decisions was difficult due to the breadth of projects’ impact (a result of the wide scope), as well as a lack of comparable metrics and contributions (a result of the application process). Combined with the number of applications, this led to a cognitive overload and in what some framed as a “spray and pray” approach to voting. A low accuracy judgment on a large number of applicants was preferred to making a high accuracy judgment on a small number. Creating [simple qualitative evaluation frameworks](https://docs.google.com/spreadsheets/d/13_omIPXbvEukklwIVK2lm-lbf1W3BfQEOfRxWp6ij5k/edit?usp=sharing) has been a common way to approach this goal of judging a large number of applications.

- “comparing aragon with department of decentralization - impossible “ - Krz
    
- “Citizen House needs to vote in specific, objective qualifying criteria. Not important to get every project - more important to capture most valuable projects with minimizing overhead for badgeholders.” - Polynya
    
- “The sheer volume of applications that needed to be processed by each badgeholder was overwhelming. While I could have focused on just my area of expertise I think its a responsiblity to provide judgement on as many projects as possible.” - Mitch
    
- “Spray and pray is a natural reaction to cognitive overload and limited bandwidth. However, our focus shouldn't be solely on creating more efficient tools for spraying. A new feature like a CSV upload button would make the work go faster, but it still encourages us to spray. What we actually need are better ways of designing, iterating, and submitting complete voting strategies.” - Carl
    

Badgeholders could self-select which applications to vote on. This resulted in selection bias, in which some badgeholders selected applications which they were already familiar with, and thought positively of, while not voting on applications which they were not familiar with or thought negatively of. The self-selection method does not guarantee that each application is receiving a review from a minimum number of badgeholders, making it less likely for an unknown applicant to meet quorum.

In its third iteration, RetroPGF still relies on manual human review of individual applications.

It’s questionable how accurate and efficient RetroPGF can become in rewarding impact, if its allocation decisions rely on individuals selecting which applications to vote on and then subjectively evaluating their impact. Core to improving Retro Funding is the advancement of reliable measurement of impact:

- “Fundamentally, this requires a shift from vibes-driven to data-driven [rewards]. Data is critical for badgeholders to transition from working at the middle of the grants funnel (i.e., reviewing individual projects) to working mostly at the top and bottom of the funnel (i.e., deciding what forms of impact matter most and reviewing the distribution formula).” - Carl

RetroPGF 3 has made significant advancements towards data driven decisions in the category of open-source contributions and onchain deployments. OpenSource Observer demonstrated how existing data can be used to create “[impact vectors](https://mirror.xyz/cerv1.eth/qL9YKLN9-dBzM89qKaZYgHK2ccpZy2XLPz2Z1PObwCg)”, a quantitative impact metric measured over a discrete period of time, to enable badgeholders to express their preferences for the types of impact that should be rewarded, rather than evaluating the impact of individual applicants.

### Takeaways:

- While a vast improvement to RetroPGF 2, the implications of the voting algorithm were difficult to understand and leave room for further research and improvement
    
- The quorum requirement had a negative effect on the applicant and badgeholder experience, transforming the process into what some perceived as a popularity contest.
    
- The broad scope of projects and lack of comparable metrics made data-informed voting decisions difficult. Despite the challenges, there was a movement towards more data-driven decisions in evaluating open-source contributions and on-chain deployments.
    
- The self-selection of applications to review by badgeholders does not ensure a fair review by a minimum number of badgeholders for each application.
    

# Badgeholder Collaboration

### **Scaling Impact Evaluation**

One of the main experiments within RetroPGF 3 was the introduction of [Lists](https://round3.optimism.io/lists), which allowed badgeholders to share their proposed votes on a number of applications with others. The goal of Lists was to allow badgeholders to focus on evaluating applications within their area of expertise and leverage the evaluation from other badgeholders. Thus the individual workload would be reduced.

Lists provided value to badgeholders in allowing for the curation and discovery of relevant applicants but lacked overall effectiveness in driving specialized applicant evaluation.

Badgeholders have voiced that the lack of requirements to create a List and missing curation made this tool less effective and possibly harmful to the overall process.

- “There’s no level of expertise required to make a list, so we’re seeing a large amount of lists that include low impact projects which then highlights them to other badge holders.” - Katie
    
- “Lists are counter productive. I feel that lists almost certainly lead to group think, winner-take-all, and allow badgeholders to be lazy” - tjayrush
    
- “I wish more badgeholders would have made lists that reflected their personal expertise and careful judgement, taking the full complexity of our task into consideration. There were a couple of lists of this kind, and I found them useful.” - joanbp
    
- “okaish with this, I think my main suggestion is to make them editable, at least at the UI/UX level. It was also mentioned as causing bias, but I don’t have a strong opinion on it; If each badgeholder does their job, it shouldn’t be a concern.” - Joxes
    
- “List: I highly recommend keeping them. The only suggestion is to make the amount of $OP optional. If possible, provide an option to sort the list according to priority. This feedback is not only mine; I had a chat with other badgeholders, and they share similar thoughts.” - OPUser
    
- “I found Lists hepful for discovery, but counter-productive for allocations. Moving forward, if we’d keep the Lists, let’s focus on impact analysis & comments” - Rev
    

The majority of the top 20 Lists, categorized by the number of events triggered by badgeholders, did not include a clear rationale for the allocation of OP or references to used frameworks.

Badgeholders were allowed to include their own projects within their list, while it was recommended to disclose this conflict of interest in the List description. A handful of cases could be observed where this ruleset was abused to promote one’s own application.

A dilemma which became apparent in the List creation process is that badgeholders who are experts within a particular field usually also work in this field and are associated with one or multiple applications. If we expect the number of badgeholders to increase, and RetroPGF to reward more impact, we should expect more badgeholders to work on projects that are part of RetroPGF. To ensure an unbiased process, [more research into collusion and bribery resistance is crucial](https://jobs.optimism.io/companies/optimism-unlimited/jobs/33626632-governance-research-and-experiments-lead#content).

### **Badgeholder Collaboration**

One of the goals of round 3, based on feedback from RetroPGF 2, has been to support badgeholders to more effectively collaborate. Feedback has shown that the facilitation of async coordination among badgeholders needs to be improved. Specifically, badgeholders demanded more effective methods to share knowledge with each other:

- “ Each badgeholder is “on their own” in the sense that I can’t really see what other badgeholders are thinking” - tjayrush
    
- “Badgeholders need a better way to unify their knowledge and research. In RPGF3, knowledge sharing happened through a variety of chats, X, blogs, etc. But during a review of applications, there was no way to learn “what do badgeholders know about this application?” - Michael Vandermeiden
    
- “It become a bit hard to keep up with the announcements, important dates and links between all the other chatter in telegram. Maybe a separate announcement channel would be helpful” - Manasi
    
- “Telegram was too chaotic with that many people.” - Amer
    
- “Maybe it makes sense to have some sort of in-line forum on each profile page? So that the badgeholders can raise concerns and the project owner can dispute them? With some sort of curation to concisify the convo if the signal to noise becomes lousy.” - Ricmo
    

Multiple calls took place to facilitate open discussions, as well as workshops to dive deeper into impact evaluation. These activities received a mixed sentiment of feedback. It is important to note that different people process data differently so striking a balance here is key.

- “Way too many pointless zoom meetings. Admin should focus on written and off-line organization a la the badgeholder manual.” (Anon)
    
- “I found the office hours really helpful. In terms of workshops, I’m not sure if it was just the dynamics of my group, but I left the Impact Evaluation Workshop with more questions than answers.” - Amy
    

### **Badgeholder workload & experience**

Survey responses have shown that the median badgeholder spent 16 hours participating in RetroPGF 3, with some spending significantly more time.This time investment was largely the result of the time intensive and manual labor of making subjective judgements on the impact of a large number of applicants.

- “However, I can say for myself that I have spent hundreds of hours (yes, literally) on RPGF3 since I got my badge - learning about Optimism and RPGF, reviewing, categorizing and prioritizing applications, researching, making lists, participating in workshops and meetings, discussing and giving feedback, voting, etc.” - Joanbp
    
- “There is WAY too much work to be a “good” badgeholder. I’ve felt guilty since the start because I don’t have the time to do what I feel like I’m supposed to do” - tjayrush
    
- “Being a badgeholder is quite a bit of work these days 😅” - Ethernaut
    
- “Weird af. But being a badgeholder is not simple. It's actually a lot of work. Many many more hours of work than initially advertised. At least for me. And I see more people put in a lot of hours here.” - Lefteris
    

While very labor intensive, badgeholders rated their overall experience to 7.6/10 points on average. This high rating is likely a result of a sense of purpose and community in participating in the single biggest Ethereum public goods Retro Funding experiment, rather than excitement about reviewing a large pool of applications.

Some badgeholders went above and beyond in their work to ensure the round was successful. While this commitment may be one of the most positive signals coming out of the round, it is not a sustainable approach to future iterations of RetroPGF.

### **Takeaways**:

- Lists were valuable for curating applications but lacked creation requirements and were not effective in driving specialized evaluations.
    
- Badgeholders expressed a need for better asynchronous collaboration tools and clearer communication channels. The current methods, including various chats and forums, were insufficient for effective knowledge sharing and coordination.
    
- The workload of individual badgeholders is unsustainable and needs to be reduced
    

# Voting Infrastructure & Tooling

In RetroPGF 2, badgeholders had very minimal voting tooling, [including a form with 195 applicants to allocate votes to](https://app.deform.cc/form/85e65189-6679-4a13-908e-c42ea3cf1498). One of the goals of RetroPGF 3, based on feedback and learnings from RetroPGF 2, has been to create tooling that improves the RetroPGF system for all types of participants.

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FqZNtXE3hqSWNhSeBHrD4A.png&w=3840&q=75)

### **Seven Teams built tooling or infrastructure for voting in RetroPGF 3**

Community-built tooling in RetroPGF 3 demonstrated how an open collaborative environment can build products that support experimentation and address user needs. Badgeholders were equipped with two frontends they could leverage to review applications, use Lists, and submit their votes: [vote.optimism.io](https://vote.optimism.io/retropgf/3/summary) built by [Agora](https://www.voteagora.com/#Home) and [round3.opimism.io](https://round3.optimism.io/) built by West. These frontends were built via a [Foundation Mission](https://github.com/ethereum-optimism/ecosystem-contributions/issues/104), which outlined requirements, specifications and designs for the voting functionality.

Community-built tools like [Pairwise](https://www.pairwise.vote/) and [retrolist.app](https://retrolist.app/) allowed badgeholders to create Lists.  [OpenSource Observer](https://www.opensource.observer/) made analytics about open source projects easily accessible. [RetroPGFhub.com](https://retropgfhub.com/retropgf3) and [GrowThePie](https://www.growthepie.xyz/optimism-retropgf-3) allowed for better discoverability of applications as well as providing additional data about projects.

### **Performance**

The backend infrastructure to collect votes, as well as an API to query relevant data was built by Agora to be used by two frontends. Agora supported builders by extending access to the API, which was used by 8 unique clients. While Agora was up 99.65% of the time, users experienced severely degraded performance for 5-6 hours during the last day of voting. You can find Agora’s retrospective on RetroPGF 3 [here](https://www.voteagora.com/blogs/rpgf-retro).

- “Both Apps seemed to have a hard time with the load as they experienced really bad downtime and lists, projects dissapearing/ not being available during critical moments of the voting process.” - Mitch
    
- “Voting app had a lot of technical difficulties. I understand that they are still figuring out how to scale and handle load, but would love to see improvements in the next round”
    

Popular feature requests included the ability to import votes via CSV, better discoverability and filter functionality as well as more functionality for knowledge sharing among badgeholders.

- “Extremely unfortunate that there was no way to import CSV so it had to all be added back to the interface manually. :/” - Amy
    
- “I used [West’s voting platform 4](https://round3.optimism.io/), and overall I found it quite intuitive and easy to use. For the next round of RPGF it would be good to add a) functionality for editing, forking, removing lists, and b) ballot import/export functionality to support the people working offline with spreadsheets - this would also be useful at times when the servers are experiencing overload.” - Joanbp
    
- “We should have the option to write notes on applications for ourselves (i.e. non public). And e.g. have buttons to indicate if we want to vote for them or not (“Yes”, “No”, “Maybe” or blank), and then use that to filter applications.” - CheekyGorilla
    
- “it would be great if there was a "hide from view" for projects that i have looked at and evaluated as not a candidate / that i will not be allocating towards / voting to” - Jenny
    
- “I have a few pieces of feedback I shared with the agora team before voting started that I think could make it better-have the ability to mark a project as seen or “don’t put in ballot” option-have the ability to allocate percentages as well as dollar amount-get rid of the lists function” - Katie
    
- “I lost my list several times (and even when restored, I lost some of my work). At many times Agora was so slow that it was unuseable. This not only was a frustrating and painful experience, it was draining and took away time that I could have used to better vote.” - Amer
    

Pairwise, [which received a mission grant from the Token House](https://gov.optimism.io/t/final-pairwise-tinder-ux-for-web3-community-signaling/6142), was created to allow badgeholders to easily create Lists by comparing a number of applications within a specific category, leveraging a pairwise comparison method. Feedback from badgeholders showed that Pairwise was useful for discovery of relevant applications but was less popular when it came to iterating on votes. 27 badgeholders have connected their wallet to Pairwise, and 5 badgeholders have used Pairwise to create Lists. You can find [Pairwise’s Retrospective here](https://gov.optimism.io/t/pairwise-retrospective-and-proposed-spec-for-retropgf-4/7479).

- “On kickoff day, I was initially excited about Pairwise's List creator due to its apparent ease of use. However, after dedicating over 50 hours to evaluating various projects and lists, I have decided to take a more oldschool way. I found that the pairwise list is somewhat lacks convincing depth….” - thesleeper
    
- “Use of Pairwise: I think this application as a discoverer fulfills its function, it is excellent, but I would not reference the resulting amounts in any way, only percentages, as a starting point.” - Joxes
    
- “I probably put about two hours into using the app. I found it helpful for discovery / curation but not for coming up with a voting strategy.” - Carl
    

Open Source Observer, [which received a builder grant](https://app.charmverse.io/op-grants/page-37085606550601957),  allowed badgeholders to view top level metrics of applicants Github, NPM packages and onchain contracts. Further, OS Observer provided an export of relevant data via CSV, to allow badgeholders to leverage data in their voting. While OS Observer’s approach is promising, it saw limited usage by badgeholders.

- “excellent for tracking repositories, recommended and I hope it continues like this and better for the next round.” - Joxes

Work on West’s voting interface (round3.optimism.io) has been continued and open sourced as [EasyRetroPGF](https://github.com/gitcoinco/easy-retro-pgf) by Gitcoin. Allowing other communities to experiment with Retroactive Funding.

### Takeaways:

- The infrastructure and tools provided to badgeholders has significantly improved. An experimental approach to tooling, with iterations based on badgeholder feedback, has emerged.
    
- The infrastructure, upon which many applications and tooling relied, saw significant downtime and degraded performance.
    
- The voting application(s) can be further improved to support the reviewer experience.
    

# Key learnings

While each round provides a lot of learnings, we want to prioritize specific areas which have received the most attention from badgeholders.

![](https://optimism.mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FiozEONwW6olTb9NzbeX3L.png&w=3840&q=75)

1. The broad round scope overwhelmed badgeholders and applicants.
    
2. The absence of standardized, verifiable, and comparable impact metrics, and the reliance on individual subjective review criteria, made it difficult to objectively measure the impact of applications.
    
3. The self-selection of applications to review by badgeholders did not ensure a fair review by a minimum number of badgeholders of each application.
    
4. The sheer volume of applications, combined with weak eligibility criteria, complicated the voting process for badgeholders. Lists were not effective in scaling the ability of badgeholders to accurately vote on more applications.
    

These learnings will inform the next iterations of Retroactive Public Goods Funding. To stay in touch with the evolution of Retro Funding [you can follow updates and discussions in the Optimism Governance forum](https://gov.optimism.io/c/retropgf/46).

Once more we improved Retro Funding based on past learnings, rewarded the builders, researchers and educators who are at the heart of Optimism and learned a ton to improve the next iteration. Together we will summon [[Ether's Phoenix]] 🕊️.

And, as always,

Stay Optimistic! 🔴✨