# SET — English Seminar Slides

An English research seminar on *SET* by Yves Zenou and Junjie Zhou
(paper version: February 17, 2026), using the supplied `Hyper0721.tex`
Beamer template.

## Files

- [Slides (PDF)](SET-English-Seminar.pdf): 54 pages — 47 main pages including
  the title, six backup proof/example pages, and one reference page.
- [Editable source](main.tex): self-contained Beamer source with inline
  diagrams, plots, references, and hidden English speaker notes.
- [Presenter guide](SET-English-Presenter-Guide.md): slide-by-slide notes
  and suggested 60-, 75-, and 90-minute routes. The detailed main-deck
  pacing totals approximately 81.5 minutes.

## Compile

Use XeLaTeX with a recent TeX Live or MacTeX installation containing
Beamer, Metropolis, TikZ/PGFPlots, natbib, and appendixnumberbeamer.

```sh
xelatex -interaction=nonstopmode -halt-on-error main.tex
xelatex -interaction=nonstopmode -halt-on-error main.tex
```

The output is `main.pdf`. No BibTeX run, external images, or external
bibliography file is required. On Overleaf, select `main.tex` as the main
document and **XeLaTeX** as the compiler.

Speaker notes are stored in `\talknote{minutes}{text}` commands. Replace
`\setbeameroption{hide notes}` with `\setbeameroption{show notes}` to
include them in the compiled document.

## Scope

The seminar covers sign-equivalent transformations, variational inequalities,
production networks, nonlinear CES strategic complements, spectral thresholds,
Bonacich centrality, key players, and strategic substitutes.

The existing image assets and `ref.bib` are preserved from the earlier
repository version but are not needed to compile the current `main.tex`.
The source paper itself is not included in this upload.
