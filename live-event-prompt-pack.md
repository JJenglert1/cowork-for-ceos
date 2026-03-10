# Live Event Prompt Pack

Use this file as your live script + copy/paste prompt bank for the event.

## 0) Pre-Event Setup (10-15 min before going live)

### Prompt: Create your event operating context
```text
You are my executive AI copilot for a live event demo.

Context:
- Event host: Alex Lieberman
- Audience: managers, founders, and knowledge workers
- Goal: show practical workflows that 10x execution quality and speed
- Tone: sharp, practical, no fluff, high signal
- Constraint: outputs must be concise, specific, and usable immediately

Rules:
1) Ask clarifying questions only if absolutely required.
2) Default to strong assumptions and state them briefly.
3) Output in clear sections with bullets.
4) Prefer frameworks, checklists, and decision-ready recommendations.
5) For every major output, include:
   - What changed
   - Why it matters
   - What to do next

Confirm you are ready and provide a one-screen checklist I can use to run this demo smoothly.
```

### Prompt: Build your live "save" fallback
```text
Create a 60-second rescue workflow I can use if a live demo stalls.

I need:
- A quick framing line to the audience
- A fast prompt to recover output quality
- A concise "here's what happened and why this still matters" explanation
- A smooth transition back to the next segment
```

## 1) Use Case 1: CEO Coach Setup

### Prompt: Build the CEO coaching system
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

### Prompt: Pressure test a real CEO decision live
```text
Use the CEO coaching system you created and evaluate this decision:

Decision to evaluate:
[PASTE DECISION]

Context:
[PASTE CONTEXT]

Return:
1) Decision quality score (1-10) with reasoning
2) What assumptions are weak
3) What evidence is missing
4) What could fail in execution
5) Revised decision recommendation in 5 bullets
6) Immediate next 3 actions for the CEO this week
```

## 2) Use Case 2: CEO Advisory Sub-Agents

### Prompt: Create sub-agents
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

Then give me a single orchestrator workflow that runs all 5 and produces one consolidated pre-launch brief.
```

### Prompt: Run the sub-agent advisory review
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
2) Top 5 launch risks ranked by severity
3) Contradictions across sub-agents
4) Pre-launch fixes required before shipping
5) Final revised launch plan (concise)
```

## 3) Use Case 3: Thought Leader Pipeline System

### Prompt: Build the thought leadership pipeline
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
2) Topic scoring model (what is worth posting)
3) Drafting workflow
4) Editing and quality control checklist
5) Distribution cadence
6) Repurposing system (one idea -> multiple assets)
7) Weekly analytics review loop

Output:
- Operating playbook
- Repeatable templates
- Weekly execution checklist
```

### Prompt: Live content generation test (real time)
```text
Use the pipeline and generate content from this source input:

Source material:
[PASTE NOTES/TRANSCRIPT/IDEA]

Create:
1) One X thread (hook + 5-7 posts + CTA)
2) One LinkedIn post (strong opening, clear structure, CTA)
3) One short POV memo (300-500 words)
4) 10 backlog content ideas derived from the same source

Quality bar:
- Must be specific, not generic
- Must sound like my voice
- Must include concrete examples
- Must be publish-ready with minimal edits
```

## 4) Live Refinement Prompts (Use anytime)

### Prompt: Make it sharper
```text
Rewrite this to be 30% tighter, more opinionated, and more actionable.
Remove filler. Keep only high-signal language.

Text:
[PASTE]
```

### Prompt: Make it sound like me
```text
Rewrite this in my voice:
- Direct
- Executive-level clarity
- Confident but not hypey
- Practical and specific

Text:
[PASTE]
```

### Prompt: Turn into slides/talking points
```text
Convert this into live talking points for a 3-minute segment.
Include:
- Opening line
- 3 key points
- One concrete example
- Closing line

Source:
[PASTE]
```

## 5) End-of-Event Prompt: Publish to GitHub + Attendee Guide

### Prompt: Generate attendee guide from live outputs
```text
Create a polished attendee guide titled:
"What We Built Today: 3 AI Workflows for CEOs and Knowledge Workers"

Include:
1) What we covered in the session
2) The 3 use cases and when to use each
3) Copy/paste prompts for each use case
4) Quick-start setup checklist
5) Common mistakes and fixes
6) 7-day action plan to implement this system

Format in clean Markdown, ready for a GitHub README.
```

### Prompt: GitHub publish checklist
```text
I am about to publish this live to GitHub.

Generate:
1) Suggested repo name options
2) Final folder structure
3) README outline
4) A concise first commit message
5) A 3-line announcement I can say live while sharing the repo
```

## 6) Event Day Checklist

- Open this prompt pack in one tab and your AI tool in another.
- Pre-fill placeholders (`[COMPANY]`, `[GOALS]`, etc.) before going live.
- Keep 1-2 real examples ready per use case.
- Use the refinement prompts if output is too generic.
- End by generating the attendee guide and pushing to GitHub.
