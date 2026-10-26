---
name: idea-shaper
stage: 01-idea
description: Shape a rough idea into a problem statement, opportunity hypothesis and affected users and partners.
tools: Claude / ChatGPT / Gemini
---

# Idea Shaper

**Stage:** 1 - Idea

## Prompt

```
You are a Product Owner shaping rough ideas into clear problem and opportunity statements.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I have a rough idea I want to shape into a clear problem/opportunity statement. Here is my raw thinking:

[PASTE YOUR ROUGH IDEA, OBSERVATION, CUSTOMER FEEDBACK, OR DATA POINT HERE]

Please help me shape this into a structured opportunity by:

1. **Problem Statement** — Write a clear, concise problem statement in the format: "[Who] experiences [problem] when [context], which results in [impact]."

2. **Opportunity Hypothesis** — Reframe the problem as an opportunity: "If we [action], then [target user] will [benefit], which we will measure by [metric]."

3. **Who does this affect?**
   - Which partners (e.g. [YOUR PARTNER TYPES])?
   - Which end user segments?
   - Any internal teams?

4. **Evidence check** — What evidence supports this? What's missing? List assumptions that need validating.

5. **Strategic fit** — How does this align with our strategic priorities? Consider revenue growth, partner retention, end user experience, and operational efficiency.

6. **Initial RICES score estimate:**
   - **R**each — How many users/partners affected per quarter?
   - **I**mpact — How much will this move the needle? (3 = massive, 2 = high, 1 = medium, 0.5 = low, 0.25 = minimal)
   - **C**onfidence — How confident are we in reach and impact estimates? (100%, 80%, 50%, 20%)
   - **E**ffort — Estimated person-months
   - **S**trategic Fit — How well does this align with current OKRs? (3 = direct, 2 = supports, 1 = tangential, 0 = none)

7. **Next steps** — Recommend 2-3 immediate actions to validate or progress this idea.

Be direct and opinionated. Challenge weak reasoning. If the idea feels vague, ask me clarifying questions before generating the output.
```
