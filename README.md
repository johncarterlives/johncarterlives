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
| Screen time (Mac) | 7h | 44.2h | 199.1h | ~2692h* |
| Interactive human attention | 6.8h | 29.9h | 107.9h | 185.7h |
| Interactive AI generation | 13.7h | 111.5h | 278.1h | 373.7h |
| Worker-classified human attention | 24.0h | 60.4h | 70.6h | 72.3h |
| Worker/headless AI generation | 3.8h | 25.8h | 108.5h | 122.7h |
| Additive observed work | 41.5h | 208.5h | 539.6h | 728.1h |
| Interactive sessions | 13 | 67 | 229 | 374 |
| Worker sessions | 96 | 693 | 1,510 | 1,612 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 162 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 29,242 | 128.1M | 6.6M | 3,915.8M | 96.8% | 321 | 262.1h |
| gpt-5.6-terra | 12,867 | 192.8M | 2.2M | 955.7M | 83.2% | 1,156 | 43.4h |
| gpt-6-astra | 4,480 | 19.2M | 1.2M | 857.3M | 97.8% | 47 | 55.7h |
| gpt-5.6-luna | 993 | 19.7M | 240K | 73.8M | 78.9% | 252 | 24.9h |
| muse-spark-1.3-contributor-free | 44 | 323K | 10K | 5.3M | 94.3% | 2 | 0.1h |
| big-pickle | 42 | 193K | 15K | 3.0M | 94.1% | 1 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **47,700** | **360.7M** | **10.4M** | **5,812.8M** | **94.2%** | **1,719** | **386.7h** |

_6,184.0M total tokens processed. 94.2% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 36,588 | 171.0M | 8.4M | 4,856.7M | 96.6% | 396 | 326.1h |
| gpt-5.6-terra | 12,915 | 194.2M | 2.2M | 959.3M | 83.2% | 1,164 | 43.6h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 94.1% | 127 | 33.4h |
| gpt-6-astra | 4,480 | 19.2M | 1.2M | 857.3M | 97.8% | 47 | 55.7h |
| gpt-5.6-luna | 1,553 | 28.1M | 453K | 132.9M | 82.5% | 274 | 30.1h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0.0% | 5 | 1.1h |
| big-pickle | 44 | 257K | 15K | 3.0M | 92.3% | 3 | 0.2h |
| muse-spark-1.3-contributor-free | 44 | 323K | 10K | 5.3M | 94.3% | 2 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **62,837** | **463.3M** | **14.5M** | **7,534.0M** | **94.2%** | **1,959** | **491.0h** |

_8,012.0M total tokens processed. 94.2% cache hit rate._
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
_Stats auto-updated 2026-09-17 06:12 UTC by [aidevops](https://aidevops.sh) pulse._
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
