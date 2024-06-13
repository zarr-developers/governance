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
is always possible. The initial steering council of Zarr consists of

* [Ryan Abernathey](https://github.com/rabernat)

* [John Kirkham](https://github.com/jakirkham)

* [Alistair Miles](https://github.com/alimanfoo)

* [Josh Moore](https://github.com/joshmoore)

* [Ryan Williams](https://github.com/ryan-williams)

The SC membership is revisited every January. SC members who do
not actively engage with the SC duties are expected to resign. New members are
added by nomination by a core developer. Nominees should have demonstrated
long-term, continued commitment to the project and its mission and values. A
nomination will result in discussion that cannot take more than a month and
then admission to the SC by consensus. During that time deadlocked votes of the SC will
be postponed until the new member has joined and another vote can be held.

The Zarr steering council may be contacted at `zarr-steering-council@googlegroups.com`,
or via the [@zarr-developers/steering-council](https://github.com/orgs/zarr-developers/teams/steering-council) GitHub team.

## Zarr Implementation Council (ZIC)

The ZSC will invite Zarr implementations to participate in the management of the
Zarr specification through the Zarr Implementation Council (ZIC).
Implementations will be selected based on maturity of implementation as well as
the activity of the developer community.  Preference will be given to open
source *and open process* implementations.  Multiple implementations in a single
programming language may be invited, or such implementations could choose to
work together as a single community.

The current list of implementations which are participating in this process are
(in alphabetical order)

 * [constantinpape/z5](https://github.com/constantinpape/z5)
    represented by [Constantin Pape](https://github.com/constantinpape)
    ([May 2022 – present](https://github.com/zarr-developers/governance/issues/26))

 * [google/tensorstore](https://github.com/google/tensorstore)
    represented by [Jeremy Maitin-Shepard](https://github.com/jbms)
    ([May 2022 – present](https://github.com/zarr-developers/governance/issues/22))

 * [freeman-lab/zarr-js](https://github.com/freeman-lab/zarr-js)
    represented by [Anderson Banihirwe](https://github.com/andersy005)
    ([May 2022 – present](https://github.com/zarr-developers/governance/issues/27))

 * [gzuidhof/zarr.js](https://github.com/gzuidhof/zarr.js)
    represented by [Trevor Manz](https://github.com/manzt)
    ([May 2022 – present](https://github.com/zarr-developers/governance/issues/28))

 * [JuliaIO/Zarr.jl](https://github.com/JuliaIO/Zarr.jl)
    represented by [Fabian Gans](https://github.com/meggart)
    ([May 2022 – present](https://github.com/zarr-developers/governance/issues/18))

 * [saalfeldlab/n5-zarr](https://github.com/saalfeldlab/n5-zarr)
   represented by [Stephan Saalfeld](https://github.com/axtimwalde)
   ([May 2022 – present](https://github.com/zarr-developers/governance/issues/25))

 * [sci-rs/zarr](https://github.com/sci-rs/zarr)
   represented by [Andrew Champion](https://github.com/aschampion)
   ([May 2022 - present](https://github.com/zarr-developers/governance/issues/20))

 * [Unidata/netcdf-c](https://github.com/Unidata/netcdf-c) and
   [Unidata/netcdf-java](https://github.com/Unidata/netcdf-java)
   represented by [Ward Fisher](https://github.com/wardf)
   ([May 2022 - present](https://github.com/zarr-developers/governance/issues/21))

 * [xtensor-stack/xtensor-zarr](https://github.com/xtensor-stack/xtensor-zarr)
   represented by [David Brochart](https://github.com/davidbrochart)
   ([May 2022 - present](https://github.com/zarr-developers/governance/issues/23))

 * [zarr-developers/zarr-python](https://github.com/zarr-developers/zarr-python)
   represented by [Joe Hamman](https://github.com/jhamman)
   (Jan 2024 - present) and seconded by
   [Davis Bennett](https://github.com/d-v-b)

The Core developers of each implementation will select one representative to the
ZIC. It is up to each implementation to determine its own process for selecting
its representatives.

This member will represent that implementation in decisions regarding the Zarr
Specification and other Zarr-wide contexts which require input from
implementations.

An additional representative should also be selected to act as an alternate
for when the primary representative is not reachable.

Continued membership on the ZIC is dependent on timely feedback and votes on
relevant issues. The ZSC also reserves the right to remove implementations from
the council.

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
