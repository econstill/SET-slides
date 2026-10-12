# SET: close-reading discussion guide

This English guide follows the 65-page PDF: 60 main pages including the
cover, four optional technical backup pages, and references on page 65.
All page numbers below are physical PDF pages, not Beamer footer numbers.
The source is Yves Zenou and Junjie Zhou, *SET*, February 17, 2026 version.
Figure 1 on page 3 is the paper's original diagram. Speaking cues are kept
only in this separate guide, not in `main.tex` or the slide PDF.

The format is a 1–2 hour literature-reading discussion. Follow each model
through **hypotheses → transformation → proof → economic implication**.
Stop at a condition or inequality when the group wants to understand it.
The proof pages are part of the main discussion; an equation appearing on a
slide is an invitation to work through it, not an instruction to read it aloud
and move on.

## Flexible reading routes

### Full route: approximately 105–120 minutes, including discussion

| PDF pages | Reading block | Flexible allocation |
|---|---|---:|
| 1–10 | Motivation, map, and both worked examples | 15 min |
| 11–16 | VI, sign equivalence, rectangularity, and the uniqueness argument | 15–20 min |
| 17–31 | Oligopoly model, demand assumptions, proof, existence, and logit checks | 30–35 min |
| 32–33 | Connections to other existing applications | 2 min |
| 34–48 | CES complements, threshold, centrality, and intervention | 20–23 min |
| 49–58 | Public goods, inverse domain, potential, and economic results | 18–20 min |
| 59–60 | Synthesis and final questions | 5 min |

These allocations include questions taken within each block. They are a
planning aid, not a ceiling on the oligopoly discussion or a requirement to
give every page equal time. If participants want to derive every intermediate
step at the board, spend longer on that module and postpone another module
or continue in a second meeting. The entire deck remains available for that
purpose. Technical backup pages can replace a planned illustration when a
specific question arises.

### Focused route: approximately 60 minutes

Use roughly 10 minutes for the map and two examples, 15 for methodology,
25 for the oligopoly reading, five for selected network conclusions, and
five for synthesis and questions. Within oligopoly, prioritize the markup
gap, boundary signs, strict log-profit concavity, the roles of E1–E3, and
the demonstration on page 31 of why SET helps the matrix test.
On page 26 explain the maximum-coordinate idea; a line-by-line integral
proof can be reserved for the longer route. Use pages 38, 42–43, 55–56,
and 60 for selected network conclusions. Do not present pages 34–58 as if
all of their proofs have been covered in this shorter session.

For either route, ask four questions before leaving a model: What is the
equilibrium problem? What is preserved? Which assumptions make the new
representation useful? Which economic conclusion follows, and which does
not?

## Paper-page reading map

These are page numbers in the supplied paper. The numerical logit price
comparison, two-player walkthroughs, coupled-constraint illustration, path
curves, and two-node algebraic calculation are seminar teaching examples.

| Deck pages | Primary reading | What to locate in the paper |
|---|---|---|
| 2–3, 10–16 | Section 2, pp. 7–16; Figure 1, p. 17 | Lemma 1; Definition 2; Theorems 1–2; SET 1–2; Lemmas 2–3 |
| 4–6, 62 | Section 2.3.2, pp. 15–16 | Why positive payoff rescaling should not change equilibrium but can change a direct matrix test |
| 7–9 | Section 2.2, p. 12; potential discussion, p. 14 | Increasing transformations of both sides and integrability; the displayed nonlinear game is an added example |
| 17–31 | Section 3.3, pp. 21–23, equations (20)–(21); appendix, p. 46 | E1–E3, price restrictions, positive rescaling, and the row-dominance proof |
| 32 | Section 3.2, pp. 19–21 | Row-normalized CES social norms and uniqueness conditional on existence |
| 33 | Sections 3.4–3.5, pp. 23–31 | Inverse functions, symmetric transformed systems, and potential methods |
| 34–46, 63 | Section 4.1, pp. 32–34; appendix, pp. 47–49 | Theorem 4: separate uniqueness, existence, non-existence, and Perron-limit arguments |
| 47–48 | Section 4.1, pp. 35–37 | Bridge network, key-player definition and numerical comparison; reported switch near beta 0.722 |
| 49–58, 64 | Section 4.2, pp. 38–41; appendix, pp. 50–52 | Assumptions 2–3, Theorem 5, Proposition 7, and neighborhood rankings |

The inverse-domain box on page 52 makes explicit a range check needed when
using the inverse marginal benefit in Section 4.2. The minimization potential
used in the deck has the opposite sign to a maximization potential; its
gradient and Hessian are kept consistent throughout.

## Page-by-page cues

| PDF page | What to say or check |
|---:|---|
| 1 | Introduce the paper and the reading-group format. The aim is to understand the method and its assumptions, not only to list conclusions. |
| 2 | The difficulty may lie in the representation of equilibrium conditions. The question is whether one can change that representation without changing equilibrium. |
| 3 | Read the original Figure 1 from left to right: game, VI, SET VI, then a matrix or potential route. Equilibrium is also a best-response fixed point; that is not the particular route drawn here. |
| 4 | Derive the two best responses using strict own-action concavity. A factor of four changes player 2's payoff units, not its best response. |
| 5 | Form negative marginal payoffs, then divide the second component by four. Explain why a rectangular domain preserves boundary solutions as well as zeros. |
| 6 | Check the three positive principal minors and both positive eigenvalues. Integrate the transformed operator to obtain the convex minimization potential. The feasible zero (2,2) proves existence; the matrix or curvature argument proves uniqueness. |
| 7 | Derive both distinct nonlinear best responses. They are positive at every feasible rival action, so equilibria are interior. |
| 8 | Apply the exponential to both sides of the second comparison. Its strict increase preserves signs, while making the two cross derivatives equal. This is more than simply multiplying payoff units. |
| 9 | Differentiate the displayed potential and check its uniformly positive-definite Hessian. Strong convexity and coercivity give a unique minimizer. The original operator already has a uniqueness certificate; the gain here is a convex optimization representation. |
| 10 | State the common reading sequence for the three applications: identify hypotheses, construct SET, prove the needed structure, then interpret the economic conclusion. |
| 11 | Start from each player's first-order inequality under own-action concavity. Sum to get the VI; vary one coordinate at a time for the converse. |
| 12 | Read the lower-bound, interior, and upper-bound signs. The independence of coordinate deviations is the reason this table characterizes the VI. |
| 13 | Explain positive profile-dependent rescaling and an increasing transformation of both sides. Logs need positive arguments; inverses need valid ranges. |
| 14 | Compute both linear objectives on the triangle. The first is minimized along the top edge, the second only at (1,0). Same signs do not preserve arbitrary coupled-constraint VIs. |
| 15 | Work through the contradiction from two VI solutions. A global P-condition ensures that at least one coordinate product is positive; coordinate optimality makes every such product nonpositive. |
| 16 | Define a P-matrix by positive principal minors, and distinguish this Jacobian certificate from the global inequality on page 15. For a potential, symmetry gives integrability; convexity is an additional condition. Existence remains separate. |
| 17 | Explain differentiated products, costs, price intervals, rival prices, and the fixed outside option. The question concerns mutually optimal prices, including constrained prices. |
| 18 | Derive demand conceptually from consumer choice. Logit is a running example with unit price coefficient and shock scale, not the full scope of the result. |
| 19 | Differentiate profit into retained-customer revenue and lost-customer effects. Define the desired markup before discussing uniqueness. It is an inverse semi-elasticity, not an inverse elasticity. |
| 20 | Divide by the positive absolute own-price demand slope. The resulting markup gap has the same sign as negative marginal profit, hence the opposite sign to a profitable price increase. |
| 21 | At a cap, positive marginal profit can be optimal; at a floor, negative marginal profit can be optimal. Sign preservation retains these outcomes. First-order sufficiency is justified on page 23. |
| 22 | State E1–E3 precisely. Include option 0 in E2 and in the hypothetical common shift in E3, while holding its price fixed during strategic play. |
| 23 | Differentiate log-profit twice. E1 plus the strictly concave log-markup term gives strict log-profit concavity for prices above cost. Treat the cost-price endpoint directly using positive marginal profit. |
| 24 | Differentiate the desired markup. E1 controls its own-price slope; E2 controls its rival- and outside-price slopes. Translate these into the diagonal and cross entries of the markup-gap Jacobian. |
| 25 | Differentiate common-price-shift invariance for the desired markup. Sum only the strategic columns of the Jacobian, leaving the outside-option term. This gives the strict row-dominance margin. |
| 26 | Pick the largest absolute coordinate of the difference between two price vectors. Integrate the Jacobian along their segment; row dominance makes the selected coordinate product strictly positive. Connect this to page 15. |
| 27 | Keep the two arguments separate: the global P-condition rules out two equilibria; unique continuous best responses and Brouwer give existence on finite compact price boxes. |
| 28 | Verify logit E1 and E2 directly and E3 by cancelling a common exponential factor. The general proof used these properties, not the logit formula itself. |
| 29 | Solve the symmetric scalar equation. The feasible zero-gap solution proves existence; the global result rules out asymmetric equilibria too. |
| 30 | Compare zero-gap interior pricing with negative-gap cap pricing and positive-gap floor pricing. Bounds change the economic outcome, while the same uniqueness argument applies in each box. |
| 31 | The original pricing derivative has a negative diagonal entry at (4,4), so it fails the global P-matrix test on the box. The transformed derivative passes throughout that same box. This concretely shows what SET changes; failure of the original sufficient test does not show multiple equilibria. |
| 32 | A nonlinear social norm need not average peer effort. This model uses row-normalized links and a conditional uniqueness statement; do not import existence from SET alone. |
| 33 | Connect inverse Engel curves and multiplex interactions to the potential route. Symmetric transformed derivatives help; further curvature assumptions are still needed for uniqueness. |
| 34 | Introduce CES complements with an unnormalized adjacency matrix. Strict own-action concavity gives the best response. Positive baselines and a connected nonempty undirected network will matter in the proofs. |
| 35 | Compare two neighbors' marginal influence. Beta changes relative weighting and, with an unnormalized aggregator, scale too. Do not describe it as only a stronger spillover parameter. |
| 36 | Every equilibrium is positive, so log actions cover the entire equilibrium set. Separate the sign-preserving log comparison from the one-to-one change of variables. |
| 37 | Derive the two factors in W and sum each row. Positive baselines make the sum strictly below one. A uniform bound is available on the compact segment between two proposed roots, not necessarily on all log-action space. |
| 38 | State the spectral threshold, including non-existence at equality. The regular-network formula checks the theorem in a transparent special case. |
| 39 | Use the Perron vector to construct an upper bound with exactly the same network amplification direction. Explain why the denominator is positive only below the threshold, then bound increasing best-response iteration. |
| 40 | Raise the equilibrium equation componentwise to beta and take its positive Perron-weighted sum. Strictly positive baselines create a strict inequality, forcing delta below the threshold. |
| 41 | Monotonicity of best responses yields monotone comparative statics within the existence region. Use the equilibrium first-order condition to verify payoff equals one half of squared effort. |
| 42 | At beta=1, write the resolvent solution. The baseline b in (I−delta G)x=b is the vector a here. A unit baseline gives standard Katz–Bonacich centrality. |
| 43 | Expand the baseline in an orthonormal eigenbasis. Each eigen-direction has its own multiplier 1/(1−delta lambda_k). Near the threshold, the leading term dominates after normalization. |
| 44 | Explain why bounded actions would imply a forbidden equilibrium at the threshold. Connectedness propagates divergence. Normalize x to the beta power, take subsequences, and use uniqueness of the positive Perron direction. |
| 45 | State the limiting ratio. Actions diverge; there is no finite equilibrium at the critical parameter. It is x to the beta power, not generally x itself, that aligns with the Perron vector. |
| 46 | Read the path-network teaching plot at a common fraction of each beta-specific threshold. It compares ratios, not finite action levels at the right endpoint. |
| 47 | Define the key player by total equilibrium activity lost after removal and re-equilibration. This includes both the removed action and the response of survivors. |
| 48 | Identify the bridge and the high-degree types before reading the table. The reported nonlinear switch is near beta 0.722 for delta 0.1, within the paper's specified parameter range. |
| 49 | Introduce benefit from local total provision and private cost of own effort. State the marginal-crossing assumptions and autarky effort k*. |
| 50 | Distinguish an interior marginal equality from a zero-effort inequality. Strict concavity gives a unique continuous best response bounded by k*, so Brouwer establishes existence before any spectral condition. |
| 51 | Implicitly differentiate the best response. Linear costs give slope minus one when interior; positive cost curvature reduces crowding out locally. A bound on one scalar slope does not by itself prove network-wide uniqueness. |
| 52 | Check the range before applying an inverse. Construct B, ell=theta(B), and the equilibrium-containing box. Explain why original and restricted games have identical best responses on this box and hence the same equilibrium set. |
| 53 | Verify the signs with b' strictly decreasing. The transformed cross derivatives equal delta g_ij and are symmetric. Differentiate the potential to check its sign convention. |
| 54 | Differentiate the inverse, then apply the Rayleigh lower bound. The displayed spectral inequality is sufficient, not necessary; cost curvature contributes an extra nonnegative diagonal term. |
| 55 | At zero effort and zero marginal cost, the marginal benefit is strictly positive at every finite profile. Every equilibrium is interior, independently of uniqueness. |
| 56 | On a complete graph, every player faces the same total provision. Strictly increasing marginal cost forces equal effort and a unique scalar solution; linear costs allow every allocation with the same total. |
| 57 | State the homogeneous-functions, zero-initial-marginal-cost, strict-convexity, and delta=1 assumptions before the ranking result. Neighborhood inclusion supports the ranking; degree alone does not on arbitrary graphs. |
| 58 | First show that all leaves have the same best response. Compare the hub's and a leaf's marginal benefits, using positive leaf effort and n at least three. Strictly increasing marginal cost gives the strict effort ranking. |
| 59 | Classify each proof by its purpose: preserving equilibrium, proving existence, or proving uniqueness. A valid transformation is not a substitute for the latter two arguments. |
| 60 | Summarize the economic payoffs: nonlinear centrality and intervention under complements, and participation and rankings under substitutes. Ask which structural feature made the chosen transformation useful. |
| 61 | Give the full coordinate proof of equilibrium-set preservation when someone wants more than the endpoint table. |
| 62 | Compare the P-matrix and symmetric-part monotonicity tests under arbitrary positive payoff scaling. The latter can impose a stricter parameter bound even though best responses do not change. |
| 63 | A unique algebraic solution can be negative and economically infeasible. Matrix invertibility is not the same as a nonnegative equilibrium in the network game. |
| 64 | Prove complete-network uniqueness directly from equal marginal costs and a strictly decreasing scalar equation. This works when the simple strict spectral bound is at equality. |
| 65 | Identify the source paper and the two benchmark network-game references. Distinguish added seminar examples from the paper's reported figures and results. |

## Methodology speaking notes

### Pages 11–12: optimality, the VI, and signs

Fix the other players' actions. With a differentiable payoff concave in own
action, a feasible action is optimal exactly when every feasible directional
derivative is nonpositive. We put a minus sign in front of marginal payoff,
so the same statement becomes the coordinate inequality on page 11.

Sum these inequalities to get the VI. To reverse the argument, choose a
test vector that differs from the candidate equilibrium in only one
coordinate. This test vector is feasible because the domain is a product
of individual intervals. The VI then recovers that player's optimality
condition. Concavity is doing substantive work: necessary first-order
conditions are now sufficient.

On an interval, only three cases remain. At the lower bound the operator
must be nonnegative; in the interior it must vanish; at the upper bound it
must be nonpositive. Coordinatewise signs therefore encode the entire
solution set on a rectangle. This statement allows binding constraints;
it is stronger than saying that two systems have the same zeros.

### Pages 13–14: constructions and the domain restriction

Multiplying a component by a positive function preserves its sign even
when that function depends on every player's action. Alternatively, an
increasing transformation preserves the ordering of two expressions. If
the original component compares A with B, applying the same increasing
function to A and B preserves the direction of the comparison. Example 2
uses an exponential; later we use logarithms and inverse functions. Their
domains must be checked before applying them.

Now consider the triangle on page 14. For a constant operator, the VI is
the first-order condition for minimizing a linear objective. The first
objective is minus total activity: every point using the whole shared
resource is optimal. The transformed objective values activity in the
first coordinate twice as much and uniquely selects (1,0). Although both
components remain negative, the magnitudes matter under a shared
constraint. One cannot vary each coordinate independently as in the
rectangle proof. This is a coupled-constraint VI illustration, not the
strategy set of the preceding ordinary two-player game.

### Pages 15–16: the uniqueness proof and its certificates

The global P-condition says that for any two distinct profiles, at least
one coordinate changes in the same strict direction as that coordinate's
operator value. Suppose there were two VI solutions. Testing each against
the other's coordinate gives two inequalities. Subtracting them shows
that none of the coordinate products can be positive, contradicting the
P-condition. That is why the condition controls constrained solutions,
not merely zeros.

A P-matrix is a matrix whose principal minors are all positive. The paper
uses this condition on the transformed Jacobian throughout a rectangular
domain as a uniqueness certificate. Keep that pointwise Jacobian statement
distinct from the global condition just proved useful. In oligopoly we
establish the global condition directly from row diagonal dominance;
we do not assume that averaging arbitrary P-matrices preserves the
P-matrix property.

The other route is integrability: symmetry of the transformed Jacobian
can reveal a potential. To turn stationary conditions into a unique
minimization problem, one also needs convexity and an existence argument.
Neither SET nor symmetry alone guarantees that a solution exists.

## Oligopoly speaking script

Pages 17–31 follow Section 3.3, pp. 21–23, with the appendix argument on
p. 46. Work through the assumptions and proof at the group's pace.
There is no fixed time limit for this application. The numerical logit
price boxes are teaching examples, not numerical results reported by the
paper.

### Page 17: the economic problem

Each firm sells a differentiated product, so a higher price need not lose
every customer. Price minus constant unit cost is the markup per sale;
markup times demand is profit. Demand depends on all strategic prices and
on the outside option, which represents not buying from these firms.

The outside price is held fixed during the game. Each firm chooses within
its own interval, with the lower endpoint at least its unit cost. These
separate intervals make the joint feasible set rectangular. Ask whether
several price vectors can make every firm's choice optimal, including
when a price floor or cap binds.

### Page 18: where demand comes from

A consumer compares product appeal minus price plus an individual taste
shock across every option, including option zero. Aggregating choices
gives each product's demand share. With unit consumer mass, its share is
also its quantity sold.

Independent standard extreme-value taste shocks give the displayed logit
formula. Its price coefficient and shock scale are normalized to one.
The numerator describes a product's own attractiveness; the denominator
includes every competing option. A higher own price loses customers to
rivals or the outside option. The paper's result is broader than logit;
we will identify the demand properties that its proof actually needs.

### Page 19: the pricing trade-off

Hold rivals' prices fixed and raise the firm's price a little. The firm
earns more on every customer it retains, creating the positive term Q_i.
It also loses customers and their current markups, creating the negative
demand-derivative term. An interior optimum balances the two.

The desired markup mu_i is Q_i divided by the absolute own-price demand
slope. It is the inverse semi-elasticity: the inverse proportional loss
of demand caused by a one-unit price increase. It is not the inverse
ordinary elasticity, which also scales by price. Importantly, mu_i depends
on the entire current price vector, including the firm's own price. The
markup equation is an implicit condition, not generally an explicit
best-response formula.

### Page 20: the SET step

Our original operator is negative marginal profit. Divide it by the
positive number minus the own-price demand derivative. This removes a
scale factor without changing a component's sign. The new expression is
actual markup minus desired markup.

If the gap is negative, marginal profit is positive and the firm would
like to raise its price. If the gap is positive, it would like to cut its
price. A zero gap balances the two effects. We have changed neither
demand, profit, cost, nor the feasible set. This is a new representation
of marginal incentives, not a new profit function or a claim that the
general pricing game has a potential.

### Page 21: why boundaries require signs

At an interior price both small directions are feasible, so marginal
profit must vanish. At a cap, the firm may still want to increase price:
marginal profit can be positive, while the markup gap is nonpositive.
At a floor, the firm may prefer a lower price: marginal profit can be
negative, while the gap is nonnegative.

Positive rescaling preserves all three cases. On the rectangular price
set, the original and transformed VIs therefore have exactly the same
solution set. Merely preserving zeros would miss constrained equilibria.
The next two pages identify and justify the demand assumptions under
which these first-order signs characterize genuine best responses.

### Page 22: E1–E3

E1 says log demand is concave in own price. Equivalently, own-price
semi-elasticity weakly increases with own price. E2 says the cross
derivative of log demand is nonnegative: higher prices of other options
weakly increase the desired markup. E2 must include the outside option.

E3 says adding the same amount to every option's price leaves choices
unchanged. It is common additive price-shift invariance, not multiplicative
degree-zero homogeneity. The outside price remains fixed during strategic
play, but is included in this hypothetical simultaneous shift. Logit
satisfies all three; arbitrary demand functions need not.

### Page 23: sufficiency, not just necessary conditions

For prices strictly above cost, profit is positive. Its logarithm is
the sum of log markup and log demand. The second derivative of log
markup is strictly negative; E1 makes the other term nonpositive.
Log-profit is therefore strictly concave in own price. Its derivative
has the same sign as the derivative of profit, so the interior or
endpoint derivative signs select the global best response.

Do not shorten this to the claim that profit itself is concave, or that
every differentiable quasi-concave function has sufficient first-order
conditions. Here strict log-concavity supplies the needed structure.
At a feasible price equal to cost, profit is zero and marginal profit
equals positive demand. A feasible higher price gives positive profit,
so that endpoint cannot be optimal.

### Page 24: E1 and E2 in the transformed derivative

Differentiate the inverse semi-elasticity mu_i. The squared denominator
is positive, so each derivative's sign is the sign of the corresponding
second derivative of log demand. E1 makes the own-price derivative of
the desired markup nonpositive. E2 makes every other-price derivative
nonnegative.

The gap is price minus cost minus desired markup. Its own derivative is
therefore at least one: actual markup rises directly, while desired
markup does not rise. Its cross derivatives are nonpositive: a rival's
higher price raises the desired markup and reduces the gap. These sign
restrictions alone are not yet the full uniqueness proof. We still need
to control their combined magnitudes.

### Page 25: E3 and the outside option

Common-shift invariance also holds for the desired markup. Differentiate
it with respect to the common shift: the sum of its derivatives across
all options is zero. In the strategic Jacobian we sum only the firms'
columns, leaving the outside-option derivative behind.

The row sum of the gap Jacobian is one plus this outside derivative,
which is nonnegative under E2. Because all strategic off-diagonal entries
are nonpositive, the row sum is also diagonal minus the sum of absolute
cross effects. It is at least one. This is exactly strict row diagonal
dominance. The outside option is not an additional strategic player;
its hypothetical derivative provides a bound on strategic feedback.

### Page 26: from local derivatives to a global proof

Take any two distinct feasible price vectors and their difference d.
Select a coordinate with the largest absolute difference. Along the
segment joining the vectors, the derivative matrix obeys the same row
dominance bound. Multiply the change in that coordinate's gap by its
price difference and express the change as an integral.

Every cross term can be bounded in absolute value by the selected
coordinate's squared difference times the absolute cross derivative.
The diagonal therefore dominates the sum of cross terms, leaving a
strictly positive coordinate product. This proves the global P-condition
from page 15. Two VI solutions are impossible, including boundary
solutions. The proof does not need compactness of the whole price domain;
finite bounds will be used separately for existence.

### Page 27: existence is a separate argument

We now have at most one equilibrium. To get exactly one on finite price
intervals, each firm must have a best response and those best responses
must be mutually consistent. Compact intervals and continuous profits
give a maximizer. The strict log-profit argument makes it unique. The
maximum theorem then makes this single-valued best response continuous.

The joint best-response map sends the compact convex price box into
itself. Brouwer gives a fixed point, which is a Nash equilibrium.
Combining existence with the uniqueness proof gives exactly one.
An unbounded price domain needs its own existence argument; the
finite-box Brouwer argument cannot simply be reused there.

### Page 28: check the running example

Differentiate logit log demand. The first own derivative is minus
(one minus the share); the second own derivative is minus Q_i times
one minus Q_i. This verifies E1. A cross second derivative is Q_i Q_j,
verifying E2 for each rival and the outside option.

When all prices rise by t, every exponential weight receives the same
factor exp(−t). It cancels in each share, verifying E3. These calculations
connect the abstract hypotheses to a familiar demand model. The general
proof did not require the explicit logit formula after the hypotheses
were established.

### Page 29: a feasible equilibrium and symmetry

Take two identical firms with zero costs and deterministic appeals,
and normalize outside utility to zero. Differentiating the share gives
minus Q_i times one minus Q_i. The desired markup simplifies to
1/(1−Q_i).

In the common price box [0,4], search for a symmetric interior solution.
The scalar equation gives p approximately 1.226751 and each firm serves
approximately 0.184838 of consumers. The rest select the outside option.
This feasible zero-gap profile is an equilibrium, demonstrating existence
directly. Symmetric search alone would not rule out asymmetric solutions;
the global uniqueness result rules them out.

### Page 30: the same market under different price bounds

Keep consumers, costs, and all demand primitives unchanged. In [0,1],
the markup gap at (1,1) is approximately −0.268941. Both firms would
prefer a higher price, but the cap binds. In [1.5,4], the gap at
(1.5,1.5) is approximately +0.317574. Both would prefer a lower price,
but the floor binds.

Neither constrained profile solves the zero-gap equations. Each solves
the relevant VI boundary signs, and each is the unique equilibrium in
its own price box. Constraints clearly matter for the outcome. SET
lets the same proof cover the different constrained problems without
mistaking a boundary optimum for an interior first-order condition.

### Page 31: why the transformation matters for the test

Could we have applied the same matrix test directly to negative marginal
profits? Evaluate that derivative in our running example at prices (4,4).
Each firm's share is about 0.017668. Its own diagonal derivative is
approximately −0.03226. A P-matrix requires every one-by-one principal
minor, including every diagonal entry, to be positive. The original
derivative therefore fails that global test on the feasible box [0,4]^2.

The transformed derivative satisfies the dominance certificate throughout
the same box. Yet the marginal-profit and markup-gap VIs have exactly
the same solution set. This is the representational gain: a useful
sufficient certificate can become visible after SET. Failure of the
original certificate did not mean multiple equilibria, just as passing
the transformed certificate did not change the game.

## Network-proof speaking notes

### Pages 36–40: conditional uniqueness versus existence

The log comparison preserves signs on positive quantities, and the log
change of variables is one-to-one. Every equilibrium is positive because
each baseline is positive. Thus no equilibrium is lost.

The derivative W on page 37 has nonnegative entries and row sums strictly
below one. This does not supply a single contraction constant below one
over all of log-action space. For two proposed finite roots, however,
their joining segment is compact. Continuity and the strict row bounds
give a common constant alpha below one on that segment, yielding the
contradiction in the infinity norm. This establishes at most one root
for any positive delta and beta, not existence for every such pair.

For existence below the spectral threshold, take the positive Perron
vector and its componentwise beta-th root. Its CES image has a known
scalar multiple. Scaling that vector by a sufficiently large M gives an
upper profile overline x with T(overline x) no larger than overline x.
Starting from a, monotone best-response iteration increases and stays
below this bound, so its limit is a fixed point. This bounded iteration
is an existence construction, not a general claim about adjustment
dynamics.

For necessity, an equilibrium obeys (x−a) to the beta power equals delta
to the beta power times G times x to the beta power. Positive a makes
the left vector strictly smaller than x to the beta power. A positive
Perron-weighted sum forces delta below the threshold, including a strict
exclusion of equality. Invertibility of a linear system above its
critical value would not rescue economic feasibility; page 63 illustrates
that distinction.

### Pages 42–45: eigenvalues, Bonacich, and the limiting direction

At beta one, the equilibrium equation is the linear resolvent response
(I−delta G) inverse times a. Expand a in the orthonormal eigenbasis of
the symmetric adjacency matrix. Each component is amplified by
1/(1−delta lambda_k). The leading positive eigen-direction becomes
dominant as delta approaches its admissible threshold from below.

The coefficient e-transpose-a records baseline heterogeneity in levels.
After normalization this scalar cancels, leaving the unit Perron vector.
This answers the connection between the system (I−delta G)x=b and the
eigenvector equation G e=lambda e: the centrality vector is generally a
combination of eigenvectors, not a single eigenvector, until its critical
normalized limit.

For general beta, normalize x to the beta power instead. Bounded actions
near the threshold would yield an equilibrium at the threshold by
continuity, which has been ruled out. Connectedness spreads divergence
to every node, making a_i/x_i negligible. Every normalized subsequence
must therefore solve the Perron eigenvector equation with unit sum.
The Perron direction is unique, so the full normalized vector converges.
Taking componentwise beta-th roots gives the limiting action ratios.
There is no finite equilibrium at the endpoint itself.

### Pages 50–54: best responses, inverse domains, and a potential

Strict own-action concavity gives a unique best response theta(t) to
neighbors' provision t. It is bounded by autarky effort k*. Its interior
slope follows by implicit differentiation; linear cost gives full local
crowding out, while positive cost curvature reduces its magnitude.
A scalar slope bound is not by itself a contraction of the whole
network map: how many neighbors enter, and with which weights, matters.

Before using h=(b') inverse composed with c', check its domain. Set
B=delta times maximum degree times k*, ell=theta(B), and K=[ell,k*]^n.
Against any profile in [0,k*]^n, neighbors supply at most B, so every
original best response lies in K. Every original equilibrium therefore
lies in K. Conversely, against rivals in K the unique original best
response still belongs to K; restricting choices to K cannot change it.
Thus the restricted and original games have exactly the same equilibrium
set, not merely one common candidate.

At ell, the interior or corner optimality condition ensures c'(ell)
exceeds the limiting marginal benefit at infinity. Throughout [ell,k*],
c' stays below b'(0), so its values lie inside the range of b'. The
inverse is finite there. If c'(0)=0, ell is positive; a finite inverse
value at zero is neither assumed nor needed.

On this valid box, decreasing b' preserves the sign between the original
negative marginal payoff and local provision minus h(x_i). Cross
derivatives become delta times the symmetric link matrix. Integrating
gives the deck's minimization potential Psi. Differentiate it to confirm
the sign. The inverse derivative h' is nonpositive, so minus h' adds
nonnegative diagonal curvature. The Rayleigh bound gives strict convexity
under 1+delta lambda_min(G)>0. Existence was already established; the
potential now supplies uniqueness. This spectral condition is sufficient,
not necessary.

### Pages 55–58: economic conclusions and their exact assumptions

With strictly convex costs and c'(0)=0, the marginal payoff at zero is
strictly positive at every finite profile. Every equilibrium is interior,
whether or not it is unique. At delta one on a complete graph, every
agent receives the same total provision. Equal marginal benefits force
equal marginal costs and hence equal efforts. A strictly decreasing
scalar equation gives the unique equilibrium. Linear costs instead allow
a continuum of allocations with the same total effort.

For the star, all leaves have the same unique best response to the hub.
Their common positive effort means the hub receives strictly more local
provision than a leaf. Its marginal benefit is lower, so its marginal
cost and own effort must be lower. This applies at every equilibrium and
does not require a uniqueness premise. Neighborhood inclusion yields
related rankings on nested-split graphs under the stated homogeneous
functions and delta-one assumptions; degree alone does not rank effort
on arbitrary networks.

## Discussion questions and short answers

1. **Does SET preserve only equilibria found in the interior?** On any
   domain, common zeros describe common interior VI solutions. On a
   rectangle, full sign equivalence also preserves boundary solutions.
   The triangle example shows why geometry matters for that stronger claim.
2. **Does SET preserve the original Jacobian or its eigenvalues?** No.
   Derivatives can change substantially under positive profile-dependent
   rescaling or nonlinear transformations. It is the VI solution set that
   is preserved under the stated conditions.
3. **Why not use injectivity alone?** It controls zeros, not all boundary
   VI solutions. On [0,1], the injective operator F(x)=1/2−x has three VI
   solutions: 0, 1/2, and 1. The global P-condition supports the stronger
   coordinate proof needed for constrained uniqueness.
4. **Where does each oligopoly assumption enter?** E1 gives strict
   log-profit concavity and controls the own markup derivative. E2 controls
   cross derivatives, including option 0. E3 links the strategic row sum to
   the outside-option derivative. The rectangle supports coordinate VI
   comparisons. Finite compact bounds support the separate existence proof.
5. **Is E1 independent of the other two demand restrictions?** With smooth
   demand, E2 covering every other option including option 0, and E3,
   differentiating the common-shift identity gives the own second derivative
   as minus the sum of cross second derivatives. Thus E1 also follows from
   those conditions. Stating it separately makes its economic and
   first-order-sufficiency role explicit.
6. **Do price constraints leave equilibrium unchanged?** No. They can
   change prices, quantities, and profits. The interior, capped, and
   floored logit cases are different games with different outcomes; the
   same uniqueness proof applies to each.
7. **Why can CES uniqueness hold above the existence threshold?** It is
   an at-most-one statement. The threshold proof shows that the number
   of feasible finite roots there is zero, which is consistent with
   conditional uniqueness.
8. **Is Bonacich centrality an eigenvector?** Generally not. It is the
   resolvent response to a baseline vector. Its eigenbasis components
   have different amplification factors. Its normalized critical limit
   is the leading eigenvector for the connected symmetric network.
9. **Why not take the inverse marginal benefit on all nonnegative effort?**
   The cost derivative need not lie in the range of b' everywhere, especially
   when c'(0)=0. The equilibrium-containing box checks and repairs the
   domain before the transformation; it does not discard equilibria.
10. **Does every strictly convex cost automatically satisfy the spectral
    uniqueness test?** No. The test is sufficient, and added cost curvature
    can help beyond it. The complete-network argument proves uniqueness
    directly even when the simple strict spectral inequality is at equality.
11. **Does a most-active player have to be the key player?** No. Removing
    a player changes the entire network equilibrium. The relevant loss is
    total activity after re-equilibration, not just the removed action.
12. **Does the paper establish a general convergent adjustment process?**
    Not from these arguments. The bounded monotone CES iteration constructs
    an equilibrium; the uniqueness and potential calculations here should
    not be relabeled a universal dynamic-stability theorem.

## Precision reminders

- The general NE–VI argument here uses own-payoff concavity. Do not replace
  it with an unrestricted assertion that quasi-concavity alone makes
  stationary first-order conditions sufficient.
- In Example 1 the original matrix already passes the P-matrix test;
  rescaling reveals a simpler symmetric/potential representation. Its
  minimization potential is the negative of the exact payoff potential of
  the rescaled game. Example 2's minimization potential is for the
  transformed VI, not an exact payoff potential of the original game.
- In Example 2, strong convexity and coercivity give a unique minimizer on
  the feasible set, approximately (0.733681,1.005649). This value is a guide
  check, not an additional number needed on the slides. The original
  operator is already strongly monotone.
- For oligopoly, desired markup is an inverse semi-elasticity. Positive
  rescaling preserves all coordinate signs. Strict log-profit concavity,
  rather than generic profit concavity, justifies the pricing conditions.
- A pointwise Jacobian P-matrix certificate, the global P-condition, and
  injectivity are related but distinct statements. The direct dominance
  proof supplies the precise global inequality used here. Arbitrary
  averages of P-matrices need not remain P-matrices.
- Connectedness and positive baselines are explicit in the CES discussion.
  The centrality limit concerns ratios or normalized vectors as action
  levels diverge, not a finite equilibrium at the threshold.
- The public-good potential is used on the valid equilibrium-containing
  box. The deck consistently uses convex minimization; negating the
  potential changes to a maximization convention without changing the
  economic equilibrium problem.
- Separate equilibrium-set preservation, existence, uniqueness,
  participation, and rankings. The last two can hold at every equilibrium
  even when uniqueness is not assumed.
