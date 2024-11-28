# Abstract

The purpose of this document is to formalize the governance process used by the
`Zarr` project, to clarify how decisions are made and how the various
elements of our community interact.

This is a consensus-based community project. Anyone with an interest in the
project can join the community, contribute to the project design, and
participate in the decision making process. This document describes how that
participation takes place, how to find consensus, and how deadlocks are
resolved.

# Roles And Responsibilities

## The Project

The Zarr project consists of the core [Zarr specification](https://github.com/zarr-developers/zarr-specs/)
and the various [implementations](https://zarr.dev/implementations/)
of Zarr in different programming languages that are hosted within this
organization. Other community implementations exist but do not follow this
governance process.

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

## Core developers

Core developers are community members that have demonstrated continued
commitment to the project through ongoing contributions to the specification,
governance, and / or implementions of Zarr.
The have shown they can be trusted to maintain the project with care.
Each implementation has its own set of core developers.
Becoming a core developer allows contributors to merge approved pull requests, cast votes
for and against merging a pull-request, and be involved in deciding major
changes to the API, and thereby more easily carry on with their project related
activities. Core developers appear as organization members on the Zarr
[GitHub organization](https://github.com/orgs/zarr-developers/people).
All core developers belong to the
[@zarr-developers/core-devs](https://github.com/orgs/zarr-developers/teams/core-devs) GitHub team
either directly or via one or more implementation-specific sub-teams.
Core developer sub-teams are given the "admin" role within the repositories that they manage. 
Core developers are expected to review code contributions while adhering to the
[core developer guide](CORE_DEV_GUIDE.md). New core developers can be nominated
by any existing core developer. For details on that process see our core developer guide.

## Zarr Steering Council

The Zarr Steering Council (ZSC) members are core developers who have additional
responsibilities to ensure the smooth running of the project. ZSC members are
expected to participate in strategic planning, approve changes to the
governance model, and make decisions about funding granted to the project
itself. (Funding to community members is theirs to pursue and manage). The
purpose of the ZSC is to ensure smooth progress from the big-picture
perspective. Changes that impact the full project require analysis informed by
long experience with both the project and the larger ecosystem. When the core
developer community (including the ZSC members) fails to reach such a consensus
in a reasonable timeframe, the SC is the entity that resolves the issue.

Members of the steering council also have the "owner" role within the [zarr-developers GitHub organization](https://github.com/zarr-developers/)
and are ultimately responsible for managing the [zarr-developers](https://github.com/zarr-developers) GitHub account, the [@zarr_dev](https://twitter.com/zarr_dev)
twitter account, the [Zarr website](https://zarr-developers.github.io), and other similar Zarr-owned resources.

The steering council is currently fixed in size to five members. This number may be increased in
the future, but will always be an odd number to ensure a simple majority vote outcome
is always possible. The current steering council of Zarr consists of

* [Ryan Abernathey](https://github.com/rabernat)

* [John Kirkham](https://github.com/jakirkham)

* [Alistair Miles](https://github.com/alimanfoo)

* [Josh Moore](https://github.com/joshmoore)

* [Norman Rzepka](https://github.com/normanrz)

The SC membership is revisited every January. SC members who do
not actively engage with the SC duties are expected to resign. New members are
added by nomination by a core developer. Nominees should have demonstrated
long-term, continued commitment to the project and its mission and values. A
nomination will result in discussion that cannot take more than a month and
then admission to the SC by consensus. During that time deadlocked votes of the SC will
be postponed until the new member has joined and another vote can be held.

The Zarr steering council may be contacted at `zarr-steering-council@googlegroups.com`,
or via the [@zarr-developers/steering-council](https://github.com/orgs/zarr-developers/teams/steering-council) GitHub team.

## Zarr Specification Core Devs

The [Zarr spec](https://github.com/zarr-developers/zarr-specs) is managed by the Zarr Spec Core Devs.
These people function in the role of "Core Devs" for the spec itself:
they have the ability to merge changes to the spec and manage the process around evolving the spec. The mandate of the spec core devs is to develop the Zarr specifications while minimizing disruption to those who depend on them, e.g. implementation developers, and the users of Zarr data. To this end the spec core devs are expected to take feedback, suggestions, and concerns from developers of Zarr implementations and Zarr users. Spec core devs should also _actively_ inform Zarr stakeholders of upcoming specification changes, in particular those changes that might affect those stakeholders. The composition of the spec core devs should reflect the diversity of Zarr implementations, to ensure that the spec evolves on a path that works for as many users as possible.

The initial spec core dev team is nominated by the steering council from the pool of currently active contributors across the project.

# Decision Making Process

Decisions about the future of the project are made through discussion with all
members of the community. All non-sensitive project management discussion takes
place on the issue trackers of the https://github.com/zarr-developers repositories.
Occasionally, sensitive discussion may occur via a private message via the GitHub team:
https://github.com/orgs/zarr-developers/teams/core-devs

Decisions should be made in accordance with the mission and values of the Zarr project.

Zarr uses a “consensus-seeking” process for making decisions. The group tries to
find a resolution that has no open objections among core developers. Core
developers are expected to distinguish between fundamental objections to a
proposal and minor perceived flaws that they can live with and not hold up the
decision-making process for the latter. If no option can be found without
objections, the decision is escalated to the SC, which will use consensus to
come to a resolution. In the unlikely event that there is still a deadlock, the
proposal will move forward if it has the support of a simple majority of the
ZSC.

Decisions (in addition to adding core developers and SC membership as above) are
made according to the following rules:

- **Minor documentation changes**, such as typo fixes, or addition / correction of a
  sentence, require approval by a core developer *and* no disagreement or requested
  changes by a core developer on the issue or pull request page (lazy
  consensus). Core developers are expected to give "reasonable time" after approval and before merging for others
  to give their opinion on the pull request if they’re not confident others
  would agree, where "reasonable time" is likely one working day.

- **Code changes and major documentation changes** require agreement by *one*
  core developer *and* no disagreement or requested changes by a core developer
  on the issue or pull-request page (lazy consensus). For all changes of this type,
  core developers are expected to give "reasonable time" after approval and before
  merging for others to weigh in on the pull request in its final state, where
  "reasonable time" is likely a few working days.

- **Changes to APIs** require a dedicated issue on the related
  issue tracker, e.g. [zarr-python](https://github.com/zarr-developers/zarr-python/issues), and follow the
  decision-making process outlined above, though "reasonable time" is likely extended
  to at least a week.

- **Changes to the specification** follow the [ZEP](https://zarr.dev/zeps)
  process. Please read [ZEP0000](https://zarr.dev/zeps/active/ZEP0000.html)
  for details and instructions to submit a new ZEP.

- **Changes to this governance model or our mission, vision, and values**
  require a  dedicated issue on our [issue tracker](https://github.com/zarr-developers/governance/issues)
  and follow the [ZEP](https://zarr.dev/zeps) process, with "reasonable time"
  being at least two weeks. However, if there is unanimous agreement from core
  developers on the change, it can move forward faster.

If an objection is raised on a lazy consensus, the proposer can appeal to the
community and core developers and the change can be approved or rejected by
escalating to the SC.
