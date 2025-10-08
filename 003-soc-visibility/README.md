# Case Study: SOC Visibility (Wazuh + Prometheus + Grafana)

## Context
Fragmented logs/metrics made triage slow; no single POV for security + ops.

## Objective
Stand up unified visibility with alert rules and a “one-glance” dashboard.

## Approach
- Wazuh for logs + rules; Prometheus exporters for infra
- Grafana dashboards + Alertmanager routes (Telegram/Email)
- Runbooks for common alerts (disk, auth anomalies, 5xx spikes)

## Results
- MTTA ↓; clearer ownership/escalation paths
- Alert fatigue reduced via tuned thresholds
- Reusable dashboard JSONs and alert rules

## Artifacts
- Dashboards: `../it-ops-dashboards/grafana/dashboards/`
- Alerts: `../it-ops-dashboards/grafana/alerts/`
- Docs: `./docs/` (screenshots + runbooks)

## Next
- Add threat intel enrichment; link incidents to postmortem template
