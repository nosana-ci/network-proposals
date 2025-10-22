# Nosana Network Proposals (NNPs)

![logo](https://github.com/nosana-ci/.github/raw/refs/heads/main/profile/img/Nosana_Logo_horizontal_color_white.svg#gh-dark-mode-only)
![logo](https://github.com/nosana-ci/.github/raw/refs/heads/main/profile/img/Nosana_Logo_horizontal_color_black.svg#gh-light-mode-only)

Welcome! This repository is the home of Nosana Network Proposals (NNPs) — project and community proposals that shape the future of the Nosana Network. NNPs document ideas, changes, and initiatives spanning technology, governance, economics, and ecosystem development.

Our goals:
- Provide a transparent, structured path for proposing and discussing changes.
- Ensure proposals are actionable, aligned with the mission, and technically feasible.
- Empower the community to participate meaningfully in network evolution.

---

## Index of Current NNPs
| # |Title |Category |Status |
|--|--|--|--
|0001|[Tokenomics](nnp/NNP-0001-tokenomics.md)|Technical/Protocol|*Draft Submission*

## What is an NNP?

An NNP is a standardized document that proposes:
- Protocol, network, or client changes.
- Economic/parameter updates (fees, incentives, rewards).
- Governance or operational processes.
- Ecosystem funding, grants, or strategic initiatives.
- Informational standards and best practices.

NNPs live in this repository and move through a lifecycle from draft to implementation.

---

## Community Principles

- Equality: Everyone has a voice, regardless of background or stake size. We’re building open, decentralized compute for anyone with a vision.
- Constructiveness: Contributions should move the network forward—be specific, solution-oriented, and respectful.
- Transparency: Discussions, rationales, and decisions should be public and easy to follow.
- Integrity: No plagiarism, disinformation, or manipulation. Declare conflicts of interest if relevant.
- Safety: No illegal activity, hate speech, or pornographic material.

---

## Before You Submit

1. Research prior proposals to avoid duplicates or conflicts.
2. Start a discussion in the community forum/Discord to gather early feedback.
3. Validate feasibility: ensure the idea can be implemented with available or realistically attainable resources.
4. If your NNP conflicts with a proposal currently up for vote, it will only be put up for vote after a reasonable cooling-off period once the first proposal is resolved.

Proposals may be removed from consideration if they:
- Involve illegal activity or violate community standards.
- Contain hate speech or pornographic material.
- Conflict with Nosana’s mission/values.
- Are technically infeasible (this is assessed during review).

---

## NNP Lifecycle and Statuses

All NNP statuses are tracked in GitHub via labels and PR state:

1. Draft Submission
    - The author submits a PR with an NNP draft for initial feedback.
2. In Nosana Team Review
    - A focused review for scope, alignment, and feasibility. Iterations may occur here.
3. Open for NNP Vote
    - The community voting window opens (per the governance framework). The NNP is locked for changes, except critical corrections.
4. Rejected
    - The proposal does not pass review or vote. A rationale is documented.
5. Approved and on the Roadmap
    - The proposal passed and is scheduled for implementation. Timelines/milestones are added when available.
6. In Development
    - Active work is underway. Linked implementation PRs and tasks are tracked.
7. Implemented
    - The proposal has been shipped. Post-implementation notes and references are added.

Notes:
- Conflicting NNPs may be sequenced or deferred to avoid confusion and wasted effort.
- Superseded proposals should clearly reference their replacements.

---

## Voting and Governance

- Voting mechanics, quorum, and thresholds are defined by the Nosana governance framework and may be executed via on-chain mechanisms or approved governance tools.
- Final outcomes are recorded in the NNP and labeled in GitHub.

---

## Proposal Categories

- Technical/Protocol: Changes to network components, workflows, or interfaces.
- Economic/Parameters: Fees, rewards, allocation rules, incentives.
- Governance/Process: Decision-making, voting processes, roles, and operations.
- Ecosystem/Grants: Funding proposals, partnerships, developer incentives.
- Informational/Standards: Non-normative guidance, best practices, specifications.

---

## Submission Checklist

- Clear problem statement and motivation.
- Background and rationale comparing alternatives.
- Precise specification and diagrams if applicable.
- Implementation plan and milestones (if proposing changes).
- Security, privacy, and risk considerations.
- Backwards compatibility and migration plan.
- Testing/rollout plan and measurable success criteria.
- Dependencies and “Requires” references.
- Discussion threads and related links.

---

## How to Submit an NNP

1. Fork this repository.
2. Create a new file under nnp/ using the next available number:
    - nnp/NNP-####-short-title.md (e.g., nnp/NNP-0007-dynamic-fee-schedule.md)
3. Use the template below.
4. Open a Pull Request with the title: NNP-####: Short Title.
5. Add labels as applicable (e.g., Draft Submission, category labels).
6. Engage with reviewers and update your NNP as needed.

## Review Standards

- Alignment: Fits the mission and long-term roadmap.
- Feasibility: Actionable with clear steps and resources.
- Clarity: Precise, testable, and internally consistent.
- Safety: Addresses security, abuse, and user risk.
- Impact: Material benefit relative to complexity/cost.
- Community Feedback: Incorporates constructive input.

Technically infeasible proposals may be declined during review.

---

## Conflicts, Duplicates, and Supersession

- Duplicate or overlapping NNPs may be merged, sequenced, or closed.
- Conflicts with active votes are deferred until after a reasonable period post-vote.
- Superseding NNPs must clearly reference and improve upon prior work.

---

## Code of Conduct

All participants must follow the community Code of Conduct. Be respectful, collaborate in good faith, and assume positive intent. Violations may result in moderation actions and proposal removal.

---

## Security and Responsible Disclosure

If your NNP touches security-sensitive areas:
- Avoid disclosing exploitable details publicly.
- Provide a private channel for maintainers to review sensitive data.
- Coordinate timelines for responsible public disclosure.

---

## Labeling and Repository Structure

- nnp/: All proposal markdown files.
- labels: Used to reflect status and category (e.g., Draft Submission, In Nosana Team Review, Open for NNP Vote, Rejected, Approved and on the Roadmap, In Development, Implemented; plus category labels).
- docs/: Optional governance/process references if provided.

---

## Acknowledgements

This process is inspired by established governance proposal systems across open networks, including RNPs, EIPs, and similar community-driven standards.

---

## Quick Start

1. Read merged NNPs to see good structure.
2. Open a discussion to test the idea and gather feedback.
3. Write your NNP.
4. Submit a PR and label it Draft Submission.
5. Iterate with reviewers; when ready, proceed to voting per governance.

Let’s build Nosana’s future together — transparently, thoughtfully, and with impact. 🚀
