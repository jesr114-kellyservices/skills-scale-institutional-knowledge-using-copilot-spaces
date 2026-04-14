# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Engineer / Test Engineer

### Role Summary
QA Engineers own quality assurance across the delivery lifecycle. They design and execute test strategies, validate acceptance criteria, and act as the last line of defense before production.

### Responsibilities
- Design, write, and maintain test plans, test cases, and automated test suites
- Review acceptance criteria with PdM and Developers before work begins
- Perform exploratory and regression testing before releases
- Track and triage defects with clear reproduction steps and severity ratings
- Verify that the Definition of Done (DoD) is met before a story is closed
- Coordinate with PM on test status and release readiness

### Goals
- Prevent defects from reaching production
- Reduce manual testing effort through automation
- Ensure releases are predictable and low-risk

### Typical Communication
- Participates in sprint planning and daily standups
- Shares test status reports before each release
- Files and updates bug tickets with evidence and steps-to-reproduce

### Interactions with Existing Roles
- **Developers**: Collaborate early ("shift left") to clarify acceptance criteria and testability; pair on fixing defects; review test approaches.
- **Product Manager (PdM)**: Confirm feature acceptance criteria are testable; align on what "done" looks like from a quality perspective.
- **Project Manager (PM)**: Provide test progress updates; flag quality blockers that could impact the release timeline.

### Lifecycle Touch Points
- **Planning**: Define the test approach and DoD quality gates.
- **Execution**: Execute test cases, report defects, and retest fixes.
- **Release**: Sign off on the pre-release checklist; confirm smoke tests pass.

---

## UX Designer

### Role Summary
UX Designers ensure that features are usable, accessible, and aligned with user needs. They create wireframes, prototypes, and design specifications that guide engineering implementation.

### Responsibilities
- Conduct user research, interviews, and usability tests to validate design decisions
- Create wireframes, mockups, and interactive prototypes
- Define user flows, interaction patterns, and accessibility requirements
- Provide annotated design specifications (handoff artifacts) to Developers
- Iterate on designs based on feedback from stakeholders, PdM, and usability findings

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce re-work caused by unclear or untested design assumptions
- Bridge the gap between user needs and technical implementation

### Typical Communication
- Design reviews and critiques with PdM and Developers
- Annotated Figma/design files shared as design handoff artifacts
- Usability test reports and research summaries for stakeholders

### Interactions with Existing Roles
- **Product Manager (PdM)**: Translate product requirements into user-centered designs; align on priorities and trade-offs; validate designs against success metrics.
- **Developers**: Provide detailed design handoffs; answer implementation questions; review built features against the original design intent.
- **Project Manager (PM)**: Communicate design progress and flag dependencies (e.g., design must be approved before development begins).

### Lifecycle Touch Points
- **Initiation**: Contribute to problem framing and user research that informs the one-pager.
- **Planning**: Provide design specifications in time to be included in backlog stories before sprint start.
- **Execution**: Support Developers during implementation; participate in review/demo to assess design fidelity.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for products, processes, and APIs. They ensure that knowledge is accessible to the right audiences at the right time.

### Responsibilities
- Author and maintain user-facing documentation (user guides, release notes, API references)
- Document internal processes and runbooks to support repeatability
- Collaborate with Developers and QA to document new features accurately before release
- Review PRs that add or change user-facing behavior for documentation impact
- Maintain the docs/ folder structure and ensure content stays current

### Goals
- Reduce support burden by making documentation self-serve and accurate
- Improve onboarding speed for new team members and users
- Ensure release notes are complete and understandable

### Typical Communication
- Coordinates documentation schedules with PM and PdM during sprint planning
- Raises documentation gaps in standups or via issues
- Publishes draft docs for review before release

### Interactions with Existing Roles
- **Developers**: Review technical accuracy; get early access to feature branches to document new behavior.
- **Product Manager (PdM)**: Align on messaging and user-facing copy; confirm documentation coverage before launch.
- **Project Manager (PM)**: Flag documentation tasks as delivery dependencies; ensure docs are included in the Definition of Done.

### Lifecycle Touch Points
- **Planning**: Identify documentation requirements as backlog items.
- **Execution**: Write or update docs alongside feature development.
- **Release**: Finalize release notes; ensure all new features have documentation coverage.

---

## Business Analyst

### Role Summary
Business Analysts bridge business strategy and technical implementation. They clarify requirements, validate that solutions address the right problems, and ensure alignment with organizational goals.

### Responsibilities
- Elicit, analyze, and document business requirements from stakeholders
- Translate business needs into clear, actionable acceptance criteria for the backlog
- Model and document business processes, workflows, and data flows
- Validate that implemented solutions fulfill the original business intent
- Facilitate workshops and requirement-gathering sessions

### Goals
- Ensure the team is solving the right problem with the right solution
- Reduce ambiguity in requirements to prevent re-work
- Maintain traceability from business goals to delivered features

### Typical Communication
- Requirement workshops and stakeholder interviews
- Detailed requirement documents, user stories, and process diagrams
- Sprint reviews to confirm delivered features match business expectations

### Interactions with Existing Roles
- **Product Manager (PdM)**: Co-author problem statements and acceptance criteria; validate that backlog priorities reflect business value.
- **Developers**: Answer "why" questions about requirements; clarify edge cases and business rules during development.
- **Project Manager (PM)**: Surface requirement risks and scope changes early; provide input for the risk register.

### Lifecycle Touch Points
- **Initiation**: Contribute to the one-pager with business context, stakeholder mapping, and success metrics.
- **Planning**: Elaborate backlog items into well-defined stories with acceptance criteria.
- **Execution**: Remain available to clarify requirements; validate delivered increments against business intent.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI & Ownership](octoacme-raci-ownership.md) for a cross-cutting view of who owns which artifacts and decisions across the lifecycle.

