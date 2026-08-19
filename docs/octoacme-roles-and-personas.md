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

## Program Manager (PM)

### Role Summary
The Program Manager owns program-level coordination across multiple related projects and ensures alignment to strategic objectives.

### Responsibilities
- Align project roadmaps and priorities across a program
- Resolve cross-project dependencies and impediments
- Coordinate executive reporting and program-level stakeholder updates
- Facilitate resource allocation across projects and initiatives

### Interactions
- Works with Project Managers to align priorities and resolve cross-project conflicts
- Escalates strategic issues and resource constraints to Sponsors and senior leadership
- Coordinates with Release Manager on program release windows and constraints
- Partners with Product Managers to align program outcomes with product strategy

### Goals
- Deliver program outcomes aligned to business strategy
- Minimize cross-project friction and duplicated effort
- Provide clear executive visibility into program progress

### Typical Communication
- Monthly program reviews and executive briefs
- Cross-project dependency boards and planning sessions

---

## Delivery Lead

### Role Summary
The Delivery Lead focuses on execution for larger initiatives that span multiple teams — ensuring delivery cadence and dependency management.

### Responsibilities
- Manage inter-team dependencies and delivery timelines
- Enforce delivery cadence and milestone discipline
- Monitor milestones and unblock delivery impediments
- Coordinate integration points and end-to-end testing schedules

### Interactions
- Partners with Technical Leads for technical decisions and implementation planning
- Reports progress and risks to the Program Manager and Product Owner
- Works closely with Project Managers to ensure task-level tracking and status
- Coordinates with QA and Release Manager for release readiness

### Goals
- Achieve predictable delivery across integrated teams
- Reduce rework due to misaligned timelines or unclear handoffs

### Typical Communication
- Cross-team standups for integration points
- Milestone reviews and readiness checklists

---

## Release Manager

### Role Summary
The Release Manager owns release planning and deployment coordination to ensure safe, timely, and well-communicated releases.

### Responsibilities
- Maintain the release calendar and schedule release windows
- Run release readiness checks and gates (code freeze, validation, rollback plans)
- Coordinate deployment stakeholders (DevOps, QA, Product, Support)
- Track release-related risks and communication artifacts

### Interactions
- Coordinates with Technical Leads and Developers to confirm technical readiness
- Works with QA Lead to ensure test coverage and acceptance criteria are met
- Partners with Change Manager / Ops to schedule deploys and rollback plans
- Notifies Product Managers and Stakeholder Representatives of release contents and timelines

### Goals
- Reduce release incidents and post-release hotfixes
- Ensure clarity on who approves, schedules, and executes releases

### Typical Communication
- Release readiness meetings and deployment runbooks
- Release notes and stakeholder notifications

---

## Risk Owner

### Role Summary
A Risk Owner is assigned for each identified risk and is accountable for tracking and driving mitigation actions.

### Responsibilities
- Maintain and update the risk register for assigned risks
- Track mitigation activities and deadlines
- Trigger escalations when predefined thresholds are met
- Communicate risk status and residual exposure to Project/Program Managers

### Interactions
- Collaborates with Project Managers to surface and track project risks
- Reports high-severity or systemic risks to the Program Manager and Sponsor
- Engages Subject Matter Experts (e.g., Technical Leads, Security) to define mitigations

### Goals
- Reduce unexpected impacts through early mitigation
- Ensure clear ownership and timely escalation for critical risks

### Typical Communication
- Risk review cadence in status meetings
- Risk logs and decision records

---

## Stakeholder Representative

### Role Summary
The Stakeholder Representative acts as the primary contact for a key stakeholder group to consolidate feedback and ensure their needs are considered in decision making.

### Responsibilities
- Consolidate stakeholder feedback and priorities
- Communicate stakeholder requirements and concerns to the project team
- Participate in review and approval ceremonies as required
- Help shape communication plans and stakeholder engagement

### Interactions
- Liaises with Product Managers and Project Managers to prioritize stakeholder inputs
- Participates in demos, reviews, and acceptance discussions
- Works with Communications/Change Manager when broad messaging is required

### Goals
- Improve alignment between stakeholders and delivery teams
- Reduce rework from misaligned expectations

### Typical Communication
- Stakeholder briefs, working sessions, and feedback summaries

---

## Vendor / Third-Party Manager

### Role Summary
The Vendor/Third-Party Manager manages relationships with external vendors and ensures contractual deliverables align with project timelines.

### Responsibilities
- Track vendor deliverables, SLAs, and contractual milestones
- Manage vendor onboarding, coordination, and offboarding
- Ensure vendor work is integrated with project schedules and quality expectations
- Escalate contract or SLA issues to Procurement or Sponsor as needed

### Interactions
- Works with Project Managers to schedule and coordinate vendor tasks
- Engages Procurement and Legal for contract matters
- Coordinates with Technical Leads and QA to validate vendor deliverables

### Goals
- Maintain predictable vendor delivery and quality
- Reduce contractual and integration risks

### Typical Communication
- Vendor status reports, SLA dashboards, and coordination meetings

---

## Business Analyst (BA)

### Role Summary
The Business Analyst clarifies requirements, acceptance criteria, and ensures solution alignment with business outcomes.

### Responsibilities
- Elicit and document requirements, user stories, and acceptance criteria
- Run requirements workshops and stakeholder alignment sessions
- Support UAT and validation of features against business needs
- Maintain traceability from requirements to implementation and test cases

### Interactions
- Works closely with Product Managers to translate product goals into actionable stories
- Collaborates with UX Lead on user flows and design handoffs
- Hands off detailed specs to Technical Leads and Developers for implementation

### Goals
- Reduce ambiguity in requirements and acceptance criteria
- Improve the quality of delivered outcomes by ensuring alignment with business intent

### Typical Communication
- Requirements documents, story walkthroughs, and UAT scripts

---

## UX Lead

### Role Summary
The UX Lead owns design direction, user experience consistency, and accessibility across features and releases.

### Responsibilities
- Lead design reviews and maintain UX guidelines or design system conformance
- Validate accessibility and usability requirements
- Provide design artifacts (wireframes, prototypes) and acceptance criteria
- Support design handoff and review during development and releases

### Interactions
- Partners with Product Managers and Business Analysts to shape user experience decisions
- Works with Developers and Technical Leads to ensure feasible implementations
- Participates in release readiness and validates UX in release checks

### Goals
- Deliver consistent, usable, and accessible user experiences
- Reduce rework from design/implementation mismatches

### Typical Communication
- Design review sessions, prototypes, and accessibility reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
