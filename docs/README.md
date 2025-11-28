# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation: concise guidance, templates, and checklists to run predictable, customer-focused, and low-friction projects. These docs are intended as a single entry point for new team members and a quick reference for active delivery teams.

OctoAcme follows a lightweight lifecycle: Initiation (a one-pager to validate the problem and stakeholders), Planning (break work into shippable backlog items and a release plan), Execution (small increments tracked on a project board with PR and CI gating), Release (pre-release checks, staging smoke tests, and rollback plans), and Close/Retrospective (capture learnings and turn them into backlog action items). The approach emphasizes iterative delivery, clear ownership (named PM + Product Lead), and data-informed decisions to validate outcomes.

Key workflows include a project board with defined columns (Backlog → Ready → In Progress → In Review → QA → Done), a PR workflow that encourages small, reviewable changes with CI gates and at least one approval, and an accessible risk register reviewed regularly. Personas and responsibilities are explicit: Product Managers define outcomes and prioritization, Project Managers coordinate delivery and communication, Developers implement and test, and QA validates acceptance criteria. Communication is structured through daily standups, weekly PM+PdM alignment, delivery syncs, and monthly stakeholder updates.

Quality assurance is enforced via automated unit/integration tests, CI security scans, end-to-end smoke tests for critical flows, and a manual QA step where required. Releases follow a checklist (passing CI/security scans, release notes, rollback plan, staging smoke tests, and post-deploy verification). Retrospectives turn learnings into prioritized action items tracked in the project backlog to ensure continuous improvement.

Process Document Links
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles and Personas — docs/octoacme-roles-and-personas.md

How to use
- Keep the README and detailed docs in docs/ updated for discoverability and onboarding.
- Use the one-pager, backlog templates, and checklists for consistent delivery.
- Add project-specific exceptions in the project README or .copilot/ to make them available to Copilot Spaces.
