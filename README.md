# Multi-Source Pipeline Health: Ingestion, Conformance & Drift Monitoring

Simulates 11 independent upstream data sources feeding a shared platform — 
each with its own schema, data quality profile, and arrival latency. Builds 
a Bronze (per-source validation + quarantine), Silver (schema conformance + 
freshness-aware join), and Gold (unified table with per-source confidence 
flags) pipeline, plus SLA-style data quality, freshness, and drift monitoring. 
Includes a simulated real-world failure — a source silently changing its unit 
of measure — which the drift detection catches and isolates.

**Stack:** PySpark · Spark SQL · Delta Lake · Data Quality · Drift Detection · Databricks-compatible

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Bawelile/multi-source-pipeline-health/blob/main/Multi_Bottler_Pipeline_Health.ipynb)

**Portfolio:** [Bawelile.github.io](https://Bawelile.github.io)
