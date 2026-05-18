# Codex Power-User Workflow

Use this when you want Agent Mode to become a working session, not a reading exercise.

## Setup

Open this repo in Codex. Ask Codex to read:

- `AGENTS.md`
- `agent-mode.md`
- `claims.md`
- `prompts/starter-prompts.md`
- `case-studies/every-ai-native-workflows.md`

Then paste the essay text or link the essay if your environment can access it.

## First Prompt

```text
You are helping me use Dan Shipper's "The Tide Is Rising" as a working document. Read the repo instructions, then help me do three things:

1. Summarize the argument in a way that preserves the strongest version of the thesis.
2. Challenge the thesis with the strongest counterargument.
3. Design one human-agent workflow I can try this week.

Before applying it to my work, ask me up to five questions about my role, team, current AI use, and what I personally review for quality.
```

## The Artifact To Create

Ask Codex to create a short local file called `my-tide-workflow.md` with:

- your role and work context;
- stable-frame tasks an agent can attempt;
- frame-changing or judgment-heavy work that should stay human-led;
- review criteria;
- one workflow to run this week;
- what to save as reusable context, prompt, checklist, or code.

## Review Criteria

The workflow is good if:

- it creates a real artifact you would otherwise have made manually;
- the human judgment step comes before and after agent execution;
- failure teaches you something concrete;
- it identifies what should compound for next time;
- it does not require sensitive company, customer, legal, financial, or personnel data in an unapproved tool.

## Second Prompt

```text
Now critique the workflow you proposed. Where is it too generic? Where does it assume my work is more stable-frame than it is? What expert judgment did you underweight? Revise the workflow so it would survive contact with a real workday.
```

## Why This Matters

The manifesto argues that the practical race is human-plus-AI versus human-plus-AI. This workflow makes that claim falsifiable in your own work. If the agent can do useful execution inside your frame, you learn what to delegate. If it fails, you learn where your expertise actually lives.
