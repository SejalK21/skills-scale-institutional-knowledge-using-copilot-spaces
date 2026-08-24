# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management knowledge base. This documentation guides all cross-functional projects that deliver product features, services, or integrations.

## Our Approach

OctoAcme follows an iterative, customer-first project management methodology focused on clear ownership, data-informed decisions, and psychological safety. We deliver in increments, measure impact, and continuously improve.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation**: Problem statement, stakeholders, high-level timeline
2. **Planning**: Scope, resources, milestones, dependencies
3. **Execution**: Build, test, review, iterate
4. **Release**: Deploy, verify, announce
5. **Close & Retrospective**: Capture learnings and next steps

## OctoAcme Project Management Processes: Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. Projects begin with a lightweight one-pager that validates business need, identifies stakeholders, and establishes success metrics before moving into detailed planning. This gate-based approach ensures alignment and reduces wasted effort on misaligned initiatives.

During the planning phase, OctoAcme breaks work into shippable increments with clear acceptance criteria, estimates scope using T-shirt sizing or story points, and creates a prioritized backlog. The team defines a Definition of Done, identifies dependencies and risks, and establishes a release plan with clear milestones. Execution is governed by a structured team rhythm: daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs review updates and flagged risks, and sprint planning respects team capacity. The project board uses a consistent workflow (Backlog → Ready → In Progress → In Review → QA → Done), and pull requests remain small (≤400 lines) with automated CI checks for tests, linting, and security scanning before review and approval.

Quality and observability are embedded throughout OctoAcme's processes. Teams implement unit tests, integration tests, and end-to-end smoke tests for critical flows, with manual QA for feature acceptance as needed. Risk management is continuous: a Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) is maintained and reviewed at weekly syncs, with escalation paths from team-level triage through the PM to the Product Lead and Sponsor. Release processes are standardized with pre-release checklists, rollback plans, and post-deploy verification, while communication templates ensure transparency to stakeholders.

Finally, OctoAcme institutionalizes learning through retrospectives held after each sprint, release, or milestone. These 45–75 minute sessions capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. This continuous improvement culture, combined with weekly PM-PdM alignment, twice-weekly standups, and monthly stakeholder updates, creates a predictable, transparent environment where teams deliver incrementally, measure impact, and adapt based on evidence.

## Documentation Guide

| Document | Purpose | When to Use |
|----------|---------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's PM approach, key roles, and artifacts | Starting any project or onboarding new team members |
| [Project Initiation](octoacme-project-initiation.md) | Define initial steps to validate and authorize work | When a new project idea or feature proposal is ready |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog | After initiation approval, before execution begins |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Guidance for day-to-day execution and progress tracking | During active project delivery |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | Throughout project lifecycle; especially at planning and syncs |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardized release and deployment procedures | Before going to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert to actionable improvements | After sprints, releases, or important milestones |
| [Roles and Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities | Understanding responsibilities and communication patterns |

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

For detailed role descriptions, see [Roles and Personas](octoacme-roles-and-personas.md).

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Getting Started

1. Read the [Project Management Overview](octoacme-project-management-overview.md) for context
2. Follow the appropriate process document based on your project stage
3. Keep artifacts updated in the project repository
4. Reference these docs in team discussions and onboarding

## Questions?

If you have questions about these processes, please raise them in team syncs or create an issue to suggest clarifications or improvements using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
