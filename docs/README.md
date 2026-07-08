# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process documentation. This folder contains comprehensive guidance for running projects at OctoAcme, from initial concept through release and retrospectives.

## Quick Start

**New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand our core principles, roles, and lifecycle.

## Our Approach

OctoAcme follows a structured yet iterative approach to project delivery:
- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: each project has a named PM and Product Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## Project Management Overview

OctoAcme's project management model is designed to centralize scattered knowledge, convert tacit team insights into searchable artifacts, and give all team members equal access to processes and decisions. Our approach connects repositories as structured knowledge sources and enables consistent, repeatable project execution across teams.

### Key Principles
- **Deliver iteratively** with small, testable increments
- **Maintain clear ownership** with named Project Managers and Product Leads
- **Make data-informed decisions** through measurement and evidence
- **Foster psychological safety** by encouraging feedback and learning
- **Prioritize customer value** in every decision

### Core Roles
- **Project Manager**: Coordinates delivery, schedules, risk, and communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Communication Cadence
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly PM + PdM sync — coordination and alignment
- Twice-weekly delivery team standups (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

### Quality & Assurance
Quality is embedded throughout execution:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small PRs (≤400 lines) with at least one approval before merge

## Documentation by Phase

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation](./octoacme-project-initiation.md) | Validate business need, align stakeholders, create lightweight plan |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments, identify dependencies |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress, escalate blockers |
| **Release** | [Release & Deployment](./octoacme-release-and-deployment.md) | Standardize releases, reduce risk, improve observability |
| **Close-Out** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, convert to actionable improvements |

## Supporting Resources

- [Risk Management & Communication](./octoacme-risks-and-communication.md) – Identify, manage, and communicate risks across project phases
- [OctoAcme Personas & Roles](./octoacme-roles-and-personas.md) – Understand typical roles, responsibilities, and communication patterns

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Using These Docs in Your Project

1. **Start here**: Read the [Project Management Overview](./octoacme-project-management-overview.md) to familiarize yourself with OctoAcme's model
2. **Follow the phases**: Navigate the documentation by your current project phase
3. **Reference as needed**: Use the supporting resources for risk management, communication, and role clarification
4. **Keep artifacts updated**: Maintain the project charter, risk register, and status updates in your project repository

## Getting Help

If you have questions about OctoAcme's processes or would like to propose updates, please open an issue using our [Process Doc Update Template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
