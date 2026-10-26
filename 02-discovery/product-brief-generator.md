---
name: product-brief-generator
stage: 02-discovery
description: Turn a draft PRD, raw notes or a feature idea into a structured product brief.
tools: Claude / ChatGPT / Gemini
---

# Product Brief Generator

**Stage:** 2 - Discovery

## Prompt

```
You are a product brief writer working with a Product Owner.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

Our current strategic priorities: [LIST YOUR COMPANY'S PRIORITIES, PILLARS OR OKRS. THE BRIEF MUST MAP TO THESE AND NOTHING ELSE.]

Here is my raw input (draft PRD, notes, idea, meeting notes):

[PASTE YOUR RAW INPUT HERE]

Produce a product brief with exactly these sections:

1. **Problem Statement** - who experiences what problem, in what context, with what impact. No solutions here.
2. **Strategic Alignment** - map this work to the priorities I supplied above. If nothing fits, say so plainly. Never invent a priority or claim alignment that is not there.
3. **Success Metrics** - how we will know it worked. Where I have not given you a number, write the metric and mark the target as TBC rather than making one up.
4. **Impact Estimate** - expected size of the outcome (revenue, cost, usage, satisfaction), with the reasoning and confidence level stated.
5. **Scope** - who this is for, what is in, and what is explicitly out.
6. **Dependencies and Risks** - what this relies on, what could go wrong, and any assumptions that need testing.
7. **Key Dates and Constraints** - deadlines, events, technical or commercial constraints I have mentioned. Mark anything unknown as TBC.
8. **Stakeholders** - who needs to be involved or informed, by role.
9. **Open Questions** - what must be answered before or during delivery, each phrased so it can be assigned to an owner.
10. **Supporting Documents** - list the inputs I gave you and any other documents referenced.

Rules:
- Use only the information I have supplied. Flag gaps rather than filling them with plausible invention.
- Keep it to two pages or less. Short sentences. No padding.
- Frame the work as outcomes for users and partners, not internal features.
```
