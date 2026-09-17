# Alexander McAulay — Octonion research index

This repository gathers source material on octonions and implementation-oriented
knowledge derived from it.

## Start here

| Resource | Purpose |
| --- | --- |
| [Octonions knowledge-agent brief](knowing/OCTONIONS-KNOWLEDGE-AGENT.md) | Concise, source-traceable concepts, claims, graph triples, and guardrails for a knowledge agent. |
| [SA-8 structural algebra specification](knowing/STRUCTURAL-ALGEBRA-SPEC.md) | Formal table-driven octonion algebra designed for PolyForth and silicon/RTL/CAD implementation. |

## Primary reference PDFs

| Source | Focus |
| --- | --- |
| [The Octonions — Michael Taylor](<oders/The Octonions -- Michael Taylor.pdf>) | Core construction, norm, alternativity, Moufang identities, automorphisms, and `G₂`. |
| [The Geometry of the Octonions](<oders/The Geometry of the Octonions.pdf>) | Geometric perspectives on octonions. |
| [Octonions, Jordan Algebras, and Exceptional Groups](<oders/Octonions, Jordan Algebras, and Exceptional Groups.pdf>) | Broader exceptional-algebra and Lie-group context. |

## Suggested paths

- For conceptual or retrieval-agent work: begin with the knowledge-agent brief,
  then consult Taylor’s PDF through its section and equation references.
- For software, firmware, or hardware design: begin with the SA-8 specification.
  Its basis-product table and arithmetic-mode choice are normative design inputs.
- For mathematical extensions beyond the core algebra: use the geometry and
  exceptional-groups references.

## Repository layout

```text
knowing/  Parsed knowledge and implementation specifications
oders/    Source PDFs
```
