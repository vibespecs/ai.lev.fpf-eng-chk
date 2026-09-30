# CHK.5 - Reconcile Checklist Results Across Shared Work: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## CHK.5:5 - Archetypal Grounding {#archetypal-grounding}

For a workshop, the venue technician checks projection and sound; the facilitator checks materials against the exercise; the organizer coordinates the session. Their local results include:

| Local claim | What it supports | What remains for the session |
| --- | --- | --- |
| Projection and sound worked in room A under the observed setup. | Equipment use under that setup. | Actual examples are current and visible from the intended seats. |
| Card set S matches wording v2 and is assembled. | The stated material conditions. | Those examples serve the exercise and can be used with the room arrangement. |
| Participants and time are confirmed. | The stated attendance and timing conditions. | Preparation and resource use fit that occasion. |

The shared account binds these claims to session W, room A and materials v2. The facilitator projects the actual example and compares it with the cards. That action contributes to both checking the presentation and preparing the exercise. A sharp image containing an obsolete example yields a useful equipment observation and an unresolved or negative content comparison. The person who notices the content problem brings that finding into the session decision instead of passing along an unqualified overall “ready.” The local equipment answer can remain true while the joint result needs another action.

If the three participants are together, can inspect the same materials and will act immediately, this reconciliation can remain a spoken exchange. If another technician will take over after a room change, the shared operating view needs to preserve W, the new room, retained material grounds and the room questions still open. An existing view that already supplies those distinctions is sufficient; a second reconciliation report would add another copy to update.

The same difficulty can occur when one facilitator also packs the cards and operates the projector. After revising the slides, she can forget that the printed set still carries the earlier wording. One performer does not make those contributions consistent; compare their actual subjects and editions just as in the multi-person arrangement.

If the venue moves W to room B, prior room-A observations remain historical. Room-B projection, audibility and relevant arrangement questions reopen; unchanged card wording need not be compared again merely because the room changed.

If the facilitator instead revises one example, the content comparison and its display can reopen while room-specific equipment facts remain useful. If handling the cards changes the set, affected physical questions reopen too. The structure has several distinct dependencies, not one inevitable progression from “unprepared” to “ready.”

No technician has been assigned in a third branch. That is an enabling gap. In a fourth branch, the technician is assigned but no one knows whether projection works. That is a missing observation. A shared “in progress” entry hides the difference and cannot select the right next action.

For an importer, parser checks and storage checks can both pass locally while their integration mishandles an error. Reconciliation connects the supplied parser result, importer's response and resulting catalogue state. Whether the catalogue entries are suitable for publication remains a different question. A session restart preserves those distinctions so a new agent can reuse grounds or perform only the missing check.

## CHK.5:6 - Bias-Annotation {#bias-annotation}

A shared view often reflects what the coordinator can see. Local work or a participant's uncertainty can disappear during aggregation. Allow the person supplying an observation to correct its shared interpretation.

A central record can also shift maintenance work to whoever has the least authority to refuse it. Include that burden when deciding how much reconciliation is useful.

## CHK.5:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | Repair |
| --- | --- |
| All local passes are treated as a whole-result pass. | Examine the combining relation and the whole's additional conditions. |
| Everyone uses “ready” with a different meaning. | Recover the actual local claims before summarizing. |
| A missing assignment and an unknown result share one status. | Name whether the next contribution is enabling work or an observation. |
| Every change restarts every checklist. | Follow the changed premise through actual reliance and retain sufficient unaffected grounds. |
| A master form displaces local views that participants need. | Connect the needed claims at the smallest worthwhile granularity. |

## CHK.5:10 - Architectural Rationale {#architectural-rationale}

Local checking and shared reconciliation solve different problems. Sound local answers can still concern incompatible occasions or omit a combining condition.

The selected arrangement preserves local usefulness and adds only the shared claims with real consumers. A single shared checklist remains a valid simpler alternative when all participants can interpret and maintain it at low cost.

## CHK.5:11 - SoTA-Echoing {#sota-echoing}

When should local checks be reconciled in conversation, an operating view or a separate retained account? **Adopt** a shared question with recoverable contributing claims, using R10's operational/coordination practice and [OPS.4][OPS4]. **Adapt** the communication arrangement to who will rely on those claims and when. Direct exchange and an already adequate operating view are serious alternatives to another maintained record.

Sections 4.1–4.3 choose the arrangement for the same needed session conclusion. In §5, participants who can inspect the same materials and act together can resolve the question in conversation. A later technician cannot depend on having heard that exchange; the existing operating view can preserve W, the changed room, still-valid material grounds and missing room observations. Adding a second report provides no further needed distinction when that view is sufficient. Accept the extra recording and update effort only when a later consequential use still lacks its subjects, grounds or changes.

R7's dependency cases and R10's views supply the practice comparison, while Gawande's open team exchanges supply a coordination candidate for trouble outside fixed questions. These accounts explain why a shared conversation can be the useful action; they do not measure the cost of every arrangement. [Anthropic's account][ANTHROPIC1] supplies bounded engineering evidence for retaining criteria and progress across agent sessions. It motivates recoverable continuation, not a universal reporting format or cadence.

The defect overcome is a lost local-to-whole dependency or an unrecoverable handover, not a low completion percentage. **Reject** aggregation of labels as the substitute for that relation. The selected arrangement deliberately trades communication and maintenance effort for the specific later reliance it enables; where an existing exchange or view suffices, it adds no new record. Reopen the choice when a new participant, delay, changed work or tool prevents recovery of a consequential connection, or when duplicate maintenance outweighs its remaining use.


## CHK.5:End {#end}

[OPS4]: spec://ai.lev/fpf-eng-ops/contract/OPS-4#root
[ANTHROPIC1]: https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents
