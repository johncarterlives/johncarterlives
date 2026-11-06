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
| Screen time (Mac) | 0h | 67.8h | 398.8h | ~3440h* |
| Interactive human attention | 2.9h | 31.1h | 146.0h | 440.3h |
| Interactive AI generation | 1.8h | 37.3h | 341.0h | 961.4h |
| Worker-classified human attention | 0.0h | 0.2h | 8.2h | 128.6h |
| Worker/headless AI generation | 1.4h | 13.0h | 97.4h | 297.4h |
| Additive observed work | 6.1h | 81.6h | 588.1h | 1,784.9h |
| Interactive sessions | 7 | 50 | 266 | 883 |
| Worker sessions | 199 | 1,005 | 4,177 | 8,565 |

_Screen time from screen-time-history:daily-observations; collection status: stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 212 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 27,399 | 163.1M | 5.4M | 2,817.8M | 0 | 94.5% | 1,547 | 133.7h |
| gpt-6.1-sol-fast | 23,500 | 80.6M | 6.7M | 3,492.9M | 0 | 97.7% | 83 | 191.6h |
| claude-opus-5-5 | 19,428 | 41K | 8.0M | 3,209.0M | 158.0M | 95.3% | 138 | 96.9h |
| gpt-6-luna | 9,062 | 194.6M | 2.9M | 720.5M | 0 | 78.7% | 2,615 | 31.0h |
| gpt-6-astra | 5,777 | 22.7M | 1.6M | 850.1M | 0 | 97.4% | 236 | 49.9h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gpt-5.6-terra | 102 | 1.8M | 15K | 16.2M | 0 | 90.0% | 9 | 0.5h |
| claude-sonnet-5-5 | 75 | 174 | 31K | 6.8M | 1.5M | 81.7% | 8 | 0.3h |
| gpt-6-sol | 62 | 832K | 6K | 438K | 0 | 34.5% | 45 | 0.2h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| claude-haiku-5-5 | 6 | 24 | 37K | 0 | 396K | 0.0% | 2 | 0.2h |
| **Total** | **85,953** | **467.0M** | **25.0M** | **11,155.5M** | **159.9M** | **94.7%** | **4,524** | **505.3h** |

_11,807.6M total tokens processed. 94.7% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 37,654 | 215.4M | 7.8M | 3,962.3M | 0 | 94.8% | 1,964 | 209.7h |
| gpt-6.1-sol-fast | 23,500 | 80.6M | 6.7M | 3,492.9M | 0 | 97.7% | 83 | 191.6h |
| claude-opus-5-5 | 19,428 | 41K | 8.0M | 3,209.0M | 158.0M | 95.3% | 138 | 96.9h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,813 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 397 | 128.9h |
| gpt-6-luna | 12,360 | 283.5M | 3.5M | 919.3M | 0 | 76.4% | 3,667 | 44.6h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,977 | 26.7M | 437K | 233.2M | 0 | 89.7% | 323 | 14.7h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| claude-sonnet-5-5 | 75 | 174 | 31K | 6.8M | 1.5M | 81.7% | 8 | 0.3h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| claude-haiku-5-5 | 6 | 24 | 37K | 0 | 396K | 0.0% | 2 | 0.2h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **189,784** | **1,299.4M** | **48.9M** | **23,616.2M** | **159.9M** | **94.2%** | **9,041** | **1,253.5h** |

_25,124.5M total tokens processed. 94.2% cache hit rate._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
- **[opendesk](https://github.com/useopendesk/opendesk)** -- The open-source support inbox + live chat and inbox collaboration for teams
- **[playwriter](https://github.com/remorses/playwriter)** -- Chrome extension & CLI to let agents control your browser. Runs Playwright snippets in a stateful sandbox. Available as CLI or MCP
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/johncarterlives)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-11-06 21:36 UTC by [aidevops](https://aidevops.sh) pulse._
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
