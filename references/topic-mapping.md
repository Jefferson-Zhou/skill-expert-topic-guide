# Topic Mapping

How to build a structured map of an unfamiliar topic that reveals deep structure rather than surface terminology.

## The 7-Layer Map

Each layer answers a different question. Together they form a navigable territory:

### Layer 1: Object
**Question**: What does this topic study, build, or operate on?

Not "what is X" in dictionary terms, but what's the thing being worked on. For "causal inference" it's causal relationships in observational data. For "LLM agents" it's task-executing systems powered by language models.

### Layer 2: Problem
**Question**: What challenges or questions drive this field?

Why does this topic exist? What would be solved if it succeeded? This layer reveals motivation and helps the learner understand why people care.

### Layer 3: Concepts
**Question**: What are the core terms, and how do they relate?

Include:
- Core concepts (must understand to participate)
- Adjacent concepts (related but distinct — common source of confusion)
- Pseudo-concepts (terms that sound important but are marketing or outdated)

Show relationships: "X is a special case of Y", "A and B are often confused but differ in Z"

### Layer 4: Mechanism
**Question**: How does it actually work?

Causal chains, processes, feedback loops, architectures. This is where experts and novices diverge most — novices memorize terms, experts understand mechanisms.

For technical topics: the core algorithm, architecture, or protocol.
For research topics: the key theoretical framework or experimental paradigm.
For applied topics: the workflow from input to output.

### Layer 5: Methods
**Question**: What approaches, tools, and techniques are used?

The practical toolkit. Include:
- Dominant methods and why they dominate
- Alternative approaches and when they're preferred
- Tools and frameworks in active use
- Evaluation methods (how people judge if something works)

### Layer 6: Practice
**Question**: What does real work in this area look like?

Concrete applications, projects, benchmarks, datasets, metrics. This grounds the abstract layers in reality. Include:
- Representative projects or products
- Standard benchmarks or evaluation setups
- Typical workflows of practitioners
- Common metrics and what they measure

### Layer 7: Controversy
**Question**: What's debated, broken, overhyped, or unsolved?

This is where expert judgment lives. Include:
- Open problems (genuinely unsolved)
- Failure modes (when and why things break)
- Overhyped claims (what's marketed beyond evidence)
- Boundary conditions (where the methods stop working)
- Active debates between camps

## Building the Map

### Strategy: Top-down then refine

1. Draft all 7 layers at surface level (one sentence each)
2. Expand the layers most relevant to the user's goal
3. Mark layers where your knowledge is uncertain — these are search targets

### Connecting layers

Show how layers relate:
- Problems motivate Methods
- Mechanisms explain why Methods work (or fail)
- Practice reveals which Methods actually get used
- Controversy often lives at the gap between Mechanism claims and Practice results

### Adapting depth

- For a 1-hour overview: one paragraph per layer
- For a 1-day dive: expand Concepts + Mechanism + Methods
- For a 1-week study: full treatment of all layers
- For research entry: deep Controversy + Methods + Practice

## Concept Relationship Patterns

When mapping concepts, use these relationship types:

- **Is-a**: X is a type of Y (agent is a type of AI system)
- **Part-of**: X is a component of Y (memory is part of an agent architecture)
- **Requires**: X depends on Y (planning requires a world model)
- **Enables**: X makes Y possible (tool use enables grounded actions)
- **Competes-with**: X and Y solve the same problem differently
- **Often-confused-with**: X and Y sound similar but differ in Z

## Quality Checks for a Good Map

A good topic map should:
- Let someone explain the field in 2 minutes using just the map
- Make clear what's central vs. peripheral
- Reveal non-obvious connections
- Highlight where beginners typically get confused
- Show where the field is moving (not just where it is)
