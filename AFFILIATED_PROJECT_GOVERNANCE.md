# Governance for Zarr Affiliated Software Projects

## Overview

This document formalizes the default governance for an individual Zarr
Affiliated Software Project. It is a meritocratic, consensus-based, and
self-governing process, akin to the Apache model. The primary goal is to
empower developers, streamline the development process, and maintain the
project's stability and continuity while adhering to the overarching Zarr
Project framework as a NumFOCUS-sponsored entity.

Projects are encouraged to start with this template and adapt it to their
needs. Projects may deviate from this template for good reasons; we suggest
starting here and evolving as the project matures.

## Roles and Responsibilities

### Users

Users are members of the community who utilize the project. Their
contributions, such as providing feedback, reporting bugs, and general
evangelism, are essential for the project's purpose and direction.

### Contributors

Contributors are community members who engage directly with the project in
concrete ways, such as:

* Proposing, discussing, or reviewing a change to the code, documentation,
  or specification via a pull request.
* Reporting a GitHub issue.
* Assisting with documentation or project infrastructure.
* Supporting new users.

All community members are encouraged to contribute. Contributions should be
made in compliance with the Zarr Project's
[Code of Conduct](https://github.com/zarr-developers/.github/blob/main/CODE_OF_CONDUCT.md).

### Core Developers

The Core Developers Group (CDG) serves as the governing and administrative
body for the individual Affiliated Software Project. It is equivalent to
the Project Committee in an Apache-governed project.

* **Function:** The Core Developers have administrative rights and make
  decisions, such as accepting or rejecting pull requests, and managing
  administrative actions within the project's repositories (e.g.
  adding/removing members). A group of one is acceptable for small projects.
* **Authority:** The Core Developers Group is **self-governing** and its
  membership is **not overseen by the Zarr Steering Council (ZSC)**.
* **Membership is Merit-Based:** Any contributor is eligible to join the
  Core Developers.
  * **Nomination:** Existing Core Developers can nominate new members.
    Nominations should be based on clear evidence of **sustained, quality
    contribution** to the project. Approval is subject to vote by the
    existing Core Developers (ideally consensus, but at minimum **majority
    approval**).
  * **Removal:** Core Developers who become inactive can and should be
    removed via a **majority vote** of the existing Core Developers.
    Core developers can resign at will.

### Core Developers Chair

Larger projects should have a Chair. The Chair's role is to act as a
**coordinator and facilitator** for the group's activities and discussions.
The Chair holds no additional authority over other Core Developers. The
Chair is optional for smaller projects.
A chair is selected by a consensus of core developers or, if consensus is not reachable, a majority vote.
Rotation of chair duties is encouraged but not required.

## Decision Making Process

Decisions should be made in accordance with the mission and values of the
Zarr Project.

### Consensus-Seeking and Voting

Core developers are empowered to make decisions for the project, which mostly comes down to deciding whether or not to merge pull requests.
Such decisions can range from very minor (e.g. fixing a type in the docs) to massive.

Decision making is via the Consensus process, as defined by the [Apache Software Foundation](https://community.apache.org/committers/decisionMaking.html).

The first step is Lazy Consensus:
>  Essentially lazy consensus means that you don’t need to get explicit approval to proceed, but you need to be prepared to listen if someone objects.

Lazy Consensus is achieved by stating your intent on a public GitHub issue. If no one objects within 72 hours, the developer can proceed with the proposed action. Lazy consensus is appropriate for minor, non-controversial changes.

For larger, more impactful decisions, Consensus Building may be a more appropriate process.
Consensus Building occurs via a discussion on GitHub where community members can share their feedback. Again, we follow the Apache way:

> Sufficient time should be provided for members of the community to express opinions, and defend objections. It is customary for the initiator of the discussion to post a summary of the discussion once it appears that consensus has been reached, to ensure that their understanding of the will of the community is accurate.

Finally, if consensus appears truly unreachable, a core developer may call for a vote, which occurs via a GitHub issue or PR.

### Lazy Consensus for Day-to-Day Operations

Lazy Consensus is used for most day-to-day decisions, allowing the majority
of contributions to proceed efficiently.

* **Minor Documentation Changes** (e.g. typo fixes): Require approval by a
  Core Developer and **no disagreement or requested changes** from any Core
  Developer within a reasonable time (e.g. one working day).
* **Code Changes and Major Documentation Changes:** Require agreement by
  **one** Core Developer and **no disagreement or requested changes** from
  any Core Developer within a reasonable time (e.g. a few working days).
* **Objections:** If a Core Developer raises an objection to a proposal
  under lazy consensus, the proposal is escalated to the full group for a
  consensus-seeking discussion or a majority vote.

## Code of Conduct

All Affiliated Software Projects must adhere to the Zarr Project's
[Code of Conduct](https://github.com/zarr-developers/.github/blob/main/CODE_OF_CONDUCT.md),
which is a requirement for NumFocus fiscal sponsorship.

## License and Attribution

This governance document is adapted from the original Zarr governance
document and the
[Meritocratic governance model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel)
by Ross Gardler and Gabriel Hanganu (licensed under a Creative Commons
Attribution-ShareAlike 4.0 International License).
