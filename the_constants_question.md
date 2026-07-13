# The Constants Question: The Layered Structure of Mathematical Necessity

*Why the numbers that matter are few, where they come from, and what their unequal knowability reveals about necessity itself.*

---

## A Note Before We Begin

This document starts from a real observation and a genuine why-question. The observation: the real numbers are uncountable, yet the constants mathematics actually encounters — the numbers that recur uninvited across unrelated fields — form a thin, structured set, and each of them appears at a specific place: the point where one mathematical structure is forced to grow into another. The why-question: why is π the number it is — and why can that question be answered completely for π, only partially for ζ(3), not at all yet for γ, and provably never for Ω?

The standard philosophical position holds that mathematical necessity is flat: every mathematical truth, if true, is necessarily true, with no gradation — one modal status for all of mathematics. This document derives a different picture from the constants themselves. Constants are treated as specimens: each one is the residue left where a structural transition occurs — where ratios fail, where algebra closes, where limits complete, where computation ends. Read together, they exhibit a gradient: fully derivable at one end, provably unknowable at the other. Whether that gradient is merely epistemic (about our access) or ontological (about necessity itself) is the contested question this document engages and does not pretend to settle.

The document sits within The Universe as Experiment framework by relevance — it derives the mathematical floor beneath the parameter-space discussion of The Architecture of Novelty — but it uses no other Apeiron document as a premise. Every claim here stands or falls on its own derivation; a reader who rejects the cosmological framework entirely loses nothing of the argument. One remark at the end notes the connection; nothing in the derivation depends on it.

A discipline note, because this territory demands it: the neighborhood of "meaning of the constants" is dense with numerology. This document's method is the opposite: every claim about a constant carries its grounding level, every open conjecture stays open, and no numerical coincidence is treated as structure. The taxonomy makes commitments that live conjectures could break; those commitments are stated in the table.

---

## Part One: The Observation

Three facts, established here, are the data everything else interprets.

### Fact 1 — Thinness

Fix any formal language with countably many symbols. Only countably many real numbers can be defined by a finite expression in that language, because there are only countably many finite expressions. The reals are uncountable. Therefore, relative to any fixed language, almost every real number is undefinable: it can never be named, singled out, or encountered as an individual. The numbers mathematics can discuss at all are a set of measure zero. (The restriction "relative to a fixed language" is required; an absolute notion of definability is incoherent by the Richard paradox. Nothing below needs the absolute notion.)

Within this already-thin definable class, the constants of practice concentrate further. Kontsevich and Zagier (2001) observed that nearly every constant arising in mathematics belongs to the class of periods: complex numbers whose real and imaginary parts are values of absolutely convergent integrals of rational functions over domains defined by polynomial inequalities with rational coefficients. The class is countable and carries algebraic structure (it forms a ring). π is a period — the area of the unit disk. So are all algebraic numbers, logarithms of algebraic numbers, ζ(3), and the multiple zeta values. The observation is cited here because the derivation uses it as a load-bearing datum: the constants of practice are not merely definable, they cluster inside a single, mathematically characterized, countable class tied to algebraic geometry.

*Grounding: EMPIRICAL. The countability argument is elementary; the period observation is established literature.*

### Fact 2 — Location

Each major constant becomes expressible at a specific structural layer and is inexpressible in the layers below. π does not exist within the arithmetic of ratios: no rational number is π, and — stronger — no finite algebraic recipe over the rationals reaches it (transcendence, Lindemann 1882). A mathematical culture equipped with exact ratio arithmetic but no limit concept can bound π between rationals forever without ever possessing it, which is precisely the historical situation of Greek mathematics. At the far end, Ω is inexpressible in a stronger sense: no fixed axiomatic system determines more than finitely many of its bits, so no formal layer, however high, contains it fully.

This is not yet the thesis; it is a family of theorems. The thesis — that the layers form a forced ladder and the constants are its scars — is the work of Part Two.

*Grounding: EMPIRICAL for each individual inexpressibility result; the layer language is defined in Part Two.*

### Fact 3 — The Gradient

The epistemic statuses of the major constants are radically unequal, and the inequality is ordered. For √2 and φ, everything elementary is proven and has been for centuries or millennia. For π and e, irrationality and transcendence are proven, with residual open questions that are statistical (normality) or relational (the status of π+e). For ζ(3), irrationality was proven only in 1978 and transcendence remains open. For γ, not even irrationality is proven. For δ, existence was first proven only by computer assistance and nothing about its arithmetic nature is known. For Ω, unknowability is a theorem.

Individually, each status is a known fact — trivia, even. The datum this document names is the correlation: epistemic resistance increases with the structural depth of the transition the constant marks, monotonically, across the full table. Either this correlation is an artifact — of proof technology, of selection, of how "depth" gets defined — or it is tracking something real about the architecture of mathematical truth. That disjunction is the contested question of Part Four.

*Grounding: EMPIRICAL for the statuses; STRUCTURAL for the ordering claim, which depends on the ladder of Part Two.*

---

## Part Two: The Ladder

This part derives the layers. The discipline for each transition: name the lower structure, name the demand it cannot meet from within, show the demand is internal (posed in the lower structure's own terms, not imported), name the structure the demand forces, and identify the constant that appears as the scar. Each section closes with what the transition does not establish.

### L1 → L2: Ratios Fail Under Their Own Demands

The rational numbers are a complete answer to the problem of ratio. They are closed under addition, subtraction, multiplication, and division; between any two there is another; every counting relationship between whole quantities is expressible. A mathematics of commerce, calendar, and harmony never needs to leave ℚ.

The demand that breaks ℚ arises inside it. The Pythagorean theorem — a statement about rational operations on lengths — asks for a number x with x² = 2, the diagonal of the unit square. The proof that no rational serves is elementary parity descent: if (p/q)² = 2 in lowest terms, then p² = 2q², so p is even, so q² is even, so q is even, contradicting lowest terms. The question is posed in ℚ's own vocabulary; the answer does not exist there. The scar is **√2**: the first number forced into existence by a demand the existing number system generated but could not satisfy. It is algebraic of degree 2 — the mildest possible transcendence of the ratio concept, one polynomial step beyond.

What this does not establish: √2's absence from ℚ is algebraic, not metric. The transition shows ℚ cannot solve its own equations; it does not yet show ℚ has gaps in the sense of missing limit points. Those are independent failures, and the ladder branches accordingly.

### L2 → L3: Algebra Completes Itself

Adjoining √2 repairs one equation and immediately exposes the pattern: x² = 3, x³ = 2, x² = −1 each demand further extensions, and piecemeal adjunction never terminates. The internal demand is closure: a number system in which every polynomial equation has a full set of solutions, so that algebra never again generates questions it cannot answer.

The demand is satisfiable, and the satisfaction is remarkable for its economy. Over the reals, adjoining a single element — a root of x² = −1 — closes everything: the Fundamental Theorem of Algebra states that every non-constant polynomial with complex coefficients has a root in ℂ. One step, closed forever. The scar is **i**: the constant of algebra completed. It marks two things the later argument uses. First, that a transition constant need not be a magnitude — i is not a point on the number line but a new direction, showing that structural demands can force new kinds of object, not just new values. Second, that closure is cheap compared to what follows: it terminates in one move, and everything about i is fully understood.

What this does not establish: closure does not require the reals. The algebraic closure of ℚ alone exists — the countable field of all algebraic numbers — without any limit concept. Closure and completion are independent demands. The ladder is not a single file of rungs; it forks at L2, and the fork is essential to what π turns out to be.

### L2 → L4: Completion — The Limit Concept

The second, independent failure of ℚ (and of the algebraic numbers) is metric. Sequences of rationals can close in on a target with all the internal marks of convergence — the terms eventually crowd within any tolerance of each other — while no rational target exists. The internal demand: every sequence that behaves as if it converges should have something to converge to. Meeting it is the construction of the real numbers, and the result is unique: up to isomorphism there is exactly one complete ordered field. No dial is turned in the construction.

Completeness is not one more repair among many; it is a change of kind. Algebraic extension adds solutions to equations — finitely specifiable demands. Completeness adds destinations for processes — and thereby makes infinite processes first-class mathematical objects. Every constant from here up is a child of the limit.

The first scar is **e**. Define it as the limit of (1 + 1/n)ⁿ, or as the sum of 1/n!; the two agree, and the number exists only because completeness guarantees the limit a target. Its structural meaning is sharper than "a limit that exists": among all functions, exactly one equals its own rate of change with value 1 at 0, and e is that function's value at 1. Self-referential growth — a quantity whose change is governed by its own current size — becomes expressible exactly at this layer, and e is its unit. The irrationality proof is short (Fourier's argument from the factorial series); transcendence took until Hermite (1873) and marks the historical birth of transcendence technology.

What this does not establish: nothing yet about rotation, periodicity, or π. On the real line, exponential growth is monotone; it meets no circle.

### L5: The Junction — Where π Lives

The two branches — closure (L3) and completion (L4) — meet in one object: ℂ, the complete algebraically closed field containing ℝ. The exponential function, defined by the same power series that completeness licensed on the real line, extends to all of ℂ. And in the junction, something happens that neither branch could produce alone: the exponential map becomes periodic.

The derivation is short enough to give in full outline. The complex exponential is a homomorphism from the additive group of ℂ to the multiplicative group of nonzero complex numbers: exp(z + w) = exp(z)·exp(w). Its kernel — the set of z with exp(z) = 1 — is a closed discrete subgroup of ℂ, and every such subgroup is a lattice generated by a single element. That generator is 2πi. **π is, by this route, defined as a period: the fundamental repetition length that self-referential growth acquires when the number system is simultaneously complete and algebraically closed.** Growth along the real axis, rotation along the imaginary axis, one function; Euler's identity exp(iπ) = −1 is this single structure read at its half-period, not a bridge between two unrelated celebrities.

Now the answer to the document's opening question can be stated with its full force. Why is π that number? Trace every choice in the construction: ℚ is forced by counting; the completion of ℚ is unique (the one complete ordered field); the algebraic closure step is unique up to isomorphism; the exponential is unique (the one fixed point of differentiation, normalized); the kernel of a homomorphism is not chosen but found. There is no dial anywhere. π is the unique period of the one self-consistent growth map over the one complete closed number system. The question "why is π 3.14159... rather than something else" has the same answer as "why is the kernel what it is" — it is a theorem all the way down. This is what full derivability at a layer looks like, and it is the calibration point for the gradient: at L5, the why-question closes completely.

A control specimen belongs here: **φ**, the golden ratio. It is algebraic (root of x² = x + 1), so it lives at L2, but its structural meaning is self-similarity — the fixed point of x = 1 + 1/x, the ratio preserved under removal of a part. Its continued fraction is [1; 1, 1, 1, ...], all ones, and by Hurwitz's theorem this makes it extremal: the real number worst approximated by rationals. Everything about φ is proven and has been for a long time. Its role in the table is as a control against the deflationary reading of the gradient: φ is a constant *about* an infinite recursive process, yet fully resolved — showing that what drives epistemic resistance is not "involves infinity" or "is old," but the depth of the transition the constant marks.

What this does not establish: full derivability at L5 does not extend to every question *about* π. Whether π is normal — whether its digits are statistically uniform in every base — is open. The taxonomy's reading: the residual mystery is statistical, not structural; the *value* is fully forced, while the fine texture of its expansions is a question of a different kind, belonging to the measure-theoretic layer where Khinchin's constant lives — a typicality axis that cuts across the ladder rather than sitting on it.

### L6: The Seam and the Depths

Two constants mark the layer where the closed, fully-derivable world of L5 ends.

**γ**, the Euler–Mascheroni constant, is the residue of comparing counting against flowing. The harmonic sum 1 + 1/2 + ... + 1/n and the logarithm ln n both diverge, and their difference converges — monotonically, boundedly, hence by completeness to a target: γ ≈ 0.5772. It is the exact size of the mismatch between the staircase and the ramp, the constant of the discrete–continuous seam. And it is the first constant on the ladder about which mathematics can prove almost nothing. Not irrationality. Not transcendence. It is formally conjectured not to be a period of the Kontsevich–Zagier class at all (Lagarias 2013, Conjecture 1.0.2) — a conjecture that, if true, implies its transcendence — while it is expected to live in the extended class of exponential periods. The taxonomy's structural reading: seam constants resist because they belong wholly to neither side of the seam — the tools of arithmetic and the tools of analysis each capture one edge of the object. This reading is a hypothesis, and Part Four gives the deflationary alternative its full voice.

**ζ(3)** marks arithmetic depth. The zeta function ties analysis to the primes through the Euler product; its values at even integers collapse into the rotation lineage — ζ(2) = π²/6, ζ(4) = π⁴/90, all rational multiples of π-powers, a theorem of Euler and structurally a consequence of the periodicity at L5. The odd values do not collapse. No closed form for ζ(3) in lower constants is known; irrationality was proven only in 1978 (Apéry), a result so unexpected it was initially met with disbelief; transcendence is open; Rivoal (2000) proved infinitely many odd zeta values are irrational without being able to say which, and Zudilin (2001) narrowed one guaranteed irrational to the set {ζ(5), ζ(7), ζ(9), ζ(11)} — yet ζ(3) remains, to this day, the only individual odd zeta value proven irrational. The even/odd split is the cleanest available exhibit of a structure the L5 layer explains half of: the half it reaches collapses into π; the half it does not reach has resisted for 250 years.

What this does not establish: that γ or ζ(3) are *permanently* resistant. Apéry's proof is the standing warning — a constant can sit unprovable for centuries and fall to an elementary argument. The gradient is a present-tense fact about accumulated resistance, not a proof of future resistance. Only at L8 does resistance become theorem.

### L7: Universality — A Constant From Nowhere Below

Take the logistic map, or the sine map, or nearly any smooth map of an interval with a single quadratic hump, and drive it through its cascade of period-doublings toward chaos. The parameter intervals between successive doublings shrink geometrically, and the ratio converges — for every such map — to the same number: **δ** ≈ 4.6692 (Feigenbaum, 1975, discovered numerically). The mechanism is renormalization: the period-doubling operator on a space of functions has a fixed point, and δ is its expanding eigenvalue. Universality means the eigenvalue does not care which map you started with; entire families of dynamical systems share it the way entire families of statistical-mechanical systems share critical exponents.

δ's place in the taxonomy is unlike anything below it. Its existence is a theorem whose own proof history is a miniature of the layer: first established computer-assisted (Lanford 1982, corrected by Eckmann–Wittwer 1987) — rigorous, yet of a texture no human had surveyed unaided — and only later given a complete non-numerical proof (Lyubich 1999). The constant was certain seventeen years before it was humanly readable. Its arithmetic nature is blank: not known to be irrational, not known to be transcendental, and — the taxonomy's sharpest commitment — connected by no known relation to any constant on the lower rungs. π and e emerge from the completion of number itself; δ emerges from the space of *functions* under a renormalization flow. If the taxonomy is right that δ is genuinely independent — a new constant forced by logic in a different room of mathematics — then necessity is generating novelty at layers far above the number line, and the famous handful of constants is a vast undercount. If instead δ someday resolves into a closed form of lower constants, this row breaks, and the flat view gains its best exhibit: what looked like a new layer was a reducible artifact.

What this does not establish: independence is not proven; it is the absence of a known relation, upgraded to a commitment the table stakes out explicitly.

### L8: The Boundary — Where Unknowability Becomes Theorem

Fix a universal prefix-free Turing machine U. **Ω** is the probability that U halts on a random program: the sum of 2^(−|p|) over all halting programs p. It is a specific real number in (0,1), definable in one line. The following are theorems. Ω is uncomputable: no algorithm generates its digits. It is algorithmically random in the sense of Martin-Löf — its bit sequence passes every effective statistical test, and (unlike π, whose normality is open) Ω is *provably* normal. It is the limit of a computable increasing sequence of rationals, so it is constructible in the weakest sense while random in the strongest. And the decisive property: any consistent, recursively axiomatized formal system can determine at most finitely many bits of Ω. Not "has not yet" — can not, ever, by theorem.

At every rung below, an open status is a confession of present ignorance that Apéry-style surprise could overturn. At L8, and only at L8, the separation between *being a determinate mathematical fact* and *being knowable from any fixed system* is itself a mathematical fact — which is why the contested-question argument of Part Four anchors here. Whatever one's philosophy, necessity and knowability provably come apart at this layer. The only question Part Four leaves open is whether they come apart gradually below it or all at once here.

What this does not establish: Ω is machine-relative — different universal machines give different Ωs — so it is a family of constants, not one; the theorems hold for each. And the theorems do not license the strong interpretive reading sometimes attached to them (mathematics as quasi-empirical, the bits of Ω as brute facts refuting the axiomatic method). That reading is contested in the literature, the criticism is on the record, and nothing in this document uses it. The rows of the table rest on the theorems alone.

---

## Part Three: The Taxonomy

The table is the document's evidentiary core. Columns: the constant; the structural transition it marks; its epistemic status (theorem-level facts, individually checkable); and the commitments this taxonomy makes — live conjectures whose resolution would confirm or break the row's placement.

| Constant | Structural transition it marks | Epistemic status | Taxonomy's commitments (what would move this row) |
|---|---|---|---|
| **√2** | Ratios fail under their own algebraic demands (ℚ → algebraic extension) | Irrational: PROVEN (antiquity). Algebraic of degree 2: PROVEN. | None open — the settled floor the gradient is measured from. |
| **i** | Algebra completes itself (algebraic closure; Fundamental Theorem of Algebra) | Existence and closure: PROVEN. | None open. Marks that a transition constant need not be a real magnitude. |
| **φ** | Self-similarity has a fixed point; extremal badness of rational approximation | Algebraic: PROVEN. Extremal for rational approximation (Hurwitz): PROVEN. | None open. Control specimen (see L5). |
| **e** | Completeness admits self-referential growth (fixed point of d/dx) | Irrational: PROVEN (Euler 1737; simplified by Fourier). Transcendental: PROVEN (Hermite 1873). | CONJECTURED not a period. If proven: π and e are formally different species (geometric vs. exponential lineage), confirming the fork at L2. If e were shown a period, the two-lineage structure collapses and the L3/L4 fork loses its scar. |
| **π** | Growth meets rotation: period of exp at the junction of completion and closure | Irrational: PROVEN (Lambert 1761). Transcendental: PROVEN (Lindemann 1882). A period: PROVEN. | Normality: OPEN. Status of π+e, πe: OPEN. The taxonomy predicts π's residual mystery is statistical (the typicality axis), not structural: no obstruction to normality will turn out to be modal. |
| **γ** | Residue of the discrete–continuous seam (harmonic sum vs. logarithm) | Irrationality: OPEN. Transcendence: OPEN. CONJECTURED not a KZ-period (Lagarias 2013, Conj. 1.0.2), which would imply transcendence. | The taxonomy reads γ's resistance as structural — seam constants belong wholly to neither side. An eventual short proof using single-layer tools (pure arithmetic or pure analysis) would count against this placement. |
| **ζ(3)** | Arithmetic depth at odd weight — the structure even weights collapse into π-powers and odd weights do not | Irrational: PROVEN (Apéry 1978); the only individual odd zeta value proven irrational. Transcendence: OPEN. A period: PROVEN. Infinitely many ζ(odd) irrational: PROVEN (Rivoal 2000; Zudilin 2001). Whether ζ(3)/π³ is rational: OPEN. | The taxonomy predicts no collapse of odd weight into the rotation lineage: ζ(3)/π³ will prove irrational. A proven closed form in lower constants would move this row down the ladder. |
| **δ** (Feigenbaum) | Universality: identical scaling across unrelated systems via a renormalization fixed point | Existence: PROVEN (Lanford 1982, computer-assisted; Lyubich 1999, non-numerical). Irrationality: OPEN. Transcendence: OPEN (believed transcendental). No known relation to any constant below. | The taxonomy commits to δ's independence — a genuinely new constant from the function-space layer. A proven closed form in π, e, or Γ-values breaks this row and hands flat-necessity its best exhibit. |
| **K₀** (Khinchin) | Measure-theoretic typicality: the statistical texture of almost every real number | Existence of the a.e. constant: PROVEN. Irrationality of K₀ itself: OPEN. No explicit real number has ever been proven Khinchin-typical; π, γ, ζ(3), and K₀ itself are numerically consistent but unproven. | The taxonomy's self-test: the constant describing typical numbers, itself of unknown status. Predicts the named constants behave typically — excluding rationals, quadratic irrationals (√2, φ), and e, all provably atypical. That e is atypical while π appears typical is itself a two-lineage datum. |
| **Ω** (Chaitin) | The provability boundary: necessity and knowability separate by theorem | Well-defined (per machine): PROVEN. Uncomputable: PROVEN. Martin-Löf random and normal: PROVEN. Any fixed axiom system yields at most finitely many bits: PROVEN. | Interpretation CONTESTED (Part Four) — the theorems are not; the row rests on the theorems alone. |

*Grounding for the table: every status entry is EMPIRICAL (theorem-level, individually checkable; load-bearing entries verified against the sources named in AM3). The column "structural transition it marks" is STRUCTURAL — it is the thesis argued in Part Two, not a reported fact. The commitments column is the document's falsification surface.*

---

## Part Four: The Contested Question

The gradient in the table is data. What it means is contested, and there are three structurally distinct positions. Each is stated with what would have to be true for it to hold.

### Position 1 — Flat necessity, stratified access

All mathematical truths have identical modal status: necessarily true if true, one grade of necessity for all of mathematics. The gradient is entirely epistemic — a fact about human provers, available techniques, and chosen axiom systems, not about the truths themselves.

The steelman deserves its full strength, and it has three independent arguments. First, the precedent argument: reverse mathematics — the program that determines exactly which axioms each theorem requires — has stratified provability with complete rigor for fifty years, and its practitioners have never needed to claim stratified *necessity*. Calibrated proof-strength with flat truth is a coherent, indeed standard, package. Second, the technology argument: transcendence theory is young — the first transcendence proof of any naturally occurring constant is Hermite's, 1873 — and its tools are notoriously narrow. γ's resistance may mean nothing more than that the right tool is three ideas away; Apéry's 1978 proof of ζ(3)'s irrationality is the standing demonstration that centuries of resistance can end in ten pages. Third, the circularity worry, which is the sharpest: if "structural depth" is not defined independently of epistemic resistance, the correlation of Fact 3 risks being a tautology — constants get called deep *because* they resist.

The circularity worry has an answer, and it is the reason Part Two was built the way it was: the ladder is defined by construction order and expressibility — which structures must exist before the constant is definable — with no reference to proof difficulty. φ is the control: a constant of an infinite recursive process, low on the ladder by expressibility, and fully resolved, exactly as the ladder predicts and problem-age would not. The technology argument, however, has no complete answer below L8, and Position 1 remains fully live for every rung between L5 and L7.

For Position 1 to hold: the ordered correlation must be explained — not explained away — as selection or technology artifact, and the explanation must cover why the ordering matches independently-defined construction depth. And the position must absorb L8: at the top rung, "stratified access" is not a human limitation but a theorem about all possible formal systems, which is at minimum an awkward fit for a picture in which access-stratification is supposed to be shallow.

### Position 2 — Layered necessity

Necessity has internal structure: what is necessary at a layer is inexpressible and unforceable from below, and the gradient tracks this structure. π's full derivability, γ's seam-resistance, δ's independence, and Ω's closure are four readings of one architecture: mathematical truth is organized in strata, and epistemic access degrades across strata because the strata are real.

For Position 2 to hold, two things must be delivered. First, non-arbitrariness of the layers: each transition in Part Two must be forced — an internal demand, not a chosen direction of generalization. Part Two argues this is so for every rung (the demands of L1–L5 are posed in the lower layer's own vocabulary; L8's boundary is a theorem), with L6 and L7 the weakest links: "the seam" and "the function-space layer" are identified by their scars more than by an independent forcing argument, and an honest statement of the position concedes this. Second — the burden the position has not met anywhere in the literature — a formalization: a definition of "necessary at layer n" precise enough that the table's placements become theorems rather than readings. Candidate raw material exists (interpretability hierarchies, definability hierarchies, the expressibility results of Part Two), but the framework does not. Position 2 is, at present, a structural hypothesis with one proven instance (L8) and an unformalized middle.

### Position 3 — The question is malformed

Constants are artifacts of notation and human interest. "The numbers that matter" is a sociological set — the ones with names, the ones in textbooks — and a sociological set needs no ontology; asking why the famous constants show a gradient is like asking why famous mountains show a height distribution.

The position deserves engagement because it is half right. Which constants get *names* is sociological; the prominence of φ in particular carries centuries of accumulated mysticism the mathematics does not support. But the deflation has two hard limits. The period class is not sociological: it is a mathematically defined, countable ring, and the concentration of practice inside it (Fact 1) is a fact about mathematics, not about fame. And Ω's properties are theorems about every formal system, indifferent to whether anyone names or celebrates the number. For Position 3 to hold, Fact 1 and the L8 theorems would need sociological readings, and none is available. What survives of the position is a discipline the document adopts: no argument here rests on which constants are famous — only on expressibility, construction order, and theorem-level status.

### The Ω interpretation, separately

Even among those who accept every theorem in the L8 row, the strong reading — the bits of Ω as brute mathematical facts, mathematics as quasi-empirical, the axiomatic method as refuted — is contested, and the criticism (that the theorems are being over-interpreted) is on the record and has force. This document takes no side: the argument uses the separation theorem and nothing stronger. If the strong reading is right, Position 2 gains; if the deflationary reading of Ω is right, the L8 anchor still holds, because the anchor is the theorem, not its gloss.

---

## Part Five: What the Derivation Supports

The derivation supports treating constants as structured evidence rather than trivia. Their thinness (a measure-zero, period-concentrated class), their placement (each expressible only from a specific rung of a construction-ordered ladder), and their gradient (epistemic resistance tracking construction depth) are facts a philosophy of mathematics should explain. The flat-necessity position currently explains them only by setting them aside, and the one place it cannot set aside — the L8 separation theorem — it must absorb as an unexplained singularity at the top of an otherwise flat landscape.

The derivation establishes the top separation: necessary-but-unknowable is a proven category, not a speculation. It is consistent with, but does not prove, graded separation below. The middle of the ladder — γ's seam, ζ(3)'s depth, δ's independence — is where the two positions genuinely differ in their predictions, and the commitments column of the table states what mathematical events would move which rows in which direction. The document's claims are, to that extent, exposed.

One consequence is stated as a conditional, marked SPECULATIVE, and quarantined to this paragraph: if necessity is layered, then for any contingent-seeming quantity — in physics or elsewhere — a third status becomes available beside "derivable" and "brute": *derivable in principle, underivable from within any fixed system*. Nothing else in this document depends on this remark.

**Illustrative remark (not foundational):** elsewhere in this corpus, the discussion of universe parameter spaces distinguishes categorical architecture — features that cannot be varied by adjusting a number — from the constants a parametric study varies. The taxonomy here is consistent with that distinction and adds one observation from the mathematical side: whatever a parametric study varies, it cannot vary π-type constants, which are invariant across any possible draw because they are theorems of any consistent structure rich enough to state them. Only contingent dimensionless quantities are available as dials. The remark illustrates consistency; neither document is evidence for the other, and nothing here crosses the boundaries that document marks as non-derivable.

---

## The Honest Limit

What this document can establish: the three facts of Part One; the forced character of the L1–L5 transitions and the theorem character of L8, with L6–L7 identified as the ladder's weakest forcing arguments; the theorem-level statuses in the table; and that necessity and knowability provably separate at the computability boundary.

What it cannot establish: that the gradient below L8 is ontological rather than epistemic. Position 1 remains fully live — everything here short of the top rung is compatible with flat necessity plus stratified access, and the technology argument (Apéry as precedent) has no complete rebuttal. What would decide the question: from the flat side, a principled account of why epistemic resistance tracks independently-defined construction depth; from the layered side, a formal framework in which "necessary at layer n" is well-defined and the table's placements become theorems. Neither exists. Individual rows will move first: a closed form for δ, a proof that e is or is not a period, γ falling to elementary tools — each is a live mathematical event with a stated direction of force on the thesis. The document ends where the derivation ends.

---

## Assumptions

**AM1. Definability thinness.**
Relative to any fixed formal language, only countably many reals are definable; the constants of practice concentrate in the period class.
*Grounding: EMPIRICAL — elementary countability plus Kontsevich–Zagier (2001).*

**AM2. Construction-order independence.**
The ladder of Part Two is defined by expressibility and construction order, without reference to proof difficulty, so the Fact 3 correlation is not circular.
*Grounding: STRUCTURAL — argued in Part Two; the L6/L7 rungs are the weakest instances and are flagged as such.*

**AM3. Status accuracy.**
Every epistemic-status entry in the table is a correct report of current theorem-level knowledge, verified against sources for the load-bearing entries: γ's non-period conjecture (Lagarias 2013); e's non-period conjecture (Kontsevich–Zagier 2001); the open status of ζ(3)/π³; δ's proof history (Lanford 1982; Lyubich 1999) and open arithmetic nature; K₀'s open arithmetic nature and the absence of any explicit real number proven Khinchin-typical.
*Grounding: EMPIRICAL — each entry individually checkable against the cited sources.*

**AM4. The L8 anchor.**
The separation of necessity from knowability at the computability boundary uses only the standard theorems about Ω, not the contested strong interpretation.
*Grounding: EMPIRICAL — the theorems; the interpretive dispute is engaged in Part Four and not relied upon.*

**AM5. Gradient as explanandum.**
The ordered correlation between construction depth and epistemic resistance is a real pattern requiring explanation, not an artifact of selection.
*Grounding: STRUCTURAL — supported by the φ control and construction-order independence; the proof-technology counter-argument is acknowledged as unrebutted below L8.*

**AM6. Layered-necessity conditional.**
The third modal status ("derivable in principle, underivable within any fixed system") follows only if Position 2 holds.
*Grounding: SPECULATIVE — explicitly conditional; quarantined to one paragraph of Part Five.*

---

*This document treats the constants of mathematics as specimens: each one the residue of a structural transition — ratios failing, algebra closing, limits completing, computation ending — and reads their ordered gradient of knowability, from π's full derivability to Ω's proven unknowability, as evidence bearing on whether mathematical necessity is flat or layered. It establishes the gradient as data, anchors one separation of necessity from knowability as theorem, states in the table which live conjectures would move which rows, and stops where the derivation stops: the status of the middle rungs remains genuinely open between the two positions.*

---

*Author: Alex Liu*
*Part of the Apeiron framework series*
*License: CC BY-NC 4.0*
