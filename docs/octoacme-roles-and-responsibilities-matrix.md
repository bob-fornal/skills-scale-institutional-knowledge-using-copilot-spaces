# OctoAcme — Roles & Responsibilities Matrix

This document provides a lightweight RACI-style matrix mapping core lifecycle activities to roles. Use it to quickly identify who is **R**esponsible, **A**ccountable, **C**onsulted, or **I**nformed for key activities across the project lifecycle.

> **R** = Responsible (does the work) | **A** = Accountable (owns the outcome) | **C** = Consulted (provides input) | **I** = Informed (kept in the loop)

---

## How to use this matrix

- **Responsible (R)**: The role(s) that perform the activity. More than one role can share responsibility.
- **Accountable (A)**: The single role that is ultimately answerable for the activity's completion and quality. Only one role should be accountable per activity.
- **Consulted (C)**: Roles whose input or expertise is sought before decisions are made or work is completed.
- **Informed (I)**: Roles that need to be kept up to date on progress or outcomes but do not actively contribute.

Refer to [Roles & Personas](octoacme-roles-and-personas.md) for full descriptions of each role.

---

## Initiation

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Release Manager | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Draft Project One-pager | R | A | C | C | — | C | — | — | I |
| Assemble stakeholder list | A | R | — | — | — | C | — | — | I |
| Capture initial risk list | A | C | C | — | C | R | — | — | I |
| Define success metrics | C | A | — | C | — | R | — | — | C |
| Approve go/no-go to Planning | A | C | — | — | — | — | — | — | C |

---

## Planning

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Release Manager | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Prioritize and refine backlog | C | A | C | C | — | R | — | C | C |
| Estimate effort | C | C | R | C | C | C | — | C | — |
| Define Definition of Done | A | C | R | C | C | C | C | R | — |
| Identify dependencies | A | C | R | C | R | C | C | C | I |
| Draft release plan and milestones | A | C | C | — | C | — | R | C | I |
| Draft initial test plan | C | — | C | — | — | C | — | A | — |

---

## Execution & Tracking

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Release Manager | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Run daily standups | A | — | R | R | R | R | — | R | — |
| Maintain project board hygiene | A | — | R | R | R | R | — | R | — |
| Follow PR workflow (branch, review, merge) | — | — | A | C | C | — | — | C | — |
| Escalate blockers | A | C | R | R | R | C | — | R | I |
| Track velocity and metrics | A | C | R | — | — | — | — | C | I |

---

## Risk & Communication

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Release Manager | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Maintain risk register | A | C | C | — | C | C | C | C | I |
| Send weekly status update | A | C | — | — | — | — | I | — | I |
| Manage incident communications | C | C | C | — | R | — | A | C | I |
| Coordinate post-incident retrospective | A | C | R | — | R | — | C | C | I |

---

## Release & Deployment

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Release Manager | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Draft release notes | C | C | R | — | — | C | A | C | I |
| Execute deployment checklist | C | — | C | — | R | — | A | C | I |
| Run staging smoke tests | — | — | C | — | R | — | C | A | — |
| Approve go/no-go for production | C | C | — | — | C | — | A | C | C |
| Communicate release to stakeholders | C | R | — | — | — | — | A | — | I |
| Execute rollback plan (if needed) | C | I | C | — | R | — | A | C | I |

---

## Retrospective & Continuous Improvement

| Activity | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Release Manager | QA / Testing | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Facilitate retrospective | A | C | R | R | R | R | R | R | — |
| Capture action items | A | — | R | R | R | R | R | R | — |
| Track and close action items | A | C | R | C | C | C | C | C | I |
| Share retrospective summary | A | C | I | — | — | — | — | — | I |

---

*For full role descriptions, see [Roles & Personas](octoacme-roles-and-personas.md). For lifecycle guidance, see the [Project Management Overview](octoacme-project-management-overview.md).*
