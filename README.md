<div align="center">
  <h1>Krishnatejaswi S</h1>
  <p>Backend · Distributed Systems · LLM Tooling · <a href="https://onfinance.ai">OnFinance.ai</a> · Bangalore</p>
  <p>
    <a href="https://linkedin.com/in/krishnatejaswi-shenthar"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://portfolio.shenthar.me"><img src="https://img.shields.io/badge/Portfolio-000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://twitter.com/kts_o7"><img src="https://img.shields.io/badge/X-000000.svg?style=for-the-badge&logo=x&logoColor=white" alt="X / Twitter" /></a>
    <a href="mailto:krishna.tejaswi@shenthar.com"><img src="https://img.shields.io/badge/Email-D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

## About

I build backend systems that stay fast, observable, and boring in production — reliable APIs, distributed workflows, and pragmatic LLM tooling (RAG, evals, orchestration).

Currently at **OnFinance.ai** building **ComplianceOS** — a compliance automation platform for the BFSI sector, processing 100M+ tokens/month of SEBI, RBI, and IRDAI regulatory data.

- BE in Computer Science @ **RV College of Engineering, Bangalore**
- Contributor to [maximhq/bifrost](https://github.com/maximhq/bifrost) (3.4k★) — fixed streaming correctness bugs in the AWS Bedrock provider
- Working across the LLM stack: agentic workflows (LangGraph), RAG pipelines (ChromaDB, Ollama), multi-model evaluation, TTS, image/video generation
- Interested in distributed systems, LLM infrastructure, and developer tooling

---

## Open Source

**[maximhq/bifrost](https://github.com/maximhq/bifrost)** — Enterprise AI Gateway · 3.4k★ · Go · ~11µs overhead at 5,000 RPS · 20+ LLM providers

| PR | Description |
|----|-------------|
| [#2427](https://github.com/maximhq/bifrost/pull/2427) | Fixed Bedrock streaming silently ignoring `max_retries` — transport errors (`*net.OpError`, `io.ErrUnexpectedEOF`, `*net.DNSError`) routed through wrong error path, bypassing retry gate; added `isStreamTransportError()` helper across 4 sites + 3 regression tests |
| [#1830](https://github.com/maximhq/bifrost/pull/1830) | Fixed concurrent tool call delta loss — deltas routed by recency instead of `tool_call.id`, causing parallel call arguments to merge; fix applied to both Chat Completions and Responses API streaming paths |

---

## Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [faceless-gen](https://github.com/KTS-o7/faceless-gen) | Local-only AI video studio — research doc in, MP4 out. 5-step editorial wizard (angles → story → scenes → music → generate). Stickman style via ComfyUI + Wan 2.2 I2V. 218 tests passing. | ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) ![FastAPI](https://img.shields.io/badge/FastAPI-005571.svg?style=flat-square&logo=fastapi) |
| [graph-rca](https://github.com/KTS-o7/graph-rca) | Log-to-resolution RAG over 200 annotated real-world incidents — LLM builds causal DAGs, ChromaDB (HNSW) retrieves runbook context, output quality validated by a 3-model judge ensemble (Qwen3:32b, GPT-4o-mini, Llama-3.1-70B) across 9 reproducible experiment scripts; GPU-accelerated, includes React frontend | ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) |
| [permission-mongo](https://github.com/KTS-o7/permission-mongo) | RBAC-powered BaaS for MongoDB targeting 50K+ QPS — AST-caching policy compiler, lock-free router, fasthttp, Prometheus + Grafana dashboard, Python SDK | ![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white) |
| [better_bing_image_downloader](https://github.com/KTS-o7/better_bing_image_downloader) | Maintained Python library · 18K+ PyPI downloads · 41★ · v3.0.0 fixed thread-safety, atomic writes, MD5 dedup; test suite grew 0 → 41 tests | ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) |
| [snapshell](https://github.com/KTS-o7/snapshell) | CLI tool to learn Linux commands interactively | ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) |
| [toy-compiler](https://github.com/KTS-o7/toy-compiler) | Full-pipeline compiler (lexer → parser → codegen) for a subset C-like language | ![C](https://img.shields.io/badge/C-%2300599C.svg?style=flat-square&logo=c&logoColor=white) |

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3670A0.svg?style=for-the-badge&logo=python&logoColor=ffdd54)
![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%2307405e.svg?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Messaging**

![FastAPI](https://img.shields.io/badge/FastAPI-005571.svg?style=for-the-badge&logo=fastapi)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600.svg?style=for-the-badge&logo=rabbitmq&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white)

**LLM & AI Tooling**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-5A5A5A.svg?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000.svg?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6719.svg?style=for-the-badge&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063.svg?style=for-the-badge&logo=pydantic&logoColor=white)

**Infra & Observability**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D.svg?style=for-the-badge&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C.svg?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KTS-o7&hide_title=true&hide_border=true&show_icons=true&include_all_commits=true&count_private=true&theme=github_dark" alt="GitHub Stats" width="49%" />
  <img src="https://streak-stats.demolab.com/?user=KTS-o7&theme=github_dark&hide_border=true" alt="GitHub Streak" width="49%" />
</div>

---

## Latest Posts

<!-- BLOG-POST-LIST:START -->
- [Problem 790 Domino and Tromino Tiling](https://KTS-o7.github.io/blog/leetcode-potd/problem-790-domino-and-tromino-tiling/)
- [Problem 3396 Minimum Number of Operations to Make Elements in Array Distinct](https://KTS-o7.github.io/blog/leetcode-potd/problem-3396-minimum-number-of-operations-to-make-elements-in-array-distinct/)
- [Problem 2570 Merge Two 2D Arrays by Summing Values](https://KTS-o7.github.io/blog/leetcode-potd/problem-2570-merge-two-2d-arrays-by-summing-values/)
- [Problem 641 Design Circular Deque](https://KTS-o7.github.io/blog/posts/extraques/problem-641-design-circular-deque/)
- [Problem 1497 Check If Array Pairs Are Divisible by k](https://KTS-o7.github.io/blog/posts/extraques/problem-1497-check-if-array-pairs-are-divisible-by-k/)
<!-- BLOG-POST-LIST:END -->
