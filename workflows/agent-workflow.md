# Agent workflow

Use this when you want Agent Mode to become a working session, not a reading exercise.

## Setup

Open this repo in Codex, Claude Code, or another coding agent. Ask the agent to read:

- `AGENTS.md`
- `the-tide-is-rising.md`
- `agent-mode.md`
- `claims.md`
- `prompts/starter-prompts.md`
- `case-studies/every-ai-native-workflows.md`

Then add any non-sensitive context about your work that the agent cannot already inspect.

## First Prompt

```text
You are helping me use Dan Shipper's "The Tide Is Rising" as a working document. Read the repo instructions, then help me do three things:

1. Summarize the argument in a way that preserves the strongest version of the thesis.
2. Inspect the evidence behind the claim most relevant to my work.
3. Design one human-agent workflow I can try this week.

If you have access to my workspace, inspect non-sensitive project files, docs, notes, commits, issue lists, calendars, or connected tools before interviewing me. Then ask up to five questions only for context you still need.
```

## The artifact to create

Ask your agent to create a short local file called `my-tide-workflow.md` with:

- your role and work context;
- stable-frame tasks an agent can attempt;
- frame-changing or judgment-heavy work that should stay human-led;
- review criteria;
- one workflow to run this week;
- what to save as reusable context, prompt, checklist, or code.

## Review criteria

The workflow is good if:

- it creates a real artifact you would otherwise have made manually;
- the human judgment step comes before and after agent execution;
- failure teaches you something concrete;
- it identifies what should compound for next time;
- it does not require sensitive company, customer, legal, financial, or personnel data in an unapproved tool.

## Second prompt

```text
Now critique the workflow you proposed. Where is it too generic? Where does it assume my work is more stable-frame than it is? What expert judgment did you underweight? Revise the workflow so it would survive contact with a real workday.
```

## Why this matters

The essay argues that the practical race is human-plus-AI versus human-plus-AI. This workflow makes that claim falsifiable in your own work. If the agent can do useful execution inside your frame, you learn what to delegate. If it fails, you learn where your expertise actually lives.
