# Claude Cowork Workshop Guide

## What You’ll Build
In this workshop, you’ll set up 3 practical AI workflows you can use immediately:
- CEO Coach System
- CEO Advisory Sub-Agents (pre-launch red team)
- Thought Leader Content Pipeline

Use this guide as your copy/paste implementation pack.

## Who This Is For
- Founders and CEOs
- Managers and operators
- Knowledge workers who want better output quality in less time

## How To Use This Guide
1. Copy a prompt.
2. Replace placeholders like `[COMPANY]`, `[GOALS]`, `[AUDIENCE]`.
3. Run it in your AI workspace.
4. Save the output as a reusable template.

---

## Prompt 1: CEO Coach System

### 1A) Build your coaching operating system
```text
Act as my CEO coach.

Company context:
- Company: [COMPANY]
- Stage: [STAGE]
- Primary goals this quarter: [GOALS]
- Top constraints: [CONSTRAINTS]
- Key metrics: [KPIS]
- Current risks: [RISKS]

My request:
Build a CEO coaching operating system with:
1) Daily decision protocol (10-15 min)
2) Weekly strategy review (45 min)
3) Prioritization rubric for initiatives
4) "Stop/Start/Continue" framework for leadership execution
5) Escalation triggers that tell me when to intervene personally

Output format:
- Section A: CEO dashboard (top 5 things that matter)
- Section B: Weekly CEO agenda template
- Section C: Decision memo template
- Section D: 5 coaching questions I should answer every Friday

Make this practical for a busy CEO. No generic advice.
```

### 1B) Pressure-test one real decision
```text
Use my CEO coaching system and evaluate this decision:

Decision to evaluate:
[PASTE DECISION]

Context:
[PASTE CONTEXT]

Return:
1) Decision quality score (1-10) with reasoning
2) Weak assumptions
3) Missing evidence
4) Execution risks
5) Revised recommendation in 5 bullets
6) Immediate next 3 actions this week
```

---

## Prompt 2: CEO Advisory Sub-Agents

### 2A) Create your sub-agent advisory board
```text
I want a pre-launch CEO advisory board made of sub-agents that critique my work.

Create 5 sub-agents:
1) Operator (execution realism)
2) Skeptic (red-team and assumption attacks)
3) Customer Advocate (user value and adoption risk)
4) Finance Partner (unit economics and downside)
5) Risk/Legal Reviewer (compliance, reputational, legal exposure)

For each sub-agent provide:
- Mission
- 7 evaluation questions
- Failure modes it detects
- Scoring rubric (1-5)
- "Ship / Fix / Stop" recommendation logic

Then provide one orchestrator workflow that runs all 5 and outputs one consolidated pre-launch brief.
```

### 2B) Run a pre-launch critique
```text
Run the 5-sub-agent advisory review on this launch:

Launch plan:
[PASTE PLAN]

Assumptions:
[PASTE ASSUMPTIONS]

Constraints:
[PASTE CONSTRAINTS]

Output exactly:
1) Executive verdict: Ship / Fix / Stop
2) Top 5 risks ranked by severity
3) Contradictions across sub-agents
4) Required fixes before launch
5) Revised launch plan (concise)
```

---

## Prompt 3: Thought Leader Pipeline

### 3A) Build your content operating system
```text
Build me a thought leadership content pipeline system for [INDUSTRY].

Profile:
- Expertise areas: [AREAS]
- POV themes: [THEMES]
- Audience: [AUDIENCE]
- Platforms: X and LinkedIn
- Posting target: [FREQUENCY]
- Brand voice: [VOICE]

Design a complete pipeline with:
1) Idea capture method
2) Topic scoring model
3) Drafting workflow
4) Editing and quality checklist
5) Distribution cadence
6) Repurposing system (one idea -> multiple assets)
7) Weekly analytics review loop

Output:
- Operating playbook
- Repeatable templates
- Weekly execution checklist
```

### 3B) Generate content in real time
```text
Use the pipeline and generate content from this source input:

Source material:
[PASTE NOTES/TRANSCRIPT/IDEA]

Create:
1) One X thread (hook + 5-7 posts + CTA)
2) One LinkedIn post (strong opening, clear structure, CTA)
3) One short POV memo (300-500 words)
4) 10 backlog ideas from the same source

Quality bar:
- Specific, not generic
- Sounds like my voice
- Includes concrete examples
- Publish-ready with minimal edits
```

---

## Fast Refinement Prompts

### Make it sharper
```text
Rewrite this to be 30% tighter, more opinionated, and more actionable.
Remove filler and keep only high-signal language.

Text:
[PASTE]
```

### Make it sound like me
```text
Rewrite this in my voice:
- Direct
- Executive clarity
- Confident but not hypey
- Practical and specific

Text:
[PASTE]
```

### Turn into a talking script
```text
Convert this into talking points for a 3-minute segment.
Include:
- Opening line
- 3 key points
- 1 concrete example
- Closing line

Source:
[PASTE]
```

---

## Same-Day Implementation Plan (Right After This Event)

### Step 1 (10 minutes)
- Build your CEO Coach System with Prompt 1A.
- Save your CEO dashboard and weekly agenda template.

### Step 2 (10 minutes)
- Run one real decision through Prompt 1B.
- Capture your revised recommendation and next 3 actions.

### Step 3 (10 minutes)
- Create your advisory sub-agents with Prompt 2A.
- Save the orchestrator workflow as a reusable template.

### Step 4 (10 minutes)
- Run one launch/project through Prompt 2B.
- Apply the top required fixes before shipping.

### Step 5 (10 minutes)
- Build your thought leader pipeline with Prompt 3A.
- Set your voice, themes, and posting cadence.

### Step 6 (10 minutes)
- Generate and finalize content with Prompt 3B.
- Publish at least one piece today.

---

## Common Mistakes To Avoid
- Using generic prompts with no business context.
- Asking for output without a quality bar.
- Not saving good outputs as reusable templates.
- Running one-off prompts instead of a repeatable workflow.

## Final Checklist
- I have my CEO Coach dashboard and weekly agenda.
- I have sub-agents that critique major decisions before launch.
- I have a repeatable content pipeline with backlog generation.
- I can run all 3 workflows in under 30 minutes total.

## Get The Files
- Prompt pack: `live-event-prompt-pack.md`
- Event outline: `live-event-outline.md`
- This attendee guide: `workshop-attendee-guide.md`
