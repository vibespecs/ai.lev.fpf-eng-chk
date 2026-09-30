# CHK.1 - Select Checklist Questions for a Work Result: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## CHK.1:5 - Archetypal Grounding {#archetypal-grounding}

A facilitator describes set S as twenty readable cards with wording v2, assembled for delivery. She assumes those cards will support a comparison exercise. The organizer's draft asks only, “Are the cards ready?”

| Selected question | Basis and contribution | Boundary |
| --- | --- | --- |
| Are all twenty described cards present and readable? | Count and inspect S against the contents description; expose omissions and unusable cards. | Does not establish instructional suitability. |
| Does the wording of each card match v2? | Compare the actual wording with the identified description. | A match does not show that v2 is a useful choice. |
| Is the identified set assembled for delivery? | Observe the actual collection and packaging for this delivery. | Assembly can persist while wording becomes obsolete. |

The facilitator retains a separate exercise trial because a complete, readable and accurately worded set can still confuse participants. That trial uses domain judgement about the exercise. Selection has produced three useful physical-set questions and an explicit return for the encompassing question.

In a catalogue importer, “Did the file import?” does not establish identifier preservation, duplicate reporting or preservation of the previous catalogue on parse failure. The team recovers those three described properties and selects questions about each. Input A17 becoming stored identifier 1 demonstrates why generic success is inadequate. Whether the three properties are enough for the team's actual use remains a further selection question.

Suppose the cards are produced on a shared printer. A complete file does not establish that the printing service can produce readable cards at the needed occasion. The selection follows one extra link: the printer's configuration and the person able to use it. If the print setup itself is being changed, questions about that enabling work become useful too. The design file describes the proposed cards; materials enter the print run, which produces the physical set. Questions about the setup, its description, the printing Method and the actual run concern different subjects. Preserve those relations when connecting their answers to the card preparation. If those enabling results are already competently supplied, the organizer can use them instead of designing a second printer-maintenance checklist.

For a community running the seminar, distinguish the organizer's recruitment and support work, members' learning and practice, and their joint use of the exercise. Sending invitations does not establish attendance; attendance does not establish a member's ability to use the distinction; individual ability does not establish that members coordinate their contributions. A useful selection might therefore ask what support was provided, what a member can actually do, and what happens in the joint exercise. Choose only questions that matter to this community's work. One person may both organize and participate, but an answer about her organizing work does not answer the question about her learning. Return the capability question to [HCD.3][HCD3] and an organizational participation difficulty to [OCE.10][OCE10].

These cases are constructed. The gain illustrated is a more discriminating question set, not an empirical claim about fewer errors.

## CHK.1:6 - Bias-Annotation {#bias-annotation}

Selection reflects the experience of those asked. Frequent, visible failures can crowd out rare consequential ones, and the person creating the list may never see the costs borne by its user. Include relevant practitioners and people consuming the result. Ask what their work reveals that the proposed questions miss.

A generated list reflects its prompt, examples and model as well as the task. Treat its fluency as help in proposing questions, not grounds for coverage.

## CHK.1:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | Repair |
| --- | --- |
| “Everything ready?” hides independently varying conditions. | Split only the distinctions that change the next move, as in the card example. |
| A copied or generated list supplies its own authority. | Recover criterion provenance, receiving use and a plausible uncovered failure. |
| Every domain instruction becomes a checkbox. | Keep the full instruction available and select the questions worth attention at this occasion. |
| Matching a description is treated as proof of usefulness. | Examine the assumption connecting those characteristics to the encompassing use. |

## CHK.1:10 - Architectural Rationale {#architectural-rationale}

Selection is independently useful because a well-presented, faithfully completed list can ask the wrong questions. Construction cannot repair absent coverage merely by adding fields, and checking cannot validate a criterion merely by applying it.

Use direct skilled attention without a maintained list for an isolated simple question or where the list's cost exceeds its contribution. A recurring, consequential omission justifies a retained question only when the aid improves that actual use.

## CHK.1:11 - SoTA-Echoing {#sota-echoing}

How should questions be selected when expert attention, description-based extraction and generated refinement are all available? **Adapt** situated selection from R7/R10 together with the proposal-and-challenge line in [AutoChecklist][AUTOCHECKLIST]: use the least costly way to expose the consequential difference, then judge the proposed question against the work and its grounds. The selected answer is conditional. An explicit, usable description favors extraction; a familiar local omission can favor direct expert selection; uncertain coverage can justify generated contrasts and refinement.

These are serious alternatives with different costs. Extraction can preserve a description's blind spot; direct expertise can miss an unfamiliar case; generation can add duplicates or plausible but unsupported criteria. [SPECA](https://arxiv.org/html/2602.07513v1) supplies a concrete specification-derived audit alternative and counterevidence about mistaken scope assumptions. Its single case and correct-specification premise do not establish general coverage. AutoChecklist supplies evaluated generation/refinement methods in its stated tasks, not evidence that generation wins for this workshop or every domain. R7/R10 supply the practice connection to subjects and work; they do not compare model performance.

Section 4.2 therefore selects the proposal method by the missing distinction and includes adjudication effort. For the three explicit importer properties in §5, extraction plus a practitioner's usefulness challenge supplies the stated questions without a generation loop. If a plausible imported result satisfies all three yet defeats the intended use, comparing that result can expose an additional question. **Reject** automatic iteration merely because more criteria can be produced. Accept the added examination cost when it can reveal such an unresolved consequential difference; retain direct selection when it already provides adequate coverage.

The sources do not rank these alternatives at equal effort across domains. Where that ranking changes a substantial investment, use a representative local comparison through [ME.11][ME11] and [ME.14][ME14]. Reopen the local choice when a missed difference defeats coverage, the description's usefulness is in doubt, or another proposal method produces needed distinctions at lower total effort.


## CHK.1:End {#end}

[HCD3]: spec://ai.lev/fpf-eng-hcd/contract/HCD-3#root
[OCE10]: spec://ai.lev/fpf-eng-oce/contract/OCE-10#root
[AUTOCHECKLIST]: https://arxiv.org/html/2603.07019v1
[ME11]: spec://ai.lev/fpf-eng-me/contract/ME-11#root
[ME14]: spec://ai.lev/fpf-eng-me/contract/ME-14#root
