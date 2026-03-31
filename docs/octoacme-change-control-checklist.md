# OctoAcme — Change Control Checklist

## Purpose
Provide a lightweight, reusable template for submitting, evaluating, and approving changes to project scope, timeline, or resources during execution. This process is owned by the **Change Manager** in coordination with the Project Manager.

---

## When to Use
Use this checklist whenever a proposed change may affect:
- Project scope (adding, removing, or significantly altering deliverables)
- Delivery timeline or milestone dates
- Budget or resource allocation
- Technical architecture or security posture

Minor clarifications or low-impact task adjustments within already-approved scope do not require a formal change request.

---

## Change Request Template

**Change Request ID:** `CR-YYYY-NNN` _(assign sequentially)_

| Field | Details |
|---|---|
| **Title** | Short description of the proposed change |
| **Requested by** | Name and role |
| **Date submitted** | YYYY-MM-DD |
| **Affected deliverables / milestones** | List impacted items |
| **Description** | What is changing and why |
| **Business justification** | Why this change is needed now |
| **Impact: Scope** | What is added, removed, or changed |
| **Impact: Timeline** | Estimated schedule change (+/- days/sprints) |
| **Impact: Effort** | Estimated effort change (+/- story points or days) |
| **Impact: Risk** | New risks introduced or existing risks affected |
| **Security implications** | Any security or compliance considerations _(Security Lead to assess if applicable)_ |
| **Recommended decision** | Approve / Reject / Defer with rationale |
| **Decision** | Pending / Approved / Rejected / Deferred |
| **Decision date** | YYYY-MM-DD |
| **Decision made by** | Name(s) and role(s) |

---

## Change Approval Checklist

### Submission (Change Manager)
- [ ] Change request form completed with all required fields
- [ ] Impacted team members notified of pending change request
- [ ] Impact analysis completed (scope, timeline, effort, risk)
- [ ] Security Lead consulted if the change affects security or compliance posture

### Review (Change Manager + Project Manager)
- [ ] Change request reviewed against project objectives and constraints
- [ ] Product Manager consulted on business impact and priority
- [ ] Effort estimate obtained from relevant Developers or DevOps Engineers
- [ ] Risk Register updated to reflect any new or changed risks
- [ ] Release Manager notified if change affects release scope or timeline

### Approval
- [ ] Decision documented in the change request record (Approved / Rejected / Deferred)
- [ ] Rationale captured for rejected or deferred requests

### Communication (Change Manager)
- [ ] Approved change communicated to all impacted team members
- [ ] Project Manager updates project plan, backlog, and milestones
- [ ] Stakeholders informed of any change to scope, timeline, or cost
- [ ] Release Manager updates release plan if applicable
- [ ] Support Coordinator notified if the change affects user-facing functionality

---

## Escalation
- If consensus cannot be reached at the team level, the **Project Manager** escalates to the **Product Lead** or **Sponsor**.
- Changes with significant security implications are escalated to the **Security Lead** for a binding assessment before a decision is made.

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Roles & Responsibilities Matrix](octoacme-roles-and-responsibilities-matrix.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
