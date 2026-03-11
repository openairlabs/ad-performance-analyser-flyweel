# Ad Performance Analyser by Flyweel [SKILL.md]

A Claude Code skill for analysing digital advertising performance across Google Ads, Meta Ads, LinkedIn, TikTok, and multi-channel budgets.

Works with any data source — CSV exports, API responses, dashboard screenshots, or MCP-connected platforms. Applies senior media buying frameworks to turn raw numbers into decisions.

## What It Does

- **Three-tier analysis framework** — 5-minute health check, 15-minute performance review, or 30+ minute deep dive
- **Industry benchmarks** — reference ranges for Google Search, Display, Meta, LinkedIn, and TikTok
- **Seven scenario playbooks** — "Are my ads working?", CPA diagnosis, budget allocation, fatigue detection, real ROAS, and more
- **Reporting templates** — copy-paste weekly and monthly review formats
- **Statistical rigour** — minimum sample sizes, significance checks, and attribution caveats built in
- **Red flag detection** — automatically surfaces zero-conversion spend, concentration risk, fatigue, and tracking issues

## Included Playbooks

| Scenario | What it answers |
|---|---|
| Are my ads working? | Define targets, diagnose CPA/ROAS vs. goal |
| Where to spend more/less? | Marginal CPA ranking and reallocation |
| CPA increased — why? | CPM/CTR/CVR diagnostic tree |
| Google vs Meta budget split | Efficiency + incrementality analysis |
| Campaign fatigue check | Frequency, CTR trend, creative lifecycle |
| Real ROAS calculation | Platform vs. blended vs. CRM revenue |
| Monthly budget planning | 90-day trend modelling with scenarios |

## Installation

```bash
# Auto-detects your agent (Claude Code, Cursor, Windsurf, Gemini, Codex, OpenCode)
npx @flyweel/skill install ad-performance-analyser-flyweel

# Or manually
git clone https://github.com/openairlabs/ad-performance-analyser-flyweel.git ~/.claude/skills/ad-performance-analyser-flyweel
```

## Usage

Works with any advertising data you provide:

```
"Analyse this CSV of Meta Ads data from last month"
"My Google Ads CPA jumped 40% this week — diagnose it"
"Help me plan next month's budget across Google and Meta"
"Is this campaign fatiguing? Here are the last 4 weeks of data..."
"Give me a monthly performance review template"
```

## Benchmarks Included

| Platform | CTR | CPC | CPM |
|---|---|---|---|
| Google Search | 3-6% | $1-5 | — |
| Google Display/PMax | 0.3-1% | $0.30-2 | $2-10 |
| Meta (FB/IG) | 0.8-2% | $0.50-3 | $5-15 |
| LinkedIn | 0.4-0.8% | $5-15 | $30-80 |
| TikTok | 0.5-1.5% | $0.30-2 | $3-10 |

## Built by Flyweel

Originally built by [Flyweel](https://flyweel.co) — we're building the layer connecting spend, revenue, and capital with agentic finance.

## License

MIT
