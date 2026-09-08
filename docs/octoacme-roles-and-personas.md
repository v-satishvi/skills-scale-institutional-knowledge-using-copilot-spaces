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

## Product Lead

### Role Summary
Product Leads provide strategic direction and ensure product coherence across multiple projects and initiatives. They review and approve high-level project plans, arbitrate priority conflicts, and serve as the decision-making authority for product trade-offs.

### Responsibilities
- Review and approve project one-pagers and high-level timelines
- Arbitrate feature prioritization conflicts between projects
- Participate in project kickoffs and key milestone reviews
- Escalate and resolve cross-project dependencies
- Ensure alignment between individual projects and broader product strategy
- Approve release decisions and go/no-go milestones

### Interaction with Existing Roles
- **Works with Product Managers**: Reviews and validates backlog prioritization and product strategy alignment
- **Works with Project Managers**: Approves project charters and provides escalation authority for prioritization conflicts
- **Works with Developers**: Participates in design reviews to ensure technical approach aligns with product vision
- **Works with QA/Testing**: Reviews quality gates and release readiness before go/no-go decisions

### Goals
- Maintain coherent product vision across multiple concurrent projects
- Enable fast decision-making and unblock planning/execution delays
- Ensure projects deliver strategic value and customer impact

### Typical Communication
- Weekly PM + PdM + Product Lead alignment meeting
- Project kickoff and milestone gate reviews
- Escalation path for prioritization and strategic decisions
- Release approval and post-launch retrospectives

---

## QA/Testing Lead

### Role Summary
QA and Testing specialists define quality standards, create test strategies, and validate that features meet acceptance criteria and quality gates before release. They work collaboratively with developers and product teams to ensure customer confidence in delivered features.

### Responsibilities
- Define Definition of Done (DoD) quality criteria with the team
- Create test plans and acceptance test cases aligned to requirements
- Execute automated and manual testing throughout development
- Participate in release readiness reviews and smoke testing
- Identify and document quality gaps or technical debt
- Collaborate with developers on test coverage and CI/CD automation setup
- Validate that all acceptance criteria are met before moving to Done

### Interaction with Existing Roles
- **Works with Developers**: Reviews test coverage, participates in code reviews from a testability perspective, and collaborates on CI/CD test automation
- **Works with Product Managers**: Reviews and refines acceptance criteria to ensure testability and clarity
- **Works with Project Managers**: Provides test status updates in standups and participates in sprint planning
- **Works with Product Lead**: Participates in release readiness sign-offs and quality gate approvals

### Goals
- Ensure all features meet acceptance criteria before release
- Minimize defects reaching production
- Reduce manual testing burden through automation
- Provide confidence in release readiness

### Typical Communication
- Sprint planning and acceptance criteria refinement meetings
- Pull request reviews (from QA and testability perspective)
- Weekly status updates on test coverage and blockers
- Pre-release readiness sign-off and smoke test reports

---

## Stakeholder

### Role Summary
Stakeholders provide business context, inputs, and approvals throughout the project lifecycle. They represent various organizational interests (e.g., sales, marketing, customer success, support) and help ensure projects deliver value to intended beneficiaries.

### Responsibilities
- Provide inputs on business requirements and customer needs
- Review and approve project charters and key milestones
- Receive regular status updates and participate in key decision gates
- Offer feedback on prototypes, features, and release readiness
- Communicate project progress to their functional area
- Identify blockers or dependencies affecting their teams

### Interaction with Existing Roles
- **Works with Product Managers**: Provides customer and business context to inform prioritization and feature definition
- **Works with Project Managers**: Participates in kickoff, milestone reviews, and receives weekly status updates
- **Works with Developers**: Reviews demos and provides feedback on feature usability and business fit
- **Works with Sponsors**: Escalates major issues or resource conflicts that require executive attention

### Goals
- Ensure projects deliver value to their functional area
- Maintain alignment between project outcomes and business objectives
- Provide timely feedback to improve product decisions

### Typical Communication
- Project kickoff and milestone review meetings
- Weekly or milestone-based status updates
- Demo and review sessions
- Escalation communications to Sponsors when needed

---

## Sponsor

### Role Summary
Sponsors are executive-level owners of project success who provide strategic authorization, resource allocation, and high-level escalation authority. They champion the work, ensure alignment with organizational strategy, and remove business-level blockers.

### Responsibilities
- Define business goals and success criteria at project initiation
- Approve project charter, budget, and high-level timeline
- Allocate resources (team members, tools, budget) to enable delivery
- Participate in key decision gates and milestone approvals
- Escalate and resolve business-level blockers impacting project success
- Communicate project status to leadership and board (if applicable)
- Make strategic trade-off decisions between scope, timeline, and quality

### Interaction with Existing Roles
- **Works with Product Managers**: Approves strategic direction and ensures product initiatives align with business strategy
- **Works with Project Managers**: Provides approval authority for project charters and major scope changes; receives executive status reports
- **Works with Stakeholders**: Escalates stakeholder-level conflicts and provides resources to resolve cross-functional dependencies
- **Works with Product Lead**: Collaborates on strategic prioritization and release decisions

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy and financial objectives
- Support delivery team with authority and resources to succeed
- Minimize business disruption and maximize ROI on project investment

### Typical Communication
- Project initiation and approval meetings
- Monthly executive status reports
- Key decision gates and milestone approvals
- Post-project retrospectives and value realization assessments

---

## Security Lead

### Role Summary
Security Leads ensure that security requirements are met throughout the project lifecycle. They participate in design reviews, define security testing requirements, and lead incident response for security-related issues.

### Responsibilities
- Conduct security reviews during project planning and design phases
- Define security requirements and acceptance criteria
- Review security scanning results in CI/CD and triage findings
- Participate in threat modeling and risk assessment activities
- Define secure coding standards and security testing plans
- Lead incident response and post-incident analysis for security issues
- Provide security training and guidance to development teams
- Ensure compliance with organizational security policies and standards

### Interaction with Existing Roles
- **Works with Developers**: Reviews code and architecture for security vulnerabilities; provides guidance on secure coding practices
- **Works with Product Managers**: Advises on security requirements and impact of security constraints on feature design
- **Works with Project Managers**: Participates in risk assessments and provides escalation path for security incidents
- **Works with QA/Testing**: Collaborates on security and penetration testing requirements
- **Works with Sponsors**: Escalates critical security findings and ensures security governance is understood at executive level

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure projects meet compliance and regulatory requirements
- Build a security-first culture across the organization
- Minimize risk exposure and potential business impact of security incidents

### Typical Communication
- Design review meetings and security threat modeling sessions
- Security scanning and vulnerability reports
- Incident response and post-incident review communications
- Security policy updates and team training sessions
- Monthly security status reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to these role definitions when clarifying responsibilities and escalation paths in project scenarios.
