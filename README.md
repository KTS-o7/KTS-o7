<div align="center">
  <h1>Krishnatejaswi S</h1>
  <p>AI + Fullstack Engineer · <a href="https://onfinance.ai">OnFinance.ai</a> · Bangalore</p>
  <p>
    <a href="https://linkedin.com/in/krishnatejaswi-shenthar"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://krishnatejaswi-s.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://twitter.com/kts_o7"><img src="https://img.shields.io/badge/X-000000.svg?style=for-the-badge&logo=x&logoColor=white" alt="X / Twitter" /></a>
    <a href="mailto:shentharkrishnatejaswi@gmail.com"><img src="https://img.shields.io/badge/Email-D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>
</div>

---

## About

I build systems at the intersection of AI infrastructure and full-stack engineering. Currently at **OnFinance.ai**, building AI-powered financial analysis tooling.

- BE in Computer Science @ **RV College of Engineering, Bangalore**
- Contributor to [maximhq/bifrost](https://github.com/maximhq/bifrost) (3.4k stars) — fixed streaming correctness bugs in the AWS Bedrock provider
- Interested in distributed systems, LLM infrastructure, and developer tooling

---

## Open Source

**[maximhq/bifrost](https://github.com/maximhq/bifrost)** — Enterprise AI Gateway · 3.4k stars · Go · ~11µs overhead at 5,000 RPS, 20+ LLM providers

| PR | Description |
|----|-------------|
| [#2427](https://github.com/maximhq/bifrost/pull/2427) | Fixed Bedrock streaming silently ignoring `max_retries` — transport errors (`*net.OpError`, `io.ErrUnexpectedEOF`, `*net.DNSError`) were routed through the wrong error path, bypassing the retry gate; added `isStreamTransportError()` helper across 4 sites + 3 regression tests |
| [#1830](https://github.com/maximhq/bifrost/pull/1830) | Fixed concurrent tool call delta loss — deltas were routed by recency instead of `tool_call.id`, causing arguments from parallel calls to merge; fix applied to both Chat Completions and Responses API streaming paths |

---

## Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [permission-mongo](https://github.com/KTS-o7/permission-mongo) | RBAC-powered BaaS for MongoDB — JWT auth, middleware-based permission enforcement, document versioning, full observability | ![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white) |
| [better_bing_image_downloader](https://github.com/KTS-o7/better_bing_image_downloader) | Fork of bing-image-downloader with improved rate limiting, error recovery, and async support · **41 stars** | ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) |
| [snapshell](https://github.com/KTS-o7/snapshell) | CLI tool to learn Linux commands interactively | ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=flat-square&logo=python&logoColor=ffdd54) |
| [toy-compiler](https://github.com/KTS-o7/toy-compiler) | Full-pipeline compiler (lexer → parser → codegen) for a subset C-like language | ![C](https://img.shields.io/badge/C-%2300599C.svg?style=flat-square&logo=c&logoColor=white) |

---

## Stack

**Languages**

![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0.svg?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

**Frameworks & Tools**

![Next.js](https://img.shields.io/badge/Next.js-black.svg?style=for-the-badge&logo=next.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

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
<!-- BLOG-POST-LIST:END -->
