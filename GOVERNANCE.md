# Project Governance — NEXUS-IXP-137 CORE

This document describes how the **IXP-137 CORE** project is governed:
who makes decisions, how direction is set, and what rules apply to the
evolution of the codebase and documentation.

The goal is to keep the project:
- coherent,
- safe,
- scientifically honest,
- and aligned with its **experimental** nature.


## 1. Roles and Responsibilities

### 1.1 Maintainer(s)
The Maintainer (or Core Maintainers) are responsible for:

- Overall technical direction of the project  
- Approving or rejecting pull requests  
- Managing releases and tags  
- Enforcing the License, Security Policy, and Code of Conduct  
- Clarifying the intended scope (experimental, non-operational)  

The Maintainer’s decisions are final regarding:
- scope  
- roadmap  
- feature acceptance  
- deprecation and removal of components  


### 1.2 Contributors
Contributors are individuals who:

- open issues  
- submit pull requests  
- propose ideas or improvements  
- help improve documentation  

Contributors must:
- follow `CONTRIBUTING.md`  
- respect `CODE_OF_CONDUCT.md`  
- accept that the project remains **research/experimental** only  
- not attempt to steer it toward safety-critical or operational use  


### 1.3 Users
“Users” are anyone who:

- clones the repository  
- runs the code locally or remotely  
- reads, adapts or experiments with IXP-137 CORE  

Users must:
- accept the terms of the **IXP-137 Experimental Research License (ERL-1.0)**  
- understand that the system is *not* an official or reliable early-warning tool  
- not promote the project as such to third parties  


## 2. Decision-Making Model

The project uses a **Maintainer-Driven** governance model:

- Suggestions are welcome via issues and discussions  
- Technical debates are encouraged, but must remain factual  
- The Maintainer evaluates proposals, weighing:
  - safety
  - clarity
  - scope alignment
  - technical soundness
  - complexity and maintainability  

If consensus cannot be reached, the Maintainer’s decision prevails.


## 3. Scope and Boundaries

The **non-negotiable** boundaries of the project:

- The system is **experimental**  
- It is **not** production or safety-critical software  
- No part of the repository may be marketed as an “official early-warning system”  
- The main goals are:
  - research
  - exploration
  - modeling
  - educational use  

Any attempt to extend the project into real-world operational warning
for the public is considered **out of scope** and will be rejected.


## 4. Roadmap and Evolution

The Maintainer defines a rough roadmap, which may include:

- Engine stability and crash-safety  
- New analysis modules (non-operational)  
- Better logging and observability  
- Improved documentation and examples  
- Tools for research and replay of simulation cycles  

The roadmap is **indicative**, not contractual.  
Items may be delayed, reprioritized or dropped at any time.


## 5. Repository Structure Authority

The Maintainer retains the authority to:

- reorganize directories and modules  
- rename or remove components  
- archive deprecated code  
- split parts of the project into separate repositories  

Contributors should avoid large structural changes without prior discussion.


## 6. Conflict Resolution

If conflicts arise:

1. Discuss the issue calmly and technically in GitHub issues or PR comments  
2. If needed, escalate to the Maintainer for a final decision  
3. Personal attacks, harassment or pressure are not tolerated  
4. The Maintainer may:
   - close discussions
   - lock threads
   - ban abusive participants

The **Code of Conduct** always applies.


## 7. Governance Changes

This `GOVERNANCE.md` file may be updated if:

- the contributor base grows significantly  
- new maintainers are added  
- responsibilities need more formal structure  

Changes to this document are made via pull request and must be:

- visible
- documented
- reviewed by the Maintainer


## 8. Final Statement

The IXP-137 CORE is a **research-oriented**, **experimental** project.

The governance model exists to ensure that:

- the project remains safe and honest about its limitations  
- no one repurposes it into something it is not  
- contributors and users share a clear understanding of boundaries  

By participating in this repository, you agree to abide by this governance model.
