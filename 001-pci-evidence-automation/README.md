# Case Study: PCI DSS Evidence Automation

## Context
Manual evidence collection + formatting slowed audit prep and created version drift.

## Objective
Automate evidence collection, hashing, and packet generation for PCI DSS 4.0.1.

## Approach
- PowerShell/Python collectors (configs, users, CA policies, logs)
- AI summaries for logs/configs (ChatGPT/Claude) for audit-ready notes
- Hash-sealed evidence index + timestamped /evidence/ bundle

## Results
- ~60% reduction in prep time
- 90% fewer manual formatting tasks
- Reusable pipeline for future cycles

## Artifacts
- Scripts: `../pci-dss-certification-automation/scripts/` (linked)
- Docs: `./docs/` (add screenshots)
- Templates: CAPA log, ITGC test steps

## Next
- Config drift detection; optional GRC integration (AuditBoard/TeamMate)
