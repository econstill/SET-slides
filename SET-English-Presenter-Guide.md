# SET: application-focused seminar guide

This guide follows the 43-page PDF: 36 main slides including the title, six optional backup slides, and references. The paper is Yves Zenou and Junjie Zhou, *SET* (February 17, 2026 version). Slide 3 uses the paper's original Figure 1. Slides 4–6 follow its full route with Example 1, a two-player game with positive payoff scaling. Slides 7–9 add Example 2, a nonlinear two-player game whose transformed conditions yield a convex minimization potential. These speaking cues are kept only in this separate guide, not in `main.tex` or the slide PDF.

## Speaking route

| Slides | Focus | Suggested route |
|---|---|---:|
| 1–12 | Question, Figure 1, Examples 1 and 2, and the one result needed for applications | 20 min |
| 13–18 | Existing applications: production, peers, pricing, network games | 10 min |
| 19–28 | New CES complementarity model, centrality, key players | 24 min |
| 29–34 | New public-good model with strategic substitutes | 14 min |
| 35–36 | Synthesis and discussion | 4 min |

Allow about six minutes each for Example 1 and Example 2: two minutes per page. The full route above totals approximately 72 minutes. For a 75–90-minute seminar, use the remaining time for questions and deeper discussion of production-network transmission, the CES threshold, or the bridge intervention. The backup slides remain optional.

## Slide-by-slide cues

| PDF slide | What to say |
|---:|---|
| 1 | State the question: can a different mathematical representation reveal a useful economic conclusion without changing the equilibrium? |
| 2 | Explain why directly analyzing the original first-order conditions can be unnecessarily difficult. |
| 3 | Show the **original Figure 1**. Equilibrium is a best-response fixed point; the figure itself follows the equivalent variational-inequality route, then branches into a $P$-property or potential method. |
| 4 | Introduce Example 1: nonnegative actions and strict own-action concavity. Derive both best responses. Multiplying player 2's payoff by four changes its units but not the chosen action. This is a teaching specialization of positive payoff scaling. |
| 5 | Take negative marginal payoffs to form the VI operator. Divide its second component by four. On the product set, the coordinatewise signs preserve the entire VI solution set, including possible boundary solutions. |
| 6 | Follow both branches of Figure 1. Positive principal minors give at most one VI solution. The symmetric transformed operator is also the gradient of a strictly convex minimization potential. The feasible zero (2,2) proves existence. The original matrix already passes the P-matrix test; scaling exposes a simpler potential representation rather than rescuing an otherwise nonunique game. |
| 7 | Introduce Example 2 on $K=\mathbb R_+^2$: $u_1=x_1(1+x_2)-x_1^2-x_1^3/3$ and $u_2=x_2\ln(2+x_1)-x_2^2/2$. Strict own-action concavity gives $BR_1(x_2)=\sqrt{2+x_2}-1$ and $BR_2(x_1)=\ln(2+x_1)$. Both best responses are positive on the feasible domain. |
| 8 | Form $F=(x_1^2+2x_1-1-x_2,\,x_2-\ln(2+x_1))$. The original cross derivatives are $-1$ and $-1/(2+x_1)$. Apply the increasing exponential to both sides of the second comparison: $\widetilde F_2=e^{x_2}-2-x_1$, keeping $\widetilde F_1=F_1$. Every coordinate sign, and hence the entire VI solution set on $K$, is preserved. Both transformed cross derivatives equal $-1$. |
| 9 | Integrate to obtain $\Phi=x_1^3/3+x_1^2-x_1-x_1x_2+e^{x_2}-2x_2$. Its Hessian is $\left[\begin{smallmatrix}2+2x_1&-1\\-1&e^{x_2}\end{smallmatrix}\right]\succeq\left[\begin{smallmatrix}2&-1\\-1&1\end{smallmatrix}\right]\succ0$ on $K$, so $\Phi$ is strongly convex and coercive. Minimization yields the unique equilibrium $x^*\approx(0.733681,1.005649)$. The original $F$ is already strongly monotone; the gain is a convex optimization representation, not a stronger uniqueness conclusion. |
| 10 | Tell the audience that examples and substantive predictions, not theorem proofs, are the main subject. |
| 11 | State sign equivalence and the product-domain qualification. It preserves the whole equilibrium set, including corner solutions; it does not create an equilibrium. |
| 12 | Distinguish the two analytical routes and keep existence separate from uniqueness. |
| 13 | Production network: input dependence makes equilibrium prices a nonlinear system. |
| 14 | Log prices expose a pass-through matrix whose row sum is the intermediate-input share. Positive labor shares yield a contraction and a unique equilibrium. |
| 15 | In the Cobb–Douglas limit, the Leontief inverse tracks direct and indirect productivity-shock transmission. |
| 16 | Nonlinear social norms need not be average peer effort. The uniqueness conclusion here is conditional on existence. |
| 17 | Price floors and caps make boundary preservation relevant. The transformed pricing condition gives at most one equilibrium under the stated demand assumptions. |
| 18 | Briefly connect the potential route to income-based public goods and to interactions across multiple network layers. |
| 19 | Introduce the paper's new CES complementarity game. Its adjacency matrix is unnormalized, unlike the social norm on slide 16. |
| 20 | Explain what $\beta$ changes: high- versus low-effort neighbors' relative marginal influence. Avoid saying it only changes spillover strength. |
| 21 | Log equilibrium conditions produce a substochastic interaction matrix, which yields uniqueness conditional on a finite equilibrium. |
| 22 | Emphasize the separate **existence** threshold $\bar\delta=\lambda_{\max}(G)^{-1/\beta}$. No finite positive equilibrium exists at or above it. |
| 23 | Within the existence region, a higher baseline or spillover parameter raises equilibrium actions. |
| 24 | At $\beta=1$, equilibrium is Katz–Bonacich centrality with baseline vector $a$. |
| 25 | Near the critical threshold, relative actions approach a transformed Perron eigenvector. The action levels diverge; this is a limiting ratio, not a finite equilibrium at the threshold. |
| 26 | Use the three-node path plot as an **analytical teaching example**, not a numerical result reported by the paper. Its horizontal axis scales $\delta$ by a $\beta$-specific threshold. |
| 27 | Define the key player by the reduction in total equilibrium activity after removing each player and resolving the game. |
| 28 | Read the bridge network first. The most active player need not be the key player; the paper reports a switch in key-player type as $\beta$ varies. |
| 29 | Transition to substitutes: neighbors' provision reduces one's own incentive to contribute to a public good. Convex costs change the benchmark. |
| 30 | Zero effort is possible in the general model. Best responses lie in a compact box, so an equilibrium exists. |
| 31 | The transformed system has a potential. The smallest network eigenvalue gives a sufficient uniqueness condition, while cost curvature can help beyond the simple bound. |
| 32 | When marginal cost at zero is zero, every player participates at every equilibrium; this statement does not require uniqueness. |
| 33 | On a complete graph, strictly convex costs give a unique equal-effort equilibrium. Linear costs instead allow a continuum of allocations of the same total effort. |
| 34 | On a star, the hub contributes less than the leaves. On nested-split graphs, the lower-degree agents contribute more; degree alone does not rank actions on arbitrary graphs. |
| 35 | Reiterate the distinct questions the slides establish: equilibrium equivalence, existence, and uniqueness. The paper does not formally analyze a general adjustment dynamic. |
| 36 | Close with the economic gains from the two new network applications and invite questions. |

## Optional backup pages

Slides 37–42 contain the coordinate proof, a matrix example, the nonlinear Perron limit, an algebraic-versus-economic-solution example, complete-network uniqueness beyond the sufficient spectral bound, and a star-network ranking argument. Slide 43 has references. Use a backup only in response to a relevant question.

## Terminology and precision

- The paper's Figure 1 is a map from a game to a variational inequality and then to a transformed variational inequality. It is not itself a picture of a fixed-point theorem.
- In Example 1, $\Phi$ is the convex minimization potential. Its negative is the exact payoff potential for the rescaled game $(u_1,u_2/4)$. The original game has a weighted potential. The example illustrates equilibrium-preserving representation, not a stronger uniqueness bound.
- In Example 2, the increasing exponential preserves the sign of the second VI comparison. The resulting $\Phi$ is a convex minimization potential for the transformed VI, not an exact payoff potential for the original game. Strong convexity and coercivity give existence and uniqueness of the minimizer on $K$. The original operator is already strongly monotone; the transformation exposes a convex optimization representation.
- Sign equivalence on a rectangular domain preserves the *set* of VI solutions. Potential symmetry alone does not make every stationary point a global optimum; curvature is needed.
- In the CES complementarity model, the log-transformed matrix gives uniqueness, while a separate Perron argument gives existence below the threshold. Its bounded best-response iteration is part of that existence proof, not a general dynamic-stability result.
- In the strategic-substitutes model, the displayed spectral bound is sufficient, not necessary. The complete-network result is a concrete example where strict convexity of costs yields uniqueness at the boundary of that bound.
