# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains the official process documents for OctoAcme's project management approach — covering everything from initial discovery through release, retrospective, and continuous improvement. Whether you're onboarding to the team, refreshing your knowledge of a specific phase, or looking for templates and checklists, this is your starting point.

## Overview of OctoAcme Project Management Processes

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle that emphasizes iterative delivery, clear ownership, and measurable outcomes. Every initiative starts with an **Initiation** phase: the team validates the business need, produces a **Project One-pager** (problem statement, SMART objective, success metrics), assembles a stakeholder list, and captures an initial risk list and rough timeline. A formal decision gate confirms that success metrics, stakeholder alignment, and team availability are in place before deeper planning begins.

**Planning** translates the approved initiative into an executable backlog. Teams run a kickoff session, create prioritized work items with acceptance criteria, estimate effort, define a **Definition of Done**, and map cross-team dependencies. Risks are captured in a **Risk Register** — tracking impact, likelihood, owner, mitigation, and status — and revisited throughout the project. Cross-team dependencies are explicitly flagged and escalated through the team cadence when they become blockers.

**Execution & Tracking** runs in short, time-boxed iterations on a project board (e.g., GitHub Projects) using the flow: **Backlog → Ready → In Progress → In Review → QA → Done**. The team meets daily to surface blockers, holds weekly delivery syncs to review progress and risks, and demos at the end of each sprint or milestone. Pull requests are kept small when practical, must reference the related issue and acceptance criteria, and require passing CI checks (tests, linting, security scanning) plus at least one peer approval before merging.

Quality assurance and release practices are integrated throughout delivery rather than treated as a final gate. New logic carries unit-test coverage; integration and end-to-end smoke tests cover critical flows; and manual QA is used for feature acceptance where needed. Releases follow a standardized checklist — verifying acceptance criteria, CI/security scans, release notes, and rollback plans — before promoting through staging to production, followed by post-deploy verification and stakeholder communication. Five key personas drive this lifecycle: **Project Manager** (schedules, risks, communications), **Product Manager/Product Lead** (outcomes, backlog), **Developers** (implementation, reviews), **QA/Testing** (validation), and **Stakeholders** (inputs, approvals). Shared artifacts and consistent communication cadences — daily standups, weekly syncs, monthly stakeholder updates — serve as the single source of truth. The lifecycle closes with structured retrospectives that capture what worked, what didn't, and a small set of owned action items fed back into the backlog, reinforcing continuous improvement.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
