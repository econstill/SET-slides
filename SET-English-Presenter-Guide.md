# SET: English seminar presenter guide

Paper: Yves Zenou and Junjie Zhou, *SET*, February 17, 2026.

Deck: **54 PDF pages**, comprising **47 main pages including the title**, **6 proof/example backups**, and **1 reference page**. All slides and notes are in English. Page numbers below refer to PDF pages, not the smaller Beamer frame number in the slide footer.

## Timing options

The detailed main-slide notes sum to **81.5 minutes**. These are pacing estimates, not a script-reading requirement. Leave time for discussion and rehearse the algebraic passages aloud.

- **About 90 minutes:** present the complete main deck (roughly 80 minutes), then use questions or one selected backup proof.
- **About 75 minutes:** omit PDF pages 9, 17, 21. The remaining notes total 75.5 minutes. These omissions remove the square/disk worked example, the additional nonlinear-best-response curvature example, and the broader-applications survey. The main equivalence result, production application, CES proofs, and public-goods results remain.
- **About 60 minutes:** omit PDF pages 8, 9, 10, 14, 15, 17, 18, 19, 20, 21. This leaves 62 minutes at the detailed pace. Keep the opening/roadmap and closing to about four minutes combined to reach approximately 60 minutes. This route omits the auxiliary payoff-scaling example and production-network extension while retaining the core SET method, CES existence/uniqueness, centrality, and substitutes.

## Main-deck map

| PDF pages | Topic | Suggested time |
| --- | --- | --- |
| 1–3 | Opening and motivation | 4 min |
| 4–17 | SET theory and proof tools | 28.5 min |
| 18–21 | Production networks and other applications | 7 min |
| 22–37 | CES complements, centrality, and key players | 27 min |
| 38–45 | Strategic substitutes and public goods | 12 min |
| 46–47 | Synthesis and discussion | 3 min |

## Optional backup slides

- PDF 48: a formal coordinate proof of Theorem 1 (2 min).
- PDF 49: matrix tests in the payoff-scaling example (2 min).
- PDF 50: the nonlinear Perron limit (3 min).
- PDF 51: algebraic solutions and positive equilibria (2 min).
- PDF 52: complete-network uniqueness without the strict spectral bound (2 min).
- PDF 53: why the hub contributes less in a star (2 min).

Use the formal coordinate proof for questions about corners, the matrix-test comparison for questions about monotonicity versus P matrices, and the normalized Perron proof for questions about convergence of ratios. The complete-network and star proofs directly explain the public-goods rankings.

## Presentation conventions

- The connected-network assumption is explicit for the Perron-limit statements.
- “At most one” is separate from existence. The CES model uses a separate bounded-iteration proof.
- The substitutes section uses the convex-minimization potential, the negative of the paper's equation (50).
- Inverse transformations require appropriate ranges or justified endpoint extensions.
- The path-network curves and the two-agent invertibility example are teaching calculations, not empirical findings from the paper.
- To recompile the editable source, run XeLaTeX twice. The source is self-contained, with no external figures or bibliography file. Speaker notes are stored in \talknote commands.

## Slide-by-slide speaker notes

### PDF 1: SET: title and opening

Suggested time: 1 min.

This seminar studies the February 17, 2026 version of SET by Yves Zenou and Junjie Zhou. The organizing question is how an equilibrium system can be rewritten without changing its economic solutions. We first establish the equivalence principle, then use it to understand nonlinear network games. The spectral discussion connects the paper to the familiar equation $(I-\delta G)x=b$. A detailed delivery takes approximately 80 minutes. The presenter guide gives a shorter route, and backup slides provide additional proofs for questions.

### PDF 2: The representation of an equilibrium system

Suggested time: 2 min.

Introduce representation dependence with a simple observation: multiplying one player's payoff by a positive constant leaves all choices unchanged, but changes the Jacobian of the game. A uniqueness test based directly on that Jacobian can therefore be unnecessarily restrictive. SET formalizes a larger family of transformations. The interesting part is both mathematical and economic: preserve corner solutions, expose tractable structure, and obtain new results in models where direct linear algebra is unavailable. This is a methodology paper, but its new network applications are substantive results rather than illustrations alone.

### PDF 3: Plan of the seminar

Suggested time: 1 min.

Give the audience the logical map. The first part explains why a transformation is legitimate. The second explains why it is useful. The CES model then combines uniqueness from SET with a separate spectral existence argument. The last application shows that similar transformations also work with strategic substitutes, but the economically relevant eigenvalue and the implications for activity rankings change. We will distinguish equilibrium equivalence, existence, uniqueness, and dynamic stability throughout.

### PDF 4: Nash equilibrium as a variational inequality

Suggested time: 2 min.

Begin with a player's one-dimensional maximization problem. Own-action concavity makes the first-order inequality sufficient as well as necessary. Summing the individual inequalities gives the displayed VI. Conversely, a deviation in just one player's action recovers that player's condition. Explain the minus sign in F: positive F means marginal payoff is negative, so the player wants to reduce the action. The paper sometimes calls F the game Jacobian. Here F denotes a vector-valued operator and $J_F$ denotes its actual derivative matrix. This distinction matters when we later transform F and study the new matrix.

### PDF 5: Boundary optimality on a rectangular domain

Suggested time: 2 min.

Spend time on the direction of each inequality. At the lower bound, only an upward deviation is feasible, so a nonpositive marginal payoff supports optimality. At the upper bound, only a downward deviation is feasible, so a nonnegative marginal payoff supports optimality. At an interior point both directions are feasible and the marginal payoff must vanish. The complementarity conditions on the nonnegative orthant combine these cases in familiar notation. The magnitudes of the nonzero marginal incentives never enter these coordinate conditions. This observation is the entire reason that preserving their signs can preserve equilibrium.

### PDF 6: Sign equivalence

Suggested time: 1.5 min.

The object whose sign we preserve is a component of the operator, not an entry of its derivative matrix. In particular, we do not require the same strategic-complement or strategic-substitute classification of all derivative entries after transformation. The requirement also extends beyond a proposed solution. Checking that two systems vanish at a single candidate would not establish the theorem. Sign equivalence permits substantial changes to the analytic representation while preserving positive, negative and zero incentives coordinate by coordinate. This freedom allows a difficult original operator to have a transformed representation with useful curvature or matrix properties.

### PDF 7: Theorem 1: equilibrium-set preservation

Suggested time: 2 min.

State the two conclusions distinctly. At an interior point the VI simply requires F to equal zero, so preserving zeros suffices without any rectangularity restriction. At the boundary, the allowed deviations depend on the geometry of the feasible set. Rectangularity gives the stronger conclusion that every solution, including corners, survives the transformation. The theorem equates sets, so it preserves multiplicity as well as uniqueness when its hypotheses hold. It does not create an equilibrium if both solution sets are empty. Infinite endpoints allow economically familiar domains such as the whole Euclidean space and the nonnegative orthant.

### PDF 8: Why the coordinate argument works

Suggested time: 2 min.

This proof is short enough to present completely. First isolate one coordinate by holding all others fixed. The product structure guarantees that the deviation remains feasible. The resulting inequality depends on which directions t minus $x_i$ can take and on the sign of $F_i$, but never on its size. Replacing $F_i$ with its sign-equivalent component therefore preserves the inequality for every feasible t. Finally, apply those inequalities at the coordinates of an arbitrary feasible vector and add them. Emphasize the single place rectangularity enters: it licenses the isolated coordinate deviations. A coupled constraint may prevent those deviations.

### PDF 9: A square and a disk

Suggested time: 2 min.

The quadratic potential makes this example transparent. Both ideal coordinates equal two, outside either feasible set. On the square the agent can move both coordinates to one without a tradeoff, so every positive weight a gives the same corner. On the disk the two coordinates compete for the radius budget. Increasing a raises the penalty for missing the target in the first coordinate and shifts the optimum toward that axis. Strict convexity gives a unique solution for each a. All these solutions lie on the boundary, so the example leaves the interior part of Theorem 1 intact.

### PDF 10: Theorem 2: the domain restriction is substantive

Suggested time: 2 min.

Explain the quantifier in the theorem. Rectangularity is necessary for a domain to preserve solutions under every sign-equivalent transformation. It does not mean every transformation fails on every nonrectangular domain. A common positive scalar multiplying the whole operator, for example, preserves the VI on any domain. The problem comes from arbitrary componentwise transformations when the feasible directions are coupled. A game with separate scalar action intervals has a rectangular joint action set, whereas a shared resource constraint creates a different geometry. We state the nondegenerate full-dimensional version here, avoiding lower-dimensional domain conventions that require separate treatment.

### PDF 11: SET1: positive componentwise rescaling

Suggested time: 2 min.

The strict positivity requirement is essential. A zero scale could manufacture a new zero, while a negative scale would reverse an incentive. Constant scales recover familiar weighted-gradient methods. Allowing profile-dependent scales is more flexible and also changes derivatives through the product rule. The extra term $F_i$ times the gradient of $\alpha_i$ is easy to overlook. Increasing transformations of a player's payoff provide a natural economic example and preserve pure-strategy preferences directly. If the transformed payoff loses own-action concavity, do not infer its Nash characterization solely from a concavity-based VI lemma. The original VI transformation remains valid through sign equivalence.

### PDF 12: SET2: monotone transformations of a difference

Suggested time: 2 min.

Use a simple scalar comparison to explain this operation. An increasing h preserves the ranking of A and B and therefore preserves the sign of their difference. A decreasing h reverses the ranking, so we must reverse the order of the transformed terms. This is especially important when an inverse marginal-benefit function is decreasing. The logarithm is useful when both terms are positive because it exposes ratios and elasticities. All transformed arguments must lie in the function's domain. Composing valid operations gives another valid transformation, which lets us combine rescaling, inversion and logarithms in the later applications.

### PDF 13: Uniqueness tools after transformation

Suggested time: 2 min.

The transformed operator gives us access to familiar tools. Strict monotonicity rules out two different VI solutions by adding their defining inequalities. The P-matrix route can succeed when the symmetric part of a derivative matrix fails the monotonicity test. A symmetric derivative matrix permits integration on the convex domain, and positive semidefinite curvature connects the VI to convex minimization. Keep the logical distinction between at most one and exactly one. A strictly convex function on an unbounded domain need not attain its infimum. Strong monotonicity or suitable coercivity can supply existence under the usual continuity and closed-domain assumptions.

### PDF 14: Payoff scaling leaves equilibrium unchanged

Suggested time: 2 min.

This example isolates the difference between an economic property and a sufficient analytic test. Multiplying player 2's entire payoff by a positive number cannot change best responses. The equilibrium equations remain $x_1$ equals one plus delta times $x_2$ and the symmetric counterpart. Their positive solution in the standard complementarity region delta below one is one over one minus delta for both players. The original derivative matrix is symmetric positive definite in this region. By dividing the second component of the scaled operator by kappa, SET immediately recovers that representation. No condition on the payoff measurement unit is economically warranted.

### PDF 15: Why a direct monotonicity test can be restrictive

Suggested time: 2 min.

For a linear operator, the antisymmetric part contributes nothing to the quadratic form that defines monotonicity. Thus we check S, whose first diagonal element is positive and whose determinant yields the displayed bound. The arithmetic-geometric mean inequality makes the bound at most one, with equality only at kappa equals one. It approaches zero as kappa approaches zero or infinity, even though the equilibrium is unchanged. Be precise about the comparison: this demonstrates a limitation of the unweighted direct monotonicity test. The scaled matrix still has positive principal minors for delta below one, so the P-matrix test succeeds here as well.

### PDF 16: Theorem 3: inversion and a network potential

Suggested time: 2.5 min.

The key step isolates all cross-player terms in a linear network expression. Once we invert $R_i$, the only own-action term is $q_i$, while the off-diagonal derivatives become minus delta times $g_{ij}$. Symmetry of the undirected network makes those cross derivatives symmetric, giving the displayed potential. This argument concerns zeros and hence interior solutions. If an $R_i$ is decreasing, applying its inverse reverses the sign of the original difference, although it preserves zeros. Therefore the displayed gradient cannot automatically replace the original operator at a boundary. Finally, a stationary point need not minimize the potential. Curvature supplies that additional conclusion.

### PDF 17: Nonlinear best responses and spectral curvature

Suggested time: 2.5 min.

In the original representation the derivative of player i's response depends on i's exposure, so cross derivatives generally differ across players even on an undirected graph. Inversion removes that asymmetry. The lower bound on D dominates the largest eigenvalue of the interaction matrix: for any vector z, the Hessian quadratic form is at least the lower bound on D minus delta $\lambda_{\max}$, times the squared norm. This delivers strong convexity. Check the inverse's range and establish existence separately in the chosen domain. For a linear response $v_i$(z) equals $a_i$ plus z, D equals the identity and the familiar condition delta $\lambda_{\max}$ below one reappears.

### PDF 18: CES production networks

Suggested time: 2 min.

The production network differs from a strategic network game, but the same transformation principle applies to its equilibrium equations. The coefficients describe which industries buy inputs from which suppliers. The model combines a labor share with a CES aggregate of intermediate inputs. I display the resulting unit-cost equation rather than the full input-demand derivation. Positive labor shares matter because part of each industry's cost comes from the exogenous wage. The displayed expression covers industries with intermediate inputs. A pure-labor industry's price equals the wage divided by its productivity.

### PDF 19: Log SET and the row-sum bound

Suggested time: 2 min.

Taking logarithms of the two positive sides preserves the sign of their difference. Replacing prices by relative log prices is a separate, one-to-one change of coordinates. Differentiate the transformed equation and inspect a row of W. Its entries are nonnegative and sum to one minus the labor share, uniformly over all log prices. Every principal submatrix of I minus W inherits strict diagonal dominance, which gives the P-matrix argument. The same uniform bound makes the fixed-point map a contraction on all of real space, establishing existence as well as uniqueness.

### PDF 20: Cobb--Douglas and the Leontief inverse

Suggested time: 1.5 min.

The Cobb--Douglas limit anticipates the centrality discussion to follow. The Leontief inverse and the Bonacich inverse share the same algebraic structure. Their economic meanings differ. Here x denotes prices relative to wages in logarithms, and a productivity improvement enters with a negative sign. A positive productivity shock lowers the firm's own log price and can lower prices at downstream firms. Each additional power of A follows another round of input dependence. Labor shares keep the spectral radius below one, so the series converges without a separate free interaction parameter.

### PDF 21: Other applications of SET

Suggested time: 1.5 min.

These examples show how broadly the method applies while keeping the conclusions separate. The peer-effects result proves uniqueness conditional on existence. In pricing, a positive rescaling preserves boundary conditions even when price caps or floors bind. The demand restrictions then deliver the P-property. The income-dependent public-good model uses an inverse Engel curve to recover symmetric cross derivatives on an undirected network. The multiplex application also yields a potential, with curvature depending on additional restrictions. None of these examples turns equilibrium existence or strict convexity into an automatic consequence of sign equivalence.

### PDF 22: CES peer effects on an unnormalized network

Suggested time: 1.5 min.

The quadratic private cost makes own-action optimization straightforward even though peer aggregation is nonlinear. The best response is always positive because the baseline a is positive. The adjacency matrix is not row normalized, so an additional neighbor raises the aggregate peer input. This differs importantly from an averaging model. We impose connectedness explicitly because the limiting ratios later use a strictly positive Perron vector. In disconnected networks, the component with the strongest amplification need not describe the asymptotic behavior of every other component.

### PDF 23: What the CES parameter changes

Suggested time: 1.5 min.

Use two neighbors with different action levels to explain beta. The derivative ratio isolates relative influence because the common aggregate term cancels. This gives a clean economic interpretation without claiming that beta simply increases total spillovers. The aggregate is unnormalized: even if every neighbor chooses the same action x, a degree-d player receives peer input d to the power one over beta times x. Thus changing beta affects both relative sensitivity and total input. Keep delta fixed when discussing beta, and check whether the resulting parameters remain below the existence threshold.

### PDF 24: A log transformation of the equilibrium conditions

Suggested time: 1.5 min.

Separate the two operations carefully. First, compare two positive quantities through an increasing logarithm. That is the sign-equivalent transformation. Second, use logarithmic coordinates, which is a variable change and not itself the definition of SET. All equilibria lie in the positive orthant, so the new coordinates lose no equilibrium. The benefit of this representation appears in its derivative: logarithms turn the nonlinear interactions into weights whose row sums have a particularly simple expression.

### PDF 25: The transformed Jacobian and uniqueness

Suggested time: 2 min.

The second factor is the share of neighbor j in the CES sum and adds to one. The first factor is the fraction of the best response due to peers, strictly below one because the baseline is positive. This yields a nonnegative matrix with row sums below one at each finite point. Explain that every principal submatrix also has spectral radius below one, giving positive principal minors for I minus W. Crucially, the row-sum slack can disappear along unbounded sequences. Uniqueness therefore holds even in parameter regions where a finite equilibrium does not exist.

### PDF 26: The spectral existence threshold

Suggested time: 1.5 min.

State the theorem before proving it. The regular-network example makes the threshold transparent: peer input is d to the power one over beta times the common action. A positive finite fixed point needs the feedback coefficient below one. In an irregular graph, the Perron eigenvalue replaces the common degree. The theorem statement in the draft uses a strict inequality in its nonexistence part, but its proof also excludes equality. We therefore state the sharpened closed-threshold version, with the source of that detail visible in the citation.

### PDF 27: Why the threshold is necessary

Suggested time: 2 min.

Walk through every inequality. At equilibrium, x minus a equals the peer term. Raising positive components to beta preserves strict order because beta is positive. Since a is positive, x minus a is strictly below x. The positive left Perron vector aggregates the componentwise inequality without losing strictness. Symmetry lets us use the same vector as a left eigenvector. Divide by the positive scalar e transpose x to the beta. This proof explains why mere invertibility of a transformed expression is insufficient: the economics requires a finite positive fixed point.

### PDF 28: Existence through a Perron upper bound

Suggested time: 2 min.

The unbounded strategy space prevents an immediate appeal to a compact-domain fixed-point theorem. The Perron vector constructs the relevant compact order interval endogenously. Verify that T maps a upward and maps z downward. Monotonicity then traps every iterate between a and z. Componentwise monotone convergence and continuity give a fixed point. The paper iterates downward from the upper bound; iterating upward from a gives the same conclusion and, by uniqueness, the same limit. Existence and uniqueness use different arguments, which is one of the main methodological lessons.

### PDF 29: Comparative statics below the threshold

Suggested time: 1.5 min.

The comparative statics follow without explicitly differentiating a nonlinear inverse. Starting at the old equilibrium, larger baselines or stronger spillovers move the first best response upward. Subsequent iterations remain ordered and converge to the new equilibrium, provided the new parameters remain in the existence region. The payoff identity follows by substituting the best-response condition into utility. It preserves the familiar linear-quadratic relationship between action and equilibrium payoff, even though the action profile itself now reflects nonlinear aggregation. Avoid interpreting the theorem as a general monotonicity result in beta.

### PDF 30: Bonacich centrality as the linear special case

Suggested time: 1.5 min.

This slide answers the original matrix question directly. The vector on the right is an exogenous input, while x is the endogenous response after all rounds of peer feedback. An eigenvector solves a homogeneous proportionality equation, whereas Bonacich centrality solves an inhomogeneous fixed point. These are different objects for a generic delta. The relationship emerges because the inverse amplifies each eigenvector direction by a different factor. We will first give the walk interpretation, then diagonalize the inverse to identify those factors.

### PDF 31: Walks, invertibility, and amplification

Suggested time: 1.5 min.

Explain the first few terms as baseline, direct-neighbor feedback, and feedback through two steps. Walks, rather than simple paths, are essential because feedback can return to the same agent. Invertibility alone excludes isolated poles, while convergence restricts an entire parameter interval. Above the positive threshold the inverse may exist algebraically but cannot deliver the positive equilibrium required by the game. This distinction is often hidden when the equilibrium is written only as an inverse matrix. A two-node example in the backup slides makes it explicit.

### PDF 32: The inverse acts separately on each eigenvector

Suggested time: 2 min.

Apply I minus delta G to a single eigenvector: the result is one minus delta lambda times that vector. Inverting therefore scales the same direction by the reciprocal. Since a symmetric adjacency matrix has an orthonormal eigenbasis, any baseline can be decomposed into these directions and the equilibrium follows term by term. This gives the exact relationship to Ax equals lambda x. At ordinary parameter values several directions matter. As delta approaches the positive spectral threshold, only the principal direction has an unbounded amplification factor.

### PDF 33: Eigenvector centrality at the critical limit

Suggested time: 2 min.

In the linear model, positivity of a ensures a positive projection onto e, so the diverging principal component cannot disappear. In the nonlinear model, large equilibrium actions make the fixed baseline negligible relative to the peer term. Raising actions to beta yields an asymptotic eigenvector equation. Connectedness makes the positive Perron direction unique up to scale. Explain that the limit is a statement about relative actions, not a finite equilibrium at the threshold. A normalized subsequence proof is available in the backup slides if the audience asks why the ratios actually converge.

### PDF 34: A three-node path: an exact nonlinear example

Suggested time: 2 min.

The three-node path is useful because the nonlinear problem collapses to two linear equations once symmetry is imposed. Each endpoint has only one neighbor, so its CES aggregate equals the center action. The center has two identical neighbors, giving the factor two to the power one over beta. Solve the two equations directly and inspect the common denominator. It vanishes precisely at the general spectral threshold. The numerator ratio has a finite limit, even though both actions diverge. This is a constructed teaching example rather than a reported table from the paper.

### PDF 35: Relative actions along the path

Suggested time: 1.5 min.

The horizontal axis is normalized by the beta-specific threshold. This is not a comparison at a common absolute delta. All curves begin with equal actions when spillovers vanish, then separate as network amplification matters more. The limits are two, square root of two, and the fourth root of two. Emphasize the difference between divergence of levels and convergence of a ratio. This graph also shows why eigenvector centrality is a limiting description: away from the threshold, the baseline still matters, and the ratio differs from its limiting value.

### PDF 36: The key-player intervention

Suggested time: 1.5 min.

Define the counterfactual before showing the network. The total loss contains the removed player's direct contribution and the endogenous response of all remaining agents. In the linear model an intercentrality expression can summarize the intervention, but that formula does not directly carry over to the nonlinear CES model. The paper instead removes each player and resolves the equilibrium. Removing a node weakens the network, so parameters that support equilibrium in the original graph also support the componentwise problems after removal, including isolated agents who simply choose their baseline.

### PDF 37: A bridge can matter more than the most active player

Suggested time: 1.5 min.

Explain the three structural types before interpreting the table. Node one links two complete groups, whereas type-two nodes have more direct links and exert more effort. Yet the bridge becomes more important when feedback is strong. The nonlinear result adds another determinant: changing peer aggregation can change the key-player type even with delta fixed. The numerical switch near point seven two two is a reported calculation over the paper's admissible interval, not a general closed-form threshold. This connects equilibrium characterization to policy while retaining the distinction between individual centrality and intervention impact.

### PDF 38: Network public goods with nonlinear costs

Suggested time: 1.5 min.

This application changes the economic mechanism. Peers now supply a public good that substitutes for one's own effort. The parameter delta allows imperfect substitution, while a convex cost makes marginal effort increasingly expensive. Explain the marginal crossing conditions rather than calling them Inada conditions without qualification. They guarantee a unique positive autarky choice and will also bound every best response. The derivative restriction on costs applies on the positive domain. At zero, the later participation result explicitly allows c prime at zero to equal zero, as in the paper's Assumption 3. Throughout this application the network is undirected and agents share the same benefit and cost functions unless stated otherwise.

### PDF 39: Best responses, corners, and existence

Suggested time: 1.5 min.

The complementarity notation combines nonnegative effort, a nonnegative negative marginal payoff, and a zero product. A corner is optimal when peers already provide enough public good that the first unit of own effort has no positive net return. The derivative calculation shows strategic substitution directly and also shows how cost curvature attenuates the response. For existence, no spectral bound is needed here. Since peers supply nonnegative effort, an agent never wants more than the autarky amount. Strict own concavity gives a unique continuous best response, and the compact invariant box yields a fixed point. This separates the existence argument from the uniqueness argument that follows.

### PDF 40: A decreasing inverse produces a symmetric system

Suggested time: 1.5 min.

Walk through the sign calculation slowly. Applying a decreasing inverse reverses the order, so the transformed residual is total provision minus the target h. The order matters for corners, even when both sign choices would have the same interior zeros. The original cross derivatives depend on each player's total provision and need not match. The transformed cross derivatives are simply delta times the adjacency entries. The inverse must exist for the marginal-cost values under consideration. If an endpoint produces an infinite inverse or lies outside its range, it needs a justified extension or restriction. The original complementarity formulation and the preceding existence proof do not depend on that inverse.

### PDF 41: A potential for the transformed equilibrium conditions

Suggested time: 1.5 min.

This is a potential for the transformed game, rather than a claim that the original marginal-payoff field was integrable. We use the negative of equation 50 so that its gradient equals the negative marginal-payoff operator and the optimization problem is minimization. This keeps the signs of the complementarity conditions consistent. A stationary point need not be a global minimizer without convexity, so make that qualification explicit. Additive constants in the antiderivatives have no effect. If the inverse diverges at zero, one must handle the antiderivative and the boundary carefully instead of writing a finite integral from zero automatically. The paper contains sign slips in the surrounding derivative statements.

### PDF 42: The smallest eigenvalue controls a uniqueness condition

Suggested time: 1.5 min.

Compare this result with the complementarity model, where the largest eigenvalue gave the amplification threshold. For strategic substitutes the smallest eigenvalue matters because the relevant matrix has a plus sign. The Hessian separates network geometry from the stabilizing curvature of private costs. Discarding the diagonal term gives the clean sufficient condition in Theorem 5. If curvature is uniformly large enough, uniqueness can survive even when this conservative bound fails. With linear costs the diagonal contribution vanishes, although failure of positive definiteness still must not be described as a universal theorem of equilibrium multiplicity. Existence comes from the bounded best-response argument, not from strict convexity alone.

### PDF 43: Zero marginal cost at zero implies full participation

Suggested time: 1.5 min.

The economic reason for full participation is local. When own effort is zero, its marginal cost is zero but its marginal benefit remains strictly positive at any finite provision level. An agent can therefore improve by contributing a small positive amount. This rules out every zero-effort component of an equilibrium, regardless of whether the equilibrium is unique. Strict convexity and the zero derivative at the origin describe the maintained environment for the following ranking results. The full-participation argument itself also works for other nonnegative substitution intensities, but the slide follows the paper's delta-equals-one proposition so that the subsequent complete-network and neighborhood results use a common setup.

### PDF 44: Complete networks: convex costs remove the continuum

Suggested time: 1.5 min.

This example shows both the economic role of cost curvature and the limits of a sufficient spectral test. In a complete graph everyone enjoys the same total provision. With strictly convex costs, equal marginal benefits require equal marginal costs and hence equal own efforts. The scalar marginal crossing then pins down a unique equilibrium. Under linear costs, marginal cost is the same for everybody regardless of effort, so only total provision matters. Any nonnegative allocation of the autarky total is an equilibrium, including full specialization. Do not interpret failure of the strict spectral inequality as nonexistence or multiplicity here. The direct equilibrium argument proves uniqueness in the convex-cost case.

### PDF 45: Network structure determines effort rankings

Suggested time: 1.5 min.

The ranking follows from comparable neighborhoods, not from degree counts by themselves. For open-neighborhood inclusion, positive efforts give the larger neighborhood a strictly greater peer contribution and the best-response function is decreasing. For closed-neighborhood inclusion, compare total provision and then invert the strictly increasing marginal-cost function. A star gives the most transparent illustration. Every leaf has the same peer contribution, while the hub benefits from all leaves and contributes less. Nested split graphs extend this logic because their neighborhood structure supports the required comparisons. These statements hold at every equilibrium and do not presume uniqueness. The appendix of the draft contains reversed inequality typos in the last step of the closed-neighborhood and corollary proofs.

### PDF 46: What SET preserves, and what must still be checked

Suggested time: 1.5 min.

Return to the distinctions made at the start. SET certifies equality of solution sets under specified conditions. It does not make every transformed problem easy, and it does not prove existence without additional structure. Symmetry gives an integrable field; curvature determines whether that field defines a convex minimization problem. Finally, two vector fields can have the same equilibria while generating different trajectories. The bounded best-response iteration used in the CES existence proof is a specific convergent construction, not a blanket stability claim about every adjustment process.

### PDF 47: Main conclusions

Suggested time: 1.5 min.

End with the central methodological question rather than a list of applications. The paper provides an equivalence principle and a set of constructive operations, but finding a helpful representation still requires economic and mathematical insight. Highlight the two spectral roles: the largest eigenvalue limits positive feedback, while the smallest eigenvalue matters for curvature under substitution. Invite discussion about coupled constraints, directed networks, heterogeneous nonlinearities, or how one might search systematically for transformations. Backup slides give details for the proofs and the matrix-invertibility distinction.

### PDF 48: Backup: a formal coordinate proof of Theorem 1

Suggested time: 2 min (optional).

This backup supplies every step behind the earlier proof intuition. Take a solution of the first VI and vary one coordinate at a time. If its operator component is zero, sign equivalence makes the transformed component zero too. If the component is positive, every feasible displacement in that coordinate must be nonnegative. If it is negative, every feasible displacement must be nonpositive. In all cases the transformed coordinate product remains nonnegative. Sum over coordinates to obtain the transformed VI. Since sign equivalence is symmetric, the same argument applies in reverse. No continuity or derivative calculation enters this particular implication.

### PDF 49: Backup: matrix tests in the payoff-scaling example

Suggested time: 2 min (optional).

This comparison prevents an overly broad interpretation of the example. The original scaled matrix satisfies the P-matrix condition throughout delta below one, because its two diagonal entries and determinant are positive. Its symmetric part can fail positive definiteness inside that same region, producing the more restrictive unweighted monotonicity bound. The explicit eigenvalue expression comes from the two-by-two symmetric-matrix formula. Positive diagonal rescaling removes the payoff units and restores a symmetric derivative with eigenvalues one minus delta and one plus delta. The example therefore compares available certificates of uniqueness, not different equilibrium sets or a necessary condition for all parameter values.

### PDF 50: Backup: the nonlinear Perron limit

Suggested time: 3 min (optional).

Monotonicity in delta implies that every component has a finite or infinite limit. A finite vector limit would solve the forbidden critical equilibrium system. Thus at least one component diverges. Along an edge the CES aggregate is at least the neighbor's action, so connectedness and delta bounded away from zero propagate divergence to all components. Normalize the beta powers to obtain a compact simplex. On any convergent subsequence, the baseline becomes negligible in the normalized equation. Perron irreducibility gives a unique nonnegative normalized eigenvector. This supplies the compactness and uniqueness steps implicit in the draft's ratio argument.

### PDF 51: Backup: algebraic solutions and positive equilibria

Suggested time: 2 min (optional).

This example isolates a common confusion. The inverse is well-defined for positive delta above one, except at the singular point, but its solution is negative. The game's best response is one plus delta times the neighbor's nonnegative action, so an admissible equilibrium must have both components strictly positive. No corner can rescue the system because each player has a strictly positive baseline. The spectral bound therefore reflects economic feasibility and finite feedback, not merely avoidance of singular matrices. For signed baselines or unconstrained algebraic systems the interpretation would differ.

### PDF 52: Backup: complete-network uniqueness without the strict spectral bound

Suggested time: 2 min (optional).

This proof avoids any issue about whether the inverse of marginal benefit is finite at zero. It works directly with the original first-order conditions and the full-participation result. Everyone has the same total public good in a complete network, so every agent faces the same marginal benefit. Strictly increasing marginal costs then imply symmetry. Finally, the common-effort equation has exactly one solution by monotonicity and the assumed marginal crossing. This is also a useful response to the question of whether Theorem 5 is necessary. The complete graph at delta equal to one lies exactly on the boundary of that sufficient spectral test, while nonlinear costs still pin down a unique equilibrium.

### PDF 53: Backup: why the hub contributes less in a star

Suggested time: 2 min (optional).

This direct proof is often easier to present than the general neighborhood-ordering argument. Each leaf has exactly one neighbor, the hub, so all leaves face the same one-dimensional optimization problem. Strict own concavity gives a unique best response even if the overall game has multiple equilibria. Positivity follows from zero marginal cost at zero. The hub therefore receives strictly more total provision than a leaf when the star has at least three nodes. Since marginal benefit decreases with provision, the hub's equilibrium marginal cost is lower. A strictly increasing marginal-cost function turns that inequality into lower hub effort. The result concerns individual effort, not the hub's total benefit or its welfare contribution.

### PDF 54: References

Suggested time: 0 min (optional).

All substantive statements about SET refer to the local February 17, 2026 draft. The presentation uses a convex-minimization sign convention consistently in the potential-function applications. Some displayed signs and labels in the draft require this clarification, as noted on the relevant slides. The two-node and three-node examples are analytical teaching additions, not empirical results or numerical tables reported by the authors.

