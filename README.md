# Jorge Benjumea

**AI Solutions Architect · Hands-on Tech Lead** · Madrid, Spain · remote (CET)

I design and build practical AI systems, from agentic workflows and MCP integrations to retrieval-augmented generation and document intelligence. With 25+ years across software engineering, infrastructure and technical leadership, I connect architecture decisions to working software.

### Start here

- **[public-sector-copilot](https://github.com/jorgitobg/public-sector-copilot)** — an integration demo: an agent triages recorded public tenders, answers BOE questions with citations or abstains, and asks permission before saving a report. It composes the MCP server, cited retrieval, gateway and agent loop below. The offline model is scripted; the README separates that demo from its live entry point and records the limitations.
- **[agent-harness](https://github.com/jorgitobg/agent-harness)** — typed tools, JSON Schema validation, permissions, a budgeted agent loop, sub-agents, routing and tracing. The reproducible examples and evaluation runner use scripted models; they are not model benchmarks.
- **[open-tender-radar](https://github.com/jorgitobg/open-tender-radar)** — screens recorded TED and PLACSP public tenders against a company profile and explains each GO / REVIEW / NO_GO decision, rule by rule. Offline demo, open data, no keys.
- **[sovereign-rag](https://github.com/jorgitobg/sovereign-rag)** — extractive question answering over BOE documents, with citations and explicit abstention. The README includes reproducible evaluation results, failures and the limits of a small, partly tuned dataset. No neural retrieval or LLM is needed for the demo.

### Supporting components

- **[mcp-toolbox](https://github.com/jorgitobg/mcp-toolbox)** — read-only BOE search and tender triage over stdio, using the official MCP SDK and a real client/server integration test.
- **[llm-gateway](https://github.com/jorgitobg/llm-gateway)** — bounded requests, ordered fallback, a circuit breaker and content-free logs. Its OpenAI-shaped chat endpoint is text-only: no tool calling, streaming or usage reporting.
- **[durable-outbox](https://github.com/jorgitobg/durable-outbox)** — a dependency-free SQLite job outbox: idempotent enqueue, leased claims, bounded retries and dead-lettering. Delivery is at-least-once, not exactly-once; the demo shows why consumers must handle duplicates.
- **[jobwatch](https://github.com/jorgitobg/jobwatch)** — watches public job-board APIs for new remote roles, with per-source baselines, atomic state and safe output. Includes an offline demo.

### Try it without API keys

After following each repository's installation instructions:

- [Copilot demo](https://github.com/jorgitobg/public-sector-copilot#run-it-no-keys-no-network): `python -m public_sector_copilot.demo --deny --primary-down` exercises operator refusal and provider fallback.
- [RAG evaluation](https://github.com/jorgitobg/sovereign-rag#evaluation): `python -m sovereign_rag.eval` reports retrieval, answer, citation and abstention results separately.
- [Outbox demo](https://github.com/jorgitobg/durable-outbox#reproduce-locally): `python -m durable_outbox.demo` exercises retries, lease recovery and duplicate delivery.

AI-assisted, human-reviewed. Specifications, trade-offs and reproducible failures matter more to me than unsupported benchmark claims.

### Technologies

Python · FastAPI · TypeScript · React · Angular · Node.js · PHP · Odoo · PostgreSQL · Docker · Kubernetes · Linux · Claude · Gemini · OpenAI · Ollama · MCP

[LinkedIn](https://www.linkedin.com/in/jbenjumea)
