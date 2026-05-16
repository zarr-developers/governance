# Abstract

The purpose of this document is to formalize the governance process used by the
Zarr Project, to clarify how decisions are made and how the various
elements of our community interact.

This is a consensus-based community project. Anyone with an interest in the
project can join the community, contribute to the project design, and
participate in the decision making process. This document describes how that
participation takes place, how to find consensus, and how deadlocks are
resolved.

# The Zarr Ecosystem

The Zarr ecosystem consists of the following entities:

1. **The Zarr Project** — The umbrella entity fiscally sponsored by NumFocus.
   NumFocus-sponsored projects are required to have a formal governance process
   and may receive financial donations via the NumFocus 501(c)(3).
2. **The Zarr Specification** — A document defining the Zarr format for
   N-dimensional typed arrays.
3. **Affiliated Software Projects** — Individual software projects (including
   the specification itself, as well as implementations, tools, and conventions
   projects) which are part of the Zarr Project. These projects are eligible
   to receive funds via NumFocus and are subject to the overarching Project
   governance framework.
   This list of affiliated projects may evolve over time.
4. **Non-Affiliated Software Projects** — Other software projects which
   implement Zarr or interact with it in some way, but are not under the
   umbrella of the Zarr Project. Non-affiliated projects are not eligible
   for direct funding via NumFocus.

Governance of the Zarr ecosystem is organized into three tiers, described
below.

# Roles And Responsibilities

## The Community

The Zarr community consists of anyone using or working with the project
in any way.

## Contributors

A community member can become a contributor by interacting directly with the
project in concrete ways, such as:

- proposing, discussing, or reviewing a change to the code, documentation, or specification
  via a GitHub pull request to any https://github.com/zarr-developers repository;
- reporting a GitHub issue
  to any https://github.com/zarr-developers repository;
- discussing examples or usage issues under the #zarr tag on StackOverflow
  (like "How do I do X in Zarr?").

among other possibilities. Any community member can become a contributor, and
all are encouraged to do so. By contributing to the project, community members
can directly help to shape its future.

Potential contributors are encouraged to read the [Contributing Guide](http://zarr.readthedocs.io/en/stable/contributing.html)
as well as the [CODE OF CONDUCT](https://github.com/zarr-developers/.github/blob/main/CODE_OF_CONDUCT.md).

Anyone who has recently engaged with the project in these concrete ways, in compliance with
the Contributing Guide and Code of Conduct, is considered a contributor and can request
to be added to the relevant GitHub team. Alternatively, any existing member
of the community can invite a contributor to join.

## Tier 1: The Zarr Project — Zarr Steering Council (ZSC)

The Zarr Project as a whole is governed by the Zarr Steering Council (ZSC).
ZSC members are core developers who have additional
responsibilities to ensure the smooth running of the project.

The ZSC's responsibilities are:

1. Interface between the Project and its fiscal sponsor (NumFocus).
2. Manage the copyrights and trademarks associated with the Project.
3. Manage the list of Affiliated Software Projects, including decisions about
   new affiliations and removal of affiliations.
4. Manage responsibilities which do not belong to a specific Affiliated
   Software Project (e.g., at the time of this writing, the Zarr website; as
   well as the zarr-developers GitHub organization, social media accounts, and
   similar Zarr-owned resources) in order to ensure smooth operations and
   effective collaboration.
5. Serve as the final escalation point for disputes that cannot be resolved
   within an individual Affiliated Software Project or the Spec Committee.

The ZSC does **not** have authority over the day-to-day decisions of individual
Affiliated Software Projects or the Spec Committee, except as explicitly stated
above.

Members of the steering council also have the "owner" role within the
[zarr-developers GitHub organization](https://github.com/zarr-developers/)
and are ultimately responsible for managing the
[zarr-developers](https://github.com/zarr-developers) GitHub account, the
[@zarr_dev](https://twitter.com/zarr_dev) twitter account, the
[Zarr website](https://zarr-developers.github.io), and other similar
Zarr-owned resources.

The steering council currently contains five members. This number may be
increased in the future. The current steering council consists of

* [Ryan Abernathey](https://github.com/rabernat)

* [John Kirkham](https://github.com/jakirkham)

* [Alistair Miles](https://github.com/alimanfoo)

* [Josh Moore](https://github.com/joshmoore)

* [Norman Rzepka](https://github.com/normanrz)

ZSC members who do not actively engage with the ZSC duties are expected to
resign. New members are added by nomination by an existing ZSC member. Nominees
should have demonstrated long-term, continued commitment to the project and
its mission and values. A nomination will result in discussion that cannot take
more than a month and then admission to the ZSC by consensus. During that time
deadlocked votes of the ZSC will be postponed until the new member has joined
and another vote can be held.

The Zarr steering council may be contacted at
`zarr-steering-council@googlegroups.com`, or via the
[@zarr-developers/steering-council](https://github.com/orgs/zarr-developers/teams/steering-council) GitHub team.

## Tier 2: The Zarr Specification — Spec Committee

The Zarr Specification is the focal point that brings together all Zarr
implementations. Because it addresses the format of data at rest, decisions about the
spec will persist for decades. Ensuring responsible and careful evolution of
the spec, balancing the need for innovation with the need for stability, is
the mandate of the Spec Committee.

### Responsibilities

The Spec Committee is responsible for:

1. Managing changes to the Zarr core Specification.
2. Maintaining the list of Zarr Extensions.
3. Overseeing the ZEP process for specification changes.

### Membership

Initial membership of the Spec Committee was drawn from the members of both
the former ZSC and the former Zarr Implementation Council (ZIC). Members are
encouraged to resign if they do not plan to actively participate. It is
expected that the Spec Committee will contain members of the most active Zarr
implementations, including both Affiliated and Non-affiliated Software
Projects.

### Self-Governance

The Spec Committee is responsible for establishing and documenting its own
operational governance model, including:

* Decision-making procedures (e.g. voting mechanisms, quorum requirements,
  and use of lazy consensus)
* Membership criteria and review processes
* Meeting cadence and participation expectations

This governance model supersedes the approval processes previously defined in
ZEP0 for core specification changes.

## Tier 3: Affiliated Software Projects — Core Developers Groups

Each Affiliated Software Project is governed independently by its own Core
Developers Group (CDG). The CDG is self-governing, and its membership is
not overseen by the ZSC.

A default governance template for Affiliated Software Projects is provided
in [AFFILIATED_PROJECT_GOVERNANCE.md](AFFILIATED_PROJECT_GOVERNANCE.md).
This template establishes a meritocratic, consensus-based process akin to the
Apache model.

Projects are free to evolve and change their governance as they see fit,
provided it remains within the accepted norms of community open-source
projects. If an Affiliated Software Project abandons open and transparent
governance, the ZSC reserves the right to remove its affiliation.

All Affiliated Software Projects must adhere to the Zarr Project's
[Code of Conduct](https://github.com/zarr-developers/.github/blob/main/CODE_OF_CONDUCT.md),
which is a requirement for NumFocus fiscal sponsorship.

## Affiliated Software Project Criteria

To be considered for affiliation with the Zarr Project, a project must:

1. Be open source.
2. Be directly related to Zarr (e.g. an implementation, tool, extension, or
   convention).
3. Demonstrate a critical mass of sustained development activity.

The ZSC will make decisions about affiliation based on these criteria and the
overall strategic direction of the Project.

Non-affiliated projects may continue to operate however they wish, outside the
boundaries of this framework, with whatever governance (or lack thereof) they
choose. Non-affiliated projects are not eligible for direct funding via
NumFocus. We welcome and encourage all Zarr-related projects to become
affiliated.

# Decision Making Process

Decisions about the future of the project are made through discussion with all
members of the community. All non-sensitive project management discussion takes
place on the issue trackers of the https://github.com/zarr-developers repositories.
Occasionally, sensitive discussion may occur via a private message via the GitHub team:
https://github.com/orgs/zarr-developers/teams/core-devs

Decisions should be made in accordance with the mission and values of the Zarr project.

## Project-Level Decisions

Decisions that affect the Zarr Project as a whole (e.g. governance changes,
affiliation decisions, management of shared resources) are made by the ZSC
using a consensus-seeking process. If consensus cannot be reached, a simple
majority of the ZSC decides.

## Specification Decisions

Changes to the Zarr Specification follow the [ZEP](https://zarr.dev/zeps)
process and are governed by the Spec Committee according to its own governance
model. Please read [ZEP0000](https://zarr.dev/zeps/active/ZEP0000.html)
for the general ZEP process.

## Affiliated Project Decisions

Each Affiliated Software Project makes its own decisions according to its
own governance document. The default governance template
([AFFILIATED_PROJECT_GOVERNANCE.md](AFFILIATED_PROJECT_GOVERNANCE.md))
provides a recommended starting point based on lazy consensus and majority
vote fallback.

## The Role of GitHub

The use of GitHub by the Zarr Project is an implementation detail. GitHub
roles, groups, and repos do not have any formal status within the Zarr
governance framework.

In practice, the Zarr Project is heavily reliant on GitHub for day-to-day
operations. The following principles guide how governance maps to GitHub:

* **Principle of least privilege**: Different actors should have only the
  minimal privileges required to perform their function, minimizing the blast
  radius of any potential security threat.
* **Centralized organization**: All Affiliated Software Projects live within
  the `zarr-developers` GitHub organization, providing a central entry point
  and allowing projects to share resources. Non-affiliated projects should not
  have repositories in the `zarr-developers` organization; every repository in
  the org should either belong to an affiliated project or default to ZSC
  oversight.
* **Project-level autonomy**: Each Affiliated Software Project manages its own
  repos and GitHub team membership. Ownership of the GitHub org as a whole
  (including creation of new repos and teams) is managed by the ZSC.
* **Automated membership management**: To avoid the ZSC becoming a bottleneck
  on project autonomy, a GitHub bot or similar automation will be used to allow
  each Affiliated Software Project to manage its own team membership
  independently.
