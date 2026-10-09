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
| Screen time (Mac) | 14.6h | 39.6h | 123.2h | ~2181h* |
| Interactive human attention | 16.7h | 44.4h | 134.4h | 294.3h |
| Interactive AI generation | 48.1h | 113.9h | 354.9h | 620.3h |
| Worker-classified human attention | 1.7h | 4.5h | 108.6h | 120.5h |
| Worker/headless AI generation | 13.9h | 33.4h | 98.4h | 200.0h |
| Additive observed work | 79.5h | 194.1h | 665.0h | 1,196.8h |
| Interactive sessions | 66 | 118 | 321 | 633 |
| Worker sessions | 465 | 1,391 | 3,518 | 4,540 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 184 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 27,657 | 114.9M | 6.1M | 3,872.5M | 0 | 97.1% | 309 | 209.7h |
| gpt-6.1-sol | 17,878 | 90.6M | 4.1M | 2,086.4M | 0 | 95.8% | 637 | 123.3h |
| gpt-5.6-terra | 8,839 | 215.5M | 1.6M | 660.1M | 0 | 75.4% | 925 | 30.5h |
| gpt-6-luna | 5,147 | 113.4M | 1.1M | 408.5M | 0 | 78.3% | 1,344 | 18.9h |
| gpt-6-astra | 3,897 | 31.9M | 1.4M | 667.8M | 0 | 95.4% | 202 | 59.5h |
| gpt-6-sol | 2,929 | 26.1M | 431K | 233.1M | 0 | 89.9% | 286 | 14.5h |
| gpt-6.1-sol-fast | 2,875 | 10.9M | 894K | 453.1M | 0 | 97.6% | 15 | 31.8h |
| gpt-5.6-luna | 846 | 26.9M | 93K | 56.7M | 0 | 67.8% | 344 | 2.0h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| muse-spark-1.3-contributor-free | 19 | 583K | 13K | 2.3M | 0 | 79.9% | 1 | 0.1h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **70,110** | **631.1M** | **15.9M** | **8,442.2M** | **0** | **93%** | **3,928** | **490.3h** |

_9,089.3M total tokens processed. 93% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 17,878 | 90.6M | 4.1M | 2,086.4M | 0 | 95.8% | 637 | 123.3h |
| gpt-5.6-terra | 16,856 | 284.3M | 3.0M | 1,278.5M | 0 | 81.8% | 1,613 | 57.9h |
| gpt-6-astra | 7,367 | 42.3M | 2.2M | 1,316.7M | 0 | 96.9% | 221 | 83.2h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-luna | 5,147 | 113.4M | 1.1M | 408.5M | 0 | 78.3% | 1,344 | 18.9h |
| gpt-6-sol | 2,929 | 26.1M | 431K | 233.1M | 0 | 89.9% | 286 | 14.5h |
| gpt-6.1-sol-fast | 2,875 | 10.9M | 894K | 453.1M | 0 | 97.6% | 15 | 31.8h |
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
| **Total** | **116,595** | **910.5M** | **27.1M** | **14,113.7M** | **0** | **93.9%** | **5,073** | **837.1h** |

_15,051.3M total tokens processed. 93.9% cache hit rate._
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
_Stats auto-updated 2026-10-09 21:17 UTC by [aidevops](https://aidevops.sh) pulse._
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
