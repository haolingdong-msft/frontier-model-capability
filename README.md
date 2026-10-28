# Frontier Model Capability

Interactive comparisons of selected frontier models, organized as:

- capability versus benchmark cost per task;
- capability versus median end-to-end response time;
- task-specific performance: website design, software engineering, and
  document creation.

Cost and response-time charts use Artificial Analysis Intelligence Index data.
Task comparisons use DesignArena Website, Terminal-Bench 4.0, AA-Briefcase v1.1,
and GDPval-AA v2.1. Native scores, exact configurations, missing data, and
available confidence intervals are shown separately rather than combined into
a universal ranking. These are model selection aids, not substitutes for
workload-specific evaluation.

The dashboard includes GPT-6.1 Sol, GPT-5.6 Sol, GPT-5.6 Sol Fast, GPT-6.1 Terra,
Gemini 4 Argon, Gemini 3.8 Flash, and Grok 4.7, alongside the existing Claude
Opus 5.5, Claude Sonnet 5.5, GPT-6 Astra, and GPT-6 Luna comparisons.

## Site

https://haolingdong-msft.github.io/frontier-model-capability/

## Data notes

Current cost/response-time series use Artificial Analysis Intelligence Index
v5.0 and were refreshed on October 28, 2026. The suite differs from the previous
v4.3.2 dashboard, so neither its scores nor benchmark-task costs are directly
comparable with the older results.

GPT-5.6 Sol has no current v5.0 aggregate result in the checked sources. Its
September 29, 2026 v4.3.2 results are retained in a separate historical table,
not plotted on the v5.0 axes. Its task-specific results remain where available.

GPT-5.6 Sol Fast is listed with missing measurements: the checked sources have
no exact matching benchmark entry. Standard Sol scores and timings are not
used as a substitute. Missing effort measurements do not establish that a
setting is unsupported.

Task snapshots have their own retrieval dates, effort settings, and agent
harnesses. Their provenance is included in `task-benchmark-snapshot.json`.
