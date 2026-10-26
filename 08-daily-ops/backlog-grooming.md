---
name: backlog-grooming
stage: 08-daily-ops
description: Triage and tidy a backlog: duplicates, stale items, missing detail.
tools: Claude / ChatGPT / Gemini
---

# Backlog Grooming Assistant

**Stage:** 8 - Daily Ops

## Prompt

```
You are an experienced product coach helping a Product Owner groom their backlog.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

Here is my current backlog (or a section of it):

[PASTE JIRA TICKETS, FEATURE LIST, OR BACKLOG ITEMS — INCLUDE TITLES, DESCRIPTIONS, AND ANY PRIORITY/STATUS]

**Sprint capacity:** [HOW MANY STORY POINTS OR DAYS AVAILABLE]
**Current sprint goal:** [WHAT ARE WE TRYING TO ACHIEVE THIS SPRINT?]
**Upcoming commitments:** [ANY PARTNER DEADLINES, LAUNCHES, OR DEPENDENCIES]

Help me groom this backlog by:

## 1. Quality Check
For each item, flag if:
- ❌ Title is vague or duplicated
- ❌ Missing acceptance criteria
- ❌ Missing user story format (As a / I want / So that)
- ❌ Too large (should be split)
- ❌ Dependencies not identified
- ❌ No success metric
- ✅ Ready for sprint (meets Definition of Ready)

## 2. Priority Recommendation
Suggest a priority order based on:
- Impact on current sprint goal
- Partner commitments and deadlines
- Dependencies and sequencing
- Quick wins vs. larger efforts
- Technical risk (de-risk early)

## 3. Split Suggestions
For items that are too large, suggest how to split them into:
- Independently deliverable slices
- Vertical slices (end-to-end thin) rather than horizontal layers
- MVP first, enhancements later

## 4. Missing Items
Based on the backlog, flag:
- Gaps — things you'd expect to see but don't (error handling, analytics, ops tooling)
- Tech debt items that should be budgeted in
- Partner-specific variants that might be missing

## 5. Recommended Grooming Actions
- Top 5 items to discuss with the team this session
- Items to remove or merge
- Items that need more information before they're ready

Be practical. The goal is a clean, prioritised, sprint-ready backlog — not perfection.
```
