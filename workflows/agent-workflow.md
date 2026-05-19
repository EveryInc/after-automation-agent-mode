# Agent workflow

Use this when you want Agent Mode to become a working session, not a reading exercise.

## Setup

Open this repo in Codex, Claude Code, OpenClaw, or another coding agent. Ask the agent to read:

- `README.md`
- `AGENTS.md`
- `claims.md`
- `prompts/starter-prompts.md`
- `case-studies/every-ai-native-workflows.md`

Only read `after-automation.md`, `research-index.md`, or files in `sources/` when the reader asks for deeper evidence or source work.

Then add any non-sensitive context about your work that the agent cannot already inspect.

## First prompt

```text
You are helping me read and use Dan Shipper's Every essay, "After Automation."

Use this companion repo as your source of truth. Start by reading README.md, AGENTS.md, claims.md, prompts/starter-prompts.md, and case-studies/every-ai-native-workflows.md.

Then give me:
1. the cleanest version of the core claim;
2. the part of the argument most relevant to what you know about me;
3. one prompt I should run next based on my work, context, and goals.

If you can inspect my workspace, first inspect non-sensitive context before interviewing me: recent project files, README or AGENTS instructions, docs, notes, commits, issue lists, calendars, or connected tools that show how I actually work. Do not open or quote confidential customer, legal, financial, or personnel details unless I explicitly approve that source.
```

## Useful session modes

### Understand the argument

Use this when the reader wants the essay explained cleanly.

```text
Engage with the cleanest version of Dan Shipper's argument in "After Automation."

Use the companion repo. Give me:
1. the thesis in one sentence;
2. the argument in 7-10 bullets;
3. the claim readers are most likely to misunderstand;
4. why that misunderstanding is tempting;
5. the strongest version of the argument without hype.

Do not turn this into a generic AI summary.
```

### Inspect the evidence

Use this when the reader wants to grapple with whether the argument holds up.

```text
Use the companion repo to help me inspect the evidence behind "After Automation."

First, list 5-7 important claims in the essay that can be checked or argued with. Ask me which claim I want to inspect.

After I pick a claim, audit:
1. the best evidence in the repo;
2. the strongest unresolved question or counterexample;
3. where the evidence is strong, weak, or incomplete;
4. what source I should read more deeply if I want to keep pushing.

Keep this conversational. Help me grapple with the claim. Do not defend the essay by default, and do not bury the answer in sources.
```

### Apply it to my work

Use this when the reader wants a practical workflow.

```text
I want to apply "After Automation" to my own work.

If you have access to my workspace, first inspect available non-sensitive context before interviewing me: recent project files, README or AGENTS instructions, docs, notes, commits, issue lists, calendars, or other connected tools that show how I actually work. Do not open or quote confidential customer, legal, financial, or personnel details unless I explicitly approve that source.

Then ask up to five questions only for context you still need.

Return:
1. work I do that is stable-frame enough for an agent;
2. work where my judgment, framing, or specificity is the point;
3. places where generic AI output creates sameness or risk;
4. review loops I should add;
5. one workflow I should try this week;
6. the reusable artifact I should save so the workflow compounds next time.
```

## The artifact to create

Ask your agent to leave behind a short local file called `after-automation-workflow.md` with:

- the reader's role and work context;
- the piece of work being redesigned;
- the human framing step;
- the agent execution step;
- the review surface;
- what good looks like;
- what failure would teach;
- the prompt, checklist, doc, repo rule, or workflow file to save for next time.

## Review criteria

The workflow is good if:

- it creates a real artifact the reader would otherwise have made manually;
- the human judgment step comes before and after agent execution;
- failure teaches something concrete;
- it identifies what should compound for next time;
- it does not require sensitive company, customer, legal, financial, or personnel data in an unapproved tool.

## Second prompt

```text
Now critique the workflow you proposed. Where is it too generic? Where does it assume my work is more stable-frame than it is? What expert judgment did you underweight? Revise the workflow so it would survive contact with a real workday.
```
