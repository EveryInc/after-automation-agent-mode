# Objections and responses prompts

Use these prompts when a reader wants to test **After Automation** instead of just summarize it. Each prompt asks the agent to steelman the objection, explain Dan's answer, inspect the companion repo, and turn the result into a practical next step.

## Can't AI produce differentiated work if prompted correctly?

```text
Use "After Automation" and this companion repo:
https://github.com/EveryInc/after-automation-agent-mode

Objection: Can't AI produce differentiated work if it is prompted correctly?

Dan's answer is that the prompt is part of the human work. If differentiated output depends on a person choosing the frame, context, and standard, then the human has not disappeared. The human and model are doing the work together.

Help me test that answer.

Return:
1. the strongest version of the objection;
2. Dan's answer in plain English;
3. the best evidence in `the repo that supports or weakens the answer;
4. where the answer might fail in my own work;
5. one workflow experiment I can run this week to see whether better prompting replaces my judgment or makes my judgment more important.
```

## What about one model prompting another model?

```text
Use "After Automation" and this companion repo:
https://github.com/EveryInc/after-automation-agent-mode

Objection: What about a model prompting another model? Doesn't that move the human out of the loop?

Dan's answer is that model-to-model prompting still bottoms out in a human-maintained frame: someone decides the goal, the evaluation, the update cycle, and what good looks like.

Help me test that answer.

Return:
1. the strongest version of the objection;
2. Dan's answer in plain English;
3. what evidence in the repo supports the idea that agents need owners, boundaries, and review loops;
4. the strongest case that autonomous agent chains could reduce the human role
5. one practical design rule for when I should let agents supervise agents, and one rule for when a human must stay in the review loop.
```

## Can't differentiated work be trained into the next model?

```text
Use "After Automation" and this companion repo:
https://github.com/EveryInc/after-automation-agent-mode

Objection: Can't differentiated work just be trained into the next model?

Dan's answer is yes, but that restarts the cycle. Once a kind of work is absorbed into the model, it becomes cheaper and more widely available. Sameness spreads again, and humans push the frontier toward a new kind of specificity, judgment, and live problem-fit.

Help me test that answer.

Return:
1. the strongest version of the objection;
2. Dan's answer in plain English;
3. the claims and sources that support or weaken the "cheap competence creates sameness" loop;
4. one market or type of work where customers may accept cheaper sameness instead of demanding difference;
5. what this means for what I should learn, save, delegate, or stop doing.
```

## What about continuous learning?

```text
Use "After Automation" and this companion repo:
https://github.com/EveryInc/after-automation-agent-mode

Objection: What about continuous learning? If a model watches me and learns from what I do, doesn't it eventually replace my judgment?

Dan's answer is that even continuous learning depends on a human defining what good is. If the model learns to do work that once required you, the new capacity usually creates new demand, new standards, and new work for you to frame.

Help me test that answer.

Return:
1. the strongest version of the objection;
2. Dan's answer in plain English;
3. what evidence in the repo supports or weakens the claim that humans move faster than model weights and workflows;
4. what kind of work continuous learning could actually absorb from me;
5. the next higher-level judgment, review loop, or artifact I should own if that happens.
```

## What about AGI, instrumental convergence, or recursive improvement?

```text
Use "After Automation" and this companion repo:
https://github.com/EveryInc/after-automation-agent-mode

Objection: What about AGI, instrumental convergence, or recursive improvement? Doesn't the argument break if models become persistent, self-improving systems with goals of their own?

Dan's answer is that current agents have autonomy but not human agency. They can pursue ends humans specify, but they do not yet generate ends from the inside. As long as they are broadly distributed and built to be helpful, the important comparison is not AI versus humans. It is human plus AI versus human plus AI.

Help me test that answer.

Return:
1. the strongest version of the objection;
2. Dan's answer in plain English;
3. what the companion repo and essay say about agents, agency, and human-plus-AI work;
4. the strongest case that this answer fails under a more capable AGI system;
5. what practical difference this should make for how I design agent workflows today.
```

## Where should we worry?

```text
Use "After Automation" and this companion repo:
https://github.com/EveryInc/after-automation-agent-mode

Objection: Where should we actually worry? Are there jobs, domains, or institutions where AI progress really does reduce human work instead of creating more of it?

Dan's answer is not that no one should worry. It is that the default story misses how cheap competence creates new attempts, sameness, review work, and higher-level framing work. Some domains may still be exposed differently.

Help me make this concrete.

Return:
1. the strongest version of the worry;
2. Dan's answer in plain English;
3. which parts of the argument apply strongly to this domain and which parts do not;
4. one example where AI probably creates more human work, and one example where it may genuinely reduce the need for human labor;
5. what a responsible team should do next if they are operating in the risky domain.
```
