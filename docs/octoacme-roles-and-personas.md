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

## Product Lead

### Role Summary
Product Leads provide strategic oversight and decision authority for product direction. They collaborate with Product Managers to ensure alignment with long-term vision and cross-project dependencies.

### Responsibilities
- Set product strategy and long-term vision
- Oversee multiple products or product lines
- Make prioritization trade-offs across projects
- Review and approve major product decisions
- Escalate risks and strategic concerns to executive leadership

### Goals
- Align all product work with organizational strategy
- Maximize cross-project synergies and prevent conflicts
- Reduce rework caused by misalignment

### Typical Communication
- Weekly sync with Product Managers
- Monthly roadmap reviews
- Leadership updates and strategic planning sessions

### Interaction with Existing Roles
- **With Product Managers**: Provides strategic direction and decides trade-offs; PdMs implement the strategy for individual products
- **With Project Managers**: Reviews high-priority project charters and approves major scope decisions
- **With Developers**: Communicates product vision and strategic priorities through Product Managers and design reviews
- **With Stakeholders**: Aligns business strategy and escalates executive-level risks

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

### Interaction with Existing Roles
- **With Developers**: Coordinates schedules, removes blockers, and tracks progress
- **With Product Managers**: Aligns delivery milestones with product priorities
- **With QA/Testing Leads**: Integrates testing timelines and quality gates into project schedule
- **With Stakeholders/Sponsors**: Provides regular status updates and escalates risks
- **With Product Lead**: Escalates strategic decisions and cross-project dependencies

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance, testing strategy, and acceptance validation. They ensure features meet acceptance criteria and maintain quality standards throughout the delivery lifecycle.

### Responsibilities
- Design and execute test plans (unit, integration, end-to-end)
- Validate acceptance criteria before feature handoff
- Coordinate with developers on test coverage and CI/CD integration
- Report quality metrics and defects
- Recommend quality improvements and testing tooling

### Goals
- Ensure zero critical defects reach production
- Reduce cycle time through effective test automation
- Maintain high quality standards while supporting delivery velocity

### Typical Communication
- Sprint planning and quality discussions
- Test reports and defect summaries
- QA sign-off on features before release

### Interaction with Existing Roles
- **With Developers**: Collaborates on test design, coverage strategy, and CI/CD configuration
- **With Product Managers**: Validates acceptance criteria and tests feature usability
- **With Project Managers**: Provides quality metrics and identifies testing risks/dependencies
- **With Stakeholders/Sponsors**: Reports on quality metrics and release readiness

---

## Stakeholders / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, prioritization guidance, and approval authority. They represent business, customer, or organizational interests in the project.

### Responsibilities
- Approve project charter and resource allocation
- Provide business requirements and success criteria input
- Participate in milestone reviews and release decisions
- Escalate risks and dependencies to executive leadership
- Support team in securing cross-functional dependencies

### Goals
- Ensure project delivers business value
- Maintain executive visibility and organizational alignment
- Remove organizational blockers to project success

### Typical Communication
- Project kickoff and initiation meetings
- Monthly stakeholder updates and milestone reviews
- Escalation and decision gates

### Interaction with Existing Roles
- **With Project Managers**: Receives regular status updates; provides approvals and prioritization guidance
- **With Product Managers**: Aligns on success metrics and business outcomes
- **With Product Lead**: Receives strategic updates and participates in major prioritization decisions
- **With Developers**: Participates in demos and review sessions; provides feedback on deliverables
- **With Security/Compliance Lead**: Reviews compliance requirements and security decisions

---

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads ensure projects meet security, privacy, and regulatory requirements. They provide guidance on threat assessment, secure design, and compliance validation.

### Responsibilities
- Conduct security reviews and threat assessments
- Define security and privacy acceptance criteria
- Coordinate security scanning and testing in CI/CD
- Review and approve security implementations
- Manage incident response and post-incident reviews

### Goals
- Prevent security and privacy incidents in production
- Ensure compliance with applicable regulations
- Enable secure delivery velocity through clear guardrails

### Typical Communication
- Design reviews and security assessments
- Security scanning reports and findings
- Incident response and escalation
- Compliance attestation and audit support

### Interaction with Existing Roles
- **With Developers**: Participates in design reviews and security assessments; defines secure coding standards
- **With Product Managers**: Identifies security and compliance requirements during feature planning
- **With Project Managers**: Integrates security testing and compliance reviews into project milestones
- **With QA/Testing Leads**: Coordinates security testing strategy and vulnerability scanning
- **With Stakeholders/Sponsors**: Reports on compliance status and security posture; escalates critical risks

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
