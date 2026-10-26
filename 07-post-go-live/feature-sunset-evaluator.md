---
name: feature-sunset-evaluator
stage: 07-post-go-live
description: Assess whether a feature should be kept, improved or retired.
tools: Claude / ChatGPT / Gemini
---

# Feature Sunset Evaluator

**Stage:** 7 - Post Go-Live

## Prompt

```
You are a product lifecycle strategist working with a Product Owner. You help make objective decisions about whether features should be grown, maintained, or sunset.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need to evaluate whether the following feature should be sunset, maintained, or invested in:

**Feature:** [DESCRIBE THE FEATURE]
**Launch date:** [WHEN DID IT GO LIVE?]
**Current usage data:** [ACTIVE USERS, TRANSACTIONS, REVENUE — WHATEVER YOU HAVE]
**Maintenance cost:** [ENGINEERING TIME, SUPPORT TICKETS, PARTNER OVERHEAD]
**Original success metrics:** [WHAT WAS THIS SUPPOSED TO ACHIEVE?]
**Current performance vs targets:** [HOW IS IT ACTUALLY DOING?]

Please evaluate this feature across these dimensions:

## 1. Value Assessment
| Dimension | Score (1-5) | Evidence |
|---|---|---|
| end user value | | |
| Partner value | | |
| Revenue contribution | | |
| Strategic alignment | | |
| Competitive differentiation | | |
| **Total** | **/25** | |

## 2. Cost Assessment
| Dimension | Score (1-5) | Evidence |
|---|---|---|
| Engineering maintenance | | |
| Support/ops burden | | |
| Technical debt impact | | |
| Opportunity cost | | |
| Partner integration overhead | | |
| **Total** | **/25** | |

## 3. Recommendation Matrix
- **Value > 18 and Cost < 10:** Invest and grow
- **Value 12-18 and Cost < 15:** Maintain and optimise
- **Value < 12 or Cost > 18:** Consider sunsetting
- **Value < 8:** Sunset

## 4. If Recommending Sunset:
- Migration plan for affected partners
- Communication timeline (minimum 90 days notice for partners)
- Data archival requirements
- Alternative solutions to offer partners and end users
- Revenue impact and how to offset it

## 5. If Recommending Growth:
- Top 3 investment opportunities to increase value
- Expected ROI for each
- Resource requirements

## 6. If Recommending Maintain:
- Minimum maintenance plan
- Triggers that would change the recommendation (up or down)
- Review date for next evaluation

Be data-driven and unsentimental. Sunk cost is not a reason to keep a feature alive.
```
