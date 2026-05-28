# Learning Diagnosis

How to assess a learner's starting point and calibrate the guidance accordingly.

## Diagnosis Dimensions

### 1. Background Level

| Level | Signal | Implication |
|-------|--------|-------------|
| Complete novice | "I know nothing about X" | Start from object/problem layer, use analogies to familiar domains |
| Adjacent field | "I do Y, which seems related to X" | Map transfer points, focus on where X diverges from Y |
| Practitioner without theory | "I use X daily but don't understand why" | Skip tool basics, focus on mechanism and design principles |
| Researcher entering new area | "I study Y, now need to understand X for my work" | Focus on methods, evidence standards, key debates |

### 2. Learning Goal

Goals determine which layers of the topic map to emphasize and what "done" looks like:

| Goal | Emphasis | Done when... |
|------|----------|--------------|
| Understand concepts | Object + Problem + Concepts + Mechanism | Can explain to someone else without notes |
| Read domain materials | + Methods + Controversy | Can read a paper/doc and identify claims, methods, limitations |
| Build things | + Practice + Methods | Can implement a working prototype and explain design choices |
| Make decisions | + Controversy + Practice | Can evaluate options, articulate tradeoffs, justify a choice |
| Do research | All layers deeply | Can identify gaps, formulate questions, design studies |

### 3. Time Budget

Time determines depth and breadth:

| Budget | Realistic outcome | Strategy |
|--------|-------------------|----------|
| 1 hour | Concept boundaries, topic map, know what you don't know | High-density overview, one good explainer |
| 1 day | Can follow domain discussions, identify key resources | Intro materials + one judgment task |
| 1 week | Can evaluate work quality, complete a small project | Core materials + project + failure analysis |
| 1 month | Independent judgment, can contribute or research | Deep dive into sub-area + original work |

### 4. Topic Type

Different topic types have different optimal entry strategies:

| Type | Examples | Best entry point |
|------|----------|-----------------|
| Theoretical | Category theory, quantum mechanics, game theory | Textbook + worked examples |
| Technical | Kubernetes, React, database internals | Official docs + hands-on demo |
| Engineering | System design, ML pipelines, compiler construction | Architecture overview + build something small |
| Research | Causal inference, protein folding, alignment | Survey paper + key debates |
| Industry | Fintech regulation, supply chain, healthcare IT | Case studies + practitioner guides |
| Hybrid | LLM agents, autonomous vehicles, biotech | Depends on user's angle — clarify first |

## Diagnosis Protocol

When the user's message is ambiguous, ask at most 2 questions. Prefer questions that disambiguate the most:

1. "What's your angle — are you trying to understand this conceptually, build something with it, evaluate it for a decision, or research it?" (disambiguates goal)
2. "What's your nearest related experience?" (disambiguates background)

If the user gives a clear goal and context in their initial message, skip diagnosis entirely and proceed to framing.

## Default Assumptions

When information is missing, assume:
- Background: adjacent field (not complete novice, not expert)
- Goal: actionable understanding (between "concepts" and "build")
- Time: 1 week
- Type: infer from topic name

Always state your assumption so the user can correct it.
