# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation hub. This folder contains standardized guides and templates used across all OctoAcme projects to ensure consistent delivery, clear communication, and continuous improvement.

## Quick Start

New to OctoAcme projects? Start here:
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, roles, and key artifacts
2. Explore the [Personas Guide](./octoacme-roles-and-personas.md) to understand team roles and responsibilities

## OctoAcme Project Management Overview

OctoAcme operates on a structured lifecycle that moves projects through five distinct phases: initiation, planning, execution, release, and retrospective. The initiation phase validates business needs and stakeholder alignment through a lightweight Project One-pager, setting clear success metrics and identifying key resources before moving forward. Once approved, the planning phase breaks work into actionable increments with a prioritized backlog, defined acceptance criteria, and a release timeline. This deliberate gating approach ensures that only well-aligned initiatives advance to execution, reducing waste and misalignment downstream.

Execution and tracking form the heart of OctoAcme's delivery rhythm, anchored by daily standups, weekly delivery syncs, and structured sprint planning. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforce small pull requests (≤400 lines) with automated CI testing and at least one approval before merge. Quality is embedded throughout—unit tests, integration tests, end-to-end smoke tests, and security scanning run in CI, with manual QA applied to critical features. A clear blocker escalation framework ensures issues are surfaced and resolved quickly, moving from team-level triage to PM escalation to sponsor involvement as needed.

Communication and risk management are centralized through a weekly cadence involving the Project Manager and Product Manager, stakeholder updates at least monthly, and a comprehensive Risk Register that tracks impact, likelihood, mitigation plans, and status. OctoAcme defines clear roles—Project Managers own delivery coordination and timelines, Product Managers drive prioritization and success metrics, Developers implement features and collaborate on design, and stakeholders provide input and approvals. Release management is standardized with pre-release checklists, staged deployments to production, and documented rollback procedures. Finally, retrospectives after each sprint or release capture learnings and convert them into tracked action items, embedding continuous improvement into the project lifecycle.

## OctoAcme Project Lifecycle

OctoAcme projects follow a five-phase lifecycle. Each phase has dedicated documentation:

### 1. Initiation
**Document:** [Project Initiation Guide](./octoacme-project-initiation.md)

Validate and authorize work, align stakeholders, and create a lightweight plan. Deliverables include a Project One-pager, stakeholder list, and initial risk assessment.

### 2. Planning
**Document:** [Project Planning](./octoacme-project-planning.md)

Turn an approved initiative into an actionable plan and backlog. Establish scope, resources, milestones, and Definition of Done.

### 3. Execution
**Document:** [Execution & Tracking](./octoacme-execution-and-tracking.md)

Manage day-to-day work, track progress, maintain quality, and escalate blockers. Follow team rhythms, PR workflows, and quality standards.

### 4. Release
**Document:** [Release & Deployment Guide](./octoacme-release-and-deployment.md)

Standardize how OctoAcme releases features to production. Covers pre-release requirements, deployment checklists, and rollback procedures.

### 5. Close & Learn
**Document:** [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

Capture learnings after each sprint, release, or milestone and convert them into actionable improvements.

## Cross-Cutting Processes

### Risk Management & Communication
**Document:** [Risk Management & Communication](./octoacme-risks-and-communication.md)

Manage risks and dependencies throughout the project lifecycle. Includes risk register templates, escalation paths, and stakeholder communication plans.

## Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Key Artifacts

Across all phases, OctoAcme uses standardized artifacts:
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Need Help?

Each document includes templates, checklists, and examples. See a gap or want to improve these docs? Open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
