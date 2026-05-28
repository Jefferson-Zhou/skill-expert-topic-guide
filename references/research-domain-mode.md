# Research Domain Mode

Additional guidance for when the user's topic is academic, research-oriented, or requires literature navigation.

## When to Activate

- User explicitly mentions research, papers, literature, proposals, or academic work
- Topic is primarily studied in academic settings (e.g., causal inference, protein folding)
- User's goal is to write a survey, proposal, or identify research gaps
- User needs to understand research lineages and debates

## Literature Role Classification

Not all papers serve the same function. Classify recommended papers by role:

| Role | Function | Example |
|------|----------|---------|
| **Anchor** | Defines the field or subfield, everyone cites it | "Attention Is All You Need" for transformers |
| **Review** | Maps the landscape, good entry point | Annual survey papers, handbook chapters |
| **Method** | Introduces a specific technique or approach | A paper proposing a new algorithm |
| **Benchmark** | Establishes evaluation standards | Papers introducing datasets or metrics |
| **Critique** | Challenges assumptions, reveals limitations | "On the Dangers of Stochastic Parrots" |
| **Frontier** | Most recent advances, may not be settled | Last 6 months of top venue papers |
| **Bridge** | Connects two subfields or disciplines | Papers that apply method from field A to field B |

## Research Lineage Mapping

Help the learner see how ideas evolved:

1. **Origin**: Where did this research direction start? (seminal paper/event)
2. **Branches**: What sub-directions emerged?
3. **Current fronts**: Where is active work happening now?
4. **Dead ends**: What was tried and abandoned? (and why)
5. **Convergences**: Where are separate lines meeting?

## Scoping Review Approach

For users who need to map an entire research area:

1. **Define scope**: What questions are in/out?
2. **Identify sources**: Which venues, databases, communities?
3. **Search strategy**: Key terms, citation chaining, author tracking
4. **Charting**: Extract structured data from each source (method, findings, limitations)
5. **Synthesis**: What patterns emerge? What gaps exist?

This is heavier than the default learning path — only use when the user's goal is explicitly research-oriented.

## Citation Network Navigation

Teach the learner to navigate literature efficiently:

- **Forward citation**: Who cited this paper? (find newer work building on it)
- **Backward citation**: What does this paper cite? (find foundational work)
- **Co-citation**: What papers are frequently cited together? (find related clusters)
- **Author tracking**: What else has this research group published?

Tools to recommend: Google Scholar, Semantic Scholar, Connected Papers, citation graphs in survey papers.

## Research Community Signals

Help the learner identify where the community lives:

- **Top venues**: Which conferences/journals matter most?
- **Key groups**: Which labs/teams are leading?
- **Funding signals**: What's being funded? (indicates direction)
- **Industry adoption**: What's moved from research to practice?
- **Workshops/tutorials**: Where are emerging topics discussed?

## Adapting the 7-Layer Map for Research

For research topics, expand certain layers:

- **Problem layer**: Include formal problem statements, not just informal descriptions
- **Methods layer**: Include experimental paradigms, not just algorithms
- **Practice layer**: Include datasets, benchmarks, and replication status
- **Controversy layer**: Include methodological debates, replication failures, and paradigm tensions

## Output Additions for Research Mode

When in research mode, add to the standard output:

```markdown
## Research Landscape
- Key venues and their focus
- Major research groups
- Funding/industry trends

## Literature Map
- Anchor papers (must-read)
- Reviews (entry points)
- Method papers (by sub-direction)
- Benchmarks (evaluation standards)
- Critiques (important challenges)

## Research Entry Points
- Accessible open problems
- Gaps in current literature
- Replication opportunities
- Cross-disciplinary bridges
```
