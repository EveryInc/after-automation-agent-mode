# After Automation: Agent Mode

This repo is the companion workflow for Dan Shipper's Every essay, **After Automation**.

Use it with Codex, Claude Code, OpenClaw, or another coding agent to turn the essay into a working session. The goal is not to read every file. The goal is to pick one useful path: understand the argument, inspect the evidence, or apply the idea to your own work.

The essay starts from a paradox: Every has automated everything it can, and yet there is more human work to do than ever. Dan's argument is that AI makes yesterday's competence cheap. Cheap competence creates more attempts. More attempts create sameness. Sameness creates new demand for human framing, judgment, review, and specificity.

## Connect your agent

Paste this into your coding agent:

```text
You are helping me read and use Dan Shipper's Every essay, "After Automation."

Use this companion GitHub repo as your source of truth:
https://github.com/EveryInc/after-automation-agent-mode

If you can access GitHub or run shell commands, clone or open that repo first. Start with only these files:
- README.md
- AGENTS.md
- claims.md
- prompts/starter-prompts.md
- case-studies/every-ai-native-workflows.md

Do not answer from the essay alone. Use the repo to help me do one useful thing with the argument.

Start by giving me:
1. the cleanest version of the core claim;
2. the part of the argument most relevant to what you know about me, if you have enough context;
3. otherwise, the most useful prompt from the repo to start with.

If I ask to inspect evidence, then read `claims.md`, `sources/public-sources.md`, and `benchmarks/senior-engineer-benchmark.md`. If I ask to apply the essay to my work, inspect available workspace context before interviewing me.

If you cannot access GitHub directly, tell me the smallest set of repo files you need me to paste before you continue.
```

## Start here

| I want to... | Use this |
|---|---|
| Give my agent operating instructions | [`AGENTS.md`](AGENTS.md) |
| Copy starter prompts | [`prompts/starter-prompts.md`](prompts/starter-prompts.md) |
| Inspect the core claims | [`claims.md`](claims.md) |
| Study Every workflow examples | [`case-studies/every-ai-native-workflows.md`](case-studies/every-ai-native-workflows.md) |
| Go deeper on benchmarks | [`benchmarks/senior-engineer-benchmark.md`](benchmarks/senior-engineer-benchmark.md) |
| Check public sources | [`sources/public-sources.md`](sources/public-sources.md) |

## What this repo is for

This repo answers three practical questions:

- **What is the argument?** AI progress makes more human work, not less, because cheap competence creates more attempts, more sameness, and more need for human framing and judgment.
- **What should I inspect?** Use the claims map and source notes to pick one part of the argument, look at the best available evidence, and identify the strongest open question.
- **What should I do with it?** Use the prompts to build one human-agent workflow where the human frames the work, the agent executes, and an expert reviews the result.

## What to copy

Start with one of these:

- **Understand the argument** if you want a clean first pass.
- **Inspect the evidence** if you want the agent to list claims, let you pick one, and audit the sources with you.
- **Apply it to my work** if you want the agent to inspect your context and propose a workflow, automation, or artifact you can try this week.

## Recent workflows to steal

The fastest way to make the essay useful is to copy one public Every workflow and run it on your own work:

- Mine your Slack, docs, notes, and transcripts before drafting.
- Use a coding agent plus Proof to review inbox drafts before anything sends.
- Turn support feedback into a product queue that routes small fixes to a coding agent.
- Ask a coding agent to inspect your real connected tools and suggest automations worth testing.
- Add a confidence check before shipping agent work.
- Treat a project folder as the agent interface: instructions, sources, prompts, and review criteria in one place.
- Define team agents by job, source of truth, allowed actions, and review loop.

See [`case-studies/every-ai-native-workflows.md`](case-studies/every-ai-native-workflows.md) for the examples and links.

## What is Every?

Every is [the only subscription you need to stay at the edge of AI](https://every.to/subscribe). Come ride the models and live in the future with our apps, ideas, trainings, and community.
