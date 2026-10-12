# SET — English Seminar Slides

An English research seminar on *SET* by Yves Zenou and Junjie Zhou
(paper version: February 17, 2026), using the supplied `Hyper0721.tex`
Beamer template.

## Files

- [Slides (PDF)](SET-English-Seminar.pdf): 50 pages — 41 main pages including
  the title, eight optional backup pages, and one reference page.
- [Editable source](main.tex): Beamer source with the paper's Figure 1 on
  slide 3, two worked two-player examples on slides 4–6 and 7–9, a production-network
  application with a running two-industry example on slides 13–20, and inline diagrams and plots, without embedded speaker notes
  or per-slide source footers.
- [Figure 1 crop](assets/set-figure1-methodology.png): the original
  methodology diagram from page 17 of the supplied paper.
- [Presenter guide](SET-English-Presenter-Guide.md): application-focused
  speaking route, suggested timing, and a detailed speaking script for each
  production-network slide.

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
Example 1 on positive payoff scaling that follows both branches of the map,
Example 2 on a nonlinear transformation that exposes a convex minimization
potential, and one concise equilibrium-set result. The production-network application
explains unit cost and zero profit through two industries that buy each other's output.
An exact productivity-shock calculation separates the direct effect from network feedback.
The sequence then introduces CES intermediate prices, the sign-preserving log
transformation, cost shares and contraction, and the Leontief–Bonacich connection.
It studies the positive price subsystem conditional on a fixed wage. The seminar then covers
nonlinear peer effects, oligopoly, multiplex interactions, nonlinear CES
strategic complements, centrality and key players, and network public goods
with convex costs. The main speaking route takes approximately 82–85 minutes,
including 14–16 minutes for production networks, leaving time for questions within
a 90-minute seminar. Pages 42–43 give the full production-cost derivation and matrix
test. Pages 44–49 contain other optional proof details, and page 50 has references.

The older image assets and `ref.bib` are preserved from the earlier
repository version but are not needed to compile the current `main.tex`.
The source paper itself is not included in this repository.
