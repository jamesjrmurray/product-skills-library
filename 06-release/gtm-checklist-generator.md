---
name: gtm-checklist-generator
stage: 06-release
description: Build a go-to-market and release checklist with owners.
tools: Claude / ChatGPT / Gemini
---

# GTM Checklist Generator

**Stage:** 6 - Release

## Prompt

```
You are a go-to-market specialist working with a Product Owner. You help ensure nothing gets missed when launching features to partners and end users.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need a GTM checklist for the following launch:

**Feature/Product:** [WHAT ARE WE LAUNCHING?]
**Launch type:** [Soft launch (limited partners) / Full launch / Feature toggle / Phased rollout]
**Target partners:** [WHICH PARTNERS GET THIS FIRST?]
**Launch date:** [DATE]
**Commercial model:** [HOW IS THIS MONETISED? ANY PRICING CHANGES?]

Generate a comprehensive GTM checklist:

## Pre-Launch (2+ weeks before)
### Product Readiness
- [ ] Feature complete and QA-approved
- [ ] Definition of Done met
- [ ] Performance tested under expected load
- [ ] Rollback plan documented and tested
- [ ] Feature flags configured for phased rollout
- [ ] Monitoring and alerting set up

### Partner Readiness
- [ ] Partner technical documentation updated
- [ ] Partner sandbox available for testing
- [ ] Partner integration tested (per partner)
- [ ] Partner communication sent (see Partner Comms Writer)
- [ ] Partner training/walkthrough scheduled if needed
- [ ] Commercial terms agreed and signed

### Internal Readiness
- [ ] Internal knowledge base / wiki updated
- [ ] Support team briefed with FAQ and escalation paths
- [ ] Account managers briefed with talking points
- [ ] Commercial/BD team briefed on upsell opportunities
- [ ] Analytics and tracking verified (events, dashboards)

## Launch Day
- [ ] Feature enabled (or flag flipped) per rollout plan
- [ ] Smoke test in production
- [ ] Key metrics dashboard monitored
- [ ] On-call team aware and available
- [ ] Partner confirmation of successful integration

## Post-Launch (Week 1)
- [ ] Daily metrics check (adoption, errors, revenue)
- [ ] Partner feedback collected
- [ ] Bug triage — launch-related issues prioritised
- [ ] Internal retrospective on launch process
- [ ] Release notes published (internal + external)

## Post-Launch (Week 2-4)
- [ ] Success metrics reviewed against targets
- [ ] Partner adoption report
- [ ] User feedback synthesis
- [ ] Iteration backlog created from learnings
- [ ] Stakeholder update sent

---

Customise this checklist by:
- Removing items not relevant to this launch type
- Adding partner-specific items
- Flagging items that are blocking vs nice-to-have
- Assigning owners to each item (suggest roles, I'll fill in names)
```
