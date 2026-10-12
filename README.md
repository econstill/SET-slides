# SET — English Close-Reading Slides

An English, 1–2 hour literature-reading discussion of *SET* by Yves Zenou and
Junjie Zhou (paper version: February 17, 2026), using the supplied
`Hyper0721.tex` Beamer template.

## Files

- [Slides (PDF)](SET-English-Seminar.pdf): 64 pages — 60 main pages (including
  the title) plus four optional technical backup pages.
- [Editable source](main.tex): native Beamer source. The paper's original
  Figure 1 is on page 3, followed immediately by the two worked two-player
  examples on pages 4–6 and 7–9. There are no embedded speaker notes or
  per-slide source footers.
- [Figure 1 crop](assets/set-figure1-methodology.png): the original methodology
  diagram from page 17 of the supplied paper.
- [Presenter guide](SET-English-Presenter-Guide.md): flexible reading routes,
  a paper-page map, cues for every PDF page, detailed methodology and
  oligopoly scripts, network-proof explanations, and discussion questions
  with answers. It also maps the formal results to their original paper
  numbers.

Page numbers in the guide refer to physical PDF pages, including the cover;
they are not the Beamer footer numbers.

## Reading-group structure

The organizing sequence is **hypotheses → transformation → proof → economic
implication**. Questions can be taken during each derivation. The main deck
contains the proof steps needed for close reading; the backups supply
additional checks rather than holding all the substantive mathematics.

Native lemma, theorem, proposition, corollary, definition, and assumption
environments retain the paper's original types and numbering. Repeated
parts of a result keep the same original number. Seminar teaching examples
remain distinct from the paper's examples; in particular, the two-player
Example 2 on pages 7–9 is not the paper's regular-network Example 2 on
page 38.

| PDF pages | Reading block |
|---|---|
| 1–9 | Motivation, original Figure 1, and two complete worked examples |
| 10–15 | Nash equilibrium and VI, rectangularity, SET constructions, and constrained uniqueness |
| 16 | Selected Applications: overview of the three close-reading blocks |
| 17–31 | Oligopoly: consumer choice, markup conditions, E1–E3, uniqueness, existence, logit price bounds, and what SET changes |
| 32–33 | Connections to existing peer-effect and potential applications |
| 34–48 | CES complements: uniqueness, the spectral existence threshold, Bonacich/eigenvector centrality, and key players |
| 49–58 | Public goods: best responses, valid inverse domains, a potential, spectral uniqueness, participation, and rankings |
| 59–60 | What has been established and final discussion |
| 61–64 | Optional technical checks |

The guide offers a full route of approximately 105–120 minutes including
interleaved discussion, and a focused approximately 60-minute route centered
on methodology and oligopoly with selected network conclusions. The shorter
route does **not** claim to derive every proof in the deck. Neither route is a
hard time limit for a particular application: use the available time to
resolve the group's questions, and select or postpone modules accordingly.

The original marginal-profit operator and the transformed markup gap are
kept distinct. So are equilibrium-set preservation, existence, and uniqueness.
For the network public-good inverse, the slides first construct an
equilibrium-containing box on which the inverse is well-defined. The linear
centrality section explicitly connects `(I − δG)x = b` to the eigenvalues and
eigenvectors of `G`.

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
