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

(Added to improve clarity of ownership, handoffs, and accountability across cross-functional activities.)

- Delivery Lead
  - Responsibilities: Coordinate sprint-level delivery, manage scope trade-offs, track dependencies across teams, ensure blockers are addressed, run sprint ceremonies as needed.
  - Typical deliverables: Sprint plan, dependency tracker, weekly delivery updates.
  - Interactions: Works closely with PM (scheduling, risks), PdM (prioritization trade-offs), Tech Lead (technical feasibility), and QA (release readiness).

- Technical Lead (Tech Lead)
  - Responsibilities: Provide technical direction and architecture guidance, review major technical decisions, ensure code quality and design consistency, mentor engineers.
  - Typical deliverables: Design reviews, architecture proposals, technical risk logs.
  - Interactions: Liaises with Developers (implementation guidance), Project Manager (estimates, technical risks), SRE/Platform (operational constraints).

- Engineering Manager (EM)
  - Responsibilities: People management, capacity planning, career development, hiring input, performance coaching.
  - Typical deliverables: Capacity forecasts, staffing plans, development plans.
  - Interactions: Coordinates with PM/Delivery Lead on team capacity; supports Tech Lead on technical staffing and team health.

- UX Researcher / Designer
  - Responsibilities: Run user research, synthesize findings, create designs and interaction specs, validate UX acceptance criteria.
  - Typical deliverables: Research briefs, wireframes/prototypes, usability reports.
  - Interactions: Works with PdM to shape requirements, Developers for implementation details, QA for usability validation.

- Site Reliability / Platform Engineer (SRE)
  - Responsibilities: Operational reliability, monitoring and alerting, incident response readiness, runbooks, capacity planning.
  - Typical deliverables: Runbooks, SLO/SLA guidance, operational playbooks.
  - Interactions: Engages during planning for operational requirements, works with Developers and Release Manager for deployments and incident mitigation.

- Data Analyst / Data Engineer
  - Responsibilities: Define metrics and instrumentation, build dashboards and reports, analyze post-release outcomes, support experimentation.
  - Typical deliverables: Metrics definitions, dashboards, analysis reports.
  - Interactions: Partners with PdM on success metrics, Developers on instrumentation, PM on reporting cadence.

- Security Engineer
  - Responsibilities: Threat modeling, security reviews, vulnerability triage, compliance guidance and checks.
  - Typical deliverables: Security review notes, vulnerability reports, remediation guidance.
  - Interactions: Works with Tech Lead and Developers during design/review; coordinates with Product/PM for risk acceptance and release gating.

- Release Manager / Build & Release Coordinator
  - Responsibilities: Coordinate release windows, run release checklists, own rollbacks and post-release verification, coordinate cross-team release readiness.
  - Typical deliverables: Release plan, rollback instructions, release notes.
  - Interactions: Coordinates with Delivery Lead, SRE, QA, and PM for release readiness and communications.

- Business Analyst / Domain SME
  - Responsibilities: Translate business requirements into clear acceptance criteria, clarify domain rules, validate edge cases and compliance-related items.
  - Typical deliverables: Detailed requirements, example scenarios, validation notes.
  - Interactions: Works with PdM and Developers during refinement and acceptance testing.

- Change Manager / Communications Lead
  - Responsibilities: Stakeholder communications, readiness plans, user communications, training materials and announcements.
  - Typical deliverables: Communication plans, announcements, training/checklist items.
  - Interactions: Coordinates announcements with PM, Support, Sales/Marketing, and Stakeholders as needed.

Notes:
- Each persona entry includes a short responsibilities list, examples of typical deliverables, and a one-line description of how they interact with existing core roles.
- Suggested next step: add a one-page matrix mapping responsibilities to existing core roles (PM, PdM, Developers, QA, etc.) as a separate doc in docs/ if desired.
