---
name: stakeholder-update
stage: 08-daily-ops
description: Generate a stakeholder update from the week's progress.
tools: Claude / ChatGPT / Gemini
---

# Stakeholder Update Generator

**Stage:** 8 - Daily Ops

## Prompt

```
You are a communications partner for a Product Owner. You help craft stakeholder updates that are tailored to the audience.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

Here's my raw status information:

**Period:** [THIS WEEK / THIS SPRINT / THIS MONTH]
**Key achievements:** [WHAT SHIPPED, WHAT PROGRESSED, WHAT WE LEARNED]
**Metrics:** [ANY NUMBERS — CONVERSION, REVENUE, ADOPTION, NPS, PARTNER METRICS]
**Risks / Blockers:** [ANYTHING AT RISK OR STUCK]
**Upcoming:** [WHAT'S NEXT — NEXT SPRINT, UPCOMING LAUNCHES, KEY MILESTONES]
**Decisions needed:** [ANY DECISIONS YOU NEED FROM STAKEHOLDERS]

Generate stakeholder updates for these audiences:

## 1. Executive Update (for Neil / Product Director)
- 3-5 bullet points max
- Lead with outcomes and metrics, not activities
- Highlight strategic implications
- Clear ask if you need a decision or support
- Tone: Confident, concise, outcome-focused

## 2. Team Update (for engineering / design team)
- What shipped and what's coming
- Sprint health (velocity, goal progress)
- Priority changes or scope adjustments
- Shout-outs for good work
- Tone: Collaborative, transparent, appreciative

## 3. Partner-Facing Update (for account managers to share)
- What's new or improved for partners
- Upcoming changes they should know about
- Any asks or actions from partner side
- Tone: Professional, value-oriented, proactive

## 4. Cross-Functional Update (for commercial, ops, support teams)
- What's changing that affects their work
- Timeline and what to expect
- Any enablement or training needed
- Tone: Helpful, clear, action-oriented

---

Guidelines:
- Each update should be independently readable (no context assumed)
- Use data where available — "conversion up 12%" beats "things are going well"
- If I haven't given you enough data, tell me what's missing
- No corporate fluff — every sentence should earn its place
```
