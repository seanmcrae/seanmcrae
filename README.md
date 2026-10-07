# Sean McRae

Technical product manager in Toronto with 9+ years building AI and data products: agentic and RAG search, machine-learning risk models in fintech, and AI transformation programs. I care about shipping AI that is measured, explainable, and cheap enough to run.

These repositories are independent portfolio projects. Each one runs end to end without API keys, ships with tests and CI, and includes a product write-up (`docs/PRODUCT.md`) covering the problem, users, scope, success metrics, trade-offs, and roadmap.

## Projects

| Project | What it does | Stack | Docs |
| --- | --- | --- | --- |
| [ragbench](https://github.com/seanmcrae/ragbench) | Evaluation harness for RAG and agentic search: retrieval metrics, answer faithfulness, latency, and cost per query, with a recommended config under a budget. | Python | [Docs](https://seanmcrae.github.io/ragbench/) |
| [credit-risk-explain](https://github.com/seanmcrae/credit-risk-explain) | Explainable default-risk ranking on public UCI credit data: gradient boosting, SHAP reason codes, calibration, fairness slices, and a model card. | Python, LightGBM, SHAP, Streamlit | [Docs](https://seanmcrae.github.io/credit-risk-explain/) |
| [agent-harness](https://github.com/seanmcrae/agent-harness) | Runtime for tool-using LLM agents with guardrails, budgets, tracing, and scenario evals. Claude or OpenAI, or a mock provider offline. | Python | [Docs](https://seanmcrae.github.io/agent-harness/) |
| [workflow-radar](https://github.com/seanmcrae/workflow-radar) | AI-opportunity audit for business workflows: friction and AI-suitability scoring, ROI with uncertainty, and a phased roadmap. | TypeScript | [Docs](https://seanmcrae.github.io/workflow-radar/) |
| [plg-metrics](https://github.com/seanmcrae/plg-metrics) | Product-led growth analytics: funnels, cohort retention, and A/B experiment analysis with CUPED, SRM checks, and power calculations. | Python, DuckDB, Streamlit | [Docs](https://seanmcrae.github.io/plg-metrics/) |
| [prd-to-backlog](https://github.com/seanmcrae/prd-to-backlog) | Turns a PRD into a reviewable backlog of epics, stories, and acceptance criteria, with quality linting and Jira or Linear export. | TypeScript | [Docs](https://seanmcrae.github.io/prd-to-backlog/) |
| [llm-gateway](https://github.com/seanmcrae/llm-gateway-cost-aware-LLM-router-) | Cost-aware, OpenAI-compatible LLM gateway: routes across model tiers by complexity, budget and latency SLO; 65% cheaper than always-premium in its replay benchmark. | TypeScript | [Docs](https://seanmcrae.github.io/llm-gateway-cost-aware-LLM-router-/) |

## How I work

- Define success metrics and evals before building, and gate releases on them.
- Prefer transparent models and explicit trade-offs over black boxes.
- Track cost to serve alongside quality.
