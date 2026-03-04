Hi There!

## Open Source Tools for Evaluating Prompt Quality

A curated list of open source tools for evaluating LLM prompt quality, including cache rate analysis and functionality testing.

### Prompt Testing & Evaluation

| Tool | Focus | Language | Key Features |
|------|-------|----------|-------------|
| [Promptfoo](https://github.com/promptfoo/promptfoo) | Prompt testing | Node.js | CLI/YAML-based prompt unit testing, A/B testing, assertions (regex, similarity, LLM-as-judge), CI/CD integration |
| [DeepEval](https://github.com/confident-ai/deepeval) | LLM evaluation | Python | Pytest-style LLM tests, built-in metrics (correctness, faithfulness, hallucination), custom metrics, dataset management |
| [Ragas](https://github.com/explodinggradients/ragas) | RAG evaluation | Python | Faithfulness, answer relevance, context precision/recall metrics for RAG pipelines |

### Observability & Cache Rate Analysis

| Tool | Focus | Language | Key Features |
|------|-------|----------|-------------|
| [Langfuse](https://github.com/langfuse/langfuse) | LLM observability | TypeScript | End-to-end tracing, prompt cache rate tracking, A/B testing, cost analytics, self-hostable |
| [Helicone](https://github.com/Helicone/helicone) | Prompt analytics | TypeScript | Per-prompt latency/token/cost tracking, cache rate visualization, API proxy integration |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | LLM observability | Python | OpenTelemetry-based tracing, debugging, live monitoring, RAG evaluation |

### Monitoring & Drift Detection

| Tool | Focus | Language | Key Features |
|------|-------|----------|-------------|
| [Evidently](https://github.com/evidentlyai/evidently) | ML/LLM monitoring | Python | Output drift detection, LLM-as-judge, dashboards, test suites for production monitoring |

### Choosing a Tool

- **Prompt iteration & regression testing**: [Promptfoo](https://github.com/promptfoo/promptfoo) or [DeepEval](https://github.com/confident-ai/deepeval)
- **Cache rate & production analytics**: [Langfuse](https://github.com/langfuse/langfuse) or [Helicone](https://github.com/Helicone/helicone)
- **Ongoing monitoring & drift detection**: [Evidently](https://github.com/evidentlyai/evidently)
- **RAG pipeline evaluation**: [Ragas](https://github.com/explodinggradients/ragas) or [Arize Phoenix](https://github.com/Arize-ai/phoenix)
