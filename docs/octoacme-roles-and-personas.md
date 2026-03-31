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

## Change Manager

### Role Summary
Change Managers oversee and coordinate changes that affect project scope, timeline, or resources. They maintain the change log, facilitate change control board (CCB) reviews when required, and ensure that all changes are properly assessed for risk and impact before implementation.

### Responsibilities
- Establish and maintain the change request process and approval workflows
- Facilitate impact analysis with relevant stakeholders before changes are approved
- Maintain the change log and keep it current throughout the project lifecycle
- Communicate approved changes and their implications to impacted teams
- Ensure rejected or deferred changes are documented with rationale

### Goals
- Prevent scope creep and uncontrolled changes from destabilizing delivery
- Ensure all changes are evaluated, approved, and communicated consistently
- Maintain an auditable record of decisions and change history

### Typical Communication
- Change request forms and approval notifications
- Change control board meetings or async reviews
- Change log updates shared with Project Managers and stakeholders
- Impact summaries for approved scope or timeline adjustments

### How they interact with existing roles
- **Project Managers**: Collaborate closely to log, prioritize, and schedule approved changes; surface change-driven risks and timeline impacts.
- **Product Managers**: Consult on scope changes to ensure alignment with product strategy and customer commitments.
- **Developers**: Notify of approved scope or technical changes that affect implementation plans; gather effort estimates for change analysis.
- **Release Manager**: Coordinate changes that affect release scope or timing; ensure change approvals are reflected in the release plan.
- **Stakeholders**: Present change requests for approval; communicate impact of approved changes on budget, timeline, and scope.

---

## Security Lead

### Role Summary
Security Leads ensure that security requirements are identified and embedded throughout the project lifecycle. They guide threat modeling, coordinate vulnerability assessments, and validate that security risks are remediated before software is released.

### Responsibilities
- Advise on security best practices, standards, and applicable regulatory requirements
- Conduct or coordinate threat assessments and security design reviews
- Review and validate remediation of identified vulnerabilities prior to release
- Maintain a security risk log and escalate critical findings to Product and Project Managers
- Ensure security scanning is integrated into CI/CD pipelines and interpreted correctly
- Act as the primary point of escalation for security incidents

### Goals
- Embed security into the delivery process from initiation through release
- Reduce the likelihood and impact of security incidents in production
- Ensure the team meets applicable compliance and regulatory obligations

### Typical Communication
- Security review findings and remediation tracking
- Pre-release security sign-off and go/no-go input
- Security incident notifications and post-incident reports
- Guidance documents and threat model outputs shared with the delivery team

### How they interact with existing roles
- **Product Managers**: Advise on security requirements that may influence roadmap priorities or product decisions; surface compliance constraints early.
- **Project Managers**: Report security risks that could affect timelines or scope; participate in risk register reviews.
- **Developers**: Provide secure coding guidance, review code for security concerns, and support remediation of identified vulnerabilities.
- **DevOps Engineers**: Collaborate on pipeline security, secrets management, infrastructure hardening, and monitoring for security events.
- **QA/Testing**: Define security acceptance criteria and support security-focused test coverage.
- **Release Manager**: Provide security sign-off as part of the pre-release checklist; flag unresolved vulnerabilities that should block release.

---

## Support Coordinator

### Role Summary
Support Coordinators manage the transition from delivery to post-release operations. They own the communication loop between end users and the delivery team, triaging production issues and user feedback to ensure timely resolution and continuous improvement.

### Responsibilities
- Triage incoming support requests, production bugs, and user feedback
- Coordinate prioritization and handoff of post-release issues to the development team
- Maintain user-facing status pages, FAQs, and support knowledge base content
- Track and report on support volume, trends, and resolution times
- Ensure support teams are briefed ahead of each release on new features and known issues

### Goals
- Minimize user impact from production issues through rapid triage and escalation
- Close the feedback loop between end users and the delivery team
- Improve self-service support coverage to reduce repetitive escalations

### Typical Communication
- Support ticket updates and escalation notifications to the development team
- Pre-release briefings from the Release Manager on upcoming changes
- Regular summaries of support volume and trending issues for Product Managers
- Post-release incident reports and user-impact assessments

### How they interact with existing roles
- **Release Manager**: Receive advance notice of release scope and timing; provide post-release user impact feedback; participate in go/no-go discussions for high-risk releases.
- **Developers**: Escalate reproducible production bugs with supporting context; coordinate fixes and verify resolutions.
- **QA/Testing**: Share user-reported issues that reveal gaps in test coverage; collaborate on regression test cases.
- **Product Managers**: Surface support trends and recurring user pain points to inform roadmap prioritization.
- **Project Managers**: Report support-related risks or production incidents that may require project-level escalation.
- **DevOps Engineers**: Escalate infrastructure-related user-impacting issues; collaborate on incident resolution.

---

## Community Moderator

### Role Summary
Community Moderators guide and maintain healthy contributor and user communities for open source or community-facing projects. They enforce community guidelines, help onboard contributors, and ensure productive interactions across forums, issue trackers, and code discussions.

### Responsibilities
- Review community contributions for adherence to contribution guidelines and code of conduct
- Moderate discussions, resolve conflicts, and enforce community standards
- Onboard and mentor new contributors; maintain contributor documentation
- Organize community calls, events, and recognition programs
- Triage community-raised issues and route them to the appropriate delivery team members

### Goals
- Foster a welcoming, productive, and inclusive contributor community
- Reduce friction for new contributors joining the project
- Ensure community feedback reaches the delivery team in a structured, actionable form

### Typical Communication
- Community forum moderation and announcements
- Contributor onboarding guides and welcome communications
- Regular community update posts and event coordination
- Issue triage summaries shared with Product Managers and Project Managers

### How they interact with existing roles
- **Product Managers**: Surface trends from community discussions and contributor feedback to inform roadmap decisions; collaborate on communicating product direction to the community.
- **Project Managers**: Report community-raised issues or risks that require internal escalation; coordinate community involvement in milestone activities.
- **Developers**: Facilitate community code contributions by clarifying contribution guidelines and coordinating PR reviews with maintainers.
- **Customer Success Manager**: Share community sentiment and adoption signals that may affect customer-facing communications.

---

## Customer Success Manager

### Role Summary
Customer Success Managers act as the primary point of contact for strategic or high-value customers, ensuring they realize measurable value from the product. They bridge the customer relationship and the delivery team, translating customer needs into actionable product insights.

### Responsibilities
- Onboard customers and guide adoption of new features and capabilities
- Collect, synthesize, and relay customer feedback to inform roadmap decisions
- Proactively identify expansion, renewal, or at-risk signals and escalate appropriately
- Represent the customer perspective in planning sessions and retrospectives
- Coordinate with Support Coordinator for escalated or high-priority customer issues

### Goals
- Ensure customers achieve their desired outcomes from the product
- Maximize customer retention and expansion through proactive engagement
- Translate customer insights into product improvements that benefit the broader user base

### Typical Communication
- Regular customer check-ins and business reviews (QBRs)
- Feature adoption reports and health metrics shared with Product Managers
- Escalation notifications to Support Coordinator and Project Managers
- Customer-facing release summaries and roadmap previews

### How they interact with existing roles
- **Product Managers**: Advocate for customer-driven feature needs and share adoption data; participate in roadmap planning to ensure customer commitments are represented.
- **Release Manager**: Receive advance notice of release scope and timing to prepare customer communications; provide customer impact assessment for high-risk releases.
- **Support Coordinator**: Collaborate on escalated or high-priority customer issues; share customer context to accelerate triage and resolution.
- **Project Managers**: Surface customer commitments or escalations that should be reflected in project priorities or risk registers.
- **Developers**: Communicate customer-specific use cases or constraints that may influence technical decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Roles & Responsibilities Matrix](octoacme-roles-and-responsibilities-matrix.md) for a view of how all roles share ownership across the project lifecycle.

