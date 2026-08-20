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

### Key Interactions
- **With QA/Testing Lead**: Collaborate on test coverage, testability, and acceptance criteria validation
- **With Technical Lead/Architect**: Follow architecture guidance and design reviews
- **With Project Managers**: Provide status updates and flag blockers
- **With Product Managers**: Clarify requirements and acceptance criteria

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

### Key Interactions
- **With Stakeholders/Sponsors**: Communicate business priorities and collect approvals
- **With Project Managers**: Align on scope, timeline, and resource trade-offs
- **With Developers**: Define requirements and acceptance criteria
- **With QA/Testing Lead**: Define success metrics and test strategy

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

### Key Interactions
- **With Stakeholders/Sponsors**: Escalate risks and blockers; provide status updates
- **With Product Managers**: Manage scope and timeline trade-offs
- **With Developers & QA/Testing Lead**: Track progress and identify impediments
- **With Technical Lead/Architect**: Coordinate technical dependencies and architecture decisions

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Design and maintain test plans aligned with features
- Execute acceptance criteria validation
- Conduct smoke tests before releases
- Report quality metrics and blockers
- Collaborate with developers on testability and test automation
- Identify gaps in test coverage and define mitigation strategies
- Validate releases meet pre-release requirements

### Goals
- Minimize production defects
- Provide confidence in releases through comprehensive testing
- Reduce rework cycles and support burden
- Maintain quality standards throughout the delivery lifecycle

### Typical Communication
- Sprint planning and backlog refinement
- Daily standups and pre-release verification meetings
- Quality dashboards and defect reports
- Test strategy and acceptance criteria alignment sessions

### Key Interactions
- **With Developers**: Collaborate on testability, test automation, and defect triage
- **With Product Managers**: Validate acceptance criteria and refine test strategy
- **With Project Managers**: Report quality status and escalate quality blockers
- **With Technical Lead/Architect**: Review test architecture and performance testing strategy
- **With Security/Compliance Officer**: Coordinate security and compliance testing

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders/Sponsors are business owners or key decision-makers who provide business context, approvals, and resource authority for projects. They represent customer needs and business priorities.

### Responsibilities
- Approve project initiation, scope, and major changes
- Provide business priorities, constraints, and success metrics
- Escalate blockers impacting project viability or business value
- Review and approve releases before go-live
- Communicate outcomes and impact to broader organization
- Remove business and political blockers
- Validate that delivered solutions meet business objectives

### Goals
- Ensure projects deliver business value and ROI
- Minimize risk to business outcomes
- Maintain stakeholder alignment and buy-in
- Ensure timely decision-making on scope and priority trade-offs

### Typical Communication
- Monthly stakeholder updates and progress briefings
- Milestone approvals and gate reviews
- Risk and blocker escalations
- Release announcements and business impact communication
- Ad-hoc decision forums when needed

### Key Interactions
- **With Project Managers**: Receive status updates, approve scope changes, escalate blockers
- **With Product Managers**: Align on business priorities and success metrics
- **With Developers & QA/Testing Lead**: Review release readiness and approve go-live
- **With Security/Compliance Officer**: Approve security and compliance trade-offs

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects guide technical strategy, design decisions, and code quality. They ensure solutions are scalable, maintainable, and aligned with system architecture.

### Responsibilities
- Design technical solutions for major features and components
- Review architecture and code quality during design and implementation
- Identify technical risks, dependencies, and mitigation strategies
- Mentor developers and guide best practices and standards
- Coordinate cross-team technical efforts and integration points
- Make architectural trade-offs between performance, scalability, and maintainability
- Review system design for security, compliance, and operational readiness

### Goals
- Maintain system health and scalability
- Reduce technical debt and future rework
- Accelerate delivery through good design and reusable patterns
- Foster engineering excellence and learning

### Typical Communication
- Design review meetings and architecture discussions
- Architecture decision records and technical documentation
- Code review and peer feedback
- Technical risk escalations and dependency coordination
- Engineering mentorship and guidance sessions

### Key Interactions
- **With Developers**: Provide architecture guidance, conduct design and code reviews, mentor on best practices
- **With QA/Testing Lead**: Review test architecture and performance testing strategy
- **With Project Managers**: Identify and coordinate technical dependencies
- **With Security/Compliance Officer**: Review security architecture and ensure compliance by design

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security, compliance, and data protection requirements. They conduct reviews and gate releases for security and regulatory readiness.

### Responsibilities
- Review features for security and compliance risks early in planning
- Conduct or coordinate security scanning and assessments in CI/CD
- Provide guidance on data handling, authentication, and authorization
- Gate releases for security readiness and compliance sign-off
- Track compliance metrics and audit requirements
- Maintain security standards and incident response procedures
- Advise on security best practices and risk mitigation strategies

### Goals
- Protect customer data and system integrity
- Meet regulatory compliance obligations and audit requirements
- Reduce security incidents and their impact
- Enable secure delivery without slowing velocity

### Typical Communication
- Security reviews during design and planning phases
- Security scanning results and threat assessment
- Incident response and post-incident reviews
- Pre-release security gates and approval
- Compliance reporting and audit preparation

### Key Interactions
- **With Developers & Technical Lead/Architect**: Review security architecture, provide secure coding guidance
- **With QA/Testing Lead**: Coordinate security and compliance testing
- **With Project Managers**: Escalate security risks and blockers
- **With Stakeholders/Sponsors**: Approve security and compliance trade-offs, report compliance status

---

## Scrum Master/Agile Coach (Optional)

### Role Summary
Scrum Masters/Agile Coaches facilitate team processes, remove blockers, and coach teams on Agile practices. This role is optional and typically used when the organization adopts formal Agile methodologies.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Monitor and remove team impediments and blockers
- Coach team on Agile best practices and continuous improvement
- Maintain team velocity metrics and burndown tracking
- Help teams adapt processes and resolve conflicts
- Foster psychological safety and encourage feedback
- Protect the team from external interruptions and scope creep

### Goals
- Maximize team productivity and flow
- Foster psychological safety and trust
- Enable continuous improvement and learning
- Maintain sustainable pace and prevent burnout

### Typical Communication
- Daily standups and impediment removal
- Sprint ceremonies (planning, review, retrospectives)
- Team health and velocity metrics
- Coaching and feedback conversations
- Process improvement initiatives

### Key Interactions
- **With All Roles**: Facilitate effective communication and collaboration
- **With Project Managers**: Coordinate sprint timing and capacity planning
- **With Developers & QA/Testing Lead**: Remove impediments and unblock work
- **With Team Members**: Coach on Agile principles and help teams self-organize

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When creating scenarios or role-playing exercises, reference the responsibilities, goals, and key interactions to ensure realistic collaboration patterns.
