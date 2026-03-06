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

## QA / Testing

### Role Summary
QA and Testing engineers validate that product increments meet acceptance criteria and quality standards before release. They collaborate closely with Developers, Product Managers, and Release Managers to surface issues early.

### Responsibilities
- Define and execute test plans and test cases
- Perform functional, regression, and exploratory testing
- Report defects and track them to resolution
- Validate acceptance criteria and definition of done
- Assist in production smoke tests and post-deploy verification

### Goals
- Ensure releases meet quality standards and customer expectations
- Reduce defect escape rate to production
- Maintain a reliable, repeatable testing baseline

### Typical Communication
- Sprint reviews and bug triage meetings
- Defect reports and test summary docs
- Pre-release readiness sign-offs with Release Manager and PM

---

## Stakeholders

### Role Summary
Stakeholders are business leaders, sponsors, or domain experts who have a vested interest in project outcomes. They provide direction, validate priorities, and approve key decisions.

### Responsibilities
- Provide business context, priorities, and constraints
- Review and approve deliverables and release readiness
- Escalate issues and champion the project internally
- Participate in demos and progress reviews

### Goals
- Ensure the project delivers measurable business value
- Minimize disruption to ongoing operations
- Maintain confidence and visibility into project progress

### Typical Communication
- Monthly status updates and executive summaries
- Decision gate reviews and go/no-go sign-offs
- Ad-hoc escalations and advisory sessions

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather and refine requirements, map business processes, and ensure proposed solutions align with organizational goals.

### Responsibilities
- Elicit, document, and refine business and functional requirements
- Map current and future-state business processes
- Translate business needs into actionable user stories and acceptance criteria
- Facilitate requirements workshops with stakeholders
- Validate that delivered solutions meet defined business objectives

### Goals
- Ensure requirements are complete, unambiguous, and traceable
- Reduce rework caused by misunderstood or missing requirements
- Align technical deliverables with business value

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story refinement sessions with PM and PdM
- Acceptance criteria documentation shared with Developers and QA

### Interactions with Other Roles
- **Project Manager:** Provides detailed requirements and scope inputs to support planning and risk assessment.
- **Product Manager:** Collaborates on backlog refinement and ensures stories align with the product vision.
- **Developers:** Clarifies ambiguous requirements and participates in technical feasibility discussions.
- **QA / Testing:** Supplies acceptance criteria and participates in test case reviews to ensure coverage.
- **Stakeholders:** Facilitates elicitation sessions and confirms that documented requirements reflect stakeholder intent.

---

## Scrum Master

### Role Summary
The Scrum Master coaches the team in agile practices, removes impediments, and facilitates key ceremonies. They act as a bridge between the technical team and process, fostering a healthy, high-performing environment.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Track sprint health, velocity, and burndown metrics
- Coach team members on agile principles and practices
- Shield the team from external distractions and scope creep

### Goals
- Maintain predictable sprint delivery and team rhythm
- Continuously improve team processes and collaboration
- Build a psychologically safe and self-organizing team

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective action item tracking
- Impediment logs and escalation to PM when needed

### Interactions with Other Roles
- **Project Manager:** Escalates unresolved blockers; aligns sprint cadence with project milestones and risk register.
- **Product Manager:** Supports backlog refinement and helps the team maintain focus on prioritized work.
- **Developers:** Protects the team's capacity, surfaces process improvements, and coaches on agile practices.
- **Business Analyst:** Facilitates risk management meetings and ensures clear communication of blockers and requirement changes.
- **Stakeholders:** Communicates team capacity and sprint commitments during reviews and demo sessions.

---

## UX Designer

### Role Summary
UX Designers create intuitive, accessible, and user-centered experiences. They conduct research, develop prototypes, and collaborate with product and engineering teams to deliver features that genuinely meet user needs.

### Responsibilities
- Conduct user research, usability testing, and journey mapping
- Design wireframes, mockups, and interactive prototypes
- Define interaction patterns and design system guidelines
- Partner with Developers to ensure design intent is implemented accurately
- Iterate designs based on feedback from users and stakeholders

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce friction and support paths for users in key workflows
- Ensure design decisions are grounded in user evidence

### Typical Communication
- Design reviews and critique sessions with PdM and Developers
- Usability study readouts and research summaries
- Annotated design specs and prototype walkthroughs

### Interactions with Other Roles
- **Project Manager:** Coordinates design milestones and communicates risks related to design dependencies.
- **Product Manager:** Aligns on user personas, success metrics, and feature scope before entering design cycles.
- **Developers:** Provides annotated specs and participates in implementation reviews to resolve design questions.
- **QA / Testing:** Supplies design acceptance criteria and reviews builds for visual and interaction regressions.
- **Stakeholders:** Presents prototypes and research findings to gather early feedback and validation.

---

## Release Manager

### Role Summary
The Release Manager plans, coordinates, and communicates product releases. They ensure readiness across engineering, testing, documentation, and support channels to maintain stable and predictable deployment cycles.

### Responsibilities
- Own and maintain the release calendar and deployment schedule
- Coordinate pre-release readiness reviews across QA, Dev, and PM
- Draft and publish release notes and customer communications
- Manage release branches and deployment pipelines in coordination with Developers
- Track rollback and mitigation plans for each release

### Goals
- Deliver releases on schedule with minimal production incidents
- Ensure all teams are aligned and prepared before each deployment
- Maintain clear audit trails of what was released and when

### Typical Communication
- Release readiness meetings with QA, Developers, and PM
- Deployment status updates to stakeholders and support teams
- Post-release retrospectives and incident reviews

### Interactions with Other Roles
- **Project Manager:** Aligns release dates with project milestones and communicates deployment risks.
- **Product Manager:** Confirms feature scope and obtains sign-off on release content.
- **Developers:** Coordinates code freeze, branch management, and deployment procedures.
- **QA / Testing:** Validates pre-release checklists, smoke test results, and regression sign-offs.
- **Customer Success:** Confirms rollout readiness for target users and prepares support teams for incoming queries.
- **Stakeholders:** Publishes release announcements and coordinates go-live communications.

---

## Customer Success

### Role Summary
Customer Success professionals serve as the voice of the customer within the organization. They gather feedback from end-users and stakeholders, document enhancement requests, and ensure product adoption and satisfaction.

### Responsibilities
- Build and maintain relationships with key customers and end-users
- Collect usage feedback and surface insights to PM and PdM
- Document and prioritize enhancement requests and pain points
- Support onboarding and training for new product capabilities
- Monitor adoption metrics and report on customer health

### Goals
- Drive high customer satisfaction and retention
- Ensure customers realize measurable value from the product
- Close the feedback loop between customers and the product team

### Typical Communication
- Regular check-ins and quarterly business reviews with customers
- Feedback summaries and enhancement request logs shared with PM/PdM
- Release communication coordination with Release Manager

### Interactions with Other Roles
- **Project Manager:** Provides customer-driven inputs to scope prioritization and risk assessment.
- **Product Manager:** Shares usage data, feedback themes, and enhancement requests to inform roadmap decisions.
- **Release Manager:** Collaborates to confirm rollout readiness and prepares customers for upcoming changes.
- **QA / Testing:** Reports customer-observed defects and validates that fixes resolve real user pain points.
- **Stakeholders:** Acts as a liaison between external customers and internal leadership on satisfaction and outcomes.

---

## Systems Architect

### Role Summary
The Systems Architect owns the high-level technical design of the product. They define architectural patterns, ensure scalability and security, and guide the development team on foundational decisions that affect the long-term health of the system.

### Responsibilities
- Define and document system architecture, integration patterns, and data flows
- Evaluate technical trade-offs and provide recommendations to engineering leadership
- Ensure architectural decisions address scalability, reliability, and security requirements
- Participate in design reviews and provide guidance on complex implementation challenges
- Maintain architecture decision records (ADRs) and technical roadmaps

### Goals
- Build systems that scale reliably and securely over time
- Reduce technical debt through intentional architectural decisions
- Align technical strategy with product and business goals

### Typical Communication
- Architecture reviews and technical design sessions
- ADR documentation and technical roadmap updates
- Escalations and advisory input during critical implementation decisions

### Interactions with Other Roles
- **Project Manager:** Communicates architectural risks, dependencies, and technical constraints that affect timelines.
- **Product Manager:** Aligns on technical feasibility of roadmap items and advises on build vs. buy decisions.
- **Developers:** Provides architectural guidance, reviews designs, and mentors on patterns and best practices.
- **QA / Testing:** Ensures non-functional requirements (performance, security, reliability) are testable and covered.
- **Stakeholders:** Presents architectural options and trade-offs at decision gates and planning reviews.

---

## Data Analyst

### Role Summary
Data Analysts track key product and project metrics, analyze outcomes, and supply actionable insights to support evidence-based decision-making by Product Managers, Project Managers, and leadership.

### Responsibilities
- Define and instrument key metrics aligned to product and business goals
- Build and maintain dashboards and reporting pipelines
- Analyze user behavior, feature adoption, and operational performance
- Surface insights and anomalies to PM/PdM for backlog and roadmap prioritization
- Conduct ad-hoc analyses to support strategic decisions and retrospectives

### Goals
- Ensure decisions are grounded in reliable, timely data
- Reduce time to insight for product and project teams
- Improve metric coverage and data quality across the product

### Typical Communication
- Weekly metric reviews and data briefings with PM and PdM
- Dashboard reports and annotated analysis summaries
- Retrospective data readouts highlighting trends and outcomes

### Interactions with Other Roles
- **Project Manager:** Supplies project health metrics and delivery trend data to support planning and reporting.
- **Product Manager:** Partners on defining success metrics and delivers data to inform prioritization and roadmap decisions.
- **Developers:** Collaborates on instrumentation and data pipeline implementation.
- **QA / Testing:** Validates data accuracy and assists with quality metrics tracking.
- **Stakeholders:** Presents outcome dashboards and business impact analyses at review milestones.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a cross-role accountability view, see [OctoAcme Roles & Interaction Guide (RACI)](octoacme-roles-and-personas-raci.md).

