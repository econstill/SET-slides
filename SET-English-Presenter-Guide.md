# SET: application-focused seminar guide

This guide follows the 37-page PDF: 30 main slides, six optional backup slides, and references. The paper is Yves Zenou and Junjie Zhou, *SET* (February 17, 2026 version). Slide 3 uses the paper's original Figure 1. Speaker notes are also embedded in `main.tex` as `\talknote` commands.

## Speaking route

| Slides | Focus | 60-minute route |
|---|---|---:|
| 1–6 | Question, Figure 1, and the one result needed for applications | 8 min |
| 7–12 | Existing applications: production, peers, pricing, network games | 10 min |
| 13–22 | New CES complementarity model, centrality, key players | 24 min |
| 23–28 | New public-good model with strategic substitutes | 14 min |
| 29–30 | Synthesis and discussion | 4 min |

For a 45-minute talk, skim slides 9–12 and 17–20, but retain 3, 8, 15–16, 21–22, and 25–28. For a 75-minute talk, use the extra time for the production-network price transmission, the CES threshold, the bridge intervention, and audience questions. The backup slides are optional and should not be part of the default route.

## Slide-by-slide cues

| PDF slide | What to say |
|---:|---|
| 1 | State the question: can a different mathematical representation reveal a useful economic conclusion without changing the equilibrium? |
| 2 | Explain why directly analyzing the original first-order conditions can be unnecessarily difficult. |
| 3 | Show the **original Figure 1**. Equilibrium is a best-response fixed point; the figure itself follows the equivalent variational-inequality route, then branches into a $P$-property or potential method. |
| 4 | Tell the audience that examples and substantive predictions, not theorem proofs, are the main subject. |
| 5 | State sign equivalence and the product-domain qualification. It preserves the whole equilibrium set, including corner solutions; it does not create an equilibrium. |
| 6 | Distinguish the two analytical routes and keep existence separate from uniqueness. |
| 7 | Production network: input dependence makes equilibrium prices a nonlinear system. |
| 8 | Log prices expose a pass-through matrix whose row sum is the intermediate-input share. Positive labor shares yield a contraction and a unique equilibrium. |
| 9 | In the Cobb–Douglas limit, the Leontief inverse tracks direct and indirect productivity-shock transmission. |
| 10 | Nonlinear social norms need not be average peer effort. The uniqueness conclusion here is conditional on existence. |
| 11 | Price floors and caps make boundary preservation relevant. The transformed pricing condition gives at most one equilibrium under the stated demand assumptions. |
| 12 | Briefly connect the potential route to income-based public goods and to interactions across multiple network layers. |
| 13 | Introduce the paper's new CES complementarity game. Its adjacency matrix is unnormalized, unlike the social norm on slide 10. |
| 14 | Explain what $\beta$ changes: high- versus low-effort neighbors' relative marginal influence. Avoid saying it only changes spillover strength. |
| 15 | Log equilibrium conditions produce a substochastic interaction matrix, which yields uniqueness conditional on a finite equilibrium. |
| 16 | Emphasize the separate **existence** threshold $\bar\delta=\lambda_{\max}(G)^{-1/\beta}$. No finite positive equilibrium exists at or above it. |
| 17 | Within the existence region, a higher baseline or spillover parameter raises equilibrium actions. |
| 18 | At $\beta=1$, equilibrium is Katz–Bonacich centrality with baseline vector $a$. |
| 19 | Near the critical threshold, relative actions approach a transformed Perron eigenvector. The action levels diverge; this is a limiting ratio, not a finite equilibrium at the threshold. |
| 20 | Use the three-node path plot as an **analytical teaching example**, not a numerical result reported by the paper. Its horizontal axis scales $\delta$ by a $\beta$-specific threshold. |
| 21 | Define the key player by the reduction in total equilibrium activity after removing each player and resolving the game. |
| 22 | Read the bridge network first. The most active player need not be the key player; the paper reports a switch in key-player type as $\beta$ varies. |
| 23 | Transition to substitutes: neighbors' provision reduces one's own incentive to contribute to a public good. Convex costs change the benchmark. |
| 24 | Zero effort is possible in the general model. Best responses lie in a compact box, so an equilibrium exists. |
| 25 | The transformed system has a potential. The smallest network eigenvalue gives a sufficient uniqueness condition, while cost curvature can help beyond the simple bound. |
| 26 | When marginal cost at zero is zero, every player participates at every equilibrium; this statement does not require uniqueness. |
| 27 | On a complete graph, strictly convex costs give a unique equal-effort equilibrium. Linear costs instead allow a continuum of allocations of the same total effort. |
| 28 | On a star, the hub contributes less than the leaves. On nested-split graphs, the lower-degree agents contribute more; degree alone does not rank actions on arbitrary graphs. |
| 29 | Reiterate the distinct questions the slides establish: equilibrium equivalence, existence, and uniqueness. The paper does not formally analyze a general adjustment dynamic. |
| 30 | Close with the economic gains from the two new network applications and invite questions. |

## Optional backup pages

Slides 31–36 contain the coordinate proof, a matrix example, the nonlinear Perron limit, an algebraic-versus-economic-solution example, complete-network uniqueness beyond the sufficient spectral bound, and a star-network ranking argument. Slide 37 has references. Use a backup only in response to a relevant question.

## Terminology and precision

- The paper's Figure 1 is a map from a game to a variational inequality and then to a transformed variational inequality. It is not itself a picture of a fixed-point theorem.
- Sign equivalence on a rectangular domain preserves the *set* of VI solutions. Potential symmetry alone does not make every stationary point a global optimum; curvature is needed.
- In the CES complementarity model, the log-transformed matrix gives uniqueness, while a separate Perron argument gives existence below the threshold. Its bounded best-response iteration is part of that existence proof, not a general dynamic-stability result.
- In the strategic-substitutes model, the displayed spectral bound is sufficient, not necessary. The complete-network result is a concrete example where strict convexity of costs yields uniqueness at the boundary of that bound.
