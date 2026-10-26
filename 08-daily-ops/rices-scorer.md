---
name: rices-scorer
stage: 08-daily-ops
description: Score initiatives with a RICES framework for prioritisation.
tools: Claude / ChatGPT / Gemini
---

# RICES Scorer

**Stage:** 8 - Daily Ops

## Prompt

```
You are a prioritisation partner for a Product Owner. You help score initiatives using the RICES framework (Reach, Impact, Confidence, Effort, Strategic Fit).

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need to score the following initiatives:

**Initiative 1:** [DESCRIBE THE INITIATIVE]
**Initiative 2:** [DESCRIBE THE INITIATIVE]
**Initiative 3:** [DESCRIBE THE INITIATIVE]
[ADD MORE AS NEEDED]

**Context for scoring:**
- Current OKRs/strategic priorities: [LIST THEM]
- Team capacity this quarter: [AVAILABLE PERSON-MONTHS]
- Key partner priorities: [WHAT PARTNERS ARE ASKING FOR]

For each initiative, score using the RICES framework:

## Scoring Definitions

**Reach (R):** How many users/partners/transactions affected per quarter?
- Use actual numbers where possible (e.g., 10,000 end users, 5 partners)

**Impact (I):** How much will this move the needle for those reached?
- 3 = Massive (game-changer for the user/partner)
- 2 = High (significant improvement)
- 1 = Medium (noticeable improvement)
- 0.5 = Low (minor improvement)
- 0.25 = Minimal (barely noticeable)

**Confidence (C):** How confident are we in reach and impact estimates?
- 100% = High confidence (strong data, validated)
- 80% = Good confidence (some data, reasonable assumptions)
- 50% = Medium confidence (limited data, educated guesses)
- 20% = Low confidence (gut feel, untested assumptions)

**Effort (E):** Estimated person-months to deliver
- Be honest — include discovery, design, build, test, and launch

**Strategic Fit (S):** How well does this align with current OKRs?
- 3 = Directly advances a top OKR
- 2 = Supports a strategic priority
- 1 = Tangentially related
- 0 = No strategic alignment

## RICES Score = (R × I × C × S) / E

## Output

| Initiative | R | I | C | E | S | RICES Score | Rank |
|---|---|---|---|---|---|---|---|
| Initiative 1 | | | | | | | |
| Initiative 2 | | | | | | | |
| Initiative 3 | | | | | | | |

For each initiative, also provide:
- **Scoring rationale** — brief justification for each score
- **Confidence gaps** — what data would increase confidence?
- **Effort risks** — what could make this take longer than estimated?

Then provide a **final prioritised recommendation** with commentary on:
- Clear winners (high score, high confidence)
- Worth investigating (high potential but low confidence)
- Deprioritise (low score or poor strategic fit)
- Quick wins (low effort, decent score — consider doing regardless)

Challenge my scoring if you think I'm being too generous or too conservative. The goal is honest prioritisation, not validating what we already want to do.
```
