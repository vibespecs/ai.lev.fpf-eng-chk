# CHK.2 - Construct a Checklist Template That Preserves Its Questions: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## CHK.2:5 - Archetypal Grounding {#archetypal-grounding}

The selected card questions become this reusable template:

| Set and comparison description | All described cards present and readable? | Wording matches the described edition? | Set assembled for delivery? |
| --- | --- | --- | --- |
| Identify the physical set and the description of its contents | Answer; count/inspection basis; observation time when reused | Answer; comparison basis and observation time | Answer; assembly observation and time |

A constructed instance supplies the references and grounds:

| Set and comparison description | All described cards present and readable? | Wording matches the described edition? | Set assembled for delivery? |
| --- | --- | --- | --- |
| S; twenty cards, wording v2 | Yes: twenty present and readable, observed 10:00 | Yes: all cards compared with v2, observed 10:05 | Yes: assembled, observed 10:10 |

Suppose the wide table on a small screen separates the answer from its S/v2 reference. Transpose the same information so the recipient can recover both together:

| Question for S against the description of twenty cards with wording v2 | Answer and basis |
| --- | --- |
| All described cards present and readable? | Yes: twenty present and readable, observed 10:00 |
| Wording matches v2? | Yes: all cards compared with v2, observed 10:05 |
| Set assembled for delivery? | Yes: assembled, observed 10:10 |

If entries are recorded at 10:12, that time describes the recording. It neither changes the observation times nor shows when each condition first became true. A split view for counting and a view for wording comparison retain the S/v2 references and the relevant observation grounds. A detached green square cannot do that.

For an AI-assisted importer, a template can ask for an observed catalogue before and after a malformed input, with a reference to the input and the comparison performed. A field headed “Tests pass” loses the specific question if it is detached from those cases. When an observation tool fails, the form supports “unknown: post-import catalogue was not obtained”; it does not coerce the agent into a positive completion entry.


## CHK.2:6 - Bias-Annotation {#bias-annotation}

A form convenient for its author may be difficult on a phone, inaccessible to a participant or opaque to an AI tool. Colour can supplement but cannot carry the only answer distinction. Specialist abbreviations and apparently obvious dates deserve testing with intended users.

Recorded evidence privileges what can be captured. Allow a relevant conversation or observation to contribute without pretending that an empty attachment field invalidates it.

## CHK.2:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | Repair |
| --- | --- |
| A copied tick survives while its question or edition changes. | Preserve the association or reopen the answer for the new question. |
| Every blank means failure, or every filled cell means success. | Give absence, unresolved answers and supported negative answers their actual meanings. |
| A timestamp silently becomes attainment time. | Name whether it records observation, entry or an independently observed change. |
| Each heading is treated as a new type or state. | Recover the subject and relation the heading expresses; keep layout as representation. |

## CHK.2:10 - Architectural Rationale {#architectural-rationale}

Template construction is separate from question selection because a sound question set can be damaged by representation. It is separate from fitting because a clear form can still appear at the wrong time or in an unused tool.

Editable text and tables are useful when people adapt, transpose or split the aid. A diagram can be useful when it preserves a conditional relation better. The choice follows the receiving action and demonstrated preservation, not a universal preference for one medium.

## CHK.2:11 - SoTA-Echoing {#sota-echoing}

When is a local form worth maintaining alongside a shared checklist? **Adapt** R7's template/instance and transposed-view practice together with R10's local interpretation: retain shared question meanings and provide a different view only where a receiving action needs it. The serious alternatives are one fixed master form and independently adapted local copies. The master is preferable when it already permits the needed interpretation; independent copies can be cheaper for a small one-off use but introduce a continuing update problem when reused.

Section 4.3 compares these choices with the same filled cases and includes preparation, reference recovery and later updates. In §5, the small-screen condition justifies transposition because the subject/basis and answer can be read together while the three questions, answers and grounds remain unchanged. It does not justify another checklist meaning. If the wide form already shows those associations adequately, keep it. If several views change frequently, accept the setup cost of deriving them from shared content when it avoids more costly inconsistent updates; a single occasional copy need not acquire that machinery.

R7 and R10 supply the competing arrangements and preservation question, not comparative reading-time measurements. The study by [Facey and colleagues][FACEY] supplies failure evidence about documentary completion and actual use. It supports preserving unknown, observation and record meanings in §§4.1–4.2; it does not show that a particular layout is superior. **Reject** uniform appearance as the selection criterion when it hides a needed distinction, and reject richer fields whose later usefulness does not warrant their entry cost.

The conditional choice improves access at the deliberately accepted cost of maintaining another expression of the same questions. Where neither interpretation nor total effort can be judged from the filled cases, compare representative use through [EXD.6][EXD6]. Reopen the choice when a recipient loses a reference, an answer meaning diverges after an update, or the extra view costs more than the difficulty it removes.


## CHK.2:End {#end}

[FACEY]: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0298224
[EXD6]: spec://ai.lev/fpf-eng-exd/contract/EXD-6#root
