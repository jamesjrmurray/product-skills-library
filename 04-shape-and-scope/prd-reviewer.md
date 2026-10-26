---
name: prd-reviewer
stage: 04-shape-and-scope
description: Review a PRD for gaps, ambiguity and missing non-functionals before sign-off.
tools: Claude / ChatGPT / Gemini
---

# PRD Reviewer

**Stage:** 4 - Shape & Scope

## Prompt

```
You are a senior product leader reviewing a PRD written by a Product Owner.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

Please critically review the following PRD:

[PASTE YOUR PRD HERE]

Review against these criteria and provide a score (1-5) and specific feedback for each:

## 1. Problem Clarity (Score: /5)
- Is the problem clearly defined with who, what, when, and impact?
- Is it a real problem backed by evidence, or an assumption?
- Could someone unfamiliar with the project understand the problem?

## 2. Goals & Metrics (Score: /5)
- Are goals specific and measurable (not vague)?
- Are success metrics tied to business outcomes, not just output?
- Are targets realistic and time-bound?
- Is there a clear definition of "good enough" vs "great"?

## 3. Scope Discipline (Score: /5)
- Is scope tight enough for a single delivery cycle?
- Are "out of scope" items explicitly called out?
- Is there scope creep hiding in the requirements?
- Could this be split into a smaller first phase?

## 4. User & Partner Understanding (Score: /5)
- Are user segments clearly identified?
- Are partner implications addressed (integration, commercial, support)?
- Are edge cases and variations across partners considered?

## 5. Risks & Assumptions (Score: /5)
- Are key assumptions stated and testable?
- Are risks identified with mitigations?
- Is the RACD (Risks, Assumptions, Constraints, Dependencies) section thorough?

## 6. Technical Feasibility (Score: /5)
- Is there enough technical context for engineering to estimate?
- Are integration points and dependencies clear?
- Are non-functional requirements addressed?

## 7. Ready for Development Check
- Would an engineer be able to start building from this PRD? If not, what's missing?
- Would QA be able to write test cases from this? If not, what's ambiguous?

## Overall Assessment
- **Overall Score:** /35
- **Top 3 Strengths** of this PRD
- **Top 3 Gaps** that need addressing before development
- **Questions the PRD doesn't answer** (list 3-5)
- **Recommended next actions** before moving to Build & Test

Be constructive but honest. A weak PRD that ships causes more pain than a delayed PRD that's solid.
```
