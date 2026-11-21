![UOR OOO research: illustrative Foundation placeholder, not approved project branding](assets/readme-banner-PLACEHOLDER.png)

*Illustrative placeholder artwork pending UOR Foundation review.*

# The OOO quadruple object in UOR

**A research exposition mapping the four aspects of Object-Oriented Ontology to a proposed algebraic model in UOR.** This repository is a mathematical and philosophical paper, **not a shipped software library or machine-verified proof**.

[Read the research](#read-the-research) · [Model overview](#model-overview) · [Evidence boundary](#evidence-boundary) · [Repository map](#repository-map) · [License](#license)

[![Research note](https://img.shields.io/badge/status-research%20note-718096)](ooo.tex) [![MIT license](https://img.shields.io/badge/license-MIT-718096)](LICENSE)

## Read the research

Begin with [`ooo.tex`](ooo.tex), the LaTeX research manuscript. [`docs/index.html`](docs/index.html) provides a browser-friendly presentation of the same topic. The HTML presentation loads external MathJax assets, so offline rendering may differ.

There is no package to install and no executable build or test command defined in this repository.

## Model overview

The manuscript studies a quadruple `(RO, SO, RQ, SQ)` in a unital *-algebra:

| Pole | Proposed modeling role |
| --- | --- |
| Real object (RO) | The withdrawn or comparatively invariant core |
| Sensual object (SO) | A context-dependent appearance |
| Real qualities (RQ) | Properties associated with the core |
| Sensual qualities (SQ) | Properties apparent in the particular context |

It explores idempotents, subalgebras, projections, and noncommutativity as *modeling choices*. Its propositions and examples should be evaluated against their mathematical assumptions and derivations.

## Evidence boundary

The repository contains a written mathematical argument and a human-readable HTML presentation. It does **not** include an independently checked Lean/Coq proof, test suite, CI acceptance receipt, or production implementation. A theorem formatted in LaTeX is not equivalent to machine verification.

## Repository map

- [`ooo.tex`](ooo.tex): research paper
- [`docs/index.html`](docs/index.html): HTML rendering
- [`LICENSE`](LICENSE): usage terms

## License

MIT, as recorded in [`LICENSE`](LICENSE).
