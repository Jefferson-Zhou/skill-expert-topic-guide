# Technical Domain Mode

Additional guidance for when the user's topic is a technology, framework, tool, engineering system, or programming-related domain.

## When to Activate

- Topic is a specific technology (Kubernetes, React, PostgreSQL)
- Topic is an engineering pattern (microservices, event sourcing, ML pipelines)
- Topic is a tool ecosystem (LLM frameworks, data pipelines, CI/CD)
- User's goal involves building, implementing, or evaluating technical systems

## Demo-First vs. Concept-First Decision

| Choose demo-first when... | Choose concept-first when... |
|---------------------------|------------------------------|
| The tool has a quick-start that works in <10 min | The system has complex prerequisites |
| Seeing it run builds intuition faster than reading | Misunderstanding fundamentals leads to dangerous mistakes |
| The user is a practitioner who learns by doing | The user needs to evaluate, not just use |
| Official docs have good tutorials | The technology is poorly documented |

For most technical topics, a hybrid works best:
1. Brief concept overview (5 min read)
2. Run the simplest possible demo
3. Explain what just happened using the concepts
4. Incrementally add complexity

## Technical Learning Path Structure

### Phase 1: Orientation (1 hour)
- What problem does this solve? What existed before it?
- Architecture diagram: major components and data flow
- Run the "hello world" equivalent
- Identify: what's the simplest useful thing I can build?
- **Minimum action**: Successfully run one demo command/example and observe the output

### Phase 2: Fundamentals (1 day)
- Core abstractions and their relationships
- Official getting-started guide or tutorial
- Build one small thing end-to-end
- Identify: where did I get confused? What broke?
- **Minimum action**: Deploy one simple application using the technology (even if just locally)

### Phase 3: Working Knowledge (1 week)
- Read architecture docs or source code overview
- Build something non-trivial with real constraints
- Encounter and debug 3-5 common failure modes
- Understand configuration, deployment, and operational concerns
- **Minimum action**: Complete one project that you can demo to a colleague

### Phase 4: Expertise (1 month)
- Read source code of key components
- Understand performance characteristics and limits
- Contribute a fix or extension
- Evaluate alternatives and articulate tradeoffs
- **Minimum action**: Produce one artifact (blog post, internal doc, or code contribution) that demonstrates deep understanding

## Failure Analysis Pattern

For technical topics, understanding failure is as important as understanding success:

### Failure Categories
1. **Configuration failures**: Wrong settings, missing dependencies, version conflicts
2. **Conceptual failures**: Misunderstanding what the tool does or doesn't do
3. **Scale failures**: Works in demo, breaks in production
4. **Integration failures**: Conflicts with other systems
5. **Operational failures**: Works once, fails over time (memory leaks, state corruption)

### Learning from Failures
For each technology, identify:
- The 3 most common beginner mistakes
- The failure mode that's hardest to debug
- The "it works but it's wrong" anti-pattern
- The production issue that tutorials never mention

## Project-Based Learning Design

For technical topics, the best practice tasks are small projects:

### Good Technical Projects
- **Minimal**: Can be completed in the time budget
- **End-to-end**: Covers the full lifecycle (build, test, deploy, observe)
- **Constrained**: Has specific requirements that force real decisions
- **Breakable**: Has known ways to fail that teach important lessons

### Project Progression
1. **Clone and modify**: Take an existing example, change one thing
2. **Build from template**: Use a starter, add a feature
3. **Build from scratch**: Implement core functionality yourself
4. **Extend and integrate**: Connect to other systems, handle edge cases

## Technical Resource Priorities

For technical topics, prioritize resources in this order:

1. **Official documentation** — authoritative, current
2. **Official examples/tutorials** — vetted, maintained
3. **Architecture decision records (ADRs)** — explain why, not just what
4. **Source code** — the ultimate truth
5. **Maintainer talks/posts** — context and philosophy
6. **Community best practices** — battle-tested patterns
7. **Benchmarks** — objective performance data

Be cautious with:
- Blog posts (may be outdated, may be wrong)
- Stack Overflow answers (may be for old versions)
- YouTube tutorials (variable quality, hard to verify)
- "Awesome lists" (quantity over quality)

## Adapting the 7-Layer Map for Technical Topics

- **Object layer**: The system/tool and what it operates on
- **Problem layer**: What pain point it addresses, what existed before
- **Concepts layer**: Core abstractions (not just API names)
- **Mechanism layer**: Architecture, data flow, execution model
- **Methods layer**: Usage patterns, configuration approaches, deployment strategies
- **Practice layer**: Production use cases, performance characteristics, operational concerns
- **Controversy layer**: Known limitations, competing tools, migration pain, vendor lock-in

## Output Additions for Technical Mode

```markdown
## Architecture Overview
- Component diagram with data flow
- Key abstractions and their relationships
- Execution model (sync/async, single/multi-threaded, etc.)

## Hands-On Path
- Quickstart: run in <10 minutes
- First project: build X with constraints Y
- Debugging exercise: fix this broken configuration
- Production readiness: what to check before deploying

## Ecosystem Map
- Core tool/framework
- Essential plugins/extensions
- Monitoring/observability
- Testing approaches
- Deployment options

## Common Pitfalls
- Beginner mistakes and how to avoid them
- "Works in dev, breaks in prod" scenarios
- Performance traps
- Security considerations
```
