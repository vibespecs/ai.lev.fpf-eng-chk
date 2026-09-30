# Sources and dependencies {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Checklist Principles Framework* (2026-09-29), `Engineering DPF Suite/CHECKLIST-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. A section of the publication that is not a pattern. See LICENSE.md for the list of changes.

## Source contributions and their limits {#source-contributions-and-their-limits}

These sources inform the Methods in different ways. The historical and conceptual sources support problem recognition and synthesis. Empirical studies and engineering accounts support their stated observations under their own conditions.

| Source and return | Contribution used here | Limit and reconsideration condition |
| --- | --- | --- |
| R7, Methodology, connected checklist passages in chapter 6 and their Method, qualification and change context | Questions about work subjects; reusable templates and filled instances; local adaptation; timing, assistance, skill, motivation and worth. | Translate the ideas under current FPF rather than importing meta-level or alpha terminology. Revisit the affected Method if a source distinction lost in translation changes use. |
| R10, Systems Management, connected operational model, shared-state and administration passages | Local interpretation, shared views, coordination and change in work involving several participants. | A shared representation does not establish performed work or the state of every subject. Revisit CHK.5 when the work arrangement changes. |
| Atul Gawande, *The Checklist Manifesto* (2009; 2010 UK edition), especially the professional-reminder, team-interaction and design/trial cases | Historical practitioner account of selecting attention and arranging real use. | Domain cases and suggested design heuristics do not establish universal list length, timing or causal effect. |
| [Urbach et al., 2014][URBACH] | A population-level implementation result constraining easy effectiveness claims. | Its before/after setting does not show that every checklist is ineffective. Seek domain-specific evidence when making an outcome claim. |
| [Facey et al., 2024][FACEY] | Mechanisms by which documentation can diverge from observed checklist practice. | One institutional setting does not establish prevalence elsewhere. Inspect the actual local arrangement. |
| [RLCF, version 2, December 2025][RLCF] | Criteria and checklist feedback in model training. | Training/benchmark results do not establish a deployed checker or current subject state. |
| [Selective Checklist Evaluation, EMNLP 2025][SELECTIVE] | Criterion-selection policy and evaluation setting can change judgement results. | No universal selection policy follows; agreement with judgements is not direct truth. |
| [AutoChecklist, version 1, March 2026][AUTOCHECKLIST] | Explicit generation, refinement and use of criteria for evaluation. | Reported experiments provide bounded support; local workflow and domain coverage still need examination. |
| [Anthropic, effective harnesses, November 2025][ANTHROPIC1]; [harness design, March 2026][ANTHROPIC2] | Observable completion checks, continuation across sessions and adaptation of evaluation means. | Engineering accounts depend on available models, tools and tasks. Reconsider the arrangement as those change. |
| [CheckPOINT, 2024](https://pubmed.ncbi.nlm.nih.gov/37734956/); [Ridgeway et al., 2026](https://doi.org/10.1016/j.pecinn.2026.100495) | Observing interaction and distinguishing aid implementation from the practice supported. | Instrument performance does not establish outcome benefit. CHK.3 tests the intended interaction. |
| [Hölzing et al., 2026](https://doi.org/10.3390/clinpract16040069) | Simulation evidence distinguishes overall team behaviour from particular subscales. | The cohort overlaps an earlier technical-performance report; no independent clinical replication follows. |
| [Chen et al., 2023](https://doi.org/10.1016/j.ergon.2023.103453) | Content and position cues for resuming interrupted work. | Student laboratory tasks limit transfer. Test the content needed for CHK.4's actual continuation. |
| [Hong et al., July 2026](https://arxiv.org/html/2607.12835v1) | Coverage, granularity and uneven emphasis in generated rubrics. | A paper-reproduction benchmark and model-based evaluation support bounded comparison, not universal criteria. |
| [CHERRL, June 2026](https://arxiv.org/html/2606.04923v1); [Rubric Dropout, August 2026](https://arxiv.org/html/2608.11669v1) | Investigating exploitation of judge biases and divergence between optimized scores and intended results. | Experimental preprints; CHK.6 checks the receiving use. Training interventions do not prescribe ordinary omitted checks. |
| [SPECA, February 2026](https://arxiv.org/html/2602.07513v1) | Transferring source-derived questions across implementations. | Its single audit and specification assumptions limit transfer. CHK.1 re-establishes applicability and grounds. |
| [Bagaria et al., August 2026](https://arxiv.org/html/2609.02942v1); [RIPD, February 2026](https://arxiv.org/html/2602.13576v1) | Sensitivity to question meaning and limits of benchmark validation after rubric edits. | Bounded preprints motivate CHK.6 contrasts, not universal failure rates. |
| [RuVerBench v2, September 2026](https://arxiv.org/html/2606.29920v2); [PReMISE v1, May 2026](https://arxiv.org/html/2605.30803v1) | Qualification of the actual judging arrangement in CHK.6. | Their benchmark and model-mediated results do not establish a universal grouping or voting rule. |

The useful synthesis is a short question set with recoverable meaning, an actual occasion and suitable grounds. A checklist does not supply all professional knowledge, prove that its described characteristics are useful, or establish a whole result merely through constituent passes.

## Relied-on framework content {#relied-on-framework-content}

The Checklist edition relies on the following content for the receiving uses stated here. The direct pattern links identify the supplying text.

| Supplier | Content used and receiving use | Change that reopens reliance |
| --- | --- | --- |
| Current FPF: [E.10.D2][E10D2], [A.3.1][A31], [A.3.2][A32], [A.6.P.RI][A6PRI] | Subject/description/use separation, Method/MethodDescription distinction and recovery of participant-relative references in the six Methods. | A changed distinction defeats the interpretation of questions, templates or performed work. |
| Current FPF: [A.3.3][A33], [A.3.4][A34], [A.22][A22] | Transformation and state-structure distinctions in the Preface and change examples. | A changed governing claim alters what a described state or transformation relation means. |
| Current FPF: [B.1.5][B15], [A.15.10][A1510], [A.15.11][A1511] | Constituent/encompassing Method use, changed premises and noticing applicable Methods in CHK.1, CHK.3–5. | A changed relation alters the local-to-whole inference, recovery or support arrangement. |
| Current FPF: [A.19.ULSAM][ULSAM] | Admitted measures and lawful aggregation when CHK.6 examines a numerical total. | Changed measures, inclusion or aggregation meaning defeat the numerical inference. Separate answers need no aggregate. |
| Method Engineering: [ME.3][ME3], [ME.8][ME8], [ME.10][ME10], [ME.11][ME11], [ME.14][ME14], [ME.16][ME16] | Criterion construction, Method description, enactment arrangement, representative trial, worth and improvement. | A changed supplier result makes the corresponding Checklist action or return unsound. ME.3's generic requirement wording is not imported as deontic force. |
| Operations Management: [OPS.3][OPS3], [OPS.4][OPS4], [OPS.6][OPS6], [OPS.18][OPS18] | Operating-subject distinctions, shared operating state, case continuation and quality/reliability control used in CHK.3–5. | Changed work or record semantics defeats combined use or recovery. |
| Organization Administration: [ADM.7][ADM7], [ADM.13][ADM13] | Claim-checking and fit-for-use record distinctions, adapted from administrative practice in CHK.4–6. Administrative authority or institutional rules apply only where independently relevant. | A changed checking or coordination relation alters the supplied result. |
| Human Capability Development: [HCD.3][HCD3]; Organization Change Engineering: [OCE.6][OCE6], [OCE.10][OCE10] | Capability analysis and organizational introduction when CHK.3 reveals those needs. | The identified capability or introduction arrangement no longer serves the intended work. |
| Explanation Design: [EXD.1][EXD1], [EXD.6][EXD6] | Recovering the explanatory question and comparing repairs to checklist meaning. | Recipients cannot recover a consequential distinction through the supplied explanation. |
| The particular work domain | Descriptions, usefulness assumptions, competent judgements and observations; separately applicable legislative requirements where relevant. | Changed domain evidence, purpose, subject or applicable law changes the criterion or receiving action. |

This edition uses the supplying text identified in its first-edition source basis. A later date or a working hyperlink does not establish semantic compatibility. Before reusing an answer affected by a supplier change, compare the actual changed content with its named receiving use. Unaffected Methods remain usable.

## Refresh and improvement {#refresh-and-improvement}

Return first to the smallest affected contribution. A missed consequential question reopens CHK.1; lost meaning reopens CHK.2; unusable timing or access reopens CHK.3; unsupported subject answers reopen CHK.4; broken shared reliance reopens CHK.5; an inadequate criterion or checker reopens CHK.6.

Repeated non-use, prefilled answers, interpretation errors, burdens shifted to others and weak whole-result inferences can reveal defects in the aid or its arrangement. Use representative work and worth appraisal before expanding it. A changed source, model, tool or framework supplier reopens the dependent claim, not automatically the entire edition. Distinguish a changed way of working from a new release of its supporting tool: newer software does not by itself make the criterion or underlying Method better. Compare actual alternatives and their conditions of use. A new independently useful Method or a materially different human/AI practice boundary can justify reconsidering the framework's scope.

[URBACH]: https://www.nejm.org/doi/abs/10.1056/NEJMsa1308261
[FACEY]: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0298224
[RLCF]: https://arxiv.org/html/2507.18624v2
[SELECTIVE]: https://aclanthology.org/2025.emnlp-main.538/
[AUTOCHECKLIST]: https://arxiv.org/html/2603.07019v1
[ANTHROPIC1]: https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents
[ANTHROPIC2]: https://www.anthropic.com/engineering/harness-design-long-running-apps
[E10D2]: spec://ai.lev/fpf-spec/contract/E-10-D2#root
[A31]: spec://ai.lev/fpf-spec/contract/A-3-1#root
[A32]: spec://ai.lev/fpf-spec/contract/A-3-2#root
[A6PRI]: spec://ai.lev/fpf-spec/contract/A-6-P-RI#root
[A33]: spec://ai.lev/fpf-spec/contract/A-3-3#root
[A34]: spec://ai.lev/fpf-spec/contract/A-3-4#root
[A22]: spec://ai.lev/fpf-spec/contract/A-22#root
[B15]: spec://ai.lev/fpf-spec/contract/B-1-5#root
[A1510]: spec://ai.lev/fpf-spec/contract/A-15-10#root
[A1511]: spec://ai.lev/fpf-spec/contract/A-15-11#root
[ULSAM]: spec://ai.lev/fpf-spec/contract/A-19-ULSAM#root
[ME3]: spec://ai.lev/fpf-eng-me/contract/ME-3#root
[ME8]: spec://ai.lev/fpf-eng-me/contract/ME-8#root
[ME10]: spec://ai.lev/fpf-eng-me/contract/ME-10#root
[ME11]: spec://ai.lev/fpf-eng-me/contract/ME-11#root
[ME14]: spec://ai.lev/fpf-eng-me/contract/ME-14#root
[ME16]: spec://ai.lev/fpf-eng-me/contract/ME-16#root
[OPS3]: spec://ai.lev/fpf-eng-ops/contract/OPS-3#root
[OPS4]: spec://ai.lev/fpf-eng-ops/contract/OPS-4#root
[OPS6]: spec://ai.lev/fpf-eng-ops/contract/OPS-6#root
[OPS18]: spec://ai.lev/fpf-eng-ops/contract/OPS-18#root
[ADM7]: spec://ai.lev/fpf-eng-adm/contract/ADM-7#root
[ADM13]: spec://ai.lev/fpf-eng-adm/contract/ADM-13#root
[HCD3]: spec://ai.lev/fpf-eng-hcd/contract/HCD-3#root
[OCE6]: spec://ai.lev/fpf-eng-oce/contract/OCE-6#root
[OCE10]: spec://ai.lev/fpf-eng-oce/contract/OCE-10#root
[EXD1]: spec://ai.lev/fpf-eng-exd/contract/EXD-1#root
[EXD6]: spec://ai.lev/fpf-eng-exd/contract/EXD-6#root
