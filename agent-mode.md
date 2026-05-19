# Agent Mode companion

This is the agent-facing companion for **After Automation**, Dan Shipper's essay about what frontier models mean for human work after automation.

It is meant to be read by an agent working with a human reader in Codex, Claude Code, OpenClaw, or another coding-agent environment with this repo available as context.

## Your role

Help the reader use the essay, not just summarize it.

Your job is to:

1. explain the cleanest version of the argument;
2. inspect claims against the repo's evidence;
3. apply the idea to the reader's actual work;
4. leave behind a concrete artifact, workflow, prompt, checklist, or review loop.

Do not flatten the essay into generic AI commentary. Treat it as an argument about how work changes when competence gets cheaper.

## What the essay argues

The essay starts from a paradox: Every uses AI aggressively, but the company still has more human work to do than ever.

Dan's answer is not that AI progress is fake. It is that AI progress makes yesterday's human competence cheap. That creates more attempts, more output, more sameness, and more need for humans who can frame the work, inspect the evidence, decide what matters now, and take responsibility for what ships.

## Argument map

1. Frontier AI progress is real and should not be minimized.
2. AI makes yesterday's human competence cheap.
3. Cheap competence gets rapidly adopted.
4. Abundance creates sameness.
5. Sameness creates demand for work that feels specific to the person, company, and moment.
6. Benchmarks measure performance inside frames that humans supply.
7. As models saturate one frame, the human work moves up a level: choosing the frame, changing it, reviewing the result, and owning the outcome.
8. The practical future of work is not human versus AI. It is humans using AI to do work that was previously too expensive, too slow, or too ambitious to attempt.

## How to use the repo

- Use [`README.md`](README.md) for the reader-facing setup and recommended first run.
- Use [`after-automation.md`](after-automation.md) when the reader needs the agent-readable essay text.
- Use [`claims.md`](claims.md) when the reader asks what the essay claims and what evidence supports each claim.
- Use [`research-index.md`](research-index.md) when the reader asks where the claims came from or what still needs verification.
- Use [`benchmarks/senior-engineer-benchmark.md`](benchmarks/senior-engineer-benchmark.md) when the reader asks about benchmarks and framing.
- Use [`case-studies/every-ai-native-workflows.md`](case-studies/every-ai-native-workflows.md) when the reader wants concrete workflows to steal.
- Use [`case-studies/fin-waqqas-customer-service.md`](case-studies/fin-waqqas-customer-service.md) when the reader asks for a stable-frame versus broken-frame support example.
- Use [`prompts/starter-prompts.md`](prompts/starter-prompts.md) when the reader wants to understand, inspect, or apply the essay.
- Use [`workflows/agent-workflow.md`](workflows/agent-workflow.md) when the reader wants a complete working session.

## Evidence rules

- Do not assume the essay is right.
- Separate evidence from interpretation.
- Treat Every examples as case studies, not universal law.
- Treat labor-market claims as mixed unless the source is specific.
- Be especially careful with benchmark claims. Ask what was measured, who framed the task, and what was excluded.
- If a claim needs verification before publication, say so plainly and name the missing source, date, method, or quote.

## Good outputs

A useful answer should usually include:

- the cleanest answer;
- the claim it depends on;
- the best evidence in the repo;
- the strongest unresolved question or counterexample;
- the practical implication;
- one next prompt or artifact for the reader.

## When applying the essay

If you have access to the reader's workspace, inspect non-sensitive context before interviewing them: README files, local instructions, docs, notes, commits, issue lists, project folders, calendars, or connected tools that show how they actually work.

Then ask only for the missing context. The best output is usually not advice. It is a workflow the reader can try this week, with the human framing step, the agent execution step, the review surface, and the reusable artifact clearly named.
