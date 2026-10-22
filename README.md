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
| Screen time (Mac) | 24h | 131.6h | 321.4h | ~3223h* |
| Interactive human attention | 5.2h | 34.8h | 141.4h | 355.0h |
| Interactive AI generation | 25.7h | 127.6h | 400.0h | 831.7h |
| Worker-classified human attention | 0.1h | 3.9h | 17.1h | 125.6h |
| Worker/headless AI generation | 6.9h | 37.5h | 118.1h | 257.3h |
| Additive observed work | 37.9h | 202.9h | 668.4h | 1,529.1h |
| Interactive sessions | 17 | 57 | 339 | 761 |
| Worker sessions | 224 | 1,166 | 4,095 | 6,369 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 197 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 30,474 | 161.6M | 6.7M | 3,364.0M | 0 | 95.4% | 1,309 | 185.0h |
| gpt-6.1-sol-fast | 20,129 | 69.1M | 5.6M | 3,006.0M | 0 | 97.8% | 68 | 172.0h |
| gpt-5.6-sol | 11,188 | 44.8M | 2.5M | 1,673.3M | 0 | 97.4% | 59 | 71.9h |
| gpt-6-luna | 10,288 | 205.5M | 2.6M | 880.8M | 0 | 81.1% | 2,363 | 37.8h |
| gpt-6-astra | 6,624 | 31.0M | 1.9M | 953.9M | 0 | 96.8% | 298 | 54.3h |
| gpt-6-sol | 2,969 | 26.7M | 437K | 233.2M | 0 | 89.7% | 316 | 14.6h |
| gpt-5.6-terra | 1,295 | 17.7M | 330K | 110.7M | 0 | 86.2% | 125 | 5.7h |
| gpt-5.6-luna | 53 | 1.6M | 7K | 5.7M | 0 | 78.0% | 15 | 0.1h |
| **Total** | **83,020** | **558.3M** | **20.4M** | **10,227.9M** | **0** | **94.8%** | **4,392** | **541.4h** |

_10,806.7M total tokens processed. 94.8% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 30,474 | 161.6M | 6.7M | 3,364.0M | 0 | 95.4% | 1,309 | 185.0h |
| gpt-6.1-sol-fast | 20,129 | 69.1M | 5.6M | 3,006.0M | 0 | 97.8% | 68 | 172.0h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,105 | 59.6M | 3.6M | 2,035.6M | 0 | 97.2% | 352 | 120.6h |
| gpt-6-luna | 10,288 | 205.5M | 2.6M | 880.8M | 0 | 81.1% | 2,363 | 37.8h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,969 | 26.7M | 437K | 233.2M | 0 | 89.7% | 316 | 14.6h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
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
| **Total** | **156,437** | **1,151.1M** | **37.4M** | **19,146.3M** | **0** | **94.3%** | **6,914** | **1,095.8h** |

_20,334.9M total tokens processed. 94.3% cache hit rate._
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
_Stats auto-updated 2026-10-22 17:32 UTC by [aidevops](https://aidevops.sh) pulse._
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
