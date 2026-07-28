<!--
  Elias 不吃糖 · GitHub Profile README
  Local images only for custom art; shields.io + github-readme-stats for badges/stats
-->

<div align="center">
  <img src="images/banner.svg" alt="Elias" width="100%" />
</div>

<br/>

<div align="center">
  <img src="images/avatar-main.jpg" width="140" height="140" alt="Elias" />
</div>

<h1 align="center">Elias 不吃糖</h1>

<p align="center">
  <strong>Agent &amp; Distributed Systems Developer</strong><br/>
  <sub>Java / Python / C++ · LangChain / LangGraph · Epoll / IO_uring</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-e85d4c?style=flat-square&labelColor=0d1117" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-58a6ff?style=flat-square&labelColor=0d1117" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/AI%20Agent-3fb950?style=flat-square&labelColor=0d1117" alt="AI Agent"/>
  <img src="https://img.shields.io/badge/Distributed%20IM-1f6feb?style=flat-square&labelColor=0d1117" alt="Distributed IM"/>
  <img src="https://img.shields.io/badge/Epoll%20%2F%20IO_uring-f5a623?style=flat-square&labelColor=0d1117" alt="Epoll / IO_uring"/>
</p>

<p align="center">
  <a href="https://github.com/elaysia-feng"><img src="https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://blog.csdn.net/2504_93605592"><img src="https://img.shields.io/badge/CSDN-FC5531?style=flat-square&logo=csdn&logoColor=white" alt="CSDN"/></a>
  <a href="https://space.bilibili.com/1394496764"><img src="https://img.shields.io/badge/Bilibili-00A1D6?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili"/></a>
  <a href="mailto:elaysia@example.com"><img src="https://img.shields.io/badge/Email-8b949e?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=elaysia-feng&show_icons=true&include_all_commits=true&count_private=true&theme=dark&hide_border=true&title_color=e85d4c&icon_color=e85d4c&text_color=c9d1d9&bg_color=0d1117&rank_icon=github" alt="GitHub stats" height="170" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=elaysia-feng&layout=compact&theme=dark&hide_border=true&title_color=e85d4c&text_color=c9d1d9&bg_color=0d1117" alt="Top languages" height="170" />
  <br/>
  <img src="https://streak-stats.demolab.com/?user=elaysia-feng&theme=github-dark&hide_border=true&background=0D1117&ring=E85D4C&fire=E85D4C&currStreakLabel=E85D4C" alt="GitHub streak" />
</div>

---

## About Me

做 **AI Agent** 与 **低延迟分布式系统**。关心的不是堆框架，而是连接数、端到端延迟，以及系统在故障时是否还能自己站起来。

| Focus | What I care about |
| :--- | :--- |
| **AI Agent** | LangChain / LangGraph, Multi-Agent collaboration &amp; planning, Tool Use / Function Calling |
| **Low-Latency IM** | 10k+ persistent connections, end-to-end latency &lt; 10ms, Epoll / IO_uring deep tuning |
| **Distributed Systems** | Canary release, circuit breaking, self-healing, observability (Logs / Metrics / Trace) |
| **Engineering Culture** | Data-driven, kernel I/O profiling, RAII, exception safety, test-first |

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**AI & Agent**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-2ECC71?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Data & Middleware**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RocksDB](https://img.shields.io/badge/RocksDB-2C3454?style=flat-square)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

<details>
<summary><strong>Detailed Skills</strong></summary>

<br/>

| | |
| :--- | :--- |
| **Languages** | C++ 11/14/17/20/23 · C · Python 3 · Java 17+ |
| **AI & Agent** | LangChain · LangGraph · Tool Use · RAG · Function Calling |
| **Systems & Network** | Linux · Epoll / IO_uring · TCP/UDP · WebSocket · gRPC |
| **Architecture** | Reactor/Proactor · Consistency vs Availability · Microservice Governance |
| **Data Layer** | MySQL read/write splitting · Redis Cluster · RocksDB |
| **Tooling** | Docker · CMake · Git · GDB · Valgrind · Shell |

</details>

---

## Featured Projects

### [NebulaChat](https://github.com/elaysia-feng/NebulaChat) · Distributed IM Platform

High-performance distributed IM built on Epoll + Reactor pattern, supporting **10k+** persistent connections with end-to-end latency **&lt; 10ms**. Integrated with MySQL + Redis + Protobuf, complete monitoring and stress-testing pipeline with second-level scaling.

`C++17` `Epoll` `MySQL` `Redis` `Protobuf` `gRPC`

[View Project](https://github.com/elaysia-feng/NebulaChat)

### [MoreChat](https://github.com/elaysia-feng/MoreChat) · Modern C++ IM

Coroutine + Async I/O driven modern IM with log and config hot-reload, **85%+** unit test coverage, full CI/CD pipeline automation, and regular performance benchmarking.

`C++20` `ASIO` `CMake` `Docker` `GTest`

[View Project](https://github.com/elaysia-feng/MoreChat)

---

## Engineering Philosophy

| Principle | Meaning |
| :--- | :--- |
| **Metrics-Driven** | Benchmark → Profile → Optimize. Data first, decisions second. |
| **Clear Boundaries** | Interfaces and contracts constrain complexity. No shared mutable state. |
| **Observability First** | Logs / Metrics / Trace instrumented from day one. Default-on observability. |
| **Code Hygiene** | RAII · Strong types · Few raw pointers · Testability first. |

<details>
<summary><strong>Recent Interests</strong></summary>

- IO_uring + coroutines in high-concurrency: benefits and pitfalls
- Lightweight monitoring agent (unified metrics / logs / traces)
- Consistency vs availability tradeoffs in IM scenarios

</details>

---

## Moments

<div align="center">
  <img src="images/life-1.jpg" width="240" alt="Moment 1" />
  <img src="images/life-2.jpg" width="240" alt="Moment 2" />
  <img src="images/hobby-1.jpg" width="240" alt="Hobby" />
</div>

---

## Contact

| | |
| ---: | :--- |
| **Email** | [elaysia@example.com](mailto:elaysia@example.com) |
| **CSDN** | [blog.csdn.net/2504_93605592](https://blog.csdn.net/2504_93605592) |
| **Bilibili** | [space.bilibili.com/1394496764](https://space.bilibili.com/1394496764) |
| **GitHub** | [github.com/elaysia-feng](https://github.com/elaysia-feng) |

<p align="center">
  <sub>Open to: Backend Architecture · Performance Tuning · Technical Writing · AI Agent Collaboration</sub>
  <br/><br/>
  <sub>Built with precision. Driven by data.</sub>
</p>
