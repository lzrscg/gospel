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

_Then, commit._ Make a pledge to work in an open manner for a meaningful period of time. Contributors must learn about your business and existing technology before adding value. Therefore, it is important for them to know the time doing so will be a worth investment because the knowledge they acquire about your business will be useful into the foreseeable future.

### Open source everything
#### The source code
Put code in a public version controlled repository system that allows for third-party contributions, such as Github. Put upcoming features and bug fixes in a public issue tracker so contributors can know what to build. See section 2.3 for more implementation details.

#### The business
Make internal communications, strategy documents, industry research, the internal knowledge base, roadmap etc. public. Operate in the open by publicizing what feature will be worked on next and then show that work being completed in the open source repository.

### Accept contributions
- [ ] **Set contribution guidelines** - clearly define best practices. If appropriate: require linting, code formatting, and full unit test coverage. Prefer correctness over individual developer speed (i.e. consider statically typed over dynamically typed lanugages). The project's development speed will increase by decreasing coordination overhead instead of the speeding up individual contributors. Optimze for easy code reviews, not easy contributions.
- [ ] **Set bounties** - set a value that each upcoming task is worth. Aim for compensation parity with salaried employees. If it would take a salaried employee approximately 1 week full time at $10k per month, pay $2.5k. Operate in good faith, but reject bad submissions and hold contributors to a high standard in accordance with contribution guidelines.

### Push the gas
- [ ] **Drive traffic** - while developing in public, try to bring new developers into the fold. Use the transparency of the enterprise for content marketing and build trust with a community of fans who know the mission (because it is public) and want to be a part of it. Entice them with fair compensation for their labor. There are also several bug bounty listing websites that can generate inbound traffic.
- [ ] **Retain great contributors** - convert impressive contributors to remote, salaried employees.
