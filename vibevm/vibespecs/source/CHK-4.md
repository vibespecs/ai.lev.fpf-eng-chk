# CHK.4 - Use a Checklist to Answer Questions and Act on the Results: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## CHK.4:5 - Archetypal Grounding {#archetypal-grounding}

Set S has twenty readable cards matching wording v2 and is assembled for delivery. Count/readability was observed at 10:00, wording at 10:05 and assembly at 10:10. The answers were entered at 10:12.

At 10:15, the facilitator changes the comparison description to v3, replacing one phrase.

| Current information | Answer to “Does S match v3?” | Useful continuation |
| --- | --- | --- |
| S is known to be unchanged since its comparison with v2; the changed phrase differs. | **No.** The retained content observation and the v3 description already establish a mismatch. | Decide whether to change the cards, description or intended exercise. A new inspection is unnecessary to establish this negative answer. |
| S may have been replaced; current wording is not known. | **Unknown.** The old observation no longer settles current content. | Inspect the affected content or obtain another adequate current result. |
| The affected card has been replaced and compared with v3; sufficient grounds remain for the other cards. | **Yes**, for the wording question on those combined grounds. | Examine whether handling also affected count, readability or assembly. |

In this constructed case, the facilitator decides to keep v3 and replace the affected card. Replacement is the selected work. A subsequent comparison establishes the new answer. If opening the set and changing a card could leave it incomplete, recounting is useful. If the remaining cards were protected and their wording unchanged, repeating every wording comparison adds no corresponding gain.

The v2 answer remains a historical answer to its actual question. Recording the v3 answer later does not alter when the earlier observation occurred, and neither observation alone establishes when a condition first became true.

A spill can make already checked cards unreadable while their wording and the completed printing work remain unchanged. Observed damage supports a current negative answer to readability; it does not erase the earlier work. In another branch, the workshop is cancelled while every physical-set answer remains true. The decision about further preparation then uses the changed occasion and value of the work, rather than trying to turn the physical answers negative.

For an importer, the agent's message “error handling implemented” concerns its account of work. To answer whether malformed input leaves the previous catalogue intact, inspect the relevant before/after state using a suitable check. A failed observation tool leaves that question unresolved even if the implementation might in fact be correct. Conversely, a demonstrated state difference can already establish No; another run is not needed just to avoid recording a negative answer.

## CHK.4:6 - Bias-Annotation {#bias-annotation}

Completion pressure can turn uncertain or negative answers into apparent passes. An expert may also rely on tacit judgement that others cannot recover. Record the grounds proportionately to how the result will be used, and preserve an honest unresolved answer.

Familiarity can encourage both stale reuse and unnecessary repetition. Examine relevance of the actual premises rather than preferring either “always recheck” or “already green.”

## CHK.4:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | Repair |
| --- | --- |
| A revised description turns a known mismatch into “unknown.” | Use the retained subject facts and new description to answer the comparison directly. |
| An old pass is copied to a subject that may have changed. | Recover current grounds or state the unresolved question. |
| A completion entry is taken as evidence that work happened. | Obtain the observation or competent result on which the answer depends. |
| A negative answer automatically orders corrective work. | Separate the comparison from the decision about subject, description and use. |

## CHK.4:10 - Architectural Rationale {#architectural-rationale}

Question selection and checker qualification happen at different scopes from an actual answer. Repeating them in every use wastes effort; omitting them when their premises fail produces unsupported certainty. This Method uses adequate supplied criteria and checking means; when either proves inadequate, return the affected question to CHK.1 or CHK.6.

Keeping decision and corrective work separate preserves the user's choice to revise a mistaken description.

## CHK.4:11 - SoTA-Echoing {#sota-echoing}

How much recovery or fresh checking is needed after an interruption or changed premise? **Adopt** sufficient existing grounds for the actual question, and **adapt** the resumption cue to the missing context. The serious alternatives are a position marker, a marker with question-specific content, and obtaining a fresh observation. Section 4.1 chooses among them by whether the question and prior grounds are recoverable and still apply, including the cost of that recovery.

A bare “card seven” is enough only when the performer already knows what was compared and against which description. When that context is missing, retaining it avoids either guessing or repeating all comparisons. The deliberate trade-off is a little more preparation and reading for a more dependable continuation. If recovering a trustworthy record costs more than an adequate direct inspection, inspect again. In §5, however, known unchanged S and the changed v3 phrase already support No: another observation adds no needed information. If S may have changed, current inspection supplies a missing basis. These branches **reject** both automatic repetition and automatic reuse.

[Chen and colleagues' laboratory experiments](https://doi.org/10.1016/j.ergon.2023.103453) supply a contextual-cue candidate and comparisons with other task support, with effects that depend on the experimental condition and measure. They motivate testing which content matters; they do not rank every workplace recovery arrangement or establish a universal interface. R7 and R10 distinguish useful work from reporting. [Anthropic's 2025 account][ANTHROPIC1] supplies a concrete testing-before-pass arrangement; its [2026 account][ANTHROPIC2] motivates revisiting the means as capabilities change. Those engineering cases do not establish that every resumed occasion needs a new test.

The selected line spends recovery effort only on information needed for a sound current answer, while preserving historical and unaffected answers in §§4.2–4.3. Reopen the choice when a cue fails to recover the next operation, a subject or basis changes, or a cheaper adequate observation becomes available. If cue alternatives remain indistinguishable on that use question, keep the simpler one.


## CHK.4:End {#end}

[ANTHROPIC1]: https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents
[ANTHROPIC2]: https://www.anthropic.com/engineering/harness-design-long-running-apps
