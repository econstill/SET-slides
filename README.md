# SET — English Close-Reading Slides

An English, 1–2 hour literature-reading discussion of *SET* by Yves Zenou and
Junjie Zhou (paper version: February 17, 2026), using the supplied
`Hyper0721.tex` Beamer template.

## Files

- [Slides (PDF)](SET-English-Seminar.pdf): 53 pages — 50 main pages (including
  the title) plus three optional technical backup pages.
- [Editable source](main.tex): native Beamer source. The paper's original
  Figure 1 is on page 3, followed immediately by the worked nonlinear
  two-player example on pages 4–10. There are no embedded speaker notes or
  per-slide source footers.
- [Figure 1 crop](assets/set-figure1-methodology.png): the original methodology
  diagram from page 17 of the supplied paper.
- [Presenter guide](SET-English-Presenter-Guide.md): flexible reading routes,
  a paper-page map, cues for every PDF page, a full worked-example script,
  detailed methodology and oligopoly scripts, network-proof explanations, and discussion questions
  with answers. It also maps the formal results to their original paper
  numbers.

Page numbers in the guide refer to physical PDF pages, including the cover;
they are not the Beamer footer numbers.

## Reading-group structure

The organizing sequence is **hypotheses → transformation → proof → economic
implication**. Questions can be taken during each derivation. The main deck
contains the main proof steps for the worked example, oligopoly, and public
goods. The CES block displays the logarithmic system and its derivative,
then states the spectral result. The conditional-uniqueness argument is
explained in the separate guide; the existence and limiting-ratio proofs
are left to the paper.
The backups supply additional checks.

Native lemma, theorem, proposition, corollary, definition, and assumption
environments retain the paper's original types and numbering. Repeated
parts of a result keep the same original number. Page 12 is the exception:
its short boundary-condition lemma heading uses automatic deck numbering,
and the guide maps it to paper Lemma 4(i). The worked example is an added
seminar game with no original-paper example number. The boundary-condition
lemma displays the lower-bound, interior, and upper-bound cases before
introducing sign equivalence.

| PDF pages | Reading block |
|---|---|
| 1–10 | Motivation, original Figure 1, and the worked nonlinear example |
| 11–17 | Nash equilibrium and VI, coordinate boundary conditions, rectangularity, SET constructions, and constrained uniqueness |
| 18 | Selected Applications: overview of the three close-reading blocks |
| 19–32 | Oligopoly: demand restrictions, markup conditions, uniqueness, existence, logit price bounds, and what SET changes |
| 33–34 | Connections to existing peer-effect and potential applications |
| 35–38 | CES complements: logarithmic system, derivative, and spectral threshold statement |
| 39–48 | Public goods: best responses, valid inverse domains, a potential, spectral uniqueness, participation, and rankings |
| 49–50 | What has been established and final discussion |
| 51–53 | Optional technical checks |

The guide offers a full route of approximately 100–120 minutes including
interleaved discussion, and a focused approximately 60-minute route centered
on methodology and oligopoly with selected network conclusions. The shorter
route does **not** claim to derive every proof in the deck. Neither route is a
hard time limit for a particular application: use the available time to
resolve the group's questions, and select or postpone modules accordingly.

The original marginal-profit operator and the transformed markup gap are
kept distinct. So are equilibrium-set preservation, existence, and uniqueness.
The worked example follows the paper's map from the game to the original
VI, a failed global P-matrix certificate, a sign-equivalent transformation,
and a successful matrix test. Its joint best-response map is not a
contraction in any fixed vector norm, even locally at the explicit unique
equilibrium $(2,1)$. This example uses no potential. Failure of either
sufficient uniqueness test does not imply multiple equilibria. For the network
public-good inverse, the slides first construct an equilibrium-containing
box on which the inverse is well-defined.

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
