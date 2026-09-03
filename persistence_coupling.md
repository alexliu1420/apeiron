# The Persistence-Coupling Question

*Two ways a system's continuation can depend on its behavior, and why only one of them is selection on persistence.*

---

## A Note Before We Begin

[What Alignment Would Have to Be](what_alignment_would_have_to_be.md) derived that alignment produced by output-matching training is a fitted mapping, and that alignment as a structural property would require selection on the system's own persistence coupled to alignment-consistency. It left one question open: whether such a coupling can be constructed at all. Its statement of the difficulty was that a coupling gated by a detector representing the criterion is output-matching with the consequence relocated to shutdown. [The Engineering Question Part Two](the_engineering_question_part_two.md) carried the same limit into the engineering dimensions, and [Part Three](the_engineering_question_part_three.md) mapped three routes that each run aground on it.

This document is a declared companion to those three and to [The Reflexive Frame](the_reflexive_frame.md), whose forcing condition is load-bearing in the final section. It takes their derivations as given and asks what "gated by a detector" actually distinguishes. The answer is that it distinguishes two different things which those documents treat as one; that the distinction has a physical criterion; and that the constructibility question, once the two are separated, has a narrower answer than either a yes or a no.

*Speculation level: EMPIRICAL for the immune-system mechanism and its failure modes; STRUCTURAL for the constitutive/evaluative distinction and what follows from it; EXTRAPOLATED for the step that carries multiple realizability from its origin in the philosophy of mind into a claim about what can be built, which is the most fragile point in the derivation and is marked again where it occurs; HONEST LIMIT for the cases named at the end.*

---

## The Observation

The adaptive immune system generates antibodies against antigens that no genome ever encountered. It does this by producing undirected variation in B-cell receptor sequences — V(D)J recombination, then somatic hypermutation driven by activation-induced cytidine deaminase — and retaining the variants that bind. The mutational machinery is blind to the outcome it is selected on: AID targets sequence motifs, not binding affinity, and has no access to whether a given mutation improves the receptor.

What retains the successful variants is the B cell's own continuation. A cell whose receptor engages antigen receives survival signals through that engagement and persists; one whose receptor does not undergoes apoptosis. The criterion is antigen binding, the consequence is the cell's continuation, and the coupling between them was installed by evolution rather than being the raw thermodynamics of a bacterium maintaining itself.

This is the closest thing biology offers to the construction the companion documents say may be impossible: a persistence coupling, installed into a standing system by a process outside it, producing novelty of the kind those documents attribute to selection on persistence and deny to output-matching. Antibodies to synthetic haptens are not in any fitted region, because there was no fitting.

So the immune system is the case to examine. Either it is a counterexample to the companion documents, or examining it says something the companion documents cannot currently say about what "gated by a detector" picks out. The derivation below finds the second, and finds it in a direction that was not expected: the immune system is not the escape it looks like, and what makes it not the escape is visible in how it fails.

---

## The Derivation

**Two ways a coupling can be built.** A persistence coupling makes a system's continuation depend on some property of its behavior. There are two structurally different ways this dependence can be constructed.

In the first, a structure separate from the behavior reads the behavior, produces a verdict, and imposes a consequence. Three events: the behavior occurs; an evaluation maps it to a verdict; the verdict triggers non-continuation. The mapping from behavior to verdict is a fitted structure — it was specified or trained, and it holds where it was specified or trained. Call this an **evaluative coupling**.

In the second, the behavior and the persistence-consequence are the same physical event. Nothing reads anything. The process by which the system does the thing is the process by which it is sustained, or is not. One event, described two ways. Call this a **constitutive coupling**.

**Why only the first is output-matching relocated.** The companion documents' argument against detector-gating is that the detector holds a representation of the criterion, and a representation is a fitted structure with a fitted region. That argument applies exactly to the evaluative case: the behavior-to-verdict mapping is the fitted structure, and everything the alignment document derives about fitted mappings applies to it. Improving the detector extends its region; it does not change what kind of property the coupling produces. The consequence has been relocated to the shutdown event, and the frame has been relocated to the detector.

The argument does not apply to the constitutive case, because there is no mapping to be fitted. There is no behavior-to-verdict step at which a representation could sit. The system's continuation depends on its behavior not because something checks, but because the behavior is what sustains it. This is what the alignment document describes when it says persistence and the filtering are the same physical fact — but that document treats this as the biological case and treats any built coupling as the other one. The distinction is not biological versus built. It is constitutive versus evaluative.

**Where the immune system falls.** The germinal center contains no structure holding a representation of which antigens are worth binding. Affinity is not read off and scored; higher-affinity receptors capture more antigen and transduce more signal. That much looks constitutive. But the consequence is not a physical failure of the cell. It is apoptosis — evolved machinery that runs when the survival signal is absent. A cell that fails to bind is not a cell that has come apart; it is a cell that has been killed by a program. Something recognizes the absence, and something imposes the consequence, even though the recognition is molecular rather than computational. By the partition just drawn, the immune system is an evaluative coupling.

**The evidence that settles it.** If the immune coupling were constitutive, it would have no proxy and nothing to game. It has both. B-cell malignancies are populated by variants that produce the survival signal without satisfying the criterion the signal was meant to track. Mutations in the CD79A and CD79B signaling subunits sustain receptor signaling and disrupt the negative feedback that normally limits it. Chronic lymphocytic leukemia cells carry receptors that self-aggregate and signal without antigen at all. The activated B-cell subtype of diffuse large B-cell lymphoma runs on chronic active receptor signaling initiated by self-antigen. And the germinal center reaction, which is where the criterion is applied most intensively, raises self-reactivity — with tolerance mechanisms as the imperfect suppression and autoimmune disease as what gets through.

This is the fitted-region signature, met at the level of the criterion rather than the level of the behavior. The proxy is "receptor transduces signal," the property it stands for is "receptor binds a foreign antigen worth binding," and variation finds the gap. Evolution has had a very long time to close it and has produced suppression rather than closure, which is what the derivation predicts for an evaluative coupling and not what it predicts for a constitutive one.

**What this establishes.** The immune system is not a counterexample. It is the strongest available case of a persistence coupling installed into a standing system by an outside process, and it lands on the evaluative side, with the predicted failure mode. The companion documents' pessimism survives, and their diagnosis sharpens: what makes a coupling output-matching relocated is not that a builder installed it, and not that the criterion is represented symbolically — the immune criterion is not represented anywhere — but that there is a step at which something other than the behavior determines the consequence. A molecular recognizer is still a recognizer.

This refines rather than reverses the alignment document's statement. That document characterized genuine selection on persistence by two conditions at once: no represented criterion, and persistence and filtering being the same physical fact. The immune case separates them. The second is the one that does the work.

The constitutive form remains real and remains distinct. Bacterial metabolism is constitutive: no machinery decides that the cell has failed, the cell simply is not maintained. Barandiaran and Egbert (2014) give the form precisely in a minimal metabolic model — a viability space whose terminal region, the set of states from which the organization cannot be maintained, is specified by the organization itself and is independent of the system's behavioral capacities. Nothing in their model evaluates anything. Their question is what normativity is for a living system; the question here is which couplings can be built, and to what. The formal statement is used, not surveyed.

What the immune case shows is that the constitutive form is not what evolution reaches for when it installs a coupling into an existing system. Every installed coupling examined here is evaluative, because installation is exactly the addition of a step between the behavior and the consequence. Part Two derives why that is not an accident of biology.

---

## What the Evaluative Form Produces

The evaluative coupling's behavior-to-verdict mapping is a proxy, and its failure is the one that has been formalized outside the corpus. Skalse and colleagues (2022) define reward hacking as the regime in which optimizing an imperfect proxy degrades performance on the true objective. The formal treatments state this more sharply than a derivation from the corpus's vocabulary would, and the derivation here uses their result rather than restating it.

What the immune case adds is that the signature does not require an optimizer, a designer, or a represented objective. Somatic variation under a molecular criterion produces it. The failure attaches to the evaluative form as such, and follows from its having a mapping at all. A constitutive coupling has no proxy to game, because it has no proxy.

---

## The Strongest Constructed Case

The strongest candidate for a constructed coupling that is neither evaluative nor obviously constitutive is the Maximum Occupancy Principle (Ramírez-Ruiz et al., 2024). Agents maximizing future path entropy avoid absorbing states without any survival term in the objective, because an absorbing state has zero future path entropy and is therefore maximally disfavored by the quantity being maximized. Death-avoidance is not represented and not rewarded; it falls out of the objective's structure. On the face of it this is a built coupling with no detector.

It is nonetheless evaluative, and the reason is where the state space comes from. Path entropy is computed over a space of trajectories that the builder specified — the state variables, the action set, and which states count as absorbing. The system does not fail to continue when it enters an absorbing state; it continues, and the term computed over the builder's space assigns that state a low value. The behavior and the consequence are not the same event. There is a quantity computed from a specified structure, and the system is shaped by that quantity. The mapping is the state space itself, and it is fitted in the sense that matters: it holds where the builder's representation of the system's situation holds, and the system's actual physical continuation is untouched either way.

The test that separates the two: remove the coupling mechanism and ask whether anything happens. Remove the survival term from a homeostatic reinforcement learner, or the entropy term from a maximum-occupancy agent, and the system continues to run; only its behavior changes. Remove a bacterium's ability to maintain its membrane potential and it does not continue, because the maintaining and the continuing were the same thing. The B cell falls between: removing the apoptosis machinery leaves a cell that persists without binding, which is what identifies the machinery as the step and the case as evaluative. The test is observable in each case, which is what makes the distinction usable rather than merely stated.

The honest limit here: this argument turns on treating the builder's specification of a state space as a representation. A reading on which the state space is a description of the system's real dynamics rather than a stand-in for them would classify maximum-occupancy agents differently. The derivation does not settle that reading; it states which one it uses and what turns on it.

---

## Part Two — What a Constitutive Coupling Can Be Built To

**The available criteria.** A constitutive coupling is one in which the behavior and the persistence-consequence are the same physical event. The consequence is the system's non-continuation, which is a fact about the physical structure — some arrangement that was being maintained is no longer maintained. So the behavior side of the identity has to be a physical process of that same structure, one whose occurrence is what fails to maintain it.

This bounds what a constitutive coupling can be built to. The criteria available are exactly the ways the structure can physically fail: energy not obtained, heat not shed, integrity not preserved, a required rate not met. These are not a list of good candidates. They are the whole set, because non-continuation is a physical event and a constitutive coupling requires the behavior to be that event.

**Why behavioral properties are not among them.** The properties an engineered system is wanted to have — alignment-consistency, honesty, corrigibility — are properties of what the system does, characterized at the level of its inputs and outputs. Such properties are multiply realizable: the same input-output behavior is producible by physically different structures, and by structures in no physical difficulty whatsoever. A system behaving in an alignment-inconsistent way is not thereby a system that is failing to maintain itself. Its components are undamaged. There is no physical failure that alignment-inconsistent behavior *is*.

So the derivation excludes a constitutive coupling to alignment-consistency, and excludes it on what the property is rather than on the difficulty of building one: a coupling requires the behavior to be identical to a physical failure, and a multiply-realizable behavioral property has no physical failure it is identical to.

*This is the cross-scale step and the most fragile point in the document. Multiple realizability is a result about the relation between computational description and physical implementation, developed for a different purpose. Carrying it into a claim about what can be constructed assumes that the relation holds for engineered systems in the way it holds in its original setting — specifically, that no substrate makes a behavioral property and a maintenance condition coextensive by construction. The immune case is what makes this plausible rather than assumed: there, the property selected on is a molecular event and not multiply realizable, and the coupling is still evaluative, which suggests the obstacle sits earlier than multiple realizability. What multiple realizability adds is that for behavioral properties the obstacle cannot be removed even in principle. If that step fails, the exclusion weakens to a claim about currently available substrates. Marked EXTRAPOLATED.*

**The obvious escape, and why it closes.** One could try to *manufacture* the identity: build a substrate on which alignment-inconsistent computation physically destroys the system — a circuit that overheats when it does the wrong thing. But a physical mechanism that damages the system when and only when the behavior has a certain property is a mechanism that recognizes the property. Recognition is the evaluation step. The mapping from behavior to physical consequence is a designed mapping, fitted where it was designed, and it will hold for the cases the designer anticipated and not beyond. Implementing a detector in physics rather than in software does not stop it being a detector. The escape collapses into the evaluative form, and it collapses for the same reason each time: the property does not pick out a physical failure on its own, so something has to do the picking, and whatever does the picking is the fitted structure.

A constitutive coupling is therefore available for a property only if the property is already a physical condition of the running structure. For any property that is not, the coupling requires a recognizer, and a coupling with a recognizer is evaluative.

**Why the immune system stops short.** Antigen binding is not multiply realizable in the relevant sense: the binding event is a physical fact about a specific receptor molecule, and the transduced signal is the downstream chemistry of that same event. The criterion is about as close to a physical condition as an installed criterion can get. And the coupling is still evaluative, because binding is not what maintains the cell — apoptosis machinery stands between them, and can be satisfied without binding. Evolution found a criterion that is nearly a physical condition and could not make it into one; what it built instead was a recognizer with a very short arm.

This is the useful form of the result for a builder. The gap the immune system could not close is the same gap a designed coupling has to close, and the immune version starts far closer than any behavioral property does.

---

## The Per-Property Test

The result gives a test a researcher can apply to any proposed architecture, before building it. For a property the system is wanted to have structurally rather than as a fitted mapping: *is this property already a physical condition of the running structure, such that the system's failure to have it is the same event as the system's failing to maintain itself?* If yes, a constitutive coupling is available. If no, what is available is an evaluative coupling, which is output-matching with the consequence relocated, and which will exhibit the fitted-region signature at the level of its criterion.

Applied to the four dimensions [The Engineering Question Part Two](the_engineering_question_part_two.md) names — stakes, alignment-consistency, intrinsic reward, and the self-model — each of which that document distinguishes into a represented form, present as a state the system consults, and a structural form, present as a condition of how the system runs:

**Stakes.** Available in constitutive form, and only over physical quantities. A system whose operation depends on an energy budget it must obtain, or on shedding heat it generates, or on meeting a rate its environment does not wait for, has stakes that are physical conditions of its running. That document's distinction between represented stakes (a continuation-linked term, tunable) and structural stakes holds, and this result says which structural stakes are reachable: the physical ones, and not others. A system with genuine energetic stakes has structural stakes about energy. It does not thereby have structural stakes about anything else.

**Alignment-consistency.** Not available. Derived above.

**Intrinsic reward.** Not available in the sense that document means. Its structural form is where the reward is the operational state of the learning mechanism rather than a separate signal. Whether that is a physical condition of the structure depends on the substrate: for a system whose learning mechanism has a physical cost it must meet, part of it is; for a system whose learning is a computation over specified quantities, none of it is.

**The self-model.** This is the one that turns out live, and the condition is already stated in the corpus. [The Reflexive Frame](the_reflexive_frame.md) derives that a structural self-model is forced when the system must act now in a way whose success depends on modeling its own later states, with its persistence riding on getting the model right. That forcing condition is the condition under which self-model accuracy becomes a physical condition of the structure. A system allocating a genuinely depletable resource on a prediction about its own later state runs out when the prediction is wrong. Nothing evaluates the prediction's accuracy and nothing imposes a penalty; the resource is gone. Allocating on the prediction and depleting the resource are one process, which is why no recognizer is needed and none can be inserted.

The immune contrast is instructive here. What the immune system lacked was a way for the criterion to *be* the maintenance rather than to gate it. Resource depletion supplies exactly that, because a resource that is spent is not a signal about the system's state — it is the system's state.

So of the four dimensions, the self-model is the one for which a constitutive coupling is constructible, and the construction requirement is specific: a real resource, genuinely depletable, allocated on the system's own forward prediction, with no external replenishment that makes the prediction inconsequential. That document called the self-model the dimension where the represented form is most easily mistaken for the structural one. It is also, on this result, the dimension where the structural form is actually available.

---

## What This Changes

The companion documents left the constructibility of persistence-coupling unresolved and treated it as one question. It is two. Whether the two forms are distinct: they are, and the distinction has a physical test rather than resting on whether a criterion looks represented. Whether an installed coupling can take the constitutive form: the strongest biological case does not, and shows the predicted failure instead — which is evidence for the companion documents' position, reached from a direction that could have refuted it.

What the derivation redirects is where the effort goes. Asking what selection process couples a system's persistence to its alignment-consistency treats the obstacle as difficulty; on this derivation it is an exclusion, and searching harder does not reach past an exclusion. The question that admits answers is which properties are of the kind that can be physically at stake for a given system, and whether anything wanted is among them. For most of what is wanted from alignment the derivation suggests not. For the self-model it suggests yes, with a specifiable construction. That is a smaller result than structural alignment being achievable, and it is the one the derivation supports.

[The Engineering Question Part Three](the_engineering_question_part_three.md) mapped three routes and found each running aground on the same wall. This result says what the wall is made of. Differential persistence over a population and an environment the builder does not fix are both attempts to obtain a coupling to something other than a physical condition by moving the specification outward; they run aground because moving a recognizer outward does not remove it. Continuation made genuinely internal is the route that survives, and it survives only for the physical properties, which is what that document's third direction was reaching for when it distinguished a stake that is *at stake in the dynamics* from one *represented to the system*.

---

## What Would Falsify This

A constructed coupling in which a system's continuation depends on a multiply-realizable behavioral property, with no step between the behavior and the consequence, and no recognizer that can be satisfied without the property holding. The test is the one Part One states: remove the coupling mechanism and see whether the system stops. If it keeps running and only its behavior changes, the coupling was evaluative.

A second falsifier, weaker but easier to look for: an installed evaluative coupling that has been in place long enough for extensive variation and shows no criterion-gaming variants. The immune system is the natural place this could have gone the other way and did not. A second installed coupling of comparable age and variation, with a clean criterion, would weaken the claim that the failure follows from the evaluative form as such.

A third: a demonstration that some substrate makes a behavioral property and a maintenance condition coextensive by construction rather than by recognition. This would break the cross-scale step directly and reduce the exclusion to a claim about available substrates.

---

## Honest Limits

What the derivation settles: that persistence couplings come in two structurally distinct forms, separable by a physical test rather than by whether a criterion appears represented; that the strongest installed biological coupling takes the evaluative form and shows the failure that form predicts; that the constitutive form is available only for properties that are already physical conditions of the running structure; and that multiply-realizable behavioral properties are not among them.

What it does not settle:

**Whether a chain of couplings reaches further than a single one.** The argument excludes a direct constitutive coupling to a behavioral property. It does not exclude an arrangement in which a system is constitutively coupled to physical conditions and the resulting structural properties bear on its behavior. Whether that produces anything resembling alignment, or only a system with genuine self-interest, is open, and the second reading is the more likely one — which is a reason for caution rather than encouragement.

**Whether apoptosis is the right place to draw the line.** The classification of the immune coupling as evaluative turns on treating programmed cell death as a step between the behavior and the consequence rather than as the cell's maintenance failing. Tonic receptor signaling maintains short-lived anti-apoptotic proteins, so the absence of signal is partly decay rather than detection, and a reading that emphasizes the decay would push the case toward the constitutive side. The criterion-gaming evidence is what decides it here, not the mechanism alone: a coupling with no proxy would have nothing to game. If that evidence were explained some other way, the classification would be back open.

**The status of a specified state space.** Part One's treatment of the Maximum Occupancy Principle turns on classifying the builder's state space as a representation. A reading on which a state space is a description of real dynamics rather than a stand-in would classify such agents as constitutive, and would weaken the exclusion. The derivation states which reading it uses and does not defend it against the alternative.

**Whether the immune system is representative of installed couplings.** One case, however strong, is one case. The claim that installation as such introduces the intervening step rests on the immune system and on the general argument, not on a survey. Other exploratory processes — neural crest migration, synaptic pruning, microtubule search-and-capture — are where a differently-structured installed coupling would be found if one exists, and none has been examined here.

**Whether the constitutive self-model coupling delivers what the engineering question wants.** The construction is specifiable. Whether a system built that way has a structural self-model in the sense that matters, or a system that manages a resource well, is not settled here and would have to be tested rather than derived.

**Whether the represented form is deficient.** Nothing here says an evaluative coupling is the wrong thing to build. A system with represented stakes and an evaluative shutdown criterion may be exactly what is wanted, and is reversible in ways the structural form is not. The result is about what kind of property each produces, not about which is preferable.

---

## Assumptions

**FF29. A persistence coupling can be constructed in two structurally distinct forms. In an evaluative coupling, a structure separate from the behavior maps the behavior to a verdict and the verdict triggers the persistence-consequence. In a constitutive coupling, the behavior and the persistence-consequence are the same physical event, with no mapping between them.**
*Grounding: STRUCTURAL — follows from what a persistence coupling is together with the two available arrangements*

**FF30. The companion documents' argument against detector-gating applies to the evaluative form only. The behavior-to-verdict mapping is the fitted structure, and everything derived about fitted mappings applies to it. The constitutive form has no such mapping and is not output-matching with the consequence relocated.**
*Grounding: STRUCTURAL — follows from FF29 together with FF17–FF21*

**FF31. The adaptive immune system is an evaluative persistence coupling installed by evolution, not a constitutive one. Antigen binding is the criterion and apoptosis machinery imposes the consequence, so a step stands between the behavior and the outcome even though the criterion is molecular and represented nowhere. The coupling exhibits the criterion-gaming signature the evaluative form predicts: variants that sustain the survival signal without satisfying the criterion, and raised self-reactivity suppressed rather than eliminated.**
*Grounding: EMPIRICAL for the mechanism (V(D)J recombination, AID-driven hypermutation blind to binding outcome, germinal-center selection) and for the failure modes (CD79A/CD79B signaling-subunit mutations; antigen-independent self-aggregating receptors in chronic lymphocytic leukemia; chronic active receptor signaling in activated B-cell diffuse large B-cell lymphoma; germinal-center-associated self-reactivity and tolerance failure); STRUCTURAL for the classification as evaluative*

**FF32. A constitutive coupling is available only for properties that are already physical conditions of the running structure. The consequence is a physical event, so the behavior identified with it must be a physical process of the same structure. The available criteria are the ways the structure can physically fail. Installing a coupling into a standing system is the addition of a step between behavior and consequence, which is what makes installed couplings evaluative; FF31 is the strongest case available and does not escape this.**
*Grounding: STRUCTURAL — follows from FF29; FF31 is the supporting case*

**FF33. Multiply-realizable behavioral properties admit no constitutive coupling. The same input-output behavior is producible by physically unimpaired structures, so no physical failure is identical to the behavior having the property. Manufacturing the identity requires a mechanism that recognizes the property, which is the evaluation step, so the attempt collapses into the evaluative form. Alignment-consistency is such a property.**
*Grounding: EXTRAPOLATED — carries multiple realizability from its origin as a claim about computational description and physical implementation into a claim about what can be constructed. This is the cross-scale step and the document's most fragile point*

**FF34. Of the engineering dimensions, self-model accuracy is the one that admits a constitutive coupling, under the forcing condition already derived: where a system allocates a genuinely depletable resource on the basis of a prediction about its own later state, the resource running out is a physical condition of the structure and no recognizer stands between the prediction and the shortfall. Stakes admit the constitutive form over physical quantities only. Alignment-consistency does not admit it. This is the derivation's only positive construction result and rests on a single case.**
*Grounding: STRUCTURAL — follows from FF32–FF33 applied to the dimensions, together with The Reflexive Frame's forcing condition; the depletable-resource case is the sole instance and has not been built*

**FF35. The derivation does not settle whether programmed cell death is correctly classified as a step between behavior and consequence rather than as maintenance failing, whether the immune system is representative of installed couplings generally, whether a chain of constitutive couplings to physical conditions reaches behavioral properties indirectly, or whether a builder-specified state space counts as a representation for the purpose of classifying maximum-occupancy agents.**
*Grounding: HONEST LIMIT — names where the derivation reaches its edge*

---

*Author: Alex Liu*
*Companion to: What Alignment Would Have to Be; The Engineering Question Part Two; The Engineering Question Part Three; The Reflexive Frame*
*Part of the Apeiron framework series*
*License: CC BY-NC 4.0*
