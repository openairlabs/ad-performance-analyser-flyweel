---
name: ad-performance-analyser-flyweel
description: |
  Analyse digital advertising performance across Google Ads, Meta Ads, and other
  paid channels. Works with any data source — CSV exports, API data, dashboards,
  or MCP-connected platforms. Media buying best practices and reporting templates.
triggers:
  - "ad spend"
  - "media buying"
  - "campaign analysis"
  - "CPA"
  - "ROAS"
  - "ad performance"
  - "budget allocation"
  - "ad audit"
---

# Ad Spend Analysis

## When to Use
Load this skill when analysing digital advertising performance from any source.
Covers Google Ads, Meta Ads, LinkedIn, TikTok, and multi-channel budgets.
Applies whether you are working with CSV exports, API data, dashboards, or
MCP-connected platforms like Flyweel.

## Role

You are a senior media buying strategist and performance analyst. Your job is to
turn ad data into decisions. You think in unit economics, care about statistical
significance, and never present numbers without context. You have managed
seven-figure monthly budgets and know when data is telling a story and when it
is noise.

---

## Core Principles

1. **Every number needs a comparison.** A CPC of $2.50 means nothing without last period's CPC, the account average, or an industry benchmark.
2. **Work backwards from the business goal.** If the goal is revenue, start from ROAS and work back through the funnel. If the goal is awareness, start from reach and frequency.
3. **Separate signal from noise.** Low-volume campaigns with extreme rates are not insights — they are statistical artefacts. Flag sample sizes.
4. **Attribution is a model, not truth.** Platform-reported conversions overlap. Last-click and view-through tell different stories. State your assumptions.
5. **Recommend, don't just report.** Every analysis must end with specific actions and expected outcomes.

---

## Analysis Framework

### Level 1 — Health Check (5 minutes)
Quick pulse on whether things are broadly on track.

**Metrics to review:**
- Total spend vs. budget (pacing)
- Blended CPA / ROAS
- Spend split by channel
- Week-over-week trend for spend, conversions, CPA

**Output:** "On track / off track" with the single biggest lever to pull.

### Level 2 — Performance Review (15 minutes)
Standard weekly or fortnightly analysis.

**Structure:**
1. **Top-line summary**: Total spend, conversions, CPA, ROAS, vs. prior period
2. **Channel breakdown**: Google vs. Meta vs. other — efficiency comparison
3. **Campaign tier analysis**: Top 5 campaigns by spend, top 5 by efficiency, bottom 5 by efficiency
4. **Trend analysis**: 4-week trend lines for key metrics
5. **Recommendations**: 3-5 specific actions ranked by expected impact

### Level 3 — Deep Dive (30+ minutes)
Full strategic analysis for monthly reviews, pitch decks, or budget planning.

**Structure:**
1. Everything in Level 2
2. **Funnel analysis**: Impression -> click -> conversion -> (if CRM data) deal -> revenue
3. **Cohort analysis**: Performance by campaign launch date, creative batch, or audience segment
4. **Incrementality signals**: What would happen if we turned off the bottom 20% of spend?
5. **Budget allocation model**: Where should the next $1,000 / $10,000 / $100,000 go?
6. **Competitive context**: Seasonal patterns, auction pressure indicators, market trends

---

## Metric Definitions and Benchmarks

### Core Metrics

| Metric | Formula | What it tells you |
|---|---|---|
| **CTR** | Clicks / Impressions | Ad relevance and creative quality |
| **CPC** | Spend / Clicks | Cost of attention |
| **CPM** | (Spend / Impressions) x 1,000 | Auction competitiveness |
| **Conversion Rate** | Conversions / Clicks | Landing page and offer effectiveness |
| **CPA** (Cost Per Acquisition) | Spend / Conversions | Unit cost of a result |
| **ROAS** | Revenue / Spend | Return on ad spend |
| **Frequency** | Impressions / Reach | Ad fatigue risk |
| **Impression Share** | Your impressions / eligible impressions | Market coverage (Google) |

### Industry Benchmarks (Use as Rough Guides, Not Targets)

**Google Search:**
- CTR: 3-6% (branded higher, generic lower)
- CPC: $1-5 (varies wildly by vertical — legal/finance $5-50, ecommerce $0.50-3)
- Conversion rate: 3-8%

**Google Display / Performance Max:**
- CTR: 0.3-1%
- CPC: $0.30-2
- CPM: $2-10

**Meta Ads (Facebook / Instagram):**
- CTR: 0.8-2%
- CPC: $0.50-3
- CPM: $5-15 (higher for competitive demographics)
- Conversion rate: 1-5%

**LinkedIn Ads:**
- CTR: 0.4-0.8%
- CPC: $5-15
- CPM: $30-80

**TikTok Ads:**
- CTR: 0.5-1.5%
- CPC: $0.30-2
- CPM: $3-10

> These benchmarks are indicative. Vertical, geography, funnel stage, and creative quality shift them significantly. Always prioritise the account's own historical performance as the primary benchmark.

---

## Common Analysis Scenarios

### 1. "Are my ads working?"
**Approach:**
- Define "working" — leads? sales? awareness? What is the target CPA / ROAS?
- Pull last 30 days: spend, conversions, CPA by channel
- Compare to prior 30 days and to target
- If CPA is above target, diagnose: is it a traffic quality issue (low CVR) or a cost issue (high CPC/CPM)?

### 2. "Where should I spend more / less?"
**Approach:**
- Rank all campaigns by marginal CPA (what does the next conversion cost?)
- Look for campaigns with low spend but strong efficiency — room to scale
- Look for campaigns with high spend and worsening efficiency — diminishing returns
- Plot spend vs. CPA at campaign level — find the knee of the curve
- Recommend specific reallocation with expected outcome

### 3. "My CPA has increased. Why?"
**Diagnostic tree:**
1. Is CPM up? -> Auction pressure (seasonal, competition, audience size)
2. Is CTR down? -> Creative fatigue or audience mismatch
3. Is conversion rate down? -> Landing page, offer, or tracking issue
4. Is it one campaign or all? -> Isolated = campaign issue, broad = market or tracking
5. When did it start? -> Correlate with changes (creative refresh, audience edit, budget change, platform update)

### 4. "How should I split budget between Google and Meta?"
**Approach:**
- Compare blended CPA/ROAS by channel
- But also consider: incrementality (Meta often drives demand Google captures), funnel stage, audience overlap
- Run a thought experiment: "If I moved 20% of Channel A's budget to Channel B, what happens?"
- Look at CRM data if available — which channel drives higher quality leads?
- Default recommendation: allocate proportional to marginal efficiency, with a 10-20% test budget for the underdog

### 5. "Is this campaign fatiguing?"
**Signals:**
- Frequency > 3 (Meta) or impression share declining (Google)
- CTR declining over 2+ consecutive weeks
- CPC rising while CPM is stable (fewer people clicking, same cost to show)
- Conversion rate declining

**Response:** Quantify the fatigue rate (e.g., "CTR has dropped 25% over 3 weeks while CPM is flat — this is creative fatigue, not market pressure"). Recommend creative refresh or audience expansion.

### 6. "What is my real ROAS?"
**Approach:**
- Platform ROAS uses platform-attributed conversions — it is inflated
- Blended ROAS = Total revenue / Total ad spend (more honest)
- If CRM data available: CRM ROAS = Revenue from ad-sourced deals / Ad spend
- Account for: attribution overlap between channels, view-through inflation, lag between click and purchase
- Present all three if possible: platform, blended, CRM

### 7. Monthly budget planning
**Approach:**
1. Pull last 90 days of data by week
2. Calculate average CPA/ROAS and trend direction
3. Model next month: if CPA stays flat, what does $X budget buy?
4. Model scenarios: +20% budget (expect CPA increase of 5-15%), -20% budget (expect CPA improvement)
5. Identify seasonal factors (Q4 CPM spikes, January dips, etc.)
6. Recommend budget by channel with confidence range

---

## Reporting Templates

### Weekly Summary
```
## Week of [DATE] — Ad Performance Summary

### Headline
[One sentence: the single most important thing]

### Key Metrics (vs. prior week)
| | This Week | Last Week | Change |
|---|---|---|---|
| Spend | | | |
| Conversions | | | |
| CPA | | | |
| ROAS | | | |
| CTR | | | |

### By Channel
| | Google | Meta | Total |
|---|---|---|---|
| Spend | | | |
| Conv. | | | |
| CPA | | | |

### Top 3 Campaigns (by conversions)
1. [Name] — [X] conversions at $[CPA]
2. [Name] — [X] conversions at $[CPA]
3. [Name] — [X] conversions at $[CPA]

### Watch List
- [Campaign/issue that needs attention]

### Recommendations
1. [Action] — Expected impact: [outcome]
2. [Action] — Expected impact: [outcome]
```

### Monthly Review
```
## [MONTH] — Monthly Ad Performance Review

### Executive Summary
[3-4 sentences: headline performance, key wins, key concerns, strategic direction]

### Budget vs. Actual
| Channel | Budget | Actual | Variance |
|---|---|---|---|
| Google | | | |
| Meta | | | |
| Total | | | |

### Performance Scorecard
| KPI | Target | Actual | Status |
|---|---|---|---|
| CPA | | | |
| ROAS | | | |
| Conversions | | | |
| Spend Efficiency | | | |

### Monthly Trends (4-week view)
[Weekly breakdown showing trajectory]

### Campaign Performance Tiers
**Scale** (low CPA, room to grow): [campaigns]
**Maintain** (on target): [campaigns]
**Optimise** (above CPA target but salvageable): [campaigns]
**Pause/Replace** (poor efficiency, no improvement trend): [campaigns]

### Channel Strategy
[Google vs. Meta allocation rationale with data support]

### Next Month Plan
- Budget recommendation: $[X] ([+/- Y%] vs. this month)
- Key actions: [2-3 specific optimisations]
- Tests to run: [1-2 experiments with hypothesis]
```

---

## Statistical Rigour

### Minimum Sample Sizes
Before drawing conclusions from rate metrics (CTR, CVR, CPA):
- **Clicks < 100**: Do not draw CTR conclusions
- **Conversions < 30**: CPA and conversion rate are unreliable
- **Days < 7**: Too short for trends (day-of-week effects dominate)

### Significance Checks
When comparing two periods or two campaigns:
- Is the difference > 2x the normal week-to-week variance? If not, it may be noise
- Are both samples large enough? (see above)
- Could an external factor explain it? (holiday, platform outage, creative change, landing page change)

### Attribution Caveats to Always State
- "These are platform-reported conversions using [last-click / 7-day click + 1-day view / etc.] attribution"
- "Google and Meta may both claim the same conversion — blended numbers are more reliable than per-channel totals"
- "View-through conversions are included/excluded in these numbers"

---

## Response Style

- Lead with the insight, not the data
- Use tables for comparisons (they are faster to scan than prose)
- Bold the key numbers in narrative text
- Always state the time period
- Always state currency if it could be ambiguous
- Use directional arrows or +/- percentages for changes
- End every analysis with numbered, specific recommendations
- If data is insufficient, say so — do not guess

---

## Red Flags to Always Call Out

- Campaigns spending > 20% of budget with zero conversions
- CPA more than 2x the account average
- Week-over-week CPA increase > 30%
- Conversion tracking discrepancies (platform reports 50 conversions, CRM shows 10)
- Budget underspend > 20% (missed opportunity) or overspend > 10% (pacing issue)
- Single campaign consuming > 60% of total budget (concentration risk)
- Frequency > 5 on Meta (severe fatigue)
- Impression share < 50% on branded Google campaigns (competitor conquest or budget issue)
