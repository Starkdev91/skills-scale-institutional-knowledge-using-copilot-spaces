# OctoAcme Roles & Interaction Guide

This document provides a lightweight RACI-style matrix mapping key project lifecycle activities to roles. It complements the detailed role descriptions in [OctoAcme Personas](octoacme-roles-and-personas.md).

**Key:** R = Responsible · A = Accountable · C = Consulted · I = Informed

---

## RACI Matrix

| Activity | PM | PdM | Dev | QA | BA | SM | UX | Rel Mgr | Cust Success | Sys Arch | Data Analyst | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | | | | | |
| Define problem statement & goals | A | R | I | I | C | I | C | I | C | C | C | C |
| Identify stakeholders & sponsors | R | C | I | I | C | I | I | I | C | I | I | A |
| Create project one-pager | R | C | I | I | C | I | I | I | I | C | I | A |
| Initial risk identification | R | C | C | C | C | I | I | C | I | C | I | I |
| **Planning** | | | | | | | | | | | | |
| Backlog creation & refinement | C | A | C | C | R | C | C | I | C | C | I | I |
| Sprint / milestone planning | A | C | R | C | C | R | C | C | I | C | I | I |
| Architecture & technical design | C | C | R | C | C | I | I | I | I | A | I | I |
| UX research & prototyping | I | C | C | I | C | I | A | I | I | I | I | I |
| Release calendar planning | C | C | C | I | I | I | I | A | C | I | I | I |
| Risk register updates | A | C | C | C | C | C | I | C | I | C | C | I |
| **Execution** | | | | | | | | | | | | |
| Feature development | I | C | A | C | C | I | C | I | I | C | I | I |
| Daily standups & impediment removal | C | I | R | R | I | A | I | I | I | I | I | I |
| Requirements clarification | C | C | C | I | A | I | C | I | I | C | I | I |
| Design review & implementation feedback | I | C | R | I | I | I | A | I | I | C | I | I |
| Test planning & execution | I | C | C | A | C | I | C | I | I | C | I | I |
| Metrics instrumentation | I | C | R | C | I | I | I | I | I | C | A | I |
| **Release** | | | | | | | | | | | | |
| Pre-release readiness review | C | C | C | C | I | I | I | A | C | C | I | I |
| Code freeze & deployment | I | I | R | C | I | I | I | A | I | C | I | I |
| Smoke tests & post-deploy validation | C | I | C | A | I | I | I | C | I | I | I | I |
| Release notes & announcements | C | C | I | I | I | I | I | A | C | I | I | I |
| Customer rollout coordination | I | C | I | I | I | I | I | C | A | I | I | I |
| **Retrospective & Close** | | | | | | | | | | | | |
| Retro facilitation | C | I | C | C | C | A | I | C | I | I | I | I |
| Metric outcome review | C | C | I | I | I | I | I | I | C | I | A | I |
| Action item tracking | A | C | C | C | C | R | I | C | I | I | I | I |
| Lessons learned documentation | R | C | C | C | C | C | I | C | C | C | C | I |

---

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developers |
| QA | QA / Testing |
| BA | Business Analyst |
| SM | Scrum Master |
| UX | UX Designer |
| Rel Mgr | Release Manager |
| Cust Success | Customer Success |
| Sys Arch | Systems Architect |
| Data Analyst | Data Analyst |

---

## Key Interaction Notes

- The **Business Analyst** and **Product Manager** jointly own requirements; the BA drives elicitation and documentation while the PdM owns prioritization and vision.
- The **Scrum Master** and **Project Manager** share coordination responsibilities: the SM focuses on team-level health and ceremony facilitation, while the PM manages cross-team delivery, milestones, and stakeholder communication.
- The **Release Manager** is the single point of coordination for release readiness, working across QA, Dev, and Customer Success to align all parties before deployment.
- The **Systems Architect** is consulted on any changes with significant technical impact (performance, security, scalability) and is accountable for the overall architecture design.
- The **Data Analyst** partners with PdM at all stages to ensure success metrics are defined early (Initiation/Planning) and measured meaningfully (Retrospective).
- The **UX Designer** should be engaged early in Planning and continuously during Execution to prevent costly design rework.

---

## References
- Full role descriptions: [OctoAcme Personas](octoacme-roles-and-personas.md)
- Lifecycle process guides: [Project Initiation](octoacme-project-initiation.md) · [Project Planning](octoacme-project-planning.md) · [Execution & Tracking](octoacme-execution-and-tracking.md) · [Release & Deployment](octoacme-release-and-deployment.md) · [Retrospective](octoacme-retrospective-and-continuous-improvement.md)
