# Cowork for CEOs

This repo is a simple workshop kit.

If you are not technical, start here:

## Start Here First (Best for Beginners)
- Watch your Claude Cowork setup video:
  [10 Tips for Getting Started with Claude Cowork](https://youtu.be/jvkDGx35rZ8)
- Follow your full getting-started guide:
  [getting-started-with-claude-cowork](https://github.com/JJenglert1/getting-started-with-claude-cowork)

If this is your first time using Cowork, do the guide above first, then come back here for workshop prompts.

## What Is In Here?
- `workshop-attendee-guide.md`  
  The main step-by-step guide. Use this first.
- `live-event-prompt-pack.md`  
  Copy/paste prompts used in the live event.
- `live-event-outline.md`  
  The 40-minute event agenda.
- `live-event-preview.html`  
  A simple webpage to preview the guides in your browser.

## Fast Start (5 Minutes)
1. Open the getting-started guide repo above if you are brand new.
2. Open `workshop-attendee-guide.md`.
3. Find a prompt you want to use.
4. Replace the placeholder text in brackets (example: `[COMPANY]`).
5. Paste it into your AI tool.
6. Save the result and reuse it.

## Top-Level Prompts (Copy/Paste)
Use these right now without opening any other file.

### 1) CEO Coach Prompt
```text
Act as my CEO coach.

Company context:
- Company: [COMPANY]
- Stage: [STAGE]
- Primary goals this quarter: [GOALS]
- Top constraints: [CONSTRAINTS]
- Key metrics: [KPIS]
- Current risks: [RISKS]

Build:
1) A daily decision protocol
2) A weekly strategy review agenda
3) A prioritization rubric
4) A Stop/Start/Continue leadership framework
5) Escalation triggers for CEO intervention

Output:
- CEO dashboard (top 5 priorities)
- Weekly CEO agenda template
- Decision memo template
- 5 Friday reflection questions
```

### 2) Advisory Sub-Agents Prompt
```text
Create a pre-launch CEO advisory board of sub-agents:
1) Operator
2) Skeptic
3) Customer Advocate
4) Finance Partner
5) Risk/Legal Reviewer

For each agent provide:
- Mission
- 7 evaluation questions
- Failure modes detected
- Scoring rubric (1-5)
- Ship / Fix / Stop logic

Then run all agents on this launch:
- Launch plan: [PASTE]
- Assumptions: [PASTE]
- Constraints: [PASTE]

Return:
1) Executive verdict (Ship/Fix/Stop)
2) Top 5 risks
3) Contradictions across agents
4) Required fixes
5) Revised launch plan
```

### 3) Thought Leader Pipeline Prompt
```text
Build me a thought leadership content pipeline for [INDUSTRY].

Profile:
- Expertise areas: [AREAS]
- POV themes: [THEMES]
- Audience: [AUDIENCE]
- Platforms: X + LinkedIn
- Posting target: [FREQUENCY]
- Brand voice: [VOICE]

Create:
1) Idea capture system
2) Topic scoring model
3) Drafting workflow
4) Editing quality checklist
5) Distribution cadence
6) Repurposing flow (one idea -> multiple assets)
7) Weekly review loop

Then generate from this source:
- Source material: [PASTE]

Output:
- 1 X thread
- 1 LinkedIn post
- 1 short POV memo
- 10 backlog content ideas
```

## Which File Should I Use?
- If you are **new to Cowork**: start with the getting-started guide repo first.
- If you want to **learn and follow along**: use `workshop-attendee-guide.md`.
- If you want to **copy prompts quickly**: use `live-event-prompt-pack.md`.
- If you want to **see the event structure**: use `live-event-outline.md`.

## Open the Preview Page
If you want a clean, readable page view:

1. Download this repo or open it locally.
2. Run this command in the folder:

```bash
python3 -m http.server 8000
```

3. Open this in your browser:  
   `http://localhost:8000/live-event-preview.html`

## No Coding Required
You do not need to code to use this repo.
Everything is designed as copy/paste templates and checklists.

## Need Help?
Start with `workshop-attendee-guide.md` and complete only one use case first:
- CEO Coach
- Advisory Sub-Agents
- Thought Leader Pipeline
