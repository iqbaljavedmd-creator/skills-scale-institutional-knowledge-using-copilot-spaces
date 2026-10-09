# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, iterative project management approach that emphasizes customer value, clear ownership, data-informed decisions, and psychological safety. This documentation suite provides comprehensive guidance for running projects from initiation through closeout.

## What is OctoAcme's Project Management Approach?

OctoAcme's project management methodology is built around five core phases that move work from idea to production to learning:

1. Initiation — validate business need, confirm measurable outcomes, align stakeholders, and establish the decision gate.
2. Planning — break work into shippable increments, estimate scope, identify dependencies, and define the Definition of Done.
3. Execution — build, test, and iterate through daily standups, weekly syncs, and continuous quality assurance.
4. Release & Deployment — deploy with pre-release verification, post-deploy validation, and rollback planning.
5. Retrospective & Continuous Improvement — capture learnings and feed validated improvements back into processes.

The approach emphasizes clear ownership, data-informed decisions, and psychological safety. Each project has a named Project Manager and Product Lead, and the team relies on a consistent set of artifacts—including project charters, roadmaps, backlog items with acceptance criteria, risk registers, and retrospective notes—to maintain transparency and alignment.

Quality is a continuous practice, not a final step. OctoAcme expects unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. These practices reduce risk, improve trust in delivery, and help the team learn quickly while maintaining customer value.

## Quick Links to Process Documents

### Core Framework
- [Project Management Overview](./octoacme-project-management-overview.md) — Start here for principles, roles, and key artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Understand Project Managers, Product Managers, Developers, QA, and Stakeholders

### Project Lifecycle
1. [Project Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, define success criteria
2. [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, manage dependencies, estimate scope
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery, standups, quality, and blocker escalation
4. [Release & Deployment](./octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive iterative improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register, escalation paths, stakeholder communication templates

## Key Principles

- Customer-first: Prioritize customer value and usability
- Iterative delivery: Deliver small, testable increments
- Clear ownership: Each project has a named PM and Product Lead
- Data-informed decisions: Measure impact and iterate based on evidence
- Psychological safety: Encourage feedback and learning

## How to Use This Documentation

- New to OctoAcme? Start with the Project Management Overview and Roles & Personas.
- Starting a new project? Follow the project lifecycle links in order.
- Facing a specific challenge? Navigate directly to the relevant process document.
- Contributing improvements? Use the Process Doc Update issue template in .github/ISSUE_TEMPLATE/.

## Communication Cadence

- Weekly sync: PM + Product Manager
- Twice-weekly standups: Delivery team
- Monthly updates: Stakeholders
- Ad-hoc escalations as needed

## Core Roles at a Glance

| Role | Primary Focus | Key Responsibilities |
|------|---------------|----------------------|
| Project Manager | Delivery, schedule, risk, coordination | Planning, scheduling, risk management, communication |
| Product Manager | Outcomes, customer value, prioritization | Problem definition, metrics, backlog prioritization, validation |
| Developers | Implementation, quality, design | Coding, testing, review, estimation |
| QA/Testing | Quality assurance, acceptance | Test planning, validation, acceptance criteria verification |
| Stakeholders | Input, approval, oversight | Requirements input, decisions, resource alignment |

## Project Lifecycle at a Glance

1. Initiation: problem statement, stakeholders, high-level timeline, decision gate
2. Planning: scope, resources, milestones, dependencies, backlog
3. Execution: build, test, review, iterate
4. Release: deploy, verify, announce, prepare rollback plan
5. Close & Retrospective: capture learnings and next steps

## Quality & Testing Standards

OctoAcme integrates quality throughout the lifecycle:

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Blocker Escalation Path

1. Team-level triage in daily standup
2. PM escalates to Product Lead and dependent teams
3. Sponsor-level escalation for business-impacting issues

---

Last updated: October 2026