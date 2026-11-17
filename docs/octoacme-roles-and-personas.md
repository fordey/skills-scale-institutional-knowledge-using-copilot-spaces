# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. blh 

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

## UX/UI Designers

### Role Summary
UX/UI Designers translate user needs and business goals into usable, consistent, and accessible product experiences. They work closely with Product Managers, Developers, and QA/Testing to ensure the intended experience is clearly designed and validated.

### Responsibilities
- Conduct user research and synthesize feedback into design opportunities
- Define user flows, interaction patterns, and product screens
- Partner with Product Managers on requirements, user stories, and usability goals
- Support Developers by clarifying behavior and edge cases during implementation
- Validate outcomes with QA/Testing and stakeholder review before release

### Goals
- Improve customer satisfaction and task completion
- Reduce confusion, friction, and rework in product experiences
- Ensure accessibility and consistency across touchpoints

### Typical Communication
- Product discovery and design reviews
- User research summaries and prototype feedback loops
- Design handoff artifacts, acceptance examples, and QA notes

### Interaction with Existing Roles
- With Product Managers: translate outcomes and customer needs into experience decisions and design priorities.
- With Developers: clarify implementation details, edge cases, and usability expectations during design handoff.
- With QA/Testing: align on acceptance criteria, usability validations, and regression checks.
- With Project Managers: share design milestones, dependencies, and review timing to keep delivery on schedule.

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide technical direction, design quality, and engineering decisions. They help teams balance speed, maintainability, and system reliability while keeping delivery aligned with project goals.

### Responsibilities
- Define technical architecture, patterns, and integration approaches
- Review system design trade-offs and technical risks early
- Help prioritize technical debt, performance needs, and scalability considerations
- Guide implementation quality through design reviews and coaching
- Partner with Project Managers to flag dependencies, risks, and delivery constraints

### Goals
- Keep the solution technically sound and maintainable
- Reduce avoidable rework and architectural drift
- Support predictable delivery and long-term operational health

### Typical Communication
- Architecture reviews and technical planning discussions
- Design documents, ADRs, and dependency mapping
- Risk and escalation updates with Project Managers and leadership

### Interaction with Existing Roles
- With Developers: provide technical direction, review quality, and support decision-making during implementation.
- With Product Managers: translate business and roadmap priorities into feasible technical scope and sequencing.
- With Project Managers: align timelines, dependencies, and risk management with engineering realities.
- With Security/Privacy and Operations roles: ensure design choices consider resilience, compliance, and deployment readiness.

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads define how a project will measure progress, customer value, and operational outcomes. They help teams decide what to instrument, how to interpret signals, and how to connect delivery to success metrics.

### Responsibilities
- Define key metrics, success criteria, and instrumentation requirements
- Collaborate with Product Managers on measurement plans and dashboard needs
- Work with Developers to ensure telemetry and analytics are implemented correctly
- Validate that data being collected supports decision-making and reporting
- Help interpret trends during releases, retrospectives, and stakeholder updates

### Goals
- Make impact measurable and actionable
- Improve evidence-based decisions across the project lifecycle
- Reduce ambiguity in product and operational performance reporting

### Typical Communication
- Metric definitions and dashboard reviews
- Reporting updates during weekly syncs and milestone reviews
- Retrospective analysis and post-release performance summaries

### Interaction with Existing Roles
- With Product Managers: align metrics with product outcomes and business goals.
- With Developers: ensure instrumentation is technically feasible and reliable.
- With Project Managers: provide evidence for progress and surfaced risks affecting delivery or adoption.
- With Stakeholders: communicate measurable outcomes and trade-offs using clear reporting.

---

## Security / Privacy Leads

### Role Summary
Security and Privacy Leads help teams identify and reduce risk related to data protection, compliance, and system integrity. They ensure project work incorporates the right controls and review points before release.

### Responsibilities
- Identify security and privacy risks during planning and execution
- Review architecture, workflows, and data handling for compliance and risk exposure
- Recommend controls, testing requirements, and remediation steps
- Partner with QA/Testing on security validation and release readiness
- Escalate issues and coordinate response when a material risk is identified

### Goals
- Protect customer and business data
- Reduce preventable security and privacy issues
- Support compliant, trustworthy delivery

### Typical Communication
- Security reviews, threat discussions, and compliance checkpoints
- Risk escalation updates and remediation tracking
- Release readiness signoff for high-impact changes

### Interaction with Existing Roles
- With Developers and Technical Leads: review design decisions and implementation safeguards.
- With Project Managers: track risk status, mitigation plans, and escalation needs.
- With Product Managers: assess business trade-offs and prioritization when controls affect scope or delivery.
- With QA/Testing: ensure verification includes security, privacy, and operational checks.

---

## Operations / SRE Leads

### Role Summary
Operations and SRE Leads ensure services are reliable, observable, and supportable in production. They help teams prepare for deployment, monitor health, and respond effectively when incidents or service issues arise.

### Responsibilities
- Define service reliability, monitoring, and alerting requirements
- Review deployment readiness and operational handoff needs
- Coordinate post-deploy verification and incident communication when needed
- Help teams reduce operational risk through runbooks, dashboards, and resilience planning
- Partner with Project Managers on release windows, rollback planning, and readiness checks

### Goals
- Minimize service disruption and recovery time
- Improve reliability, observability, and operational confidence
- Support sustainable delivery at scale

### Typical Communication
- Release readiness reviews and deployment checklists
- Incident updates, on-call escalations, and postmortem discussions
- Monitoring and reliability dashboards with stakeholders and engineering leads

### Interaction with Existing Roles
- With Developers: ensure code is observable, resilient, and ready for production operations.
- With Technical Leads: align architecture and release strategy with reliability goals.
- With Project Managers: manage deployment timing, rollback readiness, and risk communication.
- With Product Managers and Stakeholders: set expectations around service health and release impact.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Smaller teams may combine multiple responsibilities into a single role, but the responsibilities and interactions above should still be considered for clarity, accountability, and handoff quality.


