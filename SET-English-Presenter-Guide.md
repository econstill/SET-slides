# SET: application-focused seminar guide

This guide follows the 45-page PDF: 38 main slides including the title, six optional backup slides, and references. The paper is Yves Zenou and Junjie Zhou, *SET* (February 17, 2026 version). Slide 3 uses the paper's original Figure 1. Slides 4–6 follow its full route with Example 1, a two-player game with positive payoff scaling. Slides 7–9 add Example 2, a nonlinear two-player game whose transformed conditions yield a convex minimization potential. Slides 13–17 introduce the production-network model and derive its price system before applying SET. These speaking cues are kept only in this separate guide, not in `main.tex` or the slide PDF.

## Speaking route

| Slides | Focus | Suggested route |
|---|---|---:|
| 1–12 | Question, Figure 1, Examples 1 and 2, and the one result needed for applications | 20 min |
| 13–20 | Existing applications: production model and price-system derivation, peers, pricing, network games | 15 min |
| 21–30 | New CES complementarity model, centrality, key players | 24 min |
| 31–36 | New public-good model with strategic substitutes | 14 min |
| 37–38 | Synthesis and discussion | 4 min |

Allow about six minutes each for Example 1 and Example 2: two minutes per page. The production-network background and derivation add about five minutes to the previous route. The full route above totals approximately 77 minutes. For a 90-minute seminar, use the remaining time for questions and deeper discussion of production-network transmission, the CES threshold, or the bridge intervention. The backup slides remain optional.

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
| 13 | Introduce a firm in each industry, labor $l_i$, input purchases $q_{ij}$, and productivity $z_i$. The normalized technology is $y_i=z_i(l_i/\alpha_i)^{\alpha_i}(M_i/(1-\alpha_i))^{1-\alpha_i}$, with a CES intermediate bundle $M_i$. Explain the input-link weights $\omega_{ij}=a_{ij}/(1-\alpha_i)$, normalized to sum to one, and the substitution elasticity $\sigma_i$. |
| 14 | Derive costs in two steps. First, choose the cheapest intermediate bundle, with CES unit price $Q_i(p)$. Then minimize labor-plus-bundle spending at a target output. The optimal shares are $wl_i=\alpha_iE_i$ and $Q_iM_i=(1-\alpha_i)E_i$. Substitution into the normalized technology yields $c_i(p,w)=w^{\alpha_i}Q_i(p)^{1-\alpha_i}/z_i$. |
| 15 | Constant returns and price-taking imply that positive finite production requires $p_i=c_i(p,w)$. Substituting the derived unit cost gives the paper's coupled production-price system $p_iz_i=C_i(p)$. Explain why a supplier's price enters its customer's costs. Hold the wage fixed and separate this price subsystem from the demand and market-clearing conditions that determine quantities. |
| 16 | Set $x_i=\log(p_i/w)$ and take logs of the positive price equations. The transformed operator is $x-T(x)$, with derivative $I-W(x)$. Here $W_{ij}$ is supplier $j$'s share in industry $i$'s total cost, and each row sums to $1-\alpha_i$. Positive labor shares give a global contraction, so a positive price vector exists and is unique conditional on the wage. |
| 17 | In the Cobb–Douglas limit, $W=A$ and the Leontief inverse tracks direct and indirect productivity-shock transmission. The same resolvent appears in Bonacich centrality, with a different economic forcing term. |
| 18 | Nonlinear social norms need not be average peer effort. The uniqueness conclusion here is conditional on existence. |
| 19 | Price floors and caps make boundary preservation relevant. The transformed pricing condition gives at most one equilibrium under the stated demand assumptions. |
| 20 | Briefly connect the potential route to income-based public goods and to interactions across multiple network layers. |
| 21 | Introduce the paper's new CES complementarity game. Its adjacency matrix is unnormalized, unlike the social norm on slide 18. |
| 22 | Explain what $\beta$ changes: high- versus low-effort neighbors' relative marginal influence. Avoid saying it only changes spillover strength. |
| 23 | Log equilibrium conditions produce a substochastic interaction matrix, which yields uniqueness conditional on a finite equilibrium. |
| 24 | Emphasize the separate **existence** threshold $\bar\delta=\lambda_{\max}(G)^{-1/\beta}$. No finite positive equilibrium exists at or above it. |
| 25 | Within the existence region, a higher baseline or spillover parameter raises equilibrium actions. |
| 26 | At $\beta=1$, equilibrium is Katz–Bonacich centrality with baseline vector $a$. |
| 27 | Near the critical threshold, relative actions approach a transformed Perron eigenvector. The action levels diverge; this is a limiting ratio, not a finite equilibrium at the threshold. |
| 28 | Use the three-node path plot as an **analytical teaching example**, not a numerical result reported by the paper. Its horizontal axis scales $\delta$ by a $\beta$-specific threshold. |
| 29 | Define the key player by the reduction in total equilibrium activity after removing each player and resolving the game. |
| 30 | Read the bridge network first. The most active player need not be the key player; the paper reports a switch in key-player type as $\beta$ varies. |
| 31 | Transition to substitutes: neighbors' provision reduces one's own incentive to contribute to a public good. Convex costs change the benchmark. |
| 32 | Zero effort is possible in the general model. Best responses lie in a compact box, so an equilibrium exists. |
| 33 | The transformed system has a potential. The smallest network eigenvalue gives a sufficient uniqueness condition, while cost curvature can help beyond the simple bound. |
| 34 | When marginal cost at zero is zero, every player participates at every equilibrium; this statement does not require uniqueness. |
| 35 | On a complete graph, strictly convex costs give a unique equal-effort equilibrium. Linear costs instead allow a continuum of allocations of the same total effort. |
| 36 | On a star, the hub contributes less than the leaves. On nested-split graphs, the lower-degree agents contribute more; degree alone does not rank actions on arbitrary graphs. |
| 37 | Reiterate the distinct questions the slides establish: equilibrium equivalence, existence, and uniqueness. The paper does not formally analyze a general adjustment dynamic. |
| 38 | Close with the economic gains from the two new network applications and invite questions. |

## Optional backup pages

Slides 39–44 contain the coordinate proof, a matrix example, the nonlinear Perron limit, an algebraic-versus-economic-solution example, complete-network uniqueness beyond the sufficient spectral bound, and a star-network ranking argument. Slide 45 has references. Use a backup only in response to a relevant question.

## Terminology and precision

- The paper's Figure 1 is a map from a game to a variational inequality and then to a transformed variational inequality. It is not itself a picture of a fixed-point theorem.
- In Example 1, $\Phi$ is the convex minimization potential. Its negative is the exact payoff potential for the rescaled game $(u_1,u_2/4)$. The original game has a weighted potential. The example illustrates equilibrium-preserving representation, not a stronger uniqueness bound.
- In Example 2, the increasing exponential preserves the sign of the second VI comparison. The resulting $\Phi$ is a convex minimization potential for the transformed VI, not an exact payoff potential for the original game. Strong convexity and coercivity give existence and uniqueness of the minimizer on $K$. The original operator is already strongly monotone; the transformation exposes a convex optimization representation.
- Sign equivalence on a rectangular domain preserves the *set* of VI solutions. Potential symmetry alone does not make every stationary point a global optimum; curvature is needed.
- The production-network derivation follows the supplied paper, pp. 18–19, equations (9)–(14). On p. 18, equation (9) prints the normalization factor $\zeta_i$ with $\alpha_i^{+\alpha_i}$, but deriving the unit-cost expression in equation (13) requires $\alpha_i^{-\alpha_i}$. The presentation uses normalized technology consistent with equation (13), rather than reproducing that erroneous factor literally.
- The production-network normalization $\sum_j a_{ij}=1-\alpha_i$ is an additional normalization of technology weights. Constant returns to scale alone does not imply it. For general CES substitution, $a_{ij}$ are technology weights, while $W_{ij}(x)$ are the actual intermediate-input shares in total cost. They coincide in the Cobb–Douglas limit.
- The production-network contraction establishes existence and uniqueness of the positive **price subsystem conditional on the wage**. A claim about a full general equilibrium, including quantities, requires demand and market-clearing conditions beyond these slides.
- In the CES complementarity model, the log-transformed matrix gives uniqueness, while a separate Perron argument gives existence below the threshold. Its bounded best-response iteration is part of that existence proof, not a general dynamic-stability result.
- In the strategic-substitutes model, the displayed spectral bound is sufficient, not necessary. The complete-network result is a concrete example where strict convexity of costs yields uniqueness at the boundary of that bound.
