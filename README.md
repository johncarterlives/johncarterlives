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
| Screen time (Mac) | 24h | 80h | 409.6h | ~3389h* |
| Interactive human attention | 0.8h | 45.2h | 163.4h | 419.9h |
| Interactive AI generation | 2.1h | 57.8h | 401.2h | 935.8h |
| Worker-classified human attention | 0.2h | 0.6h | 9.9h | 128.6h |
| Worker/headless AI generation | 1.7h | 13.5h | 112.4h | 288.2h |
| Additive observed work | 4.8h | 116.6h | 681.7h | 1,729.6h |
| Interactive sessions | 5 | 66 | 317 | 847 |
| Worker sessions | 164 | 1,079 | 4,453 | 7,857 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 207 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 34,660 | 193.1M | 7.4M | 3,737.0M | 0 | 95.1% | 1,683 | 197.1h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| claude-opus-5-5 | 13,430 | 28K | 5.6M | 2,264.9M | 105.1M | 95.6% | 31 | 69.2h |
| gpt-6-luna | 9,463 | 215.3M | 2.9M | 763.1M | 0 | 78.0% | 2,739 | 32.6h |
| gpt-6-astra | 5,927 | 24.6M | 1.7M | 858.2M | 0 | 97.2% | 281 | 52.4h |
| gpt-5.6-sol | 765 | 2.6M | 180K | 106.9M | 0 | 97.5% | 7 | 4.4h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gpt-5.6-terra | 102 | 1.8M | 15K | 16.2M | 0 | 90.0% | 9 | 0.5h |
| gpt-6-sol | 71 | 914K | 7K | 467K | 0 | 33.9% | 52 | 0.3h |
| claude-sonnet-5-5 | 59 | 136 | 15K | 5.8M | 1.3M | 81.1% | 5 | 0.2h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| **Total** | **88,511** | **522.3M** | **24.7M** | **11,286.8M** | **106.5M** | **94.7%** | **4,735** | **549.3h** |

_11,940.5M total tokens processed. 94.7% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 35,944 | 200.9M | 7.6M | 3,829.0M | 0 | 95.0% | 1,788 | 203.4h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| claude-opus-5-5 | 13,430 | 28K | 5.6M | 2,264.9M | 105.1M | 95.6% | 31 | 69.2h |
| gpt-6-astra | 12,813 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 397 | 128.9h |
| gpt-6-luna | 11,719 | 262.7M | 3.3M | 910.4M | 0 | 77.6% | 3,256 | 42.0h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,977 | 26.7M | 437K | 233.2M | 0 | 89.7% | 323 | 14.7h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| claude-sonnet-5-5 | 59 | 136 | 15K | 5.8M | 1.3M | 81.1% | 5 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **181,405** | **1,263.9M** | **45.9M** | **22,528.5M** | **106.5M** | **94.3%** | **8,362** | **1,216.7h** |

_23,945.0M total tokens processed. 94.3% cache hit rate._
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
_Stats auto-updated 2026-11-01 06:11 UTC by [aidevops](https://aidevops.sh) pulse._
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
