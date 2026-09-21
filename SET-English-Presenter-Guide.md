# SET: application-focused seminar guide

This guide follows the 40-page PDF: 33 main slides, six optional backup slides, and references. The paper is Yves Zenou and Junjie Zhou, *SET* (February 17, 2026 version). Slide 3 uses the paper's original Figure 1. Slides 4–6 follow its full route with one two-player example. These speaking cues are kept only in this separate guide, not in `main.tex` or the slide PDF.

## Speaking route

| Slides | Focus | Suggested route |
|---|---|---:|
| 1–9 | Question, Figure 1, worked example, and the one result needed for applications | 14 min |
| 10–15 | Existing applications: production, peers, pricing, network games | 10 min |
| 16–25 | New CES complementarity model, centrality, key players | 24 min |
| 26–31 | New public-good model with strategic substitutes | 14 min |
| 32–33 | Synthesis and discussion | 4 min |

Allow about six minutes for the new example: two minutes per page. The full route above totals approximately 66 minutes. For a 75–90-minute seminar, use the remaining time for questions and deeper discussion of production-network transmission, the CES threshold, or the bridge intervention. The backup slides remain optional.

## Slide-by-slide cues

| PDF slide | What to say |
|---:|---|
| 1 | State the question: can a different mathematical representation reveal a useful economic conclusion without changing the equilibrium? |
| 2 | Explain why directly analyzing the original first-order conditions can be unnecessarily difficult. |
| 3 | Show the **original Figure 1**. Equilibrium is a best-response fixed point; the figure itself follows the equivalent variational-inequality route, then branches into a $P$-property or potential method. |
| 4 | Introduce nonnegative actions and strict own-action concavity. Derive both best responses. Multiplying player 2's payoff by four changes its units but not the chosen action. This is a teaching specialization of positive payoff scaling. |
| 5 | Take negative marginal payoffs to form the VI operator. Divide its second component by four. On the product set, the coordinatewise signs preserve the entire VI solution set, including possible boundary solutions. |
| 6 | Follow both branches of Figure 1. Positive principal minors give at most one VI solution. The symmetric transformed operator is also the gradient of a strictly convex minimization potential. The feasible zero (2,2) proves existence. The original matrix already passes the P-matrix test; scaling exposes a simpler potential representation rather than rescuing an otherwise nonunique game. |
| 7 | Tell the audience that examples and substantive predictions, not theorem proofs, are the main subject. |
| 8 | State sign equivalence and the product-domain qualification. It preserves the whole equilibrium set, including corner solutions; it does not create an equilibrium. |
| 9 | Distinguish the two analytical routes and keep existence separate from uniqueness. |
| 10 | Production network: input dependence makes equilibrium prices a nonlinear system. |
| 11 | Log prices expose a pass-through matrix whose row sum is the intermediate-input share. Positive labor shares yield a contraction and a unique equilibrium. |
| 12 | In the Cobb–Douglas limit, the Leontief inverse tracks direct and indirect productivity-shock transmission. |
| 13 | Nonlinear social norms need not be average peer effort. The uniqueness conclusion here is conditional on existence. |
| 14 | Price floors and caps make boundary preservation relevant. The transformed pricing condition gives at most one equilibrium under the stated demand assumptions. |
| 15 | Briefly connect the potential route to income-based public goods and to interactions across multiple network layers. |
| 16 | Introduce the paper's new CES complementarity game. Its adjacency matrix is unnormalized, unlike the social norm on slide 13. |
| 17 | Explain what $\beta$ changes: high- versus low-effort neighbors' relative marginal influence. Avoid saying it only changes spillover strength. |
| 18 | Log equilibrium conditions produce a substochastic interaction matrix, which yields uniqueness conditional on a finite equilibrium. |
| 19 | Emphasize the separate **existence** threshold $\bar\delta=\lambda_{\max}(G)^{-1/\beta}$. No finite positive equilibrium exists at or above it. |
| 20 | Within the existence region, a higher baseline or spillover parameter raises equilibrium actions. |
| 21 | At $\beta=1$, equilibrium is Katz–Bonacich centrality with baseline vector $a$. |
| 22 | Near the critical threshold, relative actions approach a transformed Perron eigenvector. The action levels diverge; this is a limiting ratio, not a finite equilibrium at the threshold. |
| 23 | Use the three-node path plot as an **analytical teaching example**, not a numerical result reported by the paper. Its horizontal axis scales $\delta$ by a $\beta$-specific threshold. |
| 24 | Define the key player by the reduction in total equilibrium activity after removing each player and resolving the game. |
| 25 | Read the bridge network first. The most active player need not be the key player; the paper reports a switch in key-player type as $\beta$ varies. |
| 26 | Transition to substitutes: neighbors' provision reduces one's own incentive to contribute to a public good. Convex costs change the benchmark. |
| 27 | Zero effort is possible in the general model. Best responses lie in a compact box, so an equilibrium exists. |
| 28 | The transformed system has a potential. The smallest network eigenvalue gives a sufficient uniqueness condition, while cost curvature can help beyond the simple bound. |
| 29 | When marginal cost at zero is zero, every player participates at every equilibrium; this statement does not require uniqueness. |
| 30 | On a complete graph, strictly convex costs give a unique equal-effort equilibrium. Linear costs instead allow a continuum of allocations of the same total effort. |
| 31 | On a star, the hub contributes less than the leaves. On nested-split graphs, the lower-degree agents contribute more; degree alone does not rank actions on arbitrary graphs. |
| 32 | Reiterate the distinct questions the slides establish: equilibrium equivalence, existence, and uniqueness. The paper does not formally analyze a general adjustment dynamic. |
| 33 | Close with the economic gains from the two new network applications and invite questions. |

## Optional backup pages

Slides 34–39 contain the coordinate proof, a matrix example, the nonlinear Perron limit, an algebraic-versus-economic-solution example, complete-network uniqueness beyond the sufficient spectral bound, and a star-network ranking argument. Slide 40 has references. Use a backup only in response to a relevant question.

## Terminology and precision

- The paper's Figure 1 is a map from a game to a variational inequality and then to a transformed variational inequality. It is not itself a picture of a fixed-point theorem.
- In the worked example, $\Phi$ is the convex minimization potential. Its negative is the exact payoff potential for the rescaled game $(u_1,u_2/4)$. The original game has a weighted potential. The example illustrates equilibrium-preserving representation, not a stronger uniqueness bound.
- Sign equivalence on a rectangular domain preserves the *set* of VI solutions. Potential symmetry alone does not make every stationary point a global optimum; curvature is needed.
- In the CES complementarity model, the log-transformed matrix gives uniqueness, while a separate Perron argument gives existence below the threshold. Its bounded best-response iteration is part of that existence proof, not a general dynamic-stability result.
- In the strategic-substitutes model, the displayed spectral bound is sufficient, not necessary. The complete-network result is a concrete example where strict convexity of costs yields uniqueness at the boundary of that bound.
