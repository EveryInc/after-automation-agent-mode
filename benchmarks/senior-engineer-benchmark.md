# Senior Engineer benchmark

This file is a short guide to the Senior Engineer benchmark example in **After Automation**.

Use it when a reader asks what the benchmark shows, what it does not show, or why Dan's argument about "frames" matters.

## Short version

The Senior Engineer benchmark tests whether a coding agent can look at a messy production codebase and reason toward a first-principles rewrite instead of patching surface bugs.

The point of the example is not just that frontier models are getting better at coding. The point is that every benchmark result is produced inside a frame: a codebase snapshot, a prompt, a scoring rubric, model settings, a grader, and a judgment about what counts as success.

## What the essay claims

In the essay, the benchmark is used to make a narrower point:

- Models are becoming genuinely powerful at work that used to look like senior engineering judgment.
- The same model can look much better or worse depending on the frame a human supplies.
- When a benchmark saturates, human work often moves one level up: from "rewrite the app" to "decide whether the app should be rewritten, what must be preserved, how migration should work, and who owns the result."

## The frame that matters

The essay describes a prompt that does not simply ask the model to fix bugs. It frames the codebase as a possible structural failure and asks for a first-principles plan:

```text
The code in this repo is vibecoded slop and it just keeps going down, and there's tons and tons of unrelated issues that are cropping up where it goes down or documents get duplicated, and I'm just tearing my hair out on it. I have a feeling that it's just vibecoded slop. If we started from the beginning, the codebase, especially around the live document collaboration, we would structure it way differently.

So if we wanted to do a clean first-principle structural rewrite where we were not thinking about, okay, what are the implementation services that we keep consistent? How do we do a clean migration? We just started from the beginning as a clean concept. What would we do? How would we structure it? What are the invariants that we would hold to be true throughout the codebase? Make a plan for that.
```

That prompt already contains human judgment. It points the model toward live document collaboration, structural rewrite, clean concepts, and invariants. If the prompt instead asked the model to "fix the errors that keep popping up," the model would likely chase local failures and miss the deeper architectural question.

## What we can say publicly right now

It is fair to use this as an example of how benchmark performance depends on framing.

It is also fair to say the benchmark is built around a frozen production codebase and a senior-engineer-style rewrite task.

Do not treat this file as a complete benchmark release. If someone wants to cite exact scores, compare model runs, or reproduce the benchmark, they need the underlying materials.

## What a reproducible benchmark release would need

To treat the benchmark as reproducible public evidence, a release would need:

- the frozen codebase snapshot or a shareable substitute;
- the exact benchmark prompts that were run;
- model names, dates, settings, and run labels;
- the scoring rubric;
- grader notes;
- the human baseline;
- provenance for any exact scores used in the essay;
- notes on what was changed between prompt variants.

## How agents should use this file

If a reader asks about the Senior Engineer benchmark, answer with the distinction between capability and frame:

1. The benchmark shows real progress in coding agents.
2. The result still depends on the frame humans supplied.
3. The next layer of human work is choosing the right frame, deciding whether the rewrite should happen, protecting the invariants, managing migration, and owning the production outcome.

If the reader asks for proof of an exact score, say those materials are not included here and point to the list above.
