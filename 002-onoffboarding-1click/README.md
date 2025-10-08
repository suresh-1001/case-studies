# Case Study: On/Offboarding 1-Click (Workspace/Intune/Slack)

## Context
Provisioning/deprovisioning was manual, error-prone, and slow across SaaS + endpoints.

## Objective
Create a role-based, auditable workflow that completes in minutes.

## Approach
- Role → license map; Intune device compliance + baseline profiles
- Slack/Jira intake → PowerShell automation; mailbox/archive policies
- Evidence log (who/what/when), revocation checklist for leavers

## Results
- Provisioning time: hours → minutes
- Consistent policy baseline on first login
- Complete audit trail for access changes

## Artifacts
- Scripts: `../hr-onboarding-automation/scripts/`
- Docs: `./docs/` (flow + screenshots)
- Templates: RBAC matrix, access review checklist

## Next
- Add PIM elevation for privileged roles; periodic access review job
