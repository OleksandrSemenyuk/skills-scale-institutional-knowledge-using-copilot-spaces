# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative project management approach that emphasizes customer value, clear ownership, data-informed decisions, and psychological safety. This documentation suite is the single entry point for our process docs and guidance for running cross-functional projects.

## Quick Summary of Processes
- Initiation — Validate the problem, stakeholders, and success metrics so projects are authorized with a lightweight plan.
- Planning — Create the backlog, estimate scope, define the Definition of Done, and map releases and dependencies.
- Execution & Tracking — Manage day-to-day work, run CI, track velocity, escalate blockers, and keep the risk register current.
- Risks & Communication — Identify, assess, mitigate, and communicate risks to stakeholders with a clear escalation path.
- Release & Deployment — Standardize release types, pre-release checks, and rollback/playbook procedures.
- Retrospective & Improvement — Run post-release retrospectives, convert learnings to action items, and measure improvements.
- Roles & Personas — Clarify responsibilities for Developers, Product Managers, Project Managers, QA, and Stakeholders.

## Documents (in docs/)
| Phase | Document | Purpose |
|-------|----------|---------|
| Overview | [Project Management Overview](octoacme-project-management-overview.md) | Core roles, principles, and lifecycle |
| Initiation | [Project Initiation Guide](octoacme-project-initiation.md) | Validate need and authorize work |
| Planning | [Project Planning](octoacme-project-planning.md) | Create actionable plans and backlog |
| Execution | [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day management and progress |
| Risk Management | [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify and manage risks and dependencies |
| Release | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize release processes |
| Closure | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and improve |
| Reference | [Roles & Personas](octoacme-roles-and-personas.md) | Define key roles and responsibilities |

## How to use these docs
1. Start with the [Project Management Overview](octoacme-project-management-overview.md).
2. For a new project, follow the [Project Initiation Guide](octoacme-project-initiation.md).
3. Use the phase-specific guides (Planning → Execution → Release → Retrospective) as work progresses.
4. Add project-specific artifacts (one-pager, risk register, acceptance criteria) to the project repo and keep these docs as the canonical process reference.
5. To include these docs in Copilot Spaces, add process-specific docs into `.copilot/` as needed.

## Quick Start for New Team Members
- Read the Overview.
- Use the Initiation checklist to create a one-pager and stakeholder list.
- Follow Planning to produce a prioritized backlog and release plan.
- Execute using the Execution & Tracking workflows and update the risk register weekly.
- At release, follow the Release & Deployment checklist and run post-release verifications.
- Run retrospectives and convert action items into issues with owners and due dates.

## Feedback & Contributions
To propose edits or add new process content, open an issue using the "Add Content to Project Management Process Docs" template in `.github/ISSUE_TEMPLATE/`.
