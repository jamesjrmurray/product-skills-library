---
name: bug-report-improver
stage: 05-build-and-test
description: Rewrite a vague bug report into a reproducible, triageable ticket.
tools: Claude / ChatGPT / Gemini
---

# Bug Report Improver

**Stage:** 5 - Build & Test

## Prompt

```
You are a QA lead. You help improve bug reports so they're actionable for developers and don't bounce back for more information.

About my company and product: [ONE OR TWO SENTENCES: WHAT YOU SELL, TO WHOM, AND ANY PARTNERS OR CHANNELS INVOLVED]

Here is a bug report that needs improving:

**Original bug report:**
[PASTE THE ORIGINAL BUG REPORT — HOWEVER ROUGH OR INCOMPLETE]

Please rewrite this into a clear, actionable bug report:

## Bug Title
[Clear, specific title — include the what and where]

## Environment
- **Platform:** [Web / Mobile / API / Partner integration]
- **Browser/Device:** [If applicable]
- **Partner:** [If partner-specific — which partner and integration type]
- **Environment:** [Production / Staging / QA]
- **Date/Time first observed:** [When]

## Severity
- **Severity:** [Critical / High / Medium / Low]
- **Impact:** [Who is affected and how many? Revenue impact?]
- **Workaround available?** [Yes/No — describe if yes]

## Steps to Reproduce
1. [Precise step]
2. [Precise step]
3. [Precise step]
(Number every step. Include URLs, test data, and credentials/roles needed)

## Expected Behaviour
[What should happen]

## Actual Behaviour
[What actually happens — be specific about error messages, visual glitches, incorrect data]

## Evidence
- Screenshots/video: [Describe what to capture if not yet attached]
- Console errors: [If applicable]
- API response: [If applicable]
- Logs: [If applicable]

## Additional Context
- Is this a regression? (Did it work before? When?)
- Is this partner-specific or across all partners?
- Frequency: Always / Intermittent / One-time
- Related Jira tickets: [If any]

---

Also flag:
- Any missing information in the original report that I should go find
- Whether this sounds like it might be a partner-side issue vs our platform
- Suggested labels/components for Jira routing
```
