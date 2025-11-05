# Codefast Day 17 · RUM + SEO Correlation

## Mission
- Correlate Datadog RUM metrics with SEO rankings to identify UX-driven search regressions.
- Provide dashboards, anomaly detection, and weekly reporting automation.

## Implementation Checklist
1. Ingest SEO rank data (e.g., GSC exports) and join with RUM metrics keyed by URL.
2. Build correlation models highlighting pages with performance or UX drops tied to rank loss.
3. Produce dashboards and scheduled reports stored in Git for governance.
4. Suggest remediation actions and track follow-through via issue templates.

## Telemetry & QA
- Validate data joins with unit tests and backfill pipelines with integration tests.
- Alert when correlation pipelines stop receiving fresh data or diverge unexpectedly.

## Deliverables
- README detailing data sources, pipeline schedule, and dashboard usage.
- Template for weekly experience-quality review meetings.
