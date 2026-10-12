# SET: application-focused seminar guide

This guide follows the 50-page PDF: 41 main slides including the title, eight optional backup slides, and references. The paper is Yves Zenou and Junjie Zhou, *SET* (February 17, 2026 version). Slide 3 uses the paper's original Figure 1. Slides 4–6 follow its full route with Example 1, a two-player game with positive payoff scaling. Slides 7–9 add Example 2, a nonlinear two-player game whose transformed conditions yield a convex minimization potential. Slides 13–20 explain production prices through a running two-industry example before introducing the general CES model and its log transformation. These speaking cues are kept only in this separate guide, not in `main.tex` or the slide PDF.

## Speaking route

| Slides | Focus | Suggested route |
|---|---|---:|
| 1–12 | Question, Figure 1, Examples 1 and 2, and the one result needed for applications | 20 min |
| 13–20 | Production networks: unit cost, two-industry feedback, CES prices, and SET | 16 min |
| 21–23 | Other existing applications: peers, pricing, network games | 4 min |
| 24–33 | New CES complementarity model, centrality, key players | 24 min |
| 34–39 | New public-good model with strategic substitutes | 14 min |
| 40–41 | Synthesis and discussion | 4 min |

Allow about six minutes each for Example 1 and Example 2: two minutes per page. Give the production-network sequence 14–16 minutes, including time to read the two-industry equations and solve the productivity shock. The planned route totals 82 minutes, or about 85 minutes with short pauses. This leaves five to eight minutes for questions in a 90-minute seminar. The backup slides remain optional and replace other discussion time rather than extending the talk beyond 90 minutes.

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
| 13 | Explain why suppliers' prices and customers' costs determine one another. Hold the wage fixed and ask whether a consistent positive price vector exists and is unique. This is a price subsystem, not the entire general equilibrium. |
| 14 | Define unit cost and the intermediate-bundle price $Q_i(p)$. Cobb–Douglas production between labor and this bundle gives $c_i=w^{\alpha_i}Q_i^{1-\alpha_i}/z_i$ after cost minimization. Explain each factor before proceeding. The full quantity derivation is on backup page 42. |
| 15 | Set the fixed wage to one. Each of two industries buys only the other industry's good and spends half its cost on labor. Positive finite competitive production requires $p_1=\sqrt{p_2}/z_1$ and $p_2=\sqrt{p_1}/z_2$. At unit productivity, both prices equal one. |
| 16 | Double industry 1's productivity. Log equations give $x_1=-\log2+\tfrac12x_2$ and $x_2=\tfrac12x_1$, hence prices approximately $(0.397,0.630)$. Holding industry 2's price fixed would give $p_1=0.5$. The extra fall to $0.397$ measures feedback through cheaper inputs. This is an exact solution, not a linear approximation. |
| 17 | Generalize to several suppliers and define the CES intermediate price index $Q_i(p)$. The weights $\omega_{ij}$ describe technology, while actual supplier expenditure shares can change with prices. Our one-supplier teaching case has no substitution margin and remains a special case of this model. |
| 18 | Take logs of both positive sides of the zero-profit condition, then use $p=e^x$ and $\varepsilon_i=\log z_i$. The logarithm preserves the sign of the residual, and the coordinate change is one-to-one. The equation $x=T(x)$ therefore describes exactly the same positive prices. General CES equations usually remain nonlinear in logs. |
| 19 | Interpret $W_{ij}=\partial T_i/\partial x_j$ as supplier $j$'s share in total cost. Row sums equal $1-\alpha_i<1$. The global contraction gives existence and uniqueness on $\mathbb R^n$. The paper instead develops the strong-$P$ route from the same cost-share structure. The expanded derivative and matrix test are on backup page 43. |
| 20 | In the Cobb–Douglas limit, supplier cost shares become constant and $x=-\varepsilon+Ax$. The Leontief inverse collects paths through the input network. In the teaching case, a return trip has weight $1/4$, yielding the multiplier $1+1/4+1/16+\cdots=4/3$. Connect the inverse to Bonacich centrality while distinguishing its forcing vector from productivity. |
| 21 | Nonlinear social norms need not be average peer effort. The uniqueness conclusion here is conditional on existence. |
| 22 | Price floors and caps make boundary preservation relevant. The transformed pricing condition gives at most one equilibrium under the stated demand assumptions. |
| 23 | Briefly connect the potential route to income-based public goods and to interactions across multiple network layers. |
| 24 | Introduce the paper's new CES complementarity game. Its adjacency matrix is unnormalized, unlike the social norm on slide 21. |
| 25 | Explain what $\beta$ changes: high- versus low-effort neighbors' relative marginal influence. Avoid saying it only changes spillover strength. |
| 26 | Log equilibrium conditions produce a substochastic interaction matrix, which yields uniqueness conditional on a finite equilibrium. |
| 27 | Emphasize the separate **existence** threshold $\bar\delta=\lambda_{\max}(G)^{-1/\beta}$. No finite positive equilibrium exists at or above it. |
| 28 | Within the existence region, a higher baseline or spillover parameter raises equilibrium actions. |
| 29 | At $\beta=1$, equilibrium is Katz–Bonacich centrality with baseline vector $a$. |
| 30 | Near the critical threshold, relative actions approach a transformed Perron eigenvector. The action levels diverge; this is a limiting ratio, not a finite equilibrium at the threshold. |
| 31 | Use the three-node path plot as an **analytical teaching example**, not a numerical result reported by the paper. Its horizontal axis scales $\delta$ by a $\beta$-specific threshold. |
| 32 | Define the key player by the reduction in total equilibrium activity after removing each player and resolving the game. |
| 33 | Read the bridge network first. The most active player need not be the key player; the paper reports a switch in key-player type as $\beta$ varies. |
| 34 | Transition to substitutes: neighbors' provision reduces one's own incentive to contribute to a public good. Convex costs change the benchmark. |
| 35 | Zero effort is possible in the general model. Best responses lie in a compact box, so an equilibrium exists. |
| 36 | The transformed system has a potential. The smallest network eigenvalue gives a sufficient uniqueness condition, while cost curvature can help beyond the simple bound. |
| 37 | When marginal cost at zero is zero, every player participates at every equilibrium; this statement does not require uniqueness. |
| 38 | On a complete graph, strictly convex costs give a unique equal-effort equilibrium. Linear costs instead allow a continuum of allocations of the same total effort. |
| 39 | On a star, the hub contributes less than the leaves. On nested-split graphs, the lower-degree agents contribute more; degree alone does not rank actions on arbitrary graphs. |
| 40 | Reiterate the distinct questions the slides establish: equilibrium equivalence, existence, and uniqueness. The paper does not formally analyze a general adjustment dynamic. |
| 41 | Close with the economic gains from the two new network applications and invite questions. |

## Production-network speaking script

### Slide 13: Production networks: the price question

Think of an industry as both a producer and a customer. It hires workers and buys goods from other industries. Its suppliers' prices therefore enter its production costs. The industry takes those input prices as given when choosing how to produce, but the economy must determine all of these prices together.

Suppose a supplier becomes more productive. Its cost falls, so competition allows its price to fall. Its customers now have cheaper inputs. Their costs and prices fall as well. If the original supplier buys from those customers, some of that cost reduction returns to it. This is the feedback we want to understand.

The question is whether there is one positive price vector consistent with all firms' production costs. Throughout this application, we hold the wage fixed. We are not solving for household demand, output quantities, or the wage that clears the labor market. We isolate the price equations so that the economic feedback and the role of the transformation are easy to see.

### Slide 14: A firm's cost of production

Unit cost means the smallest expenditure required to produce one unit of output. First, imagine that the firm has already combined the goods it buys into an intermediate-input bundle. The price of one unit of that bundle is $Q_i$. We will explain how the firm chooses the bundle a few slides later.

The firm combines labor and this bundle using a Cobb–Douglas technology. Cost minimization allocates the fraction $\alpha_i$ of its spending to labor and the fraction $1-\alpha_i$ to intermediates. With the normalization of the quantity technology shown on backup page 42, this gives the formula on the slide. Wages enter with exponent $\alpha_i$, the intermediate price enters with exponent $1-\alpha_i$, and productivity divides the whole expression.

Each part has a simple interpretation. More expensive labor or intermediates raise the cost of a unit of output. Higher productivity lowers that cost. Doubling productivity halves unit cost if input prices do not change. Constant returns mean that producing ten times as much costs ten times as much, so unit cost itself does not depend on output.

If someone asks for the derivation, let total expenditure be $E_i$. Optimal labor spending is $\alpha_i E_i$, and intermediate spending is $(1-\alpha_i)E_i$. Divide those expenditures by their prices to obtain input quantities. Substituting into the normalized production function gives $y_i=z_iE_i/(w^{\alpha_i}Q_i^{1-\alpha_i})$. Rearranging yields the displayed unit cost.

### Slide 15: Two industries: a simple price system

Now take two industries and measure every price in units of the fixed wage, so the wage equals one. Each industry spends half of its production cost on labor and half on the other industry's good. Industry 1 has only industry 2 as an intermediate supplier, so its bundle price is simply $p_2$. Similarly, industry 2's bundle price is $p_1$.

Substituting into the unit-cost formula gives the two square-root expressions. Why must selling price equal unit cost? If price is below unit cost, producing a positive amount loses money. If price is above unit cost, a price-taking firm with constant returns wants to produce without bound. Positive finite production therefore requires equality.

Read the first equation as saying that industry 1's price must cover its cheapest production cost, given industry 2's price. The second equation imposes the same requirement on industry 2. Both must hold at the same time. At productivity one in both industries, prices one in both industries satisfy the system.

This is a deliberately simple teaching case. Each industry has one supplier, so there is no choice among suppliers yet. It isolates price feedback before we introduce CES substitution.

### Slide 16: Two industries: a productivity shock

Start from prices one and let industry 1's productivity double. If industry 2's price stayed at one, the first unit-cost equation would give industry 1 a price of one-half. But industry 2 buys from industry 1, so it now receives a cheaper input. Its own price falls, and that helps industry 1 again.

To solve the simultaneous system, take logs. Since the log of a square root is half the log, the equations become $x_1=-\log2+\tfrac12x_2$ and $x_2=\tfrac12x_1$. Substitute the second into the first. We obtain $x_1=-\log2+\tfrac14x_1$. Moving the last term to the left gives $x_1=-\tfrac43\log2$, and then $x_2=-\tfrac23\log2$.

Exponentiating gives the prices in the table. Industry 1's price falls to about $0.397$, and industry 2's price falls to about $0.630$. The important comparison is $0.5$ versus $0.397$. The direct productivity effect alone gives $0.5$. The extra reduction comes from cheaper inputs returning through the network.

Everything here is exact. Taking logs changes the representation, not the economic solution. This particular example becomes linear in logs. The general CES system that follows usually does not.

### Slide 17: Many suppliers: the CES input price index

Return to the bundle price that we left unexplained. An industry may buy from several suppliers and choose the cheapest combination of their goods. A CES intermediate technology gives the price index shown here. We can read it as the minimum cost of obtaining one unit of the intermediate bundle.

The weights $\omega_{ij}$ describe the role of each supplier in industry $i$'s technology. They add to one. The parameter $\sigma_i$ measures how readily the firm can substitute one supplier's good for another's. The paper considers $\sigma_i>1$, and the Cobb–Douglas case follows as a limit when $\sigma_i$ approaches one.

It is important to distinguish technology weights from actual spending shares. With CES substitution, a change in relative prices changes the cheapest input mix, so the firm's expenditure shares generally change. We will use those expenditure shares on slide 19.

The zero-profit condition stays the same: selling price equals unit cost. Only the expression for the intermediate bundle's price is richer. Our two-industry example is a special case because a one-supplier bundle has price equal to that supplier's price, regardless of the CES parameter. With several suppliers, the resulting price equations are generally nonlinear.

### Slide 18: SET: the same prices in a better representation

The original price condition compares two positive quantities: $p_i z_i$ and $Q_i(p)^{1-\alpha_i}$. Since the logarithm is strictly increasing, the first quantity is above, equal to, or below the second exactly when its logarithm is above, equal to, or below the second logarithm. This preserves the sign of every equilibrium residual.

Now define $x_i=\log p_i$ and $\varepsilon_i=\log z_i$. The transformed equation says that $x_i$ equals the log unit cost, which we call $T_i(x)$. The entire system is $x=T(x)$.

There are two separate operations here. Taking logs of the positive expressions preserves their comparison signs. Writing prices as $p=e^x$ changes coordinates. Every positive price vector has exactly one log-price vector, and every vector in $\mathbb R^n$ gives exactly one positive price vector. Thus the transformed system has exactly the same positive price equilibria.

We should not promise that logs make every production network linear. They did in our teaching case, but general CES price indices remain nonlinear in logs. The benefit is that the derivatives of the transformed map have a clear economic meaning: they are cost shares.

### Slide 19: Labor limits the feedback in prices

Ask how a small percentage increase in supplier $j$'s price changes industry $i$'s unit cost. Cost minimization implies that this response equals the fraction of total production cost spent on good $j$. That is the derivative $W_{ij}$ on the slide. It is nonnegative.

Add these derivatives across all suppliers. Intermediate inputs account for $1-\alpha_i$ of total cost. The remaining fraction goes to labor, whose price we have fixed. Thus a common small percentage increase in every supplier's price raises unit cost by less than the same percentage. In our two-industry example, each industry's feedback coefficient is one-half.

This bound holds at every price vector. Integrating the derivative bound between any two log-price vectors gives the contraction inequality, with $q=\max_i(1-\alpha_i)<1$. There cannot be two fixed points: if $x$ and $y$ were both fixed points and their largest coordinate difference were $d$, the inequality would give $d\leq qd$. Since $q<1$, this forces $d=0$.

Existence is a separate part of the contraction theorem. The map is defined on all of the complete space $\mathbb R^n$ and maps it into itself. Repeatedly applying it converges to a fixed point from any starting log-price vector. Exponentiating gives the unique positive price vector, conditional on the fixed wage.

The paper develops the strong-$P$ argument using the same cost-share structure. The simpler contraction argument here supplies an intuitive explanation of both existence and uniqueness. Backup page 43 displays the expanded derivative and the corresponding $P$-matrix test. This computational iteration is not a claim about how real firms dynamically adjust their prices.

### Slide 20: Cobb–Douglas: tracing the network multiplier

In the Cobb–Douglas limit, supplier expenditure shares no longer change with prices. Write these constant shares as the matrix $A$. The log-price system becomes $x=-\varepsilon+Ax$, and solving it gives $x=-(I-A)^{-1}\varepsilon$.

The inverse has a useful expansion. The identity term is the producer's direct price response to higher productivity. The term $A$ transmits that reduction to its direct customers. The term $A^2$ transmits it through two supply links, and higher powers continue through longer paths. Positive labor shares keep the row sums of $A$ below one, so these effects shrink and the series converges.

Return to our two industries. A reduction in industry 1's log price affects industry 2 with coefficient one-half, then returns to industry 1 with another coefficient one-half. One complete return trip therefore has weight one-quarter. The total own-price multiplier is $1+1/4+1/16+\cdots=4/3$, exactly the coefficient we obtained when solving the productivity shock. Industry 2's multiplier is one-half of that, or $2/3$.

This is the same inverse that appears in Katz–Bonacich centrality when $A=\delta G$. The mathematical structure is shared, but the forcing vector has a different economic meaning. Here it is minus log productivity. In the centrality model, it is a baseline vector of activity or influence.

## Optional backup pages

Slide 42 derives the production unit cost from the normalized quantity technology and optimal expenditure shares. Slide 43 expands the log-price map and derivative, then connects the cost-share bound to the $P$-matrix test. Slides 44–49 contain the coordinate proof, a matrix example, the nonlinear Perron limit, an algebraic-versus-economic-solution example, complete-network uniqueness beyond the sufficient spectral bound, and a star-network ranking argument. Slide 50 has references. Use a backup only in response to a relevant question.

## Terminology and precision

- The paper's Figure 1 is a map from a game to a variational inequality and then to a transformed variational inequality. It is not itself a picture of a fixed-point theorem.
- In Example 1, $\Phi$ is the convex minimization potential. Its negative is the exact payoff potential for the rescaled game $(u_1,u_2/4)$. The original game has a weighted potential. The example illustrates equilibrium-preserving representation, not a stronger uniqueness bound.
- In Example 2, the increasing exponential preserves the sign of the second VI comparison. The resulting $\Phi$ is a convex minimization potential for the transformed VI, not an exact payoff potential for the original game. Strong convexity and coercivity give existence and uniqueness of the minimizer on $K$. The original operator is already strongly monotone; the transformation exposes a convex optimization representation.
- Sign equivalence on a rectangular domain preserves the *set* of VI solutions. Potential symmetry alone does not make every stationary point a global optimum; curvature is needed.
- The production-network derivation follows the supplied paper, pp. 18–19, equations (9)–(14). On p. 18, equation (9) prints the normalization factor $\zeta_i$ with $\alpha_i^{+\alpha_i}$, but deriving the unit-cost expression in equation (13) requires $\alpha_i^{-\alpha_i}$. The presentation uses normalized technology consistent with equation (13), rather than reproducing that erroneous factor literally.
- The production-network normalization $\sum_j a_{ij}=1-\alpha_i$ is an additional normalization of technology weights. Constant returns to scale alone does not imply it. For general CES substitution, $a_{ij}$ are technology weights, while $W_{ij}(x)$ are the actual intermediate-input shares in total cost. They coincide in the Cobb–Douglas limit.
- The production-network contraction establishes existence and uniqueness of the positive **price subsystem conditional on the wage**. A claim about a full general equilibrium, including quantities, requires demand and market-clearing conditions beyond these slides.
- The reciprocal two-industry example is a teaching specialization with one supplier per firm. It has no substitution margin. Its log equations are exactly linear, while the general CES log system remains nonlinear. The comparison $0.5$ versus $0.397$ separates the direct productivity effect from input-price feedback.
- The production application in the paper uses a strong-$P$ argument. The main slides give a contraction argument from the same globally bounded cost-share derivatives. The contraction gives existence as well as uniqueness on $\mathbb R^n$; the pointwise $P$-matrix test alone should not be presented as an existence theorem.
- In the CES complementarity model, the log-transformed matrix gives uniqueness, while a separate Perron argument gives existence below the threshold. Its bounded best-response iteration is part of that existence proof, not a general dynamic-stability result.
- In the strategic-substitutes model, the displayed spectral bound is sufficient, not necessary. The complete-network result is a concrete example where strict convexity of costs yields uniqueness at the boundary of that bound.
