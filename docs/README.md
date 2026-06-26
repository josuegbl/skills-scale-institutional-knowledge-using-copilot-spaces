# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation library. This collection of process documents provides guidance on how we run projects at OctoAcme—from initial concept through delivery, release, and continuous improvement.

## Quick Overview

OctoAcme follows a structured yet flexible project lifecycle:

1. **Initiation**: Validate the business need, align stakeholders, and decide whether to proceed
2. **Planning**: Define scope, create prioritized backlog, estimate effort, and plan releases
3. **Execution**: Build, test, and iterate while tracking progress and managing risks
4. **Release**: Deploy features with confidence using standardized release procedures
5. **Retrospective**: Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles with clear responsibilities
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Processes: Overview

### Lifecycle and Core Workflows

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The Initiation phase validates business need through a lightweight Project One-pager that captures the problem statement, measurable goals, and success metrics, with stakeholder alignment as a decision gate. Once approved, the Planning phase breaks work into shippable increments, establishes a prioritized backlog with clear acceptance criteria, and creates a release plan with defined milestones and dependencies. Execution then follows an iterative rhythm with twice-weekly standups, a project board (using columns: Backlog, Ready, In Progress, In Review, QA, Done), and pull request workflows that keep PRs small (≤400 lines) with at least one approval before merging. This structured approach ensures work remains transparent, measurable, and aligned with customer value.

### Roles, Responsibilities, and Communication

OctoAcme operates with three primary cross-functional roles: **Project Managers** who coordinate schedules, risks, and communications; **Product Managers** who define outcomes, prioritize the backlog, and measure success; and **Developers** who implement features, write tests, and identify technical risks. The communication cadence includes weekly syncs between PM and Product Manager, twice-weekly team standups, and monthly stakeholder updates, with ad-hoc escalations when needed. Risk escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and finally sponsor-level escalation for business-impacting issues. This clear ownership model combined with regular touchpoints ensures alignment and reduces surprises.

### Quality, Release, and Continuous Improvement

Quality is embedded throughout the delivery cycle with unit tests for new logic, integration tests where applicable, and end-to-end smoke tests before release, plus security scanning in CI and manual QA for feature acceptance. The Release & Deployment guide standardizes how features move to production by requiring all acceptance criteria to be met, CI and security scans to pass, and a documented rollback plan before deployment. Post-release, the team conducts retrospectives after each sprint or milestone to capture learnings and convert them into actionable improvements tracked in the project backlog. This combination of rigorous quality gates, standardized release practices, and a culture of continuous improvement ensures OctoAcme delivers reliable software while building institutional knowledge that strengthens future projects.

## Process Documentation

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, and key artifacts
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of typical project roles and responsibilities

### Project Lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate and authorize new work
- [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution and progress tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release procedures and deployment checklists
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Managing risks, dependencies, and stakeholder communication

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Need guidance on a specific phase?** Use the links above to jump to the relevant process document
- **Managing risks or communication?** Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md)

## Maintaining These Docs

These documents are living artifacts that evolve with our practices:

- Propose updates using the [Add/Update Content to Process Docs](https://github.com/josuegbl/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) issue template
- Review and validate changes during retrospectives
- Keep docs current by incorporating team feedback and lessons learned

## Questions or Feedback?

If you have suggestions for improving these docs or notice gaps in our processes, please open an issue or reach out to the Project Management team.
