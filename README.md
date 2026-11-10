# Jorge Benjumea

**AI Solutions Architect · Hands-on Tech Lead** · Madrid, Spain · remote (CET)

I design and build practical AI systems, from agentic workflows and MCP integrations to retrieval-augmented generation and document intelligence. With 25+ years across software engineering, infrastructure and technical leadership, I connect architecture decisions to working software.

### What I focus on

- Agentic systems, tool use and MCP
- RAG and document intelligence
- Provider-agnostic AI architecture, from cloud APIs to local inference
- Reliable delivery: clear specifications, small changes and reproducible evaluation

### Selected public work

- **[public-sector-copilot](https://github.com/jorgitobg/public-sector-copilot)** — the integration piece: one agent that triages public tenders and answers BOE questions with citations or an honest abstention, composed from four of the projects below (MCP server over stdio, cited RAG, LLM gateway with failover, permissioned agent loop). Pinned by commit, offline and deterministic; the offline demo is scripted, a live entry point runs it with a real model, and the README says exactly what is real, what is simulated and what the live run got wrong (then fixed upstream in sovereign-rag and re-checked).
- **[agent-harness](https://github.com/jorgitobg/agent-harness)** — an agent harness built from scratch, one story at a time: typed tools with JSON Schema, guardrails, budgeted loop, sub-agents, model router, tracing, and an eval runner with scripted models (no real-model claims).
- **[open-tender-radar](https://github.com/jorgitobg/open-tender-radar)** — screens public tenders from TED and PLACSP against a company profile and explains every GO / REVIEW / NO_GO decision rule by rule. Offline demo, recorded open data, no keys.
- **[sovereign-rag](https://github.com/jorgitobg/sovereign-rag)** — question answering over Spanish BOE documents where every answer cites its source passage or abstains. Offline and deterministic, with a reproducible evaluation (and its failures) in the README.
- **[mcp-toolbox](https://github.com/jorgitobg/mcp-toolbox)** — a small MCP server (official Python SDK, stdio): four read-only tools (BOE search and read, tender triage and lookup), resources and a prompt template. Tested against the real server process with the SDK's own client; offline demo, no keys.
- **[llm-gateway](https://github.com/jorgitobg/llm-gateway)** — a small LLM gateway service: bounded requests, ordered provider fallback, a per-provider circuit breaker and logs that never contain prompts. Offline demo with simulated outages; an OpenAI-compatible adapter for hosted or local models.
- **[jobwatch](https://github.com/jorgitobg/jobwatch)** — reports newly published remote roles from public job-board APIs (Greenhouse, Ashby, Lever). Per-source baselining, atomic state, untrusted-data-safe output; no runtime dependencies and an offline demo.

### Currently building

- **public-sector-copilot** — next: record a successful live run as a second fixture.
- **sovereign-rag** — next: an answer-focused model step so the extractive quote lands on the asked fact (two documented failures).
- **agent-harness** — running the eval runner against a real model through the same model port, with the cost shown next to the result.

I share work as it is ready to be reviewed. AI-assisted, human-reviewed; no benchmark claims without reproducible evidence.

### Technologies

Python · FastAPI · TypeScript · React · Angular · Node.js · PHP · Odoo · PostgreSQL · Docker · Kubernetes · Linux · Claude · Gemini · OpenAI · Ollama · MCP

[LinkedIn](https://www.linkedin.com/in/jbenjumea)
