# OctoAcme Project Management Docs

This README provides a comprehensive summary of OctoAcme's project management processes and links to the detailed process documents stored in this repository's docs/ folder.

## Summary

OctoAcme runs iterative, customer-focused projects with clear roles (PM, PdM, Developers, QA). We follow a structured five-phase lifecycle: **Initiation → Planning → Execution → Release → Retrospective**.

### Core Lifecycle and Workflow

The initiation phase focuses on validating business needs and building stakeholder alignment through a lightweight Project One-pager that captures the problem statement, objectives, success metrics, and resource requirements. Once approved at a decision gate, projects move into planning, where work is broken into shippable increments with clear acceptance criteria, estimated scope, and a prioritized backlog. Execution is managed through a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done) and supported by daily standups, weekly delivery syncs, and small, focused pull requests (≤400 lines). This iterative delivery approach ensures continuous progress and early feedback before the final release and retrospective phases.

### Roles, Responsibilities, and Communication

OctoAcme defines clear ownership across three primary roles: **Project Managers** coordinate delivery, schedules, risks, and communications; **Product Managers** own the vision, prioritize the backlog, and measure outcomes; and **Developers** implement features, write tests, and collaborate on design and quality. Communication is structured around a consistent cadence—daily standups (15 minutes) focus on progress and blockers, weekly syncs between PM and Product Manager align on status and risks, twice-weekly team standups maintain momentum, and monthly stakeholder updates provide transparency. A three-level escalation path (team → PM → Product Lead → Sponsor) ensures blockers are addressed appropriately, with emphasis on psychological safety and data-informed decisions throughout.

### Quality Assurance and Risk Management

Quality is embedded across the project lifecycle through unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. A **Definition of Done** ensures acceptance criteria are met before work is considered complete, while a **Risk Register** tracks risks by ID, impact, likelihood, mitigation plan, and owner. Risks are monitored continuously and reviewed at weekly syncs; pre-release verification includes passing CI, security scans, smoke tests in staging, and documented rollback plans. Post-deployment verification and incident playbooks ensure issues are caught quickly, with blameless retrospectives capturing learnings to drive continuous improvement through prioritized action items with clear owners and timelines.

## Key Artifacts

- **Project One-pager** — Problem statement, goals, success metrics, stakeholders, and timeline
- **Prioritized Backlog** — User stories/features with acceptance criteria and estimates
- **Definition of Done** — Shared understanding of when work is complete
- **Risk Register** — Tracking of risks, mitigation plans, and owners
- **Release Notes** — Summary of changes, migration steps, and known issues
- **Retrospective Notes** — Learnings and action items for continuous improvement

## Documentation Index

| Document | Purpose |
|----------|---------|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | Overview: principles, roles, lifecycle, and communication cadence |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Project Initiation Guide: one-pager template and decision gate |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Project Planning: backlog, estimation, and release planning |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Execution & Tracking: workflows, QA, and reporting |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release & Deployment: release types, checklists, and rollback playbook |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk Management & Communication: risk register and escalation paths |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Retrospectives: running retros and tracking action items |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Roles & Personas: responsibilities and communication patterns |

## Getting Started

- **New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for principles and roles.
- **Starting a new project?** Follow [octoacme-project-initiation.md](./octoacme-project-initiation.md) to validate the business need and get stakeholder alignment.
- **Planning a project?** Use [octoacme-project-planning.md](./octoacme-project-planning.md) to break work into shippable increments.
- **Executing a project?** Reference [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) for daily workflows and QA practices.
- **Preparing to release?** Check [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) for pre-release requirements and deployment checklists.
- **Managing risks?** See [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for risk identification and escalation.
- **Running retrospectives?** Use [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings.
- **Understanding roles?** Review [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) for role-specific responsibilities.

## Best Practices

- Keep the Project One-pager updated in your project repo
- Review the Risk Register at every weekly sync
- Define acceptance criteria before starting work
- Run retrospectives after each sprint, release, or major milestone
- Link this README from your project templates and repository root README
- Update this index when new process docs are added

## Continuous Improvement

These docs are living artifacts. If you identify gaps, inconsistencies, or improvements, please:
1. Create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Link it to the relevant process doc
3. Include rationale and suggested content

---

**Last Updated:** June 2026  
**Maintained By:** OctoAcme Project Management Community
