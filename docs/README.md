# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This README summarizes our approach to delivering cross-functional projects and links to every detailed process guide so teammates can quickly understand and navigate our practices.

## Overview

OctoAcme runs cross-functional projects with a lightweight, repeatable lifecycle: **Initiation → Planning → Execution/Tracking → Release/Deployment → Close/Retrospective**. During initiation the team validates the business need and aligns stakeholders around a **Project One-pager** (problem statement, SMART objectives, success metrics, high-level timeline, and an initial risk list). Projects move forward once success metrics are clear, priority is agreed, and team availability is confirmed—then the team establishes core artifacts such as a repository and project board that serve as the single source of truth for the entire delivery.

During planning, OctoAcme turns an approved initiative into a deliverable roadmap by running a kickoff, building a **prioritized backlog** with clear acceptance criteria and a **Definition of Done**, estimating work (T‑shirt sizing or story points), and explicitly mapping dependencies and integration points. Risks are captured in a **Risk Register** (impact, likelihood, owner, mitigation, status) and reviewed continuously. Execution emphasizes visible workflow state using a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a consistent cadence: **daily standups** for blockers and dependencies, a **weekly delivery sync** for progress and risks, and demos/reviews at sprint or milestone boundaries. Five core personas drive delivery: **Project Manager** (coordination, schedule, risk, communications), **Product Manager** (outcomes, prioritization, success metrics), **Developers** (implementation, reviews, technical risk), **QA/Testing** (acceptance validation), and **Stakeholders** (inputs and approvals). Risk escalation is tiered—team triage first, then PM escalation to product or dependent teams, then sponsor-level escalation for business impact.

Quality and release practices are integrated throughout. OctoAcme favors **small PRs** linked to issues and acceptance criteria, with CI (tests, linting, security scanning) passing and at least one approval required before merge. Testing is layered—unit tests for new logic, integration and end-to-end smoke tests for critical flows, and manual QA when needed for acceptance. Releases follow a standardized checklist (release notes, rollback plan, staging verification, post-deploy smoke tests, stakeholder announcement). Every sprint, release, or milestone ends with a **retrospective** that produces a small set of owned, time-bound action items tracked as normal backlog work to drive continuous improvement.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and the high-level lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | Problem statement, stakeholder alignment, and project charter |
| [Project Planning](octoacme-project-planning.md) | Backlog, estimation, Definition of Done, and dependency mapping |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint cadence, project board, standups, and progress tracking |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, escalation tiers, and stakeholder communications |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, staging verification, and deployment practices |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action items, and improvement tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
