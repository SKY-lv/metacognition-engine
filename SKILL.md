# skylv-metacognition-engine

> AI Agent metacognition engine. "Thinking about thinking" — detect cognitive biases, enable self-correction.

## Problem

AI agents can have cognitive biases just like humans:
- Confirmation bias (seeking only supporting evidence)
- Overconfidence (being too certain)
- Anchoring (relying too much on first information)
- Sunk cost fallacy (continuing wrong decisions due to past investment)

## Solution

**Metacognition Engine** — agents analyze their own reasoning process, detect biases, and self-correct.

## Usage

```bash
# Analyze reasoning file
node metacognition_engine.js analyze reasoning.txt

# Reflect on a decision
node metacognition_engine.js reflect "I'm definitely sure this must be correct"

# List bias types
node metacognition_engine.js biases
```

## Cognitive Biases Detected (6)

| Bias | Description | Detection |
|------|-------------|-----------|
| Confirmation Bias | Seeking only supporting evidence | High frequency of "only", "just", "exactly" |
| Overconfidence | Overestimating accuracy | High frequency of "definitely", "must" |
| Anchoring Bias | Over-reliance on first info | High frequency of "first", "initial" |
| Sunk Cost Fallacy | Continuing due to past investment | High frequency of "already", "spent" |
| Availability Heuristic | Based on easily recalled info | High frequency of "recently", "remember" |
| Framing Effect | Influenced by how question is framed | Presence of alternative perspectives |

## Output

- Bias detection with confidence scores
- Self-correction suggestions
- Alternative thinking approaches

## Market Data

Blue ocean: `metacognition-skill` scores **0.605** — almost no competition.

---

*"The first step to wisdom is knowing what you don't know."*
