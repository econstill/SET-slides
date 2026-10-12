# SET — English Close-Reading Slides

An English, 1–2 hour literature-reading discussion of *SET* by Yves Zenou and
Junjie Zhou (paper version: February 17, 2026), using the supplied
`Hyper0721.tex` Beamer template.

## Files

- [Slides (PDF)](SET-English-Seminar.pdf): 34 pages — 33 main pages (including
  the title) plus one optional coordinate-proof backup page.
- [Editable source](main.tex): native Beamer source. The paper's original
  Figure 1 is on page 3, followed immediately by the worked nonlinear
  two-player example on pages 4–10. There are no embedded speaker notes or
  per-slide source footers.
- [Figure 1 crop](assets/set-figure1-methodology.png): the original methodology
  diagram from page 17 of the supplied paper.
- [Presenter guide](SET-English-Presenter-Guide.md): flexible reading routes,
  a paper-page map, cues for every PDF page, a full worked-example script,
  methodology explanations, concise application scripts, and discussion
  questions with answers. It also maps the formal results to their original
  paper numbers.

Page numbers in the guide refer to physical PDF pages, including the cover;
they are not the Beamer footer numbers.

## Reading-group structure

Every selected application follows **original operator and Jacobian → SET →
transformed Jacobian → uniqueness**. Oligopoly uses positive rescaling,
CES complements use logarithms followed by a separate coordinate change,
and public goods use an inverse function to reveal symmetry. The application
blocks focus on these comparisons, not equilibrium-existence proofs,
numerical examples, limiting behavior, or effort rankings. Questions can be
taken during each derivation.

Formal environments retain the paper's original result types and numbering.
Page 12 is the exception:
its short boundary-condition lemma heading uses automatic deck numbering,
and the guide maps it to paper Lemma 4(i). The worked example is an added
seminar game with no original-paper example number. The boundary-condition
lemma displays the lower-bound, interior, and upper-bound cases before
introducing sign equivalence.

| PDF pages | Reading block |
|---|---|
| 1–10 | Motivation, original Figure 1, and the worked nonlinear example |
| 11–17 | Nash equilibrium and VI, coordinate boundary conditions, rectangularity, SET constructions, and constrained uniqueness |
| 18 | Selected Applications: the common Jacobian-comparison sequence |
| 19–24 | Oligopoly: original derivative, E1–E3, positive rescaling, strict diagonal dominance, and Proposition 4 |
| 25–27 | CES complements: original derivative, logarithmic SET, log coordinates, and conditional uniqueness |
| 28–31 | Public goods: original asymmetric derivative, valid inverse SET, symmetric derivative, and Theorem 5 |
| 32–33 | Cross-application Jacobian comparison and conclusions |
| 34 | Optional coordinate proof of Theorem 1(ii) |

The guide suggests a flexible 60–90 minute route including discussion.
For a longer close reading, use up to two hours to unpack the displayed
derivatives, domain checks, and uniqueness arguments. These are planning
ranges, not hard limits for an application or a requirement to add other
results from the paper.

The original marginal-profit operator and the transformed markup gap are
kept distinct. So are equilibrium-set preservation, existence, and uniqueness.
The worked example follows the paper's map from the game to the original
VI, a failed global P-matrix certificate, a sign-equivalent transformation,
and a successful matrix test. Its joint best-response map is not a
contraction in any fixed vector norm, even locally at the explicit unique
equilibrium $(2,1)$. This example uses no potential. Failure of either
sufficient uniqueness test does not imply multiple equilibria. For the network
public-good inverse, the guide explains the equilibrium-preserving box
required by the slide's domain condition. The gain there is a symmetric
Jacobian: the original derivative can already be a P-matrix under the same
spectral condition, so failure of its matrix test is not claimed.

## Compile

Use XeLaTeX with a recent TeX Live or MacTeX installation containing Beamer,
Metropolis, TikZ/PGFPlots, natbib, and appendixnumberbeamer.

```sh
xelatex -interaction=nonstopmode -halt-on-error main.tex
xelatex -interaction=nonstopmode -halt-on-error main.tex
```

The output is `main.pdf`; copy it to `SET-English-Seminar.pdf` after a
successful build. Keep the `assets/` directory next to `main.tex`. No BibTeX
run or external bibliography file is required. On Overleaf, select `main.tex`
as the main document and **XeLaTeX** as the compiler.

Speaking cues remain only in the separate English presenter guide. Older
image assets and `ref.bib` are preserved from the earlier repository version
but are not needed to compile the current `main.tex`. The source paper itself
is not included in this repository. The guide identifies seminar examples
separately from results and numerical examples in the paper.
