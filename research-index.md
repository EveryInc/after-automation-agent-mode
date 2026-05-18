# Research Index

This is a curated launch index, not the full source archive.

## How To Read Source Status

- `public`: safe public source URL.
- `public-safe-summary`: internal source summarized without raw private links or identifying details.
- `needs-provenance`: do not state as fact until checked.
- `cut-but-recoverable`: useful for later expansion, not launch-critical.

## Best Launch Sources

### 1. Senior Engineer benchmark

- **Status:** needs-provenance for exact scores and model comparisons.
- **Summary:** Dan's benchmark tests whether an agent can diagnose and plan a first-principles rewrite of a broken production codebase. The interesting point is not only the score. It is that changing the prompt/frame can dramatically change what the model does.
- **Supports:** benchmarks measure capability inside human-built frames.
- **Use with:** `benchmarks/senior-engineer-benchmark.md`.

### 2. GDPVal task prompts

- **Status:** public.
- **Summary:** GDPVal tests model performance on expert work tasks, but the tasks include substantial human framing: role, objective, inputs, constraints, sample criteria, and output format.
- **Supports:** "smuggled intelligence" and benchmark framing.

### 3. METR task-completion time horizons

- **Status:** public, exact row/date should be checked before final launch copy.
- **Summary:** Time-horizon benchmarks make model progress feel concrete and scary. They are important evidence of real progress, but still depend on task definitions, scoring, and benchmark worlds.
- **Supports:** chart psychosis and framed capability.

### 4. Humanity's Last Exam

- **Status:** public, exact dated leaderboard should be checked.
- **Summary:** HLE tracks model performance on difficult academic questions. It shows real progress but does not settle what happens in open-ended work with shifting goals.
- **Supports:** AI progress is real.

### 5. Fin and Waqqas customer-service case

- **Status:** public-safe-summary, approval required.
- **Summary:** Fin can handle a large amount of stable-frame support. Human support work remains crucial where the frame breaks: trust, policy, billing identity, escalation, reporting methodology, product feedback, and system design.
- **Supports:** demand for difference is new demand for experts.
- **Use with:** `case-studies/fin-waqqas-customer-service.md`.

### 6. Hidden work after AI replacement

- **Status:** public-safe-summary.
- **Summary:** Replacement claims often hide work that reappears as QA, escalation, prompt maintenance, knowledge-base maintenance, manager review, customer repair, or engineering cleanup.
- **Supports:** AI often moves work rather than simply eliminating it.

### 7. AI-pilled practitioner field notes

- **Status:** public-safe-summary and public source links after quote review.
- **Summary:** First-person material across customer support, admin, sales, design, translation, technical writing, paralegal work, and voice/broadcast shows a mixed labor story: replacement, augmentation, degradation, and new supervision work.
- **Supports:** real worker outcomes are mixed.

### 8. NBER customer-support productivity study

- **Status:** public.
- **Summary:** Generative AI assistance can improve productivity for support agents, especially newer or less experienced workers.
- **Supports:** AI can raise the floor of competence.

### 9. Klarna customer-service example

- **Status:** public.
- **Summary:** Klarna is a real example of AI support automation and the partial return of human support for more complex cases.
- **Supports:** routine work can be automated while trust-sensitive work remains human.

### 10. Commonwealth Bank call-center reversal

- **Status:** public.
- **Summary:** A bank reversed AI-linked support cuts after call volumes and implementation realities complicated the plan.
- **Supports:** replacement has brakes: customers, quality, unions, volume, and workflow realities.

### 11. Every internal AI-native workflows

- **Status:** public-safe-summary.
- **Summary:** Every uses agents across coding, writing, operations, customer support, design, product management, inbox work, source mining, security monitoring, and growth workflows. The useful pattern is not "AI does all the work"; it is human framing, agent execution, expert review, and compounding into reusable artifacts.
- **Supports:** Every as an inside-view anomaly.
- **Use with:** `case-studies/every-ai-native-workflows.md`.

### 12. Compound Engineering

- **Status:** public.
- **Summary:** Every's engineering method turns agent work into a loop: plan, work, review, compound. It is a practical example of human-agent work moving up a level.
- **Supports:** new expert work emerges around framing, review, and compounding systems.

### 13. Codex as knowledge-work operating system

- **Status:** public.
- **Summary:** Recent Every coverage shows Codex moving beyond code into email triage, go-to-market planning, KPI tracking, recruiting, business-document review, and tool-building. The pattern is a project folder plus connectors plus review in the destination app.
- **Supports:** coding agents are becoming general-purpose knowledge-work agents.
- **Use with:** `workflows/codex-power-user-workflow.md`, `case-studies/every-ai-native-workflows.md`.

### 14. Dan's Codex inbox workflow

- **Status:** public.
- **Summary:** Dan's inbox-zero workflow uses a one-page operating manual, Codex, Cora, and a Proof document. The agent sweeps the inbox and drafts decisions, while the human reviews in a visible shared document before anything sends.
- **Supports:** delegation and close collaboration are different modes, and serious workflows need visible review loops.
- **Use with:** `case-studies/every-ai-native-workflows.md`.

### 15. Mining scattered thinking before drafting

- **Status:** public.
- **Summary:** A recent Context Window workflow recommends connecting an agent to Slack, Notion, Drive, meeting transcripts, and voice notes, then asking it to find what you have already said on a topic and turn the strongest threads into a draft outline.
- **Supports:** AI creates leverage when it helps retrieve and structure human judgment, not when it invents generic prose from scratch.
- **Use with:** `case-studies/every-ai-native-workflows.md`.

### 16. Agent watchdog workflows

- **Status:** public.
- **Summary:** Every describes assigning an agent a bounded monitoring job, such as reading a curated feed for AI-stack vulnerabilities and surfacing relevant alerts.
- **Supports:** agents are useful when source set, output, cadence, and human response ownership are explicit.
- **Use with:** `case-studies/every-ai-native-workflows.md`.

### 17. The folder as the agent interface

- **Status:** public.
- **Summary:** Every's recent writing on folder-based agents shows a practical pattern: agents become useful when a project folder contains instructions, architecture/context docs, prompts, and source files in a stable reading order.
- **Supports:** agent work compounds when context is stored as files, not trapped in one-off chats.
- **Use with:** `case-studies/every-ai-native-workflows.md`, `workflows/codex-power-user-workflow.md`.

### 18. Confidence check before shipping

- **Status:** public.
- **Summary:** Austin's confidence-check workflow asks an agent to rate its confidence before shipping and to find improvements if confidence is below the threshold. The point is not that the number is objectively true; it is that the agent must surface uncertainty and improve before handoff.
- **Supports:** human-plus-agent workflows need explicit review gates.
- **Use with:** `case-studies/every-ai-native-workflows.md`.
