---
name: querying-axiom
description: Queries Axiom for observability data. Use when user mentions Axiom, traces, spans, APL, monitors, telemetry, latency, p99.
mcp:
  axiom:
    command: bunx
    args: ["--bun", "mcp-remote", "https://mcp.axiom.co/mcp"]
---

# Axiom Observability Integration

## Decision Tree

```text
What does the user need?
├─ Explore/discover → listDatasets → getDatasetSchema → queryApl
├─ Query specific data → queryApl (check schema first if unsure of fields)
├─ View dashboards → listDashboards → getDashboard
├─ Check alerts → getMonitors → getMonitorsHistory
├─ Reuse existing query → getSavedQueries
└─ Deep analysis → Use prompts (see below)
```

## Tools

| Tool | Purpose | Key Parameters |
|------|---------|----------------|
| `listDatasets` | List all datasets | — |
| `getDatasetSchema` | Get field names/types for a dataset | `datasetName` |
| `queryApl` | Run APL query | `apl`, `startTime`, `endTime` |
| `listDashboards` | List all dashboards | — |
| `getDashboard` | Get dashboard details | `dashboardId` |
| `getMonitors` | List configured alerts | — |
| `getMonitorsHistory` | View alert trigger history | `monitorId` |
| `getSavedQueries` | List saved APL queries | — |

## Prompts (for complex analysis)

Use these instead of manual queries when the task matches:

| Prompt | When to Use |
|--------|-------------|
| `detect-anomalies-in-events` | User asks about unusual patterns, spikes, outliers |
| `data-quality-investigation` | Missing data, gaps, inconsistencies |
| `establish-performance-baseline` | Setting up SLOs, understanding normal behavior |
| `explore-unknown-dataset` | User doesn't know what's in a dataset |
| `monitor-health-analysis` | Noisy alerts, alert fatigue, monitor effectiveness |
| `correlate-events-across-datasets` | Cross-service debugging, distributed tracing |

## Query Rules (Critical)

| Always Do | Never Do |
|-----------|----------|
| Include `where _time > ago(...)` | Query without time bounds |
| Add `limit 100` when exploring | Return unlimited rows |
| Call `getDatasetSchema` if unsure of fields | Guess field names |
| Use `summarize` for large datasets | Fetch millions of raw rows |
| Start with small time range (1h), expand if needed | Start with 30d on first query |

## APL Reference

For all functions, operators, and examples: https://axiom.co/docs/llms-apl.md

Fetch this when you need syntax for: parse_json, extract, percentile, spotlight, rate, parse_url, bin, or any other APL function.
