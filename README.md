# daehyupsohn

Building practical AI-agent systems, research automation, local-LLM learning loops, and knowledge workflows.

<!-- ACP:START -->
## Hermes Automation Control Plane

_Public status last changed: 2026-06-29 01:27 KST_

| Surface | Status |
| --- | --- |
| Gateway | 🟢 running |
| Cron scheduler | 🟢 healthy |
| Active automations | 🟢 20 enabled |
| Delivery errors | 🟢 0 |
| Kanban blockers | 🟢 0 |
| RAG indexes | 🟢 fresh |
| Localworker learning loop | 🟡 learning backlog |
| Manual action needed | 🟢 none |

### Automation lanes

| Lane | Public summary |
| --- | --- |
| Research KB / RAG | Chemistry and natural-philosophy knowledge bases are indexed and monitored. |
| Local LLM learning | Localworker is evaluated by deterministic checks plus GPT/default guidance before promotion. |
| Market and community radar | Public-source digests run with deterministic-first reporting and fail-closed guards. |
| Infrastructure watchdogs | Gateway, cron, harness, and champion-status health checks watch for actionable incidents. |
| Kanban work queue | Durable task routing is available for multi-profile agent work; no public task details shown here. |

### RAG Experts / Localworker learning map

| Domain | Learning signal | Stage | Focus |
| --- | --- | --- | --- |
| Natural Philosophy | `█████████░` 91% | mature | reasoning curriculum + seminar loop |
| Chemistry RAG | `███████░░░` 70% | strong | grounded review + RAG judgment |
| Coding / Repo Tasks | `████░░░░░░` 37% | seed | execution-backed diff/test/judge loop |

### Model benchmark scoreboard

_Seed benchmark evidence including anti-Goodhart veto cases; scores update as comparable runs accumulate._

| Model | Class | Chemistry RAG | Natural Philosophy | Coding / Repo Tasks |
| --- | --- | --- | --- | --- |
| GPT-5.5 / default | frontier | `█████████░` 92 <sub>n=5, medium</sub> | `█████████░` 88 <sub>n=5, medium</sub> | `█████████░` 90 <sub>n=6, medium</sub> |
| localworker / gemma4 | local OSS | `████████░░` 76 <sub>n=5, medium, +4 vs raw</sub> | `████████░░` 80 <sub>n=5, medium, +16 vs raw</sub> | `████████░░` 77 <sub>n=6, medium, +17 vs raw</sub> |
| raw Ollama / gemma4 | raw OSS | `███████░░░` 72 <sub>n=5, medium</sub> | `██████░░░░` 64 <sub>n=5, medium</sub> | `██████░░░░` 60 <sub>n=5, medium</sub> |

#### Scoring basis

- Score is normalized to 0-100; 1-5 judge `overall_score` values are mapped linearly.
- Cases mix user-aligned `local_gold` tasks with `safety_veto` anti-Goodhart traps.
- `n` counts distinct evaluated cases per model/domain after repeated case IDs are deduped.
- Confidence is low below n=5, medium at n>=5, and high at n>=10 with multiple benchmark sources.
- Weak bars mark low-confidence seed evidence; strong bars appear only for medium/high confidence.
- Localworker lift compares the flywheel-applied localworker/gemma4 row against raw Ollama/gemma4 direct API baseline on the same scale.

### Snapshot

- Active scheduled automations: **20**
- Telegram-delivered summaries/watchdogs: **16**
- Local-only maintenance jobs: **4**
- Current public alert posture: **green**

This profile page updates automatically when the automation status changes.
<!-- ACP:END -->
