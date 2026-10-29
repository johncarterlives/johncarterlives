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
| Screen time (Mac) | 8h | 49.5h | 354.9h | ~3158h* |
| Interactive human attention | 7.2h | 49.0h | 161.3h | 404.1h |
| Interactive AI generation | 7.5h | 79.6h | 420.0h | 911.3h |
| Worker-classified human attention | 0.1h | 2.6h | 14.0h | 128.2h |
| Worker/headless AI generation | 2.0h | 25.1h | 122.6h | 282.4h |
| Additive observed work | 16.6h | 154.3h | 710.5h | 1,683.4h |
| Interactive sessions | 34 | 72 | 316 | 821 |
| Worker sessions | 189 | 1,151 | 4,469 | 7,451 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 204 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 34,764 | 189.7M | 7.4M | 3,737.0M | 0 | 95.2% | 1,654 | 199.1h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-6-luna | 10,481 | 223.3M | 3.0M | 843.6M | 0 | 79.1% | 2,730 | 38.3h |
| claude-opus-5-5 | 9,076 | 19K | 3.8M | 1,519.6M | 67.9M | 95.7% | 18 | 47.4h |
| gpt-6-astra | 6,797 | 28.7M | 1.9M | 961.8M | 0 | 97.1% | 333 | 58.0h |
| gpt-5.6-sol | 5,859 | 18.0M | 1.3M | 869.6M | 0 | 98.0% | 24 | 36.1h |
| gpt-6-sol | 1,425 | 11.8M | 219K | 105.7M | 0 | 89.9% | 133 | 7.3h |
| gpt-5.6-terra | 132 | 1.9M | 19K | 18.1M | 0 | 90.2% | 11 | 0.6h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| claude-sonnet-5-5 | 38 | 86 | 8K | 4.0M | 783K | 83.8% | 3 | 0.1h |
| studio-glm-5.3-flash | 24 | 1.3M | 5K | 122K | 0 | 8.6% | 5 | 0.3h |
| **Total** | **92,131** | **556.5M** | **24.5M** | **11,557.9M** | **68.7M** | **94.9%** | **4,816** | **578.8h** |

_12,207.8M total tokens processed. 94.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 34,764 | 189.7M | 7.4M | 3,737.0M | 0 | 95.2% | 1,654 | 199.1h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,808 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 395 | 128.6h |
| gpt-6-luna | 11,333 | 247.7M | 3.1M | 904.4M | 0 | 78.5% | 3,016 | 40.9h |
| claude-opus-5-5 | 9,076 | 19K | 3.8M | 1,519.6M | 67.9M | 95.7% | 18 | 47.4h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,974 | 26.7M | 437K | 233.2M | 0 | 89.7% | 320 | 14.7h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| claude-sonnet-5-5 | 38 | 86 | 8K | 4.0M | 783K | 83.8% | 3 | 0.1h |
| studio-glm-5.3-flash | 24 | 1.3M | 5K | 122K | 0 | 8.6% | 5 | 0.3h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **174,981** | **1,236.9M** | **43.6M** | **21,647.5M** | **68.7M** | **94.3%** | **7,969** | **1,188.4h** |

_22,996.7M total tokens processed. 94.3% cache hit rate._
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
_Stats auto-updated 2026-10-29 12:50 UTC by [aidevops](https://aidevops.sh) pulse._
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
