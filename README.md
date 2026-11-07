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
| Screen time (Mac) | 0h | 43.8h | 374.8h | ~3440h* |
| Interactive human attention | 0.2h | 21.3h | 138.8h | 440.5h |
| Interactive AI generation | 1.2h | 28.9h | 322.2h | 962.6h |
| Worker-classified human attention | 0.0h | 0.2h | 7.2h | 128.6h |
| Worker/headless AI generation | 1.5h | 12.5h | 94.9h | 298.9h |
| Additive observed work | 2.9h | 62.9h | 559.5h | 1,787.8h |
| Interactive sessions | 7 | 49 | 259 | 886 |
| Worker sessions | 175 | 972 | 4,076 | 8,663 |

_Screen time from screen-time-history:daily-observations; collection status: stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 213 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 24,394 | 147.5M | 4.7M | 2,413.1M | 0 | 94.2% | 1,478 | 112.4h |
| gpt-6.1-sol-fast | 23,500 | 80.6M | 6.7M | 3,492.9M | 0 | 97.7% | 83 | 191.6h |
| claude-opus-5-5 | 20,145 | 42K | 8.3M | 3,302.0M | 161.8M | 95.3% | 172 | 99.4h |
| gpt-6-luna | 8,482 | 187.7M | 2.7M | 653.1M | 0 | 77.7% | 2,576 | 29.2h |
| gpt-6-astra | 5,681 | 21.9M | 1.6M | 842.6M | 0 | 97.5% | 216 | 48.6h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| claude-sonnet-5-5 | 93 | 214 | 37K | 7.7M | 1.6M | 82.2% | 10 | 0.3h |
| gpt-5.6-terra | 92 | 1.6M | 14K | 15.1M | 0 | 90.1% | 8 | 0.5h |
| gpt-6-sol | 56 | 725K | 6K | 167K | 0 | 18.8% | 43 | 0.2h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| claude-haiku-5-5 | 8 | 32 | 48K | 0 | 565K | 0.0% | 4 | 0.2h |
| **Total** | **82,993** | **443.4M** | **24.3M** | **10,768.4M** | **164.0M** | **94.7%** | **4,436** | **483.5h** |

_11,400.2M total tokens processed. 94.7% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 37,654 | 215.4M | 7.8M | 3,962.3M | 0 | 94.8% | 1,964 | 209.7h |
| gpt-6.1-sol-fast | 23,500 | 80.6M | 6.7M | 3,492.9M | 0 | 97.7% | 83 | 191.6h |
| claude-opus-5-5 | 20,145 | 42K | 8.3M | 3,302.0M | 161.8M | 95.3% | 172 | 99.4h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,813 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 397 | 128.9h |
| gpt-6-luna | 12,417 | 285.2M | 3.5M | 919.4M | 0 | 76.3% | 3,724 | 44.8h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,977 | 26.7M | 437K | 233.2M | 0 | 89.7% | 323 | 14.7h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| claude-sonnet-5-5 | 93 | 214 | 37K | 7.7M | 1.6M | 82.2% | 10 | 0.3h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| claude-haiku-5-5 | 8 | 32 | 48K | 0 | 565K | 0.0% | 4 | 0.2h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **190,578** | **1,301.1M** | **49.1M** | **23,710.0M** | **164.0M** | **94.2%** | **9,134** | **1,256.3h** |

_25,224.3M total tokens processed. 94.2% cache hit rate._
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
_Stats auto-updated 2026-11-07 16:21 UTC by [aidevops](https://aidevops.sh) pulse._
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
