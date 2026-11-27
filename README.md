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
| Screen time (Mac) | 1.5h | 29.2h | 336.7h | ~3563h* |
| Input activity (Mac) | unavailable | unavailable | unavailable | unavailable |
| Interactive human attention | 3.2h | 26.9h | 109.0h | 518.2h |
| Interactive AI generation | 0.6h | 67.3h | 238.5h | 1162.6h |
| Worker-classified human attention | 0.0h | 0.0h | 0.3h | 128.8h |
| Worker/headless AI generation | 0.2h | 9.7h | 51.8h | 336.3h |
| Additive observed work | 4.0h | 103.9h | 399.6h | 2,102.9h |
| Interactive sessions | 3 | 130 | 1,328 | 2,161 |
| Worker sessions | 6 | 299 | 2,763 | 10,323 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Input activity from macos-input-activity (time from each keyboard, mouse or trackpad input until 5 idle minutes); collection status: unavailable (no-input-activity-samples)._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 233 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5-5 | 40,623 | 86K | 16.3M | 6,144.8M | 312.1M | 95.2% | 966 | 221.8h |
| gpt-6.1-sol | 4,357 | 34.8M | 812K | 356.0M | 0 | 91.1% | 553 | 19.8h |
| gpt-6-luna | 3,021 | 74.8M | 1.2M | 99.4M | 0 | 57.1% | 1,380 | 13.2h |
| claude-fable-5-2 | 2,804 | 5K | 2.0M | 480.1M | 25.5M | 94.9% | 11 | 25.3h |
| claude-sonnet-5-5 | 2,057 | 21K | 1.5M | 137.3M | 27.9M | 83.1% | 657 | 14.7h |
| studio-glm-5.3-flash | 1,114 | 2.4M | 161K | 60.1M | 0 | 96.1% | 43 | 1.5h |
| gpt-6.1-sol-fast | 754 | 3.6M | 251K | 95.0M | 0 | 96.3% | 17 | 3.6h |
| gpt-6.2-astra-fast | 683 | 13.2M | 222K | 77.3M | 0 | 85.4% | 5 | 3.9h |
| claude-haiku-5-5 | 305 | 1K | 933K | 5.6M | 19.3M | 22.7% | 223 | 3.3h |
| gpt-6.2-sol | 87 | 1.8M | 36K | 10.7M | 0 | 85.1% | 2 | 1.0h |
| gpt-6.2-sol-fast | 53 | 1.0M | 26K | 7.5M | 0 | 87.3% | 1 | 0.3h |
| gpt-6-astra | 11 | 56K | 3K | 75K | 0 | 57.3% | 6 | 0.4h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| claude-sonnet-4-6 | 6 | 18 | 9K | 29K | 66K | 30.9% | 6 | 0.1h |
| gpt-6-sol | 6 | 45K | 124 | 0 | 0 | 0.0% | 6 | 0.0h |
| gpt-6.2-astra | 2 | 38K | 415 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **55,892** | **132.4M** | **23.7M** | **7,476.2M** | **385.1M** | **93.5%** | **3,728** | **309.2h** |

_8,017.5M total tokens processed. 93.5% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 54,086 | 245.8M | 12.5M | 7,425.8M | 0 | 96.8% | 519 | 440.4h |
| claude-opus-5-5 | 48,361 | 103K | 19.6M | 7,447.2M | 368.5M | 95.3% | 976 | 262.7h |
| gpt-6.1-sol | 38,449 | 220.7M | 8.1M | 4,031.8M | 0 | 94.8% | 2,153 | 216.5h |
| gpt-6.1-sol-fast | 24,246 | 84.2M | 6.9M | 3,587.5M | 0 | 97.7% | 99 | 195.2h |
| gpt-5.6-terra | 16,886 | 284.7M | 3.0M | 1,283.6M | 0 | 81.8% | 1,615 | 58.0h |
| gpt-6-luna | 14,076 | 316.1M | 4.3M | 987.6M | 0 | 75.7% | 4,292 | 53.4h |
| gpt-6-astra | 12,813 | 62.3M | 3.8M | 2,130.0M | 0 | 97.2% | 397 | 128.9h |
| gpt-5.5 | 7,076 | 45.3M | 2.0M | 717.6M | 0 | 94.1% | 127 | 33.4h |
| gpt-6-sol | 2,980 | 26.8M | 437K | 233.2M | 0 | 89.7% | 326 | 14.7h |
| claude-fable-5-2 | 2,804 | 5K | 2.0M | 480.1M | 25.5M | 94.9% | 11 | 25.3h |
| gpt-5.6-luna | 2,180 | 46.4M | 530K | 186.8M | 0 | 80.1% | 471 | 31.8h |
| claude-sonnet-5-5 | 2,062 | 21K | 1.5M | 137.9M | 28.3M | 83.0% | 657 | 14.7h |
| studio-glm-5.3-flash | 1,117 | 2.5M | 161K | 60.1M | 0 | 95.9% | 44 | 1.5h |
| gpt-6.2-astra-fast | 683 | 13.2M | 222K | 77.3M | 0 | 85.4% | 5 | 3.9h |
| claude-haiku-5-5 | 305 | 1K | 933K | 5.6M | 19.3M | 22.7% | 223 | 3.3h |
| gpt-6.2-sol | 87 | 1.8M | 36K | 10.7M | 0 | 85.1% | 2 | 1.0h |
| gemma4:26b-mlx | 82 | 4.1M | 26K | 0 | 0 | 0.0% | 5 | 1.1h |
| muse-spark-1.3-contributor-free | 63 | 906K | 23K | 7.6M | 0 | 89.4% | 3 | 0.2h |
| gpt-6.2-sol-fast | 53 | 1.0M | 26K | 7.5M | 0 | 87.3% | 1 | 0.3h |
| big-pickle | 44 | 257K | 15K | 3.0M | 0 | 92.3% | 3 | 0.2h |
| qwen3.8-flash | 22 | 87K | 2K | 1.3M | 0 | 93.9% | 1 | 0.1h |
| gemma4-agent | 17 | 314K | 4K | 0 | 0 | 0.0% | 2 | 0.1h |
| gpt-6-sol-fast | 9 | 206K | 4K | 1.6M | 0 | 88.8% | 1 | 0.0h |
| Qwen3.8-27B-oQ6e-mtp:qwen38-q6-stable | 7 | 63K | 1K | 249K | 0 | 79.7% | 1 | 0.3h |
| claude-sonnet-4-6 | 6 | 18 | 9K | 29K | 66K | 30.9% | 6 | 0.1h |
| gemma4-agent-mlx:latest | 6 | 170K | 3K | 0 | 0 | 0.0% | 2 | 0.1h |
| gpt-6.2-astra | 2 | 38K | 415 | 0 | 0 | 0.0% | 1 | 0.0h |
| mtplx-qwen38-27b-optimized-quality | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3.5-lightning-30b-a3b | 1 | 49K | 107 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen/qwen3.8-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **228,525** | **1,357.9M** | **66.6M** | **28,825.2M** | **441.9M** | **94.1%** | **11,527** | **1,487.5h** |

_30,691.7M total tokens processed. 94.1% cache hit rate._
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
_Stats auto-updated 2026-11-27 13:02 UTC by [aidevops](https://aidevops.sh) pulse._
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
