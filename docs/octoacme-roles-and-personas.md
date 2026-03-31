# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers ensure the product is usable, accessible, and aligned with user needs. They bridge the gap between customer insights and technical implementation by producing research-backed designs.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns and design system guidelines
- Collaborate on acceptance criteria to confirm usability requirements are captured
- Iterate on designs based on user and stakeholder feedback

### Goals
- Deliver intuitive, accessible experiences that satisfy user needs
- Reduce rework caused by unclear or incorrect UX assumptions
- Maintain consistency across the product through shared design patterns

### Typical Communication
- Design reviews and critiques with Developers and Product Managers
- Usability testing reports shared with the broader team
- Annotated mockups and prototypes in design tools (e.g., Figma)
- Participation in sprint planning and backlog refinement

### How they interact with existing roles
- **Product Managers**: Partner on defining user problems, validating designs against success metrics, and incorporating user research into prioritization decisions.
- **Project Managers**: Align on design milestones and flag dependencies that could affect delivery timelines.
- **Developers**: Provide annotated specs and prototypes; participate in technical feasibility discussions; review implemented UI for fidelity.
- **QA/Testing**: Collaborate on acceptance criteria that include usability and accessibility requirements; support exploratory testing of user flows.
- **Stakeholders**: Present design concepts and research findings; incorporate feedback before implementation begins.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build, operate, and maintain the infrastructure and automation pipelines that enable teams to deliver software reliably and at pace. They own CI/CD, environment management, and production observability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration
- Implement monitoring, alerting, and observability tooling
- Respond to and resolve production incidents and infrastructure issues
- Enforce security and compliance standards in the delivery pipeline
- Support Developers with local environment setup and debugging

### Goals
- Maximize deployment frequency while minimizing failure rate
- Ensure production stability and fast mean time to recovery (MTTR)
- Automate repetitive operational tasks to reduce toil

### Typical Communication
- Coordination with Developers during PR review for environment or pipeline concerns
- Incident retrospectives and post-mortems
- Release coordination meetings with Project Managers and Release Managers
- Infrastructure change notifications to the team

### How they interact with existing roles
- **Product Managers**: Provide input on infrastructure constraints that may affect roadmap feasibility or release timelines.
- **Project Managers**: Coordinate on release scheduling and communicate infrastructure risks or changes that affect delivery milestones.
- **Developers**: Review and advise on build configurations, containerization, and deployment scripts; provide local development support.
- **QA/Testing**: Provision and maintain test environments; ensure CI pipelines include automated test stages.
- **Stakeholders**: Communicate planned maintenance windows and infrastructure changes that may affect service availability.

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical delivery by gathering and documenting requirements, modeling processes, and facilitating shared understanding between stakeholders and the delivery team.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Model current and future-state processes (e.g., workflows, data flows)
- Facilitate workshops and requirements sessions with stakeholders
- Support backlog refinement by translating business needs into well-scoped stories
- Identify gaps, ambiguities, and conflicts in requirements early
- Maintain traceability between business goals and delivered features

### Goals
- Ensure the delivered solution solves the right business problem
- Reduce rework caused by misunderstood or missing requirements
- Accelerate stakeholder alignment through clear documentation

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written requirements specifications, process diagrams, and user stories
- Backlog refinement sessions with Product Managers and Developers
- Regular check-ins with Project Managers on scope changes and dependencies

### How they interact with existing roles
- **Product Managers**: Collaborate on translating strategy and user needs into detailed, actionable requirements; support prioritization with impact analysis.
- **Project Managers**: Communicate scope changes, dependency discoveries, and requirement risks that affect timelines or effort estimates.
- **Developers**: Clarify requirements, answer questions during implementation, and validate that delivered features meet stated business needs.
- **QA/Testing**: Provide requirements documentation as the basis for test planning; participate in acceptance testing to confirm business outcomes are met.
- **Stakeholders**: Act as a primary point of contact for requirements gathering, validation, and sign-off.

---

## Release Manager

### Role Summary
Release Managers coordinate and govern the end-to-end release process to ensure safe, predictable, and well-communicated software deployments. They act as the central point of coordination across engineering, operations, and business stakeholders.

### Responsibilities
- Own and maintain the release calendar and release plan
- Coordinate go/no-go decisions with Project Managers, Product Managers, and DevOps
- Ensure pre-release checklists are completed (CI passing, release notes, rollback plan)
- Communicate release schedules, scope changes, and risks to all stakeholders
- Manage release-related incidents and coordinate rollback decisions
- Drive continuous improvement of the release process

### Goals
- Deliver releases on schedule with minimal disruption to users
- Increase confidence and predictability in the deployment process
- Reduce release-related incidents through process discipline and automation

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Release notes and stakeholder announcements
- Coordination with DevOps on deployment windows and pipeline status
- Post-release retrospectives and incident debriefs

### How they interact with existing roles
- **Product Managers**: Confirm release scope and ensure newly released features are accurately reflected in release notes and communications.
- **Project Managers**: Align on release milestones, flag risks that may delay releases, and coordinate dependency resolution.
- **Developers**: Verify that all code intended for a release is merged, tested, and meets the Definition of Done; coordinate hotfix processes.
- **QA/Testing**: Confirm testing is complete and all blocking issues are resolved before approving a release.
- **Stakeholders**: Provide advance notice of release schedules, scope, and any potential service impact; deliver post-release summaries.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Roles & Responsibilities Matrix](octoacme-roles-and-responsibilities-matrix.md) for a view of how all roles share ownership across the project lifecycle.

