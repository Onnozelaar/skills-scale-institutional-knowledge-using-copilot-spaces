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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

The following personas are proposed to improve clarity, accountability, and cross-functional coordination on projects. Add these to the roles documentation when relevant to a project or program.

### Technical Program Manager (TPM)

Role Summary
Technical Program Managers coordinate cross-team dependencies, drive program-level schedules, and maintain risk registers for multi-team efforts.

Responsibilities
- Coordinate cross-team planning and dependency tracking
- Drive program-level schedules and milestone alignment
- Maintain program risk registers and mitigation plans
- Facilitate integration planning and release coordination for multi-team work

Interaction with existing roles
- Works closely with Project Managers (PM) and Product Managers (PdM) for prioritization and scheduling
- Partners with Engineering Managers and Developers to translate program goals into team plans
- Escalates unresolved cross-team blockers to PM or organizational leadership when needed

### QA Lead / Test Engineer

Role Summary
QA Leads define and own test strategies, coordinate test execution, and ensure release readiness through both automated and manual testing.

Responsibilities
- Define test strategy and acceptance gating
- Own test plans, automation coverage, and manual test execution
- Coordinate release testing with Developers and Release Engineers
- Report quality status and readiness to PM and stakeholders

Interaction with existing roles
- Partners with Developers to ensure testability and adequate coverage
- Reports test readiness and quality risks to PM and Release/Platform Engineers
- Works with PdM to confirm acceptance criteria are testable and met

### UX Researcher / Designer

Role Summary
UX Researchers and Designers lead user research, define UX acceptance criteria, and produce design assets and accessibility checks.

Responsibilities
- Conduct user research and synthesis to inform product decisions
- Produce wireframes, mockups, and design specifications
- Define UX acceptance criteria and accessibility checks
- Participate in demos and acceptance reviews

Interaction with existing roles
- Collaborates with PdM to define user needs and priorities
- Handoffs designs to Developers and supports implementation
- Participates in demos and acceptance reviews with PM and stakeholders

### Release / Platform Engineer (DevOps)

Role Summary
Release or Platform Engineers maintain CI/CD pipelines, manage deployments and rollback procedures, and own observability and release automation.

Responsibilities
- Maintain and improve CI/CD pipelines and release automation
- Manage deployments, release windows, and rollback plans
- Ensure observability, monitoring, and alerting for releases
- Support staging validation and production verification

Interaction with existing roles
- Works with Developers to ensure build and deployment readiness
- Coordinates with QA during staging validation
- Communicates deployment schedules and risks to PM

### Security Liaison

Role Summary
A Security Liaison surfaces security requirements, performs lightweight threat checks, and coordinates security scans and remediations with teams.

Responsibilities
- Identify and communicate security requirements and risks
- Run security scans and coordinate remediations
- Triage security findings and escalate critical issues to Security on-call
- Help teams adopt secure-by-design practices

Interaction with existing roles
- Notifies PM and PdM of potential security risks affecting scope or schedule
- Works with Developers to remediate findings and validate fixes
- Engages Security teams for critical investigations and approvals

### Data Analyst / Measurement Owner

Role Summary
Data Analysts define success metrics, instrument events and dashboards, and validate that releases meet acceptance metrics.

Responsibilities
- Define success metrics and instrumentation requirements
- Implement dashboards and alerts for key signals
- Validate experiments and release impact against success criteria
- Provide analysis to PdM and PM for decision-making

Interaction with existing roles
- Works with PdM to set measurable success criteria
- Provides monitoring and reports to PM and stakeholders
- Alerts teams when metrics deviate from expectations

---

## Suggested next steps
- Add the proposed roles and descriptions under "Additional Personas" in docs/octoacme-roles-and-personas.md (this change).
- Review with PdM, PM, Engineering, QA, Security, and Design leads before merging to confirm responsibilities and interactions.
- Optionally add role-specific checklists (e.g., Release Checklist, Security Checklist) to the docs/ folder and link them from this file.
