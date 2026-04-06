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

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, operations)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Stakeholders/Sponsors** receive milestone-based briefings and are escalated to for major decisions
- **Support/Customer Success** are informed ahead of releases and contribute customer-facing communication plans

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

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor/Stakeholder
- Engineering Manager/Tech Lead is engaged for technical risk escalations before they reach PM level
- For security incidents, follow the security incident runbook and notify Security on-call
- Operations/DevOps/SRE are engaged for production reliability risks and deployment-related issues
- Support/Customer Success are notified when customer-facing impact is confirmed or anticipated
