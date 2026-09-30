# CHK.6 - Qualify Checklist Criteria and Checking Means {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

## CHK.6:1 - Problem frame {#problem-frame}

**Use this when** a proposed criterion or checking means may fail to distinguish the difference that matters. This is common with inherited lists, generated criteria, model judgements, new tools and changed operating conditions. A checker can say “pass” while an importer replaces A17 with 1.

This Method establishes a bounded basis for using a criterion and its checking means, or returns a counterexample or unresolved qualification question. Start with one claim the proposed check is supposed to support and one plausible case where it could be wrong.

Reuse an applicable qualification when available. A second agent, a formal experiment or a broad benchmark is useful only when it answers a live uncertainty at worthwhile cost.

## CHK.6:2 - Problem {#problem}

A criterion can be irrelevant, vague or based on a mistaken description. A checker can implement a sensible criterion badly or observe a convenient proxy. Agreement among judges and high aggregate scores can hide the individual failure that matters to the work.

The problem is to examine both the criterion and the means of checking it before placing more reliance on their answers than the evidence supports. This differs from selecting which questions belong in the aid and from checking the actual subject on one occasion.

## CHK.6:3 - Forces {#forces}

| Tension | Practical implication |
| --- | --- |
| Useful coverage and cheap proxies | Test the consequential distinction rather than the easiest correlated signal. |
| Improvement speed and qualification cost | Start with a discriminating counterexample; expand only for the intended reliance. |
| Human judgement and executable checks | Use the means capable of observing the relevant property; neither is universally superior. |
| Aggregate evaluation and individual failures | Inspect the cases that could defeat the intended use. |
| Stable reuse and changing models or tools | Bound the qualification and identify what would reopen it. |

## CHK.6:4 - Solution {#solution}

### CHK.6:4.1 - Recover the claim, basis and intended reliance {#recover-the-claim-basis-and-intended-reliance}

Name the criterion, the question it interprets and the subject of that question. Recover the description and the assumption connecting it to useful work. Use [ME.3][ME3] when the criterion needs construction from the subject and situation.

Then name the checking means: a person applying a judgement, a comparison script, an observation tool or a model-based evaluator. What does it actually observe or consume? What answer does it produce? What will another person or system infer from that answer? [ADM.7][ADM7] supplies claim-checking distinctions from administrative practice. A method name or test file is not itself proof that the intended check occurred.

For a model judge, include the supplied evidence and instructions, the criteria grouped in each call, and any rule combining repeated verdicts when these can change the relied-on answer.

Separate two uncertainties. A criterion can faithfully express the description while the description poorly serves the work. A checking means can also fail to apply that otherwise useful criterion. Investigate the uncertainty that changes the intended use.

A cheap indirect signal can justify further examination without certifying the larger result when it passes. An obsolete edition label on the card box can prompt inspection of its contents; a current label alone does not establish that every card was replaced. Name this intended inference and next move. Challenge both false reassurance and unnecessary alarms. If people can satisfy the visible signal while bypassing the substantive work, examine whether the signal remains informative for the intended use.

### CHK.6:4.2 - Construct a discriminating challenge {#construct-a-discriminating-challenge}

Choose cases with known or competently established differences relevant to the criterion. Include a satisfactory case and a plausible failure. Vary the property of interest while holding irrelevant differences small enough to interpret the result. For a subjective criterion, recover the judgement basis and a meaningful disagreement rather than inventing a false objective threshold.

Predict which answers those differences support before inspecting the checker output. Then compare the outputs with adequate grounds for those expected distinctions. A false pass and a false failure can have different costs; inspect both where they affect the work.

Where a rubric may drive the verdict independently of the subject, also hold the subject facts fixed and change the question. Establish what answer the new predicate supports before asking the checker. A reversed condition can call for the opposite answer; if only wording changes and the question stays the same, the expected answer stays the same. This distinction tests responsiveness to meaning without requiring every wording change to reverse a result.

When uncertainty concerns the judging arrangement, compare it on those grounded cases with a cheaper or less interfering alternative. Grouping criteria can save calls; separating them can reveal interference. Repetition and a rule for combining verdicts may reduce sampling instability, but repeated agreement cannot correct a consistent error or supply independent truth. Select the arrangement from consequential errors and total effort; repeat only when that comparison can change reliance.

If the receiving use consumes a total or percentage, examine what that number means and how the questions affect it. Splitting one easy condition into ten items can increase its influence without improving the subject. Ten successful formatting checks may conceal one failed catalogue-preservation check. Challenge the implied priorities, duplicate contributions and treatment of missing answers. Keep consequential answers visible. Where a numerical aggregate is actually needed, [FPF A.19.ULSAM][ULSAM] governs the admitted measures and lawful aggregation; a convenient average does not supply its own justification.

Start cheaply. One counterexample can defeat an overbroad claim. Use a direct executable comparison when the question and observable property admit it. A selective rubric or pairwise judgement can help with an interpretive or relative question, but choosing the better of two results does not establish that either meets an absolute condition. Qualify that judging arrangement on cases whose consequential answers have adequate independent grounds. Compare false passes, false failures and obtaining those grounds as well as the cost per judgement. Broader reliance may call for representative cases, independent judgement, executable observation or a field trial through [ME.11][ME11]. Choose another reader or agent when it supplies a materially different basis, expertise or observation. Mere duplication of the same unsupported inference does not establish independence.

When work is repeatedly optimized against a score, compare earlier and later actual results on consequential characteristics and suitable new cases. A rising score can reward surface changes while the intended result deteriorates. For the importer, a more persuasive success report leaves identifier loss unchanged. Inspect the proposed shortcut and obtain evidence beyond the optimized signal. A stronger second model can help investigate disagreement, but its score still needs grounds and does not become ground truth by rank.

### CHK.6:4.3 - State the bounded result and a return condition {#state-the-bounded-result-and-a-return-condition}

State what the qualification supports: which criterion, checking means, cases, conditions and receiving use it covers. State detected defects and residual uncertainty in terms that change action. A narrow successful probe does not establish all-domain accuracy.

If the criterion misses a work question, return to CHK.1. If the form corrupts its meaning, return to CHK.2. If access or capability is missing, return to CHK.3 or its supplier. If the checker fails, repair, replace or restrict its use and repeat the affected challenge. Compare the gain with the qualification and operating cost through [ME.14][ME14].

Keep the qualification separate from actual subject answers. CHK.4 still establishes what is true of the subject on its occasion. Reopen qualification when a material criterion, model, tool, observation route or operating condition changes, or when a new counterexample defeats its scope. Changed evidence, instructions, criterion grouping or verdict combination can trigger this even with the same model and criterion. Retain qualification for the unaffected observations and inferences. Stop when further investigation cannot improve the intended reliance at worthwhile cost, and preserve the limit rather than extending the claim.

## CHK.6:7 - Conformance Checklist {#conformance-checklist}

Inspect the qualification's actual claim and probes:

- Are criterion, checking means, subject and receiving inference separately recoverable?
- Do the challenge cases vary a consequential property with adequate grounds for the expected distinction?
- Have false passes, false failures and unresolved observation been interpreted at their actual costs?
- Does any independent contribution supply a different basis rather than repeated agreement?
- Is the resulting reliance bounded, with material change and counterexample triggers for reconsideration?

## CHK.6:9 - Consequences {#consequences}

The Method can replace an attractive but uninformative check with a defensible, limited one. A single counterexample may prevent large misplaced reliance. Qualification also costs representative data, judgement and maintenance. Some questions remain uncertain or too expensive to settle; the useful outcome can be a smaller reliance claim or a different work arrangement.

## CHK.6:12 - Relations {#relations}

CHK.1 supplies proposed work questions and receives coverage corrections. CHK.2 preserves qualified meanings, CHK.3 makes observations accessible, CHK.4 performs actual checks, and CHK.5 interprets their combined use. [FPF A.19.ULSAM][ULSAM] is a conditional return when the receiving use needs numerical aggregation; ordinary separate answers require no such calculation.

[ME.3][ME3] supplies criterion construction, [ME.11][ME11] representative trial, [ME.14][ME14] worth appraisal, and [ADM.7][ADM7] checking. Qualification uses these results for the specific uncertainty in checklist criteria or means; it does not replace those Methods.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-3#root, spec://ai.lev/fpf-eng-me/contract/ME-11#root, spec://ai.lev/fpf-eng-me/contract/ME-14#root; spec://ai.lev/fpf-eng-adm/contract/ADM-7#root; spec://ai.lev/fpf-eng-chk/contract/CHK-1#root for coverage @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-chk/contract/CHK-1#root @status:spec/done

#source spec://ai.lev/fpf-eng-chk/source/CHK-6

[ME3]: spec://ai.lev/fpf-eng-me/contract/ME-3#root
[ADM7]: spec://ai.lev/fpf-eng-adm/contract/ADM-7#root
[ULSAM]: spec://ai.lev/fpf-spec/contract/A-19-ULSAM#root
[ME11]: spec://ai.lev/fpf-eng-me/contract/ME-11#root
[ME14]: spec://ai.lev/fpf-eng-me/contract/ME-14#root
