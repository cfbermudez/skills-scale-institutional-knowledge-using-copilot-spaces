# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented (reviewed by Operations/DevOps/SRE)
- Smoke tests prepared and executed by QA Engineers / Quality Leads
- Support/Customer Success briefed on changes and customer-facing communication ready

## Deployment Checklist
- [ ] Deployment window scheduled and confirmed with Operations/DevOps/SRE
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Engineers sign off)
- [ ] Deploy to production (automated pipeline preferred; Operations/DevOps/SRE oversee)
- [ ] Run post-deploy verifications (monitoring, alerts, error rates)
- [ ] Announce release to stakeholders and support (Support/Customer Success notified)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
