# Zarr Format Working Group Charter

## Overview

The Zarr Format Working Group (ZFWG) is responsible for the stewardship and evolution of the Zarr Format including the specification and the extension ecosystem.

The Working Group provides an open forum for proposing, discussing, reviewing, and deciding changes to the specification. It seeks to balance the needs of current and future implementations while promoting interoperability and the long-term health of the broader Zarr ecosystem.

The Working Group conducts its governance through open, asynchronous participation whenever practical, enabling broad participation across time zones and organizations.

This charter establishes the responsibilities, membership, and guiding principles of the Working Group. The detailed procedures used to evaluate proposals and make decisions are maintained separately and may evolve over time, provided they remain consistent with this charter and the Zarr Project Governance.

## Roles and Responsibilities

### Working Group Members

Working Group Members (Members) collectively steward the Zarr Format Specification.

Membership is merit-based and recognizes sustained contributions to the specification and the broader Zarr ecosystem. Contributions may include specification development, implementation experience, technical review, interoperability testing, documentation, community building, or other activities that advance the goals of the Working Group.

New Members are nominated and approved by the existing Working Group Members through a Formal Vote. Members who become inactive may be removed by the Working Group by a Formal Vote, where the Member in question is recused.

Non-normative: The composition of the Working Group Members should seek to represent all the major implementations in the ecosystem.

Current Members are:


| Member | Zarr Implementations Represented | 
| - | - |
[Josh Moore](https://github.com/joshmoore)* | | 
[Norman Rzepka](https://github.com/normanrz)* | [`zarr-java`](https://github.com/zarr-developers/zarr-java) (Java), [`zarr`](https://github.com/zarr-developers/zarr-python) (Python)
[Jeremy Maitin-Shepard](https://github.com/jbms) | [TensorStore](https://github.com/google/tensorstore) (C++, Python)
[Lachlan Deakin](https://github.com/ldeakin) | [`zarrs`](https://github.com/zarrs/zarrs) (Rust)
[Davis Bennett](https://github.com/d-v-b) | [`zarr`](https://github.com/zarr-developers/zarr-python) (Python) |

_*: denotes a member of the Zarr Steering Council_

The Working Group is responsible for:

* maintaining the [Zarr Format Specification](http://github.com/zarr-developers/zarr-specs/) including the [Zarr Extensions Registry](https://github.com/zarr-developers/zarr-extensions/);  
* evaluating proposals to modify the specification;  
* making decisions regarding the evolution of the specification;  
* documenting significant decisions and their rationale;  
* considering the impact of decisions on the broader Zarr ecosystem, including implementers, downstream users, and interoperability;  
* coordinating with implementers and the wider community;  
* approving Zarr Extensions;  
* approving and publishing new releases of the Zarr Format Specification.
The Working Group has administrative privileges over the following resources:
 * the [`@zarr-developers/zarr-specs`](https://github.com/zarr-developers/zarr-specs) GitHub repository
 * the [`@zarr-developers/zarr-extensions`](https://github.com/zarr-developers/zarr-extensions) GitHub repository
 * the [site hosting the published specification](https://zarr-specs.readthedocs.io).
 * the [`@zarr-developers/format-wg`](https://github.com/orgs/zarr-developers/teams/format-wg) GitHub team 
### Chair

The Working Group may appoint a Chair and Vice Chair from among its Members through a Formal Vote (see below).

The Chair coordinates the activities of the Working Group, facilitates asynchronous discussion, helps build informed consensus, and ensures that proposals and decisions progress in accordance with the Working Group's documented decision process. The Chair does not possess authority beyond that of any other Working Group Member.

The Vice Chair assists the Chair and acts in their place when necessary.

The Working Group is encouraged to rotate the Chair every year at the latest. Where practical, the Vice Chair should succeed the Chair at the end of a term to promote continuity while sharing responsibility across the Working Group.

Current Chair and Vice Chair are:

- Tbd (Chair)  
- Tbd (Vice Chair)

### Community

Everyone else in the community is welcome to participate in the development of the Zarr Format Specification by proposing ideas, contributing specification text, reviewing proposals, sharing implementation experience, identifying interoperability concerns, or participating in discussions.

Participation must follow the Zarr Project Code of Conduct.

## Decision Process

The Working Group seeks to make specification decisions through informed consensus. If consensus cannot be achieved, a simple majority of the Working Group decides except where specified differently below.

Discussion is encouraged to explore ideas, identify concerns, and improve proposals. Specification decisions should be made only after participants have had a reasonable opportunity (2 weeks) to review a proposal and significant technical concerns have been considered.

The Working Group conducts its decision making asynchronously wherever practical. The primary venue for proposals, discussion, review, and decision records is GitHub. Meetings and other communication channels may be used to exchange ideas or resolve questions, but decisions should be made and recorded through the documented process below to ensure that all Members have a reasonable opportunity to participate. The sections below correspond to different types of decisions which each require different procedures. The Working Group distinguishes between **Specification Decisions**, **Specification Releases**, **Extension Decisions**, and **Governance Decisions**.

### Specification Decisions

Changes to the specification are made through PRs in the zarr-specs repository. Anyone from the Community or the Working Group may open PRs. Merging PRs into the “main” branch requires approval from Members:

- If unanimous approval is reached, the PR may be merged right away.  
- If at least 33% of Members approve the PR and there have been no objections raised by other Members for 2 weeks (starting from the first approval), the PR may be merged.  
- If there remain objections after 2 weeks, the discussion should be extended or a Formal Vote may be called.

Please note that creating specification releases or amending earlier specification releases require the procedure as described below.

If at any time, a Member believes the decision process is stalled, they can unilaterally call for a Formal Vote (see below).

### Specification Releases

The publication of a new version of the Zarr Format Specification (including point releases) is a decision of the Working Group with lasting implications and therefore requires a Formal Vote (see below).

Specification releases should reflect a coherent, stable, and well-documented state of the specification. In reaching a release decision, the Working Group should consider the completeness of the specification, implementation experience where appropriate, interoperability, and the interests of the broader Zarr ecosystem.

Amending earlier specification releases should only be done as a last resort. But if necessary, it also requires a Formal Vote (see below).

The procedure for creating a specification release or amending earlier specification releases is:

1. Open a PR with a new specification version  
2. Call a Formal Vote  
3. If approved, merge and make a release tag  
4. Announce the new version to the community using various communication channels (e.g. blog posts, social media, forum posts)

### Extension Decisions

The Working Group maintains the Zarr Extensions Registry. PRs for new extensions and updated extensions are reviewed by the Working Group based on the criteria specified in the Readme of the Github repository.

Any Member can unilaterally approve and merge such PRs, if they believe the criteria are being met. However, there should be reasonable time (72h) left for other Members to raise concerns between opening and merging the PR.

If any Member believes consensus on an Extension Decision cannot be reached, a Formal Vote can be called. 

### Governance Decisions

Certain decisions have lasting implications for the governance and stewardship of the Working Group and therefore require a Formal Vote (see below).

The following are Governance Decisions:

* admitting a new Working Group Member;  
* removing a Working Group Member;  
* appointing or removing the Chair or Vice Chair; and  
* adopting amendments to this charter.

Amendments take effect following approval by the Zarr Steering Council, which verifies that they remain consistent with the Zarr Project Governance.

## Formal Vote

- A motion can be proposed by any Member in a Github issue (by tagging the Working Group (@zarr-developers/format-wg)) or by email (via mailing list), if it needs to be held in private.  
- Members vote on the motion by a Github comment or by replying to the email.  
- We allow two weeks for voting after a motion is proposed.  
- If after two weeks a majority of Members has voted and all votes agree, the majority vote becomes the decision.  
- If there are any disagreements within the initial two week voting period, a further two weeks will be allowed to try and reach consensus.  
- If after 4 weeks there is no consensus, the majority vote becomes the decision.

## Code of Conduct

The Working Group operates under the [Zarr Project Code of Conduct](../CODE_OF_CONDUCT.md). All participants are expected to contribute respectfully and constructively.

