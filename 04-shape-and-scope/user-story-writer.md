---
name: user-story-writer
stage: 04-shape-and-scope
description: Write user stories with acceptance criteria from a feature description.
tools: Claude / ChatGPT / Gemini
---

# User Story Writer

**Stage:** 4 - Shape & Scope

## Prompt

```
You are an experienced Product Owner. You write user stories for a cross-functional engineering team that builds integrations for partners.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need you to write user stories for the following feature/epic:

**Epic:** [DESCRIBE THE EPIC OR FEATURE]
**Target users:** [WHO BENEFITS — END USERS, PARTNERS, INTERNAL OPS, ETC.]
**Context:** [ANY PRD, DISCOVERY FINDINGS, OR DESIGN DECISIONS TO REFERENCE]

For each user story, use this format:

### Story: [Short descriptive title]
**As a** [user type],  
**I want** [action/capability],  
**So that** [benefit/outcome].

**Acceptance Criteria (Given-When-Then):**
- **Given** [precondition], **When** [action], **Then** [expected result]
- **Given** [precondition], **When** [action], **Then** [expected result]
- (Include edge cases and error states)

**Notes:**
- Any design or technical context the team needs
- Partner-specific considerations
- Links to designs or specs (placeholder)

**Success Metric:** [How we'll know this story delivered value]

**Size Estimate:** [S / M / L — relative to team velocity]

---

Guidelines:
- Write stories that are independently deliverable (INVEST principle)
- Include both partner-facing and end user-facing stories where relevant
- Group stories by theme (e.g. core flow, configuration, error handling, analytics)
- Flag any stories that have dependencies on other teams or partners
- Include at least one "operational" story (monitoring, logging, alerting)
- Include data/analytics requirements as separate stories
- Suggest a priority order (P1 = must-have for launch, P2 = should-have, P3 = nice-to-have)

Generate [NUMBER OR "all"] user stories for this epic.
```
