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
| Screen time (Mac) | 24h | 49.5h | 370.6h | ~3237h* |
| Interactive human attention | 5.1h | 47.3h | 159.3h | 409.2h |
| Interactive AI generation | 12.8h | 73.3h | 417.6h | 924.1h |
| Worker-classified human attention | 0.2h | 0.8h | 12.5h | 128.4h |
| Worker/headless AI generation | 2.1h | 16.5h | 117.8h | 284.5h |
| Additive observed work | 19.9h | 137.3h | 700.7h | 1,703.4h |
| Interactive sessions | 24 | 76 | 323 | 837 |
| Worker sessions | 154 | 1,105 | 4,417 | 7,566 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 205 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 34,906 | 190.6M | 7.4M | 3,745.2M | 0 | 95.2% | 1,676 | 199.2h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| claude-opus-5-5 | 10,849 | 22K | 4.5M | 1,817.6M | 83.7M | 95.6% | 22 | 58.0h |
| gpt-6-luna | 9,800 | 218.4M | 2.9M | 783.4M | 0 | 78.2% | 2,714 | 34.3h |
| gpt-6-astra | 6,005 | 25.2M | 1.7M | 865.8M | 0 | 97.2% | 300 | 53.0h |
| gpt-5.6-sol | 4,342 | 12.6M | 951K | 647.6M | 0 | 98.1% | 18 | 26.7h |
| gpt-6-sol | 522 | 2.9M | 67K | 26.7M | 0 | 90.1% | 75 | 1.8h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gpt-5.6-terra | 132 | 1.9M | 19K | 18.1M | 0 | 90.2% | 11 | 0.6h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| claude-sonnet-5-5 | 42 | 98 | 10K | 4.4M | 1.1M | 79.1% | 3 | 0.1h |
| **Total** | **90,623** | **535.4M** | **24.5M** | **11,441.5M** | **84.9M** | **94.9%** | **4,745** | **566.3h** |

_12,086.3M total tokens processed. 94.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 35,049 | 191.9M | 7.4M | 3,755.7M | 0 | 95.1% | 1,693 | 200.1h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,813 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 397 | 128.9h |
| gpt-6-luna | 11,507 | 252.6M | 3.2M | 909.8M | 0 | 78.3% | 3,084 | 41.4h |
| claude-opus-5-5 | 10,849 | 22K | 4.5M | 1,817.6M | 83.7M | 95.6% | 22 | 58.0h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,974 | 26.7M | 437K | 233.2M | 0 | 89.7% | 320 | 14.7h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| studio-glm-5.3-flash | 490 | 1.9M | 105K | 34.2M | 0 | 94.5% | 17 | 1.0h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| claude-sonnet-5-5 | 42 | 98 | 10K | 4.4M | 1.1M | 79.1% | 3 | 0.1h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **177,688** | **1,244.7M** | **44.6M** | **22,004.2M** | **84.9M** | **94.3%** | **8,091** | **1,201.5h** |

_23,378.5M total tokens processed. 94.3% cache hit rate._
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
_Stats auto-updated 2026-10-30 06:31 UTC by [aidevops](https://aidevops.sh) pulse._
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
