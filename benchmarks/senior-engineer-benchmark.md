# Senior Engineer benchmark

This page explains the benchmark example in **The Tide Is Rising**.

## Short version

The Senior Engineer benchmark tests whether a coding agent can diagnose and plan a first-principles rewrite of a broken production codebase. The important lesson is not just that newer models score better. The important lesson is that the benchmark result depends on the frame a human gives the model.

## What the benchmark is testing

The benchmark gives a coding agent a production codebase that has accumulated deep structural problems. The task is to reason like a senior engineer: find the conceptual core of the failures and propose a clean rewrite strategy.

The benchmark is meant to test:

- architectural diagnosis;
- problem framing;
- ability to find the deeper structure behind many surface bugs;
- planning quality;
- judgment about invariants and system shape.

## Why the prompt matters

One version of the prompt asks the model to collect and organize local bugs into a release plan. A model following that frame will likely try to patch local failures.

A better benchmark prompt frames the problem as vibe-coded slop that may need a first-principles rewrite. That frame gives the model a chance to see and plan around the deeper architectural issue.

That difference is the point. The model can do impressive work inside a frame. But a human still had to choose the frame that made the work possible.

## What this proves

- Frontier coding agents are becoming genuinely powerful.
- Prompt/frame design can dramatically affect benchmark performance.
- Some work that looked like senior engineering judgment can be partially elicited from a model when the frame is right.
- Benchmarks can reveal real capability.

## What this does not prove

- It does not prove the model can always find the right frame on its own.
- It does not prove senior engineers are obsolete.
- It does not prove all production judgment has been automated.
- It does not prove a benchmark score is the same thing as owning a production outcome.

## How to use this

Use this page as a conceptual explainer unless the benchmark packet, prompt, model versions, scoring rubric, and human baseline are public and verified.
