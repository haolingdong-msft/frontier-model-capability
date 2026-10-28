# Frontier Model Capability

Interactive comparisons of selected frontier models, organized as:

- capability versus benchmark cost per task;
- capability versus median end-to-end response time;
- task-specific performance: website design, software engineering, and
  document creation.

The cost graph has a benchmark selector: Artificial Analysis Intelligence Index
v5.0, CursorBench 4.0, ARC-AGI-1, and ARC-AGI-2. Both axes always use the selected
benchmark's published score/cost pairs; different scales are never mixed.
The response-time chart continues to use Artificial Analysis data.
Task comparisons use DesignArena Website, Terminal-Bench 4.0, AA-Briefcase v1.1,
GDPval-AA v2.1, CursorBench 4.0, ARC-AGI-1/2, Vals Code Migration v1.1,
and the seven LiveBench 2.0 suites from the October 25, 2026 release.
The dashboard contains 17 native-scale metrics and 274 captured
model-configuration results. Native scores, exact configurations, missing data, and
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
Available per-task costs, source-reported runtime, standard errors, task counts,
and LiveBench subscores are retained without inventing confidence intervals.

Gemini 4 Argon Low, Medium, and High results are visible in an effort-coverage
table near the top of the page. These are primary-source CursorBench and ARC
Prize measurements, not substitutes for the missing lower-effort Artificial
Analysis Intelligence Index points. The AA cost option and response-time chart remain High-only for Argon.
CursorBench and both ARC cost graphs plot Argon Low, Medium, and High, with
separate label leaders for nearby points. The cost-graph download follows the
selected benchmark. Cost and model selections are preserved in the URL, for
example `?cost=cursor&model=gemini-4-argon#cost`.

Collection exclusions are recorded in the task snapshot. Secondary-only scores,
an ambiguously versioned Vals effort chart, ARC-AGI-3's distinct interactive
harnesses, and a LiveBench Overall composite with conflicting weighting notes
are not mixed into the displayed metrics.
