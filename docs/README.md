# OctoAcme Project Management Process Documentation

## Overview

OctoAcme runs projects using a customer-first, iterative delivery model with clear ownership, data-informed decisions, and a focus on psychological safety. These process documents provide guidance for every phase of project delivery.

OctoAcme follows a structured lifecycle approach to project delivery that emphasizes customer value, iterative development, and clear ownership. The framework spans five core phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with dependencies mapped), **Execution** (building, testing, and iterating with daily standups and regular demos), **Release** (standardized deployment with pre-release verification and rollback plans), and **Close & Retrospective** (capturing learnings and continuous improvement). This end-to-end structure ensures projects move through clear decision gates and maintain consistent stakeholder engagement from conception through delivery.

The organization defines three primary roles with distinct responsibilities: **Project Managers** coordinate delivery activities, manage schedules, risks, and communications; **Product Managers** define what should be built by owning the product vision, prioritizing the backlog, and measuring outcomes; and **Developers** implement features while collaborating on design, testing, and risk identification. This clear role separation prevents ambiguity while enabling cross-functional collaboration. Each project is assigned named PM and Product Lead owners who maintain accountability throughout the lifecycle. Beyond these core roles, stakeholders, QA/Testing personnel, and domain experts contribute specialized expertise during planning, execution, and validation phases.

Communication cadence is formalized to ensure alignment and reduce surprises. The team maintains **weekly syncs between PM and PdM**, **twice-weekly standups for delivery teams**, **monthly stakeholder updates**, and **ad-hoc escalations** as needed. Risk management is embedded throughout the process via a Risk Register that tracks ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed weekly and updated continuously. Escalation follows a structured path: team-level triage → PM escalation to Product Lead → Sponsor-level escalation for business-impacting issues, with security incidents following dedicated runbooks.

Quality assurance and delivery rigor are woven throughout execution and release. The team uses small PRs (≤400 lines when possible), automated CI/CD for tests and linting, and requires at least one approval before merging. Testing includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Before any release—whether patch, minor, or major—all acceptance criteria must be met, CI and security scans must pass, and rollback/mitigation plans must be documented. This combination of clear processes, role clarity, regular communication, and rigorous quality checks positions OctoAcme to deliver reliably while maintaining visibility and learning across projects.

## Quick Navigation

### Project Lifecycle Phases

1. **[Project Initiation Guide](./octoacme-project-initiation.md)** — Start here for new ideas
   - Validate business need, identify stakeholders, create project one-pager
   - When to use: When a new project idea or feature proposal is ready to explore

2. **[Project Planning](./octoacme-project-planning.md)** — Turn approval into an actionable plan
   - Break work into shippable increments, identify dependencies, align timelines
   - When to use: After initiation approval, before execution begins

3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery
   - Daily standups, project board workflow, quality standards, risk escalation
   - When to use: During active development and sprint execution

4. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases to production
   - Pre-release checklist, deployment procedures, rollback playbook
   - When to use: When preparing features for production release

5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings
   - Run effective retros, track action items, improve iteratively
   - When to use: After sprints, releases, or important milestones

### Cross-Cutting Guidance

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme principles, roles, and artifacts
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks; escalation paths; status templates
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Responsibilities and goals for Developers, Product Managers, and Project Managers

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria

## Communication Cadence

- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly PM + PdM sync
- Twice-weekly delivery team standups (or as agreed)
- Monthly stakeholder updates
- Demo/Review at end of each sprint or milestone

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md)
2. **Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md)
3. **In active development?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
4. **Preparing to ship?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
5. **Wrapping up?** Run a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md) and capture learnings

## Contributing to Process Docs

Have feedback or want to improve these processes? Open an issue using the **Add Content to Project Management Process Docs** template in `.github/ISSUE_TEMPLATE/`.
