# Literature Planning Patterns

Use this reference when the user wants to learn an unfamiliar domain through professional literature, expert reading paths, or curated resources.

## Source Hierarchy

Prefer sources in this order unless the domain suggests otherwise:

1. Recent high-quality review or survey paper: establishes taxonomy, open problems, terminology, and dominant debates.
2. Graduate textbook chapter or lecture notes: stabilizes foundations and notation.
3. Landmark paper or canonical method: shows the field's central move in its original form.
4. Benchmark, standard, guideline, or dataset paper: reveals what the community treats as valid evidence.
5. Recent top-venue paper or frontier tutorial: exposes current direction and unresolved problems.
6. Practitioner material or implementation tutorial: useful after the conceptual frame is in place.

Do not begin with scattered blog posts unless the user needs only a very fast vocabulary bridge.

## Reading Modes

Assign each source a mode:

- Skim: learn vocabulary, structure, and scope.
- Map: extract taxonomy, assumptions, methods, and evidence standards.
- Deep read: understand one central mechanism, proof, experiment, or design pattern.
- Reproduce: implement, calculate, annotate, or replicate a small result.
- Critique: identify limitations, failure cases, and what the paper does not prove.

Every reading item should have one mode. This prevents vague "read these papers" plans.

## Sequence Templates

### Research Field

1. Read one survey to extract the problem taxonomy.
2. Read textbook or lecture material for prerequisites.
3. Read two landmark papers to understand the field's original abstractions.
4. Read one benchmark or evaluation paper to learn evidence standards.
5. Read two recent papers with opposing assumptions or methods.
6. Write a one-page field map: questions, methods, bottlenecks, and open problems.

### Technical Implementation Domain

1. Read an architecture overview or official docs to learn system boundaries.
2. Build a minimal runnable example.
3. Read one deep implementation guide or design document.
4. Inspect mature examples or reference implementations.
5. Build a small artifact that exercises the core abstraction.
6. Diagnose one failure case or performance tradeoff.

### Mathematical or Theoretical Domain

1. Identify prerequisite objects, notation, and theorem styles.
2. Read a textbook section before papers.
3. Work through definitions and simple examples.
4. Prove or derive one small result.
5. Read a survey only after the basic objects are stable.
6. Connect each theorem to the problem class it solves.

### Biomedical or Scientific Domain

1. Separate biological mechanism, measurement technology, model system, and clinical relevance.
2. Read a review for mechanism and vocabulary.
3. Read methods-focused sources to understand assays, cohorts, instruments, or experimental controls.
4. Read canonical evidence papers and note what each experiment actually establishes.
5. Read recent controversy or frontier papers.
6. Build an evidence table: claim, model/system, measurement, support strength, limitation.

## Resource Recommendation Rules

When naming concrete sources:

- Browse or use primary repositories when recency matters.
- Prefer official course pages, publisher pages, arXiv/DOI pages, standards bodies, top conference tutorials, and lab-maintained reading lists.
- State whether each source is verified in the current turn or inferred from field knowledge.
- Avoid overloading the first plan: usually 3-6 initial sources are enough.
- If the field is broad, recommend source categories first, then ask whether to specialize.

## Checkpoint Design

Use checkpoints that force active understanding:

- Explain the field's central object in one paragraph.
- Draw the problem-method-evidence map.
- Define 10 terms and show how they relate.
- Compare two methods by assumptions, inputs, outputs, and failure modes.
- Reproduce a minimal result, example, proof step, or annotation.
- Critique one paper: what it proves, what it does not prove, and what evidence would change the conclusion.

## Output Discipline

A strong plan should make these decisions explicit:

- What to learn first.
- What to postpone.
- Which literature is for orientation versus deep reading.
- What artifact the user should produce.
- How to know the user is ready to move to the next layer.
