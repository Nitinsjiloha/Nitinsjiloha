<h1 align="center">Nitin Singh Jiloha</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=00E5A0&center=true&vCenter=true&width=820&height=42&lines=Lead+Software+Engineer+%40+Solytics+Partners;Low-Latency+C%2B%2B+%E2%80%A2+HFT+%26+Trading+Systems;Built+a+sub-microsecond+LOB+matching+engine;Distributed+Systems+%E2%80%A2+Async+Python+%E2%80%A2+C%2B%2B20;Codeforces+Specialist+%E2%80%A2+Market+Microstructure" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nitin-singh-jiloha-b22691a4/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://codeforces.com/profile/nitinsingh__"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
  <a href="https://leetcode.com/u/Nitinsjiloha"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:jilohanitin@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=Nitinsjiloha&style=for-the-badge&color=00E5A0&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/p50_match_latency-%3C1%C2%B5s-00E5A0?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/throughput-1M%2B_orders%2Fsec-2E9EF7?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/records_processed-1B%2B-FFA116?style=flat-square&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/exactly--once-zero_data_loss-DC382D?style=flat-square&labelColor=0d1117" />
</p>

---

### 🧠 `whoami`

```cpp
struct NitinJiloha {
    std::string role        = "Lead Software Engineer";
    std::string company     = "Solytics Partners";
    std::string location    = "New Delhi, India";
    int         experience  = 6;  // years (and counting)

    // What I ship today
    std::vector<std::string> domains = {
        "AML & Risk", "Financial Services", "Distributed Systems"
    };

    // Where the latency budget is going
    std::vector<std::string> focus = {
        "Low-latency C++20", "Lock-free data structures",
        "Matching engines & LOB internals", "Kernel-bypass networking"
    };

    std::vector<std::string> learning = {
        "HFT / trading infra", "Competitive Programming", "Go"
    };

    [[nodiscard]] std::string mantra() const noexcept {
        return "Make it correct, make it idempotent, then make it fast.";
    }
};
```

> 🏎️  Lead engineer by day, low-latency obsessive by night. I build **fault-tolerant, idempotent distributed systems** that move **billions of records** with exactly-once guarantees — and I'm channeling that into **C++ HFT infrastructure** where the budget is nanoseconds, not milliseconds.
>
> 📈  Active **NSE/BSE intraday trader** (BankNifty / Nifty50) — market microstructure isn't a textbook chapter for me, it's a daily P&L.

---

### ⚡ Featured Build — Limit Order Book Matching Engine

```text
┌─ engine/match  ─────────────────────────────────────────────┐
│  language     C++20                                          │
│  matching     price-time priority (limit/market/cancel/mod)  │
│  data layout  cache-friendly flat arrays, pool allocators    │
│  feed         ITCH 5.0 zero-copy binary parser               │
│  decoupling   lock-free SPSC ring buffer (std::atomic, a/r)  │
│  tooling      CMake · Google Benchmark · perf · flamegraphs  │
├─ benchmarks  ───────────────────────────────────────────────┤
│  p50 match latency .......................... < 1 µs         │
│  throughput ................................. 1M+ orders/sec │
│  SPSC ring-buffer op ........................ < 50 ns        │
└──────────────────────────────────────────────────────────────┘
```

🧩 Part of a **17-project low-latency roadmap** — ITCH parser, matching engine, lock-free ring buffer, FIX engine, and more.

---

### 🛠️ Tech Stack

**Low-Latency / Systems**

![C++](https://img.shields.io/badge/C%2B%2B20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Linux perf](https://img.shields.io/badge/Linux_perf-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Lock-Free](https://img.shields.io/badge/Lock--Free_/_std::atomic-1A1A1A?style=for-the-badge&logo=cplusplus&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Async**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

### 🚀 What I'm Focused On

| Track | Detail |
|------|--------|
| 🏎️ **HFT / Low-Latency** | Lock-free structures, cache-aware C++, ITCH/FIX parsing, kernel-bypass (DPDK/AF_XDP), nanosecond budgets |
| ⚙️ **Distributed Systems** | Idempotent APIs, exactly-once processing, backpressure, circuit breakers, distributed locking |
| 🧮 **Competitive Programming** | Codeforces & LeetCode grind — advanced graphs/DP, structured rating climb |
| 📊 **Market Microstructure** | LOB anatomy, price-time priority, L1/L2/L3 feeds, NSE/BSE mechanics — applied as a live trader |

---

### 📊 GitHub Stats

<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Nitinsjiloha&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub Stats" />
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nitinsjiloha&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Nitinsjiloha&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Nitinsjiloha&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8" alt="Trophies" />
</p>

---

### 🧩 Competitive Programming

<p align="center">
  <img src="https://leetcard.jacoblin.cool/nitinsjiloha?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode Stats" />
</p>

<p align="center">
  <b>Codeforces Specialist (~1400)</b> · 150+ problems in C++ · LeetCode 200+ (graphs · DP · binary search · trees)
</p>

---

### 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Nitinsjiloha/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" />
</p>

---

<p align="center">
  <i>⚡ "Make it correct, make it idempotent, then make it fast."</i>
</p>

<!--
  ──────────────────────────────────────────────────────────────────────────
  ENABLE THE SNAKE ANIMATION (optional but slick)
  Create .github/workflows/snake.yml in your profile repo with:

  name: generate snake
  on:
    schedule: [{ cron: "0 */12 * * *" }]
    workflow_dispatch:
    push: { branches: [main] }
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: |
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v4
          with:
            target_branch: output
            build_dir: dist
          env: { GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} }
  ──────────────────────────────────────────────────────────────────────────
-->
