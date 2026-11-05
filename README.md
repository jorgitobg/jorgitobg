# Jorge Benjumea

**AI Solutions Architect · Hands-on Tech Lead** · Madrid, Spain · remote (CET)

I design and build practical AI systems, from agentic workflows and MCP integrations to retrieval-augmented generation and document intelligence. With 25+ years across software engineering, infrastructure and technical leadership, I connect architecture decisions to working software.

### What I focus on

- Agentic systems, tool use and MCP
- RAG and document intelligence
- Provider-agnostic AI architecture, from cloud APIs to local inference
- Reliable delivery: clear specifications, small changes and reproducible evaluation

### Selected public work

- **[agent-harness](https://github.com/jorgitobg/agent-harness)** — an agent harness built from scratch, one story at a time: typed tools with JSON Schema, guardrails, budgeted loop, sub-agents, model router, tracing and evals.
- **[open-tender-radar](https://github.com/jorgitobg/open-tender-radar)** — screens public tenders from TED and PLACSP against a company profile and explains every GO / REVIEW / NO_GO decision rule by rule. Offline demo, recorded open data, no keys.
- **[sovereign-rag](https://github.com/jorgitobg/sovereign-rag)** — question answering over Spanish BOE documents where every answer cites its source passage or abstains. Offline and deterministic, with a reproducible evaluation (and its failures) in the README.
- **[mcp-toolbox](https://github.com/jorgitobg/mcp-toolbox)** — a small MCP server (official Python SDK, stdio) that searches and reads BOE documents. Tested against the real server process with the SDK's own client; offline demo, no keys.
- **[llm-gateway](https://github.com/jorgitobg/llm-gateway)** — a small LLM gateway service: bounded requests, ordered provider fallback, a per-provider circuit breaker and logs that never contain prompts. Offline demo with simulated outages; an OpenAI-compatible adapter for hosted or local models.
- **[jobwatch](https://github.com/jorgitobg/jobwatch)** — reports newly published remote roles from public job-board APIs (Greenhouse, Ashby, Lever). Per-source baselining, atomic state, untrusted-data-safe output; no runtime dependencies and an offline demo.

### Currently building

- **agent-harness** — next stories: an OpenAI-compatible adapter (llama.cpp, Ollama, OpenRouter) checked against recorded fixtures, and hooks wired into the offline demo.
- **mcp-toolbox** — a tender-triage tool backed by `open-tender-radar`, plus MCP resources for the bundled BOE documents.
- **llm-gateway** — next: validate the OpenAI-compatible adapter against a live local model and publish the results, including failures.

I share work as it is ready to be reviewed. AI-assisted, human-reviewed; no benchmark claims without reproducible evidence.

### Technologies

Python · FastAPI · TypeScript · React · Angular · Node.js · PHP · Odoo · PostgreSQL · Docker · Kubernetes · Linux · Claude · Gemini · OpenAI · Ollama · MCP

[LinkedIn](https://www.linkedin.com/in/jbenjumea)
