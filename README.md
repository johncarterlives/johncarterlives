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
| Screen time (Mac) | 0h | 83.9h | 346.9h | ~3356h* |
| Interactive human attention | 8.5h | 45.4h | 159.4h | 389.4h |
| Interactive AI generation | 10.9h | 107.2h | 429.8h | 894.8h |
| Worker-classified human attention | 0.0h | 2.6h | 17.8h | 128.1h |
| Worker/headless AI generation | 2.1h | 37.0h | 129.8h | 278.0h |
| Additive observed work | 21.5h | 190.3h | 728.0h | 1,647.9h |
| Interactive sessions | 9 | 54 | 327 | 791 |
| Worker sessions | 229 | 1,181 | 4,472 | 7,165 |

_Screen time from screen-time-history:daily-observations; collection status: stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 202 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 33,228 | 181.2M | 7.2M | 3,607.6M | 0 | 95.2% | 1,556 | 194.7h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-6-luna | 10,247 | 218.3M | 2.9M | 832.5M | 0 | 79.2% | 2,632 | 37.7h |
| gpt-6-astra | 6,839 | 29.2M | 1.9M | 970.7M | 0 | 97.1% | 329 | 58.2h |
| gpt-5.6-sol | 6,600 | 22.2M | 1.5M | 971.2M | 0 | 97.8% | 28 | 45.0h |
| claude-opus-5-5 | 6,411 | 13K | 2.6M | 1,078.8M | 44.4M | 96.0% | 15 | 32.7h |
| gpt-6-sol | 1,986 | 18.4M | 298K | 146.0M | 0 | 88.8% | 205 | 9.6h |
| gpt-5.6-terra | 137 | 2.6M | 21K | 18.1M | 0 | 87.3% | 12 | 0.6h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| studio-glm-5.3-flash | 3 | 143K | 379 | 0 | 0 | 0.0% | 1 | 0.0h |
| claude-sonnet-5-5 | 2 | 6 | 755 | 186K | 186K | 49.9% | 1 | 0.0h |
| **Total** | **88,988** | **553.7M** | **23.2M** | **11,123.5M** | **44.6M** | **94.9%** | **4,683** | **570.3h** |

_11,745.2M total tokens processed. 94.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 33,228 | 181.2M | 7.2M | 3,607.6M | 0 | 95.2% | 1,556 | 194.7h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,800 | 62.2M | 3.8M | 2,129.9M | 0 | 97.2% | 390 | 128.5h |
| gpt-6-luna | 10,960 | 236.4M | 3.0M | 887.9M | 0 | 79.0% | 2,837 | 39.9h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| claude-opus-5-5 | 6,411 | 13K | 2.6M | 1,078.8M | 44.4M | 96.0% | 15 | 32.7h |
| gpt-6-sol | 2,974 | 26.7M | 437K | 233.2M | 0 | 89.7% | 320 | 14.7h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| studio-glm-5.3-flash | 3 | 143K | 379 | 0 | 0 | 0.0% | 1 | 0.0h |
| claude-sonnet-5-5 | 2 | 6 | 755 | 186K | 186K | 49.9% | 1 | 0.0h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **170,342** | **1,215.8M** | **42.0M** | **21,056.8M** | **44.6M** | **94.4%** | **7,681** | **1,167.8h** |

_22,359.3M total tokens processed. 94.4% cache hit rate._
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
_Stats auto-updated 2026-10-27 16:50 UTC by [aidevops](https://aidevops.sh) pulse._
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
