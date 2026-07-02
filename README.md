# Dae Hyup Sohn

`scientific AI tooling` · `research automation` · `local RAG/MCP systems` · `evaluation-driven agents`

I build reliable AI-assisted research tools: local RAG/MCP advisors, fail-closed automation harnesses, and evaluation-driven LLM workflows for scientific and technical knowledge work.

<!-- ACP:START -->
## RAG Expert Systems and Automation Harness

_Public technical snapshot, regenerated from local automation telemetry: 2026-07-02 11:49 KST._

This public snapshot summarizes the RAG Expert training loop, model-evaluation signals, and operational health of the automation harness.

### Technical focus

| Area | Implementation focus |
| --- | --- |
| RAG Experts | Local RAG/MCP advisors with domain retrieval, prompt contracts, and evaluation loops. |
| Automation harness | Cron/no-agent jobs, Kanban routing, source/runtime drift checks, and fail-closed monitoring. |
| Research workflows | Provenance-aware chemistry and natural-philosophy knowledge bases with review-oriented retrieval. |

### Evaluation scoring criteria

| Reported quantity | Calculation basis | Reporting unit |
| --- | --- | --- |
| Cumulative capability index | Weighted mean of capped evidence components. RAG domains use evaluation-case coverage with weight 0.35, learning-event coverage with weight 0.20, and corpus-chunk coverage with weight 0.25; available components are normalized by their total weight. Coding/repo capability uses repo-task case coverage against its threshold. A state ledger prevents reported cumulative indexes from decreasing. | 0.00-1.00 index |
| Latest sample | Most recent RAG Expert/localworker sample pass rate, reported separately from cumulative evidence so a failed sample does not erase prior evidence. | 0.00-1.00 rate plus label |
| Model benchmark score | Normalized mean score across evaluated cases; n is the scored case count for that domain/model pair. | score/100; n cases |
| Harness operation state | Direct status from gateway, cron, delivery, RAG-index, Kanban, and drift-check probes. | text status |

### RAG Expert capability matrix

| Expert system | Eval/repo cases | Learning events | Corpus chunks | Cumulative index | Latest sample | Training objective |
| --- | --- | --- | --- | --- | --- | --- |
| Natural Philosophy Expert | 81/120 | 26/80 | 107/300 | 0.49 | 0.00 (miss) | reasoning curriculum + seminar loop |
| Chemistry RAG Expert | 14/60 | 36/100 | 15960/20000 | 0.44 | 0.00 (miss) | grounded review + RAG judgment |
| Coding / Repo Expert | repo cases 1/10 | not applicable | not applicable | 0.10 | 0.00 (miss) | execution-backed diff/test/judge loop |

### Model evaluation snapshot

| Model | Class | Chemistry RAG | Natural Philosophy | Coding / Repo Tasks |
| --- | --- | --- | --- | --- |
| GPT-5.5 / default | frontier | 92/100; n=5 | 85/100; n=4 | 90/100; n=6 |
| RAG Experts / gemma4 | local OSS | 60/100; n=3 | 67/100; n=3 | 72/100; n=5 |
| Ollama / gemma4 | OSS baseline | 65/100; n=4 | 64/100; n=5 | 64/100; n=5 |

### Automation harness operations

| Subsystem | Function | Current state |
| --- | --- | --- |
| Gateway | Cross-platform command channel | running |
| Cron scheduler | Scheduled automation runner | attention |
| Active automations | Enabled cron/no-agent jobs | 22 enabled |
| Delivery monitor | Outbound report failures | 1 |
| Kanban queue | Blocked durable tasks | 0 |
| RAG indexes | Knowledge-base freshness | fresh |
| RAG Experts learning loop | Local RAG Expert training and evaluation | training backlog |
| Manual action | Operator intervention required | red attention |

### Active technical tracks

| Track | Scope | Current objective |
| --- | --- | --- |
| Research KB / RAG | Domain knowledge systems | Maintain chemistry and natural-philosophy retrieval with provenance-aware ingestion. |
| Local LLM evaluation | Training and regression checks | Improve local RAG Expert behavior under deterministic checks plus frontier-model guidance. |
| Signal monitoring | Scheduled collectors and reports | Track public technical and market signals with fail-closed source collection. |
| Infrastructure reliability | Gateway, cron, harness, and drift checks | Keep runtime automation synchronized with source-controlled manifests. |
| Kanban work queue | Durable multi-agent routing | Route implementation and review work without exposing private task details. |

### Public telemetry snapshot

| Metric | Value |
| --- | ---: |
| Active scheduled automations | 22 |
| Message delivery routes | 16 |
| Local-only jobs | 6 |
| Public alert posture | red |

Auto-generated from public-safe automation telemetry.
<!-- ACP:END -->
