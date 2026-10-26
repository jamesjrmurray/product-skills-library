# Product Skills Library

AI prompts for product owners, organised by lifecycle stage. Each file is a single paste-in prompt for Claude, ChatGPT or Gemini: copy the code block, replace the [BRACKETS], and run it.

## How to use a prompt

1. Open the prompt file for the job you need and copy everything inside the code fence.
2. Replace each [BRACKETED PLACEHOLDER] with your own content.
3. Every prompt starts with a company context line. Fill it in once, keep it somewhere handy, and paste the same line into any prompt here: the output quality depends on it.

The prompts are written from a product owner's working week: shaping ideas, running discovery, scoping, testing, releasing and the daily rituals in between. Several include partner-facing sections; these assume a B2B or channel context (you sell through or alongside other businesses). If you are purely direct-to-consumer, delete those sections.

## Stages

| Stage | Covers |
|---|---|
| [1 - Idea](01-idea/) | Turning a raw thought into a problem worth solving. |
| [2 - Discovery](02-discovery/) | Understanding the problem, the users and the assumptions. |
| [3 - Solution Design](03-solution-design/) | Choosing and shaping the right solution. |
| [4 - Shape & Scope](04-shape-and-scope/) | Turning a chosen solution into buildable, testable work. |
| [5 - Build & Test](05-build-and-test/) | Keeping quality high while the work is built. |
| [6 - Release](06-release/) | Getting the work out of the door properly. |
| [7 - Post Go-Live](07-post-go-live/) | Learning from what shipped. |
| [8 - Daily Ops](08-daily-ops/) | The recurring rituals that keep a team moving. |

## All prompts

| Prompt | Skill command | Stage | What it does |
|---|---|---|---|
| [Idea Shaper](01-idea/idea-shaper.md) | `/idea-shaper` | 1 - Idea | Shape a rough idea into a problem statement, opportunity hypothesis and affected users and partners. |
| [Assumptions Lister](02-discovery/assumptions-lister.md) | `/assumptions-lister` | 2 - Discovery | List and categorise the assumptions behind an idea so the riskiest get tested first. |
| [Customer Interview Question Generator](02-discovery/customer-interview-question-generator.md) | `/customer-interview-question-generator` | 2 - Discovery | Generate non-leading discovery interview questions for a target audience. |
| [Product Brief Generator](02-discovery/product-brief-generator.md) | `/product-brief-generator` | 2 - Discovery | Turn a draft PRD, raw notes or a feature idea into a structured product brief. |
| [Prototype Brief](02-discovery/prototype-brief.md) | `/prototype-brief` | 2 - Discovery | Brief an AI coding tool to build a throwaway prototype for a discovery bet. |
| [Architecture Brief Generator](03-solution-design/architecture-brief-generator.md) | `/architecture-brief-generator` | 3 - Solution Design | Draft an architecture brief with options, trade-offs and a Mermaid diagram. |
| [Solution Options Evaluator](03-solution-design/solution-options-evaluator.md) | `/solution-options-evaluator` | 3 - Solution Design | Compare solution options against weighted criteria and recommend one with rationale. |
| [Acceptance Criteria Generator](04-shape-and-scope/acceptance-criteria-generator.md) | `/acceptance-criteria-generator` | 4 - Shape & Scope | Turn a user story into Given/When/Then acceptance criteria. |
| [PRD Reviewer](04-shape-and-scope/prd-reviewer.md) | `/prd-reviewer` | 4 - Shape & Scope | Review a PRD for gaps, ambiguity and missing non-functionals before sign-off. |
| [User Story Writer](04-shape-and-scope/user-story-writer.md) | `/user-story-writer` | 4 - Shape & Scope | Write user stories with acceptance criteria from a feature description. |
| [Bug Report Improver](05-build-and-test/bug-report-improver.md) | `/bug-report-improver` | 5 - Build & Test | Rewrite a vague bug report into a reproducible, triageable ticket. |
| [Test Case Generator](05-build-and-test/test-case-generator.md) | `/test-case-generator` | 5 - Build & Test | Generate test cases, including edge cases, from a story or spec. |
| [GTM Checklist Generator](06-release/gtm-checklist-generator.md) | `/gtm-checklist-generator` | 6 - Release | Build a go-to-market and release checklist with owners. |
| [Partner Comms Writer](06-release/partner-comms-writer.md) | `/partner-comms-writer` | 6 - Release | Draft partner-facing comms for a release or change. |
| [Release Notes Drafter](06-release/release-notes-drafter.md) | `/release-notes-drafter` | 6 - Release | Draft reader-ready release notes from tickets or changelogs. |
| [Feature Sunset Evaluator](07-post-go-live/feature-sunset-evaluator.md) | `/feature-sunset-evaluator` | 7 - Post Go-Live | Assess whether a feature should be kept, improved or retired. |
| [OKR Review Summariser](07-post-go-live/okr-review-summariser.md) | `/okr-review-summariser` | 7 - Post Go-Live | Summarise OKR progress for a review, with status and blockers. |
| [Backlog Grooming Assistant](08-daily-ops/backlog-grooming.md) | `/backlog-grooming` | 8 - Daily Ops | Triage and tidy a backlog: duplicates, stale items, missing detail. |
| [Retro Facilitator](08-daily-ops/retro-facilitator.md) | `/retro-facilitator` | 8 - Daily Ops | Facilitate a sprint retro with themes and prioritised actions. |
| [RICES Scorer](08-daily-ops/rices-scorer.md) | `/rices-scorer` | 8 - Daily Ops | Score initiatives with a RICES framework for prioritisation. |
| [Sprint Planning Assistant](08-daily-ops/sprint-planning.md) | `/sprint-planning` | 8 - Daily Ops | Plan a sprint from team capacity and a prioritised backlog. |
| [Stakeholder Update Generator](08-daily-ops/stakeholder-update.md) | `/stakeholder-update` | 8 - Daily Ops | Generate a stakeholder update from the week's progress. |
| [Stand-up Prep](08-daily-ops/standup-prep.md) | `/standup-prep` | 8 - Daily Ops | Prepare a crisp stand-up update from yesterday's activity. |

## Using them as agent skills

Every prompt carries YAML frontmatter with a `name`, so the files double as agent skills. Drop a file into your AI agent's skills folder (for Claude Code or Cowork, `~/.claude/skills/<name>/SKILL.md`) and the agent will pick it up when you ask for that job, or you can invoke it directly by its command, e.g. `/idea-shaper`. The "Skill command" column above lists the command for every prompt. Used this way you skip the copy-paste: the agent reads the skill and asks you for the bracketed inputs instead.

## Conventions

- One prompt per file, one code fence per prompt.
- YAML frontmatter on every prompt: name, stage, description, tools.
- UK English.
- Placeholders are [UPPER CASE IN SQUARE BRACKETS].
- Prompts never invent strategy, metrics or numbers; gaps are marked TBC.

A worked example of the Idea Shaper prompt, with fictional inputs and output, is in [examples/](examples/).

## Licence

MIT. See [LICENSE](LICENSE). Use them, adapt them, share them.
