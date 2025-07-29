# SpeleoDB - Open Source Governance Model

## Overview

The SpeleoDB.org project operates under the 501c3 non-profit "Underwater Speleological and Archeological Heritage Institute" (also known as USAH Institute).

The open source governance model follows a three-tier governance structure designed to balance technical excellence, community input, and organizational sustainability. This model ensures that decisions are made transparently while maintaining the non-profit's mission and legal obligations.

## Governance Bodies

### 1. Board of Directors (BOD)

**Purpose**: Provides strategic direction, ensures legal compliance, and maintains the non-profit's mission.

**Responsibilities**:
- Set high-level organizational goals and vision
- Provide funding and administrative support
- Ensure all activities comply with non-profit status requirements
- Maintain veto power over decisions that conflict with the non-profit's mission or legal status
- Establish and maintain the Code of Conduct
- Nominate members to the Technical Steering Committee
- Ratify Explorer Advisory Board nominations
- Handle legal, financial, and administrative matters

**Composition**:
- 3-5 members serving 2-year terms
- Initial members appointed by founding members

**Decision Making**:
- Decisions by majority vote
- Veto requires 2/3 majority
- Quorum: 60% of members

### 2. Technical Steering Committee (TSC)

**Purpose**: Guide technical development, make implementation decisions, and maintain project operations.

**Responsibilities**:
- Set technical direction and roadmap
- Review and approve technical proposals
- Maintain project infrastructure and operations
- Coordinate release cycles and versioning
- Propose members for the Explorer Advisory Board
- Ensure technical decisions align with BOD directives
- Foster community contributions
- Maintain technical documentation standards

**Composition**:
- Lead project maintainer leads the committee.
- BOD members can attend and vote on the discussion 
- 3-7 members with demonstrated technical expertise
- Nominated by the BOD
- Serve 2-year renewable terms

**Decision Making**:
- Technical decisions by lazy consensus
- Formal votes require simple majority
- Must operate within BOD directives

### 3. Explorer Advisory Board (EAB)

**Purpose**: Provide domain expertise and community feedback to ensure the project serves the speleology community effectively.

**Responsibilities**:
- Provide guidance on feature priorities
- Share field experience and use cases
- Review proposals from a practitioner perspective
- Act as liaisons to the broader speleology community
- Participate in user testing and feedback cycles

**Composition**:
- 5-15 members representing diverse speleology communities
- Proposed by TSC, nominated by BOD
- Serve 1-year renewable terms

**Authority**:
- Advisory role only (non-voting) 
- Recommendations considered by TSC and BOD
- Ability to influence the road map by writing "feature request" 

## Operational Procedures

### Decision Making Framework

1. **Day-to-day technical decisions**: TSC has autonomy
2. **Major technical/direction changes**: TSC decides, BOD informed
3. **Strategic/policy changes**: BOD approval required
4. **Community feedback**: EAB consulted on user-facing changes

### Communication Channels

- **Each member of any board** will receive: Slack, Email. Google Drive
- **TSC**: Will meet on a quaterly basis (or more frequent if necessary) to review the recent changes and decide on the next targets
- **EAB**: More flexible - can meet virtually/in-person/informally/asynchronously whenever feedback is requested (pull) or given (push). It is of good practice and expected to touch base at least once every 6 months.

### Conflict Resolution

1. Technical conflicts: Resolved within TSC
2. Strategic conflicts: Escalated to BOD
3. Code of Conduct violations: Handled by BOD-appointed committee

## Standing Delegations

The BOD delegates the following authorities to the TSC:
- Technical architecture decisions
- Tool and technology selection
- Release management
- Contributor access management
- Technical documentation standards

## Transparency Commitments

- All decisions documented and publicly accessible
- Meeting minutes published within 7 days
- Roadmaps and plans shared openly

## Amendment Process

Changes to this governance model require:
1. Proposal submitted to BOD
2. BOD approval (2/3 majority)

## Initial Bootstrap Phase

During the non-profit's first year:
- All positions are appointed by the lead project maintainer: Jonathan Dekhtiar
- BOD established first, then TSC, then EAB
- First nominations begin after 12 months

---

# Code of Conduct

[To be developed by the BOD]

---

# Technical Steering Committee Charter

## Mission

Guide the technical development of SpeleoDB to best serve the global cave diving, exploration, survey and scientific community while maintaining high standards of quality, interoperability, and sustainability.

The technical committee will guarantee transparency and data secrecy. SpeleoDB is not an open data sharing platform. The TSC and BOD will ensure that nobody accesses data they should not have access to.

## Scope

- Data standards and formats
- Software architecture and design
- API specifications
- Integration protocols
- Quality assurance processes

## Operating Procedures

### Meetings
- Quaterly video conferences
- Emergency meetings as needed

### Decision Making
- Lazy consensus for routine matters
- Formal vote for major decisions
- All decisions documented in public repository

---

# Explorer Advisory Board Guidelines

## Purpose

Bridge the gap between technical development and field requirements by providing practical insights from active cave explorers and researchers.

## Participation Expectations

- Attend one semi-annual meeting (video-call or in-person) with at least 1 member of the TSC.
- Provide feedback on proposed features
- Share field experiences and challenges
- Test beta releases when possible
- Respect confidentiality when required

## Communication

- Feedback surveys after major releases
- Direct channel to TSC for urgent issues
- Writing "Feature Request" for any idea that needs to be discussed by the TSC.