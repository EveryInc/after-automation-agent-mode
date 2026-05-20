# Starter prompts

Use these prompts with **After Automation** and the companion repo. They are designed for a back-and-forth session with an agent, not a one-shot answer.

For prompts tied to the essay's objections, use [`objections-and-responses.md`](objections-and-responses.md).

## Understand the argument

**Best for:** getting the clean version of Dan's thesis.

```text
Use "After Automation" and the companion repo to explain the argument in 10 bullets. Then give me the cleanest one-sentence version of the thesis.

Do not turn this into a generic AI summary. Preserve the paradox: Every uses AI aggressively and still has more human work to do.
```

## Inspect the evidence

**Best for:** choosing a claim, auditing the sources, and grappling with the strongest unresolved questions.

```text
Use the companion repo to help me inspect the evidence behind "After Automation."

First, list 5-7 important claims from the essay that are worth auditing. For each one, give me a short label and one sentence on why it matters. Then ask me which claim I want to inspect.

After I pick a claim, audit it with me. Return:
1. the best evidence in the repo;
2. the strongest unresolved question or counterexample;
3. where the evidence is strong, weak, or incomplete;
4. what source I should read if I want to go deeper.

Keep it conversational. Do not defend the essay by default, and do not bury me in sources before I choose the claim.
```

## Apply it to my work

**Best for:** turning the essay into a workflow, automation, or artifact you can try this week.

```text
I want to apply "After Automation" to my own work.

If you have access to my workspace, first inspect context before interviewing me: recent project files, README or AGENTS instructions, docs, notes, commits, issue lists, calendars, or other connected tools that show how I actually work.

Then ask up to five questions only for context you still need.

Return:
1. work I do that is stable-frame enough for an agent;
2. work where my judgment, framing, or specificity is the point;
3. places where generic AI output creates sameness or risk;
4. review loops I should add;
5. one human-agent workflow I should try this week;
6. the prompt, checklist, doc, or repo file I should save so the workflow compounds next time.
```
