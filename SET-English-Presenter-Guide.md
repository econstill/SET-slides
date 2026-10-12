# SET: application-focused seminar guide

This guide follows the 50-page PDF: 41 main slides including the title, eight optional backup slides, and references. The paper is Yves Zenou and Junjie Zhou, *SET* (February 17, 2026 version). Slide 3 uses the paper's original Figure 1. Slides 4–6 follow its full route with Example 1, a two-player game with positive payoff scaling. Slides 7–9 add Example 2, a nonlinear two-player game whose transformed conditions yield a convex minimization potential. Slides 13–21 explain oligopoly pricing from consumer demand and firms' incentives through the markup-gap transformation, the uniqueness argument, and a two-firm logit example with price floors and caps. These speaking cues are kept only in this separate guide, not in `main.tex` or the slide PDF.

## Speaking route

| Slides | Focus | Suggested route |
|---|---|---:|
| 1–12 | Question, Figure 1, Examples 1 and 2, and the one result needed for applications | 20 min |
| 13–21 | Oligopoly: consumer choice, markup gaps, uniqueness, and binding price bounds | 18 min |
| 22–23 | Other existing applications: peers and network games | 2 min |
| 24–33 | New CES complementarity model, centrality, key players | 24 min |
| 34–39 | New public-good model with strategic substitutes | 14 min |
| 40–41 | Synthesis and discussion | 4 min |

Allow about six minutes each for Example 1 and Example 2: two minutes per page. Give the nine-page oligopoly sequence about 18 minutes, including time to distinguish marginal profit from the markup gap and read the price-bound table. The planned route totals 82 minutes, or about 85 minutes with short pauses. This leaves five to eight minutes for questions in a 90-minute seminar. The backup slides remain optional and replace other discussion time rather than extending the talk beyond 90 minutes.

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
| 13 | Introduce differentiated products, constant unit costs, own and rival prices, and the fixed outside option. State the firm's profit maximization problem on its price interval. Ask whether several price vectors can make every firm content with its own price. |
| 14 | Derive demand from consumers choosing the highest random utility. Interpret the outside option as not buying from any firm. Independent standard extreme-value taste shocks give the displayed logit demand with a unit price coefficient; the paper's uniqueness argument covers a broader demand class. |
| 15 | Differentiate profit into revenue per retained customer and lost customers. At an interior optimum, actual markup equals $\mu_i=Q_i/(-\partial_iQ_i)$, the inverse own-price semi-elasticity. Explain this quantity before using it in the transformation. |
| 16 | Divide negative marginal profit by $-\partial_iQ_i>0$. The transformed residual is actual markup minus desired markup. Negative residual means the firm wants to raise price; positive means it wants to cut price. This is a new representation of a marginal condition, not a new profit function. |
| 17 | Read all three rows of the boundary table. A cap can bind when marginal profit is positive; a floor can bind when marginal profit is negative. Positive scaling preserves these signs as well as interior zeros. The rectangular price set gives equality of the full VI solution sets. |
| 18 | Explain E1 as an own-price semi-elasticity that weakly increases with own price, E2 as a desired markup that weakly increases with a rival's price, and E3 as dependence on relative prices. E2 includes the outside option, which is fixed during strategic play but included when checking the demand restrictions. |
| 19 | Explain positive diagonal, nonpositive cross effects, and strict row diagonal dominance of the markup-gap derivative. These imply the $P$-property and at most one equilibrium. Finite price intervals add a separate existence argument using continuity and own-price quasi-concavity. Backup page 42 gives the derivative proof. |
| 20 | Work through two identical logit firms with zero costs and deterministic product appeal, and normalized outside utility. In the common price box $[0,4]^2$, a symmetric interior solution satisfies $p=(1+2e^{-p})/(1+e^{-p})$. It is approximately $1.226751$, with demand $0.184838$ per firm. Its existence and the global uniqueness result rule out asymmetric equilibria too. |
| 21 | Keep the market fixed and compare the common boxes $[0,4]$, $[0,1]$, and $[1.5,4]$. The cap gives prices $(1,1)$ and gap $-0.268941$; the floor gives $(1.5,1.5)$ and gap $+0.317574$. Bounds change prices, but the same sign-preserving uniqueness argument covers all three cases. |
| 22 | Nonlinear social norms need not be average peer effort. The uniqueness conclusion here is conditional on existence. |
| 23 | Briefly connect the potential route to income-based public goods and to interactions across multiple network layers. |
| 24 | Introduce the paper's new CES complementarity game. Its adjacency matrix is unnormalized, unlike the social norm on slide 22. |
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

## Oligopoly speaking script

This nine-page sequence follows the paper's Section 3.3, pp. 21–23. The derivative argument is in the appendix, p. 46. The two-firm numerical calculations are teaching examples added for this seminar, not calculations reported in the paper. Each script is designed for roughly two minutes, including reading the displayed equation and a short pause.

### Slide 13: Oligopoly: what price should each firm charge?

We now turn to a familiar decision: a firm choosing its price. There are several firms, and each sells a differentiated product. Consumers do not regard the products as identical, so one firm can charge more than another and still attract some customers.

Firm i has a constant unit cost c_i. Its price minus its cost is the markup earned on each unit sold. Multiplying that markup by demand gives profit. Demand depends on all firms' prices: increasing my price generally loses customers, while increasing a rival's price may make my product more attractive.

A consumer can also choose the outside option, meaning not buying from any of these firms. Its attractiveness matters for how much pricing power firms have. We hold the outside option's price fixed during the game.

Each firm chooses a price within an interval. The lower endpoint is a price floor and the upper endpoint is a cap. The lower endpoint is at least unit cost, so feasible prices never require selling below cost.

At equilibrium, every firm's price must be a best response to the prices charged by its rivals. The question is whether this mutual consistency can occur at several different price vectors. We want an argument that also works when some firms are constrained by a floor or cap.

### Slide 14: Where demand comes from

To understand the demand function, think first about one consumer. The utility from product i has three parts: its appeal v_i, minus its price p_i, plus a taste shock epsilon_i. Different consumers have different shocks, so two people facing the same prices need not choose the same product.

A consumer buys whichever option gives the highest utility, including option zero. Once we aggregate across consumers, the probability that product i wins becomes its demand share. We normalize the total mass of consumers to one, so a share of 0.2 means the firm serves twenty percent of consumers.

The logit formula on the slide comes from independent standard extreme-value taste shocks. We have normalized the coefficient on price and the scale of these shocks to one. In the numerator, a product's appeal raises demand and its own price lowers demand. In the denominator, every rival product competes for the same consumers. The outside option also appears there, even though no strategic firm chooses its price.

This formula is our running example, not a restriction of the paper's entire result. The general uniqueness argument uses three properties of demand that we will state shortly. For now, remember the economic origin: consumers compare all options, and their choices generate an interdependent system of firm demands.

### Slide 15: An optimal price balances two effects

Hold the rivals' prices fixed and increase firm i's price by a small amount. There are two effects on profit. First, the firm earns a little more from every customer it retains. This contributes the positive term Q_i. Second, some customers switch to other options. The firm loses its current markup on each of those lost sales. This is the negative term involving the demand derivative.

An interior optimum balances these effects. Rearranging the zero marginal-profit condition says that the actual markup, price minus cost, equals Q_i divided by the absolute value of the own-price demand derivative.

Call this second expression mu_i, the demand-implied or desired markup. It describes the markup at which the two marginal effects balance, evaluated at the current full price vector. It is not necessarily a best-response price formula: demand, and therefore mu_i, also depends on the firm's own price.

The ratio is the inverse own-price semi-elasticity. The semi-elasticity measures the proportional loss of customers from a one-unit increase in price. A small proportional loss supports a large markup. A large proportional loss supports a small markup.

This interpretation gives us a useful object to compare: the markup the firm currently charges versus the markup justified by its demand sensitivity. Rivals' prices influence that comparison through demand.

### Slide 16: SET: rewrite pricing as a markup gap

The original variational inequality uses negative marginal profit. The minus sign is our convention: the VI operator points in the direction of an excessive choice rather than a profitable increase.

Now divide this negative marginal profit by the positive number minus the own-price demand derivative. Dividing by a positive number does not change whether a component is positive, zero, or negative. It does, however, remove a demand-slope factor from the expression.

The resulting operator is especially easy to read: actual markup minus desired markup. If the actual markup is smaller than the desired markup, the gap is negative. Marginal profit is then positive, so the firm would like to raise its price. If the actual markup is larger, the gap is positive and the firm would like to cut its price. A zero gap means the two marginal effects balance.

This is the SET step. We are not changing consumers, costs, profits, or feasible prices. We are also not claiming that the transformed expression is a new profit function. We have rewritten the same marginal incentives using a more interpretable residual.

At interior prices, both operators vanish at exactly the same points. But that is only part of the gain. Their signs agree everywhere, and the next slide shows why those signs are essential when prices cannot move freely.

### Slide 17: Price floors and caps: signs, not just zeros

Read the table one row at a time. At an interior price, the firm can raise or lower its price a little. Neither move can be profitable at an optimum, so marginal profit must be zero. The markup gap is therefore zero too.

At a price cap, the firm cannot increase its price. It may still want to do so: marginal profit can be positive. What matters is that a feasible price reduction is not profitable. With our negative-marginal-profit convention, this corresponds to a nonpositive markup gap.

At a price floor, the directions reverse. The firm cannot cut its price. Marginal profit can be negative, indicating that it would prefer a lower price, but that move is forbidden. The markup gap is then nonnegative.

Why are these first-order signs sufficient, not merely necessary? Under own-price log-concavity of demand and prices at least as large as cost, profits are own-price quasi-concave. Equivalently, the marginal pricing incentive has the appropriate single-crossing structure. We do not need to claim that profit itself is concave.

The feasible price set is a product of intervals. On this rectangular set, preserving every component's sign preserves the entire VI solution set. Thus SET keeps interior equilibria and constrained equilibria. Simply solving the zero-gap equations would miss the binding-bound cases.

### Slide 18: The demand restrictions behind uniqueness

The paper imposes three restrictions. We write log demand as ell_i so that the derivatives have a natural interpretation in proportional terms.

E1 says log demand is concave in the firm's own price. The own-price semi-elasticity is minus the own derivative of log demand. Thus this semi-elasticity weakly increases as the firm raises its own price. Higher prices do not make demand proportionally less sensitive to another increase.

E2 is a cross-price restriction on log demand. When a rival raises its price, firm i's own-price semi-elasticity weakly decreases. Consequently its demand-implied markup weakly increases. This helps describe how firms' pricing incentives interact. The restriction also includes the outside option.

E3 says that adding the same amount to every option's price leaves demand unchanged. Consumers compare relative utilities, so a common price shift subtracts the same amount from every option's utility and does not change their ranking.

There is an important distinction here. The outside option's price is fixed during the strategic game. Nevertheless, it must be included when checking the hypothetical common shift in E3 and the cross-price restriction in E2. Its derivative is what will make the row-sum argument work.

Our logit demand satisfies all three. Backup page 43 verifies this directly. These are substantive demand assumptions; the transformation does not make uniqueness hold for arbitrary demand systems.

### Slide 19: Why the transformed pricing system is unique

Look at how the markup gap changes when prices change. Its own-price derivative is at least one. Economically, raising the firm's price directly increases its actual markup, while E1 ensures that its desired markup does not rise with its own price.

A rival's price has a nonpositive effect on the gap. Under E2, a rival's higher price raises the desired markup, reducing actual markup minus desired markup.

The crucial extra fact is that the own-price effect exceeds the combined magnitudes of all rival-price effects. E3, together with E2 for the outside option, gives a row margin of at least one. So these cross effects cannot collectively overwhelm the own effect. Backup page 42 derives this inequality.

A derivative matrix with positive diagonal, nonpositive off-diagonal entries, and this strict row dominance has the required P-structure. This gives at most one solution of the transformed VI. Since SET preserves the entire solution set, the original pricing game also has at most one equilibrium, including equilibria on the boundary.

Existence is a different question. With finite closed price intervals, continuous profits and own-price quasi-concavity provide existence through a standard fixed-point argument. Combining the two arguments gives a unique equilibrium on those boxes. On unbounded intervals, we must check existence separately.

### Slide 20: A two-firm logit example: solve for prices

Now make all of this concrete. Take two identical firms, both with zero unit cost and zero deterministic product appeal. Normalize the outside option's deterministic utility to zero. Their demands are the simple logit shares shown on the slide.

Differentiating firm i's share with respect to its own price gives minus Q_i times one minus Q_i. Substitute that into the desired-markup formula. The Q_i cancels, leaving one divided by one minus Q_i. The markup gap is therefore price minus this expression.

First let both firms choose within zero and four. Search for a symmetric interior solution with a common price p. Substituting the common demand share into the zero-gap condition gives the scalar equation on the slide. Numerically, its solution is approximately 1.227. Each firm serves approximately 18.5 percent of consumers; the remaining 63 percent choose the outside option.

The price lies strictly between the bounds, and the gap is zero for both firms, so this is an equilibrium under the own-price optimality conditions. We have explicitly demonstrated existence rather than assuming it.

Searching symmetrically alone would not rule out asymmetric equilibria. That is where the global uniqueness result matters: because this feasible equilibrium exists and there is at most one equilibrium in the box, there cannot be another symmetric or asymmetric one.

### Slide 21: The same market with price floors or caps

Keep every economic primitive unchanged: the same two firms, costs, consumers, and outside option. Change only the common feasible price interval.

The first row is our previous equilibrium. In the interval zero to four, both firms choose approximately 1.227 and the markup gaps are zero.

Now lower the upper bound to one. Evaluate the gap at prices one and one. It is approximately minus 0.269 for each firm. A negative gap means positive marginal profit: both firms would like to increase price, but they are already at the cap. The cap signs in our earlier table are satisfied, so one and one is the constrained equilibrium.

Finally, impose a floor of 1.5 and keep the upper bound at four. At prices 1.5 and 1.5, the gap is approximately plus 0.318. Each firm would like to cut price, but the floor prevents it. This is the floor-bound equilibrium.

These examples show why preserving only zeros would be inadequate: neither constrained equilibrium solves the zero-gap equations. Preserving signs keeps all three equilibria in their respective feasible sets.

The bounds are economically important because they change the outcome. The conclusion is not that constraints are irrelevant. It is that the same SET and P-property argument establishes uniqueness in each of these differently constrained games. We have now followed the paper's map from an economic model to a VI, to SET, and finally to a uniqueness result.

## Optional backup pages

Slide 42 derives the oligopoly markup-gap Jacobian, differentiates common-price-shift invariance, and shows strict row diagonal dominance and the $P$-property. Slide 43 verifies E1–E3 for logit demand and shows why applying the $P$-matrix test directly to the original negative marginal-profit operator can fail: with two identical firms at prices $(4,4)$ and zero costs and deterministic appeal, its diagonal derivatives are negative. This is a failure of a sufficient matrix condition at that profile, not evidence of multiple equilibria. The backup also distinguishes log-profit concavity from profit concavity. Slides 44–49 contain the coordinate proof, a matrix example, the nonlinear Perron limit, an algebraic-versus-economic-solution example, complete-network uniqueness beyond the sufficient spectral bound, and a star-network ranking argument. Slide 50 has references. Use a backup only in response to a relevant question.

## Terminology and precision

- The paper's Figure 1 is a map from a game to a variational inequality and then to a transformed variational inequality. It is not itself a picture of a fixed-point theorem.
- In Example 1, $\Phi$ is the convex minimization potential. Its negative is the exact payoff potential for the rescaled game $(u_1,u_2/4)$. The original game has a weighted potential. The example illustrates equilibrium-preserving representation, not a stronger uniqueness bound.
- In Example 2, the increasing exponential preserves the sign of the second VI comparison. The resulting $\Phi$ is a convex minimization potential for the transformed VI, not an exact payoff potential for the original game. Strong convexity and coercivity give existence and uniqueness of the minimizer on $K$. The original operator is already strongly monotone; the transformation exposes a convex optimization representation.
- Sign equivalence on a rectangular domain preserves the *set* of VI solutions. Potential symmetry alone does not make every stationary point a global optimum; curvature is needed.
- The oligopoly sequence follows the supplied paper, Section 3.3, pp. 21–23, equations (20)–(21), with the derivative proof on p. 46. The two-firm calculations and comparison of the common price boxes $[0,4]$, $[0,1]$, and $[1.5,4]$ are illustrative teaching examples, not numerical results reported in the paper.
- In the oligopoly model, $Q_i$ denotes demand; with unit consumer mass it is also a market share. The displayed logit example normalizes the price coefficient and the extreme-value shock scale to one. The outside option's price is fixed during strategic play, but included when differentiating common-price-shift invariance and checking E2.
- The desired markup $\mu_i=Q_i/(-\partial_iQ_i)$ is the inverse own-price semi-elasticity, not the inverse price elasticity. It depends on the full price vector, including the firm's own price, and is not by itself an explicit best-response price function.
- The oligopoly transformation divides $F_i=-\partial_i\pi_i$ by $-\partial_iQ_i>0$. Its residual $\widetilde F_i=p_i-c_i-\mu_i$ has the same sign as $F_i$ and the opposite sign to marginal profit. It represents the same pricing incentives; it is not a transformed profit function or a claim that the general game has a potential.
- Own-price log-concavity of demand does not imply concavity of profit. For $p_i>c_i$, $\log\pi_i=\log(p_i-c_i)+\log Q_i$ is concave in own price, so profit is quasi-concave. The first-order boundary signs are sufficient on the price interval; the point $p_i=c_i$ can be treated directly using positive demand. A separate fixed-point argument gives existence on finite compact price boxes. The $P$-property argument itself establishes at most one equilibrium, not existence on arbitrary unbounded intervals.
- For the oligopoly proof, E2 must cover cross effects involving the outside option $j=0$ as well as strategic rivals. With $\ell_i=\log Q_i$, E3 gives $\sum_{j=1}^n\ell_{i,ij}=-\ell_{i,i0}\le0$, and hence $\sum_jJ_{ij}=1+\ell_{i,i0}/\ell_{i,i}^2\ge1$. Combined with $J_{ij}\le0$ off the diagonal, this gives strict row diagonal dominance. It is a structural statement about the transformed derivative, not an assertion that original marginal profits share that structure.
- In the CES complementarity model, the log-transformed matrix gives uniqueness, while a separate Perron argument gives existence below the threshold. Its bounded best-response iteration is part of that existence proof, not a general dynamic-stability result.
- In the strategic-substitutes model, the displayed spectral bound is sufficient, not necessary. The complete-network result is a concrete example where strict convexity of costs yields uniqueness at the boundary of that bound.
