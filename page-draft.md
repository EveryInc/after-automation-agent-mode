# Agent Mode Page Draft

## Header

`$ cat ./the-tide-is-rising.md`

# The Tide Is Rising

The Tide Is Rising · Agent Mode

## Intro

Read the essay with an agent beside you.

Agent Mode turns Dan Shipper's piece in Every into a working surface: prompts, source notes, research trails, and Every workflows you can run in Codex, Claude Code, or another capable agent.

The standard essay view is still the canonical reading experience. Agent Mode is for readers who want to summarize the argument, attack it, inspect the evidence, and apply it to their own work.

## Connect your agent

Copy this once. It points your agent at the companion GitHub repo, tells it which files to read, and gives it enough context to summarize, challenge, and apply the argument.

```text
You are helping me read and use Dan Shipper's piece in Every, "The Tide Is Rising."

Use this companion GitHub repo as your source of truth:
https://github.com/EveryInc/tide-is-rising-agent-mode

If you can access GitHub or run shell commands, clone or open that repo first. Then read:
- README.md
- AGENTS.md
- agent-mode.md
- claims.md
- prompts/starter-prompts.md
- case-studies/every-ai-native-workflows.md
- sources/public-sources.md

Do not answer from the essay alone. Use the repo to summarize the argument, challenge it, inspect the evidence, and turn it into a workflow I can try.

Start by giving me:
1. the cleanest version of the core claim;
2. the strongest counterargument;
3. three Every workflow examples from the repo that I can steal;
4. one concrete human-agent workflow I can run this week.

If you cannot access GitHub directly, tell me what repo files you need me to paste or upload before you continue.
```

## Prompts

### Understand the argument

```text
Summarize the argument of "The Tide Is Rising" in 10 bullets. Then name the one claim I am most likely to misunderstand, explain why it is easy to misunderstand, and give me the cleanest version of the claim.
```

### Challenge the argument

```text
Give me the strongest counterargument to "The Tide Is Rising." Do not be polite; be accurate. Separate factual objections, conceptual objections, and labor-market objections. Then tell me what evidence would most weaken the piece and what evidence would most strengthen it.
```

### Inspect the evidence

```text
Use the companion repo to investigate one claim from "The Tide Is Rising." Return the best evidence, the strongest counterargument, what the evidence does not prove, what would change the conclusion, and whether the source is public, public summary, or needs source checking.
```

### Apply it to my work

```text
I want to apply "The Tide Is Rising" to my own work. Ask me up to five questions about my role, team, and current AI use. Then tell me where AI is likely to create new expert work for me instead of simply removing work. Separate stable-frame tasks, frame-changing tasks, review loops, and one workflow I should try this week.
```

### Build a human-agent workflow

```text
Build me a practical human-agent workflow from "The Tide Is Rising" that I can try this week. Include the human judgment step, the agent execution step, the expert review step, what good looks like, and what failure would teach me.
```

### Turn AI anxiety into an action plan

```text
I am worried about what AI means for my work. Use "The Tide Is Rising" to audit my role. Separate work that is likely to become stable-frame automation, work where my expert judgment becomes more valuable, risks I should take seriously, and one concrete practice plan for the next 30 days.
```

## How Every uses this

Every's inside view is the reason this artifact exists. We use agents to write code, review drafts, build presentations, inspect customer support workflows, create events, and turn repeated work into reusable systems.

The public Every archive has a set of recent workflows readers can steal directly: mine scattered thinking before drafting, write evals before agent skills, run inbox review through a coding agent plus Proof, turn support feedback into a product queue, ask a coding agent to identify automations from real connected tools, storyboard product videos from screen recordings, and give an agent a bounded security feed to monitor.

The pattern is not "AI does the work." The pattern is:

1. A human chooses the frame.
2. An agent does a large amount of execution inside the frame.
3. An expert reviews the result against taste, context, risk, and responsibility.
4. The team compounds what worked into prompts, docs, repos, tools, and workflows.

That is the practical version of the essay's thesis: demand for difference becomes demand for people who can frame, review, and compound agent work.

## Every footer

Every is the only subscription you need to stay at the edge of AI. Come ride the models and live in the future with our apps, ideas, trainings, and community. Start your free trial at every.to/subscribe.
