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

As OctoAcme projects scale, several additional roles commonly appear to clarify ownership, improve handoffs, and reduce single-person dependencies. Add these personas to project one-pagers, role assignment tables, and lifecycle artifacts where relevant (e.g., Risk Register, Release Notes, Project One-pager, Runbooks).

### Technical Lead / Architect
- Responsibilities:
  - Drive technical design decisions and own architecture diagrams.
  - Ensure non-functional requirements (scalability, performance, maintainability) are addressed.
  - Review complex PRs and mentor developers on design.
- Interactions:
  - Advises Product Manager on technical constraints during planning.
  - Coordinates with SRE/DevOps for deployment and capacity considerations.
  - Works with Developers to ensure implementation aligns with architecture.
- Where referenced:
  - Project One-pager (technical approach), Design docs, Risk Register (technical risks).

### Engineering Manager (EM)
- Responsibilities:
  - Team capacity planning and resource allocation.
  - Career development and people-related escalations.
  - Remove organizational impediments to delivery.
- Interactions:
  - Collaborates with PM on capacity during planning.
  - Works with Technical Lead and Developers on team health and staffing.
  - Escalates resourcing issues to Product Lead or Sponsor.
- Where referenced:
  - Project initiation (proposed team/roles), Planning artifacts.

### UX / Product Designer
- Responsibilities:
  - Conduct user research, create wireframes and high-fidelity designs.
  - Define accessibility standards and UX acceptance criteria.
  - Support usability testing and iterate on designs based on feedback.
- Interactions:
  - Works with PdM on user needs and acceptance criteria.
  - Hands off designs to Developers with clear specs and assets.
  - Participates in demos and acceptance validation with QA.
- Where referenced:
  - One-pager (user value), Acceptance criteria, Design annex.

### Data Analyst / Measurement Lead
- Responsibilities:
  - Define success metrics and instrumentation requirements.
  - Build dashboards and run experiment analyses.
  - Validate data quality and tagging for analytics.
- Interactions:
  - Aligns with PdM to define measurable success metrics in the One-pager.
  - Works with Developers and QA to ensure proper instrumentation before release.
  - Feeds insights into retrospectives and decision-making.
- Where referenced:
  - Project One-pager (success metrics), Release notes (metric checks), Dashboards.

### SRE / DevOps / Release Engineer
- Responsibilities:
  - Build and maintain CI/CD pipelines, deployment automation, and observability.
  - Define runbooks, deployment windows, capacity plans, and rollback procedures.
  - Support incident response and post-incident reviews.
- Interactions:
  - Collaborates with Developers on deployability and automation.
  - Coordinates with Release Manager and PM for deployment schedules and verifications.
  - Works with Technical Lead for performance tuning and capacity planning.
- Where referenced:
  - Release checklist, Runbooks, Incident playbook.

### Security Engineer / Privacy Lead
- Responsibilities:
  - Perform threat modeling, security reviews, and compliance checks.
  - Ensure security scans are integrated into CI and remediation tracked.
  - Provide guidance on data handling and privacy requirements.
- Interactions:
  - Consulted during design and PR reviews with Developers and Technical Lead.
  - Works with PdM and Legal on compliance and privacy decisions.
  - Escalates critical security issues via PM to Sponsor and Security leadership.
- Where referenced:
  - Risk Register, Pre-release checklists, Security runbook.

### Release Manager
- Responsibilities:
  - Coordinate release windows, verify release readiness, and manage release communications.
  - Own release notes, stakeholder announcements, and post-release verifications.
- Interactions:
  - Works closely with PM, SRE, QA, and Support for the release plan and verification.
  - Triggers and coordinates rollbacks or mitigations if required.
- Where referenced:
  - Release notes template, Release checklist, Stakeholder communications.

### Business Analyst / Domain SME
- Responsibilities:
  - Convert stakeholder needs into testable acceptance criteria and domain-specific documentation.
  - Validate domain logic and edge cases.
- Interactions:
  - Partners with PdM to refine requirements.
  - Assists QA with test scenarios and reproduction steps.
- Where referenced:
  - Acceptance criteria, Backlog item descriptions.

### Support / Operations Lead
- Responsibilities:
  - First-line triage for production incidents and SLA communications.
  - Maintain and update customer-facing runbooks and known-issue lists.
- Interactions:
  - Works with SRE and Developers during incidents.
  - Feeds common issues back into backlog for prioritization.
- Where referenced:
  - Incident communications, Runbooks, Support playbooks.

### Legal / Compliance Representative (if applicable)
- Responsibilities:
  - Review regulatory and contractual implications of features.
  - Advise on data handling, retention, and disclosure requirements.
- Interactions:
  - Consulted during planning and prior to release for features with legal or compliance impact.
  - Works with Security, PdM, and Sponsor as needed.
- Where referenced:
  - One-pager risk & compliance section, Release Checklist.

---

## How to reference personas in project artifacts
- Project One-pager: List the primary role owners (PM, PdM, Technical Lead, Release Manager, Data Lead).
- Risk Register: Add an Owner field for each risk and include Security/SRE owners where relevant.
- Release Notes & Checklist: Identify the Release Manager and SRE contacts.
- Runbooks & On-call: Identify SRE and Support leads and escalation paths.
- Dashboards & Metrics: Link Data Analyst to dashboard ownership and metric owners.
