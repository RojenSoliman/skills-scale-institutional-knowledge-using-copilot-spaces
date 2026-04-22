# OctoAcme Project Management Docs Overview

Welcome! This README provides quick links and a brief summary of OctoAcme's project management processes. Whether you're onboarding or looking for a specific guide, start here to navigate the documentation quickly.

## About OctoAcme Project Management

OctoAcme's project management approach is designed to be lightweight, repeatable, and easy for cross-functional teams to adopt. Work follows a clear lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. During initiation, teams validate the business need, define success criteria, identify stakeholders, and decide whether to proceed. Planning turns the approved idea into an actionable backlog with acceptance criteria, estimates, a Definition of Done, and an initial QA/testing approach—while also capturing early risks and dependencies.

Ownership is explicit and role-driven. A **Project Manager (PM)** coordinates delivery logistics, schedules, risks, and stakeholder communications; a **Product Manager (PdM)** defines outcomes, success metrics, and backlog priorities; **Developers** implement and test increments while contributing to estimation and technical risk mitigation; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide inputs and approvals. These personas reduce ambiguity by making responsibilities and expectations consistent across projects.

Execution emphasizes cadence, transparency, and incremental delivery. Teams use a project board (columns: **Backlog → Ready → In Progress → In Review → QA → Done**) and keep work moving through small pull requests linked to issues. The team rhythm typically includes short daily standups, a weekly delivery sync, and demos at the end of each sprint or milestone. Blockers are escalated through a defined path—from team triage to PM escalation and, if needed, sponsor-level escalation for business-impacting issues. Communication practices favor a single source of truth (the project board and documents here) with regular written status updates to stakeholders.

Quality assurance is built into both the development workflow and the release process. New logic includes unit tests; integration and end-to-end smoke tests cover critical flows alongside CI automation for tests, linting, and security scanning. Releases follow pre-release requirements (acceptance criteria met, CI passing, release notes, rollback plan, smoke tests) and a deployment checklist covering staging verification, production rollout, post-deploy checks, and stakeholder announcements. After sprints, milestones, or incidents, OctoAcme runs retrospectives to capture what worked, what didn't, and a small set of owned action items tracked like any other backlog work to drive continuous improvement.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level overview of OctoAcme's end-to-end project management philosophy and lifecycle |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps and templates for validating and kicking off a new project |
| [Project Planning](./octoacme-project-planning.md) | Backlog setup, estimation, Definition of Done, and risk capture |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Board management, standups, delivery syncs, and escalation paths |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk registers, communication cadences, and status update practices |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, rollback, and post-deploy validation |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and improvement practices |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Definitions and responsibilities for each role on an OctoAcme project team |

---

All content should be kept up to date to reflect current best practices and team learnings. For questions or suggested updates, open an issue or pull request in this repository.
