# Every AI-native workflows

These are public patterns from how Every works with agents. They are included so readers can steal the operating model, not just read about it.

## The common pattern

Across coding, writing, support, events, product, and design, the useful pattern is:

1. A human chooses a frame worth working inside.
2. An agent performs a large amount of execution.
3. A domain expert reviews taste, accuracy, risk, and responsibility.
4. The learning gets saved as a prompt, checklist, guide, repo, or tool.

That is the practical meaning of "demand for difference is new demand for experts."

## Recent public workflows to steal

These examples are recent, public, and practical.

| Date | Public example | Workflow to steal | Why it matters for the essay |
|---|---|---|---|
| 2026-05-13 | ["Mining Your Life for Context"](https://every.to/context-window/mining-your-life-for-context) | Connect the places where your thinking already lives, ask an agent to find everything you have said about a topic, group the strongest threads, cite sources, and turn them into an outline. | The agent does not replace judgment; it retrieves and structures the human's existing judgment. |
| 2026-05-12 | ["The Fallacy of the 16-hour Agent"](https://every.to/context-window/the-fallacy-of-the-16-hour-agent) | Improve an agent skill by writing 10 eval cases first, including cases that should not trigger the skill, then turn failures into standing lessons. | Long-running agents need tests, guardrails, and review signals, not just more runtime. |
| 2026-05-05 | ["The Dawn of Codex-native Apps"](https://every.to/context-window/the-dawn-of-codex-native-apps) | Write a one-page inbox operating manual, let a coding agent work through the inbox in Cora, and keep every draft and decision visible in a Proof document before sending. | Delegation works when the human review loop stays visible and accountable. |
| 2026-04-29 | ["Compute Is the New Cash"](https://every.to/context-window/compute-is-the-new-cash) | Turn support feedback into Linear issues, use triage intelligence to deduplicate related requests, then route small issues to a coding agent and larger ones to a closer human-agent loop. | Agents increase product throughput, but prioritization and product judgment stay human. |
| 2026-04-28 | ["One App to Rule All Knowledge Work"](https://every.to/context-window/one-app-to-rule-all-knowledge-work) | Give a coding agent access to the tools you use, ask it to identify five automations that would remove friction, run the easiest one for a week, and audit the misses. | The best use cases often come from inspecting real work, not imagining abstract prompts. |
| 2026-04-24 | ["Model Wars"](https://every.to/context-window/model-wars) | Screen-record a product flow, ask a model to storyboard from the real UI, iterate on the storyboard, then have a coding agent build the video in Remotion. | The human supplies taste and ground truth; the agent turns that frame into a polished artifact. |
| 2026-04-21 | ["Mini-Vibe Check: Claude Design Isn't for Designers-Yet"](https://every.to/context-window/mini-vibe-check-claude-design) | Give an agent a dedicated X feed of trusted AI security sources, run scheduled scans, and route relevant vulnerability alerts to Slack with severity tags. | Bounded monitoring is useful when the source set, cadence, output, and human owner are explicit. |

## Pattern 1: Compound engineering

**What the agent does:** drafts plans, writes code, runs tests, reviews diffs, searches prior learnings, and captures reusable solutions.

**What the human does:** chooses the product frame, judges tradeoffs, reviews risky changes, and decides what should become team knowledge.

**What readers can steal:** do not only ask an agent to finish a task. Ask it to leave behind a reusable trail: the plan, the review, the test signal, and the learning that makes the next task easier.

**Public sources:** Compound Engineering guide, Compound Engineering plugin, Source Code essays.

## Pattern 2: Coding agents as knowledge-work operating systems

**Recent example:** In "One App to Rule All Knowledge Work," Every describes Austin running most of his daily workflow through a coding agent: email triage, go-to-market planning, KPI tracking, recruiting, and business-document review.

**What the agent does:** searches project context, drafts and reviews assets, builds small tools, analyzes data, and catches confidently wrong plans by checking against compound knowledge.

**What the human does:** chooses which work belongs in the agent environment, reviews final outputs in the destination app, decides when to use connectors, and keeps the agent focused on the actual business artifact.

**What readers can steal:** move one recurring knowledge-work loop out of scattered browser tabs and into a project folder with instructions, source files, and review rules. Review the final output where it will actually live: the email client, doc, spreadsheet, GitHub PR, CRM, or publishing system.

**Public source:** "One App to Rule All Knowledge Work."

## Pattern 3: The folder is the agent

**Recent example:** In "The Folder Is the Agent," Kieran describes running many agents by pointing each one at a folder with the right instructions, architecture notes, prompts, and context files.

**What the agent does:** reads the project folder, follows local instructions, operates on files, and leaves artifacts behind.

**What the human does:** curates the folder, decides what context belongs there, updates the reading order, and reviews the agent's output.

**What readers can steal:** treat the folder as the interface. Put the goal, sources, instructions, review criteria, and prior decisions where the agent can read them.

**Public source:** "The Folder Is the Agent."

## Pattern 4: Agent-native product management

**What the agent does:** turns research, transcripts, specs, docs, and user feedback into structured decisions, requirements, and execution plans.

**What the human does:** decides what problem matters, what tradeoffs are acceptable, what user flow should exist, and what success means.

**What readers can steal:** use agents to expand and stress-test product thinking, but keep ownership of the problem frame. The PM's leverage moves toward framing, sequencing, and judgment.

**Public sources:** Agent-native Product Management guide, Claude Code for Product Managers, Codex, and Cowork coverage.

## Pattern 5: Agent inbox zero

**Recent example:** In "The Dawn of Codex-native Apps," Dan's inbox workflow uses a one-page operating manual, a coding agent, Cora, and a Proof document so the agent can sweep the inbox while decisions stay visible.

**What the agent does:** follows rules for VIPs, auto-archiving, scheduling, summaries, and drafts; operates in the inbox; records every decision and draft in a shared document.

**What the human does:** writes the operating manual, reviews every draft and decision, approves sends, and updates the manual when the agent misunderstands.

**What readers can steal:** before delegating email, write down how the work should be done. Keep the agent's actions visible in a document instead of letting the inbox become an opaque automation surface.

**Public source:** "The Dawn of Codex-native Apps."

## Pattern 6: Mine scattered thinking before drafting

**Recent example:** In "Mining Your Life for Context," Every describes a workflow for turning Slack threads, Notion docs, voice memos, meeting transcripts, and earlier notes into a draft outline.

**What the agent does:** searches the places where you already think, groups the strongest threads, cites sources, and turns them into an outline.

**What the human does:** names the deliverable, constrains the source set, chooses which ideas are actually yours, and decides what argument to make.

**What readers can steal:** before asking an agent to draft, ask it to recover what you have already said. This avoids blank-page slop and makes the draft start from human judgment rather than generic model priors.

**Public source:** "Mining Your Life for Context."

## Pattern 7: Confidence check before shipping

**Recent example:** In "You're the Manager Now," Every describes Austin asking Claude Code for a confidence score before creating a pull request, then sending it back for improvements until it reaches a high-confidence threshold.

**What the agent does:** evaluates its own work, identifies uncertainty, finds improvements, and reports residual risk.

**What the human does:** decides whether the confidence claim is credible, reviews the actual artifact, and avoids chasing impossible certainty.

**What readers can steal:** before shipping agent work, ask for a confidence score and the reasons behind it. If the confidence is low, send the agent back to improve or surface the blocker.

**Public source:** "You're the Manager Now."

## Pattern 8: Customer support frame collision

**What the agent does:** handles stable-frame support where intent is clear, policy is known, and the answer is in the knowledge base.

**What the human does:** handles trust, escalation, billing identity, product confusion, reporting methodology, customer repair, and feedback loops.

**What readers can steal:** separate support work into stable-frame automation and broken-frame escalation. The point is not just ticket deflection; it is turning exceptions into better product, policy, docs, and tooling.

**Related file:** `case-studies/fin-waqqas-customer-service.md`.

## Pattern 9: Editorial and Proof workflows

**What the agent does:** drafts, restructures, checks claims, summarizes review threads, and produces alternate cuts.

**What the human does:** owns taste, line of argument, factual responsibility, audience fit, and final voice.

**What readers can steal:** make the document agent-readable. Clean markdown, source notes, comments, and structured prompts make a piece easier to review with an agent.

**Public sources:** Introducing Proof, The Dawn of Codex-native Apps, One App to Rule All Knowledge Work, Every writing and agent-native workflows.

## Pattern 10: Agent security watchdog

**Recent example:** In "Mini-Vibe Check: Claude Design Isn't for Designers-Yet," Every describes a workflow where an agent monitors a dedicated X feed for vulnerabilities relevant to the AI stack.

**What the agent does:** scans a curated source feed on a schedule, flags disclosures, and reports relevance to the stack.

**What the human does:** chooses trusted sources, defines the relevant stack, decides which alerts matter, and owns any response.

**What readers can steal:** give agents recurring monitoring jobs where the source set is bounded, the output is a short report, and the human keeps authority over the response.

**Public source:** "Mini-Vibe Check: Claude Design Isn't for Designers-Yet."

## Pattern 11: Events and launch work

**What the agent does:** turns positioning, notes, and prior material into run-of-show drafts, landing-page copy, social copy, invite lists, and follow-up assets.

**What the human does:** chooses the audience, message, offer, launch sequence, and quality bar.

**What readers can steal:** the agent can produce a large volume of launch material, but the expert job becomes sharper: what story should this launch tell, what should convert, and what should be cut?

## Pattern 12: Team agents with defined jobs

**Recent example:** In "We Gave Every Employee an AI Agent. Here's What We're Doing Differently Now," Brandon Gell and Willie Williams explain why Every is moving away from one personal agent per employee toward shared agents with defined team jobs.

**What the agent does:** owns a narrower recurring job, operates with clearer boundaries, and becomes a shared resource rather than a personality-driven sidekick.

**What the human does:** designs the job, chooses the workflow boundary, maintains the source of truth, and decides when a team-level agent is more appropriate than a personal assistant.

**What readers can steal:** before rolling out agents broadly, define the job. A team agent with a specific responsibility is easier to evaluate, maintain, and trust than a general-purpose personal agent for everyone.

**Public source:** "We Gave Every Employee an AI Agent. Here's What We're Doing Differently Now."

## Prompt

```text
Use these Every workflow patterns to audit my team. For each pattern, tell me where we already have stable-frame agent work, where we have frame-collision work, what expert review loop is missing, and what reusable artifact we should create this month.
```
