# Every AI-native workflows

These are public patterns from how Every works with agents. They are included so readers can steal the operating model, not just read about it.

## The common pattern

Across coding, writing, support, product, design, events, and growth, the useful loop is:

1. A human chooses a frame worth working inside.
2. An agent performs a large amount of execution.
3. A domain expert reviews accuracy, risk, voice, context, and responsibility.
4. The learning gets saved as a prompt, checklist, guide, repo rule, eval, or tool.

That is the practical meaning of the essay's claim: when AI makes competence cheap, the valuable human work moves toward framing, review, and compounding.

## Recent public workflows to steal

These examples are recent, public, and practical. They are better prompts for the reader than a generic "use AI at work" list.

| Date | Public example | Workflow to steal | Why it matters for the essay |
|---|---|---|---|
| 2026-05-13 | ["Mining Your Life for Context"](https://every.to/context-window/mining-your-life-for-context) | Connect the places where your thinking already lives, ask an agent to find everything you have said about a topic, group the strongest threads, cite sources, and turn them into an outline. | The agent does not replace judgment. It retrieves and structures the human's existing judgment. |
| 2026-05-12 | ["The Fallacy of the 16-hour Agent"](https://every.to/context-window/the-fallacy-of-the-16-hour-agent) | Improve an agent skill by writing eval cases first, including cases that should not trigger the skill, then turn failures into standing lessons. | Long-running agents need tests, guardrails, and review signals, not just more runtime. |
| 2026-05-05 | ["The Dawn of Codex-native Apps"](https://every.to/context-window/the-dawn-of-codex-native-apps) | Write a one-page inbox operating manual, let a coding agent work through the inbox in Cora, and keep drafts and decisions visible in a Proof document before sending. | Delegation works when the review loop stays visible and accountable. |
| 2026-04-29 | ["Compute Is the New Cash"](https://every.to/context-window/compute-is-the-new-cash) | Turn support feedback into product issues, deduplicate related requests, route small issues to a coding agent, and keep larger ones in a close human-agent loop. | Agents increase throughput, but prioritization and product judgment stay human. |
| 2026-04-28 | ["One App to Rule All Knowledge Work"](https://every.to/context-window/one-app-to-rule-all-knowledge-work) | Give a coding agent access to the tools you use, ask it to identify five automations that would remove friction, run the easiest one for a week, and audit the misses. | The best use cases often come from inspecting real work, not imagining abstract prompts. |
| 2026-04-24 | ["Model Wars"](https://every.to/context-window/model-wars) | Screen-record a product flow, ask a model to storyboard from the real UI, iterate on the storyboard, then have a coding agent build the video in Remotion. | The human supplies the frame and ground truth; the agent turns that frame into a polished artifact. |
| 2026-04-21 | ["Mini-Vibe Check: Claude Design Isn't for Designers-Yet"](https://every.to/context-window/mini-vibe-check-claude-design) | Give an agent a dedicated X feed of trusted AI security sources, run scheduled scans, and route relevant vulnerability alerts to Slack with severity tags. | Bounded monitoring is useful when the source set, cadence, output, and human owner are explicit. |

## Workflow patterns

### 1. Mine scattered thinking before drafting

**Use when:** the reader needs to write, decide, or brief someone, and their best thinking is scattered across Slack, Notion, Drive, transcripts, voice notes, old docs, or project folders.

**Agent job:** search the places where the human already thinks, group the strongest threads, cite sources, and produce an outline.

**Human job:** name the deliverable, constrain the source set, choose what argument to make, and decide what does not belong.

**Reusable artifact:** a source map, outline, and prompt that can be reused for future drafts.

**Public source:** "Mining Your Life for Context."

### 2. Build evals before long-running agents

**Use when:** someone wants an agent to run longer, trigger automatically, or make decisions without constant supervision.

**Agent job:** draft test cases, run against realistic examples, and surface failure modes.

**Human job:** decide what should trigger the workflow, what should not trigger it, and what failure is unacceptable.

**Reusable artifact:** eval cases, trigger rules, and standing lessons.

**Public source:** "The Fallacy of the 16-hour Agent."

### 3. Make delegation visible

**Use when:** an agent is operating in a high-stakes or messy surface like email, customer support, calendar, CRM, or a publishing queue.

**Agent job:** follow an operating manual, draft decisions, and record actions in a review surface.

**Human job:** approve sends, update the manual, and own edge cases.

**Reusable artifact:** the operating manual plus a visible review doc.

**Public source:** "The Dawn of Codex-native Apps."

### 4. Turn support feedback into product work

**Use when:** customer support has become a pile of repeated asks, rough edges, and unclear escalation paths.

**Agent job:** cluster feedback, create product issues, deduplicate related asks, and route simple fixes.

**Human job:** decide priority, product meaning, customer repair, and what should become policy, docs, or tooling.

**Reusable artifact:** a triage rubric and issue-routing workflow.

**Public source:** "Compute Is the New Cash."

### 5. Move one knowledge-work loop into a project folder

**Use when:** a recurring workflow sprawls across tabs, docs, tools, and memory.

**Agent job:** inspect the folder and connected tools, draft the artifact, run checks, and leave notes.

**Human job:** decide the outcome, review in the destination app, and keep the folder's instructions current.

**Reusable artifact:** a folder with instructions, source files, prompts, review criteria, and prior decisions.

**Public sources:** "One App to Rule All Knowledge Work" and "The Folder Is the Agent."

### 6. Ask for confidence before shipping

**Use when:** an agent has produced a PR, draft, plan, campaign, spreadsheet, or customer-facing artifact.

**Agent job:** score confidence, justify the score, name unresolved risks, and revise if below the threshold.

**Human job:** decide whether the confidence claim is credible and inspect the artifact itself.

**Reusable artifact:** a pre-ship confidence prompt and review checklist.

**Public source:** "You're the Manager Now."

### 7. Define team agents by jobs, not personalities

**Use when:** a team wants to roll out agents broadly.

**Agent job:** own one recurring responsibility with a clear source of truth, output, cadence, and review path.

**Human job:** design the job, maintain the source of truth, and evaluate whether the agent is helping.

**Reusable artifact:** an agent job description and operating manual.

**Public source:** "We Gave Every Employee an AI Agent. Here's What We're Doing Differently Now."

## Prompt

```text
Use these Every workflow patterns to audit my team.

First, inspect any available non-sensitive context about how we work: project folders, docs, issue lists, pull requests, meeting notes, calendars, or local instructions.

Then return:
1. the strongest workflow opportunity;
2. the human frame;
3. the agent execution step;
4. the review loop;
5. the reusable artifact we should create;
6. what we should cut or avoid because it is too generic, risky, or not worth the coordination cost.
```
