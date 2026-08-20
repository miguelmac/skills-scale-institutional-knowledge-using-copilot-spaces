# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This directory contains comprehensive guides and frameworks for running projects at OctoAcme.

## About OctoAcme Project Management

OctoAcme follows a structured, customer-first approach to project delivery with clear phases, defined roles, and iterative delivery practices. Our framework emphasizes:

- **Clear ownership** with defined Project Manager (PM) and Product Manager (PdM) roles
- **Iterative delivery** of small, testable increments
- **Data-informed decisions** based on measurable success metrics
- **Psychological safety** to encourage feedback and learning
- **Transparent communication** across teams and stakeholders

## Core Project Lifecycle

Every OctoAcme project follows five key phases:

1. **Initiation** — Define the problem, align stakeholders, establish success criteria, and make a go/no-go decision
2. **Planning** — Break work into shippable increments with acceptance criteria, identify risks and dependencies, and create release timelines
3. **Execution** — Build, test, review, and iterate with regular standups, weekly syncs using GitHub Projects board (Backlog, Ready, In Progress, In Review, QA, Done), and embedded quality assurance
4. **Release** — Deploy features to production with standardized checklists, smoke tests, and documented rollback procedures
5. **Retrospective** — Capture learnings and convert them into continuous improvements with documented action items

## Key Workflows and Practices

### Communication and Alignment
OctoAcme maintains regular cadences including:
- **Twice-weekly standups** focused on progress, blockers, and dependencies
- **Weekly PM and Product Lead syncs** to align on priorities and risks
- **Monthly stakeholder updates** with status and strategic decisions
- **Ad-hoc escalations** using a three-level path: team-level → PM → Product Lead → Sponsor

### Quality and Testing
- Unit tests for new logic, integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI/CD pipelines
- Manual QA for feature acceptance when needed
- Small pull requests (≤400 lines) requiring at least one approval before merge

### Risk Management
- Maintain a Risk Register tracking ID, description, impact, likelihood, owner, and mitigation status
- Review risks continuously during weekly syncs
- Mark cross-team dependencies in the project board and escalate as needed
- Standard status update template covering progress, next steps, risks/blockers, and decisions needed

## Process Documents

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to roles, core artifacts, and lifecycle overview

### Project Phases
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business needs, align stakeholders, and authorize work
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into actionable increments, creating backlogs with acceptance criteria, and defining release timelines
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Daily standups, delivery workflow, progress tracking, and team rhythm
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release process, deployment checklists, and rollback procedures

### Critical Enablers
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk registers, escalation paths, stakeholder communication templates, and incident playbooks
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Post-project learnings, action item tracking, and continuous improvement culture
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of Developers, Product Managers, Project Managers, and other key roles with responsibilities and communication patterns

## How to Use These Docs

- **For new projects:** Start with [Project Initiation Guide](./octoacme-project-initiation.md), then [Project Planning](./octoacme-project-planning.md)
- **For ongoing execution:** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) regularly
- **For releases:** Follow [Release & Deployment Guide](./octoacme-release-and-deployment.md) procedures and checklists
- **For team clarity:** Share the [Roles & Personas](./octoacme-roles-and-personas.md) doc to align on responsibilities and communication patterns
- **For continuous improvement:** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) after each sprint or milestone

## Contributing Updates

To suggest changes or additions to these process docs, open an issue using the **"Add Content to Project Management Process Docs"** template in `.github/ISSUE_TEMPLATE/`.

This process ensures that:
- Content aligns with existing process docs
- Updates improve clarity or close documented gaps
- Proposed content is reviewed with stakeholders when needed

## Purpose and Value

This documentation centralizes scattered project management knowledge into searchable, versioned artifacts. By making these processes accessible:

- New team members can quickly understand how OctoAcme runs projects
- All team members have equal access to processes, decisions, and rationale
- Processes are validated, refined, and continuously improved collaboratively
- Execution is consistent, repeatable, and predictable
- Onboarding is accelerated and single-person dependency risk is reduced
