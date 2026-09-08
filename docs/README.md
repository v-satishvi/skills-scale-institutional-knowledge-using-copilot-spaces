# OctoAcme Project Management Process Documentation

## Overview

OctoAcme follows a structured, customer-first project management approach designed to deliver value iteratively while maintaining clear ownership, risk awareness, and data-informed decision-making. This documentation centralizes the processes, workflows, personas, and best practices used across all OctoAcme projects.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation** - Validate the business need, align stakeholders, and define success criteria through a Project One-pager
2. **Planning** - Break work into shippable increments with prioritized backlogs, acceptance criteria, and risk identification
3. **Execution** - Build, test, review, and iterate with daily standups (15 min), weekly delivery syncs, and GitHub Projects for tracking
4. **Release** - Deploy to production with pre-release verification, smoke tests, rollback planning, and post-deploy verification
5. **Retrospective** - Capture learnings and convert them into actionable improvements with clear owners and timelines

## Project Management Workflows & Practices

**Execution & Quality Assurance**

OctoAcme emphasizes quality throughout the delivery cycle. Teams use GitHub Projects with columns (Backlog, Ready, In Progress, In Review, QA, Done) to track progress. Pull requests must be small (≤400 lines when possible) and include issue links and acceptance criteria in descriptions. All code must pass automated tests, linting, and security scanning in CI before review. Unit tests are required for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. Manual QA is conducted for feature acceptance when needed.

**Risk Management & Communication**

Risks are captured systematically in a Risk Register (with ID, description, impact, likelihood, owner, and mitigation plan) during planning and ongoing execution, then monitored and updated weekly. Cross-team dependencies are marked in the project board and escalated during weekly syncs. Risk escalation follows a three-level path: team-level triage in daily standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Communication cadence includes twice-weekly standups for the delivery team, weekly PM/Product Lead syncs, and monthly stakeholder updates.

**Metrics & Continuous Improvement**

OctoAcme tracks velocity and burndown to measure progress, and monitors success metrics identified in the Project One-pager via dashboards for key signals (errors, latency, usage). Retrospectives are held after each sprint, release, or milestone to review what went well, what could improve, and to prioritize 2–3 actionable improvements. Action items are tracked in the project backlog with clear owners and due dates, and their impact is measured to drive continuous refinement of processes.

## Core Roles & Personas

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications to ensure on-time delivery
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success through data-informed decisions
- **Developers**: Implement features, write tests, collaborate on design, and help identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria throughout the delivery cycle

For detailed role definitions and responsibilities, see [Personas & Roles](./octoacme-roles-and-personas.md).

## Process Documentation

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** - Quick intro to OctoAcme's approach, roles, and key artifacts
- **[Personas & Roles](./octoacme-roles-and-personas.md)** - Detailed definitions of Project Managers, Product Managers, Developers, and QA/Testing roles

### By Project Lifecycle Phase

#### Initiation Phase
- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Steps to validate business need, align stakeholders, and authorize work. Includes the Project One-pager template and decision gate criteria.

#### Planning Phase
- **[Project Planning](./octoacme-project-planning.md)** - Breaking work into shippable increments, backlog prioritization, estimation, Definition of Done, risk identification, and release planning.

#### Execution Phase
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Day-to-day delivery workflows, standup cadence, PR guidelines, quality standards, testing requirements, and progress tracking.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Risk registers, escalation paths, stakeholder communication templates, and incident response procedures.

#### Release Phase
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Pre-release requirements, deployment checklists, rollback procedures, and release notes templates.

#### Retrospective Phase
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Running effective retrospectives, capturing learnings, tracking action items, and driving continuous process improvements.

## How to Use These Docs

- **New team members**: Start with "[Project Management Overview](./octoacme-project-management-overview.md)" and "[Personas & Roles](./octoacme-roles-and-personas.md)" to understand OctoAcme's approach and your role
- **Starting a new project**: Follow the Initiation → Planning → Execution flow using the respective phase guides
- **During project delivery**: Refer to "[Execution & Tracking](./octoacme-execution-and-tracking.md)" and "[Risk Management & Communication](./octoacme-risks-and-communication.md)" for day-to-day guidance
- **Wrapping up**: Use "[Release & Deployment](./octoacme-release-and-deployment.md)" and "[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)" guides

## Key Artifacts & Templates

Across the project lifecycle, OctoAcme teams create and maintain:

- Project Charter / One-pager (Problem, Goal, Success Metrics)
- Prioritized Backlog with Acceptance Criteria
- Definition of Done
- Risk Register
- Release Plan & Milestone Map
- Weekly Status Reports
- Retrospective notes and action items

See the individual phase guides for templates and examples.

## Communication & Reporting

- **Weekly PM + PdM sync**: Alignment on priorities, risks, and blockers
- **Twice-weekly standups**: Delivery team progress, blockers, and dependencies
- **Monthly stakeholder updates**: Progress, metrics, and upcoming milestones
- **Ad-hoc escalations**: For blockers, risks, or decisions requiring immediate attention

For communication templates and escalation procedures, see [Risk Management & Communication](./octoacme-risks-and-communication.md).

---

## Contributing to These Docs

To propose updates or additions to the OctoAcme process documentation, please use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.
