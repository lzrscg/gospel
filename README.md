# Global Open Source Permissionless Enterprise League (GOSPEL)

> This document is a work-in-progress. The ideas are presented authoritatively, however, they may not work for everyone. Pull requests and feedback are welcome. If you believe in the GOSPEL's mission, please contribute your findings.

We live in a new world. With increased global Internet connectivity and a large-scale transition from physical to information-based labor, new paradigms must emerge if organizations are to adapt to this new landscape. There is no one-size-fits-all approach, but GOSPEL recognizes the potential to radically optimize work flows to this new environment. If traditional, non-Internet-native, geography-based work is a single-core processor, this document attempts to lay out a specification for a distributed system. The Internet does not completely overturn the old principles governing how organizations operate. However, it should cause an operator to make different choices and sacrifices after taking the big picture into consideration. This allows them to take advantage of the massive increase in output that a distributed system can bring.

**About the Author:** LZRS is a software developer with experience:
* Managing community contributions and working as an engineer at a prominent cryptocurrency company
* Founding a startup with cofounders and employees in radically different timezones and countries
* Most recently, building software supporting COVID-19 immunization and working as a tech lead at one of the world's largest vaccine distributors

LZRS has been greatly inspired by some personal friends who have had success building global workforces, as well as the thought leadership of Balaji Srinivasan.

## In a nutshell
GOSPEL is targeted at commercial tech enterprises and has three tenets.
1. **Operate globally**
    * Communicate via long-form writing.
    * Execute asynchronously.
2. **Open source everything**
    * Make source code, internal communications, and business strategy public.
    * Some things may need to be proprietary, but that should be the exception and not the norm.
3. **Enable permissionless contributions**
    * Since everything is open source and globally optimized, allow anyone in the world read the source code or business strategy and get paid to contribute (i.e. fixing a bug in the app).
    * Contributors may still be able to opt for salaried employment.

These three tenets work in concert to provide enterprises with certain benefits:
* **Better talent.** 
  * _The purpose of hiring globally is to access a larger pool of highly skilled labor, not to cut costs._ 
  * Permissionless contributions enable enterprises to tap into the global talent pool without experiencing the significant friction of navigating foreign labor markets.
  * Contributors can be pseudonymous and are compensated based on merit. This provides opportunities to those excluded from the traditional hiring process and allows enterprises to utilize underrated talent.
  * Top talent often prefers the flexibility of remote, asynchronous work.
* **A more robust organization.** 
  * Long-form written communication extracts important information out of the heads of individuals and small teams, and places it into version control. 
  * Problems are often detected earlier in open source projects because there are more eyes on them.
  * Optimizing for permissionless contributions makes it easier to replace lost personelle.
* **Becoming a nexus of industry.**
  * Transparency builds good will among customers and the community.
  * Sharing implementation and execution details attracts talent when they are trying to learn.
  * An enterprise is constantly creating internal content, but wasting valuable opportunities to use it for content marketing due to unnecessary confidentiality.
* **The potentional to attain "workforce autoscaling"; by simply paying more, a workforce can be blitzscaled with few bottlenecks.**

## The playbook
This playbook is for **software company** operators. It expores specific considations that must be taken into account when enacting the three tenets.

### Levels of contribution
1. **Task delegation**
    * A contributor completes a task according to its specification.
    * _Example:_ coding a well-specified feature for an app.
2. **(Technical) product management**
    * A contributor specifies a task that must be completed to acheive a strategic goal.
    * _Example:_ designing the specification for the feature mentioned above in accordance with the roadmap.
3. **Strategy**
    * A contributor lays out, at a high level, what the company ought to do. 
    * _Example:_ creating the roadmap that indicates the need for the feature specification mentioned above.

As the levels increase, the operator's mindset must change from that of a bureaucratic manager to that of an asset allocator. The operator has capital to spend and must invest in a portfolio of features and strategies, each with their own execution risk. 

This playbook is built from real experience and not theory. **Due to the experience of the author(s), it only discusses level 1 contributions.** However, GOSPEL believes higher-level contributions are possible and has a mandate to explore them further. If you have experience with this, please consider contributing your findings.

### Decide and commit
_First, decide._ Is this right for the enterprise? If so, is there any information that cannot be shared publicly? Exclude such information when open sourcing everything.

_Then, commit._ Make a pledge to work in an open manner for a meaningful period of time. Contributors must learn about the business and existing technology before adding value. Therefore, it is important to make them comfortable investing time to learn about the enterprise. They need to be assured that this knowledge they are working to acquire will be useful for many contributions to come.

### Open source everything
#### The source code
Put code in a public Github repository or use a similar platform. Put upcoming features and bug fixes into a public issue tracker so contributors can know what to build and submit pull requests.

#### The business
Make business information public. This includes:
* Internal communications
* Strategy documents
* Industry research
* Internal Knowledge Base
* Roadmap

### Accept contributions
#### Establish roles
* **Technical Lead** The leader responsible for ensuring code quality in a repository or a portion of a repository. The technical lead also assess the difficulty of tasks and sets bounty targets (subject to financial constaints and oversight).
* **Code Reviewer** A developer that reviews code contributions to see if they should be merged or rejected. This is often the technical lead, but could also be a trusted developer on behalf of the technical lead.
* **Finance Lead** A person, group of people, or system that sets budgets and has the authority to approve or reject spending on code contributions. The finance lead should have minimal involvement and give the technical lead as much autonomy as possible.

#### Set contribution guidelines
Clearly define best practices. If appropriate: require linting, code formatting, and full unit test coverage. Prefer correctness over individual developer speed (i.e. consider statically typed over dynamically typed lanugages). The project's development speed will increase by decreasing coordination overhead instead of the speeding up individual contributors. Optimze for easy code reviews, not easy contributions.

Document architecture decisions. This allows contributors to get a better idea of which approach they should take.

#### Set bounties
Set a value that each upcoming task is worth. Aim for compensation parity with salaried employees. If a task would take a median salaried employee approximately 1 week full-time at $10k per month, pay $2.5k.

If nobody is fulfilling a given task, raise the bounty. However, this is assuming that enough capable developers have seen it. If they have not, then try driving more traffic to it (see Traffic Strategies).

#### Be firm yet compassionate
Operate in good faith, but reject bad submissions swiftly and hold contributors to a high standard in accordance with contribution guidelines.

A contributor's best effor may not be good enough. For example, a junior engineer may submit unreadable code or not notice a certain class of bug. The code reviewer must quickly reject this contribution and the contributor must not get paid. Ideally, the code reviewer will be able to point to where the submission can be improved, but this can be a time-intensive exercise and therefore must be done at the discretion of the code reviewer.

The onus is on the contributor to find a way to add value given that all information is available. The contributor might need to spend time studying the enterprise's codebase and operations more in-depth, attempting to make contributions along the way, and earning trust before getting a contribution accepted.

With that said, the enterprise must operate in good faith. Good contributions ought to be rewarded in a timely manner and opportunities to contribute must be as plentiful as the enterprise can afford. Further, providing feedback to genuine contributors is a great way of building a more robust community of developers.

### Traffic Strategies
while developing in public, try to bring new developers into the fold. Transparency is a compentitve advantage. Use public information as content marketing and build trust with a community of fans who know the mission and want to be a part of it. Entice them with fair compensation for their labor.

Content is king online. Turn business and architectural decisions into blogposts. Show your work. Build a community around people who care about the enterprise, its mission, and each other. Adopt the spirit of a community-oriented project that everyone has an opportunity to profit from if they are able to add value.

There are also several bug bounty listing websites that can generate inbound traffic. More on traffic generatorion in a later section.

### Retain great contributors
Convert impressive contributors to remote, salaried employees. Aim for pay parity if they worked full-time as a permissionless contributor. Attempt to always raise the bar when deciding who to put on salary. The best hire is someone who is able and willing to do code reviews and act as a technical lead. This is a force multiplier and typically deserves extra pay. However, even if certain contributors do not wish to interact with the community, it is valuable to reserve 100% of their time by putting them on salary.
