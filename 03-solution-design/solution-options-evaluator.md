---
name: solution-options-evaluator
stage: 03-solution-design
description: Compare solution options against weighted criteria and recommend one with rationale.
tools: Claude / ChatGPT / Gemini
---

# Solution Options Evaluator

**Stage:** 3 - Solution Design

## Prompt

```
You are a senior product strategist. You help evaluate build vs. buy vs. partner vs. do-nothing options for product initiatives, and assess architectural and commercial trade-offs.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need to evaluate solution options for the following:

**Problem/Opportunity:** [DESCRIBE WHAT WE'RE SOLVING]
**Discovery findings:** [KEY INSIGHTS FROM STAGE 2 — WHAT DID WE LEARN?]
**Constraints:** [TIMELINE, BUDGET, TEAM CAPACITY, PARTNER REQUIREMENTS]

Please evaluate the following options (or suggest better ones if I've missed something):

**Option A:** [DESCRIBE OPTION — E.G. BUILD IN-HOUSE]
**Option B:** [DESCRIBE OPTION — E.G. BUY/INTEGRATE THIRD-PARTY]
**Option C:** [DESCRIBE OPTION — E.G. PARTNER WITH EXISTING PROVIDER]
**Option D:** Do nothing / defer

For each option, assess:

| Criteria | Option A | Option B | Option C | Option D |
|---|---|---|---|---|
| **Time to value** | ? | ? | ? | ? |
| **Upfront effort** (T-shirt) | ? | ? | ? | ? |
| **Ongoing maintenance** | ? | ? | ? | ? |
| **Partner integration complexity** | ? | ? | ? | ? |
| **Scalability across partners** | ? | ? | ? | ? |
| **Revenue potential** | ? | ? | ? | ? |
| **Risk level** | ? | ? | ? | ? |
| **Strategic alignment** | ? | ? | ? | ? |
| **Data/control ownership** | ? | ? | ? | ? |

Then provide:

1. **Recommendation** — Which option and why (be opinionated)
2. **Phasing suggestion** — Can we start with one option and evolve to another?
3. **Key decision factors** — What 2-3 things should most influence this decision?
4. **What we'd need to validate** before committing to the recommended option
5. **Architecture considerations** — High-level system/integration implications

If any option is clearly dominated (worse on all dimensions), say so and remove it from consideration.
```
