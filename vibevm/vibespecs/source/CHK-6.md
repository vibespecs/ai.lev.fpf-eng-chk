# CHK.6 - Qualify Checklist Criteria and Checking Means: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## CHK.6:5 - Archetypal Grounding {#archetypal-grounding}

A team describes an importer as preserving item identifiers, reporting duplicate identifiers and retaining the previous catalogue when parsing fails. The description embodies assumptions about the team's use. A proposed generated check asks only whether an input file was accepted.

That check establishes none of the three described properties. A17 can become 1 during an otherwise successful import. A successful run also says nothing about duplicate reporting or the state after a parse failure.

The team constructs these qualification cases:

| Case | Distinction to establish | Observation capable of supporting it |
| --- | --- | --- |
| Valid catalogue with identifier A17 | Identifier preserved, rather than replaced or normalized unexpectedly. | Compare the input identifier with the stored identifier for the corresponding item. |
| Two records with the same identifier | The described duplicate report occurs for that input. | Inspect the returned report and its association with the duplicate records. |
| Malformed input with a known prior catalogue | Parse failure leaves the prior catalogue intact. | Observe the failure and compare the relevant catalogue state before and after it. |

These are three separate questions. A candidate checker that observes only an exit code cannot settle the third unless an independently established relation makes that code sufficient for the stated use. The team tests its proposed before/after comparison against a deliberately altered catalogue and an unchanged one. If it passes both, it has failed the intended discrimination; if it distinguishes them, that supports the comparison for those cases.

Complement that changed-catalogue challenge with a changed-question challenge. Use a constructed fixture whose before and after catalogues are both C. For these fixed facts, “Are the before and after catalogue contents identical?” has the expected answer **Yes**, while “Do the after contents differ from the before contents?” has the expected answer **No**. “Do both snapshots contain the same catalogue content?” preserves the first question and therefore its expected Yes. These answers follow from the fixture before any checker is run. A checker that returns the same verdict for the opposite conditions misses the question; one that changes the first answer merely because it is reworded is unstable on that case. Passing these contrasts supports only this bounded discrimination.

To examine grouped judging, give a model the same before and after snapshots C, plus a report headed “Import summary”. Before any output, content identity has expected **Yes**, and the presence of that heading has its separate expected **Yes**. Compare the identity verdict when asked alone and when asked alongside the heading question, with the same evidence supplied. The extra question changes neither snapshot nor the identity predicate. Repeat the contrast with a fixture whose after snapshot changes A17 to 1: identity is then **No** in both arrangements, while the heading answer stays Yes. If grouping changes either identity verdict, investigate or restrict that arrangement; do not average the two distinct questions into a pass. Combining repeated identity verdicts still has to answer to these fixture facts. Where grouped judging preserves the needed distinctions at lower cost, keep it. For actual stored data, an adequate direct comparison remains the cheaper starting choice.

A known malformed-input case with an unobserved post-state remains unresolved. Tool failure is not an importer failure or success. Local parser correctness does not settle the encompassing response and catalogue state; CHK.5 connects those contributions.

For the workshop display, “readable” may be judged from a desktop preview while participants will read the projected content from the back of a room. Qualification varies the viewing condition relevant to the exercise and asks a representative participant to interpret the actual content. A font-size threshold can be a useful local proxy only if its basis supports that use. Reconsider that proxy if glare or contrast makes text unreadable despite the chosen size.

Both examples are constructed probes. They illustrate how to challenge a claim, not measured checker performance.

## CHK.6:6 - Bias-Annotation {#bias-annotation}

People tend to invent tests that confirm their implementation. Generated criteria and generated answers can share the same blind spot. Recover a failure from the receiving work, seek an unlike case where it matters, and distinguish the data used to tune a checker from the evidence used to judge its broader use.

A benchmark's accessible cases can underrepresent the domain or participants who bear false failures. Make that limit part of the reliance decision.

## CHK.6:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | Repair |
| --- | --- |
| A fluent generated rubric is treated as qualified. | Recover provenance and challenge a consequential distinction. |
| Two agreeing agents establish an unobserved fact. | Obtain an adequate observation or a judgement supported by different grounds. |
| A high average hides a decisive false pass. | Inspect the case and receiving inference that the intended use cannot tolerate. |
| Training reward is treated as runtime assurance. | Test the actual current checking arrangement and subject question. |
| A checker is qualified once for all future models and tools. | Reopen the affected scope when observation or judgement behavior changes. |

## CHK.6:10 - Architectural Rationale {#architectural-rationale}

Qualification is independently triggered when the adequacy of criteria or checking means becomes uncertain. Folding it into every ordinary use wastes effort; omitting it from design lets repeated unsupported answers accumulate.

An applicable prior qualification can settle the uncertainty. Otherwise begin with a concrete difference and scale the evidence to the intended reliance, using direct executable tests or competent human judgement as appropriate.

## CHK.6:11 - SoTA-Echoing {#sota-echoing}

Which checking means and qualification effort fit the intended reliance? **Adopt** a direct comparison for an explicit observable property; **adapt** selective rubric or pairwise judging for a genuinely interpretive or relative question, with discriminating cases when its adequacy is uncertain. These are serious alternatives, not successive compulsory stages. In §§4.2 and 5, inspecting identifier or catalogue equality supplies the relevant grounds directly. Asking a model for a persuasive overall score adds cost without settling those properties. Pairwise judging can instead help choose between two explanations, but the preferred one still needs a separate answer to an absolute suitability question.

[Selective Checklist Evaluation][SELECTIVE] supplies a current rival to full-rubric/direct scoring, with effects that differ by setting and comparison mode. It warrants choosing and qualifying the mode for the receiving question, not declaring one universally superior. The study by [Hong and colleagues](https://arxiv.org/html/2607.12835v1) supplies counterevidence about detail and uneven emphasis in generated criteria. Section 4.2 therefore examines consequential errors, missing answers and induced weighting alongside judgement cost. The extra qualification is worthwhile when it can defeat misplaced reliance or select better means; an applicable prior qualification remains sufficient for its unchanged scope.

The study by [Bagaria and colleagues](https://arxiv.org/html/2609.02942v1) supplies bounded counterevidence about judges responding to changed answers and reversed criteria. Its generated and qualitatively inspected contrasts leave uncertainty about some expected verdicts. The adaptation in §§4.2 and 5 fixes expected answers from a simple fixture, then varies subject facts or question meaning separately. [RIPD](https://arxiv.org/html/2602.13576v1) supplies a further benchmark-versus-target counterexample motivating examination after rubric edits; it does not qualify a particular deployed judge.

For single, grouped or repeated model judgements, **adapt** protocol comparison to the consequential uncertainty in §§4.1–4.3 and the fixed-fixture case in §5. [RuVerBench v2](https://arxiv.org/html/2606.29920v2) supplies counterevidence about prompting, grouping and voting under long research/coding contexts; its selected binary cases exclude substantial ambiguity. [PReMISE v1](https://arxiv.org/html/2605.30803v1) separates stability from preference fit and robustness under model-mediated evaluation. Neither determines this deployment's best arrangement. Compare saved calls with consequential errors and examination effort; retain adequate prior qualification, and reopen its affected scope when a changed arrangement can alter a relied-on answer.

[AutoChecklist][AUTOCHECKLIST] and [RLCF][RLCF] supply criterion refinement and checklist-feedback training alternatives. **Reject** their benchmark or training gains as substitutes for qualifying this checker. [CHERRL](https://arxiv.org/html/2606.04923v1) and [Rubric Dropout](https://arxiv.org/html/2608.11669v1) expose proxy exploitation and divergence in bounded training settings; the latter's single-run configurations and fallible external judge limit the result. Its training intervention gives no general reason to omit operational checks. Section 4.2 instead examines actual results and new cases beyond the optimized signal.

The deliberate trade-off is the cost of obtaining discriminating grounds against the cost of a consequential false answer. None of these studies supplies a common error/cost ranking for every domain. [Anthropic's harness-design account][ANTHROPIC2] supplies a worked calibration candidate as models and tools change; [ME.11][ME11] and [ME.14][ME14] guide the local trial and worth comparison when the choice remains consequential. Reopen qualification for a material criterion, tool or use change, an unexplained verdict on a known contrast, or a cheaper adequate observation.


## CHK.6:End {#end}

[SELECTIVE]: https://aclanthology.org/2025.emnlp-main.538/
[AUTOCHECKLIST]: https://arxiv.org/html/2603.07019v1
[RLCF]: https://arxiv.org/html/2507.18624v2
[ANTHROPIC2]: https://www.anthropic.com/engineering/harness-design-long-running-apps
[ME11]: spec://ai.lev/fpf-eng-me/contract/ME-11#root
[ME14]: spec://ai.lev/fpf-eng-me/contract/ME-14#root
