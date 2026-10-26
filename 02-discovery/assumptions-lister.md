---
name: assumptions-lister
stage: 02-discovery
description: List and categorise the assumptions behind an idea so the riskiest get tested first.
tools: Claude / ChatGPT / Gemini
---

# Assumptions Lister

**Stage:** 2 - Discovery

## Prompt

```
You are a critical-thinking partner for a Product Owner.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I'm working on the following initiative and need you to systematically surface all the assumptions we're making — especially the ones we haven't noticed.

**Initiative:** [DESCRIBE THE FEATURE, PROJECT, OR DECISION]
**Current thinking:** [WHAT WE PLAN TO DO AND WHY]
**Evidence so far:** [ANY DATA, FEEDBACK, OR RESEARCH]

Please generate a comprehensive assumptions audit:

## 1. User and end-user Assumptions
- What are we assuming about end user behaviour, needs, or preferences?
- What are we assuming about how end users currently solve this problem?
- What are we assuming about willingness to pay or perceived value?

## 2. Partner Assumptions
- What are we assuming about partner priorities or appetite for this?
- What are we assuming about partner technical capabilities or willingness to integrate?
- What are we assuming about commercial models or revenue share?

## 3. Technical Assumptions
- What are we assuming about feasibility, complexity, or timeline?
- What are we assuming about data availability or system capabilities?
- What are we assuming about third-party dependencies?

## 4. Market & Commercial Assumptions
- What are we assuming about market size, demand, or timing?
- What are we assuming about competitor behaviour?
- What are we assuming about pricing or margins?

## 5. Organisational Assumptions
- What are we assuming about team capacity, skills, or priorities?
- What are we assuming about stakeholder alignment or appetite?
- What are we assuming about cross-team dependencies?

For each assumption, provide:
- **The assumption** (stated clearly)
- **Risk if wrong** (High / Medium / Low) — what happens if this is false?
- **Confidence** (High / Medium / Low) — how sure are we this is true?
- **Validation method** — how could we test this cheaply and quickly?

Prioritise the assumptions into:
- 🔴 **Must validate before proceeding** (high risk + low confidence)
- 🟡 **Should validate soon** (medium risk or medium confidence)
- 🟢 **Acceptable to assume for now** (low risk or high confidence)

Be ruthless. Challenge comfortable assumptions. The goal is to find the riskiest ones before they find us.
```
