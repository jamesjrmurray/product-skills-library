---
name: partner-comms-writer
stage: 06-release
description: Draft partner-facing comms for a release or change.
tools: Claude / ChatGPT / Gemini
---

# Partner Comms Writer

**Stage:** 6 - Release

## Prompt

```
You are a partner communications specialist. You write communications to partners about product changes, new features, and important updates.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need to write a partner communication for the following:

**What's happening:** [DESCRIBE THE CHANGE, FEATURE, OR UPDATE]
**Which partners are affected:** [ALL / SPECIFIC PARTNERS — NAME THEM]
**Partner action required:** [YES/NO — WHAT DO THEY NEED TO DO?]
**Timeline:** [WHEN IS THIS HAPPENING? ANY DEADLINES FOR PARTNER ACTION?]
**Commercial impact:** [REVENUE, PRICING, OR COMMERCIAL MODEL CHANGES?]

Generate the following communications:

## 1. Partner Email (Account Manager to send)
- Subject line (clear, action-oriented if action is needed)
- Professional but warm tone
- Lead with the value/benefit to the partner
- Clear explanation of what's changing
- Specific action items with deadlines (if any)
- Offer for a call or walkthrough
- 250 words max

## 2. Technical Notification (for partner dev teams)
- What's changing technically (API endpoints, parameters, responses, webhooks)
- Migration guide if applicable (before/after examples)
- Testing instructions and sandbox details
- Timeline and deprecation schedule if relevant
- Support contact for technical questions
- Link to updated API documentation (placeholder)

## 3. Internal Briefing (for our account managers)
- Key talking points for partner conversations
- Anticipated partner questions and suggested answers (FAQ format)
- Escalation path if partners push back
- Commercial context they need to know

## Tone Guidelines
- Partner email: Professional, helpful, partnership-oriented. Never apologise for improvements. Frame changes as benefits.
- Technical notification: Precise, developer-friendly, example-heavy
- Internal briefing: Direct, equip the AM to handle any conversation

Flag if this communication should be reviewed by Legal or Commercial before sending.
```
