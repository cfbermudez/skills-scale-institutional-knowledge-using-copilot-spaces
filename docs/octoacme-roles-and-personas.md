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

## Engineering Managers / Tech Leads

### Role Summary
Engineering Managers and Tech Leads provide technical leadership and enable the engineering team to deliver high-quality solutions. They are accountable for technical direction, implementation quality, and ensuring that engineering practices support project outcomes.

### Responsibilities
- Define and communicate technical approach and architecture for the project.
- Ensure code quality, reliability, and performance standards are met.
- Support Developers with design reviews, pairing, and mentoring.
- Collaborate with Product Managers and Project Managers on scope, trade-offs, and sequencing.
- Identify and manage technical risks, dependencies, and spikes.
- Advocate for non-functional requirements (security, scalability, observability, resilience).

### Goals
- Deliver technically sound solutions that meet business and customer needs.
- Reduce technical debt and avoid high-risk shortcuts that jeopardize long-term health.
- Maintain healthy engineering practices (testing, CI/CD, code review, documentation).

### Typical Communication
- Architecture and design discussions with Developers and Product Managers.
- Risk and dependency updates in planning and execution meetings.
- Status updates on technical work items and spikes.
- Input into release readiness and rollback strategy.

### Interaction with Existing Roles
- Works with Product Managers to shape feasible scope, trade-offs, and timelines.
- Partners with Project Managers to surface and track technical risks and dependencies.
- Supports Developers with guidance, code review, and unblocking.
- Coordinates with Operations/DevOps/SRE on deployment, observability, and reliability concerns.

---

## QA Engineers / Quality Leads

### Role Summary
QA Engineers and Quality Leads champion quality throughout the project lifecycle. They help define test strategies, validate that acceptance criteria are met, and ensure releases are safe and reliable.

### Responsibilities
- Collaborate on acceptance criteria and testability of backlog items.
- Define and maintain test strategy (manual, automated, regression, smoke tests).
- Execute tests and report defects with clear reproduction steps and impact.
- Contribute to or oversee automation suites integrated into CI.
- Partner with Developers and Engineering Managers to prevent defects earlier in the lifecycle.

### Goals
- Minimize escaped defects and production incidents.
- Provide reliable, timely feedback on release readiness.
- Make quality expectations visible and measurable.

### Typical Communication
- Test plans and execution status shared with the delivery team.
- Defect reports linked to issues/PRs.
- Risk-based recommendations on release readiness.

### Interaction with Existing Roles
- Collaborates with Product Managers to validate that features meet user and business expectations.
- Works with Project Managers to ensure testing activities are planned and visible on the project board.
- Partners with Developers to design testable solutions and improve automation coverage.
- Coordinates with Operations/DevOps/SRE on post-release monitoring and incident follow-ups.

---

## UX/UI Designers

### Role Summary
UX/UI Designers ensure that solutions are usable, accessible, and aligned with user needs. They translate problem statements and requirements into user flows, wireframes, and visual designs.

### Responsibilities
- Conduct or leverage user research to inform design decisions.
- Create user flows, wireframes, and high-fidelity designs.
- Collaborate with Product Managers to refine requirements and acceptance criteria.
- Work with Developers to clarify implementation details and edge cases.
- Advocate for accessibility and design consistency.

### Goals
- Deliver intuitive, accessible user experiences that support business outcomes.
- Reduce rework caused by unclear or late-breaking design decisions.
- Ensure design intent is preserved in implementation.

### Typical Communication
- Design reviews and walkthroughs with Product Managers, Developers, and stakeholders.
- Asynchronous feedback via design tools and comments.
- Documentation of design decisions and rationale.

### Interaction with Existing Roles
- Partners with Product Managers during initiation and planning to shape the solution.
- Works with Project Managers to align design milestones with development timelines.
- Collaborates with Developers to clarify designs and handle implementation trade-offs.
- Engages with Stakeholders/Sponsors to validate that designs meet expectations where appropriate.

---

## Support / Customer Success

### Role Summary
Support and Customer Success roles represent the voice of the customer post-release. They provide input on customer pain points, ensure smooth adoption, and feed real-world feedback back into the roadmap.

### Responsibilities
- Communicate common issues, feature requests, and pain points to Product Managers.
- Prepare and deliver customer-facing communication for launches and changes.
- Help define and track adoption and satisfaction metrics.
- Participate in incident communication and follow-up where customers are impacted.
- Maintain and update help content, FAQs, and internal support documentation.

### Goals
- Improve customer satisfaction and reduce friction in day-to-day use.
- Ensure changes are well-communicated and supported.
- Help prioritize improvements based on real customer impact.

### Typical Communication
- Regular feedback loops with Product Managers and Project Managers.
- Updates to knowledge bases, FAQs, and customer-facing documentation.
- Participation in post-incident reviews where customer impact is high.

### Interaction with Existing Roles
- Works with Product Managers to influence roadmap priorities based on customer data.
- Collaborates with Project Managers on communication plans and rollouts.
- Provides Developers and QA with real-world scenarios and repro steps.
- Keeps Stakeholders informed about customer sentiment and key account risks.

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide direction, funding, and organizational support. They are accountable for ensuring that projects align with strategic priorities and deliver expected outcomes.

### Responsibilities
- Define or validate the business problem, value, and success metrics.
- Approve major scope, timeline, and budget decisions.
- Remove organizational blockers and provide necessary resources.
- Participate in key decision gates (initiation approval, go/no-go, major release decisions).
- Champion the project across the organization.

### Goals
- Ensure projects deliver meaningful business outcomes.
- Maintain alignment between project work and strategic priorities.
- Provide clear, timely decisions and feedback.

### Typical Communication
- Regular status updates from Project and Product Managers.
- Decision-focused briefings at milestones and gates.
- Post-release reviews on impact and next steps.

### Interaction with Existing Roles
- Works with Product Managers to set and refine goals and success metrics.
- Partners with Project Managers to review risks, high-level plans, and escalations.
- Engages with Developers, QA, and Designers as needed for demos and feedback.
- Coordinates with Support/Customer Success to understand customer impact and adoption.

---

## Operations / DevOps / SRE

### Role Summary
Operations, DevOps, and Site Reliability Engineers (SREs) ensure that systems are reliable, observable, and maintainable in production. They collaborate with the delivery team to design for operability and streamline deployment.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment processes.
- Define and monitor SLOs, SLIs, and error budgets where applicable.
- Implement and maintain observability (logging, metrics, tracing, alerts).
- Participate in incident response and post-incident reviews.
- Provide input on capacity planning, performance, and scalability.

### Goals
- Minimize downtime and production incidents.
- Shorten time to detect and resolve issues.
- Make deployments safe, predictable, and repeatable.

### Typical Communication
- Coordination with Developers and Engineering Managers around releases.
- Alerting and incident communications during outages or degradations.
- Ongoing feedback into reliability and performance improvements.

### Interaction with Existing Roles
- Partners with Project Managers to plan deployment windows, rollback strategies, and incident playbooks.
- Works with Developers and Engineering Managers to design operable, observable systems.
- Collaborates with Product Managers on impact assessment and prioritization of reliability work.
- Aligns with Support/Customer Success on incident communications and known issues.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

