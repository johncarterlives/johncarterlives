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
| Screen time (Mac) | 7.2h | 27.1h | 228.7h | ~2455h* |
| Interactive human attention | 6.2h | 28.5h | 129.3h | 219.8h |
| Interactive AI generation | 10.2h | 58.3h | 331.4h | 441.9h |
| Worker-classified human attention | 0.0h | 26.3h | 106.7h | 108.5h |
| Worker/headless AI generation | 2.3h | 16.0h | 121.1h | 141.6h |
| Additive observed work | 18.8h | 123.9h | 656.9h | 879.4h |
| Interactive sessions | 37 | 75 | 287 | 459 |
| Worker sessions | 174 | 748 | 2,250 | 2,449 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 170 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 37,805 | 167.2M | 8.6M | 5,188.1M | 96.9% | 400 | 319.3h |
| gpt-5.6-terra | 16,348 | 277.0M | 2.9M | 1,233.9M | 81.7% | 1,573 | 56.2h |
| gpt-6-astra | 5,706 | 30.9M | 1.8M | 1,118.1M | 97.3% | 61 | 68.3h |
| gpt-5.6-luna | 1,379 | 34.8M | 241K | 102.6M | 74.7% | 437 | 25.1h |
| gpt-6-sol | 657 | 5.2M | 95K | 55.1M | 91.4% | 74 | 3.4h |
| gpt-6-luna | 637 | 12.3M | 90K | 54.5M | 81.5% | 134 | 2.0h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 89.4% | 3 | 0.2h |
| big-pickle | 42 | 193K | 15K | 3.0M | 94.1% | 1 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **62,669** | **529.0M** | **13.8M** | **7,764.8M** | **93.6%** | **2,601** | **475.0h** |

_8,307.7M total tokens processed. 93.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 47,176 | 222.3M | 10.9M | 6,405.6M | 96.6% | 492 | 394.1h |
| gpt-5.6-terra | 16,706 | 280.2M | 3.0M | 1,263.9M | 81.9% | 1,592 | 57.3h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 94.1% | 127 | 33.4h |
| gpt-6-astra | 5,706 | 30.9M | 1.8M | 1,118.1M | 97.3% | 61 | 68.3h |
| gpt-5.6-luna | 2,137 | 45.5M | 522K | 181.2M | 79.9% | 466 | 31.7h |
| gpt-6-sol | 657 | 5.2M | 95K | 55.1M | 91.4% | 74 | 3.4h |
| gpt-6-luna | 637 | 12.3M | 90K | 54.5M | 81.5% | 134 | 2.0h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **80,339** | **647.9M** | **18.5M** | **9,808.6M** | **93.8%** | **2,876** | **592.4h** |

_10,475.2M total tokens processed. 93.8% cache hit rate._
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
_Stats auto-updated 2026-09-25 20:39 UTC by [aidevops](https://aidevops.sh) pulse._
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
