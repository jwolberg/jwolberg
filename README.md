Applied AI Engineer · Autonomous Agents & Agent Infrastructure
  
I build and ship autonomous AI agent -- tool-calling, multi-agent, with guardrails in code so cost and behavior stay predictable. Multi-agent orchestration, human-in-the-loop gates enforced in code, deterministic routing, RAG, and evals. 

Founder: I've built 2 companies and a production SaaS platform end-to-end.
Published Model Context Protocol server to PyPI.

🔗 [LinkedIn](https://www.linkedin.com/in/jaywolberg/) 


### Flagship
**[tradingvolatility.net](https://stocks.tradingvolatility.net/)** — production options-analytics platform I built and run: ~1M options contracts/day → ~60M decision-ready signals across ~1,000 securities. Its **[Model Context Protocol server](https://github.com/tradingvolatility/tv-mcp)** (published to PyPI) puts those live signals inside Claude, Cursor, and VS Code.


### Shipped products — designed, built & owned end-to-end

| Product | What it is |
|---|---|
| **[tradingvolatility.net](https://stocks.tradingvolatility.net/)** | Production options-analytics platform (~1M contracts/day → ~60M signals). Live subscription business. |
| **[arethingsok.com](https://arethingsok.com)** | Event-driven world-monitoring (news, air traffic, earthquakes, port congestion, ISP/data-center outages, FX, air quality, sports, prediction markets). When an event fires, a swarm of LLM agents analyzes it from  multiple angles and produces a synthesized report. |
| **[optionace.net](https://optionace.net)** | Provides portfolio-specific optimization opportunities and trade automation for stocks and options. |
| **[sparkbuddy.io](https://sparkbuddy.io)** | Turns a business idea into a step-by-step plan (GPT-4o, server-side). Full-stack React/Vite + Stripe. |

### Selected AI systems demos

- **[chartbreaker](https://github.com/jwolberg/chartbreaker)** — autonomous multi-agent red-teamer: an orchestrator dispatches six specialized attackers; an isolated LLM-as-judge auto-promotes confirmed findings into a regression suite. 
- **[intake-hub](https://github.com/jwolberg/intake-hub)** — document → structured extraction with per-field confidence that routes low-confidence records to a human instead of guessing.
- **[ai-sales-agent](https://github.com/jwolberg/ai-sales-agent)** — real-time voice agent with human-approval-gated payments; a consequential action never fires on its own.
- **[blastgate](https://github.com/jwolberg/blastgate)** — deterministic agent/MCP supply-chain security gate; fails a change only on a real attacker→secret path; mapped to the OWASP Agentic Top 10. 
- **[entityiq](https://github.com/jwolberg/entityiq)** — business verification and sanctions screening: a multi-stage pipeline pulls registry, sanctions, domain, network, and web evidence into a deterministic, explainable risk score; every decision is replayable and a human approves every account.

### Stack
Python (Flask / FastAPI) · JavaScript / React / Vite · TypeScript (ramping) · LangChain / LangGraph · RAG (Pinecone) · MCP · Google Cloud (App Engine, Cloud Run) · Docker · Postgres / Firestore
