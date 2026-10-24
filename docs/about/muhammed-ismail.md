# About Muhammed Ismail

Muhammed Ismail is a theoretical mathematician in South Africa who proved that six structural capabilities are necessary for a decision-maker to avoid failure under uncertainty in six defined situations, checked the proof in Lean 4, and owns and directs Literacity, the service that applies it.

<img src="../images/muhammed-ismail.jpg" alt="Muhammed Ismail seated at his desk with a laptop" width="360">

## At a glance

| Item | Detail |
|---|---|
| Work | Theoretical mathematics: formal verification in Lean 4, decision theory under uncertainty, and translating one structure across domains |
| Based in | South Africa |
| Main result | Ismail's Primitives: six structural properties proved necessary, mutually independent and sequentially dependent for adaptive decision-making in a defined class of environments, Class C |
| Machine check | 12,667 lines of Lean 4 in seven files against Mathlib as of 2026-10-24, with zero `sorry`, zero custom `axiom`, zero `opaque` declarations and zero linter suppressions |
| Publications | Six papers on Zenodo, all under CC BY 4.0 |
| Repositories | IsmailsPrimitives, IsmailsGlossary and IsmailsProtocols |
| Company | Owner and director of Literacity Pty Ltd, founded in 2016, registration number 2016/135857/07 |
| ORCID | [0009-0000-3713-7105](https://orcid.org/0009-0000-3713-7105) |
| GitHub | [M-Ismail-ZA](https://github.com/M-Ismail-ZA) |
| LinkedIn | [researcher-adaptationtheory](https://www.linkedin.com/in/researcher-adaptationtheory/) |
| Email | [literacity@outlook.com](mailto:literacity@outlook.com) |

## The question he works on

Ismail's work asks one question: what must a decision-maker get right, structurally, to avoid failure under uncertainty? His answer is six capabilities, named Ismail's Primitives. A decision structure that lacks one of them accrues loss in proportion to time, however well the rest is run. Lean 4 checks the proof, and anyone can rebuild it. The proof establishes necessity, and sufficiency work is planned from Q4 2027.

## How the work began

In September 2025 Ismail noticed that his own decisions followed a recurring six-step pattern, which he first treated as a personal heuristic. He asked whether the pattern could be proved. He then answered his own question by proving it in Lean 4.

| When | What happened |
|---|---|
| September 2025 | Noticed the six-step pattern in his own decisions |
| 28 January 2026 | First companion paper |
| 8 April 2026 | Second companion paper |
| May to June 2026 | Moved the work into Lean 4 |
| July 2026 | Released Ismail's Primitives and the Glossary |

## The six primitives and what is proved

The formalisation defines six functional properties of decision rules, called X1 to X6 throughout the proof and the papers.

| | Primitive | What it requires |
|---|---|---|
| X1 | Objective Tracking | Tell two live hypotheses apart before acting on either |
| X2 | Cross-Context Safety Transfer | Recognise the action that cannot be undone, and do not take it |
| X3 | Global Attractor Exploration | Keep probing past the comfortable, safe plateau |
| X4 | Policy Simplification | Commit once the evidence is in |
| X5 | Feasibility Projection | Treat a hard limit as a wall |
| X6 | Feedback Adaptation | Discard a belief once the world it described has changed |

Every Literacity finding traces to these theorems and on to the axioms, as [the Trace](../the-trace.md) shows.

The proof has three parts.

1. **Necessity.** For each primitive, Ismail builds a minimal environment and proves a linear regret lower bound, written Ω(T), for any decision-maker that lacks it. Six necessity theorems result.
2. **Independence.** For each ordered pair of primitives, he exhibits a decision rule that has one and lacks the other and still suffers linear regret. All thirty pairs follow from one master theorem, so no primitive can stand in for another.
3. **Sequential dependence.** Six Information Enhancement Theorems show that the primitives form a chain, X1 to X2 and on to X6, which closes back on X1. The closing link rests on a Doob martingale construction over cycles of play.

## Repositories

Three public repositories on [GitHub](https://github.com/M-Ismail-ZA) carry the work. A fourth, the profile repository `M-Ismail-ZA`, holds the overview.

| Repository | What it is | Key figures | Licence |
|---|---|---|---|
| [IsmailsPrimitives](https://github.com/M-Ismail-ZA/IsmailsPrimitives) | The Lean 4 and Mathlib formalisation of the six primitives. Created 1 July 2026. [Website](https://m-ismail-za.github.io/IsmailsPrimitives/) | 12,667 lines of Lean 4 in seven files as of 2026-10-24; zero `sorry`, zero custom `axiom`, zero `opaque`, zero linter suppressions; six necessity theorems, thirty independence results, six Information Enhancement Theorems; GitHub Actions CI with a pinned toolchain and a reproducible build | MIT |
| [IsmailsGlossary](https://github.com/M-Ismail-ZA/IsmailsGlossary) | A navigation index for every module in Mathlib4, with plain-English descriptions and disambiguation of similarly named modules. Created 4 July 2026. [Website](https://m-ismail-za.github.io/IsmailsGlossary/) | 9,150 modules in 1,129 directories and 8,021 files across 32 top-level domains; snapshot of Lean 4.29.1 and Mathlib4 commit `1ad783f9bf` (9 May 2026); 9,107 entries Complete and 43 Benchmark Theorem; five deliverables: JSON, RAG export, Claude Skill bundle, master spreadsheet and interactive website | CC BY 4.0 |
| [IsmailsProtocols](https://github.com/M-Ismail-ZA/IsmailsProtocols) | Two rule-based evaluation protocols packaged as portable AI skills, with porting guides for ChatGPT and Gemini. Created 22 September 2026 | A credibility checker with eight rules, two depth tiers and four severity levels; an AI-writing review with 21 rules in five parts, adapted from Wikipedia's essay on signs of AI writing; every rule traces to a cited source | Rule content CC BY 4.0; tooling and prose MIT |

## Papers

All six papers are on Zenodo under CC BY 4.0. The first holds the mathematics, and the next four apply it to other domains.

| Paper | Version | DOI | What it covers |
|---|---|---|---|
| Ismail's Primitives: A Unified Functional Theory of Necessity, Independence, and Sequential Dependence in Adaptive Decision Systems | V6.2, 2026 | [10.5281/zenodo.23080967](https://doi.org/10.5281/zenodo.23080967) | The foundational mathematics: necessity, independence and sequential dependence of the six primitives |
| Ismail's Primitives: Lean-verified Economic Adaptation Theory | V2.0, 2026 | [10.5281/zenodo.21289756](https://doi.org/10.5281/zenodo.21289756) | The same structure relabelled for economies, with Walrasian equilibrium as the case where the environment lies outside Class C, and the 2008 financial crisis read as a structural diagnostic |
| Ismail's Primitives and Human Development: A Functional Isomorphism Between a Lean-Verified Computational Theory and Developmental Psychology | V3.0, 2026 | [10.5281/zenodo.21257553](https://doi.org/10.5281/zenodo.21257553) | The six primitives set in sequence against Erikson's stages, Maslow's hierarchy and Bowlby's attachment phases, with eight derived testable predictions |
| Ismail's Primitives: An Emotional Adaptation Theory for Therapy Discovered through Functional Isomorphism | V2.0, 2026 | [10.5281/zenodo.21289914](https://doi.org/10.5281/zenodo.21289914) | Emotional life as a Class C environment, six therapeutic functions, and a structural account of the Dodo Bird verdict |
| Ismail's Primitives: The SPEA Protocol for Clinical Psychology | V1.0, 2026 | [10.5281/zenodo.21311895](https://doi.org/10.5281/zenodo.21311895) | A six-step clinical sequence (Emotional Archaeology, Pattern Mapping, Emotional Imagination, Authentic Distillation, Embodied Integration, Narrative Weaving) with five falsification criteria, each paired with a study design |
| Ismail's Glossary: A Complete Navigation Index for Mathlib4 | V1.0, 2026 | [10.5281/zenodo.21192789](https://doi.org/10.5281/zenodo.21192789) | The Glossary's index of Mathlib4 modules |

## Skills

The degrees below are the ones Ismail gives on his [GitHub profile](https://github.com/M-Ismail-ZA/M-Ismail-ZA), each with the public artefact that shows it. His standing rests on those artefacts, listed on the field's [author page](https://decisional-integrity.github.io/Field/about/author/).

| Skill | Degree | Evidence |
|---|---|---|
| Formal verification in Lean 4 and Mathlib | Advanced | 12,667 lines in seven files as of 2026-10-24 with zero `sorry`, `axiom`, `opaque` and linter suppressions; CI; a phased dependency graph; a public repository |
| Novel argument construction | Advanced | Six distinct lower-bound proofs (Le Cam two-world, survival-conditional, horizon-parameterised, Fano and entropy-inverse, Cesàro-average, window-calibration) and a master reduction that collapses thirty pairwise results into three shared lemmas |
| Reinforcement learning and lower-bound construction | Advanced | Six minimal adversarial environments and six Ω(T) necessity theorems |
| Measure-theoretic probability | Advanced, in a specific construction | The `trajMeasure` infrastructure, used as the ambient space of every downstream theorem |
| Information theory | Advanced, finite-alphabet and decision-theoretic | Entropy, Fano and a KL, total-variation and Jensen-Shannon toolkit built from first principles |
| Domain translation | Distinctive | Four domain instantiations (economics, developmental psychology, clinical theory, clinical protocol) plus the Glossary's Mathlib index, each citing primary sources |
| Research programme design | Distinctive | A four-tier epistemic architecture across six interdependent documents |
| Epistemic scoping and version discipline | Distinctive | A consistent separation of what is machine-verified from what is argued, with structured version histories and documented corrections |
| Rule-based protocol design | Distinctive | Two protocols, ordered by dependency, cited rule by rule and ported across three AI platforms |
| Consilience argumentation | Proficient | The Erikson, Maslow and Bowlby convergence argument; several therapeutic traditions converging on the same six functions |
| Real analysis | Proficient | `kronecker_lemma` and the log-inequality chain that ends in `necessity_x4` |
| Convex analysis | Proficient | Binary-entropy concavity and Fano monotonicity, used through an entropy-inverse construction |
| Stochastic processes and martingale theory | Proficient | `cycle_filtration`, `cycle_posterior` and `azuma_hoeffding`, the anchor of the closing chain link |
| Technical writing in mathematics | Proficient | Paper-length exposition with a Rosetta appendix that maps every numbered result to a Lean identifier |
| Economics, developmental psychology, clinical psychology | Reading-level fluency | Citation of primary sources across six economics sub-fields, the major developmental traditions and the major psychotherapy traditions |
| Software engineering | Working | Public repositories with clear module separation, CI, pinned toolchains and reproducible builds |
| Data engineering | Working | Multi-format Glossary export, with the Lean toolchain, the Mathlib snapshot and the Glossary release versioned separately |

## Literacity and the approver role

Ismail founded Literacity Pty Ltd in 2016 and owns and directs it. Literacity applies the primitives for clients. An audit examines a decision structure against the open criteria and gives a finding for each of the six, build support closes any gap, and a pass earns a dated verification statement that is valid for twelve months and listed in a public [registry](../certification/registry.md).

Literacity is a team that works from Ismail's research from start to finish. Ismail leads it, trains it in the research and is the final arbiter of every verification. The approver role is held on proof. The field's [competence page](https://decisional-integrity.github.io/Field/field/competence/) says another person can take it by presenting public, dated, reproducible artefacts of a stated type and depth, and Ismail's own approval rests on the same rule, with its artefacts public on the field's [author page](https://decisional-integrity.github.io/Field/about/author/). The first cohort of verifications will be published by Q2 2027. [Literacity and Ismail](relationship-to-ismail.md) sets out how the research, the field and the service relate.

Literacity is on [LinkedIn](https://www.linkedin.com/company/literacity-research/), and this repository holds its documentation.

## Contact

Write to [literacity@outlook.com](mailto:literacity@outlook.com), or find him on [GitHub](https://github.com/M-Ismail-ZA), [ORCID](https://orcid.org/0009-0000-3713-7105) and [LinkedIn](https://www.linkedin.com/in/researcher-adaptationtheory/). More on his work is in his [GitHub profile](https://github.com/M-Ismail-ZA/M-Ismail-ZA) and on the [Glossary site](https://m-ismail-za.github.io/IsmailsGlossary/).
