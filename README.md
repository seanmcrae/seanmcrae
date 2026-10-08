# Sean McRae

**I ship AI that is measured, explainable, and cheap enough to run.**

AI product leader in Toronto. 9+ years in product management, building AI and data products: agentic and RAG search, machine-learning risk models in fintech, and AI transformation programs. Open to Director of Product, AI PM and AI strategy roles (Toronto or remote, Canada).

<!-- CONTACT PLACEHOLDER: site, LinkedIn, email, X and any "Previously:" credential line go here once Sean approves them. -->

## Work

Each repo runs end to end without API keys, ships with tests and CI, and includes a product brief (`docs/PRODUCT.md`): problem, users, scope, success metrics, trade-offs, roadmap. Start with the first two.

| Project | Decision it supports | Proof | Links |
| --- | --- | --- | --- |
| **[ragbench](https://github.com/seanmcrae/ragbench)** | Which RAG or agentic-search config to fund, on quality, groundedness, latency and cost under a budget | The only significant gain over BM25 (agentic search) costs 2.9x as much per query | [Docs](https://seanmcrae.github.io/ragbench/) · [PRODUCT.md](https://github.com/seanmcrae/ragbench/blob/main/docs/PRODUCT.md) |
| **[llm-gateway](https://github.com/seanmcrae/llm-gateway-cost-aware-LLM-router-)** | Which model tier each request deserves, within budget, cost cap and latency SLO | 65% cheaper than always-premium on a 300-prompt replay | [Docs](https://seanmcrae.github.io/llm-gateway-cost-aware-LLM-router-/) · [PRODUCT.md](https://github.com/seanmcrae/llm-gateway-cost-aware-LLM-router-/blob/main/docs/PRODUCT.md) |
| [pocketbrains-app](https://github.com/seanmcrae/pocketbrains-app) | How far a private, on-device iOS agent can go: multi-step plans with undo, cited Q&A over your notes | Notes Q&A: 96.7% recall@3, 100% citation faithfulness | [Docs](https://seanmcrae.github.io/pocketbrains-app/) · [PRODUCT.md](https://github.com/seanmcrae/pocketbrains-app/blob/main/docs/PRODUCT.md) |
| [agent-harness](https://github.com/seanmcrae/agent-harness) | How much autonomy to give an agent: budgets, guardrails and human approvals, tested in CI | 19/19 scenarios pass with guardrails on; 15/19 with them off | [Docs](https://seanmcrae.github.io/agent-harness/) · [PRODUCT.md](https://github.com/seanmcrae/agent-harness/blob/main/docs/PRODUCT.md) |
| [credit-risk-explain](https://github.com/seanmcrae/credit-risk-explain) | Whether a risk model is fit to ship: calibration, reason codes, fairness slices, model card | 50.7% of defaulters caught in the riskiest 20% of the queue (real UCI data) | [Docs](https://seanmcrae.github.io/credit-risk-explain/) · [PRODUCT.md](https://github.com/seanmcrae/credit-risk-explain/blob/main/docs/PRODUCT.md) |
| [workflow-radar](https://github.com/seanmcrae/workflow-radar) | Which AI opportunities to fund first: measured friction, suitability, Monte Carlo ROI | Top quick win pays back in 1.2 months (P50) | [Docs](https://seanmcrae.github.io/workflow-radar/) · [PRODUCT.md](https://github.com/seanmcrae/workflow-radar/blob/main/docs/PRODUCT.md) |
| [prd-to-backlog](https://github.com/seanmcrae/prd-to-backlog) | Whether a PRD is buildable: a traceable, linted backlog for GitHub Issues, Jira or Linear | Every requirement traced to a story; lint scores 94 to 97 out of 100 | [Docs](https://seanmcrae.github.io/prd-to-backlog/) · [PRODUCT.md](https://github.com/seanmcrae/prd-to-backlog/blob/main/docs/PRODUCT.md) |
| [plg-metrics](https://github.com/seanmcrae/plg-metrics) | Whether an A/B result is real: SRM checks, CUPED, power, peeking guardrails | CUPED lift +2.31 pp against a true effect of +2.28 pp | [Docs](https://seanmcrae.github.io/plg-metrics/) · [PRODUCT.md](https://github.com/seanmcrae/plg-metrics/blob/main/docs/PRODUCT.md) |

Results come from each repo's bundled synthetic or public data; the repo READMEs give the setup and the caveats.

## How I work

- **Define success metrics and evals before building, and gate releases on them.** [ragbench success metrics](https://github.com/seanmcrae/ragbench/blob/main/docs/PRODUCT.md#success-metrics-and-evals) · [CI fails on a quality regression](https://github.com/seanmcrae/ragbench/blob/main/.github/workflows/ci.yml)
- **Prefer transparent models and explicit trade-offs over black boxes.** [credit-risk-explain model card](https://github.com/seanmcrae/credit-risk-explain/blob/main/docs/MODEL_CARD.md) · [trade-offs considered](https://github.com/seanmcrae/credit-risk-explain/blob/main/docs/PRODUCT.md#trade-offs-and-alternatives-considered)
- **Track cost to serve alongside quality.** [llm-gateway cost vs quality results](https://github.com/seanmcrae/llm-gateway-cost-aware-LLM-router-#results)

Built in public from October 2026 with AI-assisted coding; the product decisions, evals and trade-offs are mine.

## Recent releases

- [pocketbrains-app v0.3.0](https://github.com/seanmcrae/pocketbrains-app/releases/tag/v0.3.0): honest generalization, tool trimming, RAG eval, docs site · 2026-10-08
- [pocketbrains-app v0.2.0](https://github.com/seanmcrae/pocketbrains-app/releases/tag/v0.2.0): multi-step agent, cited note Q&A, system integrations · 2026-10-08
- v0.1.0 of [ragbench](https://github.com/seanmcrae/ragbench/releases/tag/v0.1.0), [llm-gateway](https://github.com/seanmcrae/llm-gateway-cost-aware-LLM-router-/releases/tag/v0.1.0), [agent-harness](https://github.com/seanmcrae/agent-harness/releases/tag/v0.1.0), [credit-risk-explain](https://github.com/seanmcrae/credit-risk-explain/releases/tag/v0.1.0), [workflow-radar](https://github.com/seanmcrae/workflow-radar/releases/tag/v0.1.0), [prd-to-backlog](https://github.com/seanmcrae/prd-to-backlog/releases/tag/v0.1.0) and [plg-metrics](https://github.com/seanmcrae/plg-metrics/releases/tag/v0.1.0) · 2026-10-07
