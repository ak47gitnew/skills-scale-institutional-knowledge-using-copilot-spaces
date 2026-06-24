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

To reduce ambiguity, improve handoffs, and accelerate decision-making in cross-functional work, the following personas are recommended additions. Each entry lists responsibilities, typical deliverables, interactions with existing roles, and escalation guidance.

### Delivery Lead
- Responsibilities:
  - Coordinate day-to-day delivery across squads or workstreams.
  - Manage sprint scope, cadence, and cross-team work intake.
  - Ensure cross-team dependencies are visible and tracked.
- Key deliverables:
  - Sprint plans, dependency board views, impediment logs.
- Interactions:
  - Works with Project Manager on schedule/risk, with Developers and QA to unblock work, and with Product Manager to ensure priorities are respected.
- Escalation:
  - Escalate unresolved cross-team blockers to the Project Manager.

### Engineering Manager
- Responsibilities:
  - People management, capacity planning, and technical roadmap alignment.
  - Ensure engineering quality, maintainability, and technical debt management.
- Key deliverables:
  - Capacity plans, hiring/skill-gap assessments, technical growth plans.
- Interactions:
  - Partners with Developers on career growth and implementation approaches, advises Product on realistic delivery timelines based on capacity.
- Escalation:
  - Escalate significant resource constraints or technical risks to Project Manager and Product Lead.

### UX Researcher / Designer
- Responsibilities:
  - Run user research, create designs and prototypes, validate usability and accessibility.
  - Provide design acceptance criteria and component specs.
- Key deliverables:
  - Research reports, wireframes, prototypes, accessibility notes.
- Interactions:
  - Works with Product Manager to translate user needs into requirements; collaborates with Developers to ensure designs are implementable.
- Escalation:
  - Escalate unresolved design trade-offs or accessibility blockers to Product Manager.

### Security Engineer / Security SME
- Responsibilities:
  - Review designs and implementations for security implications.
  - Define security requirements and validate mitigations.
  - Triage and remediate security scan findings.
- Key deliverables:
  - Threat assessments, security requirements, remediation plans.
- Interactions:
  - Consults during planning and design reviews; works with Developers and SREs on fixes.
- Escalation:
  - Escalate critical security findings immediately to Project Manager and Security on-call.

### Data Analyst / Data Engineer
- Responsibilities:
  - Define measurement strategy and success metrics.
  - Implement instrumentation and maintain data pipelines and dashboards.
  - Analyze usage and experiment results.
- Key deliverables:
  - Measurement plans, dashboards, analysis reports.
- Interactions:
  - Works with Product Manager to define success metrics and with Developers to implement tracking.
- Escalation:
  - Escalate data quality or instrumentation gaps to the Product Manager and Delivery Lead.

### Site Reliability / Platform Engineer (SRE)
- Responsibilities:
  - Ensure reliability, observability, and operational readiness.
  - Maintain deployment pipelines, runbooks, and on-call rotations.
- Key deliverables:
  - SLIs/SLOs, runbooks, deployment scripts, observability dashboards.
- Interactions:
  - Coordinates with Developers and Release Manager on deployment plans and with Project Manager on incident impact.
- Escalation:
  - Escalate production-impacting incidents to the incident response lead and Project Manager.

### Release Manager
- Responsibilities:
  - Coordinate release windows, validate release readiness, and manage release communications.
  - Maintain rollback plans and versioning policies.
- Key deliverables:
  - Release readiness checklist, release notes, rollback procedures.
- Interactions:
  - Works with SRE, Security, QA, and PM to confirm release readiness; notifies Stakeholders.
- Escalation:
  - Escalate release blockers to Project Manager and Product Lead.

### Support / Customer Success Lead
- Responsibilities:
  - Capture customer feedback, prioritize post-release issues, and maintain support runbooks.
  - Track customer-impacting bugs and feature requests.
- Key deliverables:
  - Support runbooks, incident postmortems (customer impact focus), prioritized issue lists.
- Interactions:
  - Feeds customer issues into the backlog and works with Product Manager and Developers on fixes and documentation.
- Escalation:
  - Escalate high-severity customer-impact incidents to Project Manager and Product Lead.

---

### Notes on usage
- For each new persona entry, include:
  - A short example of a typical responsibility
  - Key deliverables
  - Where to escalate issues
- Add cross-links in the document to other process docs where relevant (planning, release, risks).
- Consider a “persona quick reference” one-pager (table) for onboarding and README linking.
