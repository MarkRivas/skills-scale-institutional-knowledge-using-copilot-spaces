# OctoAcme Project Management Docs

Welcome to OctoAcme's Project Management Documentation. This repository contains standardized processes, templates, and guidance for running cross-functional projects from initiation through retrospective.

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

- **Clear Roles & Accountability**: Each project has a dedicated Project Manager and Product Manager with defined responsibilities
- **Regular Communication Cadence**: Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates
- **Risk-Driven Planning**: Active risk registers maintained throughout the project lifecycle with escalation paths defined
- **Quality-First Execution**: Comprehensive testing strategy including unit, integration, and end-to-end smoke tests with automated CI/CD
- **Structured Artifacts**: Key deliverables including Project Charter, One-pagers, Release Plans, and Retrospective notes create transparency and accountability
- **Continuous Improvement**: Post-project and post-incident retrospectives drive actionable improvements tracked to completion

## Documentation Guide

### Start Here

- **[Project Management Overview](./octoacme-project-management-overview.md)** - A concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle. Start here if you're new to the team.

### By Project Phase

Navigate to the documentation for your current project phase:

- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Use when a new project idea or feature proposal is ready to be explored. Covers business validation, stakeholder alignment, and the go/no-go decision gate.

- **[Project Planning](./octoacme-project-planning.md)** - Use after a project is approved to move into planning. Covers backlog creation, estimation, Definition of Done, dependency mapping, and release planning.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Use during active development. Covers team rhythms (standups, syncs, demos), workflow management with project boards, quality standards, and blocker escalation.

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Use throughout the project. Covers risk register maintenance, risk lifecycle, stakeholder communication strategies, and escalation paths.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Use when preparing for production release. Covers release types, pre-release requirements, deployment checklist, rollback procedures, and release notes.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Use after each sprint, release, or milestone. Covers retrospective structure, action item tracking, and building a culture of continuous improvement.

### By Role

Find role-specific guidance and understand key responsibilities:

- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Detailed descriptions of core roles including Project Manager, Product Manager, Developers, and QA/Testing. Includes responsibilities, goals, and typical communication patterns for each role.

## Key Artifacts at a Glance

| Artifact | Created During | Purpose |
|----------|----------------|---------|
| **Project Charter / One-pager** | Initiation | Single source of truth for problem statement, goals, success metrics, stakeholders, timeline, and risks |
| **Backlog with Acceptance Criteria** | Planning | Prioritized list of work items with clear success definitions |
| **Definition of Done (DoD)** | Planning | Shared agreement on what "done" means for each work item |
| **Risk Register** | Planning, ongoing | Catalog of identified risks with impact, likelihood, owner, and mitigation plans |
| **Project Board** | Execution | Visual workflow tracking (Backlog → Ready → In Progress → In Review → QA → Done) |
| **Weekly Status Report** | Execution, ongoing | Communication of progress, blockers, risks, and decisions needed |
| **Release Notes** | Release | Summary of changes, migration steps, known issues, and rollback plan |
| **Retrospective Notes** | Retrospective | What went well, improvements, and action items with owners and due dates |

## Communication Cadence

- **Daily**: Team standups (15 min) - focus on progress, blockers, and dependencies
- **Weekly**: PM + Product Manager sync - alignment on priorities and risks
- **Twice Weekly** (or as agreed): Delivery team standups
- **Monthly**: Stakeholder updates on progress and business impact
- **Ad-hoc**: Escalations for blockers and critical issues

## Quick Reference: Escalation Paths

For different issue types, follow these escalation paths:

- **General Blockers**: Team → PM → Product Lead → Sponsor
- **Security Incidents**: Immediate notification to Security on-call, follow security incident runbook
- **Quality/Defect Issues**: QA triage → Team → PM escalation if impacting release

## Getting Started

**New to OctoAcme?**
1. Read the [Project Management Overview](./octoacme-project-management-overview.md)
2. Find your role in [Roles and Personas](./octoacme-roles-and-personas.md)
3. Navigate to the relevant project phase documentation above

**Joining an Active Project?**
1. Review the Project One-pager (available in your project repo)
2. Check the project board for current status and your assignments
3. Refer to the phase-specific documentation as you execute your work

**Contributing to Process Documentation?**
- Submit updates using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
- All process documentation is version-controlled and tracked for traceability

---

**Last Updated**: September 29, 2026  
**Maintained By**: OctoAcme Project Management Team
