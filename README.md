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
| Screen time (Mac) | 4.2h | 28.8h | 227.4h | ~2450h* |
| Interactive human attention | 2.6h | 27.9h | 128.1h | 213.7h |
| Interactive AI generation | 3.9h | 57.9h | 327.3h | 431.6h |
| Worker-classified human attention | 0.0h | 36.2h | 106.9h | 108.5h |
| Worker/headless AI generation | 1.1h | 16.6h | 122.6h | 139.2h |
| Additive observed work | 7.6h | 132.5h | 653.2h | 860.7h |
| Interactive sessions | 9 | 56 | 263 | 425 |
| Worker sessions | 90 | 683 | 2,164 | 2,287 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 169 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 35,107 | 153.3M | 8.0M | 4,763.8M | 96.9% | 379 | 303.9h |
| gpt-5.6-terra | 15,814 | 269.7M | 2.7M | 1,189.2M | 81.5% | 1,519 | 53.1h |
| gpt-6-astra | 5,612 | 29.3M | 1.7M | 1,104.0M | 97.4% | 58 | 67.5h |
| gpt-5.6-luna | 1,432 | 35.3M | 257K | 108.5M | 75.4% | 439 | 25.6h |
| gpt-6-sol | 308 | 2.3M | 32K | 21.0M | 90.0% | 38 | 1.4h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 89.4% | 3 | 0.2h |
| gpt-6-luna | 56 | 3.7M | 1K | 453K | 10.8% | 55 | 0.1h |
| big-pickle | 42 | 193K | 15K | 3.0M | 94.1% | 1 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **58,466** | **495.1M** | **12.8M** | **7,199.4M** | **93.6%** | **2,414** | **452.3h** |

_7,707.5M total tokens processed. 93.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 43,980 | 205.3M | 10.1M | 5,915.4M | 96.6% | 469 | 375.5h |
| gpt-5.6-terra | 15,933 | 272.0M | 2.8M | 1,196.8M | 81.5% | 1,534 | 53.7h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 94.1% | 127 | 33.4h |
| gpt-6-astra | 5,612 | 29.3M | 1.7M | 1,104.0M | 97.4% | 58 | 67.5h |
| gpt-5.6-luna | 2,137 | 45.5M | 522K | 181.2M | 79.9% | 466 | 31.7h |
| gpt-6-sol | 308 | 2.3M | 32K | 21.0M | 90.0% | 38 | 1.4h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 89.4% | 3 | 0.2h |
| gpt-6-luna | 56 | 3.7M | 1K | 453K | 10.8% | 55 | 0.1h |
| big-pickle | 44 | 257K | 15K | 3.0M | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **75,346** | **609.6M** | **17.4M** | **9,149.0M** | **93.8%** | **2,681** | **565.4h** |

_9,776.1M total tokens processed. 93.8% cache hit rate._
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
_Stats auto-updated 2026-09-24 09:08 UTC by [aidevops](https://aidevops.sh) pulse._
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
