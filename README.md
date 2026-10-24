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
| Screen time (Mac) | 24h | 131.6h | 338.2h | ~3310h* |
| Interactive human attention | 6.8h | 35.6h | 142.0h | 361.9h |
| Interactive AI generation | 19.1h | 136.3h | 408.9h | 850.8h |
| Worker-classified human attention | 2.0h | 2.1h | 19.1h | 127.6h |
| Worker/headless AI generation | 10.7h | 45.6h | 126.4h | 268.0h |
| Additive observed work | 36.9h | 217.8h | 686.6h | 1,566.0h |
| Interactive sessions | 25 | 62 | 340 | 774 |
| Worker sessions | 302 | 1,247 | 4,230 | 6,602 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 198 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 31,862 | 170.2M | 7.0M | 3,499.3M | 0 | 95.4% | 1,397 | 190.1h |
| gpt-6.1-sol-fast | 23,315 | 79.4M | 6.6M | 3,470.9M | 0 | 97.8% | 80 | 191.1h |
| gpt-6-luna | 10,413 | 211.5M | 2.7M | 881.8M | 0 | 80.7% | 2,438 | 38.3h |
| gpt-5.6-sol | 10,106 | 40.4M | 2.3M | 1,510.4M | 0 | 97.4% | 52 | 64.8h |
| gpt-6-astra | 7,147 | 32.8M | 2.0M | 1,021.9M | 0 | 96.9% | 318 | 60.4h |
| gpt-6-sol | 2,723 | 25.1M | 410K | 214.9M | 0 | 89.5% | 295 | 13.5h |
| gpt-5.6-terra | 958 | 12.7M | 224K | 87.0M | 0 | 87.2% | 84 | 4.4h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| **Total** | **86,567** | **573.4M** | **21.5M** | **10,692.1M** | **0** | **94.9%** | **4,497** | **562.7h** |

_11,287.1M total tokens processed. 94.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 31,862 | 170.2M | 7.0M | 3,499.3M | 0 | 95.4% | 1,397 | 190.1h |
| gpt-6.1-sol-fast | 23,315 | 79.4M | 6.6M | 3,470.9M | 0 | 97.8% | 80 | 191.1h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,759 | 62.1M | 3.8M | 2,125.9M | 0 | 97.2% | 376 | 128.0h |
| gpt-6-luna | 10,455 | 214.3M | 2.7M | 882.1M | 0 | 80.5% | 2,480 | 38.4h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,974 | 26.7M | 437K | 233.2M | 0 | 89.7% | 320 | 14.7h |
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
| **Total** | **161,837** | **1,181.3M** | **38.9M** | **19,838.1M** | **0** | **94.4%** | **7,147** | **1,127.9h** |

_21,058.4M total tokens processed. 94.4% cache hit rate._
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
_Stats auto-updated 2026-10-24 00:28 UTC by [aidevops](https://aidevops.sh) pulse._
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
