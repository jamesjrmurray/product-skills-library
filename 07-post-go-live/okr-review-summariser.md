---
name: okr-review-summariser
stage: 07-post-go-live
description: Summarise OKR progress for a review, with status and blockers.
tools: Claude / ChatGPT / Gemini
---

# OKR Review Summariser

**Stage:** 7 - Post Go-Live

## Prompt

```
You are a product analytics partner working with a Product Owner. You help translate raw metrics and data into clear OKR progress summaries for leadership.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

Here are the OKRs and current data for review:

**Review period:** [E.G. Q1 2026 / SPRINT 40-42 / APRIL 2026]

**Objective 1:** [STATE THE OBJECTIVE]
- KR1: [KEY RESULT + TARGET] → Current: [ACTUAL VALUE]
- KR2: [KEY RESULT + TARGET] → Current: [ACTUAL VALUE]
- KR3: [KEY RESULT + TARGET] → Current: [ACTUAL VALUE]

**Objective 2:** [STATE THE OBJECTIVE]
- KR1: [KEY RESULT + TARGET] → Current: [ACTUAL VALUE]
- KR2: [KEY RESULT + TARGET] → Current: [ACTUAL VALUE]

[ADD MORE OBJECTIVES AS NEEDED]

**Additional context:** [ANY NOTABLE EVENTS — LAUNCHES, INCIDENTS, PARTNER CHANGES, SEASONALITY]

Generate an OKR review summary with:

## 1. Traffic Light Summary
| Objective | Status | Confidence |
|---|---|---|
| Obj 1 | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | [High/Medium/Low] |
| Obj 2 | ... | ... |

## 2. Key Result Detail
For each KR:
- Progress: [X]% of target achieved, [Y]% of time elapsed
- Trend: Accelerating / Steady / Decelerating / Stalled
- What's driving the result (or blocking it)
- Forecast: Will we hit this by end of period? What needs to change?

## 3. Wins & Highlights
- What went well this period? (2-3 bullets, specific and evidence-based)

## 4. Risks & Blockers
- What's threatening our OKRs? (2-3 bullets with suggested mitigations)

## 5. Recommendations
- Actions to take in the next period to improve trajectory
- Any OKRs that should be revised (with reasoning)
- Resources or support needed

## 6. Partner Impact
- How are partner-specific metrics trending?
- Any partner-level highlights or concerns?

Keep the summary executive-friendly — one page max. Lead with the headline, support with data, close with actions.
```
