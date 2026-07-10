# Agent Memory Architecture

A reference architecture for AI agent memory where the agent **persists**, not just retrieves. Five engineering layers, each mapped to a source lineage and a build-feasibility verdict, plus a companion mental model that shows the layers working as a closed loop.

The thesis it is built on: *memory is not storage to be retrieved; it is the active process an agent navigates to persist across time.*

## Live pages

- **Five-layer architecture:** https://ianpilon.github.io/agent-memory-architecture/
- **Living-loop mental model:** https://ianpilon.github.io/agent-memory-architecture/living-loop.html
- **Ecosystem map:** https://ianpilon.github.io/agent-memory-architecture/ecosystem.html

## The five layers

| Layer | Capability | Source lineage | Verdict |
|---|---|---|---|
| 1 | Hierarchy and goal-filtering | Conway (working-self + autobiographical KB) | Shippable today |
| 2 | Active reinterpretation on retrieval | Levin (bowtie) | Buildable, recipe now published |
| 3 | Salience and emotional weighting | Damasio + Conway | Scoring trivial, wiring hard |
| 4 | Narrative layer and co-emergent self-model | Bruner + Klein/Nichols | Research frontier |
| 5 | Substrate flexibility | Levin (polycomputing + no-single-substrate) | Blocked on substrate |

The bottom line: layers 1 through 3 are an engineering project; layer 4 is a research bet; layer 5 is the honest unknown, blocked not on effort but on whether any engineered substrate can hold Levin's claim.

## Sources

Derived from the [Memory as Navigation](https://github.com/ianpilon/memory-as-navigation-site) wiki, which synthesizes:

- **Conway (2005)** — the Self-Memory System (psychology)
- **Levin (2024)** — self-improvising, substrate-agnostic memory (biology)
- **Youssef (2026)** — five principles AI memory lacks, via Conway, Damasio, Bruner, Klein & Nichols (engineering principles)
- **Xu et al. (2026) / NapMem** — memory as a structured action space, the first *measured* engineering source; it corroborates layers 1 and 2 with a published GRPO training recipe and sharpens (without resolving) the layer 5 question

Verdicts are a read of 2026 tooling, not a spec.

## This repo

A two-page published document, served by GitHub Pages from `main`. No build step.

- `index.html` — the five-layer architecture, data-flow diagrams, and the verdict ledger
- `living-loop.html` — the same system drawn as a closed loop a self is reconstructed on
- `ecosystem.html` — the provenance map: how all eight sources flow through the synthesis into the derived artifacts
