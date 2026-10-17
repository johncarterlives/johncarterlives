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
| Screen time (Mac) | 24h | 150h | 257.4h | ~2975h* |
| Interactive human attention | 8.0h | 32.6h | 141.0h | 334.2h |
| Interactive AI generation | 12.5h | 86.5h | 341.2h | 726.9h |
| Worker-classified human attention | 0.0h | 4.1h | 31.7h | 125.5h |
| Worker/headless AI generation | 3.0h | 21.5h | 98.6h | 225.4h |
| Additive observed work | 23.5h | 143.4h | 600.5h | 1,371.6h |
| Interactive sessions | 9 | 96 | 335 | 725 |
| Worker sessions | 209 | 975 | 3,789 | 5,564 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 192 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 24,296 | 131.9M | 5.4M | 2,708.9M | 0 | 95.4% | 1,024 | 157.6h |
| gpt-5.6-sol | 16,912 | 72.2M | 3.9M | 2,487.7M | 0 | 97.2% | 119 | 111.2h |
| gpt-6.1-sol-fast | 12,581 | 44.0M | 3.5M | 1,890.8M | 0 | 97.7% | 46 | 94.0h |
| gpt-6-luna | 6,671 | 155.0M | 1.5M | 507.6M | 0 | 76.6% | 1,918 | 23.2h |
| gpt-6-astra | 3,921 | 27.5M | 1.3M | 598.1M | 0 | 95.6% | 254 | 35.2h |
| gpt-5.6-terra | 3,592 | 73.9M | 730K | 293.3M | 0 | 79.9% | 428 | 13.3h |
| gpt-6-sol | 2,950 | 26.6M | 435K | 233.2M | 0 | 89.8% | 303 | 14.6h |
| gpt-5.6-luna | 519 | 16.4M | 60K | 42.7M | 0 | 72.2% | 182 | 1.4h |
| **Total** | **71,442** | **547.8M** | **16.9M** | **8,762.6M** | **0** | **94.1%** | **4,131** | **450.4h** |

_9,327.4M total tokens processed. 94.1% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 24,296 | 131.9M | 5.4M | 2,708.9M | 0 | 95.4% | 1,024 | 157.6h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6.1-sol-fast | 12,581 | 44.0M | 3.5M | 1,890.8M | 0 | 97.7% | 46 | 94.0h |
| gpt-6-astra | 8,510 | 47.6M | 2.6M | 1,478.0M | 0 | 96.9% | 300 | 91.7h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-luna | 6,671 | 155.0M | 1.5M | 507.6M | 0 | 76.6% | 1,918 | 23.2h |
| gpt-6-sol | 2,950 | 26.6M | 435K | 233.2M | 0 | 89.8% | 303 | 14.6h |
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
| **Total** | **135,437** | **1,032.7M** | **31.8M** | **16,439.5M** | **0** | **94.1%** | **6,124** | **946.7h** |

_17,504.1M total tokens processed. 94.1% cache hit rate._
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
_Stats auto-updated 2026-10-17 16:26 UTC by [aidevops](https://aidevops.sh) pulse._
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
