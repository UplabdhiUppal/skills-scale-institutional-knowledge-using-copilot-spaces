# OctoAcme Project Management Docs

This directory contains the OctoAcme project management process documents, designed to centralize scattered project management knowledge and enable consistent, repeatable project execution across the organization.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management centered on customer value, iterative delivery, and clear ownership. The methodology spans five core phases:

- **Initiation**: Problems are validated and stakeholders are aligned around success metrics through a lightweight one-pager process
- **Planning**: Work is broken into shippable increments with defined acceptance criteria, dependencies, and a Definition of Done
- **Execution**: Managed through daily standups, project boards, and small, reviewable pull requests with CI and testing
- **Release**: Deployments follow a rigorous checklist to minimize risk, with pre-release requirements and rollback plans
- **Close & Retrospective**: Learnings drive continuous improvement and inform future project planning

### Key Organizational Elements

OctoAcme's organizational model emphasizes clear role definition and cross-functional collaboration:

- **Project Managers** coordinate delivery activities, manage schedules, risks, and stakeholder communications
- **Product Managers** define what should be built and prioritize the backlog based on customer and business value
- **Developers** implement features with high quality standards and contribute to planning and risk identification
- **QA/Testing teams** validate acceptance criteria and quality gates

Communication is structured around a well-established cadence: daily standups, weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. This ensures decisions are made with full context and risks are surfaced early.

### Quality & Risk Management

Quality and risk management are embedded throughout OctoAcme's execution framework. The process mandates:

- Unit and integration testing for new logic
- Smoke tests for critical flows before release
- Security scanning in CI pipelines
- Small PRs (≤400 lines when possible) with at least one approval before merging

Risks are identified during planning and continuously monitored through a formal Risk Register. Escalation follows three levels: team-level triage, PM escalation to Product Leads, and sponsor-level escalation for business-impacting issues.

---

## Process Documents

Browse the detailed process documentation below:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to roles, principles, artifacts, and the high-level project lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan and backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, workflows, and quality standards
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardized approach to releasing features with reduced risk
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and converting them into actionable improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (PM, Product, Developers, QA) and responsibilities

---

## How to Use These Docs

- **For new projects**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the lifecycle, then follow the [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md) guides
- **For ongoing execution**: Reference the [Execution & Tracking](octoacme-execution-and-tracking.md) guide and check the [Risk Management](octoacme-risks-and-communication.md) doc for escalation paths
- **For releases**: Use the [Release & Deployment](octoacme-release-and-deployment.md) checklist
- **For process improvements**: Follow the [Retrospective](octoacme-retrospective-and-continuous-improvement.md) guide
- **For Copilot Spaces**: Add these docs as context to enable AI-assisted guidance aligned with OctoAcme processes

---

## Contributing to Process Docs

To propose updates or additions to these process documents, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template. This ensures changes are reviewed and aligned with the broader OctoAcme approach.
