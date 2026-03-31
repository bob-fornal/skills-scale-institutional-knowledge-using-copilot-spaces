# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains the official process documents for OctoAcme's project management approach — covering everything from initial discovery through release, retrospective, and continuous improvement. Whether you're onboarding to the team, refreshing your knowledge of a specific phase, or looking for templates and checklists, this is your starting point.

## Overview of OctoAcme Project Management Processes

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle that emphasizes iterative delivery, clear ownership, and measurable outcomes. Work begins with **Initiation**, where teams validate the business need and define success through a **Project One-pager** (problem statement, SMART objective, and success metrics), a stakeholder list, an initial risk list, and a rough timeline. A formal decision gate ensures that success metrics, stakeholder alignment, and team availability are confirmed before deeper planning begins. From there, **Planning** turns the initiative into an executable backlog: teams run a kickoff, create prioritized work items with acceptance criteria, estimate effort, define a **Definition of Done**, and map cross-team dependencies. Risks are captured in a **Risk Register** (impact, likelihood, owner, mitigation, status) and revisited at each planning cycle.

During **Execution & Tracking**, the team works in short, time-boxed iterations tracked on a project board (e.g., GitHub Projects) with a flow of **Backlog → Ready → In Progress → In Review → QA → Done**. The team rhythm includes daily standups for surfacing blockers, weekly delivery syncs to review progress and risks, and end-of-sprint demos. Pull requests are kept small when practical, must include issue links and acceptance criteria, and require passing CI checks (tests, linting, security scanning) plus at least one peer approval before merging. Blockers follow a clear escalation path from team triage, to PM and Product Lead coordination, and up to sponsor-level escalation for business-impacting issues.

Quality assurance and release practices are integrated throughout delivery rather than treated as a final gate. New logic is expected to have unit test coverage, with integration and end-to-end smoke tests for critical flows; manual QA is used for feature acceptance where appropriate. Releases follow a standardized checklist: verify acceptance criteria are met, confirm CI and security scans pass, prepare release notes and rollback plans, deploy to staging with smoke tests, then promote to production followed by post-deploy verification and stakeholder communication. Across roles — **Project Manager**, **Product Manager/Product Lead**, **Developers**, **QA/Testing**, and **Stakeholders** — OctoAcme maintains consistent communication cadences (daily standups, weekly syncs, monthly stakeholder updates) and uses shared artifacts as a single source of truth. The lifecycle closes with structured retrospectives that capture what worked, what didn't, and a small set of owned action items tracked back in the backlog, reinforcing a culture of continuous improvement.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
