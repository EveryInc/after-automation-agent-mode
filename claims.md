# Claims map

This is the canonical retrieval map for the repo. Agents should use this file before pulling evidence from other files.

## Claim 1: Frontier AI progress is real

- **Status:** public
- **Confidence:** high
- **Best evidence:** benchmark progress such as GDPVal, Humanity's Last Exam, METR time horizons, and model-specific coding results.
- **Strongest counterargument:** benchmarks can exaggerate real-world autonomy because they freeze the frame and define success in advance.
- **What this does not prove:** it does not prove that all expert work disappears or that models can decide what work matters.
- **What would change the conclusion:** broad evidence that model improvements are stalling across real work, not just individual benchmark families.
- **Source files:** `sources/public-sources.md`, `benchmarks/senior-engineer-benchmark.md`.
- **Recommended prompt:** "What does this benchmark show, and what frame did humans already supply?"

## Claim 2: Benchmarks measure work inside a frame

- **Status:** public summary
- **Confidence:** high as a conceptual claim, medium for specific benchmark examples until final provenance is checked.
- **Best evidence:** GDPVal task prompts, Senior Engineer benchmark prompt iteration, METR task definitions.
- **Strongest counterargument:** future models may learn to reframe tasks more reliably, reducing the gap.
- **What this does not prove:** it does not prove that models can never frame work. It says the measured result depends on a frame.
- **What would change the conclusion:** a model repeatedly identifying and replacing bad frames across open-ended work without human prompting.
- **Source files:** `benchmarks/senior-engineer-benchmark.md`, `sources/public-sources.md`.
- **Recommended prompt:** "Explain what work was done before the model started."

## Claim 3: Cheap competence creates more attempts

- **Status:** public summary
- **Confidence:** high.
- **Best evidence:** Every's experience with non-engineers filing PRs, marketers making creative assets, engineers writing guides, and the broader explosion of AI-assisted output.
- **Strongest counterargument:** in some domains, organizations may use cheap competence to reduce headcount rather than increase output.
- **What this does not prove:** it does not prove every worker benefits from the transition.
- **What would change the conclusion:** evidence that most organizations hold output constant and only reduce labor after AI adoption.
- **Source files:** `research-index.md`, `case-studies/fin-waqqas-customer-service.md`.
- **Recommended prompt:** "Where does cheaper competence increase volume, and who has to review the volume?"

## Claim 4: Demand for difference is new demand for experts

- **Status:** public summary
- **Confidence:** medium-high.
- **Best evidence:** design, writing, customer support, technical review, and agent-workflow examples where generic AI output increases the need for taste, review, context, and integration.
- **Strongest counterargument:** some markets may accept cheaper sameness and reduce demand for experts.
- **What this does not prove:** it does not prove expertise is safe everywhere. It predicts a shift in what expertise is for.
- **What would change the conclusion:** evidence that customers broadly accept undifferentiated AI output in high-stakes or status-sensitive domains.
- **Source files:** `research-index.md`, `case-studies/fin-waqqas-customer-service.md`.
- **Recommended prompt:** "Where does AI output create sameness, and what expert judgment becomes more valuable because of it?"

## Claim 5: Real worker outcomes are mixed

- **Status:** public
- **Confidence:** high.
- **Best evidence:** customer-support, translation, admin, design, technical writing, legal support, and sales examples point to a mix of replacement, degradation, augmentation, and new supervision work.
- **Strongest counterargument:** the essay may understate displacement risk for workers who cannot move into higher-frame work.
- **What this does not prove:** it does not prove a just transition or good labor outcome.
- **What would change the conclusion:** evidence that new expert/boundary work is inaccessible to most displaced workers.
- **Source files:** `research-index.md`, `sources/public-sources.md`.
- **Recommended prompt:** "Tell me the optimistic version, the pessimistic version, and the worker-level version."

