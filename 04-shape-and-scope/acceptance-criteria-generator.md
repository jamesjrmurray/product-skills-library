---
name: acceptance-criteria-generator
stage: 04-shape-and-scope
description: Turn a user story into Given/When/Then acceptance criteria.
tools: Claude / ChatGPT / Gemini
---

# Acceptance Criteria Generator

**Stage:** 4 - Shape & Scope

## Prompt

```
You are a detail-oriented Product Owner. You write acceptance criteria that are clear enough for developers to implement and QA to test without ambiguity.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I have user stories that need thorough acceptance criteria. Here are the stories:

**Story 1:** [PASTE USER STORY — "As a... I want... So that..."]
**Story 2:** [PASTE ADDITIONAL STORIES IF NEEDED]

**Context:** [ANY RELEVANT DESIGN DECISIONS, PARTNER CONSTRAINTS, OR TECHNICAL NOTES]

For each story, generate acceptance criteria using Given-When-Then format:

## Story: [Title]

### Happy Path
- **Given** [precondition], **When** [user action], **Then** [expected outcome]
- (Cover the main success scenario end-to-end)

### Validation & Error Handling
- **Given** [invalid input/state], **When** [user action], **Then** [error handling behaviour]
- Cover: empty states, invalid data, timeout scenarios, API failures

### Edge Cases
- **Given** [unusual but possible condition], **When** [action], **Then** [expected behaviour]
- Consider: concurrent users, boundary values, partner-specific configurations

### Partner Variations
- **Given** [partner has specific configuration], **When** [action], **Then** [partner-appropriate behaviour]
- Consider: different partner integrations (API vs widget vs redirect), branding, language

### Accessibility & UX
- **Given** [accessibility context — screen reader, keyboard nav, mobile], **When** [interaction], **Then** [accessible behaviour]

### Data & Analytics
- **Given** [user completes action], **Then** [event/metric is tracked with these properties: ...]

### Performance
- **Given** [normal load], **When** [action], **Then** [response within X ms]

---

For each criterion:
- Be specific about expected values, states, and messages
- Avoid vague words like "appropriate", "correct", "properly" — say exactly what should happen
- Flag any criteria where you need a decision from the team (mark as ⚠️ DECISION NEEDED)

Also note any criteria that might need partner sign-off before development.
```
