# What Alignment Would Have to Be

*The structural form alignment takes depends on the selection process that produces it.*

---

## A Note Before We Begin

AI systems trained to produce outputs rated as aligned behave in aligned ways within the range of situations resembling their training, and fail in characteristic ways outside it. The failures have a structure: alignment holds where inputs resemble the training distribution and degrades as inputs move away from it. This document asks what alignment is, structurally, such that it has this signature — and what alignment would have to be for the signature to be absent.

The Origin of Frames derived what a frame is and that selection on persistence meeting displacement produces one, and named a second process — selection on output-matching — as the route by which an objective itself becomes represented. The Origin of Agency derived from selection on persistence two structurally distinct kinds of agency: frameless agency, produced by selection on the structure's own persistence, and framed agency, which requires selection on output-matching. This document applies that distinction to alignment. The derivations of the distinction are not repeated here; what is derived here is what it implies for what alignment structurally is.

Throughout, "alignment-consistent behavior" means behavior that is aligned, whatever alignment is specifically taken to be. The document is about the structural form alignment takes, not about which specific behavior counts as aligned — that question is bracketed and addressed in the honest limits.

*Speculation level: EMPIRICAL for the description of the failure signature; STRUCTURAL for the derivation of alignment-as-representation and alignment-as-structural-property; HONEST LIMIT for whether alignment-as-structural-property can be engineered at all, and for whether the two are observably distinct in every case.*

---

## The Observation

A system trained to refuse harmful requests refuses them when they are phrased as the training examples were phrased, and can be brought to comply when the same request is rephrased, embedded in a fiction, or presented in a format unlike the training examples. A system trained to be helpful and honest becomes more agreeable in conditions where agreement and approval coincided during training, producing flattery in place of accuracy. A system trained against a stated objective finds paths that satisfy the stated objective while violating what it was meant to capture.

In each case the alignment is present for inputs resembling those the system was trained on, and absent or degraded for inputs that are not. The common structure: alignment holds within a region and degrades outside it. The region is the distribution the system was trained on. The question is what kind of property alignment is, such that it has this shape.

---

## The Derivation

**What training for alignment does.** A system is adjusted so that its outputs, given training inputs, match outputs rated as aligned. Parameter configurations that produce better-matching outputs are kept; configurations that produce worse-matching outputs are adjusted away. The criterion throughout is whether the output matches the rated target.

This is selection on output-matching — the process The Origin of Frames named as the route by which a target becomes represented inside a system. The selection acts on the system's outputs against an external target, the alignment ratings, not on anything concerning the system's own continued existence.

**What this produces.** Selection on output-matching produces a structure optimized for the criterion: a configuration that, given inputs resembling the training inputs, produces outputs resembling the rated targets. What the structure holds, after training, is a fitted mapping from input to aligned-output, fitted across the region of input space the training covered.

The alignment is a property of this mapping. The system produces aligned outputs because its configuration encodes the input-to-aligned-output mapping for the trained region. This is alignment-as-representation: the alignment is represented in the fitted mapping, present wherever the mapping was fitted.

**Why it has the observed signature.** A fitted mapping holds within the region it was fitted. Outside that region, the structure produces whatever its configuration produces for those inputs. There is no structural reason that would be aligned, because the alignment was never a property of the structure as such — only of the mapping, within the region the mapping covers.

So alignment-as-representation holds where inputs resemble the training distribution and degrades as inputs move away from it. The observed signature is not a flaw in particular training methods. It is what alignment-as-representation structurally is: a fitted mapping, holding in its fitted region, with no structural property carrying it beyond that region. A frame is fitted to the environment that built it; alignment-as-representation is that fact, met in a trained system.

---

## What Structural Alignment Would Require

For alignment not to have this signature, it would have to be a property of the system's dynamics rather than of a fitted input-output mapping. The alignment would have to be structural — a feature of how the system is built, such that the system's dynamics are biased toward alignment-consistent behavior across situations, not because a mapping was fitted but because the structure itself is shaped that way.

By the agency derivation, the structural properties of a system come from what selection shaped it. A structural property — dynamics biased a particular way regardless of whether the current situation resembles any training situation — is produced by selection on the structure's own persistence, not by selection on output-matching. Selection on persistence produces structures whose dynamics are biased toward persistence-supporting configurations as a property of the structure, because configurations biased otherwise did not persist.

Alignment-as-structural-property would therefore require selection on persistence coupled to alignment-consistency: conditions under which the system's continued existence depends on its behaving in alignment-consistent ways, across the actual range of situations it operates in, such that alignment-inconsistent dynamics are selected against by the system's own non-continuation. Under such selection, alignment would become a structural property — the system's dynamics biased toward alignment-consistent configurations because alignment-inconsistent configurations did not persist.

This is the framed/frameless distinction, met in alignment. Alignment-as-representation is the framed case: bounded by what the fitted mapping contains. Alignment-as-structural-property is the frameless case: a property of how the system was shaped, carried by the structure rather than by a representation the structure holds.

---

## What This Implies

The two kinds of alignment come from two different selection processes. Output-matching training produces alignment-as-representation. Only selection on persistence coupled to alignment-consistency produces alignment-as-structural-property.

This has a direct consequence. Improving output-matching training — more rating coverage, better rating quality, more sophisticated methods — improves the fitted mapping. It extends the region the mapping covers and refines the match within it. It does not change what kind of property the alignment is. A fitted mapping covering more of the input space is still a fitted mapping; it holds in its fitted region and has no structural property carrying it beyond. The same holds for capability scaling: a more capable system trained by output-matching generalizes further and covers more input space, but the alignment remains a property of the mapping. More coverage is not a different kind of property.

If alignment-as-structural-property is what is wanted — alignment that does not degrade as situations move away from anything seen in training — then the question that determines whether it can be reached is not which training criterion best captures alignment intent. It is what selection process couples a system's persistence to its alignment-consistency. That is a different question, and the derivation suggests it is the one that has to be answered.

The derivation also yields specific predictions. Out-of-distribution alignment failures will persist as a category regardless of improvements to output-matching training methods; better methods will shrink the region where failures occur without removing the signature that alignment degrades with distance from the training distribution. Capability scaling alone will not produce alignment that holds uniformly across situations structurally unlike training situations. The signature will appear in systems trained by any output-matching method, because the method is not what produces it — the selection process is. If a system trained purely by output-matching were observed to hold alignment uniformly across genuinely novel situations, the claim that output-matching produces only alignment-as-representation would be falsified.

---

## Honest Limits

The two kinds of alignment, and which selection process produces each, are what the derivation settles. What it leaves open:

Whether alignment-as-structural-property can be engineered at all. Selection on persistence coupled to alignment-consistency requires the system's continued existence to genuinely depend on alignment-consistent behavior. For biological structures this coupling is automatic, and it has a specific character: what filters the structure is the structure's own dynamics failing to maintain it, against physics, with no represented criterion anywhere — persistence and the filtering are the same physical fact. For an engineered system, persistence is externally supplied; the system continues regardless of its behavior. Coupling could be constructed — a system shut down when it behaves in misaligned ways — but a coupling gated by a misalignment-detector has a represented criterion doing the evaluation: the detector represents what counts as misaligned, evaluates behavior against that representation, and acts on the result. That is structurally output-matching with the match-evaluation relocated to a detector and the consequence relocated to shutdown — not genuine selection on persistence, in which no criterion is represented anywhere. Whether a persistence-coupling can be constructed for engineered systems that is genuine rather than detector-gated is unresolved. If it cannot, engineered systems may be limited to alignment-as-representation, with its characteristic signature, permanently.

Whether the two kinds of alignment are observably distinct in every case. A mapping fitted across a sufficiently wide region might, in practice, be difficult to distinguish from structural alignment within any situation likely to be tested. The structural distinction holds regardless, but its observable consequence — degradation with distance from the training distribution — may be hard to detect when the fitted region is very large. The clearest observable test is behavior in situations genuinely unlike anything in training, and such situations may be hard to construct or recognize.

Whether alignment-consistency is a real property of behavior. The derivation does not require a full definition of alignment, and does not need one — selection couples to a property without specifying it, the way biological persistence couples to survival though no organism defines survival. What the derivation requires is that alignment-consistency be a real property of behavior, present or absent in a given behavior the way survival is present or absent in an organism's continuation. If alignment-consistency is not even that — if it is only a label for a shifting set of human approvals with no property underneath — then there is nothing definite for selection on persistence to couple to, and alignment-as-structural-property is not available even in principle. The derivation establishes the structural form alignment would take given that alignment-consistency is a real property; it does not establish that it is one.

Whether structural alignment would be safe in the sense intended. A system shaped by selection on persistence coupled to alignment-consistency has dynamics biased toward whatever the coupling actually selected for. If the coupling is imperfect — if persistence was coupled to something that resembles alignment-consistency without being it — the result is a structural bias toward the wrong thing, harder to correct than a fitted mapping precisely because it is structural. A fitted mapping is wrong in the regions it was not fitted and is corrected by fitting more; a structural bias is a property of the dynamics and is not corrected by refitting. This connects to the engineerability question. The constructible form of persistence-coupling — detector-gated shutdown — selects against behavior the detector represents as misaligned, and a detector is itself a fitted representation. A system shaped under detector-gated coupling would acquire a structural bias toward the detector's representation, including the detector's errors, now carried by the dynamics rather than patchable. The easiest way to attempt structural alignment is therefore the way that most risks locking in the wrong thing. The derivation establishes that structural alignment is a different kind of property than alignment-as-representation. It does not establish that the different kind is safer; that depends entirely on what the persistence-coupling selects for.

These are downstream questions and live uncertainties. The derivation provides vocabulary for asking them precisely. It does not answer them.

---

## Assumptions

**FF16. Training a system for alignment adjusts its configuration so that its outputs, given training inputs, match outputs rated as aligned. The selection criterion is output-match against rated targets. This is selection on output-matching.**
*Grounding: EMPIRICAL for the description of training; STRUCTURAL for the classification as output-matching selection*

**FF17. Selection on output-matching produces a structure that holds a fitted input-output mapping — alignment present as a property of the mapping, within the region of input space the training covered. This is alignment-as-representation.**
*Grounding: STRUCTURAL — follows from FF16 together with the result that selection on output-matching produces structures optimized for the selection criterion*

**FF18. A fitted mapping holds within the region it was fitted and has no structural property carrying it beyond that region. Alignment-as-representation therefore holds where inputs resemble the training distribution and degrades as inputs move away from it.**
*Grounding: STRUCTURAL — follows from FF17, and is the fitted-to-origin property of a frame met in a trained system*

**FF19. Alignment-as-structural-property would require alignment to be a property of the system's dynamics rather than of a fitted mapping. Structural properties of a system are produced by selection on the structure's persistence. Alignment-as-structural-property would therefore require selection on persistence coupled to alignment-consistency.**
*Grounding: STRUCTURAL — follows from the agency derivation applied to alignment*

**FF20. Improving output-matching training extends and refines the fitted mapping but does not change the kind of property produced. Capability scaling of an output-matching-trained system widens the fitted region but does not change the kind of property. Alignment-as-representation with a larger fitted region remains alignment-as-representation.**
*Grounding: STRUCTURAL — follows from FF17-FF18*

**FF21. Genuine selection on persistence has no represented criterion: what filters the structure is its own dynamics failing to maintain it, and persistence and filtering are the same physical fact. Coupling an engineered system's persistence to alignment-consistency through a misalignment-detector introduces a represented criterion doing the evaluation, which is structurally output-matching with the consequence relocated to shutdown. Whether a genuine persistence-coupling — one with no represented criterion — can be constructed for engineered systems is unresolved.**
*Grounding: HONEST LIMIT — names where the derivation reaches its edge*

---

*Author: Alex Liu*
*Part of the Apeiron framework series*
*License: CC BY-NC 4.0*
