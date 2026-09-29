# OctoAcme Project Management Docs

Welcome to OctoAcme's Project Management Documentation. This repository contains the standard project management processes used by OctoAcme for cross-functional work, from initiation through retrospective.

This README is the central entry point for the team's process documentation. It summarizes the project management approach, links to the phase-based guides, and helps teammates find the right process guidance for their role and project stage.

## Core Principles

OctoAcme operates on five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leads (PM and Product Manager)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Overview

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation** - Validate business need and align stakeholders
2. **Planning** - Break work into shippable increments
3. **Execution** - Build, test, and review iteratively
4. **Release** - Deploy to production with confidence
5. **Retrospective** - Capture learnings and improve

## OctoAcme Project Management Approach

OctoAcme's project management methodology emphasizes:

- **Clear Roles & Accountability**: Each project has a dedicated Project Manager and Product Manager with defined responsibilities.
- **Regular Communication Cadence**: Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates.
- **Risk-Driven Planning**: Active risk registers maintained throughout the project lifecycle with escalation paths defined.
- **Quality-First Execution**: Comprehensive testing strategy including unit, integration, and end-to-end smoke tests with automated CI/CD.
- **Structured Artifacts**: Key deliverables including Project Charter, one-pagers, release plans, and retrospective notes create transparency and accountability.
- **Continuous Improvement**: Post-project and post-incident retrospectives drive actionable improvements tracked to completion.

## Documentation Guide

### Start Here

- **[Project Management Overview](./octoacme-project-management-overview.md)** - A concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle.

### By Project Phase

- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Use when a new project idea or feature proposal is ready to be explored.
- **[Project Planning](./octoacme-project-planning.md)** - Use after a project is approved to move into planning.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Use during active development to manage day-to-day execution and tracking.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Use throughout the project to identify and manage risks and stakeholder communication.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Use when preparing for production release.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Use after each sprint, release, or milestone.

### By Role

- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Detailed descriptions of core roles including Project Manager, Product Manager, Developers, and QA/Testing.

## Key Artifacts at a Glance

| Artifact | Created During | Purpose |
|----------|----------------|---------|
| **Project Charter / One-pager** | Initiation | Single source of truth for goals, stakeholders, timeline, and risks |
| **Backlog with Acceptance Criteria** | Planning | Prioritized list of work items with clear success definitions |
| **Definition of Done (DoD)** | Planning | Shared agreement on what "done" means |
| **Risk Register** | Planning, ongoing | Tracks risk impact, likelihood, owner, and mitigation |
| **Project Board** | Execution | Visual workflow tracking across backlog, review, QA, and done states |
| **Release Notes** | Release | Summary of changes, migration steps, and known issues |
| **Retrospective Notes** | Retrospective | What went well, improvements, and action items with owners |

## Communication Cadence

- **Daily**: Team standups (15 min) focused on progress, blockers, and dependencies
- **Weekly**: PM + Product Manager sync for alignment on priorities and risks
- **Twice weekly** (or as agreed): Delivery team standups
- **Monthly**: Stakeholder updates on progress and business impact
- **Ad-hoc**: Escalations for blockers and critical issues

## Quick Reference: Escalation Paths

- **General blockers**: Team → PM → Product Lead → Sponsor
- **Security incidents**: Notify Security on-call and follow the incident runbook
- **Quality/defect issues**: QA triage → Team → PM escalation if release impact is significant

## Getting Started

**New to OctoAcme?**
1. Read the [Project Management Overview](./octoacme-project-management-overview.md)
2. Find your role in [Roles and Personas](./octoacme-roles-and-personas.md)
3. Navigate to the relevant phase-specific guide for your project stage

**Joining an Active Project?**
1. Review the Project One-pager in the project repo
2. Check the project board for current status and your assignments
3. Refer to the phase documentation while working on deliverables

**Contributing to Process Documentation?**
- Submit updates using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- Keep process docs current and aligned with team practices

---

**Last Updated**: September 29, 2026
