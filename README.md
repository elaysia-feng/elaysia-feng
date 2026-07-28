<!--
  Elias 不吃糖 · GitHub Profile README
  Palette: Lycoris red #e85d4c · ink #0b0f14 · mist #9aa4b2 · signal blue #58a6ff
  GitHub-safe: tables + shields + SVG banner (no flex/grid/shadows)
-->

<div align="center">
  <img src="images/banner.svg" alt="Elias 不吃糖" width="100%" />
</div>

<br/>

<div align="center">
  <img src="images/avatar-main.jpg" width="118" height="118" alt="Elias 不吃糖" style="border-radius:50%; border:3px solid #e85d4c;" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-e85d4c?style=for-the-badge&labelColor=161b22" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-58a6ff?style=for-the-badge&labelColor=161b22" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/AI%20Agent-3fb950?style=for-the-badge&labelColor=161b22" alt="AI Agent"/>
  <img src="https://img.shields.io/badge/Distributed%20IM-1f6feb?style=for-the-badge&labelColor=161b22" alt="Distributed IM"/>
  <img src="https://img.shields.io/badge/Epoll%20%2F%20IO_uring-f5a623?style=for-the-badge&labelColor=161b22" alt="Epoll / IO_uring"/>
</p>

<p align="center">
  <a href="https://github.com/elaysia-feng"><img src="https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=e6edf3" alt="GitHub"/></a>
  <a href="https://blog.csdn.net/2504_93605592"><img src="https://img.shields.io/badge/CSDN-FC5531?style=flat-square&logo=csdn&logoColor=white" alt="CSDN"/></a>
  <a href="https://space.bilibili.com/1394496764"><img src="https://img.shields.io/badge/Bilibili-00A1D6?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili"/></a>
  <a href="mailto:elaysia@example.com"><img src="https://img.shields.io/badge/Email-8b949e?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About

做 **AI Agent** 与 **低延迟分布式系统**。关心的不是堆框架，而是连接数、端到端延迟、以及系统在故障时是否还能自己站起来。

| Focus | What I care about |
| :--- | :--- |
| AI Agent | LangChain / LangGraph · Multi-Agent · Tool Use / Function Calling |
| Low-Latency IM | 10k+ 长连接 · 端到端延迟 &lt; 10ms · Epoll / IO_uring |
| Distributed Systems | 灰度 · 熔断 · 自愈 · Logs / Metrics / Trace |
| Engineering | 数据驱动 · 内核 I/O profiling · RAII · Test-first |

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**AI & Agent**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2ECC71?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Data & Middleware**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RocksDB](https://img.shields.io/badge/RocksDB-2C3454?style=flat-square&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

<details>
<summary><strong>Detailed Skills</strong></summary>

<br/>

| | |
| :--- | :--- |
| **Languages** | C++11–23 · C · Python 3 · Java 17+ |
| **AI & Agent** | LangChain · LangGraph · Tool Use · RAG · Function Calling |
| **Systems & Network** | Linux · Epoll / IO_uring · TCP/UDP · WebSocket · gRPC |
| **Architecture** | Reactor / Proactor · Consistency vs Availability · Microservice Governance |
| **Data Layer** | MySQL 读写分离 · Redis Cluster · RocksDB |
| **Tooling** | Docker · CMake · Git · GDB · Valgrind · Shell |

</details>

---

## Featured Projects

### [NebulaChat](https://github.com/elaysia-feng/NebulaChat) · Distributed IM Platform

基于 Epoll + Reactor 的高性能分布式 IM，支持 **10k+** 长连接，端到端延迟 **&lt; 10ms**。MySQL + Redis + Protobuf，配套监控与压测流水线，支持秒级扩缩容。

`C++17` `Epoll` `MySQL` `Redis` `Protobuf` `gRPC`

[![Repo](https://img.shields.io/badge/View_Project-e85d4c?style=flat-square)](https://github.com/elaysia-feng/NebulaChat)

### [MoreChat](https://github.com/elaysia-feng/MoreChat) · Modern C++ IM

协程 + 异步 I/O 驱动的现代 IM：日志与配置热更新，单测覆盖率 **85%+**，完整 CI/CD，定期性能基准。

`C++20` `ASIO` `CMake` `Docker` `GTest`

[![Repo](https://img.shields.io/badge/View_Project-58a6ff?style=flat-square)](https://github.com/elaysia-feng/MoreChat)

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=elaysia-feng&show_icons=true&include_all_commits=true&count_private=true&theme=transparent&hide_border=true&title_color=e85d4c&icon_color=e85d4c&text_color=c9d1d9&bg_color=00000000" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=elaysia-feng&layout=compact&theme=transparent&hide_border=true&title_color=e85d4c&text_color=c9d1d9&bg_color=00000000" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=elaysia-feng&theme=dark&hide_border=true&background=00000000&ring=e85d4c&fire=e85d4c&currStreakLabel=e85d4c" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/e85d4c/elaysia-feng" alt="Contribution graph" width="100%" />
</p>

---

## Engineering Philosophy

| | |
| :--- | :--- |
| **Metrics-Driven** | Benchmark → Profile → Optimize。先有数据，再做决策。 |
| **Clear Boundaries** | 用接口与契约约束复杂度，拒绝共享可变状态。 |
| **Observability First** | Logs / Metrics / Trace 从第一天就埋好。 |
| **Code Hygiene** | RAII · 强类型 · 少裸指针 · 可测试性优先。 |

<details>
<summary><strong>Recent Interests</strong></summary>

- IO_uring + 协程在高并发场景下的收益与坑
- 轻量监控 Agent（统一 metrics / logs / traces）
- IM 场景下一致性与可用性的取舍

</details>

---

## Moments

<p align="center">
  <img src="images/life-1.jpg" width="220" height="140" alt="Moment 1" />
  &nbsp;
  <img src="images/life-2.jpg" width="220" height="140" alt="Moment 2" />
  &nbsp;
  <img src="images/hobby-1.jpg" width="220" height="140" alt="Hobby" />
</p>

---

## Contact

<p align="center">
  <a href="mailto:elaysia@example.com">Email</a>
  ·
  <a href="https://blog.csdn.net/2504_93605592">CSDN</a>
  ·
  <a href="https://space.bilibili.com/1394496764">Bilibili</a>
  ·
  <a href="https://github.com/elaysia-feng">GitHub</a>
</p>

<p align="center">
  <sub>Open to Backend Architecture · Performance Tuning · Technical Writing · AI Agent Collaboration</sub>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=elaysia&layout=compact&theme=transparent&hide_border=true&title_color=e85d4c&text_color=c9d1d9&bg_color=00000000" alt="WakaTime" />
</p>

<p align="center">
  <sub>Built with precision. Driven by data.</sub>
</p>
