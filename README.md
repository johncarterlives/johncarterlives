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
| Screen time (Mac) | 6.8h | 33.3h | 122.2h | ~2116h* |
| Interactive human attention | 15.0h | 34.9h | 121.8h | 277.6h |
| Interactive AI generation | 21.2h | 81.0h | 310.1h | 572.3h |
| Worker-classified human attention | 0.0h | 4.6h | 106.9h | 118.7h |
| Worker/headless AI generation | 3.9h | 26.3h | 89.2h | 186.1h |
| Additive observed work | 40.2h | 144.3h | 597.6h | 1,117.2h |
| Interactive sessions | 24 | 71 | 269 | 576 |
| Worker sessions | 246 | 1,127 | 3,190 | 4,109 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 183 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 31,002 | 127.4M | 6.7M | 4,332.8M | 0 | 97.1% | 338 | 240.7h |
| gpt-6.1-sol | 11,156 | 58.3M | 2.5M | 1,257.6M | 0 | 95.6% | 456 | 80.6h |
| gpt-5.6-terra | 9,870 | 222.3M | 1.8M | 729.4M | 0 | 76.6% | 978 | 34.0h |
| gpt-6-astra | 4,766 | 31.7M | 1.5M | 890.4M | 0 | 96.6% | 154 | 61.1h |
| gpt-6-luna | 3,383 | 93.1M | 684K | 201.3M | 0 | 68.4% | 1,110 | 13.8h |
| gpt-6-sol | 2,915 | 25.9M | 430K | 232.8M | 0 | 90.0% | 278 | 14.4h |
| gpt-5.6-luna | 921 | 28.4M | 102K | 59.7M | 0 | 67.8% | 367 | 2.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| muse-spark-1.3-contributor-free | 19 | 583K | 13K | 2.3M | 0 | 79.9% | 1 | 0.1h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **64,055** | **588.1M** | **14.0M** | **7,707.9M** | **0** | **92.9%** | **3,576** | **447.1h** |

_8,310.1M total tokens processed. 92.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-5.6-terra | 16,784 | 282.9M | 3.0M | 1,267.4M | 0 | 81.8% | 1,606 | 57.5h |
| gpt-6.1-sol | 11,156 | 58.3M | 2.5M | 1,257.6M | 0 | 95.6% | 456 | 80.6h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-astra | 7,042 | 39.6M | 2.1M | 1,280.0M | 0 | 97.0% | 166 | 79.2h |
| gpt-6-luna | 3,383 | 93.1M | 684K | 201.3M | 0 | 68.4% | 1,110 | 13.8h |
| gpt-6-sol | 2,915 | 25.9M | 430K | 232.8M | 0 | 90.0% | 278 | 14.4h |
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
| **Total** | **104,823** | **842.6M** | **24.0M** | **12,576.4M** | **0** | **93.7%** | **4,611** | **753.3h** |

_13,443.1M total tokens processed. 93.7% cache hit rate._
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
_Stats auto-updated 2026-10-08 11:18 UTC by [aidevops](https://aidevops.sh) pulse._
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
