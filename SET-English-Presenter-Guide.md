# SET: close-reading discussion guide

This English guide follows the 53-page PDF: 50 main pages (including the
cover) plus three optional technical backup pages.
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

### Full route: approximately 100–120 minutes, including discussion

| PDF pages | Reading block | Flexible allocation |
|---|---|---:|
| 1–10 | Motivation, map, and the worked example | 20 min |
| 11–18 | Methodology on pages 11–17, then Selected Applications on page 18 | 15–20 min |
| 19–32 | Oligopoly model, demand restrictions, proof, existence, and logit checks | 30–35 min |
| 33–34 | Connections to other existing applications | 2 min |
| 35–38 | CES complements: logarithmic system, derivative, and threshold statement | 8–10 min |
| 39–48 | Public goods, inverse domain, potential, and economic results | 20–25 min |
| 49–50 | Synthesis and final questions | 5–8 min |

These allocations include questions taken within each block. They are a
planning aid, not a ceiling on the oligopoly discussion or a requirement to
give every page equal time. If participants want to derive every intermediate
step at the board, spend longer on that module and postpone another module
or continue in a second meeting. The entire deck remains available for that
purpose. Technical backup pages can replace a planned illustration when a
specific question arises.

### Focused route: approximately 60 minutes

Use roughly 10 minutes for the map and the worked example, 15 for methodology,
25 for the oligopoly reading, five for selected network conclusions, and
five for synthesis and questions. Within oligopoly, prioritize the markup
gap, boundary signs, strict log-profit concavity, the roles of E1–E3, and
the demonstration on page 32 of why SET helps the matrix test.
On page 27 explain the maximum-coordinate idea; a line-by-line integral
proof can be reserved for the longer route. Select page 38 or pages 44–46
for network conclusions, then use page 50 for synthesis. Do not present
pages 35–48 as if all of their proofs have been covered in this shorter
session. The CES conditional-uniqueness proof can be explained from the
separate notes below; its proof block is not in the current slides. The
existence and limiting-ratio proofs are left to the paper even on the full
route.

For either route, ask four questions before leaving a model: What is the
equilibrium problem? What is preserved? Which assumptions make the new
representation useful? Which economic conclusion follows, and which does
not?

## Paper-page reading map

These are page numbers in the supplied paper. The worked nonlinear game,
numerical logit price comparison, coupled-constraint illustration, and
two-node algebraic calculation are seminar teaching examples.

| Deck pages | Primary reading | What to locate in the paper |
|---|---|---|
| 2–3, 11–17 | Section 2, pp. 7–16; Figure 1, p. 17; appendix, p. 42 | Definition 1; Lemma 1; Lemma 4(i), equation (51); Definition 2; Theorem 1(ii); Proposition 1/SET 1–2; Lemmas 2–3 |
| 4–10 | Section 2.2, p. 12; P-property discussion, p. 14 | The added game applies the square root to two positive terms. Compare the failed original matrix test and the noncontractive best responses with the transformed positive principal minors. No potential is used. |
| 19–32 | Section 3.3, pp. 21–23, equations (20)–(21); appendix, p. 46 | Assumptions E1–E3, Proposition 4, price restrictions, positive rescaling, and the row-dominance proof |
| 33 | Section 3.2, pp. 19–21 | Proposition 3: row-normalized CES social norms and uniqueness conditional on existence |
| 34 | Sections 3.4–3.5, pp. 23–31 | Inverse functions, symmetric transformed systems, and potential methods |
| 35–38, 52 | Section 4.1, pp. 32–34; appendix, pp. 47–49 | Theorem 4: the deck displays the derivative underlying conditional uniqueness and states the spectral threshold and limiting ratios. The notes below explain the uniqueness argument. Read the existence, non-existence, and Perron-limit proofs in the appendix. Page 52 is an added algebraic-feasibility check. |
| 39–48, 53 | Section 4.2, pp. 38–41; appendix, pp. 50–52 | Assumptions 2–3, Theorem 5, Proposition 7, and neighborhood rankings |

The inverse-domain box on page 42 makes explicit a range check needed when
using the inverse marginal benefit in Section 4.2. On that valid domain,
with a common valid integration reference, the deck's minimization potential
is $\Psi=-\phi^{BKC}_{\mathrm{paper}}+C$. Thus it has the opposite sign to
the paper's maximization potential, up to an integration constant. The
deck's gradient and Hessian use the minimization convention consistently.

## Original-number result map

Native lemma, theorem, proposition, corollary, definition, and assumption
environments preserve the paper's original result types and numbering.
Page 12 is the exception: its short boundary-condition lemma heading uses
automatic deck numbering. The map gives its original label, paper Lemma 4(i).
Repeated parts retain the same number; they are not renumbered in order of
appearance in this deck. Seminar examples and pedagogical proof steps do
not acquire invented original-paper labels. Pages 4–10 contain the worked
example, an added seminar game with no original-paper example number.

| Deck page | Original label | Scope to retain |
|---:|---|---|
| 11 | Definition 1; Lemma 1 | Well-behaved games: closed convex strategy sets, $C^2$ payoffs, and own-action concavity. The negative payoff gradients give the NE–VI representation. |
| 12 | Lemma 4(i), equation (51) | On a rectangle, the VI is equivalent to a nonnegative component at a lower bound, zero in the interior, and a nonpositive component at an upper bound, for every coordinate. |
| 13 | Definition 2; Theorem 1(ii) | Full-domain sign equivalence and preservation of the entire VI solution set on a rectangle. |
| 14 | Proposition 1 | Sign-preserving operations and their compositions; square-root, log, and inverse domains must be valid. |
| 17 | Lemma 2(ii); Lemma 3 | Rectangular-domain P-property uniqueness, and the convex-potential route; existence is separate. |
| 20 | Assumptions E1–E3 | Preserve the letter-number identifiers, including the outside option in E2 and E3. |
| 28 | Proposition 4 | At most one pricing equilibrium. Finite-box Brouwer existence is a separate argument, not the proposition's literal conclusion. |
| 33 | Proposition 3 | For positive baselines, under $0<\lambda_1+\lambda_2<1$ and $0<\lambda_1<1$, any positive solution of the specified peer-effect system is unique, conditional on existence. |
| 38 | Theorem 4 | Statement of the threshold, comparative statics, and limiting ratios. Part (iii) literally states non-existence for $\delta>\bar\delta$; appendix Claim 2 also excludes equality. The existence and limit proofs are outside the current slides. |
| 39 | Assumption 2 | Benefit/cost curvature, marginal crossing, and the autarky solution. |
| 44 | Theorem 5 | The sufficient spectral condition for potential curvature and a unique public-good equilibrium. |
| 45 | Assumption 3; Proposition 7(i) | Zero initial marginal cost and full participation under the stated model assumptions. |
| 46 | Proposition 7(iii) | Complete-network uniqueness and equal efforts under the maintained strictly convex-cost assumptions. |
| 47 | Proposition 7(ii); Corollary 2 | Neighborhood-inclusion rankings, and the degree ranking specifically for nested-split graphs. |
| 48 | Proposition 7(iv) | Equal leaf efforts and strictly lower hub effort in a star with at least three nodes. |
| 51 | Proof of Theorem 1(ii) | Coordinate proof of full solution-set preservation on a rectangle. |
| 53 | Proof of Proposition 7(iii) | Complete-network uniqueness even when the simple strict spectral inequality is at equality. |

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
| 18 | Introduce Selected Applications. Oligopoly traces demand assumptions into uniqueness, CES complements display the conditional-uniqueness derivative and state the separate threshold, and public goods use a potential to study convex costs. Keep the promised proof scope distinct across these blocks. |
| 19 | Explain differentiated products, costs, price intervals, rival prices, and the fixed outside option. The question concerns mutually optimal prices, including constrained prices. |
| 20 | State the demand restrictions E1–E3 before deriving markup conditions. Include option 0 in E2 and in the hypothetical common shift in E3, while holding its price fixed during strategic play. These restrictions, not a logit-only consumer model, drive the general result. |
| 21 | Differentiate profit into retained-customer revenue and lost-customer effects. Define the desired markup before discussing uniqueness. It is an inverse semi-elasticity, not an inverse elasticity. |
| 22 | Divide by the positive absolute own-price demand slope. The resulting markup gap has the same sign as negative marginal profit, hence the opposite sign to a profitable price increase. |
| 23 | At a cap, positive marginal profit can be optimal; at a floor, negative marginal profit can be optimal. Sign preservation retains these outcomes. First-order sufficiency under the already-stated E1 is justified on page 24. |
| 24 | Differentiate log-profit twice. E1 plus the strictly concave log-markup term gives strict log-profit concavity for prices above cost. Treat the cost-price endpoint directly using positive marginal profit. |
| 25 | Differentiate the desired markup. E1 controls its own-price slope; E2 controls its rival- and outside-price slopes. Translate these into the diagonal and cross entries of the markup-gap Jacobian. |
| 26 | Differentiate common-price-shift invariance for the desired markup. Sum only the strategic columns of the Jacobian, leaving the outside-option term. This gives the strict row-dominance margin. |
| 27 | Pick the largest absolute coordinate of the difference between two price vectors. Integrate the Jacobian along their segment; row dominance makes the selected coordinate product strictly positive. Connect this to page 16. |
| 28 | Proposition 4 gives at most one pricing equilibrium. Keep finite-box existence separate: unique continuous best responses and Brouwer supply a fixed point, yielding exactly one only after combining both arguments. |
| 29 | Verify logit E1 and E2 directly and E3 by cancelling a common exponential factor. The general proof used these properties, not the logit formula itself. |
| 30 | Solve the symmetric scalar equation. The feasible zero-gap solution proves existence; the global result rules out asymmetric equilibria too. |
| 31 | Compare zero-gap interior pricing with negative-gap cap pricing and positive-gap floor pricing. Bounds change the economic outcome, while the same uniqueness argument applies in each box. |
| 32 | The original pricing derivative has a negative diagonal entry at (4,4), so it fails the global P-matrix test on the box. The transformed derivative passes throughout that same box. This concretely shows what SET changes; failure of the original sufficient test does not show multiple equilibria. |
| 33 | Proposition 3 requires $0<\lambda_1+\lambda_2<1$ and $0<\lambda_1<1$. The row-normalized social norm need not average peer effort. The conclusion is conditional uniqueness, not existence supplied by SET. |
| 34 | Connect inverse Engel curves and multiplex interactions to the potential route. Symmetric transformed derivatives help; further curvature assumptions are still needed for uniqueness. |
| 35 | Introduce CES complements with an unnormalized adjacency matrix. Strict own-action concavity gives the best response. Maintain positive baselines and a connected nonempty undirected network for the derivative argument and threshold statement. |
| 36 | Every equilibrium is positive, so log actions cover the entire equilibrium set. Separate the sign-preserving log comparison from the one-to-one change of variables. |
| 37 | Derive the two factors in W and sum each row. Positive baselines make the sum strictly below one. The current slide displays the derivative only; the optional argument in this guide uses a uniform bound on the compact segment between two proposed roots, not necessarily on all log-action space. |
| 38 | State Theorem 4's three parts: existence and monotonicity below the threshold, diverging levels and Perron ratios at the limit, and non-existence above it. The appendix also excludes equality. The derivative on page 37 supports conditional uniqueness; the theorem's additional claims require the paper's appendix arguments. |
| 39 | Introduce benefit from local total provision and private cost of own effort. Assumption 2 states curvature and marginal crossing; define autarky effort k*. |
| 40 | Distinguish an interior marginal equality from a zero-effort inequality. Strict concavity gives a unique continuous best response bounded by k*, so Brouwer establishes existence before any spectral condition. |
| 41 | Implicitly differentiate the best response. Linear costs give slope minus one when interior; positive cost curvature reduces crowding out locally. A bound on one scalar slope does not by itself prove network-wide uniqueness. |
| 42 | Check the range before applying an inverse. Construct B, ell=theta(B), and the equilibrium-containing box. Explain why original and restricted games have identical best responses on this box and hence the same equilibrium set. |
| 43 | Verify the signs with b' strictly decreasing. The transformed cross derivatives equal delta g_ij and are symmetric. Differentiate the potential to check its sign convention. |
| 44 | Theorem 5 follows by differentiating the inverse and applying the Rayleigh lower bound. The spectral inequality is sufficient, not necessary; cost curvature contributes an extra nonnegative diagonal term. |
| 45 | State Assumption 3, then Proposition 7(i). At zero effort and zero marginal cost, marginal benefit is strictly positive at every finite profile. Every equilibrium is interior, independently of uniqueness. |
| 46 | Proposition 7(iii): on a complete graph all players face the same total provision. Strictly increasing marginal cost forces equal effort and a unique scalar solution; linear costs allow every allocation with the same total. |
| 47 | State the homogeneous-functions, zero-initial-marginal-cost, strict-convexity, and delta=1 assumptions. Proposition 7(ii) uses neighborhood inclusion; Corollary 2 gives the nested-split degree ranking, not a degree rule on arbitrary graphs. |
| 48 | Proposition 7(iv): all leaves have the same best response. Compare hub and leaf marginal benefits using positive leaf effort and n at least three. Strictly increasing marginal cost gives the strict effort ranking. |
| 49 | Classify each proof by its purpose: preserving equilibrium, proving existence, or proving uniqueness. A valid transformation is not a substitute for the latter two arguments. |
| 50 | Summarize the current deck: SET restores a global matrix certificate in the worked example despite noncontractive best responses, CES conditional uniqueness is distinct from the threshold statement, and public goods connect cost curvature to uniqueness, participation, and rankings. Ask which structure the transformation exposes. |
| 51 | Give the full coordinate proof of Theorem 1(ii) when participants want the details of boundary-solution preservation. |
| 52 | A unique algebraic solution can be negative and economically infeasible. Matrix invertibility is not the same as a nonnegative equilibrium in the network game. |
| 53 | Prove Proposition 7(iii) directly from equal marginal costs and a strictly decreasing scalar equation. This works when the simple strict spectral bound is at equality. |

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

## Oligopoly speaking script

Pages 19–32 follow Section 3.3, pp. 21–23, with the appendix argument on
p. 46. Work through the assumptions and proof at the group's pace.
There is no fixed time limit for this application. The numerical logit
price boxes are teaching examples, not numerical results reported by the
paper.

### Page 19: the economic problem

Each firm sells a differentiated product, so a higher price need not lose
every customer. Price minus constant unit cost is the markup per sale;
markup times demand is profit. Demand depends on all strategic prices and
on the outside option, which represents not buying from these firms.

The outside price is held fixed during the game. Each firm chooses within
its own interval, with the lower endpoint at least its unit cost. These
separate intervals make the joint feasible set rectangular. Ask whether
several price vectors can make every firm's choice optimal, including
when a price floor or cap binds.

### Page 20: the demand restrictions E1–E3

State the restrictions before deriving the markup equation. E1 says log
demand is concave in own price. Equivalently, own-price semi-elasticity
weakly increases with own price. E2 says the cross derivative of log
demand is nonnegative: higher prices of other options weakly increase
the desired markup. E2 must include the outside option.

E3 says adding the same amount to every option's price leaves choices
unchanged. It is common additive price-shift invariance, not multiplicative
degree-zero homogeneity. The outside price remains fixed during strategic
play, but is included in this hypothetical simultaneous shift. The logit
checks later provide an example; the general theorem is not restricted to
that demand formula. The deck takes demand and these restrictions as
primitives, rather than deriving them from a consumer-choice model.

### Page 21: the pricing trade-off

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

### Page 22: the SET step

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

### Page 23: why boundaries require signs

At an interior price both small directions are feasible, so marginal
profit must vanish. At a cap, the firm may still want to increase price:
marginal profit can be positive, while the markup gap is nonpositive.
At a floor, the firm may prefer a lower price: marginal profit can be
negative, while the gap is nonnegative.

Positive rescaling preserves all three cases. On the rectangular price
set, the original and transformed VIs therefore have exactly the same
solution set. Merely preserving zeros would miss constrained equilibria.
E1 has already been stated. The next page justifies why these first-order
signs characterize genuine best responses under that restriction.

### Page 24: sufficiency, not just necessary conditions

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

### Page 25: E1 and E2 in the transformed derivative

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

### Page 26: E3 and the outside option

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

### Page 27: from local derivatives to a global proof

Take any two distinct feasible price vectors and their difference d.
Select a coordinate with the largest absolute difference. Along the
segment joining the vectors, the derivative matrix obeys the same row
dominance bound. Multiply the change in that coordinate's gap by its
price difference and express the change as an integral.

Every cross term can be bounded in absolute value by the selected
coordinate's squared difference times the absolute cross derivative.
The diagonal therefore dominates the sum of cross terms, leaving a
strictly positive coordinate product. This proves the global P-condition
from page 16. Two VI solutions are impossible, including boundary
solutions. The proof does not need compactness of the whole price domain;
finite bounds will be used separately for existence.

### Page 28: existence is a separate argument

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

### Page 29: check the running example

Differentiate logit log demand. The first own derivative is minus
(one minus the share); the second own derivative is minus Q_i times
one minus Q_i. This verifies E1. A cross second derivative is Q_i Q_j,
verifying E2 for each rival and the outside option.

When all prices rise by t, every exponential weight receives the same
factor exp(−t). It cancels in each share, verifying E3. These calculations
connect the abstract hypotheses to a familiar demand model. The general
proof did not require the explicit logit formula after the hypotheses
were established.

### Page 30: a feasible equilibrium and symmetry

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

### Page 31: the same market under different price bounds

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

### Page 32: why the transformation matters for the test

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

### Pages 35–38: CES derivative and the threshold statement

Page 35 derives the best response from the quadratic own-action cost.
The unnormalized CES aggregate enters linearly in own action. Maintain
positive baselines and a connected nonempty undirected network throughout
this block. Page 36 introduces the log system; the current deck has no
separate CES-parameter comparison slide.

The log comparison preserves signs on positive quantities, and the log
change of variables is one-to-one. Every equilibrium is positive because
each baseline is positive. Thus no equilibrium is lost.

Page 37, "CES uniqueness: the transformed derivative," defines the CES
aggregate $S_i$ and displays W with nonnegative entries and row sums
strictly below one. The current slide contains the derivative, not the
following proof. If the group wants the conditional-uniqueness argument,
work it through orally or at the board. The row bound does not supply a
single contraction constant below one
over all of log-action space. For two proposed finite roots, however,
their joining segment is compact. Continuity and the strict row bounds
give a common constant alpha below one on that segment, yielding the
contradiction in the infinity norm. This establishes at most one root
for any positive delta and beta, not existence for every such pair.

Page 38 states the additional conclusions of Theorem 4, with
$\bar\delta=\lambda_{\max}(G)^{-1/\beta}$. Below the threshold there is a
unique positive equilibrium with monotone comparative statics. Actions
diverge as delta approaches the threshold, with the stated Perron ratios.
Part (iii) excludes finite positive equilibria above the threshold, and
appendix Claim 2 also excludes equality. These existence, non-existence,
and limiting-ratio arguments require the paper's appendix, pp. 47–49.
They are not proved on the current slides. The optional derivative-based
argument above establishes conditional uniqueness only.

If the group asks how an invertible algebraic system can fail to give an
economic equilibrium, use the two-node check on page 52. Above its
threshold the unique algebraic solution is negative. This backup is a
feasibility illustration, rather than the general proof of Theorem 4.

### Pages 40–44: best responses, inverse domains, and a potential

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

### Pages 45–48: economic conclusions and their exact assumptions

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
   an at-most-one statement. Theorem 4 states that the number of feasible
   finite roots above the threshold is zero, which is consistent with
   conditional uniqueness. Its existence and non-existence proofs are
   reading material in the paper's appendix.
8. **Does the failed original matrix test imply multiple equilibria?** No.
   In the worked example, it fails at $(2+\ln2,3)$ with determinant $-2$,
   yet SET exposes a global P-matrix certificate. The game has the explicit
   unique equilibrium $(2,1)$, without a potential argument. The original
   test was sufficient, so its failure alone could not establish multiplicity.
9. **Why not take the inverse marginal benefit on all nonnegative effort?**
   The cost derivative need not lie in the range of b' everywhere, especially
   when c'(0)=0. The equilibrium-containing box checks and repairs the
   domain before the transformation; it does not discard equilibria.
10. **Does every strictly convex cost automatically satisfy the spectral
    uniqueness test?** No. The test is sufficient, and added cost curvature
    can help beyond it. The complete-network argument proves uniqueness
    directly even when the simple strict spectral inequality is at equality.
11. **Why not use a weighted norm to make the best responses contractive?**
    At $(2,1)$ their derivative has spectral radius $\sqrt2>1$. Every
    induced matrix norm, including weighted norms, is at least that radius.
    Thus no fixed vector norm gives a local contraction there. Uniqueness
    does not require contraction. This example takes the matrix branch of
    Figure 1 and does not introduce a potential.
12. **Does the paper establish a general convergent adjustment process?**
    Not from these arguments. The uniqueness and potential calculations
    here do not establish a general dynamic-stability theorem. Any proposed
    best-response or gradient adjustment rule needs its own analysis.

## Precision reminders

- The general NE–VI argument here uses own-payoff concavity. Do not replace
  it with an unrestricted assertion that quasi-concavity alone makes
  stationary first-order conditions sufficient.
- In the worked example, the original determinant is $-2$ at $(2+\ln2,3)$.
  Its global P-matrix certificate fails, while the transformed certificate
  succeeds everywhere on the feasible domain. Failure of the original
  sufficient test alone says nothing about equilibrium multiplicity.
- The worked example uses SET 2 with $h(t)=\sqrt t$ on strictly positive
  arguments. The transformed principal minors are $1$, $1$, and
  $1+2x_2e^{2-x_1}\geq1$. Its derivative is not symmetric; no potential is
  used. The feasible zero $(2,1)$ supplies existence on the unbounded
  orthant, and the matrix certificate supplies uniqueness. Its original
  best-response map has spectral radius $\sqrt2$ at that point and is not
  a contraction in any fixed vector norm, even locally.
- For oligopoly, desired markup is an inverse semi-elasticity. Positive
  rescaling preserves all coordinate signs. Strict log-profit concavity,
  rather than generic profit concavity, justifies the pricing conditions.
- A pointwise Jacobian P-matrix certificate, the global P-condition, and
  injectivity are related but distinct statements. The direct dominance
  proof supplies the precise global inequality used here. Arbitrary
  averages of P-matrices need not remain P-matrices.
- Connectedness and positive baselines are explicit in the CES discussion.
  The main slides display the derivative underlying conditional uniqueness;
  the separate notes explain that argument. Theorem 4's existence threshold
  and limiting ratios are stated, with those proofs left to the paper's
  appendix. The ratio limit does not describe a finite equilibrium at the
  threshold.
- The public-good potential is used on the valid equilibrium-containing
  box. The deck consistently uses convex minimization; negating the
  potential changes to a maximization convention without changing the
  economic equilibrium problem.
- Separate equilibrium-set preservation, existence, uniqueness,
  participation, and rankings. The last two can hold at every equilibrium
  even when uniqueness is not assumed.
