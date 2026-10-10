# johncarterlives

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 24h | 57.1h | 142.6h | ~2310h* |
| Interactive human attention | 7.4h | 47.7h | 137.0h | 301.7h |
| Interactive AI generation | 20.1h | 119.3h | 366.4h | 640.4h |
| Worker-classified human attention | 0.9h | 3.1h | 107.3h | 121.4h |
| Worker/headless AI generation | 3.9h | 31.7h | 98.1h | 204.0h |
| Additive observed work | 31.5h | 200.2h | 678.9h | 1,228.3h |
| Interactive sessions | 14 | 106 | 309 | 633 |
| Worker sessions | 223 | 1,329 | 3,486 | 4,613 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 185 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 26,145 | 108.2M | 5.8M | 3,690.6M | 0 | 97.2% | 277 | 201.8h |
| gpt-6.1-sol | 18,109 | 92.1M | 4.1M | 2,101.5M | 0 | 95.8% | 663 | 124.0h |
| gpt-5.6-terra | 8,322 | 211.5M | 1.5M | 612.4M | 0 | 74.3% | 905 | 28.6h |
| gpt-6-luna | 5,195 | 115.8M | 1.1M | 408.6M | 0 | 77.9% | 1,391 | 19.0h |
| gpt-6-astra | 3,871 | 31.8M | 1.4M | 665.8M | 0 | 95.4% | 199 | 59.4h |
| gpt-6.1-sol-fast | 2,977 | 11.2M | 917K | 471.5M | 0 | 97.7% | 15 | 32.5h |
| gpt-6-sol | 2,929 | 26.1M | 431K | 233.1M | 0 | 89.9% | 286 | 14.5h |
| gpt-5.6-luna | 800 | 25.7M | 91K | 54.8M | 0 | 68.1% | 322 | 2.0h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| muse-spark-1.3-contributor-free | 19 | 583K | 13K | 2.3M | 0 | 79.9% | 1 | 0.1h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **68,390** | **623.3M** | **15.6M** | **8,242.4M** | **0** | **93%** | **3,927** | **481.9h** |

_8,881.4M total tokens processed. 93% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 18,109 | 92.1M | 4.1M | 2,101.5M | 0 | 95.8% | 663 | 124.0h |
| gpt-5.6-terra | 16,870 | 284.5M | 3.0M | 1,280.5M | 0 | 81.8% | 1,614 | 58.0h |
| gpt-6-astra | 7,382 | 42.5M | 2.3M | 1,319.2M | 0 | 96.9% | 221 | 83.3h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-luna | 5,195 | 115.8M | 1.1M | 408.6M | 0 | 77.9% | 1,391 | 19.0h |
| gpt-6.1-sol-fast | 2,977 | 11.2M | 917K | 471.5M | 0 | 97.7% | 15 | 32.5h |
| gpt-6-sol | 2,929 | 26.1M | 431K | 233.1M | 0 | 89.9% | 286 | 14.5h |
| gpt-5.6-luna | 2,137 | 45.5M | 522K | 181.2M | 0 | 79.9% | 466 | 31.7h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **117,005** | **915.1M** | **27.1M** | **14,151.9M** | **0** | **93.9%** | **5,146** | **838.8h** |

_15,094.2M total tokens processed. 93.9% cache hit rate._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
- **[playwriter](https://github.com/remorses/playwriter)** -- Chrome extension & CLI to let agents control your browser. Runs Playwright snippets in a stateful sandbox. Available as CLI or MCP
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/johncarterlives)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-10-10 10:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/johncarterlives?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="johncarterlives's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/johncarterlives?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
