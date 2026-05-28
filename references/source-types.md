# Source Types

How to select, evaluate, and sequence learning materials by type.

## Material Type Selection

Different material types serve different learning functions. Never default to papers for all topics.

### Selection Matrix

| Material Type | Best for | Strengths | Weaknesses |
|---------------|----------|-----------|------------|
| Textbooks | Stable theory, foundational concepts | Systematic, vetted, exercises included | May be outdated, slow to update |
| Online courses | High barrier topics, visual learners | Structured progression, multimedia | Variable quality, may be superficial |
| Official documentation | Tools, APIs, standards | Authoritative, current | Assumes context, often reference-style |
| Survey/review papers | Unclear field scope | Broad coverage, citations as map | May be dated, author bias |
| Research papers | Frontier topics, evidence-based claims | Primary source, methods detail | Requires background, jargon-heavy |
| Open source projects | Engineering topics | Real implementation, runnable | Code quality varies, may lack docs |
| Benchmarks/leaderboards | Method comparison | Objective metrics, reproducible | May not reflect real-world performance |
| Case studies/postmortems | Applied domains | Real constraints, failure lessons | Survivorship bias, context-specific |
| Community discussions | Fast-moving topics | Current pain points, practical tips | Noisy, unvetted, may be wrong |
| Standards/specifications | Protocol/format-driven topics | Definitive, precise | Dense, hard to read without context |

### Topic-Type to Material Priority

| Topic type | Primary materials | Secondary | Avoid starting with |
|------------|-------------------|-----------|---------------------|
| Theoretical | Textbook → survey → papers | Courses, worked examples | Random blog posts |
| Technical | Official docs → tutorials → projects | Community discussions | Academic papers |
| Engineering | Architecture docs → projects → postmortems | Benchmarks, talks | Textbooks |
| Research | Survey → key papers → benchmarks | Courses, replication code | Blog summaries |
| Industry | Case studies → practitioner guides → standards | News, reports | Academic papers |

## Authority Assessment

How to judge if a resource is worth recommending:

### High-authority signals
- Published by recognized institution or press
- Authored by active practitioners/researchers in the field
- Frequently cited or referenced by other authoritative sources
- Maintained and updated (for docs/projects)
- Has clear methodology or evidence basis

### Low-authority signals (use with caution)
- Anonymous or unknown author
- No citations or references
- Marketing-heavy language
- Outdated (check publication date vs. field pace)
- Contradicts multiple authoritative sources without evidence

### Fast-moving field adjustments
For topics that change rapidly (AI, crypto, specific frameworks):
- Prefer resources from the last 6-12 months
- Official docs and changelogs over textbooks
- Active GitHub repos over archived ones
- Conference papers over journal papers (faster publication)
- Verify that recommended tools/libraries still exist and are maintained

## Resource Annotation Protocol

When recommending any resource, always include:

1. **Role**: Why read this? What gap does it fill?
2. **Timing**: When in the learning sequence? (e.g., "after you understand X but before attempting Y")
3. **Effort**: How long will it take? (e.g., "2-hour read", "weekend project")
4. **Caveat**: Any known limitations? (e.g., "great for concepts but code examples are outdated")

Example:
> **"Attention Is All You Need" (Vaswani et al., 2017)**
> - Role: Understand the transformer architecture that underlies all modern LLMs
> - Timing: After you grasp embeddings and sequence modeling basics
> - Effort: 2-3 hours for a careful read
> - Caveat: The original notation is dense; pair with Jay Alammar's visual guide

## Layered Resource Organization

Organize resources into layers that match learning progression:

1. **Introductory** — Build basic vocabulary and intuition
2. **Authoritative** — Establish correct understanding from primary sources
3. **Practical** — Enable hands-on work and implementation
4. **Frontier** — Show current state and open problems
5. **Pitfall-avoidance** — Warn about common mistakes and misconceptions

## Priority Tiers (Critical for Managing Information Overload)

Within each layer, mark resources with priority tiers to prevent overwhelming the learner:

- **Must-read** (1-2 per stage) — Core resources that directly enable the current stage's goal. If the learner only reads these, they can still complete the stage.
- **Should-read** (2-3 per stage) — Valuable supplements that deepen understanding or provide alternative perspectives. Read these if time permits.
- **Optional** (unlimited) — For learners who want to go deeper or explore tangents. Clearly mark these as "optional" or "for later" so learners don't feel obligated.

**Default rule**: If you're listing more than 3 resources for a single stage without priority markers, you're overwhelming the learner. Trim or tier.
