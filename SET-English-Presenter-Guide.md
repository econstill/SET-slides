# SET: close-reading discussion guide

This English guide follows the 34-page PDF: 33 main pages (including the
cover) plus one optional coordinate-proof backup page.
All page numbers below are physical PDF pages, not Beamer footer numbers.
The source is Yves Zenou and Junjie Zhou, *SET*, February 17, 2026 version.
Figure 1 on page 3 is the paper's original diagram. Speaking cues are kept
only in this separate guide, not in `main.tex` or the slide PDF.

The format is a literature-reading discussion. Each selected application
follows **original operator and Jacobian → SET → transformed Jacobian →
uniqueness**. Stop at a derivative or assumption when the group wants to
understand it. Application-existence proofs, numerical illustrations,
limiting behavior, and effort rankings are outside the current deck.

## Flexible reading routes

### Suggested route: 60–90 minutes, including discussion

| PDF pages | Reading block | Flexible allocation |
|---|---|---:|
| 1–10 | Motivation, map, and the worked example | 15–20 min |
| 11–18 | Methodology and the application-comparison sequence | 12–18 min |
| 19–24 | Oligopoly: original derivative, SET, and diagonal dominance | 12–18 min |
| 25–27 | CES complements: logarithmic SET and the new derivative | 7–10 min |
| 28–31 | Public goods: inverse SET, symmetry, and positive definiteness | 10–16 min |
| 32–33 | Comparison, conclusions, and questions | 4–8 min |

These allocations include interleaved questions and sum to 60–90 minutes.
They are planning ranges, not ceilings on an application. A close reading
can use up to two hours by deriving the Jacobian entries at the board,
unpacking the inverse-domain check, and discussing how the uniqueness
certificate works. Use backup page 34 if the preservation of boundary VI
solutions needs a complete proof. A longer meeting need not add applications
or results beyond this deck's scope.

Before leaving each model, ask: What was the original operator? What exactly
was transformed? Which Jacobian property is now transparent? Does the
calculation establish at most one equilibrium, or also establish existence?

## Paper-page reading map

These are page numbers in the supplied paper. The worked nonlinear game
and coupled-constraint illustration are added seminar teaching examples.

| Deck pages | Primary reading | What to locate in the paper |
|---|---|---|
| 2–3, 11–17 | Section 2, pp. 7–16; Figure 1, p. 17; appendix, p. 42 | Definition 1; Lemma 1; Lemma 4(i), equation (51); Definition 2; Theorem 1(ii); Proposition 1/SET 1–2; Lemmas 2–3 |
| 4–10 | Section 2.2, p. 12; P-property discussion, p. 14 | The added game applies the square root to two positive terms. Compare the failed original matrix test and the noncontractive best responses with the transformed positive principal minors. No potential is used. |
| 19–24 | Section 3.3, pp. 21–23, equations (20)–(21); appendix, p. 46 | Assumptions E1–E3, Proposition 4, the original operator, positive rescaling, and strict row dominance |
| 25–27 | Section 4.1, pp. 32–33, equations (42)–(44); appendix, p. 47 | The conditional-uniqueness argument used in Theorem 4: logarithmic SET, log coordinates, and the P-property. The theorem's existence and limiting statements are not presented. |
| 28–31 | Section 4.2, pp. 38–40; appendix, pp. 50–51 | Assumption 2, the inverse marginal-benefit transformation, symmetry, and Theorem 5's uniqueness argument |
| 34 | Section 2; appendix, p. 43 | Coordinate proof of Theorem 1(ii) |

## Original-number result map

Formal environments preserve the paper's original result types and numbering.
Page 12 is the exception: its short boundary-condition lemma heading uses
automatic deck numbering. The map gives its original label, paper Lemma 4(i).
Results are not renumbered in order of appearance in this deck. Seminar
examples and pedagogical proof steps do not acquire invented original-paper
labels. Pages 4–10 contain the worked example, an added seminar game with
no original-paper example number.

| Deck page | Original label | Scope to retain |
|---:|---|---|
| 11 | Definition 1; Lemma 1 | Well-behaved games: closed convex strategy sets, $C^2$ payoffs, and own-action concavity. The negative payoff gradients give the NE–VI representation. |
| 12 | Lemma 4(i), equation (51) | On a rectangle, the VI is equivalent to a nonnegative component at a lower bound, zero in the interior, and a nonpositive component at an upper bound, for every coordinate. |
| 13 | Definition 2; Theorem 1(ii) | Full-domain sign equivalence and preservation of the entire VI solution set on a rectangle. |
| 14 | Proposition 1 | Sign-preserving operations and their compositions; square-root, log, and inverse domains must be valid. |
| 17 | Lemma 2(ii); Lemma 3 | Rectangular-domain P-property uniqueness, and the convex-potential route; existence is separate. |
| 20 | Assumptions E1–E3 | Preserve the letter-number identifiers, including the outside option in E2 and E3. |
| 24 | Proposition 4 | At most one pricing equilibrium under E1–E3; no existence proof is included. |
| 27 | Uniqueness argument used in Theorem 4 | Conditional uniqueness for every $\delta,\beta>0$, not a restatement of the theorem's existence result. This is an explanatory conclusion, not a newly numbered theorem. |
| 28 | Assumption 2 | Benefit/cost curvature and the marginal crossing needed for the public-good model and inverse-domain check. |
| 31 | Theorem 5 | Under $1+\delta\lambda_{\min}(G)>0$, the paper states a unique public-good equilibrium. The displayed calculation establishes uniqueness; its existence argument is not covered. |
| 34 | Proof of Theorem 1(ii) | Coordinate proof of full solution-set preservation on a rectangle. |

## Page-by-page cues

| PDF page | What to say or check |
|---:|---|
| 1 | Introduce the paper and the reading-group format. The aim is to understand the method and its assumptions, not only to list conclusions. |
| 2 | The difficulty may lie in the representation of equilibrium conditions. The question is whether one can change that representation without changing equilibrium. |
| 3 | Read the original Figure 1 from left to right: game, VI, SET VI, then a matrix or potential route. Equilibrium is also a best-response fixed point; that is not the particular route drawn here. |
| 4 | Introduce $a(x_1)=e^{2-x_1}$ and differentiate each payoff, holding the rival's action fixed. Strict own-action concavity gives $B_1(x_2)=1+x_2^2$ and $B_2(x_1)=a(x_1)$. One response is increasing, the other decreasing; both are positive, so every equilibrium is interior. |
| 5 | Form $F_i=-\partial_i u_i$ and use own-action concavity to obtain the original VI. State the two-dimensional P-matrix test: both diagonal entries and the determinant must be positive throughout the domain. |
| 6 | Differentiate the original operator. At the feasible interior point $(2+\ln2,3)$, $a=1/2$ and $DF=\left(\begin{smallmatrix}1&-6\\-3/2&7\end{smallmatrix}\right)$ has determinant $-2$. This defeats the global sufficient matrix certificate, without implying multiple equilibria. |
| 7 | Check that $(2,1)$ is a best-response fixed point. There $DB=\left(\begin{smallmatrix}0&2\\-1&0\end{smallmatrix}\right)$ has eigenvalues $\pm i\sqrt2$ and spectral radius $\sqrt2>1$. Every induced matrix norm dominates the spectral radius, ruling out contraction in any fixed vector norm, even on a neighborhood of that point. |
| 8 | Complete the square: $F_2=(x_2+a)^2-(2a)^2$. Apply SET 2 with the increasing square root to obtain $\widetilde F_2=x_2-a$. Both arguments and $x_2+a$ are positive, so the square root introduces no absolute-value ambiguity. Rectangularity preserves the entire VI solution set. |
| 9 | Check the transformed principal minors: $1$, $1$, and $1+2ax_2\geq1$. This gives at most one equilibrium on the same feasible domain. The derivative is not symmetric; this example uses the matrix route, not a potential. |
| 10 | Evaluate $\widetilde F(2,1)=0$ to prove existence explicitly. Combine this with uniqueness and positive best responses. Recap the failed raw matrix test, noncontractive best responses, and successful SET matrix test. Do not invoke Brouwer on the unbounded orthant. |
| 11 | State Definition 1's three conditions, then define the negative payoff gradients and state Lemma 1. The slide gives the definition and NE–VI equivalence without the coordinate-by-coordinate derivation. |
| 12 | The boundary-condition lemma (paper Lemma 4(i)) displays $F_i\geq0$ at a lower bound, $F_i=0$ in the interior, and $F_i\leq0$ at an upper bound, for every $i$. Vary one coordinate while holding the others fixed; rectangularity makes each such deviation feasible. With $F_i=-\partial_i u_i$, these are the familiar constrained first-order conditions. |
| 13 | Definition 2 specifies sign equivalence; Theorem 1(ii) preserves the full VI solution set on a rectangle. Explain how independent coordinate deviations preserve boundary solutions as well as interior ones. |
| 14 | Proposition 1 supplies sign-preserving constructions. Explain positive profile-dependent rescaling and an increasing transformation of both sides. Square-root, log, and inverse domains must be valid. |
| 15 | Compute both linear objectives on the triangle. The first is minimized along the top edge, the second only at (1,0). Same signs do not preserve arbitrary coupled-constraint VIs. |
| 16 | Work through the contradiction from two VI solutions. A global P-condition ensures that at least one coordinate product is positive; coordinate optimality makes every such product nonpositive. |
| 17 | Read Lemma 2(ii) and Lemma 3 as separate routes. Define a P-matrix by positive principal minors, distinguishing the Jacobian certificate from page 16's global inequality. Symmetry gives integrability; convexity and existence require their own arguments. |
| 18 | Introduce the shared sequence: original operator and Jacobian, SET, transformed Jacobian, uniqueness. Keep all three applications focused on that comparison. |
| 19 | Explain prices, costs, demand, and the fixed outside option, then differentiate profit to obtain the original operator. E1 gives strict log-profit concavity above cost; positive marginal profit rules out the cost-price endpoint. These facts justify the VI representation without assuming profit itself is concave. |
| 20 | State E1–E3 precisely. Include option 0 in E2 and in E3's hypothetical common additive price shift, while holding its price fixed during strategic play. |
| 21 | Differentiate the original operator. The own-price demand slope gives a positive diagonal contribution, but the demand-curvature term need not. Even diagonal positivity is not guaranteed for the original global P-matrix test. |
| 22 | Divide by $-Q_{i,i}>0$. The multiplier is $1/(-Q_{i,i})$, and the new operator is actual markup minus demand-implied markup. Rectangularity preserves the entire VI solution set, including binding bounds. |
| 23 | Differentiate the inverse semi-elasticity. E1 gives diagonal entries at least one; E2 gives nonpositive strategic cross entries. The outside-option derivative is available for the next step but is not a column of the strategic Jacobian. |
| 24 | Use E3 to replace the sum of strategic markup derivatives by the negative outside derivative. The strict row-dominance margin is at least one, giving a P-matrix everywhere. Proposition 4 concludes at most one equilibrium, not existence. |
| 25 | Introduce the CES aggregate and original operator. Differentiate to obtain $DF=I-\delta DS$ on strictly positive actions. Positive baselines put every equilibrium there; for $\beta<1$, do not claim differentiability at zero. |
| 26 | First apply the increasing logarithm to two positive quantities, then separately set $z=\log x$. The SET preserves signs; the one-to-one coordinate change puts the root problem on $\mathbb R^n$. |
| 27 | Sum the rows of W. Positive baselines make every row sum strictly below one; no self-loops give $W_{ii}=0$. Thus $DH=I-W$ is strictly row diagonally dominant with positive diagonal, hence a P-matrix. Conclude conditional uniqueness for all positive $\delta,\beta$, not existence. |
| 28 | Define local provision and negative marginal payoff. Check the full original derivative $DF=C+A(I+\delta G)$, with $A\succ0$ diagonal. Its row-dependent benefit curvature generally makes it asymmetric. Do not claim the original P-matrix test must fail. |
| 29 | Check the inverse's domain before applying it. On the equilibrium-preserving rectangle, decreasing $b'$ gives the sign-equivalent operator $(I+\delta G)x-h(x)$. The guide below supplies the box construction if needed. |
| 30 | Differentiate the inverse relation. Since $h'\leq0$, the diagonal is at least one and the cross entries are the symmetric weights $\delta g_{ij}$. The gain is symmetry and access to the potential route. |
| 31 | Apply the smallest-eigenvalue bound. The spectral inequality makes the symmetric transformed derivative positive definite, giving uniqueness. Theorem 5 states a unique equilibrium, but its separate existence argument is not presented here. |
| 32 | Compare the original and transformed Jacobians across the three models. The first two use a P-matrix; public goods reveal symmetry and positive definiteness. The representational gain need not be identical in every application. |
| 33 | Recap equilibrium preservation and the useful new derivative. Recall the worked example's failed original matrix test and noncontractive best responses. Keep uniqueness distinct from existence. |
| 34 | Give the full coordinate proof of Theorem 1(ii) if boundary-solution preservation needs further explanation. |

## Worked-example speaking script

Pages 4–10 walk through Figure 1 using one added seminar game. Call it
the worked example throughout. On $K=\mathbb R_+^2$, put
$a(x_1)=e^{2-x_1}>0$. Its payoffs are

\[
u_1=x_1(1+x_2^2)-\tfrac12x_1^2,
\qquad
u_2=3a(x_1)^2x_2-a(x_1)x_2^2-\tfrac13x_2^3.
\]

### Page 4: the game and its best responses

Player 1's marginal benefit rises with the square of player 2's action,
against a quadratic own-action cost. For player 2, the rival-dependent
index $a$ enters the linear benefit and quadratic cost; there is also a
cubic own-action cost. Hold the rival's action fixed when differentiating:
$a(x_1)$ is constant in player 2's own optimization problem.

For player 1,

\[
\partial_1u_1=1+x_2^2-x_1,
\qquad \partial_{11}u_1=-1<0.
\]

The unique maximizer is $B_1(x_2)=1+x_2^2>0$.

For player 2,

\[
\partial_2u_2=3a^2-2ax_2-x_2^2=(a-x_2)(3a+x_2),
\qquad \partial_{22}u_2=-2(a+x_2)<0.
\]

The roots are $x_2=a$ and $x_2=-3a$. Only the first is feasible, so
$B_2(x_1)=a(x_1)=e^{2-x_1}$. Each payoff tends to minus infinity as its
own action increases without bound, and each is strictly own-action
concave. These are global best responses, not merely stationary candidates.
Both are strictly positive for every feasible rival action, so every Nash
equilibrium is interior. The first response is increasing and the second
decreasing; this statement about best responses does not assert a global
cross-payoff-derivative sign for player 2.

### Page 5: the original equilibrium operator

Take negative marginal payoffs:

\[
F_1=x_1-1-x_2^2,
\qquad F_2=x_2^2+2ax_2-3a^2.
\]

Own-action concavity makes each player's first-order optimality condition
sufficient. Summing the coordinate conditions gives the VI displayed on
the slide. A candidate sufficient uniqueness certificate is that $DF$ is a
P-matrix at every feasible profile. In two dimensions this requires two
positive diagonal entries and a positive determinant.

### Page 6: why the original sufficient test fails

Remember $a'(x_1)=-a(x_1)$ when differentiating the second row:

\[
DF=\begin{pmatrix}
1&-2x_2\\
2a(3a-x_2)&2(a+x_2)
\end{pmatrix},
\qquad
\det DF=2(a+x_2)+4ax_2(3a-x_2).
\]

Both diagonal entries are positive. At the feasible interior point
$\widehat x=(2+\ln2,3)$, however, $a=1/2$, so
$DF(\widehat x)=\left(\begin{smallmatrix}1&-6\\-3/2&7\end{smallmatrix}\right)$
has determinant $7-9=-2$. A global certificate must hold everywhere on
the feasible domain, so one such point defeats it. The point need not
itself be an equilibrium. Failure of a sufficient condition alone
establishes neither multiplicity nor non-existence.

### Page 7: why best-response contraction does not help

The joint best-response map is a self-map of the nonnegative orthant:

\[
B(x)=\begin{pmatrix}1+x_2^2\\e^{2-x_1}\end{pmatrix},
\qquad
DB(x)=\begin{pmatrix}0&2x_2\\-e^{2-x_1}&0\end{pmatrix}.
\]

At $x^*=(2,1)$, $B(x^*)=x^*$ and
$DB(x^*)=\left(\begin{smallmatrix}0&2\\-1&0\end{smallmatrix}\right)$.
Its characteristic equation is $\lambda^2+2=0$, so its spectral radius
is $\sqrt2>1$.

If a differentiable map is a contraction with modulus $q<1$ in a fixed
vector norm on a neighborhood of an interior point, taking directional
difference quotients gives $\|DB(x^*)\|\leq q$. Every induced matrix norm
is at least the spectral radius. Hence no such norm can make this map a
contraction, even locally around its fixed point. This rules out that
Banach argument, not uniqueness itself. It does not make a claim about
every conceivable metric, transformed dynamic, or adjustment rule.

### Page 8: the sign-equivalent transformation

Complete the square in the second component:

\[
F_2=(x_2+a)^2-(2a)^2.
\]

The function $h(t)=\sqrt t$ is strictly increasing on $(0,\infty)$.
Both operands are strictly positive on $K$, and $x_2+a>0$, so SET 2 gives

\[
\widetilde F_2=\sqrt{(x_2+a)^2}-\sqrt{(2a)^2}=x_2-a.
\]

There is no hidden absolute-value issue. Keep $\widetilde F_1=F_1$.
Strict increase preserves the ordering of the two operands, including
equality, at every feasible profile. Thus

\[
\widetilde F=\begin{pmatrix}x_1-1-x_2^2\\x_2-e^{2-x_1}\end{pmatrix},
\qquad \Sol(K,F)=\Sol(K,\widetilde F).
\]

Rectangularity is what promotes full-domain sign equivalence to equality
of the entire constrained VI solution sets. The payoffs and feasible
actions have not changed.

### Page 9: the transformed matrix certificate

\[
D\widetilde F=\begin{pmatrix}1&-2x_2\\a&1\end{pmatrix}.
\]

Its principal minors are $1$, $1$, and $1+2ax_2\geq1>0$ on all of $K$.
The P-matrix test succeeds throughout the very domain where the original
test failed. This yields at most one VI solution and hence at most one
equilibrium. Existence is still a separate question at this step.

The transformed Jacobian is not symmetric: its cross entries have opposite
signs in the interior. Do not introduce a potential for this operator.
The example follows only the matrix branch of Figure 1.

### Page 10: existence and the unique equilibrium

Evaluate the transformed operator at $(2,1)$: both components vanish.
This explicit feasible zero proves existence on the unbounded domain;
no compact-domain fixed-point theorem is needed. Combined with the
P-matrix certificate, it gives the unique equilibrium $(2,1)$. Both best
responses are strictly positive, so boundary equilibria cannot be missing.

Return to Figure 1. The original global P-matrix test failed; best responses
also failed every fixed-norm contraction test. SET preserved the equilibrium
problem and revealed a useful P-matrix certificate. It did not change the
best responses or turn the original best-response iteration into a
contraction.

For an optional independent check, substitute $x_1=1+x_2^2$ into
$x_2=e^{2-x_1}$ to obtain
$\log x_2+x_2^2=1$. The left-hand side is strictly increasing on
$(0,\infty)$ and equals one at $x_2=1$, giving $(x_1,x_2)=(2,1)$.
This corroborates uniqueness for this particular game; it is separate
from the matrix route taught on the slide.

## Methodology speaking notes

### Pages 11–13: optimality, the VI, and signs

Page 11 states Definition 1 before Lemma 1. Page 12, "The VI as familiar
boundary conditions," displays the boundary-condition lemma (paper
Lemma 4(i)), with three coordinate conditions from appendix p. 42,
equation (51). The scalar-action derivation below explains their connection
to the VI.

Fix the other players' actions. With a differentiable payoff concave in own
action, a feasible action is optimal exactly when every feasible directional
derivative is nonpositive. We put a minus sign in front of marginal payoff,
so optimality becomes $(y_i-x_i^*)F_i(x^*)\geq0$ for every feasible $y_i$.

Sum these inequalities to get the VI. To reverse the argument, choose a
test vector that differs from the candidate equilibrium in only one
coordinate. This test vector is feasible because the domain is a product
of individual intervals. The VI then recovers that player's optimality
condition. Concavity is doing substantive work: necessary first-order
conditions are now sufficient.

Page 12 displays the three cases on an interval: at the lower bound,
$F_i(x^*)\geq0$; in the interior, $F_i(x^*)=0$; at the upper bound,
$F_i(x^*)\leq0$, for every $i$. Coordinatewise signs therefore encode
the entire solution set on a rectangle. This statement allows binding
constraints; it is stronger than saying that two systems have the same
zeros. Page 13 then defines sign equivalence and states the preservation
result.

### Pages 14–15: constructions and the domain restriction

Multiplying a component by a positive function preserves its sign even
when that function depends on every player's action. Alternatively, an
increasing transformation preserves the ordering of two expressions. If
the original component compares A with B, applying the same increasing
function to A and B preserves the direction of the comparison. The worked
example uses $h(t)=\sqrt t$ on two positive arguments. Later we use logarithms
and inverse functions. Their domains must be checked before applying them.

Now consider the triangle on page 15. For a constant operator, the VI is
the first-order condition for minimizing a linear objective. The first
objective is minus total activity: every point using the whole shared
resource is optimal. The transformed objective values activity in the
first coordinate twice as much and uniquely selects (1,0). Although both
components remain negative, the magnitudes matter under a shared
constraint. One cannot vary each coordinate independently as in the
rectangle proof. This is a coupled-constraint VI illustration, not the
strategy set of the preceding ordinary two-player game.

### Pages 16–17: the uniqueness proof and its certificates

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

## Application speaking scripts

All three applications use the same sequence: original operator and
Jacobian, SET, transformed Jacobian, uniqueness. The scripts below explain
only that sequence and the assumptions needed to make it valid.

### Oligopoly, pages 19–24

**Pages 19–20: primitives and the VI.** Profit is markup times demand:
$\pi_i=(p_i-c_i)Q_i$. The price set is a product of intervals with lower
bounds at least cost, and the outside-option price is fixed. Negative
marginal profit gives
\[
F_i=-Q_i-(p_i-c_i)Q_{i,i}.
\]
Under E1, for $p_i>c_i$,
\[
\partial_{p_i}^2\log\pi_i
=-\frac1{(p_i-c_i)^2}+\partial_{p_i}^2\log Q_i<0.
\]
Strict log-profit concavity makes the interior or endpoint derivative signs
sufficient for a best response. At cost, marginal profit is $Q_i>0$, and
a feasible higher price gives positive profit. This justifies the original
VI representation; it does not assert that profit itself is concave.

E1 controls own-price log curvature. E2 controls cross log curvature,
including option 0. E3 is common additive price-shift invariance, not
multiplicative homogeneity. Its hypothetical shift includes the outside
price even though that price is fixed during the game.

**Page 21: the original Jacobian.** Differentiate once more:
\[
(DF)_{ii}=-2Q_{i,i}-(p_i-c_i)Q_{i,ii},\qquad
(DF)_{ij}=-Q_{i,j}-(p_i-c_i)Q_{i,ij}\quad(j\ne i).
\]
The law of demand makes the first diagonal contribution positive; it does
not control the second contribution enough to guarantee diagonal
positivity. The original derivative need not pass the global P-matrix
test. This is a failure of a sufficient certificate, not proof of
multiple equilibria.

**Page 22: SET1.** Divide by $-Q_{i,i}>0$:
\[
\widetilde F_i=p_i-c_i-\mu_i,\qquad
\mu_i=\frac{Q_i}{-Q_{i,i}}=-\frac1{\partial_{p_i}\log Q_i}.
\]
The positive multiplier is $1/(-Q_{i,i})$. The gap compares actual markup
with demand-implied markup, an inverse semi-elasticity rather than an
inverse ordinary elasticity. A negative gap means positive marginal profit;
a positive gap means negative marginal profit. All signs, not merely zeros,
are preserved. Rectangularity therefore preserves constrained equilibria
as well as interior ones.

**Pages 23–24: transformed derivative and uniqueness.** With
$\ell_i=\log Q_i$,
\[
\partial_{p_j}\mu_i
=\frac{\partial_{p_i p_j}^2\ell_i}{(\partial_{p_i}\ell_i)^2},
\qquad J=D\widetilde F=I-D\mu.
\]
E1 gives $J_{ii}\geq1$; E2 gives $J_{ij}\leq0$ for strategic $j\ne i$.
E3 implies $\sum_{j=0}^n\partial_{p_j}\mu_i=0$, so
\[
J_{ii}-\sum_{\substack{j=1\\j\ne i}}^n|J_{ij}|
=1+\partial_{p_0}\mu_i\geq1.
\]
Thus the strategic Jacobian has positive diagonal and strict row diagonal
dominance, hence is a P-matrix everywhere. Proposition 4 gives at most one
equilibrium. No existence argument is supplied in this block.

If a longer discussion asks how the derivative controls two constrained VI
solutions, choose $|d_i|=\|d\|_\infty>0$ for $d=p-q$. Integrating along their
segment gives
$d_i[\widetilde F_i(p)-\widetilde F_i(q)]\geq d_i^2>0$.
This proves the global inequality from page 16 directly; it does not
assume that arbitrary averages of P-matrices remain P-matrices.

### CES complements, pages 25–27

**Page 25: the original operator and derivative.** With positive baselines,
every best response is $T_i=a_i+\delta S_i>0$, where the CES aggregate
$S_i$ is homogeneous of degree one. Thus every equilibrium is interior and
solves $F_i=x_i-T_i(x)=0$. On strictly positive actions,
\[
DF=I-\delta DS,\qquad
(DS)_{ij}=g_{ij}x_j^{\beta-1}S_i^{1-\beta}.
\]
Maintain the slide's connected nonempty undirected network without
self-loops and $a_i,\delta,\beta>0$. When $\beta<1$, derivatives need not
exist at zero; the calculation is deliberately on $\mathbb R_{++}^n$,
which contains every equilibrium.

**Page 26: two distinct steps.** First, increasing logarithms preserve the
sign of the comparison between positive $x_i$ and $T_i(x)$:
$\widetilde F_i(x)=\log x_i-\log T_i(x)$. This is SET2.
Second, the one-to-one change $z=\log x$ gives
$H_i(z)=z_i-\log T_i(e^z)$ on $\mathbb R^n$.
Changing coordinates is not itself a sign-equivalent transformation.
Together the steps identify the original positive equilibria with zeros
of H.

**Page 27: the new derivative and conditional uniqueness.** Differentiate:
\[
DH=I-W,\qquad
W_{ij}=
\frac{\delta S_i(e^z)}{a_i+\delta S_i(e^z)}
\frac{g_{ij}e^{\beta z_j}}{\sum_k g_{ik}e^{\beta z_k}}.
\]
The second factor sums to one in each row. The first is strictly below
one because $a_i>0$. Hence $W\geq0$, $W_{ii}=0$, and
$\sum_jW_{ij}<1$. The Jacobian DH has positive diagonal and strict row
dominance, so it is a P-matrix everywhere. There is at most one zero and
therefore at most one equilibrium for every positive $\delta,\beta$.
This is the conditional-uniqueness argument used in Theorem 4, not a
restatement of the theorem's existence result.

The strict row bounds do not give a single contraction modulus below one
on all log-action space. If needed, continuity gives a uniform bound below
one on the compact segment between two proposed finite roots; integrating
$DL$, where $L(z)=\log T(e^z)$ componentwise, along that segment then yields
the contradiction in the infinity norm.

### Public goods, pages 28–31

**Page 28: original operator and full derivative.** Maintain $G=G^\top$
and $g_{ii}=0$, so the network is undirected and has no self-loops. With
$s=(I+\delta G)x$, the negative marginal payoff is
$F_i=c'(x_i)-b'(s_i)$. Define
$C=\operatorname{diag}(c''(x_i))$ and
$A=\operatorname{diag}(-b''(s_i))\succ0$. Then
\[
DF=C+A(I+\delta G).
\]
For $j\ne i$, the cross entry is $-\delta g_{ij}b''(s_i)$. Its row-dependent benefit
curvature generally makes the original Jacobian asymmetric, despite an
undirected network. Assumption 2 gives strictly concave benefits, convex
costs, and the marginal crossing used below.

**Page 29: inverse SET and its domain.** To explain the rectangle if asked,
let $k^*>0$ solve $b'(k^*)=c'(k^*)$, define
$\theta(t)=\arg\max_{u\geq0}\{b(u+t)-c(u)\}$, and put
$B=\delta d_{\max}k^*$, $\ell=\theta(B)$, $K=[\ell,k^*]^n$.
For this box construction take a nonempty network; an edgeless network
decouples into the individual autarky problems and needs no inverse argument.
Best responses are nonincreasing in neighbor provision and at most $k^*$.
Against rivals in $[0,k^*]^n$, every original best response lies in K.
Every original equilibrium is therefore in K; against rivals in K the
original best response still belongs to K, so restricting choices to K
does not change it or the equilibrium set. The optimality condition at
$\ell$ gives, for $u\in[\ell,k^*]$,
\[
\lim_{s\to\infty}b'(s)<c'(u)\leq c'(k^*)=b'(k^*)<b'(0).
\]
Consequently $h(u)=(b')^{-1}(c'(u))$ is finite there. In particular,
$c'(0)=0$ implies $\ell>0$; no inverse value at zero is needed.

On this valid rectangle, decreasing $b'$ gives
\[
F_i=b'(h(x_i))-b'(s_i)
\quad\sim_{\rm sign}\quad s_i-h(x_i).
\]
The transformed operator is $\widetilde F=(I+\delta G)x-h(x)$.
Rectangularity preserves the entire constrained VI solution set.

**Page 30: symmetry is the gain.** Implicit differentiation yields
$h'=c''/b''(h)\leq0$, and
\[
D\widetilde F=I+\delta G-\operatorname{diag}(h'(x_i)).
\]
Its diagonal is at least one and its cross entries are exactly the
symmetric weights $\delta g_{ij}$. The row-dependent benefit curvature
has disappeared from the cross effects. Symmetry supplies an integrable
potential; the next step checks its curvature.

**Page 31: positive definiteness and uniqueness.** The Rayleigh bound gives
\[
D\widetilde F\succeq[1+\delta\lambda_{\min}(G)]I.
\]
Under the strict spectral inequality the potential is strictly convex,
so there is at most one constrained solution. Theorem 5 states a unique
equilibrium; the displayed Jacobian calculation is its uniqueness
argument, not its separate existence proof. The convex-minimization
potential can be negated to use the paper's concave-maximization convention.

Do not claim that the original P-matrix test fails here. Under the same
spectral condition,
\[
A^{-1}DF=A^{-1}C+I+\delta G
\]
is symmetric positive definite. Positive diagonal row scaling preserves
the signs of principal minors, so DF is already a P-matrix. SET's gain
in this application is the symmetric transformed derivative and the
transparent potential route, not a previously unavailable P-certificate.

### Comparison and conclusions, pages 32–33

Compare the derivative structures, not every economic result of the
models. Oligopoly removes a demand-slope scale and reveals strict
diagonal dominance. CES logarithms and log coordinates reveal row sums
below one. Public goods remove row-dependent benefit curvature from the
cross effects and reveal symmetry. Different models benefit from different
representations.

Finish by separating three claims: SET preserves the equilibrium problem;
a matrix or curvature condition gives at most one solution; existence
requires another argument. The opening game supplies an explicit solution,
but the application blocks do not develop their existence proofs.

## Discussion questions and short answers

1. **Why do signs preserve boundary equilibria?** On a rectangle, each
   coordinate can be varied independently. The lower-bound, interior,
   and upper-bound conditions depend only on the component sign. The
   triangle illustration shows why shared constraints change this.
2. **Does SET preserve the original Jacobian or its eigenvalues?** No.
   Its derivatives may change substantially. Under the stated conditions,
   it is the VI solution set that is preserved.
3. **Why not use injectivity alone?** It controls zeros, not all constrained
   VI solutions. On $[0,1]$, the injective operator $F(x)=1/2-x$ has VI
   solutions $0,1/2,1$. The global P-condition supports the stronger
   coordinate argument.
4. **Where do E1–E3 enter?** E1 supplies strict log-profit concavity and
   the own markup-derivative sign; E2 supplies cross signs including
   option 0; E3 produces the strict row-dominance margin.
5. **Are CES logarithms and log coordinates the same operation?** No.
   Comparing logarithms preserves signs; changing coordinates is a
   separate one-to-one identification of positive roots.
6. **Does CES conditional uniqueness imply existence?** No. “At most one”
   allows no equilibrium. The current block does not address existence.
7. **Must SET rescue a failed original P-matrix test in every application?**
   No. It does in the opening game, and the original oligopoly derivative
   need not pass the test. In public goods the original derivative already
   passes under the stated spectral condition; the gain is symmetry.
8. **Why check the inverse marginal-benefit domain?** Cost derivatives
   need not lie in the range of $b'$ everywhere. The equilibrium-preserving
   box validates the inverse without discarding equilibria.
9. **Could a weighted norm make the worked game's best responses contractive?**
   No. At $(2,1)$ their derivative has spectral radius $\sqrt2>1$, and
   every induced matrix norm is at least that large. No fixed vector norm
   gives a local contraction there, although the equilibrium is unique.
10. **Does uniqueness establish convergence of adjustment dynamics?** No.
    A best-response, gradient, or other adjustment rule requires its own
    stability and convergence analysis.

## Precision reminders

- General NE–VI equivalence uses own-payoff concavity. Oligopoly instead
  justifies its marginal conditions with strict log-profit concavity above
  cost and a direct endpoint argument; profit itself need not be concave.
- The worked example uses increasing square-root SET2, has raw determinant
  $-2$ at $(2+\ln2,3)$, and has transformed principal minors
  $1,1,1+2x_2e^{2-x_1}>0$. Its unique equilibrium is $(2,1)$.
  No potential or fixed-norm best-response contraction is used.
- Pointwise Jacobian P-property, the global P-condition, and injectivity
  are distinct statements. Arbitrary averages of P-matrices need not
  remain P-matrices; strict row dominance supports a direct global argument.
- CES derivatives are evaluated at strictly positive actions. The
  logarithmic SET and coordinate change must be distinguished, and the
  strict pointwise row bound is not a uniform global contraction bound.
- The public-good inverse is used only on a valid equilibrium-preserving
  box. Its representational gain is symmetry, not a claim that the
  original derivative fails the P-matrix test.
- Proposition 4 and the CES argument give at most one equilibrium.
  Theorem 5 states existence and uniqueness, but this deck presents its
  uniqueness calculation only. SET itself does not establish existence.
