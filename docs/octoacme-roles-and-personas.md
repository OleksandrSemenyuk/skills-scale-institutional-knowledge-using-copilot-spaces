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

## Additional Personas (New additions)

### Technical Lead
Role summary: Senior engineer responsible for technical architecture, design decisions, and technical quality across the project.

Responsibilities:
- Define and validate architecture choices and key technical approaches
- Ensure non-functional requirements (scalability, performance, maintainability) are addressed
- Mentor engineers and coordinate technical design reviews

Interaction with existing roles:
- Works with Developers to translate designs into implementations
- Advises PM/PdM on technical trade-offs and effort implications
- Collaborates with QA on test strategy and acceptance criteria

---

### UX Designer
Role summary: Responsible for user research, interaction design, and ensuring design quality and usability.

Responsibilities:
- Lead user research and prototype testing for features
- Produce wireframes, interaction specs, and visual assets
- Validate designs against acceptance criteria

Interaction with existing roles:
- Partner with PdM to align user needs and product goals
- Deliver design handoffs to Developers and clarify UX intent
- Work with QA to define usability acceptance checks

---

### Release Engineer (Release Manager)
Role summary: Coordinates release pipelines, deployment schedules, and rollbacks for production changes.

Responsibilities:
- Maintain deployment pipelines and release checklists
- Coordinate staging/production deployments and rollback plans
- Ensure release notes and stakeholder communications are prepared

Interaction with existing roles:
- Works with PM/PdM to schedule release windows
- Coordinates with DevOps/Platform and Security for safe deployments
- Notifies Support/Customer Success and Stakeholders on release outcomes

---

### Security Lead
Role summary: Ensures security requirements and reviews are part of project lifecycle.

Responsibilities:
- Conduct threat modelling and security reviews
- Coordinate security scans and remediation plans
- Define and validate security acceptance criteria

Interaction with existing roles:
- Advises Developers and Technical Lead on secure design
- Works with Release Engineer and DevOps on secure deployment practices
- Escalates security risks to PM/PD when business impact is identified

---

### Data Analyst / Data Lead
Role summary: Owns data definitions, tracking, and analysis that measure success metrics.

Responsibilities:
- Define instrumentation and metrics to validate success criteria
- Create dashboards and analysis to inform product decisions
- Validate data quality and report on outcomes post-release

Interaction with existing roles:
- Works with PdM to define measurable success criteria
- Provides Developers with schema and tracking requirements
- Supports retrospectives with data-driven insights

---

### Customer Success / Support Liaison
Role summary: Represents customer-facing insights and coordinates support readiness.

Responsibilities:
- Surface customer feedback and support trends to the team
- Prepare knowledge base updates and runbook changes for releases
- Coordinate post-release support and escalations

Interaction with existing roles:
- Works with PM/PdM on prioritizing customer-impacting fixes
- Coordinates with Release Engineer for stakeholder communications
- Collaborates with QA on reproducing customer issues

---

### DevOps / Platform Engineer
Role summary: Builds and maintains infrastructure, CI/CD, and platform services.

Responsibilities:
- Maintain infrastructure-as-code and CI pipelines
- Monitor platform health and respond to incidents
- Optimize deployment reliability and scalability

Interaction with existing roles:
- Works with Developers/Technical Lead during architecture and deployments
- Coordinates with Release Engineer and Security Lead for production changes
- Provides operational runbooks for Support and Customer Success

---

### Change Manager (optional for larger programs)
Role summary: Manages organizational change impact, stakeholder readiness, and rollout coordination.

Responsibilities:
- Plan stakeholder communications and training for major changes
- Assess organizational readiness and adoption risks
- Track adoption metrics post-release

Interaction with existing roles:
- Works with PM/PdM and Customer Success to coordinate rollout
- Ensures documentation and training materials are available

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Next steps / Suggested edits
- Add contact or on-call information where applicable (e.g., Security on-call)
- Add links to team runbooks or org-specific role owners if available
- Consider adding a short table that maps persona -> primary responsibilities for quick scanning
