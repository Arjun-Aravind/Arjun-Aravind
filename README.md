<h3 align="center">Hi, I'm Arjun Aravind</h3>
<p align="center"><b>Backend Engineer</b><br>
Distributed systems, real-time platforms and AI infrastructure.<br>
Python • FastAPI • Kafka • Redis • Go • Kubernetes • Azure</p>

---

I build backend systems that have to stay fast and correct under load: real-time voice AI, event pipelines, and the platforms AI agents run on. I'm happiest in the hard middle of a system, where concurrency, failover and latency budgets decide whether it holds up in production.

### What I've built

- **Real-time voice AI platform**: 500+ concurrent calls under 800ms, with distributed scheduling peaking at 500,000 calls/day
- **Kafka notification platform**: 10,000+ messages/min at 99.9% reliability, with multi-vendor failover
- **Multi-tenant AI agent platform** on LangGraph: a workflow engine that compiles visual graphs into state machines, and a coding agent that opens verified GitHub PRs
- **Search and API performance**: OpenSearch over 30M+ records (60% faster search), and 35% faster responses across 100+ FastAPI endpoints

### Open source

- [**moderato**](https://github.com/Arjun-Aravind/moderato): async rate limiting for FastAPI, on [PyPI](https://pypi.org/project/moderato/). Fixed window, token bucket and sliding window as atomic Lua scripts on Redis server time. One round trip per check, ~8.4k checks/s, 240+ tests and published benchmarks.

### How I build

- Correctness first under concurrency: atomic operations and one source of time
- Plan for the dependency that fails: retries, failover and backpressure built in from day one
- Measure before optimizing, and publish benchmarks others can reproduce
- Keep it simple until load proves otherwise

---

<p align="center"><a href="https://www.linkedin.com/in/aravindarjun/">LinkedIn</a> · arjunaravind748@gmail.com</p>
