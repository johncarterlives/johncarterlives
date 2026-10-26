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
| Screen time (Mac) | 0h | 84.3h | 346.9h | ~3356h* |
| Interactive human attention | 6.2h | 43.6h | 153.9h | 380.9h |
| Interactive AI generation | 5.9h | 115.8h | 427.0h | 883.9h |
| Worker-classified human attention | 0.0h | 2.6h | 18.3h | 128.1h |
| Worker/headless AI generation | 1.2h | 39.4h | 129.3h | 275.9h |
| Additive observed work | 13.3h | 199.5h | 719.5h | 1,626.4h |
| Interactive sessions | 5 | 67 | 326 | 787 |
| Worker sessions | 216 | 1,187 | 4,387 | 6,996 |

_Screen time from screen-time-history:daily-observations; collection status: ok, stale. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 201 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 32,832 | 178.1M | 7.1M | 3,581.0M | 0 | 95.3% | 1,510 | 193.5h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-6-luna | 10,091 | 214.9M | 2.8M | 827.6M | 0 | 79.4% | 2,570 | 37.2h |
| gpt-6-astra | 6,841 | 29.3M | 1.9M | 971.0M | 0 | 97.1% | 329 | 58.2h |
| gpt-5.6-sol | 6,632 | 22.4M | 1.5M | 974.8M | 0 | 97.8% | 28 | 45.1h |
| claude-opus-5-5 | 4,618 | 9K | 1.8M | 782.3M | 26.6M | 96.7% | 11 | 22.0h |
| gpt-6-sol | 2,092 | 19.6M | 307K | 151.6M | 0 | 88.5% | 227 | 10.1h |
| gpt-5.6-terra | 144 | 2.7M | 21K | 18.5M | 0 | 87.3% | 13 | 0.6h |
| gpt-5.6-luna | 43 | 947K | 7K | 5.6M | 0 | 85.6% | 5 | 0.1h |
| studio-glm-5.3-flash | 3 | 143K | 379 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **86,788** | **548.9M** | **22.4M** | **10,805.1M** | **26.6M** | **94.9%** | **4,597** | **558.5h** |

_11,403.1M total tokens processed. 94.9% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| gpt-6.1-sol | 32,832 | 178.1M | 7.1M | 3,581.0M | 0 | 95.3% | 1,510 | 193.5h |
| gpt-6.1-sol-fast | 23,492 | 80.5M | 6.7M | 3,492.4M | 0 | 97.7% | 82 | 191.6h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-astra | 12,799 | 62.2M | 3.8M | 2,129.9M | 0 | 97.2% | 389 | 128.5h |
| gpt-6-luna | 10,762 | 229.7M | 2.9M | 882.8M | 0 | 79.4% | 2,733 | 39.3h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| claude-opus-5-5 | 4,618 | 9K | 1.8M | 782.3M | 26.6M | 96.7% | 11 | 22.0h |
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
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **167,952** | **1,205.9M** | **41.2M** | **20,728.3M** | **26.6M** | **94.4%** | **7,529** | **1,155.3h** |

_22,002.1M total tokens processed. 94.4% cache hit rate._
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
_Stats auto-updated 2026-10-26 14:52 UTC by [aidevops](https://aidevops.sh) pulse._
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
