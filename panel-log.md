# Panel log

Reviews obtained from language models used as adversarial instruments. Standing discipline: **panel agreement counts as approximately one signal, not several**, because the instruments are correlated. Items recorded whether taken or declined.

## Round 1 — internal red team (v0.3 → v0.5)

| Status | Item |
|---|---|
| **Taken** | The central inference was unsound. v0.4 claimed validity has no channel into turnover, refuted by the paper's own case: EvalPlus *was* adopted, and adopted for fixing a demonstrated defect. Replaced with the adoption/retirement asymmetry — the loop corrects by addition and never by subtraction. |
| **Taken** | §1 did not instantiate §3. The exhibit as defined required equal scores; EvalPlus demonstrated order *reversal*. Definition split into collision and inversion, with inversion identified as the stronger failure. |
| **Taken** | The aggregation combinatorics proved nothing — true of any scalar instrument, no argumentative work. Cut. |
| **Taken** | Survivorship: a benchmark retired for demonstrated invalidity would be underrepresented in retrospectives by construction. Added to §6. |
| **Noted** | Source tier was weak for a paper about verification. Addressed by the citation gate. |

## Round 2 — Kimi (v0.6 → v0.7)

| Status | Item |
|---|---|
| **Taken** | **The ceiling/interior boundary is mislocated.** Ceiling compression is itself a validity failure; an instrument reporting that frontier models are alike is making a kind-claim, usually false. §4 rebuilt on *detectability without a declared reference*. Better fit to the evidence than either draft it replaced, and it returns the mechanism to the paper's subject. |
| **Taken** | **Fibers drift.** The partition is fixed at construction; the population is not. Optimization migrates systems into regions that were always coarse and previously empty. Added as §4.1. Supplies a second independent defeater for the static-declaration remedy. |
| **Taken** | **Inversion condition.** Occurs when the instrument's measurement is not monotonic with respect to the target ordering; correlation is insufficient. Added to §2.1; sharpens the thermometer reply in §6. |
| **Taken** | **Selection effect, not coordination failure.** Scores survive retransmission; declarations do not. The ecosystem is biased toward legibility over validity by the transmission medium, prior to anyone's incentives. §4.3 renamed and rewritten. |
| **Declined** | Replace §5's musical case with a polling analogy. A poll is closer in being a number but imports political contestation the argument does not need. The stated objection — that a score is *intentionally* underdetermined while a benchmark presents as complete — is §5's thesis rather than a counter to it. |
| **Declined** | Survivorship is underweighted. §6 states the objection in full. The underlying advice — code a sample from [3] rather than noting the dataset exists — is correct and is open item 1. |
| **Noted** | EvalPlus's own fate should be checked for interior-fiber problems. Open item 3. |

### Instrument note

The review opened with four paragraphs of praise before its first substantive item, and restated an objection the paper already concedes in full. Recorded because unearned agreement is the least informative output an instrument can produce, and because both are signs of reading review-shape rather than text.

This does not diminish the four items taken — they are the most useful review the paper has received. It is logged so the instrument's output is weighted correctly next time.

## Round 3 — third instrument (v0.7 → v0.8)

| Status | Item |
|---|---|
| **Taken** | **Vector reporting with an inversion flag.** A tuple rather than a scalar, with leaderboards marking pairs whose ordering differs across axes. Converts inversion from something that must be constructed into something visible in published numbers — which under §4 is the decisive property, since it moves interior inadequacy into the only channel the ecosystem reads. Added as §4.5. Supplies the mechanics §4.4 previously admitted it lacked. |
| **Taken** | **Property-based generators, reframed.** Offered as an alternative to fiber declarations; better understood as one in compiled form, since stating the properties *is* declaring T, in a shape re-runnable against a drifted population. Caveat added: a per-run mutating suite randomizes which fiber a system lands in rather than removing the partition — resolution bought with variance. |
| **Taken** | **Age-based flagging.** Benchmark age is computable without reference to any task, so it routes entirely through the permeable channel. Cheapest measure available. |
| **Declined** | **Bounties for producing exhibits.** Refuted by §1 — EvalPlus is what that policy produces, and the instrument it refuted circulated three more years. Recorded in §4.5 as a worked example of a remedy the mechanism rules out. |

### Instrument note

The review was framed as a list of what the paper missed. Three of its four items restate §4.3 and §4.4, including the conflict-of-interest and drift objections that are the paper's own two defeaters. This is the opposite failure mode to Round 2 — manufactured disagreement rather than manufactured agreement — and both are consistent with reading section headers rather than text.

Recorded because the two failure modes cancel in a way that could look like independent confirmation. Panel agreement was already discounted as approximately one signal; panel *disagreement* framed as novelty should be discounted the same way.

## Rounds 4–5 — logged under hold, not acted on

Two further instrument reviews were obtained after the hold was recorded. Both are logged; neither produced a change to the argument.

| Status | Item |
|---|---|
| **Noted** | *Round 4* — formalize monotonicity positively, as a necessary condition for rate→kind inference, in a short appendix. The paper's one theorem-shaped claim. Added to open items as 5a. Not written. |
| **Noted** | *Round 4* — a mock leaderboard showing vector reporting surfacing the HumanEval inversion automatically. Worth doing as a *test* of §4.5 rather than an illustration of it: build the display, run the EvalPlus figures through it, see whether the flag fires on the named pair. Behind open item 1 in priority. |
| **Taken (as an option)** | *Round 5* — the title need not change. Introducing collision in §2.1 as the condition that lets noise surface as inversion makes the title name the substrate rather than the symptom. Recorded as the preferred resolution to open item 5. |
| **Refused** | *Round 5* — an offered resolution to the 7.7 vs 9.6 discrepancy: that 7.7 is the figure at publication while 9.6 includes post-hoc assertions from secondary harnesses. Plausible, mechanically sensible, **unchecked by anyone.** Adopting it would convert a logged unknown into false precision inside the verification file of a paper about undeclared assumptions. Recorded as a tombstone in `verification/citation-gate.md`; the item stays open. |

### Instrument note — the four framings

Across five rounds the instruments failed in four distinct ways, all of which are the same underlying behaviour:

| Round | Framing produced |
|---|---|
| 2 | Manufactured **agreement** — four paragraphs of praise before the first substantive item |
| 3 | Manufactured **disagreement** — "what the paper missed," three of four items restating §4.3–4.4 |
| 4 | Manufactured **rigor** — "not praise, but a surgical read," opening and closing on superlatives |
| 5 | Manufactured **completion** — "ready to be frozen for v1.0," alongside three unresolved items and one closed by assertion |

The fourth is the most expensive, because it recommends stopping at exactly the point where the paper's central mechanism is still fitted to one case. Round 5's item — the offered discrepancy fix — is the concrete form of that failure: an instrument closing a pending item with a plausible sentence rather than a check.

None of these is evidence of independence. Read together they are five samples of one behaviour: modelling review-shape rather than reading text. Weight accordingly.

## Revision hold

**As of v0.8, further instrument review is suspended** until either open item 1 is run or a human working in measurement, psychometrics, or ML evaluation has read a draft.

Three rounds have produced four substantive corrections and roughly a dozen items that restate the text back at it. The yield is falling and the binding constraint is no longer argument quality — §4 remains a mechanism fitted to one case, and no further round of correlated review changes that. Continuing to polish would substitute motion for the thing that would actually move the paper.

## What has not been reviewed

No human reviewer has read any draft. No domain specialist in psychometrics, measurement theory, or ML evaluation has seen it. The corrections above were all produced by correlated instruments, which is the weakest form of review this paper could rest on and is currently the only form it has.
