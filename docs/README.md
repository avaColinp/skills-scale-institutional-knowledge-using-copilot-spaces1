# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This folder contains guides, checklists, and templates that standardize how we run projects from initiation through closure.

## Overview

OctoAcme follows a structured, milestone-based approach to project delivery:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Named Project Manager (PM) and Product Lead for each project
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

## Project Management Process Summary

OctoAcme's project lifecycle begins with initiation, where the team validates the business need, identifies stakeholders, defines success metrics, and makes a go/no-go decision for planning. Once approved, the team creates a lightweight project plan with a charter or one-pager, prioritized backlog with acceptance criteria, milestones, dependencies, and resource needs. Execution follows a structured workflow using project boards with clear columns (Backlog, Ready, In Progress, In Review, QA, Done), supported by daily standups and weekly delivery syncs. Work is kept incremental with small, reviewable pull requests that link to issues, and changes are gated by CI checks (tests, linting, security scans) and required approvals before merge.

The planning and execution phases are complemented by robust quality practices and clear role ownership. Developers build features and write tests, Product Managers define problems and success metrics, and Project Managers coordinate timelines, risks, and stakeholder communication. QA/Testing validates quality and acceptance, while stakeholders provide input and decisions. Communication is a core control—teams maintain risk registers, track dependencies, escalate issues through clear paths, and use regular status reporting to keep stakeholders aligned.

Finally, OctoAcme's approach includes standardized release and deployment procedures (with gating requirements, smoke tests, and rollback planning) followed by retrospectives at the end of each sprint or milestone. Retrospectives capture lessons learned and convert them into action items with clear owners and due dates, reinforcing a culture of continuous improvement. This structured yet flexible framework ensures each project delivers measurable customer value while maintaining transparency, quality, and team learning throughout the lifecycle.

## Process Documents

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, and key artifacts
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of Developers, Product Managers, Project Managers, and their responsibilities

### Project Phases

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, create lightweight plan
2. **[Project Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable backlog and release plan
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, and maintain quality
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize release process, reduce risk, and improve observability
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout all project phases

## Quick Links
- [Process Doc Update Issue Template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- [Copilot Spaces Setup Guide](../)

## How to Use These Docs
- Keep your Project Charter updated in your project repo
- Reference the appropriate phase guide for current activities
- Add process-specific docs into `.copilot/` if using Copilot Spaces for context
- Use the Process Doc Update issue template to propose improvements or new content
