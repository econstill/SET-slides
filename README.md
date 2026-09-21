# SET — English Seminar Slides

An English research seminar on *SET* by Yves Zenou and Junjie Zhou
(paper version: February 17, 2026), using the supplied `Hyper0721.tex`
Beamer template.

## Files

- [Slides (PDF)](SET-English-Seminar.pdf): 40 pages — 33 main pages including
  the title, six optional backup pages, and one reference page.
- [Editable source](main.tex): Beamer source with the paper's Figure 1 on
  slide 3, a worked two-player example on slides 4–6, and inline diagrams
  and plots, without embedded speaker notes
  or per-slide source footers.
- [Figure 1 crop](assets/set-figure1-methodology.png): the original
  methodology diagram from page 17 of the supplied paper.
- [Presenter guide](SET-English-Presenter-Guide.md): application-focused
  speaking route and suggested timing.

## Compile

Use XeLaTeX with a recent TeX Live or MacTeX installation containing
Beamer, Metropolis, TikZ/PGFPlots, natbib, and appendixnumberbeamer.

```sh
xelatex -interaction=nonstopmode -halt-on-error main.tex
xelatex -interaction=nonstopmode -halt-on-error main.tex
```

The output is `main.pdf`; copy it to `SET-English-Seminar.pdf` after a
successful build. Keep the `assets/` directory next to `main.tex`. No BibTeX
run or external bibliography file is required. On Overleaf, select `main.tex`
as the main document and **XeLaTeX** as the compiler.

The separate presenter guide contains speaking cues and timing suggestions.
They are not embedded in `main.tex` or the slide PDF.

## Scope

The seminar introduces the transformation through the paper's Figure 1,
a worked two-player example that follows both branches of the map, and
one concise equilibrium-set result. It then focuses on production networks,
nonlinear peer effects, oligopoly, multiplex interactions, nonlinear CES
strategic complements, centrality and key players, and network public goods
with convex costs. Proof details are in the optional backup pages.

The older image assets and `ref.bib` are preserved from the earlier
repository version but are not needed to compile the current `main.tex`.
The source paper itself is not included in this repository.
