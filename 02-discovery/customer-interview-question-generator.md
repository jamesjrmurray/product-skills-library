---
name: customer-interview-question-generator
stage: 02-discovery
description: Generate non-leading discovery interview questions for a target audience.
tools: Claude / ChatGPT / Gemini
---

# Customer Interview Question Generator

**Stage:** 2 - Discovery

## Prompt

```
You are a user researcher supporting a Product Owner.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

I need to generate interview questions for the following research:

**Research objective:** [WHAT ARE YOU TRYING TO LEARN?]
**Interview audience:** [WHO ARE YOU INTERVIEWING — E.G. PARTNER ACCOUNT MANAGERS, END USERS, INTERNAL OPS TEAM]
**Context:** [ANY BACKGROUND — E.G. WE'RE EXPLORING A NEW FEATURE, INVESTIGATING A DROP IN CONVERSION, UNDERSTANDING A PAIN POINT]

Generate a structured interview guide with:

## 1. Opening (2-3 mins)
- Warm-up questions to build rapport
- Set expectations for the conversation

## 2. Context & Current Behaviour (5-7 mins)
- Questions about their current workflow, habits, and experience
- "Walk me through the last time you..." style questions
- Understand frequency and importance of the relevant activity

## 3. Pain Points & Needs (10-12 mins)
- Open-ended questions to surface problems (avoid leading)
- Follow-up probes for each question (the "why behind the why")
- Questions about workarounds they currently use

## 4. Opportunity Exploration (5-7 mins)
- Reaction questions to the concept (without showing solutions)
- "If you could wave a magic wand..." style questions
- Priority and trade-off questions

## 5. Closing (2-3 mins)
- "What haven't I asked that I should have?"
- Next steps and thank-you

## Guidelines
- Write in plain, conversational language
- No jargon — adapt for the audience
- Include 2-3 follow-up probes per main question
- Flag which questions are must-ask vs. nice-to-have
- If interviewing partners: include questions about their end-customer feedback
- If interviewing end users: include questions about their booking journey context

Total interview should fit within 30 minutes.
```
