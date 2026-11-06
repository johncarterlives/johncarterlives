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
| Interactive sessions | 6 | 49 | 265 | 882 |
| Worker sessions | 165 | 971 | 4,143 | 8,531 |

_Screen time from screen-time-history:daily-observations; collection status: stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 212 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 29,266 | 170.4M | 5.9M | 3,082.0M | 0 | 94.8% | 1,581 | 147.7h |
| gpt-6.1-sol-fast | 23,500 | 80.6M | 6.7M | 3,492.9M | 0 | 97.7% | 83 | 191.6h |
| claude-opus-5-5 | 19,122 | 40K | 7.9M | 3,167.6M | 156.2M | 95.3% | 127 | 95.9h |
| gpt-6-luna | 9,204 | 198.5M | 2.9M | 731.6M | 0 | 78.7% | 2,646 | 31.4h |
| gpt-6-astra | 5,793 | 22.9M | 1.6M | 850.2M | 0 | 97.4% | 244 | 50.4h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gpt-5.6-terra | 102 | 1.8M | 15K | 16.2M | 0 | 90.0% | 9 | 0.5h |
| claude-sonnet-5-5 | 75 | 174 | 31K | 6.8M | 1.5M | 81.7% | 8 | 0.3h |
| gpt-6-sol | 68 | 894K | 7K | 467K | 0 | 34.3% | 49 | 0.3h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| claude-haiku-5-5 | 4 | 16 | 24K | 0 | 271K | 0.0% | 1 | 0.1h |
| **Total** | **87,676** | **478.4M** | **25.4M** | **11,389.5M** | **158.0M** | **94.7%** | **4,586** | **519.3h** |

_12,051.5M total tokens processed. 94.7% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 37,654 | 215.4M | 7.8M | 3,962.3M | 0 | 94.8% | 1,964 | 209.7h |
| gpt-6.1-sol-fast | 23,500 | 80.6M | 6.7M | 3,492.9M | 0 | 97.7% | 83 | 191.6h |
| claude-opus-5-5 | 19,122 | 40K | 7.9M | 3,167.6M | 156.2M | 95.3% | 127 | 95.9h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,813 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 397 | 128.9h |
| gpt-6-luna | 12,340 | 282.9M | 3.5M | 919.3M | 0 | 76.5% | 3,648 | 44.5h |
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
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| claude-haiku-5-5 | 4 | 16 | 24K | 0 | 271K | 0.0% | 1 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **189,456** | **1,298.7M** | **48.7M** | **23,574.7M** | **158.0M** | **94.2%** | **9,011** | **1,252.5h** |

_25,080.3M total tokens processed. 94.2% cache hit rate._
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
_Stats auto-updated 2026-11-06 15:30 UTC by [aidevops](https://aidevops.sh) pulse._
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
