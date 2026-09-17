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
| Screen time (Mac) | 7h | 44.2h | 206.1h | ~2687h* |
| Interactive human attention | 6.8h | 29.9h | 107.9h | 185.7h |
| Interactive AI generation | 13.7h | 111.5h | 278.1h | 373.7h |
| Worker-classified human attention | 24.0h | 60.4h | 70.6h | 72.3h |
| Worker/headless AI generation | 3.8h | 25.8h | 108.5h | 122.7h |
| Additive observed work | 41.5h | 208.5h | 539.6h | 728.1h |
| Interactive sessions | 17 | 71 | 233 | 378 |
| Worker sessions | 125 | 722 | 1,539 | 1,641 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 162 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 29,532 | 129.1M | 6.7M | 3,957.5M | 96.8% | 325 | 263.1h |
| gpt-5.6-terra | 13,088 | 205.6M | 2.2M | 971.1M | 82.5% | 1,180 | 44.2h |
| gpt-6-astra | 4,481 | 19.3M | 1.2M | 857.3M | 97.8% | 47 | 55.7h |
| gpt-5.6-luna | 976 | 20.0M | 227K | 72.1M | 78.3% | 256 | 24.7h |
| muse-spark-1.3-contributor-free | 62 | 709K | 23K | 7.6M | 91.5% | 3 | 0.2h |
| big-pickle | 42 | 193K | 15K | 3.0M | 94.1% | 1 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **48,213** | **375.2M** | **10.5M** | **5,870.5M** | **94%** | **1,751** | **388.3h** |

_6,256.3M total tokens processed. 94% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 36,901 | 172.2M | 8.5M | 4,901.7M | 96.6% | 400 | 327.5h |
| gpt-5.6-terra | 13,136 | 207.0M | 2.3M | 974.8M | 82.5% | 1,188 | 44.4h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 94.1% | 127 | 33.4h |
| gpt-6-astra | 4,481 | 19.3M | 1.2M | 857.3M | 97.8% | 47 | 55.7h |
| gpt-5.6-luna | 1,573 | 28.5M | 455K | 134.3M | 82.5% | 279 | 30.1h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 62 | 709K | 23K | 7.6M | 91.5% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **63,410** | **478.3M** | **14.6M** | **7,598.2M** | **94.1%** | **1,992** | **493.2h** |

_8,091.2M total tokens processed. 94.1% cache hit rate._
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
_Stats auto-updated 2026-09-17 12:37 UTC by [aidevops](https://aidevops.sh) pulse._
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
