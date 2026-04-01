# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

**Ownership of risk register updates:**
- **Project Manager** — Accountable; owns the register and ensures it is reviewed at weekly syncs.
- **Change Manager** — Responsible for logging and updating change-driven risks; consults on impact assessment.
- **Security Lead** — Responsible for maintaining and updating security risk entries; consults on mitigation approaches for all technical risks.
- **All team leads** — Consulted; responsible for flagging new risks in their domain.

## Risk Lifecycle
- Identify: during planning and ongoing execution; Change Manager flags scope-change risks; Security Lead flags security and compliance risks
- Assess: estimate impact and likelihood; Security Lead assesses severity of security risks; Change Manager assesses impact of pending changes
- Mitigate: reduced via actions, contingency plans; Security Lead validates remediation of security findings
- Monitor: review at weekly syncs and update status; Change Manager and Security Lead attend or provide async updates

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Security Lead** coordinates security-specific communications and ensures the right parties are notified of security risks without unnecessary broad disclosure.
- **Change Manager** ensures approved changes are communicated to all impacted stakeholders.

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

**Security Incident Communication** (owned by Security Lead):
- Incident classification (severity / scope)
- Immediate containment actions taken
- Affected systems or data
- Regulatory / compliance notification obligations
- Post-incident review scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- **Change-related escalation:** Team-level -> Change Manager -> Project Manager -> Sponsor
- **Security incidents:** Security Lead notified immediately; Security Lead -> Project Manager -> Sponsor; follow the security incident runbook and notify Security on-call
- **Production / support escalation:** Support Coordinator -> Project Manager -> Product Lead (for customer-impacting incidents)
