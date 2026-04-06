# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management documentation! This README serves as your starting point for understanding our processes, accessing key guides, and navigating our lightweight, practical approach to project delivery.

## Project Management Processes Summary

OctoAcme operates a structured, lifecycle-based project management approach designed to deliver customer value through iterative increments while maintaining clear ownership and accountability. The framework consists of five core phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (daily standups and continuous delivery), **Release** (standardized deployment with rollback plans), and **Close & Retrospective** (capturing learnings for continuous improvement). This end-to-end lifecycle is underpinned by three guiding principles: customer-first prioritization, iterative delivery of testable increments, and data-informed decision-making supported by clear metrics and dashboards.

The organization employs a well-defined role structure with distinct responsibilities to ensure smooth coordination and accountability. **Project Managers** orchestrate schedules, risks, and communications—maintaining project plans, managing dependencies, and facilitating alignment across stakeholders. **Product Managers** define what should be built by owning the product vision, prioritizing the backlog, and measuring outcomes through success metrics. **Developers** implement features to meet acceptance criteria while writing tests and participating in design reviews. **QA/Testing** teams validate quality and acceptance criteria. This clear delineation of roles, combined with named Project and Product Leads per project, eliminates ambiguity and ensures psychological safety for team collaboration.

Communication and risk management are woven throughout OctoAcme's execution model. The team maintains a regular cadence—daily standups (15 min, focused on progress and blockers), weekly PM-PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates—ensuring transparency across organizational levels. A formal **Risk Register** captures identified risks with impact, likelihood, ownership, and mitigation plans, reviewed weekly during syncs. An escalation hierarchy (Team → PM → Product Lead → Sponsor) manages blockers efficiently, with special protocols for security incidents. Weekly status communications follow a consistent template (Progress, Next Steps, Risks & Blockers, Ask/Decisions Needed), and a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) provides a single source of truth for work status.

Quality and continuous improvement are embedded as operating standards rather than afterthoughts. Before deployment, teams complete comprehensive pre-release verification including passing CI/security scans, drafted release notes, and prepared smoke tests. The execution checklist mandates unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. Post-release, a blameless retrospective captures learnings—what went well, what could improve, and prioritized action items tracked with clear owners and due dates. This combination of rigorous quality gates, regular retrospectives, and structured action-item tracking creates a culture of measured, iterative improvement while reducing single-person dependency and accelerating team onboarding.

## Core Roles

- **Project Manager (PM):** Coordinates delivery activities, manages schedules, risks, dependencies, and stakeholder communication. Facilitates meetings and ensures consistent project documentation.
- **Product Manager (PdM):** Owns product vision, defines outcomes, prioritizes the backlog, and measures success via metrics and stakeholder feedback.
- **Developers:** Build, test, and deliver features according to acceptance criteria and quality standards. Contribute to code reviews, technical designs, and estimations.
- **QA/Testing:** Validate features against acceptance criteria, ensure release quality, design and run tests, and participate in pre-release checks.
- **Stakeholders:** Provide input, feedback, and approvals through all phases. May include customers, sponsors, and other business partners.

## Documentation Index

Use these guides to dive deeper into specific aspects of OctoAcme's project management approach:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to principles, roles, artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate, authorize, and kickoff new work
- **[Project Planning Guide](octoacme-project-planning.md)** — Breaking work into shippable increments and creating actionable backlogs
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, team rhythm, quality standards, and reporting
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, stakeholder communication, and escalation paths
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release processes, checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and driving iterative improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities for Project Managers, Product Managers, Developers, and QA

> **Tip:** Keep this list up to date as new process docs are added to the docs folder.

## Quick Start

**New to OctoAcme?** Start here:

1. Read the [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles and roles
2. If you're starting a new project, review the [Project Initiation Guide](octoacme-project-initiation.md)
3. For day-to-day execution questions, check [Execution & Tracking](octoacme-execution-and-tracking.md)
4. When in doubt, escalate using the paths outlined in [Risk Management & Communication](octoacme-risks-and-communication.md)

## Contributing to These Docs

To propose updates or new content:

1. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
2. Describe the gap or improvement needed
3. Propose content and align with stakeholders
4. Submit a pull request with changes

These living documents evolve based on team feedback and continuous improvement. We appreciate your contributions!
