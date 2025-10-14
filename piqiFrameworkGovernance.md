# PIQI Framework Governance
## Overview
This is a meritocratic, consensus-based community project to support the Patient Information Quality Improvement (PIQI) Framework, its reference implementations, and any supporting information. Anyone with interest in the project can join the community, contribute to the project, and participate in the decision making process. Participation in these processes is completely voluntary. This document describes how that participation takes place and how to set about earning merit within the project community. 

The PIQI Alliance consists of senior representatives of the member companies as well as subject matter experts. All representatives of the Executive Steering Committee and Community Members (described below) will participate in oversight and workflow as well as supply in-kind resources to support the technical implementation of the open standards and reference implementations to measure patient data quality.

Although these processes are adapted from the [OSSWatch Meritocratic Model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel), this documentation is a formalization of existing processes involving relevant stakeholders.

In particular, this project is a primary focus of the [Paitent Information Quality Improvement - PIQI Framework ](https://piqiframework.org).


## Roles
 
### Executive Steering Committee

The PIQI Alliance will operate by means of an Executive Steering Committee (ESC). The ESC will approve the group’s specific agenda and policy positions, establish goals and objectives, and oversee the overall direction of the Alliance. Workgroups may be created as desired by ESC members to research and address specific issues or questions. This could evolve to more formal communities of practice as the alliance matures. Each Workgroup will be composed of ESC members, Community Members, and Government Observers to ensure diverse perspectives and broad engagement.

### Community Members

The PIQI Alliance will be made up of key stakeholders, implementers, and experts in patient data quality measurement from a cross-section of the industry as designated by the ESC.

All members hold equal voices and decision-making authority. This ensures a balanced representation of perspectives and expertise in guiding the direction of the PIQI Alliance. In the event of a tie, a neutral convener within the ESC, will hold the tie-breaking vote. Any open standards will be published to HL7. Any actual technical work products (for example, implementations of evaluation profiles, Simple Assessment Modules, or other similar artifacts) will be governed under the Apache 2.0 license.

Final deliverables from the PIQI Alliance will be open source. Consequently, anyone can be a member of the community; there are no special requirements. However, the most important members in this community consist of:

·       Platform or technology owners that provide software to report on patient information quality.

·       Any business entity that used software to ingest of transfer patient information electronically (e.g. payers, providers, labs, research institutions, etc.).

### Government Observers

Data quality is a critical issue to reduce fraud, waste, and abuse (FWA) in government-sponsored health plans as well as manage the health and wellness of those members. Feedback from key agencies that are evaluating health care data will ensure PIQI will support all critical use cases for these products.


### Committers
Committers are Community Members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. New committers can be nominated by any existing committer. Once they have been nominated, there will be a vote by Executive Steering Committee (ESC; see below) and their firm must also meaningfully contribute to the PIQI Alliance [PIQI Alliance]([https://link-url-here.org](https://piqialliance.atlassian.net/)). Committer voting is one of the few activities that takes place on the private management list. This is to allow members to freely express their opinions about a nominee without causing embarrassment. Once the vote has been held, the aggregated voting results are published on the public chat. The nominee is entitled to request an explanation of any ‘no’ votes against them, regardless of the outcome of the vote. This explanation will be provided by the ESC and will be anonymous and constructive in nature.

## Decision-Making Process
The PIQI Alliance, as a community of practice, is a consensus-driven organization. The following principles and procedures will be followed. While each member will have an equal voice, no single organization will have a “veto” in the PIQI Alliance.

Decisions on the project such as whether to accept a change, add a feature, or what to include in a particular release, are made through discussion with all members of the community. Anyone is welcome to comment on proposed changes, but ultimately, the committers make the determination on accepting or rejecting a proposed change. Where committer consensus cannot be reached, the decision is escalated to the ESC. In order to ensure that the project is not bogged down by endless discussion and continual voting, the project operates a policy of consensus. This allows the majority of decisions to be made without resorting to a formal vote.

### Principles of Consensus

The following principles will be followed for all deliverables maintained by the PIQI Alliance:

Principle One: Seek informed consensus. All members have a responsibility to share and seek input for proposed changes.

Principle Two: Consensus is Not Uniform Agreement. Achieving consensus inherently involves a process of give and take amongst members. It is assumed not all members will achieve ideal positions for all proposed changes. This is recognized as normal and acceptable in the process to achieving consensus to advance shared objectives.

Principle Three: Recognize and report minority opinions. As part of the decision process, objections should be noted and acknowledged before decisions are made. This ensures that all voices are heard.

Principle Four: When there is no active objection, consent is implied. This requires careful planning for all changes. For this type of consensus to be effective, it is necessary to allow sufficient time for stakeholders to review proposed decisions before assuming that there are no objections. For more significant issues, more time must be provided to enable discussion within their organizations to consider the impacts. This will provide the framework for all members, regardless of location or other commitments, will have sufficient time to read, digest, and respond to the proposal..

Principle Five: Continuously move toward a productive conclusion. All members have a responsibility to adhere to the shared principles and values of the Alliance. Active collaboration is continuously required. This principle implies the following core goals:

·       An equal opportunity for each member to express its positions and objectives.

·       A desire to collectively engage in a consensus process to build new content and policy together.

·       Professional respect and honest dialogue to foster genuine consideration of proposals, suggestions, and positions put forward by members

### Procedures of Consensus

1. Consensus does not require perfect agreement.

Consensus means the group has reached a conclusion the entire group is prepared to endorse. 

2. Consensus does not require zero reservations or doubts, but does indicate that there is enough agreement that members are willing to support advancing the recommendation as a “consensus.” 

3. As the Alliance facilitator, Leavitt Partners will help declare when a consensus exists.

In absence of a consensus, Leavitt Partners may declare a “near consensus” which will serve as the new basis from which to work to refine thinking and achieve consensus.

4. In absence of a Near Consensus, the parties agree to move forward with the following options:

Members agree to table the issue

Issue may be addressed it at a later date, or

Group members may decide the issue is not one that is in scope for the Alliance.

In rare cases, a single member who is objecting to a broader, deeper consensus and direction of the Alliance may conclude that the work as evolved in a manner unaligned with the member’s organizational focus. In such rare case, the single member organization may choose to withdraw from the Alliance.

## Contributions
The project uses a stable-trunk methodology, meaning that the master branch must be always kept in a releasable state. This is ensured through regression tests and continuous integration is used to check pull requests to the master branch.

All changes to the main branch must be made using a pull request and must be reviewed by at least two committers that were not the author of the pull request prior to being applied.

In addition, large, significant, or breaking changes must have full committer consensus before being applied.

In general, when a new version is created, a new branch of the test repository is created to implement support for that version. Although changes to this new version branch may be committed directly, best practice is to use pull requests for the new version branch as well. Once the new version of the specification is published, the tests in this repository are added.

Note that changes must always align with the specification. Changes made in this repository will be submitted back to the informative tests published as part of the specification. Any changes to the specification itself are governed by HL7 and must be done through the HL7 process, either by submitting an STU comment, or balloting a new version of the specification.

## Communication Channels
Communication should be done in an open and public manner. The project uses many different channels for open communication, including:

- Chat
- Email
- Public discrouse on PIQIAlliance channel
  
Sometimes, communication occurs outside of these public channels, and that is okay; however, committers must summarize any private discussions that impact the tooling project in a public channel.

## Code of Conduct
In support of a healthy and inclusive community, we use and enforce a code of conduct for all members of our community, including committers and ESC members. Our code of conduct is adapted from the [Contributor Covenant](https://www.contributor-covenant.org/).

If you encounter any violation of these terms, please contact ESC members. All reports will be kept in strict confidence and dealt with promptly.

## Issues
This project uses the Github Issues tracker to track all issues and feature requests. Anyone can submit an issue at any time. Committers are generally responsible for reviewing, responding to, and resolving issues in a timely manner.

## Releases
All packages within the project shall use semantic versioning. Any stakeholder can propose a release, but the ESC must review and approve the contents and timing of any release. Specifically, releases must be coordinated with impacted stakeholders and timed with availability of published versions of the specifications involved.

The ESC is responsible for announcing releases to the community via the zulip chat. When appropriate, the ESC should also announce plans for upcoming releases to solicit feedback from the community on release content and timing.

## Change Management Continuous Improvement
This project is committed to continous improvement of code and process. While changes can happen at any time, the ESC and Committers shall formally review and discuss governance bi-annually. As with all other artifacts, consensus shall be used to approve.


 
