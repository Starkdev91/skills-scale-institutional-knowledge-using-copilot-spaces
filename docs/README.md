# OctoAcme Project Management Docs

## Project Management Processes Overview

OctoAcme manages projects through five defined lifecycle phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase has clear entry and exit criteria, owned artifacts, and cross-functional responsibilities to keep delivery predictable and transparent. Our approach is grounded in five core principles: customer-first prioritization, iterative delivery of small testable increments, clear ownership (a named PM and Product Lead on every project), data-informed decisions, and psychological safety to encourage open feedback and learning.

Day-to-day execution is structured around a project board with columns—Backlog, Ready, In Progress, In Review, QA, and Done—and a disciplined PR workflow: small, focused pull requests linked to issues with clear acceptance criteria, CI checks (including security scanning), and required approvals before merge. Risks are tracked in a living Risk Register and reviewed at weekly syncs; escalation follows a clear path from the team level to the PM, then to the Product Lead, and finally to the Sponsor (security incidents route directly to the Security on-call team). Communication runs on a predictable cadence: a weekly PM + Product Manager alignment, twice-weekly team standups, a weekly delivery sync, periodic demos/reviews, and monthly stakeholder updates, supported by a standard weekly status template.

Quality assurance is built into every phase: unit and integration tests are required for all changes, end-to-end smoke tests cover critical user flows, security scanning runs in CI on every PR, and manual QA is performed when needed. Releases follow a structured checklist and are backed by a rollback and incident playbook. After each sprint, release, or significant milestone—and after any incident—the team runs a timeboxed retrospective to capture what went well, what could be improved, and two to three prioritized action items with named owners and due dates. Action items are tracked in the project backlog and reviewed in the weekly PM sync to close the improvement loop.

Key roles across all phases are: **Project Manager (PM)** — coordinates delivery, schedules, risk, and communications; **Product Manager (Product Lead / PdM)** — defines outcomes, prioritizes the backlog, and measures success; **Developers** — implement features, write tests, and participate in design and code reviews; **QA/Testing** — validate quality and acceptance criteria; and **Stakeholders/Sponsors** — provide strategic inputs and approvals.

---

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, core roles, key artifacts, lifecycle phases, and communication cadence at a glance.
- [Project Initiation Guide](octoacme-project-initiation.md) — Kickoff checklist, project charter template, stakeholder mapping, and how to set up a new project.
- [Project Planning](octoacme-project-planning.md) — Scope definition, milestone planning, dependency mapping, resource allocation, and sprint setup.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Project board workflow, PR process, daily standups, status reporting, and how to manage in-flight changes.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk Register format, risk lifecycle, stakeholder communication templates, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release checklist, deployment steps, smoke testing, rollback procedure, and incident playbook.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — When and how to run retrospectives, action item template, and how to track improvements over time.
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed responsibilities, goals, and communication patterns for each role (Developer, Product Manager, Project Manager).

> Use this README as your starting point for navigating OctoAcme's project management processes and for onboarding new team members.
