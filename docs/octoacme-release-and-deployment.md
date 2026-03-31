# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

> **Role clarity:** The **Release Manager** owns end-to-end release coordination — maintaining the release calendar, driving go/no-go decisions, and communicating release outcomes to stakeholders. The **DevOps Engineer** is responsible for pipeline execution, infrastructure provisioning, and rollback mechanics. See [Roles & Personas](octoacme-roles-and-personas.md) for full descriptions, and the [Roles & Responsibilities Matrix](octoacme-roles-and-responsibilities-matrix.md) for per-activity ownership.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- **Security Lead** has reviewed and signed off on security findings; no unresolved critical or high vulnerabilities
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- **Support Coordinator** briefed on new features, known issues, and any user-facing changes

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (**Release Manager** to notify **Support Coordinator** and customer-facing teams)
- [ ] **Support Coordinator** confirms support runbook / FAQs are updated for this release

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - **Support Coordinator** monitors user-reported symptoms and provides impact updates to the incident team
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - **Security Lead** is notified if the incident has a potential security dimension

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
