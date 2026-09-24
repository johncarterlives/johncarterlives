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
| Screen time (Mac) | 4.4h | 24.6h | 225.2h | ~2477h* |
| Interactive human attention | 5.9h | 32.1h | 127.2h | 211.0h |
| Interactive AI generation | 10.1h | 67.7h | 327.2h | 427.7h |
| Worker-classified human attention | 6.5h | 60.2h | 106.9h | 108.5h |
| Worker/headless AI generation | 3.8h | 19.2h | 123.0h | 138.1h |
| Additive observed work | 23.1h | 166.3h | 652.7h | 853.0h |
| Interactive sessions | 17 | 64 | 262 | 424 |
| Worker sessions | 187 | 757 | 2,160 | 2,272 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 168 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 35,107 | 153.3M | 8.0M | 4,763.8M | 96.9% | 379 | 303.9h |
| gpt-5.6-terra | 15,809 | 269.6M | 2.7M | 1,189.0M | 81.5% | 1,518 | 53.1h |
| gpt-6-astra | 5,612 | 29.3M | 1.7M | 1,104.0M | 97.4% | 58 | 67.5h |
| gpt-5.6-luna | 1,432 | 35.3M | 257K | 108.5M | 75.4% | 439 | 25.6h |
| gpt-6-sol | 278 | 1.9M | 29K | 19.6M | 91.0% | 31 | 1.3h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 89.4% | 3 | 0.2h |
| gpt-6-luna | 49 | 3.2M | 1K | 424K | 11.5% | 48 | 0.1h |
| big-pickle | 42 | 193K | 15K | 3.0M | 94.1% | 1 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **58,424** | **494.2M** | **12.8M** | **7,197.8M** | **93.6%** | **2,399** | **452.1h** |

_7,704.9M total tokens processed. 93.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 43,980 | 205.3M | 10.1M | 5,915.4M | 96.6% | 469 | 375.5h |
| gpt-5.6-terra | 15,928 | 271.9M | 2.8M | 1,196.6M | 81.5% | 1,533 | 53.6h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 94.1% | 127 | 33.4h |
| gpt-6-astra | 5,612 | 29.3M | 1.7M | 1,104.0M | 97.4% | 58 | 67.5h |
| gpt-5.6-luna | 2,137 | 45.5M | 522K | 181.2M | 79.9% | 466 | 31.7h |
| gpt-6-sol | 278 | 1.9M | 29K | 19.6M | 91.0% | 31 | 1.3h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 89.4% | 3 | 0.2h |
| gpt-6-luna | 49 | 3.2M | 1K | 424K | 11.5% | 48 | 0.1h |
| big-pickle | 44 | 257K | 15K | 3.0M | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **75,304** | **608.6M** | **17.4M** | **9,147.3M** | **93.8%** | **2,666** | **565.3h** |

_9,773.5M total tokens processed. 93.8% cache hit rate._
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
_Stats auto-updated 2026-09-24 04:22 UTC by [aidevops](https://aidevops.sh) pulse._
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
