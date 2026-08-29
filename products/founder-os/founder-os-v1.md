# Founder OS
## An AI Execution System for Solo Builders

**Launch price:** $50  
**Regular price:** $75

---

## Introduction

Most founders do not have an idea problem.

They have an execution problem.

AI helps, but it also creates noise. You get scattered prompts, half-finished plans, bloated task lists, and too many false starts. Founder OS fixes that by giving you a simple operating system for planning, delegating, shipping, and reviewing work with AI.

This is not a generic prompt pack.

It is a practical execution system for solo founders and tiny teams using Claude, ChatGPT, and coding agents to get real work done.

---

## 1. How to Use Founder OS

Use Founder OS in four layers:

### Layer 1 — Think
Use AI to clarify the problem, user, outcome, and trade-offs.

### Layer 2 — Plan
Turn rough ideas into a small, sharp spec and a realistic task breakdown.

### Layer 3 — Execute
Delegate cleanly to AI, review outputs fast, and keep momentum.

### Layer 4 — Learn
Review what worked, log decisions, and tighten the system every week.

### Core rule
Do not ask vague questions.

Always provide:
- context
- constraints
- required output
- quality bar
- definition of done

---

## 2. Weekly Founder Operating Cadence

### Monday — Direction
Use Monday to set direction, not to pretend to be busy.

Answer:
- What is the single most important outcome for this week?
- What must ship?
- What can be ignored?
- What will kill momentum if left unresolved?

**Prompt:**

> Act as a startup operator. Based on these projects, help me choose the single most important outcome for this week. Break it into the smallest meaningful milestones, identify the likely blockers, and recommend the cleanest order of execution.

### Tuesday to Thursday — Build
During the middle of the week:
- build the core milestone
- use AI for breakdowns, drafting, debugging, and synthesis
- capture decisions as they happen
- resist shiny work

### Friday — Review
Use Friday to close loops.

Review:
- what shipped
- what got stuck
- what created drag
- what should be stopped
- what becomes next week’s main outcome

**Prompt:**

> Review this week’s work log and identify: 1) what moved the business forward, 2) what created noise, 3) what should be stopped, and 4) the highest-leverage focus for next week.

---

## 3. Idea-to-PRD Workflow

### Step 1 — Capture the idea
Use this raw template:
- idea
- target user
- problem
- why now
- likely value
- biggest risk

### Step 2 — Clarify with AI
**Prompt:**

> Turn this rough startup idea into a crisp product concept. Identify the target user, core pain, current alternatives, value proposition, must-have feature set, and biggest product risk.

### Step 3 — Write a mini-PRD
Use this template:

#### Mini-PRD Template
- **Problem statement:**
- **Target user:**
- **Desired outcome:**
- **Scope:**
- **Non-goals:**
- **Success metric:**
- **Release standard:**

### Rule
If the PRD still sounds clever but vague, it is not ready.

---

## 4. Feature Breakdown Workflow

Once the PRD is clear, break work into:
- frontend
- backend
- data
- integrations
- testing
- launch tasks

**Prompt:**

> You are a senior product engineer. Break this feature into implementation tasks grouped by frontend, backend, data, integrations, testing, and release. Highlight dependencies, risks, and the smallest shippable version.

### What to force every time
Ask for:
- dependencies
- risks
- smallest shippable version
- what can wait

That is how you stop bloat.

---

## 5. AI Delegation System

Most people waste AI by delegating badly.

Do not say:
- build this
- help me with this
- fix this bug

Use a proper delegation frame.

### Delegation Template
- **Objective:** what needs to happen?
- **Context:** what does the AI need to know?
- **Constraints:** what is out of scope, fixed, or non-negotiable?
- **Output required:** plan, code, table, checklist, draft?
- **Definition of done:** what must be true for this to count as complete?

### Example
**Objective:** Produce a launch checklist for this feature.

**Context:** This is a fintech dashboard for South African professionals.

**Constraints:** Lean team, web-first MVP, no mobile scope.

**Output required:** A step-by-step launch checklist grouped into product, engineering, legal, analytics, and support.

**Definition of done:** Each item must be concrete, testable, and relevant to a lean MVP launch.

### Delegation Prompt

> Objective: [insert objective]
> 
> Context: [insert context]
> 
> Constraints: [insert constraints]
> 
> Output required: [insert output type]
> 
> Definition of done: [insert done condition]

---

## 6. Daily Execution Loop

### Morning
Define one meaningful outcome for the day.

Ask:
- What would make today count?
- What is blocked?
- What should AI accelerate?

**Prompt:**

> Based on these open tasks, help me choose the highest-leverage task for today, define the fastest path to done, and identify what should be delegated to AI.

### During the day
- delegate narrowly
- review outputs quickly
- log decisions immediately
- stop reopening solved questions

### End of day
Write down:
- what moved
- what stalled
- what gets picked up tomorrow

### Rule
A good day is not “I touched many things”.
A good day is “one important thing moved materially”.

---

## 7. Bug Triage Workflow

When bugs appear, do not flail.

### Triage Template
- **Bug summary:**
- **Severity:**
- **Affected user flow:**
- **Reproduction steps:**
- **Suspected root cause:**
- **Workaround:**
- **Fix owner:**
- **Release impact:**

**Prompt:**

> Given this bug report, create a clean triage summary with severity, likely root cause, investigation steps, workaround options, and the fastest safe fix path.

### Severity rubric
- **P0:** broken core flow, revenue or trust risk
- **P1:** major pain, but workaround exists
- **P2:** annoying but tolerable
- **P3:** cosmetic or low urgency

---

## 8. Launch Readiness Checklist

Before shipping, check:
- the core user flow works
- obvious failures are visible
- analytics are in place
- copy is acceptable
- known issues are documented
- support path exists
- rollback or fallback exists

### Launch Prompt

> Create a lean launch readiness checklist for this feature. Group items into product, engineering, analytics, support, and risk. Keep only what is necessary for a credible MVP release.

### Rule
Ship when the product is usable and safe.
Not when it is emotionally perfect.

---

## 9. Decision Log

Founders forget why decisions were made, then repeat old debates.

### Decision Log Template
- **Date:**
- **Decision:**
- **Why:**
- **Alternatives rejected:**
- **Expected upside:**
- **Known risk:**
- **Review date:**

### Example
- **Date:** 10 May 2026
- **Decision:** Launch Founder OS at $50, regular price $75
- **Why:** Lower friction for early traction while preserving a stronger value anchor
- **Alternatives rejected:** $29, $49, $99
- **Expected upside:** Better conversion with enough room to raise price later
- **Known risk:** Some buyers may anchor too hard to launch pricing
- **Review date:** After first 10 sales

---

## 10. Post-Mortem Template

After a launch, sprint, or failed push, run a simple post-mortem.

### Template
- what happened
- what went well
- what went badly
- what surprised us
- what should change
- what gets documented

**Prompt:**

> Turn these raw notes into a concise post-mortem with wins, failures, surprises, lessons, and process changes.

### Rule
Post-mortems are for learning, not self-punishment.

---

## 11. Example Workflow in Practice

### Scenario: Launching a Small Paid Product
1. Capture the idea
2. Clarify the product with AI
3. Write the mini-PRD
4. Break the feature set into smallest shippable tasks
5. Delegate narrow chunks to AI
6. Run the daily execution loop
7. Triage bugs or friction fast
8. Use the launch checklist
9. Log key decisions
10. Run a post-mortem after launch

That is Founder OS in motion.

---

## 12. Quick-Start Pack

If you only use five things from this product, use these:
- weekly founder review
- mini-PRD template
- feature breakdown workflow
- delegation template
- launch checklist

Used together, they clean up most founder execution mess very quickly.

---

## Closing Note

Most founders do not need more inspiration.
They need a cleaner operating rhythm.

Founder OS gives you one.

Use it to plan better, delegate cleaner, and ship faster.
