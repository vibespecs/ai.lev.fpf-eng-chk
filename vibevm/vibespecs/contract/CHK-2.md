# CHK.2 - Construct a Checklist Template That Preserves Its Questions {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

## CHK.2:1 - Problem frame {#problem-frame}

**Use this when** selected questions are becoming a reusable form, or an existing checklist is being transposed, split, translated or moved into another tool. A row of green cells is easy to scan, but its user can no longer tell which set, description edition or observation each cell concerns.

This Method constructs a checklist template: a reusable description of the questions, their interpretation and how answers can be expressed. A filled instance records answers for an identified occasion. Start by carrying one selected question from its wording to a plausible filled answer.

The result is a form that preserves the selected distinctions in its intended use. If the difficulty is missing or unjustified questions, return to CHK.1 or CHK.6. If the existing representation already works, retain it.

## CHK.2:2 - Problem {#problem}

A heading can survive a redesign while its meaning disappears. A copied checkmark can lose the subject it refers to; a date can become ambiguous between observation and entry; a binary checkbox can force an unresolved question into a false answer.

The construction problem is to make truthful interpretation easy without turning the aid into a burdensome evidence repository. The template's layout serves the question set. It does not define the kinds or states of the things being checked.

## CHK.2:3 - Forces {#forces}

| Tension | Practical implication |
| --- | --- |
| Compact scanning and sufficient meaning | Put common references once, while preserving their reach to every answer. |
| Reuse and particular subjects | Make the places for binding actual subjects and descriptions unambiguous. |
| Simple answers and real uncertainty | Provide a way to express unresolved or inapplicable questions where they occur. |
| Local convenience and shared interpretation | A split view retains the associations needed by another participant. |
| Nearby help and reading burden | Explain a difficult distinction where it is used; avoid copying entire manuals. |

## CHK.2:4 - Solution {#solution}

### CHK.2:4.1 - Carry the question and its interpretation together {#carry-the-question-and-its-interpretation-together}

Take the selected questions and coverage from CHK.1 or another adequate source. Identify information shared across the list, such as the physical set and comparison description. Place it where users can see its scope. Keep question-specific conditions with the question.

Phrase the questions in the language practitioners use for their actual work: the card set, print run or catalogue import. Adapt the selected subjects, conditions and questions as well as their names. Replacing “target system” with “cards” is insufficient if “ready” still hides an unfamiliar or unsuitable account of readiness. Compare the wording with a real case and the recipient's way of working. [EXD.1][EXD1] helps recover the explanation needed for that use. Framework distinctions can guide the author's reasoning without requiring every recipient to learn their terminology.

Develop ambiguous headings with someone who understands the work. For a printing checklist, distinguish the person who wrote the comparison description, the system assigned to checking, and the system that actually performed this check. One person may occupy all three positions, but a name under “Responsible” does not tell the recipient which relation is asserted. A system's role kind and assignment, its capability and its performed work remain distinct; [OCE.6][OCE6] helps when the assignment or enabling arrangement itself needs repair. For a file or description, name the actual relation, such as input to printing or basis of comparison. Use the resulting practitioner wording in the form and retain further explanation only where it helps interpretation.

For each answer, make recoverable what is being asked, what counts as an answer and what grounds could support it. A direct instruction may name the observation; a more complex judgement may point to a domain procedure. [ME.8][ME8] supplies the broader description of how to carry out the Method. A short checklist can refer to that description without trying to replace it.

Distinguish a reusable instruction from a filled claim. “Count the cards against the contents description” is part of the template's help. “Twenty cards present in S, observed at 10:00” is an instance answer and its basis. [FPF A.3.2][A32] supplies the MethodDescription distinction where the template substantively describes a Method; a table label alone does not establish that membership.

### CHK.2:4.2 - Give answers enough expressive range {#give-answers-enough-expressive-range}

Use answer forms that preserve consequential distinctions. In the examples here, **Yes** asserts the question's condition on the stated basis; **No** denies it on such a basis; **unknown** says the available grounds do not settle it; **not checked** says no check was performed for this occasion. These are local answer meanings, not a universal state taxonomy. An old adequate result may be reused even when no fresh check occurred.

Use **not applicable** only with a reason why the question does not concern this subject or use. Missing access is a reason for an unresolved answer, not for inapplicability. Some questions call for a quantity, identified alternative or short account rather than Yes/No. Choose that form when it carries the distinction more faithfully.

When a label such as “prepared” abbreviates several conditions, recover which conditions hold together, which are alternatives, and which depend on another subject. A later label in a displayed list does not establish every earlier condition. A supplied plan can answer a question about planning while leaving resource availability or actual performance unanswered. Keep those conditions explicit enough for the intended action; an ordinary explanation can suffice.

Where the aid supports planning, distinguish an expected occasion for a condition from when it actually holds, is observed, and is recorded. Preserve the scope of a question that continues across several editions or attempts, as well as questions confined to one edition. Repeated attempts and alternative paths do not form a universal ladder in which every answer stays positive.

Add observation time, description edition, performer or evidence reference when the receiving use depends on it. Keep entry time distinct from observation time. Avoid fields with no practical consumer. A three-question aid used immediately can be spoken; a record reused tomorrow usually needs enough context to recover its grounds.

### CHK.2:4.3 - Transform the form and compare the meaning {#transform-the-form-and-compare-the-meaning}

Choose paper, editable text, a table or a working application according to the occasion. Transpose or split the presentation only while preserving the associations needed to interpret an answer: subject, question, comparison basis, answer and grounds. Keep shared reference information visible or directly reachable in each local view.

Retain one form when it serves the receiving uses. Make another view only for a specific access or interpretation difficulty, and compare both with the same filled cases. Include the effort of preparing the view, recovering references during use and updating affected copies. Deriving views from shared content can reduce divergent copies; a separate generator is worthwhile only when that saving exceeds its setup and maintenance cost.

For a maintained aid, make clear which question set and template edition are in use. A corrected wording question in the working application can coexist unnoticed with an obsolete printed form or presentation. Derive needed views from the same maintained content where practical; otherwise identify how affected copies are updated or withdrawn. Preserve the earlier question and comparison basis when historical answers still refer to them. The useful result is a recoverable current form and interpretable earlier records; a separate modeling application is worthwhile only if it helps sustain that result.

Inspect what entering an answer does in the chosen tool. A mark may record a comparison, but the application may also use it to release a file or notify another participant. Make that additional effect apparent and preserve the distinct decision behind it. A truthful “matches v3” answer does not, by its meaning alone, select distribution of v3. Use separate controls when the two moves need separate decisions.

An outline that puts each item under one heading can hide another relevant relationship. One comparison of the projected example with the cards may contribute both to display preparation and to exercise preparation. Preserve both uses when they affect the next action; use a cross-reference or a small relation table if one parent heading cannot express them. Do not infer that the subject has only one such relation from the form's single indentation.

Replay one satisfactory answer, one negative answer and one unresolved case in the proposed form. Ask a representative recipient to recover the actual question and next move. [EXD.1][EXD1] identifies what explanation the user needs; [EXD.6][EXD6] helps compare the repair with its burden. Return a missing distinction to the template, a misunderstood question to selection, and inaccessible observation to CHK.3.

When transfer changes the speaker or recipient, recover relative references through [FPF A.6.P.RI][A6PRI]: “my cards” or “our current description” can acquire a different referent in a copied view. Check the question's associations after the change even when its words are unchanged.

## CHK.2:7 - Conformance Checklist {#conformance-checklist}

Inspect an actual filled example, not only the blank template:

- Can the intended recipient recover the subject, question, comparison basis, answer and sufficient grounds?
- Can the form represent a negative answer and an unresolved one without conflating them?
- Is any inapplicability reason about the question's scope rather than missing evidence?
- Do shared references and answer meanings survive the actual transpose, split or tool transfer?
- Does every retained field help the intended use, and is nearby help enough for the expected user?

## CHK.2:9 - Consequences {#consequences}

Users can adapt the form without losing the differences that matter. Shared information can be stated once instead of repeated in every cell. The cost is maintaining its scope and links through change. More elaborate evidence fields can improve later reuse while slowing immediate work; retain them only where that trade-off is worthwhile.

## CHK.2:12 - Relations {#relations}

CHK.1 supplies questions and bounded coverage. CHK.3 consumes the usable template to arrange an occasion. CHK.4 supplies real answers, and CHK.5 consumes local views without assuming that identical layouts imply identical claims.

[ME.8][ME8] supplies the broader Method description; [EXD.1][EXD1] and [EXD.6][EXD6] supply explanation design and comparison. [FPF A.3.2][A32] governs an actual MethodDescription claim; [A.6.P.RI][A6PRI] supplies recovery of references whose meaning depends on the participant or occasion.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-chk/contract/CHK-1#root or an existing question set; spec://ai.lev/fpf-eng-me/contract/ME-8#root; spec://ai.lev/fpf-eng-exd/contract/EXD-1#root, spec://ai.lev/fpf-eng-exd/contract/EXD-6#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-chk/contract/CHK-3#root @status:spec/done

#source spec://ai.lev/fpf-eng-chk/source/CHK-2

[EXD1]: spec://ai.lev/fpf-eng-exd/contract/EXD-1#root
[OCE6]: spec://ai.lev/fpf-eng-oce/contract/OCE-6#root
[ME8]: spec://ai.lev/fpf-eng-me/contract/ME-8#root
[A32]: spec://ai.lev/fpf-spec/contract/A-3-2#root
[EXD6]: spec://ai.lev/fpf-eng-exd/contract/EXD-6#root
[A6PRI]: spec://ai.lev/fpf-spec/contract/A-6-P-RI#root
